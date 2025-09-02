<html lang="fr">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>KNOTINUS — L’Upcycling Pop & Unique</title>
<meta name="description" content="Knotinus transforme des housses de couette vintage en chemises et accessoires uniques. Ateliers de réparation & upcycling.">
<link rel="canonical" href="https://knotinus.example" />

<!-- Open Graph -->
<meta property="og:title" content="KNOTINUS — L’Upcycling Pop & Unique">
<meta property="og:description" content="Chemises & accessoires upcyclés + ateliers de réparation et création.">
<meta property="og:type" content="website">
<meta property="og:url" content="https://knotinus.example">
<meta property="og:image" content="https://knotinus.example/KNOTINUS.jpg">
![KNOTINUS](https://github.com/user-attachments/assets/cdb600ea-4a7a-4682-9ff9-628c8b53c8e5)

<!-- Twitter -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Knotinus — L’upcycling pop & unique">
<meta name="twitter:description" content="Chemises & accessoires upcyclés + ateliers de réparation et création.">
<meta name="twitter:image" content="https://knotinus.example/og-image.jpg">

<style>
/* Variables & Reset */
:root{
--bg:#fffdfa;
--ink:#151515;
--muted:#6b6b6b;
--primary:#ff2d55;
--accent:#ffd166;
--blue:#1982ff;
--radius:14px;
--shadow:0 10px 30px rgba(0,0,0,.08);
--max:1100px;
}
*{box-sizing:border-box}
body{margin:0;font-family:system-ui,-apple-system,Segoe UI,Roboto,Inter,Arial,sans-serif;background:var(--bg);color:var(--ink);line-height:1.5}
a{color:inherit;text-decoration:none}
img{max-width:50%;display:block}
.container{max-width:var(--max);margin:0 auto;padding:0 20px}

/* Header */
header{position:sticky;top:0;background:rgba(255,253,250,.85);backdrop-filter:blur(6px);border-bottom:1px solid rgba(0,0,0,.08)}
.nav{display:flex;justify-content:space-between;align-items:center;height:64px}
.brand{display:flex;align-items:center;gap:8px;font-weight:800}
.logo{width:36px;height:36px;border-radius:10px;background:conic-gradient(from 200deg, var(--primary), var(--blue));box-shadow:var(--shadow)}
.nav a.btn{padding:8px 14px;border:1.5px solid #000;border-radius:999px;font-weight:700;margin-left:8px;background:#fff}

/* Hero */
.hero{background:linear-gradient(180deg,#fffdfa 0%, #fff4e0 100%);padding:60px 0}
.hero-inner{display:grid;grid-template-columns:1.2fr .8fr;gap:30px;align-items:center}
.title{font-size:clamp(36px,6vw,60px);font-weight:900;margin:0}
.subtitle{color:var(--muted);margin:14px 0;max-width:55ch}
.cta{display:flex;gap:12px;margin-top:20px;flex-wrap:wrap}
.btn-primary{background:var(--ink);color:#fff;border:2px solid #000;padding:12px 18px;border-radius:14px;font-weight:800}
.btn-ghost{background:#fff;border:2px dashed #000;padding:12px 18px;border-radius:14px;font-weight:800}

/* Sections */
section{padding:70px 0;border-top:1px dashed rgba(0,0,0,.1)}
h2{font-size:clamp(26px,3.5vw,38px);margin:0;font-weight:900}

/* Grid collection */
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:16px}
.card{background:#fff;border:1.5px solid #000;border-radius:14px;overflow:hidden;box-shadow:var(--shadow)}
.card .info{padding:12px}
.price{font-weight:900}

/* Workshop */
.workshop{display:grid;grid-template-columns:1fr 1fr;gap:20px}
.panel{background:#fff;border:2px solid #000;border-radius:14px;padding:20px}

/* About */
.about{display:grid;grid-template-columns:1fr 1fr;gap:20px;align-items:center}

/* Footer */
footer{background:#111;color:#eee;padding:40px 20px;margin-top:40px}
.socials{display:flex;gap:10px;flex-wrap:wrap;margin-top:10px}
.socials a{background:#fff;color:#000;padding:8px 12px;border-radius:999px;font-weight:800}

/* Responsive */
@media (max-width:900px){
.hero-inner{grid-template-columns:1fr}
.workshop,.about{grid-template-columns:1fr}
}
</style>
</head>
<body>

<header>
<div class="container nav">
<div class="brand"><div class="logo"></div><span>Knotinus</span></div>
<nav>
<a href="#collection" class="btn">Collection</a>
<a href="#ateliers" class="btn">Ateliers</a>
<a href="#apropos" class="btn">À propos</a>
<a href="#contact" class="btn">Contact</a>
</nav>
</div>
</header>

<main>
<!-- HERO -->
<section class="hero">
<div class="container hero-inner">
<div>
<h1 class="title">KNOTINUS — L’Upcycling <span style="color:var(--primary)">Pop & Unique</span></h1>
<p class="subtitle">Chemises et accessoires réalisés à partir de housses de couette vintage aux motifs BD. Ateliers de réparation & création pour donner une seconde vie à tes vêtements.</p>
<div class="cta">
<a class="btn-primary" href="#collection">Découvrir la collection</a>
<a class="btn-ghost" href="#ateliers">Réserver un atelier</a>
</div>
</div>
<img src="images/KNOTINUS.jpg" alt="Création Knotinus en housse BD vintage">
</div>
</section>

<!-- COLLECTION -->
<section id="collection">
<div class="container">
<h2>Collection</h2>
<div class="grid">
<article class="card">
<img src="images/KNOTINUS.jpg" alt="Chemise BD #01">
<div class="info">
<h3>Chemise BD #01</h3>
<p class="price">89 €</p>
</div>
</article>
<article class="card">
<img src="images/KNOTINUS.jpg" alt="Banane BD">
<div class="info">
<h3>Banane BD</h3>
<p class="price">39 €</p>
</div>
</article>
</div>
</div>
</section>

<!-- ATELIERS -->
<section id="ateliers">
<div class="container">
<h2>Ateliers</h2>
<div class="workshop">
<div class="panel">
<h3>Prochaines dates</h3>
<ul>
<li>Samedi 14/09 — Reprisage visible (2h)</li>
<li>Dimanche 22/09 — Upcycler une chemise (3h)</li>
</ul>
</div>
<div class="panel">
<h3>Tu apprendras</h3>
<ol>
<li>Réparer & transformer</li>
<li>Techniques solides</li>
<li>Finitions créatives</li>
</ol>
</div>
</div>
</div>
</section>

<!-- À PROPOS -->
<section id="apropos">
<div class="container about">
<div>
<h2>À propos</h2>
<p>Je chine des tissus à histoires et je les transforme en pièces actuelles. Chaque création Knotinus est pensée pour durer et pour te donner le sourire.</p>
</div>
<img src="images/KNOTINUS.jpg" alt="La créatrice de Knotinus">
</div>
</section>

<!-- CONTACT -->
<section id="contact">
<div class="container">
<h2>Contact & lien unique</h2>
<p>Partage partout : <strong>knotinus.example/go</strong></p>
<div class="cta">
<a class="btn-primary" href="https://instagram.com/knotinus">Instagram</a>
<a class="btn-primary" href="mailto:hello@knotinus.example">Email</a>
</div>
</div>
</section>
</main>

<footer>
<div class="container">
<div class="brand"><div class="logo"></div><span>Knotinus</span></div>
<p>Upcycling pop de textiles vintage • Pièces uniques • Ateliers à Lyon</p>
<div class="socials">
<a href="https://instagram.com/knotinus">Instagram</a>
<a href="https://tiktok.com/@knotinus">TikTok</a>
<a href="https://facebook.com/knotinus">Facebook</a>
</div>
</div>
</footer>


<body>

