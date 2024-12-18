---
layout: page
title: Mamma's Milkeria
permalink: /MM/
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
  .embed-wrapper{
    display: flex;
    allign-items: center;
    gap: 20px;
    margin: 20px;
  }
</style>
<div class="embed-wrapper">
<p> <strong>Where to play:</strong> <br>
  <iframe frameborder="0" src="https://itch.io/embed/2693733?border_width=2&amp;dark=true" width="554" height="169"><a href="https://kungaroh.itch.io/mammas-milkeria">Mamma's Milkeria by Kungaroh | Henry</a></iframe> </p> 
</div>

<div class="game-page-container">
  <!-- Game description and experience -->
  <div class="game-description">
   <!-- <p> <strong>Find the source:</strong> <br> <a href="https://github.com/kungaroh/BubbleSort" target="_blank">On my GitHub</a> </p> -->
    <p><strong>About the Game:</strong><br>Create and grow your cow milking empire in this idle game, that keeps you active!
    <br>Mamma's Milkeria is an idle game, where you have to shake your controller up and down to milk your cow, to sell the milk to upgrade and by more cows! </p>
    <h3>My Experience:</h3>
      <p>
      <br><strong>Why?</strong> 
      <br>I created Mamma's Milkeria as apart of the final week of the "Rapid Game Prototyping" unit at university. This game jam style unit tasked me to create a game prototypes over the course of 7 days, following the Theme of `The Dream Machine`.
        This game follows this theme because it is the story of Mamma, who's dream was to have a cow farm, and milk them for the best possible milk. This farm quickly became a well oiled machine where Mamma heads the milk empire!
      <br><br><strong>What did I learn?</strong>
      <br>Whilst creating this game I learned about <strong>Interacting with controllers in Unity</strong>, <strong>finding and adding external libraries to Unity</strong>, <strong> cirle maths </strong>. 
        <br>I used Circle Maths for spawning the cow teats around the udder ensuring they only spawn on the underside. 
        <br>Due to Unity not appearing to support Nintendo Switch JoyCon acceleration, I had to find a library which allowed me to get this data as I 
        wanted the unique twist of this idle game to be doing the motion of milking the cow (<a href="https://www.youtube.com/watch?v=m9bWVJrfCkY" target="_blank">inspired by the 1-2 Switch milk game</a>).
        I found <a href="https://github.com/JibbSmart/JoyShockLibrary" target="_blank">JibbSmart's JoyShockLibrary</a> which is a library to allow using all the features of DualShock4, DualSense, and Switch Joy-Cons to be usable natively in PC games.
        This library was perfect for me, as it meant I simply had to interact with the library to get the necessary data of the controller which was a lot easier than finding the library itself!
      <br> This is also the first game that I've use <strong>Unit's particle system</strong> which I used for the milk coming out of the udders, this was very simple application and was just a case of creating the shape and having the partlices shoot straight out.
      <br><br><strong> Improve the game?</strong>
      <br> If I were to improve this prototype to be a full game, I believe it wouldn't take much work, although the menu could look better, the milk particles improved to look more like milk, the controls could be improved so you have to press the side buttons whilst doing the milking motion, although this would remove compatibility with PlayStation controllers!
    </p>
  </div>

  <!-- Game images -->
  <div class="game-images">
    <img src="/MM Images/MM Logo.png" alt="Mamma's Milkeria Logo">
    <img src="/MM Images/buying teats2.gif" alt="a gif of upgrading cow in Mammas Milkeria">
    <img src="/MM Images/friesian cow.png" alt="an image of mammas milkeria game">
    <img src="/MM Images/Prestige.gif" alt="a gif of using prestige in Mammas Milkeria">
    <img src="/MM Images/vanilla cow.png" alt="an image of mammas milkeria game having unlocked the first prestige">
     
  </div>
</div>
