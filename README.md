<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Portofolio Raehan - Grafika Komputer</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Inter', sans-serif;
      background-color: #f4f8fb;
      color: #1e2a38;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(to right, #0d47a1, #1976d2);
      color: white;
      padding: 80px 20px 60px;
      text-align: center;
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 10px;
    }

    nav {
      background-color: #ffffff;
      border-bottom: 1px solid #e0e0e0;
      padding: 15px;
      text-align: center;
    }

    nav a {
      margin: 0 20px;
      color: #0d47a1;
      font-weight: 600;
      text-decoration: none;
      position: relative;
    }

    nav a::after {
      content: '';
      height: 2px;
      width: 0;
      background: #0d47a1;
      position: absolute;
      bottom: -5px;
      left: 0;
      transition: 0.3s;
    }

    nav a:hover::after {
      width: 100%;
    }

    main {
      max-width: 1100px;
      margin: 40px auto;
      padding: 0 20px;
    }

    section {
      margin-bottom: 60px;
    }

    h2 {
      font-size: 2rem;
      color: #0d47a1;
      margin-bottom: 20px;
      text-align: center;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }

    .card {
      background-color: white;
      border-radius: 12px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.05);
      padding: 20px;
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 25px rgba(0,0,0,0.1);
    }

    .card h3 {
      margin-bottom: 10px;
      color: #1565c0;
    }

    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 8px;
      margin-bottom: 15px;
    }

    .contact p {
      margin: 10px 0;
      text-align: center;
    }

    .contact a {
      color: #1565c0;
      text-decoration: none;
    }

    .contact a:hover {
      text-decoration: underline;
    }

    #social {
      text-align: center;
    }

    .social-media {
      margin-top: 10px;
      font-size: 1.2rem;
    }

    .social-media a {
      color: #0d47a1;
      text-decoration: none;
      margin: 0 15px;
      font-weight: 600;
      display: inline-block;
    }

    .social-media a i {
      margin-right: 8px;
    }

    .social-media a:hover {
      color: #1976d2;
    }

    footer {
      text-align: center;
      background-color: #0d47a1;
      padding: 30px 10px;
      color: #cfd8dc;
      font-size: 0.9rem;
      margin-top: 50px;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }

      nav {
        display: flex;
        flex-direction: column;
        gap: 10px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Portofolio Mata Kuliah Grafika Komputer</h1>
  </header>

  <nav>
    <a href="#about">Profil</a>
    <a href="#tugas">Daftar Tugas</a>
    <a href="#tentang">About</a>
  </nav>

  <main>
    <section id="about">
      <h2>Profil</h2>
      <div style="text-align: center;">
        <div style="display: flex; justify-content: center; margin-bottom: 20px;">
          <img src="images/raehan.jpg" alt="Foto Raehan" style="width: 150px; height: 150px; object-fit: cover; border-radius: 50%; border: 3px solid #0d47a1;">
        </div>
        <p>Nama: Raehan</p>
        <p>NPM: 2413025033</p>
      </div>
    </section>

    <section id="tugas">
      <h2>Daftar Tugas</h2>
      <div class="grid">
        <div class="card">
          <img src="images/steve.jpg" alt="Cover Tugas Tokoh">
          <h3>Tokoh Perintis Grafika Komputer</h3>
          <p>
            <a href="files/tokoh_perintis.pdf">Buka File</a> |
            <a href="https://drive.google.com/file/d/1KN_BKBQjRTLONSm-OlFkkaQ9aZwz80Sg/view" target="_blank">Tonton Video</a>
          </p>
        </div>
        <div class="card">
          <img src="images/garis.jpg" alt="Cover Tugas Garis">
          <h3>Algoritma Garis DDA & Bresenham</h3>
          <p>
            <a href="files/algoritma_garis.pdf">Buka File</a> |
            <a href="https://drive.google.com/file/d/1ZvTkdLrz0EvPC7Cm7Ngtk_gt-fMR5eYS/view" target="_blank">Tonton Video</a>
          </p>
        </div>
        <div class="card">
          <img src="images/lingkaran.jpg" alt="Cover Tugas Lingkaran">
          <h3>Algoritma Lingkaran Bresenham & Midpoint</h3>
          <p>
            <a href="files/algoritma_lingkaran.pdf">Buka File</a> |
            <a href="https://drive.google.com/file/d/1nD1mjUyBj4q6O1A5V8_VNhbqZ2oqQw1-/view" target="_blank">Tonton Video</a>
          </p>
        </div>
      </div>
    </section>

    <section id="tentang">
      <h2>About Me</h2>
      <p style="text-align: center;">
        Hai! Saya Raehan, mahasiswa S1 Pendidikan Teknologi Informasi (PTI) Universitas Lampung angkatan 2024.
        Saya tertarik dengan dunia teknologi, terutama dalam pemrograman, grafika komputer, dan bagaimana teknologi bisa diterapkan dalam dunia pendidikan.
        Website ini saya buat sebagai tempat untuk menyimpan dan mendokumentasikan tugas-tugas kuliah, khususnya mata kuliah Grafika Komputer.
      </p>
      <p style="text-align: center;">
        Kalau ada pertanyaan atau ingin diskusi, jangan ragu untuk menghubungi saya melalui email:
        <a href="mailto:raehann25@gmail.com">raehann25@gmail.com</a>
      </p>
    </section>

    <section id="social">
      <h2>Social Media</h2>
      <div class="social-media">
        <a href="https://instagram.com/_raehann25" target="_blank"><i class="fab fa-instagram"></i>Instagram</a>
        <a href="https://www.linkedin.com/in/raehan-363680326" target="_blank"><i class="fab fa-linkedin"></i>LinkedIn</a>
        <a href="https://www.facebook.com/raehan.olenk" target="_blank"><i class="fab fa-facebook"></i>Facebook</a>
      </div>
    </section>
  </main>

  <footer>
    &copy; 2025 Raehan.
  </footer>

</body>
</html>
