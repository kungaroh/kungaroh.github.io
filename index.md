---
layout: home
title: "Henry Varley's Portfolio!"
---


    
# About Me
I'm Henry Varley and I am an aspiring Game/Engine Programmer! I have a strong passion for building robust and expandable systems such as games, engines and other software alike!
<h2>Skills Overview:</h2>
<div class="skills-grid">
<ul>
<li><div>Unity</div></li>
<li><div>C#</div></li>
<li><div>C++</div></li>
<li><div>Unreal Engine</div></li>
<li><div>Lua</div></li>
<li><div>Project Management</div></li>
<li><div>Jira</div></li>
<li><div>Git</div></li>
</ul>
</div>

<p>If you want to learn more about my experience <a href="/aboutme">Click Here</a>.</p>


# Projects/Portfolio
<img alt="An image with all the Logos from my game portfolio" src="/gameCollection.png">

<style>
    .skills-grid {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 10px;
        margin: 10px 0;
    }
    .portfolio-grid {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
        gap: 20px;
  }
    .game-card {
        position: relative;
        background-color: #f3f3f3;
        padding: 10px;
        text-align: center;
        border-radius: 8px;
        transition: transform 0.2s;
        border: 2px solid white;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.6);
  }
    .game-card .playable-badge {
        position: absolute;
        top: 10px;
        right: 10px;
        background-color: green;
        color: white;
        padding: 2px 8px;
        border-radius: 4px;
        font-size: 0.8em;
        font-weight: bold;
        z-index: 1;
  }
    .game-card .download-badge {
        position: absolute;
        top: 10px;
        right: 10px;
        background-color: blue;
        color: white;
        padding: 2px 8px;
        border-radius: 4px;
        font-size: 0.8em;
        font-weight: bold;
        z-index: 1;
 }
    .game-card .source-badge {
        position: absolute;
        bottom: 0px;
        right: 0px;
        background-color: purple;
        color: white;
        padding: 2px 8px;
        border-radius: 4px;
        font-size: 0.8em;
        font-weight: bold;
        z-index: 1;
 }
    .game-card .image-container {
      position: relative;
 }
    .game-card img {
        width: 100%;
        height: auto;
        border-radius: 5px;
  }
    .game-card p {
        font-size: 0.9em; 
        color: #555;
        margin: 8px 0 0;
   }
    .game-card a {
         color: inherit;
         text-decoration: none;
   }
    .game-card a:hover {
         color: #555; /* Optional: Different color on hover */
   }
    .game-card:hover {
        transform: scale(1.05);
  }
</style>

<div class="portfolio-grid">
  <div class="game-card">
   <div class="download-badge">Download</div>
    <a href="fireteam">
      <img src="/portfolio icons/fire team icon.png" alt="Fire Team Thumbnail">
      <p><strong>Fire Team</strong></p>
     <p>Use the Playdate crank to pump your water and extinguish fires!</p>
    </a>
  </div>
  <div class="game-card">
   <div class="playable-badge">Playable</div>
    <a href="/bubblesort">
     <div class="image-container">
      <div class="source-badge">Source</div>
      <img src="/portfolio icons/bubble sort icon.png" alt="Bubble Sort Thumbnail">
     </div>
        <p><strong>Bubble Sort Puzzle</strong></p>
     <p>Sort the bubbles into the correct tube to win!</p>
    </a>
  </div>
  <div class="game-card">
   <div class="download-badge">Download</div>
     <a href="/MM">
       <img src="/portfolio icons/mammas milkeria icon.png" alt="Mammas milkeria Thumbnail">
       <p><strong>Mamma's Milkeria</strong></p>
      <p>Create and grow your milk empire!</p>
     </a>
   </div>
  <div class="game-card">
     <a href="/musicagems">
      <div class="download-badge">Download</div>
      <div class="image-container">
       <div class="source-badge">Source</div>
       <img src="/portfolio icons/musicagems icon.png" alt="Musica Gems Thumbnail">
      </div>
       <p><strong>Musica Gems</strong></p>
      <p>Solve Sound Based Puzzles to return the magic music back to Musica</p>
     </a>
   </div>
  <div class="game-card">
     <a href="/stcbi">
      <div class="download-badge">Download</div>
       <img src="/portfolio icons/stcbi logo.png" alt="The Scratch That Can't Be Itched Thumbnail">
       <p><strong>The Scratch That Can't Be Itched</strong></p>
      <p>This game is currently in developement!</p>
     </a>
   </div>
 <div class="game-card">
     <a href="/gameengine">
      <div class="image-container">
       <div class="source-badge">Source</div>
       <img src="/portfolio icons/ionix logo.png" alt="Ionix Game Engine Placeholder Thumbnail">
      </div>
       <p><strong>Ionix Game Engine</strong></p>
      <p>A currently in developement game engine</p>
     </a>
   </div>
  <!-- Add more games similarly -->
