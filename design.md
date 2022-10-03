---
layout: page
title: Design Portfolio
permalink: /design/
---

This page is under construction! Please excuse the state of it while I'm working on improving the layout.

[![JayWalker Design Page Link](https://i.imgur.com/7Hjfqje.jpg)](https://www.nealspellman.com/jaywalker/)

<p align="center"><h2>Fan design for a Pinnacle Quest in Destiny 2</h2></p>
[This design document](https://drive.google.com/file/d/1U4_rl-em8Dgsw6hVt_XP8O0lmDNyhYsX/view?usp=sharing) was used as an exercise to practice quest design for an MMO-lite, offering player progression for a "season".
* Details estimated time for hardcore and casual/average players to complete each step and individual goal.
* Incentivizes gameplay across the season without power/item level attached to it, focusing more on letting players create builds they like and earn cosmetics.

<p align="center"><h2>Fan design for a new raid race mode in Destiny 2</h2></p>
<object data="https://www.nealspellman.com/documents/NealSpellman-ActivityDesignTrials.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://www.nealspellman.com/documents/NealSpellman-ActivityDesignTrials.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://www.nealspellman.com/documents/NealSpellman-ActivityDesignTrials.pdf">Download PDF</a>.</p>
    </embed>
</object>
* Incentivizes playing a bunch of matches to try and win, but still guarantees you won't walk away with nothing at our minimum effort level.
* Gives the player something they can do with friends that can easily be updated in new seasons, reusing any past/present boss monsters.


<p align="center"><h1>Technical Projects</h1></p>
<p align="center"><h2>NexusHQ (C#)</h2></p>
[NexusHQ](https://github.com/NealSpellman/NexusHQ) is an open-source project I released on Github, allowing players to check drop locations and rates for items within LEGO Universe.
This isn't yet complete (especially the UI!), but offers a starting point for other developers to jump on and help the project.
* Converted XML database tables to JSON for application consumption
* Added a modular image loading system, where users can slot in the item images from their game client's files.
* Dynamically generate item prefabs and activity info prefabs based on the number of items & loot tables per activity.

![Preview Picture](https://i.imgur.com/96IVgPB.png)

<p align="center"><h2>LEGO Universe Modding (Lua)</h2></p>
While this isn't necessarily a standalone project that you can "play", this is talking about the time I spent to learn Lua and run my own scripts within LEGO Universe.
* Self-taught myself Lua by researching dozens of client scripts and creating new ones.
* Created scripts to visualize database values for the player's customization options.
* Created scripts for new enemy types and making current bosses smarter.
* Made a master document of Lua functions and their arguments by dumping from the executable.
* Created two new content zones for Darkflame Universe, one of which was shown in a recent testing session.

<iframe width="100%" height="400" src="https://www.youtube.com/embed/videoseries?list=PL7RzS9Xujh65TncUYQ_H4S8bKWiHlOHHR" frameborder="0" allowfullscreen></iframe>

<p align="center"><h2>LEGO VR Experience (C#)</h2></p>
* Used the SteamVR plugin to create VR experiences and test on a Vive.
* Created a simple movement system for the player using the Vive controllers.
* Implemented interactible bricks to build with around the map.

<iframe width="100%" height="400" src="https://www.youtube.com/embed/videoseries?list=PL7RzS9Xujh67e687FQXxPnJgGm77_ZLz9" frameborder="0" allowfullscreen></iframe>
