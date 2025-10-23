# Bahcebakim.com
Profesyonel peyzaj ve bahçe bakım hizmetleri — Bahçe Bakım, peyzaj ve dış mekân tasarımı uzmanları.
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>BahceBakim.com — Profesyonel Peyzaj & Bahçe Bakımı</title>
  <link rel="stylesheet" href="style.css" />
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>

  <!-- Header -->
  <header class="site-header">
    <div class="container header-inner">
      <div class="brand">
        <h1>BahceBakim.com</h1>
        <p class="tag">Profesyonel Peyzaj & Bahçe Bakımı</p>
      </div>

      <nav>
        <div class="hamburger" id="hamburger" aria-label="menu" aria-expanded="false" role="button">
          <span></span><span></span><span></span>
        </div>
        <ul class="nav-list" id="navList">
          <li><a href="#hakkimizda">Hakkımızda</a></li>
          <li><a href="#hizmetler">Hizmetler</a></li>
          <li><a href="#projeler">Projeler</a></li>
          <li><a href="#iletisim">İletişim</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Hero slider with parallax -->
  <section class="hero">
    <div class="hero-slider" id="heroSlider">
      <div class="slide" style="background-image:url('images/hero1.jpg')">
        <div class="slide-inner">
          <h2>Bahçenizi Yenileyin</h2>
          <p>Estetik peyzaj tasarımı ve güvenilir bakım hizmetleri.</p>
          <a class="btn" href="#iletisim">Teklif Al</a>
        </div>
      </div>
      <div class="slide" style="background-image:url('images/hero2.jpg')">
        <div class="slide-inner">
          <h2>Profesyonel Sulama Sistemleri</h2>
          <p>Su tasarrufu sağlayan çözümler ve kurulum.</p>
          <a class="btn" href="#iletisim">Hemen İletişime Geç</a>
        </div>
      </div>
      <div class="slide" style="background-image:url('images/hero3.jpg')">
        <div class="slide-inner">
          <h2>Dış Mekan Aydınlatması</h2>
          <p>Akşam bahçenize sıcak ve etkileyici bir atmosfer katıyoruz.</p>
          <a class="btn" href="#projeler">Projelerimize Bak</a>
        </div>
      </div>

      <!-- Slider controls -->
      <div class="slider-controls">
        <button id="prevSlide" aria-label="previous">&#10094;</button>
        <div id="dots" class="dots"></div>
        <button id="nextSlide" aria-label="next">&#10095;</button>
      </div>
    </div>
  </section>

  <!-- About -->
  <section id="hakkimizda" class="section fade-in">
    <div class="container">
      <h2>Hakkımızda</h2>
      <p>BahceBakim.com profesyonel peyzaj ve bahçe bakım hizmetleri sunar. Her projede estetik ve fonksiyonelliği birleştirir, müşterilerimize uzun ömürlü ve bakımı kolay dış mekanlar tasarlarız.</p>
    </div>
  </section>

  <!-- Services -->
  <section id="hizmetler" class="section fade-in">
    <div class="container">
      <h2>Hizmetlerimiz</h2>
      <div class="cards">
        <article class="card">
          <h3>Bahçe Bakımı</h3>
          <p>Çim bakımı, budama, gübreleme ve mevsimsel düzenlemeler.</p>
        </article>
        <article class="card">
          <h3>Peyzaj Tasarımı</h3>
          <p>Modern, fonksiyonel ve estetik tasarımlar.</p>
        </article>
        <article class="card">
          <h3>Sulama Sistemleri</h3>
          <p>Otomatik sulama ve bakım çözümleri.</p>
        </article>
        <article class="card">
          <h3>Dış Mekan Aydınlatma</h3>
          <p>Ambiyans aydınlatmaları ile bahçenizi geceye taşıyoruz.</p>
        </article>
      </div>
    </div>
  </section>

  <!-- Portfolio -->
  <section id="projeler" class="section">
    <div class="container">
      <h2>Projelerimiz</h2>
      <div class="portfolio-grid" id="portfolioGrid">
        <div class="portfolio-item"><img src="images/proje1.jpg" alt="Proje 1"></div>
        <div class="portfolio-item"><img src="images/proje2.jpg" alt="Proje 2"></div>
        <div class="portfolio-item"><img src="images/proje3.jpg" alt="Proje 3"></div>
        <div class="portfolio-item"><img src="images/proje4.jpg" alt="Proje 4"></div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="iletisim" class="section fade-in">
    <div class="container">
      <h2>İletişim</h2>
      <p>Bize aşağıdaki bilgilerden veya formu doldurarak ulaşabilirsiniz.</p>
      <ul class="contact-list">
        <li>Email: <a href="mailto:info@bahcebakim.com">info@bahcebakim.com</a></li>
        <li>Telefon: +90 5XX XXX XXXX</li>
        <li>Instagram: <a href="https://instagram.com/bahcebakim" target="_blank">@bahcebakim</a></li>
      </ul>

      <form class="contact-form" action="#" method="POST" onsubmit="return false;">
        <input type="text" name="isim" placeholder="Adınız" required>
        <input type="email" name="email" placeholder="Email" required>
        <textarea name="mesaj" placeholder="Mesajınız" required></textarea>
        <button class="btn" type="submit">Gönder</button>
      </form>
    </div>
  </section>

  <footer class="site-footer">
    <div class="container">
      <p>© 2025 BahceBakim.com — Tüm hakları saklıdır.</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
