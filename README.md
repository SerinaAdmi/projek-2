<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <title>Portofolio Coffee-in</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet" />
  <style>
    * { box-sizing: border-box; }
    body {
      font-family: "Poppins", sans-serif;
      background: #fff5ea;
      padding: 20px;
      color: #333;
    }
    .section { margin-bottom: 40px; }
    h2 {
      font-size: 28px;
      margin-bottom: 10px;
      color: #5c2c06;
    }
    h2 img {
      width: 50px;
      vertical-align: middle;
      margin-right: 10px;
    }
    /* Logo + Tentang */
    #tentang p {
      font-size: 16px;
      color: #444;
    }
    /* Menu / Proyek */
    .project {
      border: 1px solid #b5691e;
      padding: 15px;
      margin: 15px 0;
      transition: transform 0.3s;
      border-radius: 8px;
      background: #fffaf3;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    }
    .project:hover {
      transform: scale(1.03);
      background-color: #fff3dc;
    }
    .judul {
      font-weight: bold;
      font-size: 18px;
      margin-bottom: 10px;
      color: #8b4513;
    }
    .project img {
      width: 100%;
      max-width: 300px;
      border-radius: 10px;
      display: block;
      margin-bottom: 10px;
    }

    /* Kontak */
    #kontak p {
      background: #fff;
      padding: 12px;
      border-left: 4px solid #8b4513;
      border-radius: 6px;
      margin-bottom: 10px;
      box-shadow: 0 1px 3px rgba(0,0,0,0.1);
    }
    #kontak a {
      color: #8b4513;
      text-decoration: none;
    }
    #kontak a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      margin-top: 50px;
      font-size: 14px;
      color: #666;
    }
  </style>
</head>
<body>

  <!-- ✅ Logo & Tentang -->
  <section class="section" id="tentang">
    <h2>
      <img src="https://cdn-icons-png.flaticon.com/512/2935/2935417.png" alt="Logo Coffee-in" />
      Coffee-in
    </h2>
    <p>The Best Coffee in Lambung*</p>
  </section>

  <!-- ✅ Menu -->
  <section class="section" id="proyek">
    <h2>Menu</h2>

    <div class="project">
      <div class="judul">Espresso</div>
      <img src="https://images.unsplash.com/photo-1605478371236-377aae3dc32e?auto=format&fit=crop&w=600&q=80" alt="Espresso" />
      <p>Kata espresso berasal dari kata Italia yang berarti “ditekan”. Biji kopi yang telah digiling halus dimasukkan ke dalam portafilter, ditekan, lalu dialirkan air panas bertekanan tinggi.</p>
    </div>

    <div class="project">
      <div class="judul">Macchiato</div>
      <img src="https://images.unsplash.com/photo-1541167760496-1628856ab772?auto=format&fit=crop&w=600&q=80" alt="Macchiato" />
      <p>Macchiato adalah espresso dengan sedikit susu berbusa. Cocok bagi kamu yang suka espresso tapi ingin sentuhan lembut dari susu.</p>
    </div>

    <div class="project">
      <div class="judul">Kopi Latte</div>
      <img src="https://images.unsplash.com/photo-1568912494257-029d1933a058?auto=format&fit=crop&w=600&q=80" alt="Kopi Latte" />
      <p>Latte terdiri dari espresso, steamed milk, dan foam tipis di atasnya. Rasanya creamy dan cocok untuk santai.</p>
    </div>
  </section>

  <!-- ✅ Kontak -->
  <section class="section" id="kontak">
    <h2>Kontak Kami</h2>
    <p><strong>📍 Alamat:</strong> Jl. Kopi No. 17, Lambung City</p>
    <p><strong>☎️ Telepon:</strong> 0812-3456-7890</p>
    <p><strong>✉️ Email:</strong> coffeein.lambung@gmail.com</p>
    <p><strong>🕒 Jam Buka:</strong> Senin - Minggu, 08.00 - 22.00</p>
    <p><strong>🌐 Instagram:</strong> <a href="https://instagram.com/coffeein.id" target="_blank">@coffeein.id</a></p>
  </section>

  <footer>
    &copy; 2025 Coffee-in. All rights reserved.
  </footer>

</body>
</html>
