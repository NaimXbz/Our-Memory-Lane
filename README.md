<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Our Memory Lane</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(to bottom right, #d0aaff, #b38bff);
      font-family: 'Segoe UI', sans-serif;
      color: #fff;
      text-align: center;
    }

    .container {
      padding: 2rem;
    }

    h1 {
      font-size: 3rem;
      font-weight: 800;
      color: #6d28d9;
    }

    .intro {
      margin-bottom: 2rem;
      font-size: 1.2rem;
      color: #f3e8ff;
    }

    .slideshow-btn, .nav-btn {
      background: #7c3aed;
      color: white;
      border: none;
      padding: 10px 20px;
      margin: 1rem;
      border-radius: 20px;
      font-weight: bold;
      cursor: pointer;
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
    }

    .highlight {
      background: #facc15;
      color: #4c1d95;
    }

    .gallery {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 1.5rem;
      margin: 2rem 0;
    }

    .photo-card {
      position: relative;
      width: 220px;
      height: 300px;
      overflow: hidden;
      border-radius: 15px;
      box-shadow: 0 6px 20px rgba(0, 0, 0, 0.3);
    }

    .photo-card img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      border-radius: 15px;
    }

    .overlay {
      position: absolute;
      bottom: 0;
      left: 0;
      right: 0;
      background: rgba(108, 0, 180, 0.75);
      color: white;
      padding: 10px;
      opacity: 0;
      transition: opacity 0.3s ease;
      font-size: 0.95rem;
    }

    .photo-card:hover .overlay {
      opacity: 1;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Our Memory Lane</h1>
    <p class="intro">A journey through the most incredible moments we’ve shared together. Hover over each photo to see why these memories mean so much to me! ✨❤️</p>
    
    <button onclick="startSlideshow()" class="slideshow-btn">▶ Start Slideshow</button>

    <div class="gallery">
      <div class="photo-card">
        <img src="assets/images/photo1.jpg" alt="Memory 1"/>
        <div class="overlay">🌸 The day our journey began.</div>
      </div>
      <div class="photo-card">
        <img src="assets/images/photo2.jpg" alt="Memory 2"/>
        <div class="overlay">💞 Caught in a candid moment I’ll never forget.</div>
      </div>
      <div class="photo-card">
        <img src="assets/images/photo3.jpg" alt="Memory 3"/>
        <div class="overlay">💋 Our favorite movie-style kiss!</div>
      </div>
      <div class="photo-card">
        <img src="assets/images/photo4.jpg" alt="Memory 4"/>
        <div class="overlay">☀️ The day we laughed till sunset.</div>
      </div>
    </div>

    <div class="buttons">
      <button class="nav-btn">← Back to Welcome</button>
      <button class="nav-btn highlight">✨ Next Surprise! ✨</button>
    </div>
  </div>

  <script>
    function startSlideshow() {
      alert("Slideshow feature coming soon! For now, hover over each photo to explore the memories 💫");
    }
  </script>
</body>
</html>
