
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SoRealosity</title>
  <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Press Start 2P', cursive;
      background-color: #2b2b2b;
      color: #fefefe;
      text-align: center;
    }

    header {
      padding: 3rem 1rem 1rem 1rem;
    }

    .title {
      font-size: 4rem;
      color: #00ffff;
      text-shadow: 4px 4px 0 #ffff00;
    }

    .tagline {
      font-size: 1.25rem;
      margin-top: 1rem;
      color: #ffcc00;
      text-shadow: 1px 1px #000;
    }

    .hero {
      background: url('newhero.png') center/cover no-repeat;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
      text-shadow: 2px 2px 4px #000;
      font-size: 1.5rem;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      padding: 3rem;
    }

    .product-card {
      background: #1e1e1e;
      border: 2px solid #ff00ff;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.5);
      transition: transform 0.2s ease-in-out;
    }

    .product-card:hover {
      transform: scale(1.05);
    }

    .product-card img {
      width: 100%;
      height: auto;
    }

    .info {
      padding: 1rem;
    }

    .info h3 {
      color: #00ffcc;
      margin-bottom: 0.5rem;
    }

    .info p {
      font-size: 0.85rem;
    }

    button {
      background-color: #00ffff;
      color: #000;
      border: none;
      padding: 0.5rem 1rem;
      font-weight: bold;
      font-family: 'Press Start 2P', cursive;
      cursor: pointer;
      border-radius: 5px;
      margin-top: 1rem;
    }

    button:hover {
      background-color: #00cc99;
    }

    .footer {
      background-color: #111;
      color: #888;
      padding: 1rem;
      font-size: 0.75rem;
    }
  </style>
</head>
<body>
  <header>
    <div class="title">SoRealosity</div>
    <div class="tagline"><i>Surreal iconic images that never happened, but should have!</i></div>
  </header>

  <section class="products">
    <div class="product-card">
      <img src="art1.jpg" alt="Sinatra on Toilet">
      <div class="info">
        <h3>Sinatra on a Toilet</h3>
        <p>Marilyn Monroe hands him the roll. Glam meets absurdity.</p>
        <button>Buy Print</button>
      </div>
    </div>

    <div class="product-card">
      <img src="art2.jpg" alt="Churchill Breakdancing">
      <div class="info">
        <h3>Churchill Breakdancing</h3>
        <p>The PM with power moves. History’s hottest remix.</p>
        <button>Buy Print</button>
      </div>
    </div>

    <div class="product-card">
      <img src="art3.jpg" alt="Hitchcock Directs Dinner">
      <div class="info">
        <h3>Hitchcock's Dinner Scene</h3>
        <p>Alfred Hitchcock directs a surreal dinner with Julia Child and Hannibal Lecter — culinary tension with a twist of horror.</p>
        <button>Buy Print</button>
      </div>
    </div>
    <!-- Art 4 -->
<div class="art-item" style="border: 3px solid pink; padding: 10px; margin: 10px;">
  <img src="art4.jpg" alt="Bruce Lee and Dean Martin in Heaven" style="width:100%;" />
  <p>Bruce Lee and Dean Martin in Heaven</p>
  <button onclick="buyArt('art4.jpg')">Buy Print</button>
</div>

<!-- Art 5 -->
<div class="art-item" style="border: 3px solid pink; padding: 10px; margin: 10px;">
  <img src="art5.jpg" alt="Barbara Walters Interviewing Satan" style="width:100%;" />
  <p>Barbara Walters interviewing Satan</p>
  <button onclick="buyArt('art5.jpg')">Buy Print</button>
</div>

<!-- Art 6 -->
<div class="art-item" style="border: 3px solid pink; padding: 10px; margin: 10px;">
  <img src="art6.jpg" alt="George Michael Eating a Cinnabon" style="width:100%;" />
  <p>George Michael eating a Cinnabon instead of singing jitterbug</p>
  <button onclick="buyArt('art6.jpg')">Buy Print</button>
</div>

<!-- Art 7 -->
<div class="art-item" style="border: 3px solid pink; padding: 10px; margin: 10px;">
  <img src="art7.jpg" alt="Arnold on Protein and Chicken vs Egg" style="width:100%;" />
  <p>Arnold telling you just eat protein, who cares about what comes first between chicken and egg</p>
  <button onclick="buyArt('art7.jpg')">Buy Print</button>
</div>

<!-- Art 8 -->
<div class="art-item" style="border: 3px solid pink; padding: 10px; margin: 10px;">
  <img src="art8.jpg" alt="Coach Ted Lasso Directing Chess Match" style="width:100%;" />
  <p>Coach Ted Lasso directing a classic chess match between greats Ronaldo and Messi with legends watching</p>
  <button onclick="buyArt('art8.jpg')">Buy Print</button>
</div>

<!-- Art 9 -->
<div class="art-item" style="border: 3px solid pink; padding: 10px; margin: 10px;">
  <img src="art9.jpg" alt="David Bowie and Mr Rogers Podcasting" style="width:100%;" />
  <p>David Bowie and Mr. Rogers</p>
  <button onclick="buyArt('art9.jpg')">Buy Print</button>
</div>
  </section>

  <div class="footer">&copy; 2025 SoRealosity.com delivers AI-powered artwork where Pop Culture, History, and Absurdity Collide in Iconic Style!  Retro Icons, Twisted Realities, Timeless Cool </div>
</body>
</html>

 

