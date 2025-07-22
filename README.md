<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF‑8" />
  <meta name="viewport" content="width=device-width, initial‑scale=1.0"/>
  <title>SoRealosity</title>
  <style>
    body {
      font-family: 'Courier New', monospace;
      background-color: #111;
      color: #eee;
      margin: 0;
      padding: 0;
    }
    .hero {
      background: url('hero.jpg') center/cover no-repeat;
      height: 450px;
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 2rem;
      text-align: center;
      padding: 2rem;
      background-color: #222;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 1rem;
      padding: 2rem;
    }
    .gallery img {
      width: 100%;
      max-height: 400px;
      object-fit: cover;
      border: 3px solid #ff66cc;
      border-radius: 10px;
      box-shadow: 0 0 20px rgba(255, 102, 204, 0.4);
    }
    .footer {
      text-align: center;
      padding: 1rem;
      background-color: #222;
      color: #aaa;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <div class="hero">
    Where Retro Gets Real — Digital Dreams, Printed Magic
  </div>
  <div class="gallery">
    <img src="art1.jpg" alt="Surreal scene 1" />
    <img src="art2.jpg" alt="Surreal scene 2" />
    <img src="art3.jpg" alt="Surreal scene 3" />
  </div>
  <div class="footer">© 2025 SoRealosity. All rights reserved.</div>
</body>
</html>
