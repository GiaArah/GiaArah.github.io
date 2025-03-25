---
hidden: false
permalink: /engineering/
title: "Engineering"
toc: true
toc_sticky: true
---
<!-- # Engineering -->
## The Lantern
<div markdown="1">
  <a href="https://giaarah.itch.io/thelantern" class="btn btn--primary"><i class="fa-brands fa-itch-io"></i> Play The Lantern on Itch</a>
</div>
*Developed Using C#, Unity*

<!-- Lucerna is semester-long student project developed by a team of two. I was the primary engineer and game designer on the team and managed the implementation between Wwise and the Unity project. -->

Lucerna is a 3D adventure game where you play as the guardian of the sky, who has woken from a deep period of dormancy, and now needs to return corrupted stars back to their constellations. A semester-long student project developed by a team of two.

<div>
  <iframe width="560" height="315" src="https://www.youtube.com/embed/oo3QrY19f6Y?si=1bgIXnG9hJxtA0WL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

Primary contributions for the project:
- Created a robust flight-based player character controller 
- Integrated flight and player movement with a bow-and-arrow style mechanic
- Additively loading in 2D puzzles into 3D game through render textures
- Created game managers for cutscenes, cameras, audio, & gameplay

### Lucerna: Player Controller Script
For Lucerna, the player has 4 states: grounded, flying, aiming, and in-puzzle. 

The player should be able to seamlessly transition between all states, and the aiming state can be activated simultaneously with other locomotive states. 

<!-- See the in-progress code [on GitHub](https://github.com/GiaArah/TheLanternCodeSamples/blob/main/PlayerController.cs). -->


## Egress (game prototype)
*Developed Using C#, Unity*

Egress is an infinite, minimalist puzzle game where players must navigate a grid of color-coded portals to reach the end goal in the shortest amount of steps. 

A 3-week long student project made for a "game prototyping" class. The prompt for this prototype was "randomization." 

<div>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/j3vC4bmY0U0?si=FgJ6pjkmBhiPdjFq&amp;start=33" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

### Egress: Randomized Grid Spawning; BFS for Shortest Path Detection
- Implemented randomized linkages between portals and assigned random color to linked portals
- Utilized BFS search algorithm to determine shortest path size, assigning points based on player's distance from shortest path
- Created an AI that plays the game itself for an interactive title screen
- Developed a save system to keep score, position on board, and board layout

### Egress: Colorspace Conversion
- To solve the issue where randomized color selections were too similar, I used a C# color utility tool to convert the color selection from the RGB color space to the CIE Lab colorspace, which more accurately reflects the human eye's color perception. Using a distance calculation, I ensured the colors chosen sequentially were distinct enough.