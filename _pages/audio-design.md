---
hidden: false
permalink: /audio/
title: "Audio Design"
toc: true
toc_sticky: true

feature_row:
  - image_path: /assets/images/bio-photo.jpg
    alt: "Manas: Technical Audio Lead"
    title: "Manas: Technical Audio Lead"
    excerpt: "Used Unreal Engine & FMOD to implement all audio in-game."
    url: "/manas/"
    btn_class: "btn--primary"
    btn_label: "view project"
  - image_path: /assets/images/bio-photo.jpg
    alt: "Call of Duty: MW3"
    title: "Call of Duty: MW3"
    excerpt: "Interned with Sledgehammer Games designing audio in Reaper and implementing in CoD proprietary game engine."
    url: "/game-design/"
    btn_class: "btn--primary"
    btn_label: "view project"
  - image_path: /assets/images/bio-photo.jpg
    alt: "Diablo 4: Vessel of Hatred"
    title: "Diablo 4: Vessel of Hatred"
    excerpt: "Interned with Blizzard Entertainment designing and implementing audio in Wwise and proprietary game engine"
    url: "/engineering/"
    btn_class: "btn--primary"
    btn_label: "view project"      
---
<!-- # Audio Design -->
## Overview
### Audio Reel
<div>
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKQH_X4-X-E?si=TnsQ5oN8cKXHToA2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

## Diablo 4: Vessel of Hatred (Audio Design Internship)

*Designed and implemented sound effects using Reaper, Wwise, and proprietary engine, AXE*

<div markdown="1">
  <a href="https://diablo4.blizzard.com/" class="btn btn--primary"><i class="fa-solid fa-snowflake"></i> Diablo 4 Official Site</a>
</div>

- Designed and implemented 20+ sound effects for the Spiritborn class affixes using Wwise, Soundminer, and Reaper
  <!--   - Aspect of Empowered Feathers  - Aspect of Recalling Feathers   -->
  <!-- - Plugins used:    - Waves    - Melda Productions    - S-Layer    - Padshop    - Reaper -->
- Edited and implemented 600 unique NPC town vocalizations for the new “Nahantu” region
    <!-- - Set up base random containers with volume and pitch modulation in Wwise -->
    <!-- - Utilized the Diablo 4 "SoundMod" system, associating a Wwise RTPC with unique actors in-game at runtime -->
      <!-- - SoundMod value ensured each NPC character in-game would play appropriate vocalizations and had a randomly generated, unique, and consistent volume and pitch value attached -->
- Optimized reaper workflow by configuring DAW with scripts and custom actions
  <!-- - Integrated the following plugins:     - NVK Tools    - SWS    - Repack -->

  <iframe width="560" height="315" src="https://www.youtube.com/embed/-iHuczxeRW0?si=r-8KIkEXcE2ow64n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

  <iframe width="560" height="315" src="https://www.youtube.com/embed/BVZ_O01bsFY?si=8FibOt9Lf99Ximv1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<!-- <div style="display: flex; gap: 20px;"> -->
<!-- <div>
  <div>
    <h5>nahantu walla</h5>
    <video width="640" height="360" controls><source src="/assets/videos/nahantu_walla.mp4" type="video/mp4">Your browser does not support the video tag. You can download the video by
      <a href="/assets/videos/nahantu_walla.mp4">clicking here</a>.
    </video>
  </div>
      
  <div>
    <h5>spiritborn legendary eagle affixes</h5>
    <video width="640" height="360" controls><source src="/assets/videos/spiritborn_affixes.mp4" type="video/mp4">Your browser does not support the video tag. You can download the video by 
      <a href="/assets/videos/spiritborn_affixes.mp4">clicking here</a>.
    </video>
  </div>
</div> -->

## Call of Duty: MW3 (Audio Design Internship)
*Designed and implemented sound effects using Reaper and proprietary game and audio engines, APE and Audio Manager*

