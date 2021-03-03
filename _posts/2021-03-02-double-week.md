---
layout: default
title:  "Double Week"
---

<h1>Double Week</h1>

<h2>March 2, 2021</h2>

A decent chunk of my time the past two weeks was sucked away on prepatory stuff. I spent an hour playing <i>Sagebrush</i> to prepare for an upcoming meeting with Nate Berens of Redact Games, which sadly hasn't happened quite yet. I also spent some time putting together my questions and information for all of my upcoming interviews, some of which went out in the form of an email interview to Scott Brodie of Heart Shaped Games. I was also fortunate enough to speak with a contact of mine at Ubisoft - Jeff currently works as a recruiter but also has experience and an interest in the narrative side of game dev. 

I also spent some time exploring some of the ways AI is used in some AAA survival-style games, including the AI Director in <i>Left 4 Dead</i>, which is most similar to what I'm hoping to accomplish.

Another chunk of time was lost down the rabbit hole of asset searching. I was on the lookout for simple but engaging assets for my map, characters, and items. 

Next, I got into setting up my "playground" - that is, the basic survival game that I will use for my future AI experiments. I started out by setting up my Unity project and creating pretty simple main menu, where I will be able to add settings options for later experimentation and exploration.

![Basic Menu](/assets/BasicMenu.png)

The bulk of my development time for the past few weeks has been in the setting up of the game itself. I created a map with some simple items, and started working on the player characters. The game focuses on a "base" in the center of the map, which the player will defend and improve by collecting items and fighting zombies. I initially started out with a more Rimworld-style game, where the player congrols multiple characters, but soon realized I bit off more than I could chew for the purposes of experimentation. I'll be continuing to develop and tweak the game alongside the AI work for the remainder of the semester.

![Tilemap](/assets/tilemap.png)
<small>Baby's First Tilemap</small>

In addition to working on the game itself, I worked on the remainder of my brainstorming necessary to get into the meat of my actual AI work. Some of this time was spent simply planning for the "playground" game itself, both in the design/functionality of the game, and how it will interact with the narrative-generating aspects I plan to integrate. Part of this process included coming up with a solid list of events to use along the way, which admittedly probably includes more elements than I will have time to include. I plan to start by implementing one negative and one positive event to use for the basics of the AI work. (I intend for those first events to be zombie attacks and loot drops.)

![Possible Event Ideas](/assets/EventIdeas.png)

I also spent some time working with my concept of the "story graphs" and had a bit of an epiphany. Rather than going through the trouble of creating a collection of graphs that the AI can select from, the AI itself should generate the graphs. That way each narrative experience is unique at its core. (Honestly, I'm not sure why I didn't think of this sooner - I had to scrap a bit of previous work done in creating my own graphs to be used.) I also worked on coming up with the best way to actually represent these graphs in code, and ultimately decided that the simplest way is probably the best way: numbers - most likely as <i>lists</i> of numbers representing the peaks and valleys. Since the values inbetween the peaks don't really matter to the AI, we only need the values of those highs and lows that we want the player to reach, which is much easier to generate and keep track of then a full graph to aim for. To keep it really simple, I plan to make this a capped scale of 0 to 100, but I predict that when scaling up this project, it'd probably be easiest not to cap the tension scale, so the game can continue to build with no end. 

Next week, I'm hoping to have code written to generate these "graphs." I also want to start developing a system to measure the player's "tension," or how well they are doing in the game, in order to help the AI determine which events to pursue. And of course, with my extra time, I will continue developing my "playground" game, particularly setting up the zombie characters and combat in order to test out the future AI choices.›

I've finally reached a comfortable point in my researching and planning that I expect to finally focus my time on actual experimentation, and I'm excited to see how it turns out!