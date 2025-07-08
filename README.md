<!DOCTYPE html>
<html lang="id">
<head>
  <meta name="google-site-verification" content="eb4TsiEpMWYICwUIO5R95odfXxbFezjOyksVh7aC2Ck" />
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" />

  <style>
    /* Animasi Background */
    @keyframes gradientMove {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .profile-header {
      background: linear-gradient(270deg, #0f2027, #203a43, #2c5364);
      background-size: 300% 300%;
      animation: gradientMove 15s ease infinite;
      position: relative;
      overflow: hidden;
      color: white;
    }

    .profile-header::before {
      content: "";
      position: absolute;
      inset: 0;
      background: url('https://images.unsplash.com/photo-1518770660439-4636190af475?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80') center/cover;
      opacity: 0.15;
      animation: zoomPan 20s linear infinite;
    }

    @keyframes zoomPan {
      0% { transform: scale(1) rotate(0deg); }
      50% { transform: scale(1.1) rotate(1deg); }
      100% { transform: scale(1) rotate(0deg); }
    }

    .profile-content {
      position: relative;
      z-index: 1;
    }

    .profile-img {
      width: 150px;
      height: 150px;
      object-fit: cover;
      border-radius: 50%;
      margin-bottom: 20px;
      border: 4px solid rgba(255, 255, 255, 0.8);
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
      transition: transform 0.3s ease;
    }

    .profile-img:hover {
      transform: scale(1.05);
    }

    /* Efek Partikel */
    .particles {
      position: absolute;
      inset: 0;
      z-index: 0;
      overflow: hidden;
    }

    .particle {
      position: absolute;
      background: rgba(255, 255, 255, 0.5);
      border-radius: 50%;
      animation: float linear infinite;
    }

    @keyframes float {
      0% { transform: translateY(0) translateX(0); opacity: 1; }
      100% { transform: translateY(-100vh) translateX(100px); opacity: 0; }
    }
  </style>
</head>

<body>
  <!-- Welcome Banner -->
  <div class="bg-primary text-white text-center py-2">
    <p class="mb-0">Selamat datang di portofolio saya! Senang bisa berbagi profil dan pengalaman dengan Anda.</p>
  </div>

  <!-- Profile Header -->
  <header class="profile-header text-center py-5">
    <div class="particles" id="particles-js"></div>
    <div class="profile-content d-flex flex-column align-items-center">
      <img src="Pas Foto.jpg" alt="Foto Rizki Aulia" class="profile-img" />
      <h1 class="display-4">Rizki Aulia</h1>
    </div>
  </header>

  <!-- Navigasi -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light sticky-top">
    <div class="container">
      <a class="navbar-brand" href="#">Menu</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a href="#about" class="nav-link">Tentang Saya</a></li>
          <li class="nav-item"><a href="#education" class="nav-link">Pendidikan</a></li>
          <li class="nav-item"><a href="#experience" class="nav-link">Pengalaman</a></li>
          <li class="nav-item"><a href="#skills" class="nav-link">Kemampuan</a></li>
          <li class="nav-item"><a href="#cv" class="nav-link">CV</a></li>
          <li class="nav-item"><a href="#contact" class="nav-link">Kontak</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Tentang Saya -->
  <section id="about" class="container my-5">
    <h2 class="mb-3">Tentang Saya</h2>
    <p>
      Saya adalah lulusan Teknik Elektro Universitas Malikussaleh, dapat diandalkan, mudah beradaptasi, dan mampu bekerja sama dengan baik. Saya memiliki pengalaman magang di PT. PLN (Persero), studi independen di PT. Orbit Ventura Indonesia, serta bekerja sebagai teknisi di PT. Meraki Teknologi Indonesia.
    </p>
  </section>

  <!-- Pendidikan -->
  <section id="education" class="container my-5">
    <h2 class="mb-3">Pendidikan</h2>
    <ul>
      <li><strong>Universitas Malikussaleh</strong> - Teknik Elektro (2020 - 2024)</li>
      <li><strong>SMK Teknologi Industri YPT. P. Berandan</strong> - Teknik Instalasi Listrik (2017 - 2020)</li>
      <li><strong>SMP Negeri 1 Pangkalan Susu</strong> (2014 - 2017)</li>
    </ul>
  </section>

  <!-- Pengalaman -->
  <section id="experience" class="container my-5">
    <h2 class="mb-3">Pengalaman & Organisasi</h2>
    <ul>
      <li>Teknisi - PT Meraki Teknologi Indonesia (4 bulan)</li>
      <li>Magang - PT PLN Rayon Pangkalan Susu & PT PLN UBP Indonesia Power</li>
      <li>Studi Independen - PT Orbit Ventura Indonesia</li>
      <li>Himpunan Mahasiswa Teknik Elektro - Divisi Kesekretariatan</li>
      <li>Sains Riset & Robotika - Ketua Divisi SDM</li>
      <li>Himpunan Mahasiswa Langkat - Divisi Hubungan Masyarakat</li>
    </ul>
  </section>

  <!-- Kemampuan -->
  <section id="skills" class="container my-5">
    <h2 class="mb-3">Kemampuan & Sertifikat</h2>
    <div class="row">
      <div class="col-md-4">
        <h5>Hard Skill</h5>
        <ul>
          <li>Instalasi Listrik, CCTV, Fiber Optik</li>
          <li>Smart Home, Distribusi Jaringan</li>
          <li>Perakitan & Pengujian Panel</li>
          <li>Welding & Piping</li>
        </ul>
      </div>
      <div class="col-md-4">
        <h5>Software</h5>
        <ul>
          <li>Microsoft Office, Arduino IDE, Visio</li>
          <li>SketchUp, Fritzing, ETAP</li>
          <li>LabView, VS Code, Psim</li>
          <li>IoT, PLC</li>
        </ul>
      </div>
      <div class="col-md-4">
        <h5>Sertifikat</h5>
        <ul>
          <li>Magang PT PLN</li>
          <li>Studi Independen Orbit Ventura</li>
          <li>Asisten Laboratorium</li>
          <li>TOEFL</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- CV -->
  <section id="cv" class="container my-5">
    <h2 class="mb-3">Curriculum Vitae</h2>
    <a href="RA FILE.pdf" class="btn btn-primary mb-3" target="_blank">Download CV</a>
  </section>

  <!-- Kontak -->
  <section id="contact" class="container my-5">
    <h2 class="mb-3">Kontak</h2>
    <p><strong>Email:</strong> <a href="mailto:11rizkiaulia@gmail.com">11rizkiaulia@gmail.com</a></p>
    <p><strong>Telepon:</strong> +62 8126 5075 517</p>
    <p><strong>Lokasi:</strong> Medan, Sumatera Utara</p>
  </section>

  <!-- Form Feedback -->
  <section id="feedback" class="container my-5">
    <h2 class="mb-3">Kirim Komentar</h2>
    <form action="https://formspree.io/f/xrbqlgvn" method="POST">
      <div class="mb-3">
        <label for="name" class="form-label">Nama</label>
        <input type="text" class="form-control" id="name" name="nama" required />
      </div>
      <div class="mb-3">
        <label for="email" class="form-label">Email</label>
        <input type="email" class="form-control" id="email" name="email" required />
      </div>
      <div class="mb-3">
        <label for="message" class="form-label">Pesan / Komentar</label>
        <textarea class="form-control" id="message" name="pesan" rows="4" required></textarea>
      </div>
      <button type="submit" class="btn btn-primary">Kirim</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3">
    <p>&copy; 2025 Rizki Aulia.</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

  <script>
    document.addEventListener('DOMContentLoaded', function () {
      const particlesContainer = document.getElementById('particles-js');
      const particleCount = 30;

      for (let i = 0; i < particleCount; i++) {
        createParticle();
      }

      function createParticle() {
        const particle = document.createElement('div');
        particle.classList.add('particle');

        const size = Math.random() * 5 + 2;
        particle.style.width = `${size}px`;
        particle.style.height = `${size}px`;
        particle.style.left = `${Math.random() * 100}%`;
        particle.style.top = `${Math.random() * 100 + 100}%`;

        const duration = Math.random() * 20 + 10;
        particle.style.animationDuration = `${duration}s`;

        const delay = Math.random() * 5;
        particle.style.animationDelay = `${delay}s`;

        particlesContainer.appendChild(particle);

        particle.addEventListener('animationend', () => {
          particle.remove();
          createParticle();
        });
      }
    });
  </script>
</body>
</html>
