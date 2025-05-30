ZELIASTORE.ID
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Multifunctional Mop Holder with Hook - Produk Premium</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap');
  * {
    box-sizing: border-box;
  }
  body {
    font-family: 'Montserrat', sans-serif;
    margin: 0;
    background: #f9fafb;
    color: #222;
    line-height: 1.6;
  }
  header {
    background: linear-gradient(135deg, #4a90e2, #50e3c2);
    color: white;
    padding: 2rem 1rem;
    text-align: center;
  }
  header h1 {
    margin: 0;
    font-weight: 700;
    font-size: 2rem;
    letter-spacing: 1px;
    text-shadow: 0 1px 3px rgba(0,0,0,0.3);
  }
  header p.tagline {
    margin: 0.5rem 0 0;
    font-size: 1.2rem;
    font-style: italic;
    opacity: 0.9;
  }

  main {
    max-width: 960px;
    margin: 2rem auto;
    padding: 0 1rem;
  }

  .product-images {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(140px,1fr));
    gap: 1rem;
    margin-bottom: 2rem;
  }
  .product-images img {
    width: 100%;
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
    cursor: pointer;
  }
  .product-images img:hover {
    transform: scale(1.05);
  }

  section {
    margin-bottom: 2rem;
  }
  section h2 {
    font-weight: 700;
    color: #4a90e2;
    margin-bottom: 1rem;
    border-bottom: 3px solid #50e3c2;
    display: inline-block;
    padding-bottom: 0.2rem;
  }
  ul.features-list {
    list-style: none;
    padding-left: 0;
  }
  ul.features-list li {
    background: url('data:image/svg+xml;utf8,<svg fill="%234a90e2" height="14" viewBox="0 0 24 24" width="14" xmlns="http://www.w3.org/2000/svg"><path d="M9 16.2l-3.5-3.5L4 14l5 5 12-12-1.5-1.5z"/></svg>') no-repeat left center;
    padding-left: 24px;
    margin-bottom: 0.7rem;
    font-weight: 600;
  }

  .usage-steps {
    counter-reset: step-counter;
  }
  .usage-steps li {
    margin-bottom: 1rem;
    padding-left: 2.5rem;
    position: relative;
  }
  .usage-steps li::before {
    counter-increment: step-counter;
    content: counter(step-counter);
    position: absolute;
    left: 0;
    top: 0;
    background: #50e3c2;
    color: white;
    font-weight: 700;
    border-radius: 50%;
    width: 24px;
    height: 24px;
    line-height: 24px;
    text-align: center;
  }

  .testimonials {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
    gap: 1rem;
  }
  .testimonial-card {
    background: white;
    border-radius: 10px;
    box-shadow: 0 3px 10px rgb(0 0 0 / 0.1);
    padding: 1rem;
    font-style: italic;
  }
  .testimonial-card strong {
    display: block;
    margin-bottom: 0.5rem;
    font-style: normal;
    color: #4a90e2;
  }

  .urgency {
    background: #ffe4e1;
    border: 2px solid #ff3b3b;
    padding: 1rem;
    text-align: center;
    font-weight: 700;
    color: #d80000;
    font-size: 1.2rem;
    border-radius: 8px;
    margin-bottom: 2rem;
  }

  .dynamic-counters {
    display: flex;
    justify-content: center;
    gap: 2rem;
    margin-bottom: 2rem;
  }
  .counter {
    background: #4a90e2;
    color: white;
    border-radius: 8px;
    padding: 1rem 2rem;
    font-size: 1.2rem;
    font-weight: 700;
    min-width: 120px;
    text-align: center;
    box-shadow: 0 3px 7px rgba(0,0,0,0.2);
  }

  .countdown-timer {
    font-size: 1.3rem;
    font-weight: 700;
    text-align: center;
    margin-bottom: 2rem;
    color: #d80000;
    letter-spacing: 2px;
  }

  .price-banner {
    background: #50e3c2;
    color: #033;
    text-align: center;
    padding: 1rem;
    font-weight: 700;
    border-radius: 10px;
    margin: 2rem 0;
    box-shadow: 0 5px 15px rgba(80,227,194,0.5);
  }
  .price-banner del {
    color: #033;
    opacity: 0.6;
    margin-left: 1rem;
    font-weight: 500;
  }

  .cta-button {
    display: block;
    background: #4a90e2;
    color: white;
    font-weight: 700;
    text-align: center;
    padding: 1.3rem;
    border-radius: 8px;
    font-size: 1.3rem;
    text-decoration: none;
    max-width: 320px;
    margin: 0 auto 3rem;
    box-shadow: 0 5px 15px rgba(74,144,226,0.6);
    transition: background 0.3s ease;
  }
  .cta-button:hover {
    background: #357abd;
  }

  footer {
    text-align: center;
    color: #999;
    font-size: 0.9rem;
    padding-bottom: 1rem;
  }

  /* Responsive */
  @media (max-width: 600px) {
    .dynamic-counters {
      flex-direction: column;
      gap: 1rem;
    }
    .price-banner {
      font-size: 1rem;
    }
  }