<div markdown="1">
  <a href="https://www.callofduty.com/modernwarfare3" class="btn btn--primary"><i class="fa-solid fa-gun"></i> CoD MW3 Official Site</a>
</div>

- Incorporated physics-based destruction sound effects into 5 multiplayer maps: Derail, Estate, Favela, Invasion, and Terminal using CoD proprietary engine, APE, and custom CSV-based audio engine, Audio Manager
  <!-- - Implemented in CoD proprietary engine, APE, and custom CSV-based audio engine, Audio Manager -->
  <!-- - Used knowledge of audio design fundamentals to make custom sound banks for each audio asset  -->
    <!-- - Configured audio asset sound banks, specifying parameters such as volume, pitch, fade, and bussing structures -->
    <!-- - Ensured efficient memory usage by reusing audio asset aliases across physics sounds, tightly trimming wav file tails, and reducing sounds to mono when stereo is unnecessary -->
- Designed and implemented 10 ambient emitter sound effects for various mechanical environment props across campaign and multiplayer maps
- Refinined and edited 6 field recording sessions, adding metadata for seamless integration into Sledgehammer Games Audio Libraries
<iframe width="560" height="315" src="https://www.youtube.com/embed/J7OQeF72Oik?si=2PzTYPSi_c6aQgZL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- <div style="display: flex; gap: 20px;"> -->
<!-- <div>
  <div>
    <h5>physics-based destructible environment objects</h5>
    <video width="640" height="360" controls><source src="/assets/videos/CoD_destructibles.mp4" type="video/mp4">Your browser does not support the video tag. You can download the video by
      <a href="/assets/videos/CoD_destructibles.mp4">clicking here</a>.
    </video>
  </div>
</div> -->

# Technical Audio Implementation
## Manas
#### Project Technical Audio Lead
*Developed Using UE Blueprints, Unreal Engine 5.1*

Manas is a student capstone project under USC Games' Advanced Games Project (AGP), developed in Unreal Engine 5.1.

Manas is a 3D, 3rd-person Action Adventure game featuring mounted combat, where you play as the legendary hero of Kyrgyzstan defending his nomadic village from invading conquerors, the Oirats.

<div markdown="1">
  <a href="https://uscgames.itch.io/manas" class="btn btn--primary"><i class="fa-brands fa-itch-io"></i> Play Manas on Itch</a>
</div>

- Configured FMOD project structure, designing project hierarchy, sound banks, and bussing structure for mixing and sidechaining
- Scripted all audio play events using UE 5 Blueprints
- Created a state-changing music system reactive to player conditions
- Implemented detailed natural world ambiences that change depending on story progression
- Conducted a foley recording session for player and enemy sound effects
- Implemented material-based weapon structure, playing impact sounds based on enemy/player armor and blocking status
- Designed early combat sounds for Manas and enemies
<iframe width="560" height="315" src="https://www.youtube.com/embed/vHO6T7LvVL8?si=JRYZdhE0UfFYZMEs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
- Created linear cutscene audio
- Edited 150+ lines of dialogue for all in-game voiceover
- Set up dialogue system in FMOD studio: dialogue loaded in at runtime from the Unreal project plays through FMOD, allowing reverb and effect chain processing
- Assisted with voice acting direction alongside project director during recording sessions
<iframe width="560" height="315" src="https://www.youtube.com/embed/wqtXwnrrxic?si=L286Quc5y9P_WDqU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- <div style="display: flex; gap: 20px;"> -->
<!-- <div>
  <div>
    <h5>manas audio design demonstration</h5>
    <video width="640" height="360" controls><source src="/assets/videos/manas_audio.mp4" type="video/mp4">Your browser does not support the video tag. You can download the video by
      <a href="/assets/videos/manas_audio.mp4">clicking here</a>.
    </video>
  </div>
</div> -->


<!-- # See More -->
<!-- {% include feature_row %} -->


