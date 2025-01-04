---
layout: page
title: "The Scratch That Can't be Itched"
permalink: /stcbi/
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
.lightbox {
  display: none;
  justify-content: center;
  align-items: center;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.8);
  z-index: 1000;
}

.lightbox img {
  max-width: 90%;
  max-height: 90%;
}
</style>


<div class="embed-wrapper">
      <p> <strong>Where to play:</strong> <br>
      <iframe frameborder="0" src="https://itch.io/embed/3173227?dark=true" width="552" height="167"><a href="https://kungaroh.itch.io/the-scratch-that-cant-be-itched">The Scratch That Can't Be Itched by Kungaroh | Henry, lozicon</a></iframe>    </p>
      </div>
<div class="game-page-container">

<div class="game-page-container">
  
  <!-- Game description and experience -->
  <div class="game-description">
    <h2>The Scratch That Can't be Itched</h2>
    <p> <strong>Where to play:</strong> <br> Unfortunately my team and I are still working on The Scratch That Can't be Itched (STCBI) and so it is unavailable to play! </p> 
    <p><strong>About the Game:</strong><br>SCTBI is a comedy puzzle game where you play as Jim who is on a mission to prove his mother wrong and show that he isn't a failure and can make friends!</p>
    <h3>My Experience:</h3>
      <p>
        <br><strong>What I did</strong>
        <br> Throughout this project I was the team lead. I had responsibilities such as demonstrating work completed in a weekly standup, assigning tasks at the start of each sprint, and reviewing the previous sprint's performance and how we all felt about it.<br> in addition to these responsibilities, I also did programming for the game, including creating quest scripts, creating a checkpoint system and debugging and refactoring broken scripts written by other members. Finally I also brought the game together, combining the different scenes that the different designers made, adding models to the characters, and adding the created animations to the characters in the engine.
      <br><strong>Why?</strong> 
      <br> We are creating STCBI as apart of the 11 week long "VFX and Game Production Studio" university unit, where we (Computer Games Development, Computer Games Design, Computing and VFX) are apart of a simulated games development studio with 9 games being created in parallel and I am leading the team creating this one! 
      <br><br><strong>What did I learn?</strong>
      <br> Whilst leading and creating STCBI I have learned to lead a team, <strong>Jira</strong> to assign work to teammates, <strong> prioritisation</strong> and to give weekly standups on the progress the team has made.
      <br> Throughout this project we have used Jira to manage our sprints, whilst learning spring review techniques such as "glad, sad, mad" and "the sailboat". These have assisted the team in identifying weakness both in ourselves, and the game and tasks being set each week.
      <br> I have learned a lot about the nuances of managing a team, such as ensuring communication and solving issues with team members who are not pulling their weight or turning up.
      <br> I have also learned about the creative processes of creating a game such as the different stages of conceptualising, designing and implementing whilst trying not to get stuck with lots of ideas and ensuring there is a clear path with next stages.
    </p>
  </div>

  <!-- Game images -->
  <div class="game-images">
    <img src="/stcbi images/stcbi logo.png" alt="Scratch That Can't Be Itched Logo">
    <img src="/stcbi images/fighting ducks in castle.png" alt="fighting ducks in a castle">
    <img src="/stcbi images/talking to mum.gif" alt="A gif of talking to mam">
    <img src="/stcbi images/talking to Phrogius.png" alt="image of talking to phrogius">
  </div>

  <div class="lightbox" id="lightbox">
    <img src="" alt="Expanded image" id="lightbox-image">
  </div>

  <script>
  const images = document.querySelectorAll('.game-images img');
  const lightbox = document.getElementById('lightbox');
  const lightboxImage = document.getElementById('lightbox-image');

  images.forEach(img => {
  img.addEventListener('click', () => {
    const fullImage = img.getAttribute('src');
    if (fullImage) {
      lightboxImage.src = fullImage;
      lightbox.style.display = 'flex';
    }
  });
});

lightbox.addEventListener('click', () => {
  lightboxImage.src = ''; // Clear src when lightbox is closed
  lightbox.style.display = 'none';
});
</script>
</div>
