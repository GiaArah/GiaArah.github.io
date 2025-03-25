---
hidden: false
permalink: /projects/Egress/
title: "Egress"
toc: true
toc_sticky: true
---

<!-- ## Egress (game prototype) -->
*Developed Using C#, Unity*

<div markdown="1">
  <a href="https://giaarah.itch.io/egress" class="btn btn--primary"><i class="fa-brands fa-itch-io"></i> Download Prototype on Itch</a>
</div>

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