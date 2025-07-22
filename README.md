<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css" rel="stylesheet">
<style>
  body {
    background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), 
                url('https://images.unsplash.com/photo-1605106702734-205df224ecce?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80') no-repeat center center fixed;
    background-size: cover;
    color: #ffffff;
  }
  
  .section-container {
    background-color: rgba(13, 110, 253, 0.2);
    backdrop-filter: blur(5px);
    border-radius: 10px;
    padding: 25px;
    margin-bottom: 30px;
    border: 1px solid rgba(255, 255, 255, 0.1);
    box-shadow: 0 0 15px rgba(0, 89, 255, 0.3);
  }
  
  .section-title {
    color: #ffffff;
    text-shadow: 0 0 5px #0d6efd;
    border-bottom: 2px solid #0d6efd;
    padding-bottom: 10px;
  }
  
  .section-text, ul {
    color: #e0e0e0;
  }
  
  .navbar {
    background-color: rgba(248, 249, 250, 0.9) !important;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
  }
  
  .form-control {
    background-color: rgba(255, 255, 255, 0.1);
    border: 1px solid #0d6efd;
    color: white;
  }
  
  .form-control:focus {
    background-color: rgba(255, 255, 255, 0.2);
    color: white;
  }
  
  .form-label {
    color: #ffffff;
  }
  
  .btn-primary {
    background-color: #0d6efd;
    border: none;
    box-shadow: 0 0 10px rgba(13, 110, 253, 0.5);
  }
  
  .btn-primary:hover {
    background-color: #0b5ed7;
    box-shadow: 0 0 15px rgba(13, 110, 253, 0.8);
  }
  
  footer {
    box-shadow: 0 -5px 15px rgba(0, 0, 0, 0.2);
  }
  
  ::placeholder {
    color: #cccccc !important;
    opacity: 1;
  }
</style>
</head>
<body>
<header class="bg-primary text-white text-center py-5" style="background-color: rgba(13, 110, 253, 0.7) !important;">
  <img src="Pas Foto.jpg" alt="Foto Rizki Aulia" class="rounded mb-3" style="width:220px;height:320px;object-fit:cover;border:4px solid white;box-shadow: 0 0 20px rgba(255, 255, 255, 0.5);">
  <h1 class="fw-bold">Rizki Aulia</h1>
  <p class="lead fw-bold text-white fs-4">Teknik Elektro • Universitas Malikussaleh</p>
</header>
<nav class="navbar navbar-expand-lg navbar-light bg-light sticky-top">
  <div class="container">
    <a class="navbar-brand fw-bold" href="#">Portfolio</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a href="#about" class="nav-link">Tentang</a></li>
        <li class="nav-item"><a href="#education" class="nav-link">Pendidikan</a></li>
        <li class="nav-item"><a href="#experience" class="nav-link">Pengalaman</a></li>
        <li class="nav-item"><a href="#skills" class="nav-link">Kemampuan</a></li>
        <li class="nav-item"><a href="#cv" class="nav-link">CV</a></li>
        <li class="nav-item"><a href="#contact" class="nav-link">Kontak</a></li>
        <li class="nav-item"><a href="#feedback" class="nav-link">Komentar</a></li>
      </ul>
    </div>
  </div>
</nav>

