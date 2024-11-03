---
layout: page
title: Bubble Sort Puzzle
permalink: /bubblesort/
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

<iframe frameborder="0" src="https://itch.io/embed-upload/11501822?color=1d78c0" allowfullscreen="" width="850" height="670"><a href="https://kungaroh.itch.io/bubble-sort-puzzle">Play Bubble Sort Puzzle on itch.io</a></iframe>
<div class="game-page-container">
  
  <!-- Game description and experience -->
  <div class="game-description">
    <h2>Bubble Sort Puzzle</h2>
    <p> <strong>Where to play:</strong> <br> <a href="https://kungaroh.itch.io/bubble-sort-puzzle" target="_blank">On my Itch page</a> </p> 
    <p> <strong>Find the source:</strong> br <a href="https://github.com/kungaroh/BubbleSort" target="_blank">On my GitHub</a> </p>
    <p><strong>About the Game:</strong><br>Bubble Sort Puzzle is a simple puzzle game where you sort the bubbles into tubes so that each tube only contains a single colour bubble!</p>
    <p><strong>My Experience:</strong><br> I first created Bubble Sort Puzzle to further improve my Unity and C# skills from what I had learned in my first year at University. 
      <br> Whilst creating this game I learned about 2D raycasts, and Unity's 2D physics system. This is because I was able to use Unity's built in physics to cause the bubble to fall into the tubes. 
      <br> I initially made it with a <i> lot </i> of if-statements for all the checks in the game, such as if a bubble is held, if it is the same colour as the bubble clicked on, if the tube is full etc. 
      Due to making it this way, it resulted in having some logic errors and being difficult to come back and make changes to the code. This is the first time I <strong>refactored</strong> code into a <strong>state machine</strong>.
      By refactoring the code to be a state machine, the number of checks that needed to happen were reduced, the aforementioned logic errors no longer exist and the code is easily readable and could potentially be expanded on!
      <br> Whilst making Bubble Sort Puzzle, I quickly became tired of making all the bubbles the child of the tube they start in, and wanted a quicker way to make levels. 
      So I created an <a href="https://github.com/kungaroh/BubbleSort/blob/main/Assets/Editor/AutoChild.cs"target="_blank">editor script</a>, where once I have arranged all the bubbles in the scene, I could go to <code> Tools > Auto Child </code> and all the bubbles would be set as children of the correct tube!
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
