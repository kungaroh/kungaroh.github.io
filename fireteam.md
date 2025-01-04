---
layout: page
title: Fire Team
permalink: /fireteam/
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
  .spacer{
    height: auto;
    width: 100px;
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

<iframe width="560" height="315" src="https://www.youtube.com/embed/YVx7q3mQ2nA?si=wR-avY-xtCi0MwZL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<div class="embed-wrapper">
      <p> <strong>Where to play:</strong> <br>
      <iframe frameborder="0" src="https://itch.io/embed/2815691?dark=true" width="552" height="167"><a href="https://kungaroh.itch.io/fire-team">Fire Team by Kungaroh | Henry</a></iframe></p>       
      </div>
<div class="game-page-container">
  <!-- contain the embed -->
      
  
  <!-- Game description and experience -->
  <div class="game-description">
      <!-- <br> <a href="https://kungaroh.itch.io/fire-team" target="_blank">On My Itch page</a> -->
    <p><strong>About the Game:</strong><br> Fire Team is a game which is played on the Playdate Console using it's unique hardware (the crank) to pump up the water and unleash it on the ablaze building!</p>
    <p><strong>My Experience:</strong><br> Throughout my time creating Fire Team, I learned the programming language Lua! This is a small and light language which is perfect to perform tasks with minimum power, which is ideal for the Playdate!
      <br><br> I also learned how to quickly become familiar with a new SDK whilst prototyping a game. This skill will benefit me going forward with learning new programming languages and new game engines alike as I have learned how to navigate and search for the necessary functions that I may need to use!
      <br><br> Whilst creating Fire Team I had to have weekly stand ups with the game leads to show what progress I had made that week followed by prioritizing and planning the following week. To manage this project we used a kanban board on Trello!
    </p>
  </div>

  <!-- Game images -->
  <div class="game-images">
    <img src="/FireTeam Images/FireTeam Logo.png" alt="Fire Team Logo">
    <img src="/FireTeam Images/ladders and spray.gif" alt="A gif where the ladder increase and the hose is sprayed">
    <img src="/FireTeam Images/playing on playdate.jpeg" alt="An image of the game on a playdate">
    <img src="/FireTeam Images/medium building.png" alt="An image of a large building in the game on fire">
    <img src="/FireTeam Images/large building.png" alt="An image of a large building in the game on fire">
    <!-- Add more images as needed -->
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
