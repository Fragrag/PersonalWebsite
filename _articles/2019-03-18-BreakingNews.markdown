---
layout: article
title: Breaking News
description: A post mortem of a failed game
tech: (Unreal Engine 4, Substance Designer, Game Design)
date: 2019-03-18 18:00:00
---

In the early months of 2018, a user posted a thread on the Unreal Engine reddit including a video of a high speed car chase. He proposed the idea of creating a small game that would recreate the experience and quickly collected a group of volunteer game developers, including myself. As is typical of such projects, it quickly fizzled out after a brief bout of drama and development was halted. A bit over a year later, I decided to visit this project again. This report won't focus on the drama, but will document my own processes and contributions, which has remained buried up to now but does include some achievements that I am rather proud of and would like to share.

![alt text]({{ site.baseurl }}/img/articles/breakingnews/chaser_Groundwork.png){: .projectimage}

# The Getaway

When I joined the project's Slack, the team was still assembling. At that moment, there were roughly eight people who were active in the chat but many were still uncertain what to do. After introducing myself and noticing that no one was actively working on the 3D side of the project yet, I took it upon myself to start laying down some foundations. It quickly became apparent I was one of the more experienced 3D artists and I became the team's lead artist. 

I started by researching the video. I quickly found out it was in the city of Tempe, Arizona. I even managed to pin down the exact stretch of road. The environment was typical of North American cities, with long straight boulevards and intersections at regular intervals. This gave me the idea of creating levels in a procedural manner with modular assets. I quickly sketched my idea in Photoshop illustrating the basic building blocks of a level. I had the idea of two types of road to start with: wide boulevards and narrow streets. This would already add a gameplay element where the player would have to look at the road ahead and adjust accordingly. The road themselves would be constructed of segments that would interlock with each other, allowing for varying lengths of straights. Using Google Maps I then took a screenshot of the boulevard where the event took place and took its rough measurements which would serve as my reference for the scale of the city.

![alt text]({{ site.baseurl }}/img/articles/breakingnews/chaser_roadMaterials.png){: .projectimage}

# The Chase

Armed with this information I created the first rudimentary 3D models. Once loaded into the UE4 project, I could tell that it was working as well as I had hoped and it was a matter of creating a simple Blueprint to generate the levels.

Afterwards I focused on the materials for the road assets and gauged the approach for it. I quickly made a road asphalt material which I found a bit monotonous. So a variant with cracks was added. For the road markings I quickly found out that with my method each type of road segment required a bespoke layout of street markings.

All of these elements were then combined in Unreal Engine. I first created a base material in which the two asphalt types were masked with a noise map to alleviate the tiling and repetitiveness. From this base material a material instance could be created for each road segment. In the base material were texture parameters, in which the maps for the road markings could be implemented in for the appropriate road segment. 

Naturally at this early stage of development, these implementations were still very rudimentary. I took care to make sure that making adjustments further down the road would be as painless as possible and creating variants wouldn't be difficult. Once the skeleton of the game had been established, we could move on to the next stage, expand and improve.

Once these assets were implemented into the project, working properly and received the approval of the other team members, I tasked the other 3D artists with creating smaller assets such as traffic lights, street lights and other smaller details with the instructions to look at Tempe so that our urban environment would remain consistent and coherent. I then proceeded on to creating building meshes that would populate the city blocks. While taking a digital stroll through the streets, I took note of the types of businesses and buildings you were likely to encounter. The types that would be developed first would have to be immediately recognisable, have different sizes and have a varied placement in the city (e.g. a gas station was more likely to be at an intersection than anywhere else). I settled on three to start with: a fast food restaurant, a gas station and a strip mall. I proceeded on creating preliminary versions of these buildings and implementing them.

![alt text]({{ site.baseurl }}/img/articles/breakingnews/chaser_IngameMaterials.png){: .projectimage}


# The Crash

Development lasted only three weeks before it imploded. I wasn't surprised that it did. That's how these open projects generally go. It was still a disappointment that it did not at least reach a more presentable stage but that's how it is. I am happy that I was able to dip my toes in a game development role, testing the waters and getting a feel of what is required. As the lead 3D artist I wasn't only expected to create assets, but to choose the visual theme, establish the workflow and lay down the pipeline. I communicated with other members of the team on requirements, shared my ideas with them and listened to their feedback. I requested features to the others and I kept myself up to date on their progress. 

In the end, it had become evident that after the initial enthousiasm, fewer people were remaining involved. Eventually most of the work was being done by me and a programmer, with another 3D artist contributing smaller items. The project lead, who posted the original thread, was still enthousiastic but he did not possess the skills that we needed at that point so he was relegated to proposing ideas and checking up on us. Unfortunately, when one of his proposals was shut down, he became irate and left the Slack channel, never to be heard from again. At that point, me and the programmer saw the writing on the wall. We stopped what we were doing, pushed our last revisions and signed off.
