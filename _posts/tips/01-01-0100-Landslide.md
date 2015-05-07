---
tipid: Landslides
title: Landslides and Road Blocks
category: tip
images:
  - https://github.com/hotosm/tracing-guides/blob/gh-pages/images/Landslide_Before.JPG
  - https://github.com/hotosm/tracing-guides/blob/gh-pages/images/Landslide_After.JPG
  - https://github.com/hotosm/tracing-guides/blob/gh-pages/images/Landslide_Tag.JPG
  - https://github.com/hotosm/tracing-guides/blob/gh-pages/images/RoadBlock_Tag.JPG
  - https://github.com/hotosm/tracing-guides/blob/gh-pages/images/Debris_Tag.JPG
tags: [Nepal, Earthquake, Landslide]
---
Area feature

The goal is to map earthquake induced landslides and roads blocked by debris or damaged. Please compare with any previous background imagery available to make sure the landslide occurred recently and possibly induced by the 2015 earthquake.

Objects to map:  

- landslide cones (area covering the entire landslide, use hazard_type=landslide)  
- landslide locations (node, point within the landslide cone area, use hazard_type=landslide)  
- road blocks caused by landslide debris (node, use barrier=debris)  
- roads damaged or blocked by landslides (way, use smoothness=impassable)  


*Landslides (node or area)*  
hazard_type=landslide  
source:date=add date of imagery per task  
source=add appropriate source per task  
damage:event=nepal_earthquake_2015  

*Blocked/damaged roads (way)*  
highway=*  
smoothness=impassable  
source:date=add date of imagery per task  
source=add appropriate source per task  
damage:event=nepal_earthquake_2015  

*Road blocks (node)*
barrier=debris  
source:date=add date of imagery per task  
source=add appropriate source per task  
damage:event=nepal_earthquake_2015  