/* Reset & base */
* { box-sizing: border-box; }
html,body{ height:100%; }
body {
  margin:0;
  font-family: 'Roboto', sans-serif;
  color:#243028;
  background:#fafafa;
  -webkit-font-smoothing:antialiased;
  -moz-osx-font-smoothing:grayscale;
}

/* Container */
.container { width:92%; max-width:1200px; margin:0 auto; }

/* Header */
.site-header {
  background: linear-gradient(180deg,#2e7d32,#246430);
  color:#fff;
  position:sticky;
  top:0;
  z-index:1000;
  box-shadow:0 2px 8px rgba(0,0,0,0.12);
}
.header-inner { display:flex; align-items:center; justify-content:space-between; padding:14px 0; }
.brand h1 { margin:0; font-size:1.1rem; letter-spacing:0.5px; }
.brand .tag { margin:0; font-size:0.75rem; opacity:0.9; }

/* Nav */
nav { display:flex; align-items:center; gap:20px; }
.nav-list { list-style:none; margin:0; padding:0; display:flex; gap:18px; }
.nav-list a { color:#fff; text-decoration:none; font-weight:700; transition: color .2s; }
.nav-list a:hover { color:#ffb74d; }

/* Hamburger */
.hamburger { display:none; width:30px; height:22px; cursor:pointer; flex-direction:column; justify-content:space-between; }
.hamburger span { display:block; height:3px; background:#fff; border-radius:3px; transition:transform .3s,opacity .3s; }

/* Hero slider */
.hero { position:relative; overflow:hidden; min-height:62vh; display:flex; align-items:center; justify-content:center; }
.hero-slider { width:100%; height:100%; position:relative; }
.slide {
  position:absolute; inset:0; background-position:center; background-size:cover;
  display:flex; align-items:center; justify-content:center; transition:opacity .9s ease, transform .9s ease;
  opacity:0; transform:scale(1.02);
}
.slide.active { opacity:1; transform:scale(1); z-index:1; }
.slide-inner { background:rgba(0,0,0,0.35); padding:30px; border-radius:10px; text-align:center; color:#fff; max-width:900px; margin:20px; }
.slide-inner h2 { margin:0 0 10px; font-size:2rem; }
.slide-inner p { margin:0 0 18px; font-size:1.05rem; }

/* slider controls */
.slider-controls { position:absolute; bottom:18px; left:50%; transform:translateX(-50%); display:flex; align-items:center; gap:12px; z-index:3; }
.slider-controls button { background:rgba(0,0,0,0.45); border:none; color:#fff; padding:8px 12px; border-radius:6px; cursor:pointer; }
.dots { display:flex; gap:8px; align-items:center; }

/* buttons & general */
.btn {
  display:inline-block;
  background:#ff9800;
  color:#fff;
  padding:10px 18px;
  text-decoration:none;
  border-radius:6px;
  font-weight:700;
  transition:transform .18s ease, background .18s;
}
.btn:hover { transform:translateY(-3px); background:#e68900; }

/* Sections */
.section { padding:64px 0; opacity:0; transform:translateY(20px); transition:all .6s ease-out; }
.section.visible { opacity:1; transform:translateY(0); }
.section h2 { text-align:center; color:#2e7d32; margin-bottom:28px; }

/* Cards */
.cards { display:grid; grid-template-columns:repeat(auto-fit,minmax(220px,1fr)); gap:18px; }
.card { background:#fff; border-radius:10px; padding:20px; box-shadow:0 6px 18px rgba(36,52,40,0.06); transition:transform .28s, box-shadow .28s; }
.card:hover { transform:translateY(-6px); box-shadow:0 18px 36px rgba(36,52,40,0.12); }

/* Portfolio */
.portfolio-grid { display:grid; grid-template-columns:repeat(auto-fit,minmax(220px,1fr)); gap:16px; }
.portfolio-item { overflow:hidden; border-radius:10px; background:#fff; box-shadow:0 6px 18px rgba(36,52,40,0.06); }
.portfolio-item img { width:100%; height:100%; display:block; transition:transform .5s ease, opacity .5s ease; transform-origin:center; }
.portfolio-item:hover img { transform:scale(1.06); }

/* Contact */
.contact-list { padding:0; list-style:none; display:flex; gap:18px; flex-wrap:wrap; margin:0 0 18px; }
.contact-list a { color:#246430; font-weight:700; text-decoration:none; }
.contact-form { max-width:520px; display:flex; flex-direction:column; gap:12px; }
.contact-form input, .contact-form textarea { padding:12px; border-radius:8px; border:1px solid #e0e0e0; font-size:1rem; resize:vertical; }

/* Footer */
.site-footer { background:linear-gradient(180deg,#1f5c2a,#163d1b); color:#fff; padding:18px 0; text-align:center; }

/* Responsive */
@media(max-width:900px){
  .slide-inner h2 { font-size:1.4rem; }
  .nav-list { display:none; }
  .hamburger { display:flex; }
  .header-inner { gap:12px; }
  .hero { min-height:46vh; }
}

/* mobile open nav */
.nav-list.show { display:flex; position:absolute; top:64px; right:20px; background:linear-gradient(180deg,#2e7d32,#246430); padding:12px;border-radius:8px; flex-direction:column; gap:8px; z-index:2000; }
// Basic interactive behaviors: hamburger, smooth scroll, hero slider, appear on scroll

document.addEventListener('DOMContentLoaded', function () {
  // Hamburger toggle
  const hamburger = document.getElementById('hamburger');
  const navList = document.getElementById('navList');
  hamburger.addEventListener('click', () => {
    const open = navList.classList.toggle('show');
    hamburger.setAttribute('aria-expanded', open ? 'true' : 'false');
    hamburger.classList.toggle('active');
  });

  // Smooth link scroll
  document.querySelectorAll('a[href^="#"]').forEach(a => {
    a.addEventListener('click', function (e) {
      // allow normal external links
      if (this.getAttribute('href') === '#') return;
      e.preventDefault();
      const target = document.querySelector(this.getAttribute('href'));
      if (target) target.scrollIntoView({ behavior: 'smooth', block: 'start' });
      if (navList.classList.contains('show')) {
        navList.classList.remove('show');
        hamburger.classList.remove('active');
      }
    });
  });

  // Fade-in on scroll using IntersectionObserver
  const faders = document.querySelectorAll('.fade-in, .section');
  const appearOptions = { threshold: 0.15, rootMargin: "0px 0px -80px 0px" };
  const appearOnScroll = new IntersectionObserver((entries, observer) => {
    entries.forEach(entry => {
      if (!entry.isIntersecting) return;
      entry.target.classList.add('visible');
      observer.unobserve(entry.target);
    });
  }, appearOptions);
  faders.forEach(f => appearOnScroll.observe(f));

  // Simple hero slider (auto + controls)
  const slides = Array.from(document.querySelectorAll('.hero .slide'));
  const dotsContainer = document.getElementById('dots');
  let current = 0;
  let slideInterval = null;
  const slideTime = 6000;

  // create dots
  slides.forEach((s, i) => {
    const dot = document.createElement('button');
    dot.className = 'dot';
    dot.setAttribute('aria-label', 'slide-' + (i+1));
    dot.addEventListener('click', () => goToSlide(i));
    dotsContainer.appendChild(dot);
  });

  const dots = Array.from(dotsContainer.children);

  function showSlide(idx) {
    slides.forEach((s, i) => s.classList.toggle('active', i === idx));
    dots.forEach((d, i) => d.classList.toggle('active', i === idx));
    current = idx;
  }

  function nextSlide() { showSlide((current + 1) % slides.length); }
  function prevSlide() { showSlide((current - 1 + slides.length) % slides.length); }
  function goToSlide(i) { showSlide(i); resetInterval(); }

  // hook buttons
  document.getElementById('nextSlide').addEventListener('click', () => { nextSlide(); });
  document.getElementById('prevSlide').addEventListener('click', () => { prevSlide(); });

  function resetInterval() {
    clearInterval(slideInterval);
    slideInterval = setInterval(nextSlide, slideTime);
  }

  // start
  if (slides.length) {
    showSlide(0);
    slideInterval = setInterval(nextSlide, slideTime);
  }

  // light parallax on scroll for hero (subtle)
  const hero = document.querySelector('.hero');
  window.addEventListener('scroll', () => {
    const scrollY = window.scrollY;
    if (hero) hero.style.backgroundPosition = `center ${-scrollY * 0.08}px`;
  });
});
# BahceBakim.com

Professional landscaping and garden maintenance website for BahceBakim.com.

## How to use
- Put images in `images/` (hero1.jpg, hero2.jpg, hero3.jpg, proje1.jpg...).
- Push files to GitHub repository.
- Enable GitHub Pages: Settings → Pages → Source: `main` / root.

## Files
- `index.html` — main page
- `style.css` — styles
- `script.js` — JS behaviors (slider, menu, scroll animations)
- `images/` — place project and hero images

