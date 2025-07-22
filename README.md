<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SoRealosity</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@600&family=Press+Start+2P&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Press Start 2P', cursive;
      background: linear-gradient(to bottom right, #1a1a1a, #3d3d3d);
      color: #fefefe;
      margin: 0;
      padding: 0;
    }
    header {
      background: #000;
      padding: 2rem;
      text-align: center;
      font-size: 2rem;
      color: #00ffcc;
      text-shadow: 2px 2px #ff00ff;
    }
    .hero {
      background: url('your-hero-image.jpg') center/cover no-repeat;
      height: 450px;
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 1.5rem;
      color: #ffcc00;
      text-shadow: 1px 1px 5px #000;
      letter-spacing: 2px;
      text-align: center;
      padding: 1rem;
    }
    .section {
      padding: 2rem;
      text-align: center;
    }
    .section h2 {
      color: #00ffcc;
      margin-bottom: 1rem;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
      padding: 2rem;
    }
    .product-card {
      background: #222;
      border: 2px solid #ff00ff;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 4px 12px rgba(0,0,0,0.6);
      transition: transform 0.2s ease-in-out;
    }
    .product-card:hover {
      transform: scale(1.03);
    }
    .product-card img {
      width: 100%;
      height: auto;
    }
    .product-card .info {
      padding: 1rem;
    }
    .product-card h3 {
      color: #ffcc00;
    }
    .footer {
      text-align: center;
      padding: 1rem;
      background: #111;
      color: #888;
      font-size: 0.75rem;
    }
    button {
      background: #00ffcc;
      color: #000;
      border: none;
      padding: 0.5rem 1rem;
      font-weight: bold;
      cursor: pointer;
      border-radius: 5px;
      margin-top: 0.5rem;
    }
    button:hover {
      background: #00cc99;
    }
  </style>
</head>
<body>
  <header>SoRealosity</header>
  <div class="hero">Where Retro Gets Real — Digital Dreams, Printed Magic</div>

  <section class="section">
    <h2>Explore Our One-of-a-Kind Retro Art</h2>
    <p>SoRealosity delivers AI-powered nostalgic artwork inspired by iconic moments that never happened — but should have.</p>
  </section>

  <section class="products">
    <div class="product-card">
      <img src="art1.jpg" alt="Sinatra on Toilet" />
      <div class="info">
        <h3>Sinatra on a Toilet</h3>
        <p>Marilyn Monroe hands him the roll. Glam meets absurdity.</p>
        <button>Buy Print</button>
      </div>
    </div>

    <div class="product-card">
      <img src="art2.jpg" alt="Churchill Breakdancing" />
      <div class="info">
        <h3>Churchill Breakdancing</h3>
        <p>The PM with power moves. History’s hottest remix.</p>
        <button>Buy Print</button>
      </div>
    </div>

    <div class="product-card">
      <img src="art3.jpg" alt="Hitchcock Directs Dinner" />
      <div class="info">
        <h3>Hitchcock's Dinner Scene</h3>
        <p>Alfred Hitchcock directs a surreal dinner with Julia Child and Hannibal Lecter — culinary tension with a twist of horror.</p>
        <button>Buy Print</button>
      </div>
    </div>
  </section>

  <div class="footer">&copy; 2025 SoRealosity.com — Designed in the Twilight Zone</div>
</body>
</html>
