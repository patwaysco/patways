<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>PATWAYS</title>
  <style>
    body {
      margin: 0;
      font-family: 'Helvetica Neue', sans-serif;
      background: #f7f7f7;
      color: #222;
      scroll-behavior: smooth;
    }

    header {
      background: #871210;
      height: 90vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
      flex-direction: column;
      position: relative;
    }

    header h1 {
      font-size: 4rem;
      margin: 0;
      text-transform: uppercase;
      letter-spacing: 4px;
    }

    header p {
      font-size: 1.2rem;
      margin-top: 10px;
      font-style: italic;
    }

    .shop-btn {
      margin: 40px auto 0;
      background: white;
      color: #871210;
      border: none;
      padding: 14px 28px;
      font-weight: bold;
      font-size: 1.1rem;
      border-radius: 30px;
      cursor: pointer;
      text-decoration: none;
      transition: transform 0.3s ease, background 0.3s ease;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
      animation: floatPulse 2.5s ease-in-out infinite;
      display: inline-block;
    }

    .shop-btn:hover {
      background: #ffdde1;
      transform: scale(1.05);
    }

    @keyframes floatPulse {
      0% { transform: translateY(0px); }
      50% { transform: translateY(-6px); }
      100% { transform: translateY(0px); }
    }

    nav {
      background: #fff;
      padding: 15px 0;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav a {
      margin: 0 20px;
      text-decoration: none;
      font-weight: bold;
      color: #871210;
    }

    section {
      padding: 60px 20px;
      max-width: 1200px;
      margin: auto;
    }

    .section-title {
      font-size: 2.5rem;
      margin-bottom: 20px;
      text-align: center;
      color: #871210;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 30px;
    }

    .gallery img {
      width: 100%;
      border-radius: 10px;
      height: auto;
      object-fit: cover;
      transition: transform 0.3s ease;
    }

    .gallery img:hover {
      transform: scale(1.03);
    }

    .about, .contact {
      background: #fff;
      padding: 60px 30px;
      line-height: 1.6;
      border-top: 1px solid #ccc;
    }

    .about h2, .contact h2 {
      color: #871210;
      text-align: center;
      margin-bottom: 20px;
    }

    .tiktok-button-wrapper {
      text-align: center;
      margin-top: 40px;
    }

    footer {
      background: #871210;
      color: white;
      text-align: center;
      padding: 30px 10px;
    }

    @media screen and (max-width: 600px) {
      header h1 {
        font-size: 2.5rem;
      }

      nav a {
        margin: 0 10px;
        font-size: 0.9rem;
      }

      .shop-btn {
        font-size: 1rem;
        padding: 10px 22px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>PATWAYS</h1>
    <p>Your Style, Your Way</p>
  </header>

  <nav>
    <a href="#acidwashed">Acid Washed Tees</a>
    <a href="#longsleeves">Pull Overs</a>
    <a href="#croptops">Cropped Tops</a>
    <a href="#espresso">Espresso Collection</a>
    <a href="#spa">SZA "Life's Better On Saturn"</a>
    <a href="#knitted">Knitted Tops</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="acidwashed">
    <h2 class="section-title">Acid Washed Tees</h2>
    <div class="gallery">
      <a href="https://ibb.co/YT4swZZQ"><img src="https://i.ibb.co/CspGD228/americano.png" alt="americano" border="0"></a>
<a href="https://ibb.co/k6h48DFj"><img src="https://i.ibb.co/6J4HPt5z/aurora-2.png" alt="aurora-2" border="0"></a>
<a href="https://ibb.co/8D5wGjjn"><img src="https://i.ibb.co/rG6hqZZK/ECLIPSE-1.png" alt="ECLIPSE-1" border="0"></a>
<a href="https://ibb.co/ymrQgz5L"><img src="https://i.ibb.co/j9Sr3CG7/ESPRESSO.png" alt="ESPRESSO" border="0"></a>
<a href="https://ibb.co/LXbFfdGL"><img src="https://i.ibb.co/bMq0n5fS/kekeno-3.png" alt="kekeno-3" border="0"></a>
<a href="https://ibb.co/N288pTVL"><img src="https://i.ibb.co/DfxxkrV7/KIWI.png" alt="KIWI" border="0"></a>
<a href="https://ibb.co/wZQjXbSz"><img src="https://i.ibb.co/p6K58sfL/lavender.png" alt="lavender" border="0"></a>
<a href="https://ibb.co/ZRTGMxCn"><img src="https://i.ibb.co/20KWkdBD/MATCHA.png" alt="MATCHA" border="0"></a>
<a href="https://ibb.co/tTb9sMK5"><img src="https://i.ibb.co/dwQR20My/mocha.png" alt="mocha" border="0"></a>
<a href="https://ibb.co/dssZGX5h"><img src="https://i.ibb.co/vCC9Zfjt/P-2-2.png" alt="P-2-2" border="0"></a>
    </div>
  </section>

  <section id="longsleeves">
    <h2 class="section-title">Long Sleeve Acid Washed Tees</h2>
    <div class="gallery">
      <a href="https://ibb.co/3yYB1DpP"><img src="https://i.ibb.co/zhHGsyXt/kekeno-a.png" alt="kekeno-a" border="0"></a>
<a href="https://ibb.co/PGBphJzH"><img src="https://i.ibb.co/jk7KMqZX/MATCHAAAA-asa.png" alt="MATCHAAAA-asa" border="0"></a>
<a href="https://ibb.co/zhbLJXVW"><img src="https://i.ibb.co/rGMLsx2K/mocha-222.png" alt="mocha-222" border="0"></a>
<a href="https://ibb.co/rRhMVsxG"><img src="https://i.ibb.co/8Lw2HcrD/sasasasasasas.png" alt="sasasasasasas" border="0"></a>
    </div>
  </section>

  <section id="croptops">
    <h2 class="section-title">Cropped Acid Washed Tees</h2>
    <div class="gallery">
<a href="https://ibb.co/R436rqM3"><img src="https://i.ibb.co/2YvMVTLv/ameriii-2323.png" alt="ameriii-2323" border="0"></a>
<a href="https://ibb.co/xSd7SBQC"><img src="https://i.ibb.co/qMVrMcwy/Lavv-23232.png" alt="Lavv-23232" border="0"></a>
<a href="https://ibb.co/Dft15b4t"><img src="https://i.ibb.co/r2mQ4tkm/navvv-23.png" alt="navvv-23" border="0"></a>
<a href="https://ibb.co/Kj3KknBQ"><img src="https://i.ibb.co/SX9f8SH1/rora.png" alt="rora" border="0"></a>
<a href="https://ibb.co/qMJJHzT6"><img src="https://i.ibb.co/svWWTh87/Untitled-11.png" alt="Untitled-11" border="0"></a>
     

    </div>
  </section>

  <section id="espresso">
    <h2 class="section-title">Espresso Acid Wash Collection</h2>
    <div class="gallery">
     <a href="https://ibb.co/0j6tD9L6"><img src="https://i.ibb.co/0j6tD9L6/13.png" alt="13" border="0"></a> <a href="https://ibb.co/VpTxbYGk"><img src="https://i.ibb.co/VpTxbYGk/14.png" alt="14" border="0"></a> <a href="https://ibb.co/qYTdPBtk"><img src="https://i.ibb.co/qYTdPBtk/15.png" alt="15" border="0"></a> <a href="https://ibb.co/HLbX2yky"><img src="https://i.ibb.co/HLbX2yky/16.png" alt="16" border="0"></a>
    </div>
  </section>

  <section id="spa">
    <h2 class="section-title">SZA "Life's Better On Saturn"</h2>
    <div class="gallery" style="display: flex; justify-content: center;">
      <a href="https://ibb.co/WW809vy5"><img src="https://i.ibb.co/WW809vy5/IMG-2035.jpg" alt="IMG-2035" border="0"></a>
    </div>
  </section>

  <section id="knitted">
    <h2 class="section-title">Knitted Tops</h2>
    <div class="gallery">
     <a href="https://ibb.co/NnswNbQ0"><img src="https://i.ibb.co/NnswNbQ0/patways-35.png" alt="patways-35" border="0"></a>  
      <a href="https://ibb.co/tMr3456g"><img src="https://i.ibb.co/tMr3456g/BLACK-3.png" alt="BLACK-3" border="0"></a>
      <a href="https://ibb.co/99dZqyjV"><img src="https://i.ibb.co/99dZqyjV/patways-46.png" alt="patways-46" border="0"></a>
    </div>
  </section>

  <div class="tiktok-button-wrapper">
    <a class="shop-btn" href="https://www.tiktok.com/@patways.co" target="_blank">Shop Now on TikTok</a>
  </div>

  <section class="about" id="about">
    <h2>About Us</h2>
    <p>
      Founded by <strong>Ma. Patricia Alyanna Merida</strong> on March 25, 2025, PATWAYS was born from a passion for comfort, confidence, and self-expression.
      Our collections of acid washed and plain tees are designed to reflect your journey and move with you — no matter where you’re headed.
    </p>
    <p>
      PATWAYS isn’t just a fashion label; it’s a feeling. A sense of pride in being yourself. From cropped tops to oversized fits, every design tells a story of individuality. We believe fashion should walk beside you — not ahead of you.
    </p>
  </section>

  <section class="contact" id="contact">
    <h2>Contact & Orders</h2>
    <p>DM us on Instagram: <a href="https://instagram.com/patways.co" target="_blank">@patways.co</a></p>
    <p>Follow us on TikTok: <a href="https://www.tiktok.com/@patways.co" target="_blank">@patways.co</a></p>
    <p>Email: <a href="mailto:pat.waysofficial@gmail.com">pat.waysofficial@gmail.com</a></p>
    <p>For bulk/reseller pricing, just ask 💌</p>
  </section>

  <footer>
    <p>&copy; 2025 PATWAYS. All rights reserved. | @patways.co</p>
  </footer>

</body>
</html>

