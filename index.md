---
layout: home
title: "Henry Varley's Portfolio!"
---


    
# About Me
I'm Henry Varley and I am an aspiring Game/Engine Programmer! I have a strong passion for building robust and expandable systems such as games, engines and other software alike!
<h2>Skills Overview:</h2>
<div class="skills-grid">
<ul>
<li><div>Jira</div></li>
<li><div>Git</div></li>
<li><div>C#</div></li>
<li><div>C++</div></li>
<li><div>Unity</div></li>
<li><div>Unreal Engine</div></li>
<li><div>Lua</div></li>
<li><div>Project Management</div></li>
</ul>
</div>

<h2>Currently Working Towards:</h2>
<ul>
    <li>Improving my Unreal Engine knowledge</li>
<li>Improving my C++ knowledge</li>
</ul>
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
        overflow: hidden;
        z-index: 10;
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
        z-index: 11;
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
        z-index: 11;
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
        z-index: 11;
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
     <a href="/MM">
         <div class="download-badge">Download</div>
        <div class="image-container">
         <div class="source-badge">Source</div>
         <img src="/portfolio icons/mammas milkeria icon.png" alt="Mammas milkeria Thumbnail">
        </div>
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
      <p>The Scratch That Can’t Be Itched is an irreverent comedy game filled with absurd characters!</p>
     </a>
   </div>
 <div class="game-card">
     <a href="/gameengine">
      <div class="image-container">
       <div class="source-badge">Source</div>
       <img src="/portfolio icons/ionix logo.png" alt="Ionix Game Engine Placeholder Thumbnail">
      </div>
       <p><strong>Ionix Game Engine</strong></p>
      <p>A 2D game engine integrated with Tiled to create small and fun games!</p>
     </a>
   </div>
    <div class="game-card">
     <a href="/procgenTool">
      <div class="image-container">
       <!--<div class="source-badge">Source</div>-->
       <img src="/portfolio icons/Traffic Cone.png" alt="An image of a traffic cone">
      </div>
       <p><strong>Procedural Generation Tool</strong></p>
      <p>A procedural generation tool which I am developing as part of my Synoptic Project(dissertation)</p>
     </a>
   </div>
</div>
