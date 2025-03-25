---
hidden: false
permalink: /projects/TheLantern/
title: "The Lantern"
toc: true
toc_sticky: true
---

<!-- ## The Lantern -->
<div markdown="1">
  <a href="https://giaarah.itch.io/thelantern" class="btn btn--primary"><i class="fa-brands fa-itch-io"></i> Play The Lantern on Itch</a>
</div>
*Developed Using C#, Unity*

<!-- The is semester-long student project developed by a team of two. I was the primary engineer and game designer on the team and managed the implementation between Wwise and the Unity project. -->

The Lantern is a 3D adventure game where you play as the guardian of the sky, who has woken from a deep period of dormancy, and now needs to return corrupted stars back to their constellations. A semester-long student project developed by a team of two.

<div>
  <iframe width="560" height="315" src="https://www.youtube.com/embed/oo3QrY19f6Y?si=1bgIXnG9hJxtA0WL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

Primary contributions for the project:
- Created a robust flight-based player character controller 
- Integrated flight and player movement with a bow-and-arrow style mechanic
- Additively loading in 2D puzzles into 3D game through render textures
- Created game managers for cutscenes, cameras, audio, & gameplay

### Player Controller Script
For The Lantern, the player has 4 states: grounded, flying, aiming, and in-puzzle. 

The player should be able to seamlessly transition between all states, and the aiming state can be activated simultaneously with other locomotive states. 

<!-- See the in-progress code [on GitHub](https://github.com/GiaArah/TheLanternCodeSamples/blob/main/PlayerController.cs). -->
