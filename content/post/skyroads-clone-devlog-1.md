+++
title = "Skyroads clone devlog #1 - 3 months"
date = "2016-12-24T23:13:40Z"

+++

It's christmas evening and I'm here writing my first devlog. I decided to do these because I think I can keep better track of my progress and it's also nice to share ideas, it might come to be useful for someone someday.

So, I want to talk about a game I have been working on for about 3 months now, which is much more time than I ever did work on a game.
As you can tell by the title of this post, it's a Skyroads clone/remake, if you don't know what game Skyroads is, you should definitely look up, it's
a pretty fun game from the good old DOS times. Originally made by Bluemoon Interactive, Skyroads is a remake itself from an older game from the same
developer called Kosmonaut, it's one of that games that is "easy to learn, hard to master" with the gameplay being pretty much you guiding a
space ship while having to jump some blocks in space, simple right? Well, I advise you to confirm that by yourself ;)

My version of Skyroads is pretty faithful to the original, I only made it prettier and will possibly add some more features in the future, but I really
need to focus on getting the gameplay solid right now.

### Tools

I'm writing the game using [libGDX](https://libgdx.badlogicgames.com/), which is a Java framework for cross-platform games,
It's the framework/library that I am most familiar with, so I'm feeling pretty confortable with the development.

I will also use Blender for modeling the ship's 3D model, every model until now has been hard-coded into the game.

### How the game looks like now

I've written too much and showed you nothing, so here it goes:

![1](/skyroads-devlog-1-s1.png)
![2](/skyroads-devlog-1-s2.png)
![3](/skyroads-devlog-1-s3.png)
![4](/skyroads-devlog-1-s4.png)
![6](/skyroads-devlog-1-s6.png)
![7](/skyroads-devlog-1-s7.png)
<small>No roads for Andromeda :c</small>

"Taiho" is just a temporary name that I don't even remember what it means. I still haven't come up with a final name, so I'm accepting suggestions.

### How the code looks like now

Well, not great, in fact, pretty ugly. I actually started writing this game more than half a year ago, but gave up after 1 month, and then I started working on it
again in the middle of November, and my coding style has changed a lot in that short period of time, lots of bad design choices like functions receiving arguments that it
shouldn't even know it exists, separation of concerns, general code organization, etc... I wish I had started writing this as an engine and only after I had a working engine
I should start writing the game itself, but no, everything is mixed up and you can see gameplay code together with physics simulation. Can I fix that? Of course. Will I fix that? mmm, probably not.
I just have this feeling that I need to "ship the product" as fast as possible because it has been so much time since I've "finished" a game (last was in June 2015) that I need to prove to myself
that I'm able to finish this as quick as possible. After that, I will start working on a new game from scratch, and focus on writing a proper game engine first.

### TODOs

- Finish the gameplay mechanics (tile effects, etc...), I'm almost done here.
- Make a proper 3d model for the ship, I still want it to be pretty basic, but anything is better than the fucking rectangle that it is now.
- Make a level editor, editing level files by hand is pretty boring right now, maybe I'll polish it enough that I will leave it there for players who want to build their own levels.
- Make more worlds, there is only "Red Heat" and "Andromeda" at the moment, need to come up with some A E S T H E T I C S for the rest, I plan to have 6 worlds, each with 3 roads.
- Support for controllers.
- Optimize the renderer post-processing pipeline, I’m already mentally preparing myself for this.

Hopefully it will be done by March 2017.

### Open source

The game is not open-source at the moment, I think it hasn't reached a level where it might be useful for anyone yet, specially for the grotesque mistakes that I've made.
But I will make it open-source in the future, I just hate when small games like this are not open-source, as ugly as the code maybe, they are still a great source of learning
for people who want to get into game development and see how that particular game was made.

### Summary

So that is it, this is the project I've been working on to practice game development, if you liked it, stay tuned for more devlogs. ;)

And also, merry christmas.