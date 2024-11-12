---
layout: page
title: Musica Gems
permalink: /musicagems/
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



<div class="game-page-container">
  
  <!-- Game description and experience -->
  <div class="game-description">
    <h2>Musica Gems</h2>
    <p> <strong>Where to play:</strong> <br> <iframe frameborder="0" src="https://itch.io/embed/2665102?border_width=2&amp;dark=true" width="554" height="169"><a href="https://kungaroh.itch.io/musica-gems">Musica Gems by Kungaroh | Henry</a></iframe> </p> 
    <p> <strong>Find the source:</strong> <br> <a href="https://github.com/kungaroh/MusicaGems" target="_blank" class="github-button">View Source on GitHub</a>
</p>
    <p><strong>About the Game:</strong><br>Musica Gems is a puzzle game where you use sound to interact with the world around you and decipher puzzles!</p>
    <h3>My Experience:</h3>
      <p>
        <strong> Achievements </strong>
        Musica Gems won the Highly Commended award within the unit, competing against both Game Development BSc, MSc and Game Design BSc
        <br> Musica Gems was also featured at Upgrade, MMUs showcase of the best student work completed in the academic year.
      <br><strong>Why?</strong> 
      <br>I created Musica Gems as apart of the Rapid Game Prototyping unit at university. This game jam style unit challenged me to make a game prototype in 7 days, following the theme <q>The Enchanted Instrument</q>.
      <br><strong>What did I learn?</strong>
      <br>Whilst creating this game I learned about <strong>Unity animations</strong>, <strong> 3D sound in Unity </strong> <strong>coroutines</strong> and creating interesting menus such as a weapon wheel.
      <br>I used Unity's built in animation system to create an animation for a chest opening, once a puzzle is complete, and also for a bridge fading in and out of existing once the correct tune is played. 
      The bridge fading in and out was interesting, as I had to check the alpha of the material on the bridge so I could toggle on/off the collider for the bridge to ensure it would only play whilst the tune is playing!
      <br> Using Unity's sound system was very simple as all I had to do was add the sound I wanted to the relevant game object, set it to be spatial, and then I had to call when I wanted it to play, such as when interacting with one of the big gems!
      <br> I used coroutines in this project when I was creating the chest puzzle, where you have to bonk the big gems in a specific order to unlock the chest. I used the coroutine when the gems were played in the wrong order, as I would play a bad sound
        telling the player it was wrong, wait for 1 second so the player cannot interact with the gems, and also so the bad sound can play without being interupted.
      <br><strong>Improvements?</strong>
        If I were to improve Musica Gems, I would add more puzzles to the game, and make things in the level clearer, such as the enemy which you can charm by playing the correct tune, making it clear whether they are charmed or not, 
        I would improve the chest puzzle system to be clearer to players when they have it right or wrong (a lot of players found the answer half way through the puzzle and got confused when the bad tune played)
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
