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
  .github-button {
  display: inline-block;
  background-color: #333; /* GitHub color */
  color: #fff;
  padding: 10px 20px;
  border-radius: 5px;
  font-weight: bold;
  text-decoration: none;
  transition: background-color 0.3s;
}

.github-button:hover {
  background-color: #444;
}
</style>

<iframe frameborder="0" src="https://itch.io/embed-upload/11501822?color=1d78c0" allowfullscreen="" width="850" height="670"><a href="https://kungaroh.itch.io/bubble-sort-puzzle">Play Bubble Sort Puzzle on itch.io</a></iframe>
<div class="game-page-container">
  
  <!-- Game description and experience -->
  <div class="game-description">
    <p> <strong>Where to play:</strong> <br> Right Here! Alternatively:
      <br> <iframe frameborder="0" src="https://itch.io/embed/2394303?border_width=2&amp;dark=true" width="554" height="169"><a href="https://kungaroh.itch.io/bubble-sort-puzzle">Bubble Sort Puzzle by Kungaroh | Henry</a></iframe> </p>
    <p> <strong>Find the source:</strong> <!-- <br> <a href="https://github.com/kungaroh/BubbleSort" target="_blank">On my GitHub</a> -->
    <br> <a href="https://github.com/kungaroh/BubbleSort" target="_blank" class="github-button">View Source on GitHub</a> </p>
    <p><strong>About the Game:</strong><br>Bubble Sort Puzzle is a simple puzzle game where you sort the bubbles into tubes so that each tube only contains a single colour bubble!</p>
    <h3>My Experience:</h3>
      <p>
      <br><strong>Why?</strong> 
      <br>I first created Bubble Sort Puzzle to further improve my Unity and C# skills from what I had learned in my first year at University. 
      <br><br><strong>What did I learn?</strong>
      <br>Whilst creating this game I learned about <strong>2D raycasts</strong>, and <strong>Unity's 2D physics system</strong>. This is because I was able to use Unity's built in physics to cause the bubble to fall into the tubes. 
      <br>I initially made it with a <i> lot </i> of if-statements for all the checks in the game, such as if a bubble is held, if it is the same colour as the bubble clicked on, if the tube is full etc. 
      Due to making it this way, it resulted in having some logic errors and being difficult to come back and make changes to the code. This is the first time I <strong>refactored</strong> code into a <strong>state machine</strong>.
      By refactoring the code to be a state machine, the number of checks that needed to happen were reduced, the aforementioned logic errors no longer exist and the code is easily readable and could potentially be expanded on!
      <br><br><strong>Editor Tools? </strong>
        <br> Whilst making Bubble Sort Puzzle, I quickly became tired of making all the bubbles the child of the tube they start in, and wanted a quicker way to make levels. 
      So I created an <a href="https://github.com/kungaroh/BubbleSort/blob/7dda536be97948844bf164d098745d07a0f3ec2a/Assets/Editor/AutoChild.cs" target="_blank">editor script</a>, where once I have arranged all the bubbles in the scene, I could go to <code> Tools > Auto Child</code> and all the bubbles would be set as children of the correct tube!
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
