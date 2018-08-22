---
layout: article
title: Creating Blueberry Garden
image: CreatingBlueberryGarden.jpg
color: '#3BF'
tags: [article]
---

[This article was first published by Gamasutra in 2010.](https://www.gamasutra.com/view/feature/132710/creating_blueberry_garden.php)

I was a bit reluctant to write this text at first, since I don't think I'm the best person to pick my own game apart. I'm a creator, and not a game critic, and obviously what I'm going to write about lies too close to my heart for me to really see it clearly.

Initially I was going to write a regular Gamasutra postmortem, which would have solved the problem to some extent. I could have focused on obvious mistakes such as releasing a game with no saving functionality, ridiculously high system requirements, and extremely limited buying options in today's video game market.

I resisted this, though; it's not what I am interested in. I'm primarily a game designer, and since the rest of the world clearly has moved beyond my level of amateurishness I will just promise to do better in the future and move on to look at the more interesting points of my game.

When I set out to create the game, I almost completely looked at it as an experiment, or rather two experiments, combined into one whole. First of all, I really wanted to create a game where the underlying world was a working ecosystem. I imagined many creatures with different behaviors eating, mating, dying, etc. -- completely independent of the presence of the player.

Secondly I wanted to see what I could do with the idea of telling a story solely through interactivity, the "holy grail" of our art form. This would include not forcing the player to do anything she didn't want to do.

In other words, she would have total control over the actions of the player character. In my mind this meant to not use any cutscenes, descriptive texts, or triggered events -- all meaning of the story would have to emerge from the systems of the game (and these systems would have to be general). This would turn out to be a very difficult thing to do, indeed.

I started the actual production in early 2008 as a part of my final thesis at the bachelor degree Game Design program in Skövde that I went to at the time. As I worked along on my game and people got hold of the trailer and my working version, it became increasingly clear that I could not look at my work as completely academic or self-fulfilling. I realized that people would actually want to play my creation (and even pay money for it -- gasp!)

This of course presented me with some interesting problems, mainly concerning the length of the game. This text aims to look at these two main parts of the game (the ecosystem and the interactive storytelling) in separation to see how well they work on their own. After that I will discuss how they combine into a game and how they represent some possibilities for creating meaning through interaction.

## The ecosystem

The idea of having an ecosystem in a game is naturally nothing new. It has been done many times before and I should have taken a better look at existing examples to be better prepared for the daunting task I had set up for myself. The reason I wanted an ecosystem in the game in the first place was that it's one of the most interesting and easy to understand real-world systems with emergent properties.

For some reason it speaks to the human soul that we're just part of a greater circle of life. Also I wanted to beat Peter Molyneux by putting growing trees into games before he succeeded.

To make the ecosystem "real" I decided that it had to be simulated in all places simultaneously, without any difference if the camera of the player was there or not. This is something that I think many people that are new to video games take for granted, but gradually learn that "that's not how it works in games" and eventually come to terms with.

I wanted people to be able to bring real-world knowledge into the game and make use of it there. One could even say that my goal was to make the game easier for a person used to surviving in the woods than for an experienced gamer. Sadly (and predictably) this failed... I think I will try again someday.

To be able to build this kind of system I realized I needed elements like plants,seeds and creatures. This in turn made me understand that some kind of physics simulation was necessary; gravity had to pull the apples down from the trees, so tospeak. This is where things got messy:

## Problems of simulation

This article will not discuss programming, so suffice it to say that constantly simulating all the physics in a big, freely explorable world is not a great idea, especially not if someone is going to use the computer to play a platforming game at the same time. This was clearly one of the things where my academic interest and artistic vision was prioritized, with the players of the game paying the price. In a way, I think it was worth it though; it really is an area of computer games that needs exploration.

I have had some clever people giving me pointers on how the simulation could be simplified to make it more manageable. This could involve running a less accurate version of the physics in far off places in the world, for example.

I don't want the game to work that way though. For me, a huge part of the experience is knowing that everything is "for real." In Blueberry Garden the tree falls in the forest even if no one hears it. This might not be the route for the future of game design. Maybe you could even dismiss it as utterly meaningless. But now I've at least tried it and can go on with my life.




## Impossible puzzles

One problem with making things "realistic" in games is that it's usually not very fun,at least not in the immediate and happy-go-lucky way that we've somehow gotten used to over the years. A perfect example of that is the choice to make every action in the game world irreversible and permanent. This means that in my game, if you, for example, kill all the creatures of a certain kind, they will be extinguished (until you start over the game from the beginning).

It also means that if the player messes up a puzzle so that it can't be solved, there is no reset button. Even if you walk far away from the location everything will still be the same way when you come back. This seems to cause less problems than I thought it would, probably because there aren't that many actual puzzles in the game. Actually there are very few things that you really need to do -- a prerequisite for making a non-linear experience work.



## Underused puzzle potential

One interesting dilemma I was presented with early in the design process was how many puzzles and obstacles I really wanted to put into the game. Of course most video game players would expect a constant stream of challenges, something that was problematic in several ways:

First, I didn't want to make the landscape feel like it was designed by someone. It should feel as if it had evolved on its own through erosion, volcanos, etc. In early versions of the game I even wanted to simulate that whole process for a long period of time and then let the game take off from there.

Secondly, I didn't want to make a game that was about puzzles. I wanted to focus on storytelling and the experience of discovery. Puzzles draw attention to the designer, simply because they are designed. I wanted the players to forget about me.

This idea didn't last for long though; when I started building the game it quickly became clear to me that I had to design the environment down to its smallest detail. This turned out to be much more fun as I could try to subconsciously influence the player to do certain things: explore in different directions, perform interesting actions, etc.

At the time I read several texts talking about game design as architecture; shaping a space for people to explore. This had a profound effect on the way I worked and with time my role changed from scientist to hypnotist.

Instead of observing the player I tried to influence her to create a memorable and strong experience for herself, without even noticing that she was being led to do this. Instead of making the environment feel untouched I focused on creating the most well-thought out experience I could -- still without ever forcing the player to do anything.

## Interactive Storytelling

At the time I made the game I was kind of obsessed with the thought of the player as an actor, taking on the main role in the game and trying to make as great a performance as possible.

This is something that turned out somewhat fuzzy during development. Since it's not communicated to the player, I don't think a lot of people consciously played the game like an actor. Still I hope that it's actually part of what draws players in; the feeling of being allowed to create your own story as an effect of not being told what to do. I will now look at some
other things related to the interactive storytelling in my game.



## Tangibility and an even level of interaction

A big part of designing computer games is to decide what actions the player should be allowed to perform. From the verbs of text adventure games to different attacks for units in strategy games, the actions are crucial for shaping the experience.

For me, the most important thing while designing the actions in Blueberry Garden was to make them all feel natural and on the same level. By "level", I here refer to the complexity of different actions, such as for example walking forward, picking up a rock, or eating a blueberry. All of these actions are short, simple and easy to recognize.

It would have been against this philosophy to mix them up, with for example the possibility to bend your left middle finger (which is a very tiny action) or to build a house (which is a very complex action). I'm not sure this obsession with a minimal and well-put together toolset of actions is really good for the game, mainly because it severely limits the storytelling possibilities. I even had to add a special action to enable the most significant story event: turning off the faucet.

## Speech

Originally I had some plans for the player to meet other human-like characters in the game that he or she could interact with. Since I really wanted to make all actions in the game feel believable and of the same level of complexity, I eventually decided that I couldn't use speech between characters. This in turn influenced the design of the other beings in the world, since it had to feel natural that they didn't talk.

The obvious way to do this was to make them animals, so that's what I did. I initially had the idea to let the player interact in different non-verbal ways with the animals; for example by scaring them or giving them food to make them more friendly. Unfortunately a lot of this got cut out of the final design; the animals don't care that much about the player. This is a real shame and I hope to revisit these design concepts in the future.




## Story

Even though walking through my whimsical garden surely could have pleased some people solely through sensory pleasures such as music and visuals, I wanted to try to make the experience into something more memorable.

In my mind that meant that playing the game should at least remotely resemble a proper story. Of course my main problem was the restrictions I had put upon myself; no cutscenes, descriptive text, or triggered events -- arguably the most common ways to make people put together what is happening in a video game into something understandable and meaningful.



The first narrative element I had in the game was the tower that you build by finding building blocks scattered around the game world. This mechanic was what made up the core idea for the game, all the way from the beginning.

In its simplest form this is the story of someone growing or improving in some way -- a popular plot that seems to engage most humans. In a way it's exactly the same thing as characters leveling up in role playing games, only very much more tangible and wordless, since the actual output is a construction and not a number.

The tower, and its construction, was a given from the beginning. What I didn't know, though, was how to explain why the player wanted to build the tower. I figured that most people would want to build for a while just to be able to see more of the world (the higher the tower is, the more places you can reach by gliding from the top of it.) But after a certain time they would probably feel satisfied and lose interest.

I toyed around with different ideas; the first one was that you had fell down from the moon where you and your loved one lived; alas, you needed to build a tower to get up there again. Another one was about competing with another character in the world about who could build the highest tower.

At some point I got the idea of flooding the world, and was thrilled with how well that worked together with the tower building. A threat or an antagonist is part of most stories. This was the perfect chance to include one in mine!

It's worth noting how my restrictions on cutscenes and triggered events prevented me from telling the player about anything directly. All has to be deducted from the environment and how it changes -- something that doesn't work if the player isn't actually trying to analyze things.

This kind of storytelling by its very nature feels very vague, as we are all used to it actually involving "telling" (something that text and cutscenes do very well). To some extent this can be solved through a clearer and well-framed execution, but I also think that it's part of letting the player handle being the author. It might be a strange feeling, since no one is telling you if you're doing it right -- but that's just because there is no wrong!



## Putting it all together

It's evident that my two main areas of interest while making the game, the ecosystem and the interactive storytelling, overlap quite a bit when put into the same game. The reason is that they both have the same basic idea of being based on systems instead of manuscripts and on rules instead of pre-made decisions.

This concept is of course what all games have in common, though only to a different degree. My hope before starting making the game was to place myself firmly on the outer edge of the "interactivity" side while still giving the player the tools to experience some kind of meaningful story. By "meaningful", I mean that it should include memorable events, follow some kind of structure, and make sense to human beings. If I could succeed in that while still letting the player "do whatever he wants" I thought I would be happy.

In the end all this boils down to what has been a hot topic for a long time now, namely how games have to start saying things to be taken seriously. The one important thing to realize is that I'm not talking about "meaning" as in contemporary art, where some obscure thought from the artist (or the viewer of the artwork) is imagined to be hidden inside the work.

When I talk about the game being meaningful to people, I mean that in a very direct way: showing them things that interests them, preferably from an angle they haven't seen before. So how does Blueberry Garden hold up in this respect? What do the gameplay and interactions in my game say to the player?

This is of course up to everyone to figure out for themselves. One simple but powerful feature of interactive experiences is that they can be easily changed, meaning different things to different people. Of course so can books and movies too, but not in the same extreme way. If you want to play Blueberry Garden as a story about how a maniac killed every animal in the world by throwing them down into the water -- be my guest. The meaning I will discuss here is primarily my intended meaning.

This is dangerous territory indeed! One could argue that the need to explain things shows a clear failure of communication on my side. I agree with this; actually I'd rather have you go play the game and see what you come up with yourself. On the other hand I think there is value in me revealing what I wanted to achieve since, it will make it more obvious where I succeeded and where I failed.

I have decided to break down the meaning of the game in three levels, from the lowest to the highest. Unfortunately, this is not based on any well acknowledged theories I've read; it's just a way that I like to think about it. Please bear with me even if you don't approve of my classification. My point is not to present "the grand theory of meaning in games." I just want to present my thinking in an orderly fashion.



Meaning in games can occur at several levels simultaneously. First of all, every small event in the game brings with it some meaning. A player throwing a creature into the water to let it drown could be described as "murder", for instance. This is not something the game and its rules say anything about, it's just something that emerges from how the creatures and the game world work.

Other meaningful actions are more pre-planned, such as the ability to eat fruit to get special powers or building the tower a little higher by finding a strange object in the landscape. Still, the meaning is there; nothing is so abstract that it can't be described through normal means of telling a story. Most video games work very well on this level.



The second layer is way more interesting. It could probably best be described as "the story layer." This is where the smaller, atomic events of playing the game work together to form some kind of a story. This is where most modern video games use cutscenes and other pre-determined chunks of events to make things work out.

If those elements would be removed, no one would know really what was going on. When this works out in a FPS for example, it gives you a reason to shoot at the enemies, and you know that the game is over when the bad boss is killed.

So what story does Blueberry Garden tell? Of course there are several, arguably boring stories that some people have created through playing the game. Someone might just have walked around the garden, looking at things for a while, and then turned it off. That story is certainly not very interesting to tell back to someone.

Another potential story is when the ecosystem goes crazy and birds invade the whole world. This happens rarely, but it certainly makes for a different experience.

The stories that I hoped that most people would experience are a bit more substantial, though. To my great pleasure it seems like most players experience exactly the series of events that was intended. The first playthrough this goes something like this, retold from a first person perspective:

I found myself lost in a strange land filled with flowers and strangely shaped terrain.

Since no one was around to tell me what was going on, I decided to explore some.

First of all I learned how to fly, then that I could eat blueberries. Eventually I realized how I could construct a tower with objects that I found; this tower helped me to explore the world more.

Suddenly it dawned upon me that the water in the world was rising. Yikes! What could I do?! I tried flying as far as I could to the right, where I found a faucet. I couldn't reach it, but maybe if I could make the tower a little higher...? As I tried finding more building blocks, the water started rising very quickly. Panic! As the water flooded the whole world, my only chance of survival was to stand carefully on a log. When I tried to move I fell down into the abyss. Game over.

This is certainly more exciting! This is not just some random dude with a beak running around in a crazy garden; this is an actual series of events that makes sense only when put together. It certainly lacks human drama and interesting character portraits -- it's very primal. To me, that's fine. My work is just a small stepping stone in trying to help evolve storytelling in games.

The next level of meaning is what could be described as "the message." Some people seem obsessed with the idea that things that could be described as "works of art" also have to have some kind of underlying message.

The simple answer here is that I didn't have any message with Blueberry Garden. Some people might think that I was commenting on global warming, for instance. While ecology and sustainability are certainly things that are close to my heart, this is not something that I was pushing for very much (at the same time I think that it's impossible to not embed a part of yourself in your work).



