<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>SoRealosity</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Courier New', monospace;
      background-color: #111;
      color: #fff;
    }

    .hero {
      background-image: url('hero.png'); /* Make sure 'hero.png' is in your repo */
      background-size: cover;
      background-position: center;
      height: 550px;
      position: relative;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
    }

    .hero::before {
      content: "";
      position: absolute;
      top: 0; left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.5); /* dark overlay */
      z-index: 1;
    }

    .hero h1 {
      z-index: 2;
      position: relative;
      font-size: 4.5rem;
      color: #ff66cc;
      text-shadow: 3px 3px 10px #000;
      margin: 0;
    }

    .hero h2 {
      z-index: 2;
      position: relative;
      font-size: 1.5rem;
      color: #fff;
      margin-top: 1rem;
      padding: 0 1rem;
      max-width: 800px;
      text-shadow: 2px 2px 8px #000;
    }

    .hero p {
      z-index: 2;
      position: relative;
      font-size: 1.1rem;
      font-style: italic;
      color: #ccc;
      margin-top: 1rem;
      padding: 0 2rem;
      max-width: 800px;
      text-shadow: 1px 1px 6px #000;
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
    <h1>SoRealosity</h1>
    <h2>Where Retro Gets Real — Digital Dreams, Printed Magic</h2>
    <p>SoRealosity delivers AI-powered nostalgic artwork inspired by iconic moments that never happened — but should have.</p>
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

