<!DOCTYPE html>
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
      background-image: url('hero.png'); /* ✅ Make sure this matches your uploaded image file */
      background-size: cover;
      background-position: center;
      height: 500px;
      display: flex;
      flex-direction: column;
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
      font-size: 4rem;
      margin: 0;
      color: #ff66cc;
      text-shadow: 3px 3px 10px #000;
    }

    .hero h2, .hero p {
