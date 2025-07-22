<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>SoRealosity</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: 'Courier New', monospace;
      margin: 0;
      padding: 0;
      background-color: #111;
      color: #fff;
    }

    .hero {
      position: relative;
      background-image: url('hero.jpg');
      background-size: cover;
      background-position: center;
      height: 450px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }

    .hero::before {
      content: "";
      position: absolute;
      top: 0; left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.5); /* Dark overlay */
      z-index: 1;
    }

    .hero h1 {
      position: relative;
      z-index: 2;
      font-size: 2.5rem;
      color: #ff66cc;
      padding: 1rem 2rem;
      text-shadow: 2px 2px 10px #000;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 1.5rem;
      padding: 2rem;
    }

    .gallery img {
      width: 100%;
      height: auto;
      border-radius: 10px;
      border: 3px solid #ff66cc;
      box-shadow: 0 0 20px rgba(255, 102, 204, 0.5);
    }

    .footer {
      background-color: #222;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      color: #aaa;
    }
  </style>
</head>
<body>

  <div class="hero">
    <h1>Where Retro Gets Real — Digital Dreams, Printed Magic</h1>
  </div>

  <div class="gallery">
    <img src="art1.jpg" alt="Retro surreal art 1">
    <img src="art2.jpg" alt="Retro surreal art 2">
    <img src="art3.jpg" alt="Retro surreal art 3">
  </div>

  <div class="footer">
    &copy; 2025 SoRealosity. All rights reserved.
  </div>

</body>
</html>
