# M.Hasan.github.io
Marketplaceodio
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Marketplace Audio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      scroll-behavior: smooth;
    }
    header {
      background: #111;
      color: white;
      padding: 20px;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 10px;
      font-weight: bold;
    }
    section {
      padding: 60px 20px;
      min-height: 100vh;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1585386959984-a41552264cf5?ixlib=rb-4.0.3&auto=format&fit=crop&w=1350&q=80') center/cover;
      color: white;
      text-align: center;
    }
    .hero h1 {
      font-size: 3em;
      margin-top: 100px;
    }
    .section-title {
      text-align: center;
      font-size: 2em;
      margin-bottom: 20px;
    }
    .produk-grid {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .produk {
      background: #f0f0f0;
      padding: 10px;
      border-radius: 10px;
      width: 200px;
      text-align: center;
    }
    .produk img {
      width: 100%;
      border-radius: 10px;
    }
    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>

<header>
  <nav>
    <a href="#beranda">Beranda</a>
    <a href="#tentang">Tentang Kami</a>
    <a href="#produk">Produk Kami</a>
    <a href="#promo">Promo</a>
    <a href="#testimoni">Testimoni</a>
    <a href="#kontak">Kontak</a>
    <a href="#faq">FAQ</a>
  </nav>
</header>

<section id="beranda" class="hero">
  <h1>Marketplace Audio</h1>
  <p>Temukan audio gear terbaik untukmu</p>
</section>

<section id="tentang">
  <h2 class="section-title">Tentang Kami</h2>
  <p style="max-width: 600px; margin: auto;">Kami adalah toko audio online yang menyediakan berbagai jenis headphone, speaker, dan perangkat audio profesional dari berbagai brand ternama.</p>
</section>

<section id="produk">
  <h2 class="section-title">Produk Kami</h2>
  <div class="produk-grid">
    <div class="produk">
      <img src="https://via.placeholder.com/200x150" alt="Produk 1">
      <h4>Headphone Pro</h4>
      <p>Rp750.000</p>
    </div>
    <div class="produk">
      <img src="https://via.placeholder.com/200x150" alt="Produk 2">
      <h4>Speaker Bluetooth</h4>
      <p>Rp500.000</p>
    </div>
    <div class="produk">
      <img src="https://via.placeholder.com/200x150" alt="Produk 3">
      <h4>Soundbar X</h4>
      <p>Rp1.250.000</p>
    </div>
  </div>
</section>

<section id="promo">
  <h2 class="section-title">Promo</h2>
  <p style="text-align: center;">Diskon 20% untuk pembelian pertama! Gunakan kode: <strong>AUDIO20</strong></p>
</section>

<section id="testimoni">
  <h2 class="section-title">Testimoni</h2>
  <p style="max-width: 600px; margin: auto;">"Kualitas produk sangat memuaskan! Pengiriman cepat dan pelayanan ramah." - <strong>Rina, Jakarta</strong></p>
</section>

<section id="kontak">
  <h2 class="section-title">Kontak</h2>
  <p style="text-align: center;">📞 0812-3456-7890 | ✉️ audiomarketplace@gmail.com</p>
  <p style="text-align: center;">📍 Jl. Audio No.1, Bandung</p>
</section>

<section id="faq">
  <h2 class="section-title">FAQ</h2>
  <p style="max-width: 600px; margin: auto;">
    <strong>Q:</strong> Apakah bisa COD?<br>
    <strong>A:</strong> Ya, kami melayani COD untuk wilayah Jabodetabek.
  </p>
</section>

<footer>
  <p>&copy; 2025 Marketplace Audio. All rights reserved.</p>
</footer>

</body>
</html>
