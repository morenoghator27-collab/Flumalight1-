# Flumalight1-
<!doctype html>

<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Fluma Light — Lilin Aromaterapi dari Minyak Jelantah</title>
  <meta name="description" content="Fluma Light: lilin aromaterapi ramah lingkungan yang dibuat dari minyak goreng bekas. Nyaman, wangi, dan berkelanjutan." />
  <style>
    :root{
      --accent:#F59E0B;
      --muted:#6B7280;
      --bg:#fafaf9;
      --card:#ffffff;
      --radius:14px;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:var(--bg);color:#111;line-height:1.5}
    header{background:linear-gradient(90deg,#fff 0%, rgba(245,158,11,0.05)100%);padding:18px 24px;position:sticky;top:0;z-index:40;border-bottom:1px solid rgba(16,24,40,0.04)}
    .container{max-width:1100px;margin:0 auto;padding:24px}
    .nav{display:flex;gap:18px;align-items:center;justify-content:space-between}
    .brand{display:flex;gap:12px;align-items:center;font-weight:700}
    .brand .logo{width:42px;height:42px;border-radius:10px;display:grid;place-items:center;background:linear-gradient(135deg,#FDE68A,#F59E0B);color:#111}
    nav a{color:var(--muted);text-decoration:none;font-weight:600}
    .hero{display:grid;grid-template-columns:1fr 420px;gap:32px;align-items:center;padding:48px 0}
    .hero h1{font-size:2.2rem;margin:0 0 12px}
    .lead{color:var(--muted);margin-bottom:18px}
    .cta{display:inline-block;background:var(--accent);color:#111;padding:12px 18px;border-radius:10px;font-weight:700;text-decoration:none}
    .product-card{background:var(--card);border-radius:var(--radius);box-shadow:0 6px 20px rgba(16,24,40,0.06);padding:18px}
    .features{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-top:18px}
    .feature{background:#fff;padding:14px;border-radius:12px;border:1px solid rgba(16,24,40,0.03)}
    .swot{display:grid;grid-template-columns:1fr 1fr;gap:18px;margin-top:28px}
    .swot > div{background:#fff;padding:18px;border-radius:12px;border:1px solid rgba(16,24,40,0.04)}
    .swot h3{margin-top:0}
    .grid-2{display:grid;grid-template-columns:1fr 1fr;gap:18px}
    .faq{margin-top:18px}
    footer{margin-top:36px;padding:24px 0;color:var(--muted);text-align:center}
    /* Responsive */
    @media (max-width:900px){
      .hero{grid-template-columns:1fr;}
      .features{grid-template-columns:repeat(2,1fr)}
      .swot{grid-template-columns:1fr}
      .grid-2{grid-template-columns:1fr}
    }
    @media (max-width:520px){
      .features{grid-template-columns:1fr}
    }
    /* small utilities */
    .muted{color:var(--muted)}
    .pill{display:inline-block;padding:6px 10px;border-radius:999px;background:rgba(245,158,11,0.08);font-weight:700}
    .tag{font-size:0.9rem;color:var(--muted)}
    .contact-form input,.contact-form textarea{width:100%;padding:10px;border-radius:8px;border:1px solid rgba(16,24,40,0.06);margin-bottom:10px}
    .btn{display:inline-block;padding:10px 14px;border-radius:10px;background:var(--accent);font-weight:700}
  </style>
</head>
<body>
  <header>
    <div class="container nav">
      <div class="brand">
        <div class="logo" aria-hidden>FL</div>
        <div>
          <div>Fluma Light</div>
          <div class="tag">Sustainably scented</div>
        </div>
      </div>
      <nav aria-label="Main navigation">
        <a href="#about">Tentang</a> &nbsp; 
        <a href="#features">Keunggulan</a> &nbsp; 
        <a href="#swot">SWOT</a> &nbsp;
        <a href="#contact">Kontak</a>
      </nav>
    </div>
  </header>  <main class="container">
    <section class="hero" aria-labelledby="hero-title">
      <div>
        <p class="pill">Produk Ramah Lingkungan</p>
        <h1 id="hero-title">Fluma Light — Lilin Aromaterapi dari Minyak Jelantah</h1>
        <p class="lead">Fluma Light memanfaatkan minyak goreng bekas (minyak jelantah) yang diolah, difiltrasi dan diproses menjadi lilin aromaterapi berkualitas — wangi tahan lama, pembakaran bersih, dan ramah lingkungan.</p>
        <a class="cta" href="#contact">Pesan Sekarang</a><div class="features" id="features" style="margin-top:22px">
      <div class="feature">
        <strong>100% Daur Ulang</strong>
        <div class="muted">Mengurangi limbah minyak rumah tangga dan industri kecil.</div>
      </div>
      <div class="feature">
        <strong>Wangi Terpilih</strong>
        <div class="muted">Perpaduan essential oil untuk suasana relaksasi.</div>
      </div>
      <div class="feature">
        <strong>Pembakaran Bersih</strong>
        <div class="muted">Perlakuan khusus agar nyala stabil dan asap minimal.</div>
      </div>
    </div>
  </div>

  <aside class="product-card" aria-label="Gambaran produk">
    <img src="https://images.unsplash.com/photo-1508739773434-c26b3d09e071?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Fluma Light — contoh lilin" style="width:100%;border-radius:10px;object-fit:cover;height:220px;margin-bottom:12px">
    <h3>Varian &amp; Harga</h3>
    <ul class="muted">
      <li>Mini (120 ml) — Rp 35.000</li>
      <li>Standard (250 ml) — Rp 60.000</li>
      <li>Premium (450 ml, kotak kado) — Rp 120.000</li>
    </ul>
    <div style="margin-top:12px">
      <strong>Pesan untuk acara?</strong>
      <div class="muted">Bulk order &amp; kustom aroma tersedia.</div>
    </div>
  </aside>
</section>

<section id="about" style="margin-top:28px">
  <div class="grid-2">
    <div class="product-card">
      <h3>Apa itu Fluma Light?</h3>
      <p class="muted">Fluma Light adalah proyek sosial + bisnis yang mengubah minyak goreng bekas menjadi lilin aromaterapi berkualitas. Fokus kami: meminimalkan limbah, membuka peluang ekonomi mikro, dan memberi konsumen alternatif produk rumah tangga lebih berkelanjutan.</p>
      <ul class="muted">
        <li>Proses filtrasi multi-tahap</li>
        <li>Campuran essential oil pilihan</li>
        <li>Paket ramah lingkungan (kertas &amp; kaca)</li>
      </ul>
    </div>

    <div class="product-card">
      <h3>Bagaimana Cara Kerjanya?</h3>
      <ol class="muted">
        <li>Kumpulkan minyak jelantah dari mitra rumah tangga/warung.</li>
        <li>Filtrasi &amp; netralisasi bau dasar.</li>
        <li>Campur dengan bahan bantu pembakar dan essential oil.</li>
        <li>Tuang ke wadah, uji pembakaran, kemas.</li>
      </ol>
    </div>
  </div>
</section>

<section id="swot" style="margin-top:28px">
  <h2>SWOT Singkat</h2>
  <div class="swot">
    <div>
      <h3>Strengths (Kekuatan)</h3>
      <ul class="muted">
        <li>Unik: Bahan baku dari minyak jelantah — cerita sustainability yang kuat.</li>
        <li>Biaya bahan rendah sehingga margin fleksibel.</li>
        <li>Nilai sosial: memberdayakan mitra pengumpul skala kecil.</li>
        <li><strong>Keunikan khusus:</strong> Teknik penyaringan dan formula aroma proprietary yang menghasilkan bau dasar netral sehingga aroma utama essential oil terasa murni — sulit ditiru tanpa proses khusus.</li>
      </ul>
    </div>
    <div>
      <h3>Weaknesses (Kelemahan)</h3>
      <ul class="muted">
        <li>Stigma awal tentang minyak bekas — butuh edukasi pelanggan.</li>
        <li>Skala produksi bergantung pada pasokan minyak jelantah berkualitas.</li>
      </ul>
    </div>
  </div>

  <div class="swot" style="margin-top:12px">
    <div>
      <h3>Opportunities (Peluang)</h3>
      <ul class="muted">
        <li>Kolaborasi kafe &amp; restoran untuk pasokan dan branding bersama.</li>
        <li>Pasar hadiah ramah lingkungan &amp; corporate gifting.</li>
      </ul>
    </div>
    <div>
      <h3>Threats (Ancaman)</h3>
      <ul class="muted">
        <li>Pesaing dengan brand besar yang punya modal marketing.</li>
        <li>Peraturan sanitasi atau bahan baku yang tiba-tiba berubah.</li>
      </ul>
    </div>
  </div>
</section>

<section class="faq" aria-labelledby="faq-title">
  <h2 id="faq-title">Pertanyaan Umum</h2>
  <div class="product-card">
    <p><strong>Apakah aman memakai lilin dari minyak bekas?</strong></p>
    <p class="muted">Ya — setelah melalui proses pemurnian dan penambahan bahan pembantu, produk diuji untuk memastikan pembakaran bersih. Kami melakukan uji laboratorium internal dan pengujian pembakaran rutin.</p>

    <p><strong>Bagaimana aroma terbentuk?</strong></p>
    <p class="muted">Aroma utama berasal dari essential oil berkualitas yang dicampur pada tahap akhir sehingga bau dasar tidak mengganggu.</p>
  </div>
</section>

<section id="contact" style="margin-top:22px">
  <h2>Kontak &amp; Pemesanan</h2>
  <div class="product-card contact-form">
    <p class="muted">Isi form di bawah untuk pemesanan atau pertanyaan. (Form ini demo — hubungi kami via email/WA untuk proses nyata.)</p>
    <input type="text" id="name" placeholder="Nama" />
    <input type="email" id="email" placeholder="Email" />
    <textarea id="message" rows="4" placeholder="Pesan / jumlah pemesanan..."></textarea>
    <button class="btn" onclick="fakeSend()">Kirim Pesan</button>
    <p id="sent" style="display:none;margin-top:10px;color:green">Terima kasih! Pesan Anda sudah dicatat (demo).</p>
  </div>
</section>

<footer>
  <div class="muted">© Fluma Light — Produk ramah lingkungan. Dikembangkan dengan cinta &amp; minyak jelantah yang didaur ulang.</div>
</footer>

  </main>  <script>
    function fakeSend(){
      const name=document.getElementById('name').value.trim();
      const email=document.getElementById('email').value.trim();
      if(!name || !email){
        alert('Isi nama dan email terlebih dahulu.');
        return;
      }
      document.getElementById('sent').style.display='block';
    }
  </script></body>
</html>
