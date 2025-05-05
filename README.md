# Gaming-website-
Gaming
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gaming Channel</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      background-color: #0d0d0d;
      color: #f2f2f2;
      font-family: 'Orbitron', sans-serif;
    }
    header {
      background-color: #1a1a1a;
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 2px solid #00ffcc;
    }
    header h1 {
      margin: 0;
      color: #00ffcc;
    }
    nav a {
      color: #f2f2f2;
      margin-left: 20px;
      text-decoration: none;
    }
    nav a:hover {
      color: #00ffcc;
    }
    .hero {
      text-align: center;
      padding: 100px 20px;
      background-image: url('https://i.imgur.com/3ZQ3ZbD.jpg');
      background-size: cover;
      background-position: center;
      background-blend-mode: overlay;
      background-color: rgba(0, 0, 0, 0.7);
    }
    .hero h2 {
      font-size: 48px;
      margin-bottom: 20px;
      color: #00ffcc;
    }
    .hero p {
      font-size: 20px;
    }
    .videos, .social {
      padding: 40px 20px;
      text-align: center;
    }
    .video-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }
    .video {
      background-color: #1a1a1a;
      padding: 10px;
      border: 1px solid #00ffcc;
      border-radius: 10px;
    }
    footer {
      background-color: #111;
      text-align: center;
      padding: 20px;
      border-top: 2px solid #00ffcc;
    }
  </style>
</head>
<body>
  <header>
    <h1>GamerZone</h1>
    <nav>
      <a href="#">خانه</a>
      <a href="#videos">ویدیوها</a>
      <a href="#about">درباره</a>
      <a href="#contact">تماس</a>
    </nav>
  </header>

  <section class="hero">
    <h2>به دنیای گیم خوش آمدید!</h2>
    <p>جای بازی، هیجان و لحظات خنده‌دار با گیم‌های برتر روز</p>
  </section>

  <section class="videos" id="videos">
    <h2>آخرین ویدیوها</h2>
    <div class="video-grid">
      <div class="video">
        <iframe width="100%" height="160" src="https://www.youtube.com/embed/VIDEO_ID_1" frameborder="0" allowfullscreen></iframe>
        <p>عنوان ویدیو ۱</p>
      </div>
      <div class="video">
        <iframe width="100%" height="160" src="https://www.youtube.com/embed/VIDEO_ID_2" frameborder="0" allowfullscreen></iframe>
        <p>عنوان ویدیو ۲</p>
      </div>
    </div>
  </section>

  <section class="social">
    <h2>ما را دنبال کنید</h2>
    <p>
      <a href="#" style="color:#00ffcc;">یوتیوب</a> |
      <a href="#" style="color:#00ffcc;">اینستاگرام</a> |
      <a href="#" style="color:#00ffcc;">دیسکورد</a>
    </p>
  </section>

  <footer>
    <p>© 2025 GamerZone - همه حقوق محفوظ است</p>
  </footer>
</body>
</html>
