<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>SoRealosity</title>
  <style>
    body {
      margin: 0;
      font-family: 'Courier New', monospace;
      background-color: #111;
      color: #fff;
    }

    .hero {
      background-image: url('hero.png');
      background-size: cover;
      background-position: center;
      height: 80vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 2rem;
    }

    h1 {
      font-size: 4rem;
      margin: 0;
      color: #fff;
    }

    .tagline {
      font-size: 1.25rem;
      margin-top: 1rem;
      max-width: 700px;
      color: #ddd;
    }

    .gallery {
      display: flex;
      flex-direction: column;
      gap: 2rem;
      padding: 2rem;
      background-color: #222;
    }

    .gallery img {
      width: 100%;
      max-width: 800px;
      margin: 0 auto;
      border: 3px solid #fff;
      box-shadow: 0 0 10px #000;
      display: block;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background: #111;
      font-size: 0.8rem;
      color: #666;
    }
  </style>
</head>
<body>
  <div class="hero">
    <h1>SoRealosity</h1>
    <div class="tagline">
      SoRealosity delivers AI-powered nostalgic artwork inspired by iconic moments that never happened — but should have.
    </div>
  </div>

  <div class="gallery">
    <img src="art1.jpg" alt="Art 1" />
    <img src="art2.jpg" alt="Art 2" />
    <img src="art3.jpg" alt="Art 3" />
  </div>

  <footer>
    &copy; 2025 SoRealosity. All surreal rights imagined.
  </footer>
</body>
</html>

