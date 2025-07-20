<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Buat Ulya</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(#fff8f0, #ffd6d6);
      scroll-behavior: smooth;
    }
    header {
      background: #ffb6b6;
      color: white;
      text-align: center;
      padding: 1rem;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    section {
      padding: 3rem 1rem;
      max-width: 1000px;
      margin: auto;
    }
    .photo-gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
    }
    .photo-gallery img {
      width: 100%;
      border-radius: 1rem;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
      transition: transform 0.3s;
    }
    .photo-gallery img:hover {
      transform: scale(1.05);
    }
    .video-section video {
      width: 100%;
      border-radius: 2rem;
      margin-top: 1rem;
    }
    .scroll-reveal {
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 0.6s ease-out, transform 0.6s ease-out;
    }
    .scroll-reveal.visible {
      opacity: 1;
      transform: translateY(0);
    }
    footer {
      text-align: center;
      padding: 2rem;
      background: #ffc1c1;
      color: #fff;
    }
  </style>
</head>
<body>
  <header>
    <h1>Happy Anniversary!</h1>
    <p>❤️04/08/2024 - 04/08/2025 ❤️</p>
  </header>

  <section class="scroll-reveal">
    <h2>Ini Foto Kita Yang paling lucuuuu❤️</h2>
    <div class="photo-gallery">
      <img src="c:\Users\Kyupa\Downloads\Web\Photo\IMG_20250127_165229.jpg" alt="Memory 1" />
      <img src="c:\Users\Kyupa\Downloads\Web\Photo\IMG_20250701_144706_145.jpg" alt="Memory 2" />
      <img src="c:\Users\Kyupa\Downloads\Web\Photo\IMG-20241209-WA0021.jpg" alt="Memory 3" />
      <img src="c:\Users\Kyupa\Downloads\Web\Photo\IMG-20250101-WA0053.jpg" alt="Memory 4" />
    </div>
  <section class="scroll-reveal video-section">
    <h2>Lucuuu Banget Kannn kitaaaa💖</h2>
    <video controls>
      <source src="c:\Users\Kyupa\Downloads\Web\photo\lv_7168730948257729794_20250409140126.mp4" type="video/mp4" />
      Your browser does not support the video tag.
    </video>
  </section>


  <section class="scroll-reveal">
    <h2>Notes</h2>
    <p style="font-style: italic; font-size: 1.2rem;">
      "Setiap Hari ada cerita, ada suka duka dan masalah."
    </p>
    <p style="font-style: italic; font-size: 1.2rem;">
      "Tapi Kita berdua, aku kamu dan dunia kita."
    </p>
    <p style="font-style: italic; font-size: 1.2rem;">
      "Kita lewatin semua masalah yang ada, kita berjuang bareng bareng sampai tua ya?"
    </p>
    <p style="font-style: italic; font-size: 1.2rem;">
      "Diatas tawa, sakit, bahagia. kita udah lewatin itu semua."
    </p>
    <p style="font-style: italic; font-size: 1.2rem;">
      "care each other, mengerti dan sabar"
    </p>
    <p style="font-style: italic; font-size: 1.2rem;">
      "Aku gabisa bilang yang lain, tapi Aku Sayang kamu lebih dari apapun💖"
    </p>
  </section>

  <footer>
    <p>Ur Beloved 💖</p>
    <p>-Nagu</p>
  </footer>

  <script>
    const reveals = document.querySelectorAll('.scroll-reveal');
    const revealOnScroll = () => {
      for (let el of reveals) {
        const windowHeight = window.innerHeight;
        const elementTop = el.getBoundingClientRect().top;
        const elementVisible = 100;

        if (elementTop < windowHeight - elementVisible) {
          el.classList.add('visible');
        }
      }
    };

    window.addEventListener('scroll', revealOnScroll);
    window.addEventListener('load', revealOnScroll);
  </script>
</body>
</html>
