---
layout: page
title: Ionix Game Engine
permalink: /gameengine/
---

<style>
  .game-page-container {
    display: flex;
    gap: 20px;
    margin: 20px;
  }
  .game-description {
    flex: 2;
    padding-right: 20px;
  }
  .game-images {
    flex: 1;
    display: flex;
    flex-direction: column;
    gap: 10px;
  }
  .game-images img {
    width: 100%;
    border-radius: 5px;
  }
  .github-button:hover {
  background-color: #444;
}
</style>

<div class="game-page-container">
  
  <!-- Game description and experience -->
  <div class="game-description">
    <h2>Ionix Game Engine</h2>
    <p> <strong>Where to use:</strong> <br> Due to Ionix Engine being in development, you currently cannot use it. </p> 
    <p> <strong>Find the source:</strong>
    <br> <a href="https://github.com/kungaroh/Ionix-Game-Engine" target="_blank" class="github-button">View Source on GitHub</a> </p>
    <p><strong>Find the Engine API Reference:</strong> 
      <br> <a href="https://kungaroh.github.io/Ionix-Game-Engine/" target="_blank" class="github-button">View API Reference</a>
    <p><strong>About the Engine:</strong><br>Ionix Engine is a lightweight C++ game engine, with a lua wrapper for simple 2D game development!</p>
    <h3>My Experience:</h3>
<br><p><strong>why?</strong></p>
<br><p>Ionix Engine was created as part of the Game Engine unit at university. Ionix Engine is being developed to give the Computer Game Development cohort hands on experience with working in a large code base, with a large team. 
    This includes expanding on an existing framework, and implementing all the features you would want to have in a 2D game engine.
<br>The class was split up into team , these were Architecture, Scripting, physics, Input, UI and Graphics/Audio</p>


  <p><br><br><strong>What Team was I on?</strong>
  <br> I started the project as a member of the architecture team, throughout this time, 
  <ul> <li>I assisted implementing the layer system</li> <li>creating a resource manager</li> <li>Taking ownership of the object system</li> </ul>
  <br>The layer system is fairly simple, each system had it's own layer, such as the <code>Object Layer</code>, this meant that the different systems could interact with eachother (running scripts that effect the physics on an object), without being coupled together, through the use of the observer pattern!
  <br>I assisted in creating the resource manager by being a paired programmer working with another team member, together we created the texture loading, and I handled the font loading alone.
  <br> <strong>Object System</strong>
  <br>I then moved onto creating the object system, this includes the scene, the objects inside the scene, and the components on the objects! I had to create a number of functions including <code>AddObject()</code>,  <code>RemoveObject()</code>,  <code>EnableObject()</code>,  <code>DisableObject()</code>, the same for all the components, and the start and update functions for them all.
  <br>
  <br> Once the MVP had been reached for the general engine, we moved to extending it to using an Editor, to save time on building our own editor we used Tiled. Tiled allowed us to export the scene data as a <code>.lua</code> file, which allowed us to easily import the data and bring it into C++ since we were already interacting between lua and C++.
  With the data imported, it was again my time to shine, to use the data and create objects and components so that the engine could run them!
  <br>
  <br><strong>What did I learn?</strong>
  <br>Throughout this process I learned a number of things including:
  <li><ul>Debugging</ul><ul>Using GitHub/source control as part of a large team</ul><ul>How to read/understand existing code and integrate it with new code</ul></li></p>
  </div>

  <!-- Game images -->
  <div class="game-images">
     <img src="/portfolio icons/ionix logo.png" alt="Ionix Engine Logo">
    <!--<img src="/FireTeam Images/ladders and spray.gif" alt="A gif where the ladder increase and the hose is sprayed">
    <img src="/FireTeam Images/playing on playdate.jpeg" alt="An image of the game on a playdate">
    <img src="/FireTeam Images/medium building.png" alt="An image of a large building in the game on fire">
    <img src="/FireTeam Images/large building.png" alt="An image of a large building in the game on fire"> -->
     
  </div>
</div>