</style>
</head>
<body>

<header>
  <h1>Multifunctional Mop Holder with Hook</h1>
  <p class="tagline">Solusi Praktis dan Rapi untuk Alat Kebersihan Anda!</p>
</header>

<main>
  <div class="product-images" aria-label="Gambar produk">
    <img src="https://cdn.fastcdnshop.com/image/09cdaf7c7a4416827d8b4c7c72076168f9be5db5-700.jpeg" alt="Multifunctional Mop Holder - foto utama" />
    <img src="https://cdn.fastcdnshop.com/image/e151475271efeb413ce032d5df1cd9f414964f26.gif" alt="Animasi penggunaan Multifunctional Mop Holder" />
    <img src="https://cdn.fastcdnshop.com/image/512cf98eeb7f0178c5d44d45a2321b4c11219464.webp" alt="Mop holder dalam berbagai sudut" />
    <img src="https://cdn.fastcdnshop.com/image/ae53b44079e4376ce12357b55acbdebb570fa50d.webp" alt="Detail hook Multifunctional Mop Holder" />
  </div>

  <section aria-labelledby="desc-heading">
    <h2 id="desc-heading">Deskripsi Produk</h2>
    <p>
      Multifunctional Mop Holder with Hook adalah solusi inovatif untuk menjaga kebersihan dan kerapihan alat-alat rumah tangga Anda. Dengan desain ergonomis dan bahan berkualitas, produk ini memudahkan Anda menyimpan sapu, pel, dan alat kebersihan lain secara rapi tanpa ribet.
    </p>
  </section>

  <section aria-labelledby="features-heading">
    <h2 id="features-heading">Fitur Utama</h2>
    <ul class="features-list">
      <li>Desain kuat dan tahan lama, dapat menahan berbagai jenis alat kebersihan</li>
      <li>Hook tambahan untuk gantungan kain lap atau alat kecil</li>
      <li>Mudah dipasang tanpa perlu alat khusus</li>
      <li>Anti slip dan tidak merusak dinding</li>
      <li>Material ramah lingkungan dan mudah dibersihkan</li>
    </ul>
  </section>

  <section aria-labelledby="usage-heading">
    <h2 id="usage-heading">Cara Penggunaan</h2>
    <ol class="usage-steps">
      <li>Pasang holder pada dinding di tempat yang diinginkan.</li>
      <li>Letakkan sapu atau pel di bagian penjepit yang tersedia.</li>
      <li>Gunakan hook tambahan untuk menggantung alat kecil lainnya.</li>
      <li>Nikmati ruang yang lebih rapi dan bersih.</li>
    </ol>
  </section>

  <section aria-labelledby="testi-heading">
    <h2 id="testi-heading">Testimoni Pelanggan</h2>
    <div class="testimonials">
      <div class="testimonial-card" role="article" aria-label="Testimoni dari Ibu Rini">
        <strong>Ibu Rini, 34 tahun</strong>
        <p>"Holder ini benar-benar memudahkan saya menyimpan alat kebersihan. Rumah jadi lebih rapi dan bersih. Pemasangannya juga mudah."</p>
      </div>
      <div class="testimonial-card" role="article" aria-label="Testimoni dari Mas Arif">
        <strong>Mas Arif, 28 tahun</strong>
        <p>"Bahan holder kuat dan hook-nya sangat membantu untuk gantung lap. Worth it banget buat harga segini."</p>
      </div>
      <div class="testimonial-card" role="article" aria-label="Testimoni dari Bu Dewi">
        <strong>Bu Dewi, 39 tahun</strong>
        <p>"Saya suka desainnya yang simpel dan tidak makan tempat. Kini alat kebersihan saya tidak berserakan lagi."</p>
      </div>
      <div class="testimonial-card" role="article" aria-label="Testimoni dari Pak Joko">
        <strong>Pak Joko, 42 tahun</strong>
        <p>"Pengiriman cepat dan produk sesuai gambar. Ini sangat membantu saya mengorganisir peralatan rumah."</p>
      </div>
    </div>
  </section>

  <div class="urgency" role="alert" aria-live="assertive" id="urgency">
    Hanya tersisa <span id="stock">15</span> stok! Promo berakhir dalam <span id="countdown">00:15:00</span> menit!
  </div>

  <div class="dynamic-counters" aria-label="Statistik pembelian">
    <div class="counter" aria-live="polite">Pengunjung sekarang: <span id="viewers">0</span></div>
    <div class="counter" aria-live="polite">Stok tersedia: <span id="stock-counter">15</span></div>
  </div>

  <div class="price-banner" aria-label="Harga produk">
    Harga Normal: <del>Rp247.500</del> &nbsp;&nbsp;&nbsp;
    Harga Spesial: <span style="font-size: 1.5rem; color:#033;">Rp165.000</span>
  </div>

  <a href="https://wa.me/+6287886635076" target="_blank" rel="noopener" class="cta-button" role="button" aria-label="Pesan Sekarang via WhatsApp">PESAN SEKARANG</a>

