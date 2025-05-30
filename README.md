WELCOME TO ZELIASTORE.ID AND HAPPY SHOPPING
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🔥 Multifunctional Mop Holder - Solusi Praktis Rumah Bersih!</title>
    <meta name="description" content="Gantungan Sapu & Pel Multifungsi dengan 6 Hook - Hemat Tempat, Tahan Lama, Mudah Dipasang. PROMO TERBATAS!">
    
    <!-- Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: #333;
            overflow-x: hidden;
        }

        /* Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes pulse {
            0%, 100% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.05);
            }
        }

        @keyframes glow {
            0%, 100% {
                box-shadow: 0 0 20px rgba(255, 215, 0, 0.6);
            }
            50% {
                box-shadow: 0 0 40px rgba(255, 215, 0, 0.9);
            }
        }

        @keyframes floatUp {
            0%, 100% {
                transform: translateY(0px);
            }
            50% {
                transform: translateY(-10px);
            }
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header */
        .header {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(20px);
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            animation: fadeInUp 0.8s ease-out;
        }

        .nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
        }

        .logo {
            font-size: 24px;
            font-weight: 800;
            background: linear-gradient(135deg, #667eea, #764ba2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .stats {
            display: flex;
            gap: 30px;
            font-size: 14px;
            color: #666;
        }

        .stat-item {
            display: flex;
            align-items: center;
            gap: 5px;
        }

        .stat-number {
            font-weight: 700;
            color: #e74c3c;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, rgba(102, 126, 234, 0.9), rgba(118, 75, 162, 0.9));
            color: white;
            padding: 80px 0;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><pattern id="grain" width="100" height="100" patternUnits="userSpaceOnUse"><circle cx="25" cy="25" r="1" fill="rgba(255,255,255,0.1)"/><circle cx="75" cy="75" r="1" fill="rgba(255,255,255,0.1)"/><circle cx="50" cy="10" r="0.5" fill="rgba(255,255,255,0.05)"/></pattern></defs><rect width="100" height="100" fill="url(%23grain)"/></svg>') repeat;
            opacity: 0.3;
        }

        .hero-content {
            position: relative;
            z-index: 2;
            animation: fadeInUp 1s ease-out;
        }

        .hero h1 {
            font-size: clamp(32px, 5vw, 56px);
            font-weight: 800;
            margin-bottom: 20px;
            line-height: 1.2;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }

        .hero-subtitle {
            font-size: clamp(18px, 3vw, 24px);
            margin-bottom: 30px;
            opacity: 0.9;
        }

        .hero-badge {
            display: inline-block;
            background: rgba(255, 255, 255, 0.2);
            padding: 10px 20px;
            border-radius: 50px;
            margin-bottom: 40px;
            backdrop-filter: blur(10px);
            animation: pulse 2s infinite;
        }

        /* Product Gallery */
        .product-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin: 40px 0;
        }

        .product-image {
            position: relative;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
            animation: floatUp 3s ease-in-out infinite;
        }

        .product-image:hover {
            transform: scale(1.05);
        }

        .product-image img {
            width: 100%;
            height: 300px;
            object-fit: cover;
        }

        /* CTA Buttons */
        .cta-button {
            display: inline-block;
            background: linear-gradient(135deg, #ff6b6b, #ee5a24);
            color: white;
            padding: 18px 40px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 700;
            font-size: 18px;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: all 0.3s ease;
            box-shadow: 0 10px 30px rgba(238, 90, 36, 0.4);
            animation: glow 2s infinite;
            position: relative;
            overflow: hidden;
        }

        .cta-button:before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.3), transparent);
            transition: left 0.5s;
        }

        .cta-button:hover:before {
            left: 100%;
        }

        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 40px rgba(238, 90, 36, 0.6);
        }

        /* Content Sections */
        .section {
            padding: 80px 0;
            background: white;
            margin: 40px 0;
            border-radius: 30px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.1);
            animation: fadeInUp 0.8s ease-out;
        }

        .section-title {
            text-align: center;
            font-size: clamp(28px, 4vw, 42px);
            font-weight: 800;
            margin-bottom: 50px;
            background: linear-gradient(135deg, #667eea, #764ba2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        /* Features */
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 40px;
            margin-top: 60px;
        }

        .feature-card {
            background: linear-gradient(135deg, #f8f9ff, #e8eeff);
            padding: 40px;
            border-radius: 20px;
            text-align: center;
            transition: transform 0.3s ease;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.05);
        }

        .feature-card:hover {
            transform: translateY(-10px);
        }

        .feature-icon {
            font-size: 60px;
            color: #667eea;
            margin-bottom: 20px;
        }

        .feature-title {
            font-size: 24px;
            font-weight: 700;
            margin-bottom: 15px;
            color: #333;
        }

        /* How to Use */
        .steps {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-top: 50px;
        }

        .step {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            padding: 30px;
            border-radius: 20px;
            text-align: center;
            transition: transform 0.3s ease;
        }

        .step:hover {
            transform: scale(1.05);
        }

        .step-number {
            font-size: 48px;
            font-weight: 800;
            margin-bottom: 15px;
            opacity: 0.7;
        }

        /* Testimonials */
        .testimonials {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
            margin-top: 50px;
        }

        .testimonial {
            background: white;
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            position: relative;
        }

        .testimonial::before {
            content: '"';
            font-size: 60px;
            color: #667eea;
            position: absolute;
            top: -10px;
            left: 20px;
            font-family: Georgia, serif;
        }

        .stars {
            color: #ffd700;
            font-size: 18px;
            margin-bottom: 15px;
        }

        .testimonial-text {
            font-style: italic;
            margin-bottom: 20px;
            line-height: 1.6;
        }

        .testimonial-author {
            font-weight: 700;
            color: #667eea;
        }

        /* Price Banner */
        .price-banner {
            background: linear-gradient(135deg, #ff6b6b, #ee5a24);
            color: white;
            padding: 60px 0;
            text-align: center;
            margin: 60px 0;
            border-radius: 30px;
            position: relative;
            overflow: hidden;
            animation: glow 3s infinite;
        }

        .price-banner::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: repeating-linear-gradient(
                45deg,
                transparent,
                transparent 2px,
                rgba(255, 255, 255, 0.1) 2px,
                rgba(255, 255, 255, 0.1) 4px
            );
            animation: floatUp 4s linear infinite;
        }

        .price-content {
            position: relative;
            z-index: 2;
        }

        .original-price {
            font-size: 24px;
            text-decoration: line-through;
            opacity: 0.7;
            margin-bottom: 10px;
        }

        .current-price {
            font-size: 48px;
            font-weight: 800;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }

        .discount-badge {
            background: rgba(255, 255, 255, 0.2);
            padding: 10px 20px;
            border-radius: 50px;
            font-weight: 700;
            margin-bottom: 30px;
            display: inline-block;
            backdrop-filter: blur(10px);
        }

        /* Countdown Timer */
        .countdown {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 40px 0;
        }

        .countdown-item {
            background: rgba(255, 255, 255, 0.2);
            padding: 20px;
            border-radius: 15px;
            text-align: center;
            backdrop-filter: blur(10px);
            min-width: 80px;
        }

        .countdown-number {
            font-size: 32px;
            font-weight: 800;
            display: block;
        }

        .countdown-label {
            font-size: 12px;
            opacity: 0.8;
            text-transform: uppercase;
        }

        /* Urgency Section */
        .urgency {
            background: linear-gradient(135deg, #e74c3c, #c0392b);
            color: white;
            padding: 40px 0;
            text-align: center;
            margin: 40px 0;
            border-radius: 20px;
            animation: pulse 2s infinite;
        }

        .urgency h3 {
            font-size: 28px;
            margin-bottom: 15px;
        }

        .stock-info {
            font-size: 18px;
            margin-bottom: 20px;
        }

        .stock-bar {
            background: rgba(255, 255, 255, 0.3);
            height: 20px;
            border-radius: 10px;
            margin: 20px auto;
            max-width: 300px;
            overflow: hidden;
        }

        .stock-fill {
            background: #ffd700;
            height: 100%;
            width: 23%;
            border-radius: 10px;
            animation: pulse 1s infinite;
        }

        /* Footer */
        .footer {
            background: #2c3e50;
            color: white;
            padding: 40px 0;
            text-align: center;
            margin-top: 60px;
        }

        /* Mobile Responsiveness */
        @media (max-width: 768px) {
            .container {
                padding: 0 15px;
            }

            .stats {
                gap: 15px;
            }

            .hero {
                padding: 60px 0;
            }

            .section {
                padding: 60px 0;
                margin: 20px 0;
            }

            .features-grid,
            .steps,
            .testimonials {
                grid-template-columns: 1fr;
                gap: 20px;
            }

            .countdown {
                gap: 10px;
            }

            .countdown-item {
                padding: 15px 10px;
                min-width: 60px;
            }

            .countdown-number {
                font-size: 24px;
            }

            .current-price {
                font-size: 36px;
            }
        }

        /* Floating Elements */
        .floating-whatsapp {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: #25d366;
            color: white;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 30px;
            z-index: 1000;
            animation: pulse 2s infinite;
            box-shadow: 0 5px 20px rgba(37, 211, 102, 0.5);
        }

        .floating-whatsapp:hover {
            transform: scale(1.1);
        }

        /* Loading Animation */
        .fade-in {
            animation: fadeInUp 0.8s ease-out forwards;
            opacity: 0;
        }
    </style>
</head>

<body>
    <!-- Header -->
    <header class="header">
        <div class="container">
            <nav class="nav">
                <div class="logo">🏠 HomeSmart</div>
                <div class="stats">
                    <div class="stat-item">
                        <i class="fas fa-eye"></i>
                        <span><span class="stat-number" id="viewers">1,247</span> melihat</span>
                    </div>
                    <div class="stat-item">
                        <i class="fas fa-box"></i>
                        <span>Stok: <span class="stat-number" id="stock">23</span></span>
                    </div>
                </div>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <div class="hero-content">
                <div class="hero-badge">🔥 PROMO TERBATAS HARI INI!</div>
                <h1>Multifunctional Mop Holder</h1>
                <p class="hero-subtitle">Solusi Praktis untuk Rumah Bersih & Rapi - Hemat Tempat, Tahan 10 Tahun!</p>
                
                <div class="product-gallery">
                    <div class="product-image">
                        <img src="https://cdn.fastcdnshop.com/image/09cdaf7c7a4416827d8b4c7c72076168f9be5db5-700.jpeg" alt="Multifunctional Mop Holder">
                    </div>
                    <div class="product-image">
                        <img src="https://cdn.fastcdnshop.com/image/e151475271efeb413ce032d5df1cd9f414964f26.gif" alt="Cara Penggunaan Mop Holder">
                    </div>
                    <div class="product-image">
                        <img src="https://cdn.fastcdnshop.com/image/512cf98eeb7f0178c5d44d45a2321b4c11219464.webp" alt="Mop Holder Installed">
                    </div>
                    <div class="product-image">
                        <img src="https://cdn.fastcdnshop.com/image/ae53b44079e4376ce12357b55acbdebb570fa50d.webp" alt="Mop Holder Features">
                    </div>
                </div>

                <a href="https://wa.me/+6287886635076" class="cta-button">
                    <i class="fab fa-whatsapp"></i> PESAN SEKARANG
                </a>
            </div>
        </div>
    </section>

    <!-- Product Description -->
    <section class="section fade-in">
        <div class="container">
            <h2 class="section-title">Kenapa Harus Multifunctional Mop Holder?</h2>
            <div style="text-align: center; font-size: 18px; line-height: 1.8; max-width: 800px; margin: 0 auto;">
                <p>Lelah dengan rumah yang berantakan karena sapu, pel, dan alat kebersihan berserakan? 
                <strong>Multifunctional Mop Holder</strong> adalah solusi revolusioner yang akan mengubah cara Anda mengorganisir peralatan rumah tangga!</p>
                
                <p style="margin-top: 30px;">Dengan desain premium dan teknologi perekat super kuat, produk ini mampu menahan beban hingga <strong>15kg</strong> 
                tanpa merusak dinding. Cocok untuk kamar mandi, dapur, gudang, atau area manapun di rumah Anda.</p>
            </div>
        </div>
    </section>

    <!-- Features -->
    <section class="section fade-in">
        <div class="container">
            <h2 class="section-title">Fitur Unggulan yang Bikin Hidup Lebih Mudah</h2>
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">🔧</div>
                    <h3 class="feature-title">6 Hook Multifungsi</h3>
                    <p>Dapat menggantung berbagai alat: sapu, pel, sikat, handuk, kunci, dan masih banyak lagi. Satu produk untuk semua kebutuhan!</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">💪</div>
                    <h3 class="feature-title">Super Kuat & Tahan Lama</h3>
                    <p>Material premium ABS + perekat nano technology yang mampu menahan beban 15kg. Garansi awet hingga 10 tahun!</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">⚡</div>
                    <h3 class="feature-title">Tanpa Bor & Paku</h3>
                    <p>Instalasi super mudah dalam 30 detik! Tidak merusak dinding, tidak perlu alat khusus. Sekali tempel, langsung kuat!</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">💧</div>
                    <h3 class="feature-title">100% Waterproof</h3>
                    <p>Anti air dan lembab, cocok untuk kamar mandi. Tahan segala cuaca dan kondisi ekstrem. Tidak akan rusak atau melepas!</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">🎨</div>
                    <h3 class="feature-title">Desain Modern</h3>
                    <p>Tampilan elegan yang cocok dengan dekorasi rumah modern. Tersedia warna abu-abu yang netral dan stylish.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">🏠</div>
                    <h3 class="feature-title">Hemat Ruang 90%</h3>
                    <p>Ubah ruangan berantakan jadi rapi dalam sekejap! Maksimalkan ruang dengan desain vertikal yang space-saving.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- How to Use -->
    <section class="section fade-in">
        <div class="container">
            <h2 class="section-title">Cara Pasang Super Mudah - Hanya 3 Langkah!</h2>
            <div class="steps">
                <div class="step">
                    <div class="step-number">1</div>
                    <h3>Bersihkan Permukaan</h3>
                    <p>Pastikan dinding bersih dan kering. Lap dengan kain untuk hasil tempel yang maksimal.</p>
                </div>
                <div class="step">
                    <div class="step-number">2</div>
                    <h3>Lepas & Tempel</h3>
                    <p>Lepas stiker pelindung, tempel pada dinding, tekan kuat selama 10 detik hingga merekat sempurna.</p>
                </div>
                <div class="step">
                    <div class="step-number">3</div>
                    <h3>Siap Digunakan!</h3>
                    <p>Tunggu 1 jam untuk hasil optimal, lalu gantung semua peralatan Anda. Selesai!</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="section fade-in">
        <div class="container">
            <h2 class="section-title">Apa Kata Pelanggan yang Sudah Membuktikan?</h2>
            <div class="testimonials">
                <div class="testimonial">
                    <div class="stars">⭐⭐⭐⭐⭐</div>
                    <p class="testimonial-text">MasyaAllah bagus banget! Kamar mandi yang tadinya berantakan jadi super rapi. Gampang banget pasangnya, ga perlu pake bor segala. Sudah 6 bulan masih kuat banget nempel di dinding!</p>
                    <div class="testimonial-author">- Siti Nurhaliza, Jakarta</div>
                </div>
                <div class="testimonial">
                    <div class="stars">⭐⭐⭐⭐⭐</div>
                    <p class="testimonial-text">Sebagai ibu rumah tangga, produk ini bener-bener life saver! Dapur jadi lebih organized, alat-alat kebersihan ga berserakan lagi. Worth it banget dengan harganya!</p>
                    <div class="testimonial-author">- Rina Wijaya, Surabaya</div>
                </div>
                <div class="testimonial">
                    <div class="stars">⭐⭐⭐⭐⭐</div>
                    <p class="testimonial-text">Kualitasnya premium, materialnya terasa solid. Udah dipake buat gantung sapu, pel, bahkan tas belanja. Tetap kuat! Recommended banget deh!</p>
                    <div class="testimonial-author">- Budi Santoso, Bandung</div>
                </div>
                <div class="testimonial">
                    <div class="stars">⭐⭐⭐⭐⭐</div>
                    <p class="testimonial-text">Desainnya bagus, cocok sama interior rumah modern saya. Yang paling suka, instalasi ga ribet dan ga bikin dinding rusak. Perfect!</p>
                    <div class="testimonial-author">- Maya Sari, Medan</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Price Banner -->
    <section class="price-banner fade-in">
        <div class="container">
            <div class="price-content">
                <h2 style="margin-bottom: 20px; font-size: 36px;">🔥 PROMO SHOCK PRICE HARI INI!</h2>
                <div class="original-price">Harga Normal: Rp 262.500</div>
                <div class="current-price">Rp 175.000</div>
                <div class="discount-badge">HEMAT 33% - HANYA HARI INI!</div>
                
                <div class="countdown">
                    <div class="countdown-item">
                        <span class="countdown-number" id="hours">23</span>
                        <span class="countdown-label">Jam</span>
                    </div>
                    <div class="countdown-item">
                        <span class="countdown-number" id="minutes">45</span>
                        <span class="countdown-label">Menit</span>
                    </div>
                    <div class="countdown-item">
                        <span class="countdown-number" id="seconds">30</span>
                        <span class="countdown-label">Detik</span>
                    </div>
                </div>
                
                <a href="https://wa.me/+6287886635076" class="cta-button">
                    <i class="fab fa-whatsapp"></i> BELI SEKARANG - GRATIS ONGKIR!
                </a>
            </div>
        </div>
    </section>

    <!-- Urgency -->
    <section class="urgency fade-in">
        <div class="container">
            <h3>⚠️ STOK TERBATAS - JANGAN SAMPAI KEHABISAN!</h3>
            <p class="stock-info">Sisa stok hari ini: <strong>23 unit</strong
