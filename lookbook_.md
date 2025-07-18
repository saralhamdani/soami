<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>so am i</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@1,700&display=swap" rel="stylesheet">
  <style>
    body {
      background-color: white;
      background-image: radial-gradient(black 5%, transparent 6%);
      background-size: 30px 30px;
      margin: 0;
      font-family: 'Playfair Display', serif;
    }

    header {
      text-align: center;
      padding: 40px 20px 10px;
    }

    header img {
      max-width: 300px;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 20px;
      font-size: 1.2em;
    }

    nav a {
      text-decoration: none;
      color: black;
      border-bottom: 2px solid transparent;
      transition: border-color 0.3s;
    }

    nav a:hover {
      border-color: black;
    }

    .closet-section {
      padding: 40px;
      max-width: 800px;
      margin: auto;
    }

    .closet-section h2 {
      font-size: 2em;
      border-bottom: 1px solid black;
      padding-bottom: 10px;
    }

    .closet-section p {
      font-size: 1.1em;
      line-height: 1.6;
    }
  </style>
</head>
<body>

  <header>
    <img src="soami logo.png" alt="so am i logo">
  </header>

  <nav>
    <a href="#cbk">CBK's Closet</a>
    <a href="#carrie">Carrie's Closet</a>
    <a href="#naomi">Naomi's Closet</a>
    <a href="#diana">Diana's Closet</a>
  </nav>

  <div class="closet-section" id="cbk">
    <h2>CBK's Closet</h2>
    <p>Inspired by Carolyn Bessette-Kennedy — minimalist, elegant, timeless. Think: Ralph Lauren, The Row, clean tailoring, and buttery neutrals.</p>
  </div>

  <div class="closet-section" id="carrie">
    <h2>Carrie's Closet</h2>
    <p>Playful and unapologetic — a tribute to Carrie Bradshaw. Eclectic pairings, vintage Dior, bold shoes, and dreamy tulle moments.</p>
  </div>

  <div class="closet-section" id="naomi">
    <h2>Naomi's Closet</h2>
    <p>Glamour meets edge. Inspired by Naomi Campbell's supermodel era — Versace sparkle, structured silhouettes, and high drama.</p>
  </div>

  <div class="closet-section" id="diana">
    <h2>Diana's Closet</h2>
    <p>Princess off-duty. Diana Spencer's iconic off-duty style: bike shorts, sweatshirts, and effortless preppy flair with an aristocratic touch.</p>
  </div>

</body>
</html>