In the end though, I think the most correct analysis comes from looking at what my top-level design goals were. As stated before, the main reason for me to make the game was to try out some underused game design ideas (the ecosystem and storytelling solely through interaction). These two messages, when combined into one game, become all about what that game asks its players to do; namely to think for themselves and be responsible.

Put into an unknown environment with no one to tell you right from wrong, what would you do? As humans we so often rely on the hive-mind and other people's opinions. Left to our own devices we have to get back in a kind of primal state, where our actions have real consequences. Without any load button or possibility to reset missed opportunities, we suddenly are forced to think hard -- or everything is lost. This is not something that is ever told to the player directly, but anyone who plays the game will feel those things.

Finally there is something more to be said about my process of creating the game. As I hope is clear from the text, I used science or academic interest as a big motivation. I wanted to know certain things and let that determine how the game should work. Of course that is not the whole truth; I also had more personal and artistic reasons to make the game.

Much of what makes people like the game, I think, comes from the fact that I brought in a lot of what is "me" and my experiences to the game. A good example of this is the landscape, which is very much inspired by Sweden's west coast archipelago, with its bare rocks and occasional trees swaying in the wind.

A big part of what I tried to do was capture the mood of an empty island in the middle of the summer. The kind of day where it's neither cloudy nor sunny and a small wind is chilling everything down a little. The water is dark, and even though everything is very nice you have a certain sense of doom. If anything of that feeling has appeared in the room while you played the game I'm very satisfied.

If this game will be remembered in the future it will not be for what it is, but rather for what it tried to do. Looked at from afar, through the binoculars of today's game design practice, it does not make very much sense. Instead I beg everyone to focus on the finer details, the subtle things that really try to make the player experience something profound.

These details are a direct result of trying to take a relatively simple idea (a story told solely through interactive means, set in an ecosystem) and bringing it to its extreme, adding as little extraneous elements as possible. Even if the results are both rough and vague, hidden behind code of dubious quality, I hope they will encourage more exploration. To all of us who are pursuing that path -- good luck!