</div>



<!--

 
## Game 1: Fire Team
[<img alt="Fire Team Logo Image" src="https://img.itch.zone/aW1nLzE2ODM2MzM3LnBuZw==/original/h3v5Ym.png">](https://kungaroh.itch.io/fire-team){:target="blank"}

About: This is Fire Team, this is the game which I created throughout my 6 week internship at MMU! This game makes use of the Playdate's unique hardware to create a fun game that anyone can play! Turn the crank to pressurise your water and put out fires with Barry and Larry!

Platform: Playdate

Where to play: [https://kungaroh.itch.io/fire-team](https://kungaroh.itch.io/fire-team){:target="blank"}


<!-- ------------------- Fire Team Ends ------------------- 


## Game 2: Bubble Sort Puzzle
[<img alt="Bubble Sort Puzzle Logo Image" src="https://img.itch.zone/aW1nLzE0MTcyNjM2LnBuZw==/315x250%23c/aZQtgY.png">](https://kungaroh.itch.io/bubble-sort-puzzle){:target="blank"}

About: Solve puzzles by sorting bubbles so that they only contain their own colour!

Platform: Web

Where to play: [https://kungaroh.itch.io/bubble-sort-puzzle](https://kungaroh.itch.io/bubble-sort-puzzle){:target="blank"}

Find the Source: [https://github.com/kungaroh/BubbleSort](https://github.com/kungaroh/BubbleSort){:target="blank"}

<!-- ------------------- Bubble Sort Ends ------------------- 

## Game 3: Mamma's Milkeria
[<img alt="Mammas Milkeria Logo Image" src="https://img.itch.zone/aW1nLzE2MDc5NDI1LnBuZw==/original/mgQNEf.png" width="350">](https://kungaroh.itch.io/mammas-milkeria){:target="blank"}

About: Shake you controller to milk the cow in this idle milking dream!

Platform: Windows *Requires a Nintendo Switch JoyCon or a PlayStation Dualshock 4/5 Controller to Play*

Where to play: [https://kungaroh.itch.io/mammas-milkeria](https://kungaroh.itch.io/mammas-milkeria){:target="blank"}

<!-- ------------------- Mamma's Milkeria Ends -------------------

## Game 4: Musica Gems
[<img alt="Musica Gems Logo Image" src="https://img.itch.zone/aW1hZ2UvMjY2NTEwMi8xNTg4MTIyNy5qcGc=/347x500/LTgKiz.jpg" width="350">](https://kungaroh.itch.io/musica-gems){:target="blank"}

About: Travel around the Land of Musica using Sound to solve puzzles and return the power of Magic Music back to the land of Musica!

Platform: Windows

Where to play: [https://kungaroh.itch.io/musica-gems](https://kungaroh.itch.io/musica-gems){:target="blank"}

Find the source: [https://github.com/kungaroh/MusicaGems](https://github.com/kungaroh/MusicaGems){:target="blank"}


<!-- ------------------- Muscia Gems Ends ------------------- -->


# Contact Me
If you have any feedback, or would like to get in touch for anything you can contact me by email
📫 henryvarley14+contact@gmail.com

<!--
**Iths567/Iths567** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