<div class="container my-5">
  <section id="about" class="section-container">
    <h2 class="mb-3 section-title"><i class="bi bi-person-fill"></i> Tentang Saya</h2>
    <p class="section-text">Saya adalah lulusan program studi Teknik Elektro, Universitas Malikussaleh. Saya mampu diandalkan dan diberi tanggung jawab juga selalu berusaha memberikan yang terbaik dalam setiap pekerjaan saya. Saya mudah beradaptasi dengan lingkungan sosial yang baru, mampu bekerja sama dengan baik dalam tim dan yang terpenting dalam hidup saya adalah selalu berusaha agar orang lain mengenal diri saya karena manfaat yang saya berikan. Saya memiliki pengalaman magang di PT. PLN (Persero) Rayon Pangkalan Susu selama 3 bulan sebagai teknisi, Studi Independen di PT. Orbit Ventura Indonesia selama 4 bulan dan PT. PLN Indonesia Power UBP Pangkalan Susu 1 bulan sebagai teknisi. Dan Saya memiliki pengalaman kerja di PT. Meraki Teknologi Indonesia selama 4 bulan sebagai teknisi.</p>
  </section>

  <section id="education" class="section-container">
    <h2 class="mb-3 section-title"><i class="bi bi-book-fill"></i> Pendidikan</h2>
    <ul>
      <li><strong>Universitas Malikussaleh</strong> – Teknik Elektro (2020–2024)</li>
      <li><strong>SMK Teknologi Industri YPT P. Berandan</strong> – Teknik Instalasi Listrik (2017–2020)</li>
      <li><strong>SMP Negeri 1 Pangkalan Susu</strong> (2014–2017)</li>
    </ul>
  </section>

  <section id="experience" class="section-container">
    <h2 class="mb-3 section-title"><i class="bi bi-briefcase-fill"></i> Pengalaman & Organisasi</h2>
    <ul>
      <li>Teknisi di PT Meraki Teknologi Indonesia (4 bulan)</li>
      <li>Magang di PT PLN Rayon Pangkalan Susu & Indonesia Power</li>
      <li>Studi Independen di PT Orbit Ventura Indonesia</li>
      <li>Himpunan Mahasiswa Teknik Elektro – Divisi Kesekretariatan</li>
      <li>Sains Riset & Robotika – Ketua Divisi SDM</li>
      <li>Himpunan Mahasiswa Langkat – Hubungan Masyarakat</li>
    </ul>
  </section>

  <section id="skills" class="section-container">
    <h2 class="mb-3 section-title"><i class="bi bi-tools"></i> Kemampuan & Sertifikat</h2>
    <div class="row">
      <div class="col-md-4">
        <h5>Hard Skill</h5>
        <ul>
          <li>Instalasi Listrik, CCTV, Smart Home</li>
          <li>Analisis Jaringan Distribusi</li>
          <li>Perakitan & Pengujian Panel Listrik</li>
          <li>Pengukuran</li>
          <li>PLC</li>
          <li>Arus Kuat</li> 
          <li>Arus Lemah</li>
          <li>IoT</li>
          <li>Robotika</li>
          <li>Welding</li>
          <li>Piping</li>
        </ul>
      </div>
      <div class="col-md-4">
        <h5>Software</h5>
        <ul>
          <li>Microsoft Office</li>
          <li>SketchUp</li>
          <li>Visual Studio Code</li>
          <li>Psim</li>
          <li>AutoCad</li>
          <li>Arduino Ide</li>
          <li>Visio</li>
          <li>ETAP</li>
          <li>LabView</li>
          <li>Fritzing</li>
        </ul>
      </div>
      <div class="col-md-4">
        <h5>Sertifikat</h5>
        <ul>
          <li>Kerja Praktek – PT PLN & Indonesia Power</li>
          <li>Studi Independen – Orbit Ventura Indonesia (MSIB)</li>
          <li>Asisten Laboratorium Teknik Elektro</li>
          <li>TOEFL</li>
        </ul>
      </div>
    </div>
  </section>

  <section id="cv" class="section-container text-center">
    <h2 class="mb-3 section-title"><i class="bi bi-file-earmark-person-fill"></i> Curriculum Vitae</h2>
    <a href="DOKUMEN RIZKI.pdf" class="btn btn-primary" target="_blank">Download CV</a>
  </section>

  <section id="contact" class="section-container">
    <h2 class="mb-3 section-title"><i class="bi bi-envelope-fill"></i> Kontak</h2>
    <p class="section-text"><strong>Email:</strong> <a href="mailto:11rizkiaulia@gmail.com" style="color: #ffffff;">11rizkiaulia@gmail.com</a></p>
    <p class="section-text"><strong>Telepon:</strong> +62 8126 5075 517</p>
    <p class="section-text"><strong>Lokasi:</strong> Medan, Sumatera Utara</p>
  </section>

  <section id="feedback" class="section-container">
    <h2 class="mb-3 section-title"><i class="bi bi-chat-left-text-fill"></i> Kirim Komentar</h2>
    <form action="https://formspree.io/f/xrbqlgvn" method="POST">
      <div class="mb-3">
        <label for="name" class="form-label">Nama</label>
        <input type="text" class="form-control" id="name" name="nama" required placeholder="Nama Anda">
      </div>
      <div class="mb-3">
        <label for="email" class="form-label">Email</label>
        <input type="email" class="form-control" id="email" name="email" required placeholder="email@contoh.com">
      </div>
      <div class="mb-3">
        <label for="message" class="form-label">Pesan / Komentar</label>
        <textarea class="form-control" id="message" name="pesan" rows="4" required placeholder="Tulis pesan Anda di sini..."></textarea>
      </div>
      <button type="submit" class="btn btn-primary">Kirim</button>
    </form>
  </section>
</div>

<footer class="bg-primary text-white text-center py-3" style="background-color: rgba(13, 110, 253, 0.7) !important;">
  <p>&copy; 2025 Rizki Aulia</p>
</footer>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
