<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Toko Audio Hasan</title>
  <style>
    * {
      margin: 0; padding: 0; box-sizing: border-box; scroll-behavior: smooth;
    }
    body {
      font-family: 'Segoe UI', sans-serif; line-height: 1.6;
    }
    header {
      position: sticky; top: 0; z-index: 999;
      background: white; padding: 1rem 2rem;
      display: flex; justify-content: space-between; align-items: center;
      border-bottom: 1px solid #eee; flex-wrap: wrap;
    }
    .logo {
      font-size: 1.5em; font-weight: bold;
    }
    nav {
      display: flex; flex-wrap: wrap; justify-content: center;
    }
    nav a {
      margin: 5px 10px; text-decoration: none; color: #333; font-weight: 500;
    }
    .hero {
      background: #f5f5f5;
      text-align: center;
      padding: 60px 20px;
    }
    .hero h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 1.2em;
      color: #555;
    }
    section {
      padding: 60px 20px;
    }
    h2 {
      font-size: 2em;
      margin-bottom: 20px;
    }
    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 20px;
    }
    .product-grid img {
      width: 100%; 
      border-radius: 10px;
      border: 1px solid #ddd; /* Border untuk semua gambar produk */
      box-shadow: 0 2px 5px rgba(0,0,0,0.1); /* Shadow ringan untuk efek depth */
      padding: 5px; /* Jarak antara border dan gambar */
      background: white; /* Background putih untuk gambar dengan transparansi */
      transition: all 0.3s ease; /* Animasi hover */
    }
    .product-grid img:hover {
      transform: scale(1.02); /* Efek zoom kecil saat hover */
      box-shadow: 0 5px 15px rgba(0,0,0,0.1); /* Shadow lebih tebal saat hover */
    }

    .container {
      max-width: 1200px;
      margin: 0 auto;
    }

    /* Responsiveness */
    @media (max-width: 768px) {
      header {
        flex-direction: column;
        align-items: flex-start;
      }
      .hero h1 {
        font-size: 2em;
      }
      .hero p {
        font-size: 1em;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">焰雨</div>
    <nav>
      <a href="#earphone">Earphone</a>
      <a href="#headphone">Headphone</a>
      <a href="#dac">DAC</a>
      <a href="#kabel">Kabel</a>
      <a href="#eartips">Eartips</a>
      <a href="#keranjang">Keranjang</a>
      <a href="#tentang">Tentang Kami</a>
    </nav>
  </header>

  <section class="hero">
    <div class="container">
      <h1>Selamat Datang di Toko Audio Hasan</h1>
      <p>Kami menyediakan produk audio terbaik: earphone, headphone, DAC, kabel, dan aksesori lainnya dengan kualitas tinggi dan harga bersaing.</p>
    </div>
  </section>

  <section id="earphone">
    <div class="container">
      <h2>Earphone</h2>
      <div class="product-grid">
        <img src="https://ae01.alicdn.com/kf/Sfbd07154d4624730a4091b0728cb4044Q.jpg" alt="Earphone 1">
        <img src="https://ae01.alicdn.com/kf/Sb51db5532b834a85a4872e9cdb29ca62d.jpg" alt="Earphone 2">
        <img src="https://ae01.alicdn.com/kf/Sd190d21580b0480cb8042e1b96f29437G.jpg" alt="Earphone 3">
      </div>
    </div>
  </section>

  <section id="headphone">
    <div class="container">
      <h2>Headphone</h2>
      <div class="product-grid">
        <img src="https://m.media-amazon.com/images/I/61cez984qdL.jpg" alt="Headphone 1">
        <img src="https://m.media-amazon.com/images/I/71iBJ8MknGL._AC_UF894,1000_QL80_.jpg" alt="Headphone 2">
        <img src="https://cdn.prod.website-files.com/627128d862c9a44234848dda/676410ed82ea45da46ff78e8_edge.jpg" alt="Headphone 3">
      </div>
    </div>
  </section>

  <section id="dac">
    <div class="container">
      <h2>DAC</h2>
      <div class="product-grid">
        <img src="https://ae01.alicdn.com/kf/Abe97a4184e864e248b852090a17d9e3bW.jpg" alt="DAC 1">
        <img src="https://m.media-amazon.com/images/I/61n2pPgtIRL.jpg" alt="DAC 2">
      </div>
    </div>
  </section>

  <section id="kabel">
    <div class="container">
      <h2>Kabel</h2>
      <div class="product-grid">
        <img src="https://images.tokopedia.net/img/cache/700/VqbcmM/2024/12/16/bfa3e743-99be-4d42-9ad5-dcd44af9a91c.jpg" alt="Kabel 1">
        <img src="https://www.static-src.com/wcsstore/Indraprastha/images/catalog/full//86/MTA-6462221/tfz_tfz_tc-1_upgrade_cable_silver_plated_-_single_crystal_copper_-_4-4mm_full04_g6khjt9c.jpg" alt="Kabel 2">
      </div>
    </div>
  </section>

  <section id="eartips">
    <div class="container">
      <h2>Eartips</h2>
      <div class="product-grid">
        <img src="https://m.media-amazon.com/images/I/51MAW4zJtuL._AC_UF894,1000_QL80_.jpg" alt="Eartips 1">
        <img src="https://m.media-amazon.com/images/I/41b7xIfa0cL.jpg" alt="Eartips 2">
      </div>
    </div>
  </section>

  <section id="keranjang">
    <div class="container">
      <h2>Keranjang</h2>
      <p>Keranjang belanja Anda masih kosong.</p>
    </div>
  </section>

  <section id="tentang">
    <div class="container">
      <h2>Tentang Kami</h2>
      <p>Kami adalah penyedia perlengkapan audio berkualitas tinggi yang berdedikasi untuk menghadirkan suara terbaik bagi pelanggan kami.</p>
    </div>
  </section>
</body>
</html>
