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
    <br> Ionix Engine source will be available once the semester is over and I can fork the repo!<!--UPDATE ONCE FORKED <a href="https://github.com/kungaroh/BubbleSort" target="_blank" class="github-button">View Source on GitHub</a>--> </p>
    <p><strong>About the Engine:</strong><br>Ionix Engine is a lightweight C++ game engine, with a lua wrapper for simple 2D game development!</p>
    <h3>My Experience:</h3>
      <p>
      <br><strong>Why?</strong> 
      <br>Ionix Engine is being created as apart of the "Games Enignes" unit at university. Ionix Engine is being developed by the full Computer Games Development BSc cohort, who have been split into teams to tackle the various sections of the game engine (Physics, Scripting, Architecture, Input, UI, Graphics/Audio)
      <br><br><strong>What team was I on?</strong>
      <br> I started the project on the Architecture team, however this work  was quickly completed and we moved on to assist the Input team, followed by becoming the Editor team.
        <br> As the <strong>Architecture team</strong>, we created layers for the engine for the different teams to interact with by firing events as the engine has been made using the <strong> Observer Pattern</strong>. 
        <br>In addition to the layers, I worked on creating the <strong>Scene</strong>, <strong>game object</strong>, and <strong>components</strong> systems. This meant creating all of the getters, setters and creation functions necessary, along with start and update functions, and of course their destructors, ensuring everything was destroyed correctly!
      <br><br> Supporting the <strong>Input team</strong>, my team coordinated and created key down, held and up functions using SDL2 event polling, along with creating mouse button down, held and up., before finally adding mouse movement, and the getters for other teams to be able to access this data.
      <br><br> As apart of the <strong>Editor team</strong>,we are using Tiled where we will learn how to use the Tiled Editor, and then using it's exported Lua data to created any scenes, objects and components needed for a game to be made using the engine. In addition to this, we will be customising the editor to be better incorporated with the engine, to allow a "play mode" and allow the user to test games in the Editor itself!
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

