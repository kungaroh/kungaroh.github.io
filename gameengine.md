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
</style>

<div class="game-page-container">
  
  <!-- Game description and experience -->
  <div class="game-description">
    <h2>Ionix Game Engine</h2>
    <p> <strong>Where to use:</strong> <br> Due to Ionix Engine being in development, you currently cannot use it! </p> 
    <p> <strong>Find the source:</strong> <br> Due to being a University Project containing the full cohort, I don't believe the source code will ever be available although this will be updated if it ever is!</p>
    <p><strong>About the Engine:</strong><br>Ionix Engine is a lightweight C++ game engine, with a lua wrapper for simple 2D game development!</p>
    <h3>My Experience:</h3>
      <p>
      <br><strong>Why?</strong> 
      <br>Ionix Engine is being created as apart of the "Games Enignes" unit at university. Ionix Engine is being developed by the full Computer Games Development BSc cohort, who have been split into teams to tackle the various sections of the game engine (Physics, Scripting, Architecture, Input, UI, Graphics/Audio)
      <br><strong>What team was I on?</strong>
      <br> I started the project on the Architecture team, we created layers for the engine for the different teams to interact with by firing events as the engine has been made using the <strong> Observer Patter </strong>. In addition to the layers, I worked on creating the Scene, game object, and components. This meant creating all of the getters, setters and creation functions necessary, along with on start and on update functions necessary for scripts and physics to properly run.
      <br> Following completing the base architecture of the engine, my team was swiftly allocated work that other teams were struggling with, namely input. My team coordinated and created key down, held and up functions using SDL2 event polling, along with creating mouse button down, held and up.before finally adding mouse movement, and the getters for other teams to be able to access this data.
      <br> Moving forward the Architecture team is being reallocated, and is becoming the Editor team. For the editor we are using Tiled, and we shall be creating the necessary systems for the engine to recieve and parse the Lua data exported from tiled to be able to run the game. In addition to the parsing and allocating the data to the necessary places, we will also be working on customising the Tiled Editor, to make it feel more integrated with the Ionix Engine.
      
    </p>
  </div>

  <!-- Game images -->
  <div class="game-images">
   <!-- <img src="/FireTeam Images/FireTeam Logo.png" alt="Fire Team Logo">
    <img src="/FireTeam Images/ladders and spray.gif" alt="A gif where the ladder increase and the hose is sprayed">
    <img src="/FireTeam Images/playing on playdate.jpeg" alt="An image of the game on a playdate">
    <img src="/FireTeam Images/medium building.png" alt="An image of a large building in the game on fire">
    <img src="/FireTeam Images/large building.png" alt="An image of a large building in the game on fire">
     -->
  </div>
</div>

