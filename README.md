<!DOCTYPE html>
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
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      color: #333;
    }
    header {
      position: sticky; 
      top: 0; 
      z-index: 999;
      background: white; 
      padding: 1rem;
      display: flex; 
      justify-content: space-between; 
      align-items: center;
      border-bottom: 1px solid #eee; 
      flex-wrap: wrap;
    }
    .logo {
      font-size: 1.5rem; 
      font-weight: bold;
      margin-bottom: 0.5rem;
    }
    nav {
      display: flex; 
      flex-wrap: wrap; 
      justify-content: center;
      width: 100%;
    }
    nav a {
      margin: 5px 8px; 
      text-decoration: none; 
      color: #333; 
      font-weight: 500;
      font-size: 0.9rem;
      padding: 5px;
    }
    .hero {
      background: #f5f5f5;
      text-align: center;
      padding: 40px 15px;
    }
    .hero h1 {
      font-size: 1.8rem;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 1rem;
      color: #555;
    }
    section {
      padding: 40px 15px;
    }
    h2 {
      font-size: 1.5rem;
      margin-bottom: 20px;
      text-align: center;
    }
    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 15px;
    }
    .product-card {
      background: white;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }
    .product-card:hover {
      transform: translateY(-5px);
    }
    .product-grid img {
      width: 100%; 
      height: 150px;
      object-fit: cover;
      border-bottom: 1px solid #eee;
    }
    .product-info {
      padding: 12px;
    }
    .product-info h3 {
      font-size: 0.95rem;
      margin-bottom: 5px;
    }
    .product-info p {
      font-size: 0.85rem;
      color: #666;
      margin-bottom: 8px;
    }
    .price {
      font-weight: bold;
      color: #2a6496;
    }
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 10px;
    }
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
    }

    /* Menu Toggle untuk Mobile */
    .menu-toggle {
      display: none;
      cursor: pointer;
      font-size: 1.5rem;
    }
    
    /* Responsiveness */
    @media (max-width: 768px) {
      header {
        flex-direction: row;
        align-items: center;
        padding: 0.8rem 1rem;
      }
      .logo {
        margin-bottom: 0;
      }
      nav {
        display: none;
        width: 100%;
        flex-direction: column;
        background: white;
        padding: 10px 0;
      }
      nav.active {
        display: flex;
      }
      nav a {
        padding: 10px 15px;
        border-bottom: 1px solid #eee;
      }
      .menu-toggle {
        display: block;
      }
      .hero h1 {
        font-size: 1.5rem;
      }
      .hero p {
        font-size: 0.9rem;
      }
      .product-grid {
        grid-template-columns: repeat(2, 1fr);
      }
      section {
        padding: 30px 10px;
      }
    }

    @media (max-width: 480px) {
      .product-grid {
        grid-template-columns: 1fr;
      }
      .product-card {
        max-width: 280px;
        margin: 0 auto;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">Toko Audio Hasan</div>
    <div class="menu-toggle">☰</div>
    <nav id="main-nav">
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
      <p>Produk audio berkualitas dengan harga terbaik untuk pengalaman mendengarkan sempurna</p>
    </div>
  </section>

  <section id="earphone">
    <div class="container">
      <h2>Earphone</h2>
      <div class="product-grid">
        <div class="product-card">
          <img src="https://ae01.alicdn.com/kf/Sfbd07154d4624730a4091b0728cb4044Q.jpg" alt="Earphone 1">
          <div class="product-info">
            <h3>Earphone Model X1</h3>
            <p>Sound signature balanced dengan bass yang dalam</p>
            <p class="price">Rp 350.000</p>
          </div>
        </div>
        <div class="product-card">
          <img src="https://ae01.alicdn.com/kf/Sb51db5532b834a85a4872e9cdb29ca62d.jpg" alt="Earphone 2">
          <div class="product-info">
            <h3>Earphone Pro 2</h3>
            <p>Driver hybrid untuk detail suara maksimal</p>
            <p class="price">Rp 550.000</p>
          </div>
        </div>
        <div class="product-card">
          <img src="https://ae01.alicdn.com/kf/Sd190d21580b0480cb8042e1b96f29437G.jpg" alt="Earphone 3">
          <div class="product-info">
            <h3>Earphone Bass+</h3>
            <p>Khusus untuk pecinta bass dengan kualitas tinggi</p>
            <p class="price">Rp 420.000</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="headphone">
    <div class="container">
      <h2>Headphone</h2>
      <div class="product-grid">
        <div class="product-card">
          <img src="https://m.media-amazon.com/images/I/61cez984qdL.jpg" alt="Headphone 1">
          <div class="product-info">
            <h3>Headphone Studio Pro</h3>
            <p>Monitoring profesional dengan noise isolation</p>
            <p class="price">Rp 1.200.000</p>
          </div>
        </div>
        <div class="product-card">
          <img src="https://m.media-amazon.com/images/I/71iBJ8MknGL._AC_UF894,1000_QL80_.jpg" alt="Headphone 2">
          <div class="product-info">
            <h3>Wireless Headphone</h3>
            <p>Bluetooth 5.0 dengan baterai tahan 30 jam</p>
            <p class="price">Rp 850.000</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="dac">
    <div class="container">
      <h2>DAC</h2>
      <div class="product-grid">
        <div class="product-card">
          <img src="https://ae01.alicdn.com/kf/Abe97a4184e864e248b852090a17d9e3bW.jpg" alt="DAC 1">
          <div class="product-info">
            <h3>Portable DAC V2</h3>
            <p>Meningkatkan kualitas audio dari smartphone</p>
            <p class="price">Rp 750.000</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="kabel">
    <div class="container">
      <h2>Kabel</h2>
      <div class="product-grid">
        <div class="product-card">
          <img src="https://images.tokopedia.net/img/cache/700/VqbcmM/2024/12/16/bfa3e743-99be-4d42-9ad5-dcd44af9a91c.jpg" alt="Kabel 1">
          <div class="product-info">
            <h3>Kabel Upgrade Silver</h3>
            <p>Meningkatkan detail dan soundstage</p>
            <p class="price">Rp 250.000</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="eartips">
    <div class="container">
      <h2>Eartips</h2>
      <div class="product-grid">
        <div class="product-card">
          <img src="https://m.media-amazon.com/images/I/51MAW4zJtuL._AC_UF894,1000_QL80_.jpg" alt="Eartips 1">
          <div class="product-info">
            <h3>Eartips Memory Foam</h3>
            <p>Nyaman dan isolasi suara maksimal</p>
            <p class="price">Rp 80.000</p>
          </div>
        </div>
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
      <p>Toko Audio Hasan berkomitmen untuk menyediakan peralatan audio berkualitas tinggi dengan harga terjangkau. Kami percaya setiap orang berhak menikmati pengalaman mendengarkan musik yang premium.</p>
      <p style="margin-top: 15px;"><strong>Hubungi Kami:</strong><br>
      Email: info@tokoaudiohasan.com<br>
      WhatsApp: 0812-3456-7890</p>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2023 Toko Audio Hasan. Semua hak dilindungi.</p>
    </div>
  </footer>

  <script>
    // Menu toggle untuk mobile
    document.querySelector('.menu-toggle').addEventListener('click', function() {
      const nav = document.getElementById('main-nav');
      nav.classList.toggle('active');
    });
    
    // Tutup menu saat item diklik (untuk mobile)
    document.querySelectorAll('nav a').forEach(item => {
      item.addEventListener('click', () => {
        const nav = document.getElementById('main-nav');
        if (window.innerWidth <= 768) {
          nav.classList.remove('active');
        }
      });
    });
  </script>
</body>
</html>
