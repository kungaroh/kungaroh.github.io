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



<iframe width="560" height="315" src="https://www.youtube.com/embed/X6xnIptPP1Y?si=JLSen8Qlp5l4m0B8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<div class="game-page-container">
  
  <!-- Game description and experience -->
  <div class="game-description">
    <h2>Ionix Game Engine</h2>
    <p> <strong>Where to use:</strong> <br> Due to Ionix Engine being in development, you currently cannot use it. </p> 
    <p> <strong>Find the source:</strong>
    <br> <a href="https://github.com/kungaroh/Ionix-Game-Engine" target="_blank" class="github-button">View Source on GitHub</a> </p>
    <p><strong>Find the Engine API Reference:</strong> 
    <br> <a href="https://kungaroh.github.io/Ionix-Game-Engine/" target="_blank" class="github-button">View API Reference</a></p>
    <p><strong>About the Engine:</strong><br>Ionix Engine is a lightweight C++ game engine, with a lua wrapper for simple 2D game development!</p>
    <h3>My Experience:</h3>
    <br><p><strong>what I did</strong></p>
    <br><p>Throughout this project I woked on the Architecture team! My duties included, implementing and managing the layer system, and assiting with implementing the Tiled editor<br>I took control over the Object layer to ensure functionality of the <strong>scene</strong>, <strong>objects</strong>, and <strong>omponents</strong>. I implemented the functions in these classes to ensure they can all interact with eachother and can be accessed and changed through the scripts, as well as being made when the engine first starts.</p>
    <br><p><strong>why?</strong></p>
    <br><p>Ionix Engine was created as part of the Game Engine unit at university. Ionix Engine is being developed to give the Computer Game Development cohort hands on experience with working in a large code base, with a large team. 
    This includes expanding on an existing framework, and implementing all the features you would want to have in a 2D game engine.
    <br>The class was split up into team , these were Architecture, Scripting, physics, Input, UI and Graphics/Audio</p>
    <br><p><strong>How can it be expanded?</strong></p>
    <br><p>The engine can be expanded and improved by improving the Tiled intergration, such as being able to run the engine directly from Tiled with a single button press! </p>
    
    
  </div>

  <!-- Game images -->
  <div class="game-images">
    <img src="/portfolio icons/ionix logo.png" alt="Ionix Engine Logo">
    <img src="/Ionix Images/launching game.gif" alt="A gif of launching a game from the Tiled Editor">
    <img src="/Ionix Images/LayerObject code snippet.png" alt="A code snippet from the Object Layer">
    <img src="/Ionix Images/tiled editor.png" alt="An image of the tiled editor with a simple 2D game in it">
    <img src="/Ionix Images/Object class code snippet.png" alt="A code snippet from the Object class">
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
