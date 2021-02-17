---
layout: default
title:  "First Full Week"
---

<h1>Planning and Prepping</h1>

<h2>February 16, 2021</h2>

This week was a slightly less technical one than last week, made up of a lot of brainstorming and planning. Next week, I am hoping to get started on the basics of the survival game that I can use as the "playground" for my AI storybuilding endeavors. I wanted to be sure to have a solid plan before getting started so that I wouldn't have to waste too much time getting the details of the game right, because the story building is my real priority. Ultimately I'm faced with the challenge of creating a game that is engaging enough to properly showcase my AI storytelling advancements while also being simple enough that it won't take up too much of my development time and effort. I've decided I want to make as generic a survival game as possible, while also leaving it open to further development beyond this semester.

I also did quite a bit of brainstorming as to my approach for getting started on my AI developments. Last week I determined that I would use a "morale" system to keep track of a player's success in order to make decisions about what events to throw their way next. I think to start it'll be easiest to make this a simple, numerical-based system, where the player gets positive or negative "morale points" based on how they are doing in the game. That way the challenge will be how to recognize those moments rather than how to represent or measure them.

This week, I thought a lot more about how to use that system to actual make decisions about events. Using what I learned last week from reading <a href="https://www.jessicabrody.com/books/non-fiction/save-cat-writes-novel/about/">Save the Cat</a>, I started to think about this graphically. I want to focus on the "Rising Action" portion of storytelling, since we're using the video game format rather than a novel, and the building to the climax often lasts a lot longer (or shorter, if the player loses quickly). To visualize this, I have the following graph, which represents the "highs and lows" of a story (or of the player/character's experience).

![Graph of Story Tension](/assets/novel-graph.jpg)

As the game progresses, the player will reach more of those hills (or "crises") that make up the action, where the high and low points can vary over time. By having a graph such as this one prepared, the computer could choose from available events in order to "follow the curve," providing some guidance of what the story should be shaped like rather than just throwing random events at a player. The computer could keep throwing challenges at a player until they reach a low enough point, for example, before giving them some relief and time to prepare for the next "crisis." By having a collection of different graphs with different shapes, plus different events chosen by the computer for the different peaks, ths could allow for entirely unique playing experiences. (For further development on this project, this view would also make it easier to enable differing levels of difficulty, where the "hills" are more or less spaced out, and reach higher or lower peaks.)

I started to sketch out a few examples of what these "graphs" could look like and the kinds of variety that they could have. For next week, I'm hoping to come up with the best way to represent these graphs programmatically so that they can be easily read and followed by the AI. 

I also worked on putting together a list of some of the potential events for the survival game, such as fires, zombie hordes, and sickness. It's an interesting challenge to keep the list relatively small while also being diverse enough to create an interesting environment for the AI to work with.

I did do a bit of technical exploration, however, by looking at some <a href ="https://github.com/topics/game-ai?l=c%23">current open source projects</a> related to games and AI. I did this partially to explore some of the code that is available out there, to see what kinds of tools and tactics others are using in the field, but also to potentially find AI tools that could assist in my own project. For example, <a href="https://github.com/shaunwhyte/GOAP/blob/master/README.md">Goal Oriented Action planning</a>, which is Unity compatible, is an open source project for AI agents within a game. My hope is that GOAP, and other projects like it, will help me to build a base survival game more quickly and easaily so that I can focus on the storytelling AI aspect of my own project rather than getting bogged down in all of the moving parts.
