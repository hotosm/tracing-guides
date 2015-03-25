---
tipid: validating-volcano
title: Validating Grids
category: tip
images:
  - https://cloud.githubusercontent.com/assets/9657971/6358094/324d4c5a-bc37-11e4-808a-47a0fdb59700.png
  - https://cloud.githubusercontent.com/assets/9657971/6359769/5e94f216-bc43-11e4-8bf3-11fa9306acae.gif
  - https://cloud.githubusercontent.com/assets/9657971/6359733/31396b30-bc43-11e4-8780-c661dfc96d7c.png
tags: [Karangetang, Validation, Tasking Manager]
---

OSM is constantly changing and no matter how filled out an area on the map is it is never done. The impression that validating a grid will mean that it will never be revisited leads many to feel intimidated by it. Anyone can validate! Just remember, *do not validate your own work*. 

Validating a grid means that everything that needs to be done to meet the goals of the task you are working on. If the task is to map every type of feature possible and provide attributes this may be very complex and may require field verification but if the goal is to map basic features in a sparsly populated area this process is fairly straight forward.

###Initial Scan
Have an initial quick scan around to see if you will be continuing or will be invalidating the square. If it is obvious that major improvements need to be made, click on the 'invalidate' button on the tasking manager & add a comment explaining what needs to be done. The most frequent problem is a simple one that anyone can make, and the square has somehow been marked as complete, when it is obvious that the whole or majority of the square is still to be mapped – this type of error does not really need a message to the mapper, and may even be a software glitch (That's what we all claim). Do not invalidate a square for something that is not a requirement of the task.

###Buildings
Now check if buildings are missing. If there are a large number missing, the grid can be invalidated. If it's only a few then it's simpler to add them as you check around.
Are the buildings correctly traced. Sometimes mappers do not trace buildings accurately & if significant this needs correcting. You may find that a group of buildings looks like they match the shape of roofs but are displaced from where the building is in the imagery, this often happens when OSM has been traced based on imagery that has been misaligned. For the purposes of this task - unless the alignment is aggregious - leave the buildings if you suspect displacement is due to an imagery issue.

###Highways
* *Highway tags are correct? Some mappers tag every highway as a track because they are not paved, but this is not a meaningful criteria in these developing countries considering 99% of roads are unpaved. Check the wiki definitions, perhaps the Highway_Tag_Africa is relevant & you should research there before going any further.
Road geometry. 
* *Road Geometry. Some mappers do not put enough details and others too much (eg a node every 10 or 20 m even if the road is straight).  Deleting extra nodes if they actually make a straight road weave.
* *Start/end of roads. Some mappers produce long winding ways which meander through several junctions. Click on the 'way' and break it into more obvious parts, probably at junctions or changes in the tagging. Some other streets or roads are broken up without any reason (same tags for all the sections), and need to be combined.

