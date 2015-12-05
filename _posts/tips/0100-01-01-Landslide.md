---
tipid: Landslides
title: Landslides and Road Blocks
category: tip
layout: tip-preview
images:
  - https://raw.githubusercontent.com/hotosm/tracing-guides/gh-pages/images/Landslide_Before.JPG
  - https://raw.githubusercontent.com/hotosm/tracing-guides/gh-pages/images/Landslide_Tag.JPG
  - https://raw.githubusercontent.com/hotosm/tracing-guides/gh-pages/images/RoadBlock_Tag.JPG
  - https://raw.githubusercontent.com/hotosm/tracing-guides/gh-pages/images/Debris_Tag.JPG
tags: [Nepal, Earthquake, Landslide]
---
Area feature

Objects to map:  

- landslide cones (area covering the entire landslide, use hazard_type=landslide)  
- landslide locations (node, point within the landslide cone area, use hazard_type=landslide)  
- road blocks caused by landslide debris (node, use barrier=debris)  
- roads damaged or blocked by landslides (way, use smoothness=impassable)  


**Landslides (node or area)**  
hazard_type=landslide  
source:date=add date of imagery per task  
source=add appropriate source per task  
damage:event=nepal_earthquake_2015  

**Blocked/damaged roads (way)**  
highway=*  
smoothness=impassable  
source:date=add date of imagery per task  
source=add appropriate source per task  
damage:event=nepal_earthquake_2015  

**Road blocks (node)**  
barrier=debris  
source:date=add date of imagery per task  
source=add appropriate source per task  
damage:event=nepal_earthquake_2015  

