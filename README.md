<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Audio Store</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Segoe UI', sans-serif; }

    /* Navbar */
    header {
      background: #fff;
      padding: 15px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #eee;
      position: sticky;
      top: 0;
      z-index: 999;
    }

    .logo {
      font-size: 1.5em;
      font-weight: bold;
    }

    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #333;
      font-weight: 500;
    }

    /* Hero Slider */
    .slider {
      display: flex;
      overflow: hidden;
      position: relative;
      height: 100vh;
      background: #f8f8f8;
    }

    .slide {
      min-width: 100%;
      display: flex;
      align-items: center;
      justify-content: space-around;
      padding: 50px;
      transition: 0.5s ease;
    }

    .slide img {
      max-width: 400px;
      border-radius: 20px;
    }

    .slide-content {
      max-width: 500px;
    }

    .slide-content h1 {
      font-size: 2em;
      margin-bottom: 15px;
    }

    .slide-content p {
      margin-bottom: 20px;
      font-size: 1.1em;
    }

    .btn {
      padding: 10px 20px;
      background: black;
      color: white;
      border: none;
      border-radius: 20px;
      cursor: pointer;
    }

    /* Arrows */
    .arrow {
      position: absolute;
      top: 50%;
      transform: translateY(-50%);
      font-size: 2em;
      color: #444;
      background: rgba(255,255,255,0.7);
      border-radius: 50%;
      width: 40px;
      height: 40px;
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      z-index: 1;
    }

    .left-arrow { left: 10px; }
    .right-arrow { right: 10px; }
  </style>
</head>
<body>

  <!-- Navbar -->
  <header>
    <div class="logo">焰雨</div>
    <nav>
      <a href="#smartphone">Smartphone</a>
      <a href="#audio">Pro Audio</a>
      <a href="#tws">TWS</a>
      <a href="#collabs">Collabs</a>
      <a href="#keyboard">Keyboards</a>
      <a href="#about">About Us</a>
      <a href="#support">Support</a>
    </nav>
  </header>

  <!-- Hero Slider -->
  <section class="slider" id="beranda">
    <div class="arrow left-arrow" onclick="prevSlide()">&#10094;</div>
    <div class="arrow right-arrow" onclick="nextSlide()">&#10095;</div>

    <div class="slide" id="slide1">
      <img src="https://i.imgur.com/wVnS9NQ.png" alt="Robin Character">
      <div class="slide-content">
        <h1>Nice to meet you, I'm Robin!</h1>
        <p>Dear Trailblazers, get ready to immerse yourself in dynamic melodies with Robin!</p>
        <button class="btn">Learn More</button>
      </div>
    </div>

    <div class="slide" id="slide2">
      <img src="https://via.placeholder.com/400x500?text=Product+2" alt="Product 2">
      <div class="slide-content">
        <h1>New Audio Series</h1>
        <p>High-fidelity audio experience with cutting-edge technology and elegant design.</p>
        <button class="btn">Explore Now</button>
      </div>
    </div>

  </section>

  <script>
    let currentIndex = 0;
    const slides = document.querySelectorAll('.slide');

    function showSlide(index) {
      slides.forEach((slide, i) => {
        slide.style.transform = `translateX(-${index * 100}%)`;
      });
    }

    function nextSlide() {
      currentIndex = (currentIndex + 1) % slides.length;
      showSlide(currentIndex);
    }

    function prevSlide() {
      currentIndex = (currentIndex - 1 + slides.length) % slides.length;
      showSlide(currentIndex);
    }

    // Optional: auto-slide every 6s
    setInterval(nextSlide, 6000);
  </script>

</body>
</html>
