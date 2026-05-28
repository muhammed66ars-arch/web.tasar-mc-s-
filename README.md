<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Arslan Studio</title>

  <!-- FONT -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: #0a0f1c;
      color: white;
      overflow-x: hidden;
    }

    /* GLOW ARKA PLAN */
    .glow {
      position: absolute;
      width: 600px;
      height: 600px;
      background: #3b82f6;
      filter: blur(160px);
      top: -200px;
      left: -200px;
      opacity: 0.5;
      z-index: 0;
    }

    /* NAV */
    nav {
      display: flex;
      justify-content: space-between;
      padding: 30px 70px;
      position: relative;
      z-index: 2;
    }

    nav h1 {
      color: #60a5fa;
      font-size: 28px;
    }

    nav a {
      text-decoration: none;
      color: white;
      background: rgba(255,255,255,0.08);
      padding: 10px 18px;
      border-radius: 12px;
      backdrop-filter: blur(10px);
      transition: 0.3s;
    }

    nav a:hover {
      transform: scale(1.1);
      background: #2563eb;
    }

    /* HERO */
    .hero {
      text-align: center;
      padding: 120px 20px;
      position: relative;
      z-index: 2;
    }

    .hero h2 {
      font-size: 60px;
      margin-bottom: 20px;
    }

    .hero p {
      max-width: 750px;
      margin: auto;
      color: #cbd5e1;
      font-size: 18px;
      line-height: 1.6;
    }

    /* BUTTONS */
    .buttons {
      margin-top: 35px;
    }

    .btn {
      padding: 14px 30px;
      border: none;
      border-radius: 12px;
      margin: 10px;
      cursor: pointer;
      font-size: 16px;
      transition: 0.3s;
    }

    .btn-primary {
      background: #3b82f6;
      color: white;
    }

    .btn-primary:hover {
      transform: scale(1.1);
      background: #2563eb;
    }

    .btn-outline {
      background: transparent;
      border: 1px solid #3b82f6;
      color: white;
    }

    .btn-outline:hover {
      transform: scale(1.1);
      background: rgba(59,130,246,0.2);
    }

    /* CARDS */
    .cards {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
      margin-top: 80px;
      position: relative;
      z-index: 2;
    }

    .card {
      width: 260px;
      padding: 25px;
      border-radius: 15px;
      background: rgba(255,255,255,0.06);
      backdrop-filter: blur(12px);
      text-align: center;
      transition: 0.3s;
      border: 1px solid rgba(255,255,255,0.1);
    }

    .card:hover {
      transform: translateY(-10px);
      background: rgba(59,130,246,0.2);
    }

    /* CONTACT */
    .contact {
      text-align: center;
      margin-top: 90px;
      padding-bottom: 80px;
      position: relative;
      z-index: 2;
    }

    .contact a {
      display: inline-block;
      margin: 10px;
      padding: 12px 20px;
      border-radius: 12px;
      text-decoration: none;
      color: white;
      background: rgba(255,255,255,0.08);
      transition: 0.3s;
    }

    .contact a:hover {
      background: #2563eb;
      transform: scale(1.1);
    }

  </style>

</head>

<body>

  <div class="glow"></div>

  <!-- NAV -->
  <nav>
    <h1>Arslan Studio</h1>

    <a href="https://www.instagram.com/arslan_muhammedanil?igsh=MTh4cjd1Mmdobjk4Nw==" target="_blank">
      Instagram
    </a>
  </nav>

  <!-- HERO -->
  <div class="hero">

    <h2>Modern Web Siteleri Tasarlıyoruz</h2>

    <p>
      Arslan Studio olarak modern, hızlı ve profesyonel web siteleri geliştiriyoruz.
      İşletmeler ve kişisel markalar için premium dijital çözümler sunuyoruz.
    </p>

    <div class="buttons">
      <button class="btn btn-primary">İletişim</button>
      <button class="btn btn-outline">Projeler</button>
    </div>

  </div>

  <!-- CARDS -->
  <div class="cards">

    <div class="card">
      <h3>Web Tasarım</h3>
      <p>Modern ve şık arayüzler</p>
    </div>

    <div class="card">
      <h3>Mobil Uyum</h3>
      <p>Tüm cihazlara uygun tasarım</p>
    </div>

    <div class="card">
      <h3>SEO & Hız</h3>
      <p>Google uyumlu hızlı siteler</p>
    </div>

  </div>

  <!-- CONTACT -->
  <div class="contact">

    <h3>İletişim</h3>

    <a href="mailto:ornek@gmail.com">Gmail</a>

    <a href="tel:+900000000000">Telefon</a>

    <a href="https://www.instagram.com/arslan_muhammedanil?igsh=MTh4cjd1Mmdobjk4Nw==" target="_blank">
      Instagram
    </a>

  </div>

</body>
</html>