</main>

<footer>
  &copy; 2025 Multifunctional Mop Holder Indonesia
</footer>

<script>
  // Dynamic counters: viewers and stock
  let viewers = 20 + Math.floor(Math.random() * 50); // random between 20-70
  let stock = 15;
  const viewersEl = document.getElementById('viewers');
  const stockEl = document.getElementById('stock');
  const stockCounterEl = document.getElementById('stock-counter');
  const urgencyStockEl = document.getElementById('stock');

  function updateCounters() {
    // Simulate viewers fluctuation
    viewers += Math.floor(Math.random() * 5 - 2);
    if(viewers < 10) viewers = 10;
    if(viewers > 100) viewers = 100;
    viewersEl.textContent = viewers;

    // Stock decreases slowly over time randomly
    if(stock > 0 && Math.random() < 0.1) {
      stock--;
      stockEl.textContent = stock;
      stockCounterEl.textContent = stock;
    }
  }
  setInterval(updateCounters, 4000);
  updateCounters();

  // Countdown Timer (15 minutes)
  const countdownEl = document.getElementById('countdown');
  let countdownTime = 15 * 60; // 15 minutes in seconds

  function updateCountdown() {
    if(countdownTime <= 0) {
      countdownEl.textContent = "Waktu habis!";
      clearInterval(countdownInterval);
      return;
    }
    let minutes = Math.floor(countdownTime / 60);
    let seconds = countdownTime % 60;
    countdownEl.textContent = `00:${minutes.toString().padStart(2,'0')}:${seconds.toString().padStart(2,'0')}`;
    countdownTime--;
  }
  const countdownInterval = setInterval(updateCountdown, 1000);
  updateCountdown();

  // Redirect tab to form order on CTA click is via link directly to WhatsApp
</script>

</body>
</html>
