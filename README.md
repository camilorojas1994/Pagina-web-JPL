[index_1.html](https://github.com/user-attachments/files/30707982/index_1.html)
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Camilo Rojas Mosquera | Abogado Especialista en Juzgados de Policía Local (JPL)</title>
<meta name="description" content="Abogado especialista en Juzgados de Policía Local. Multas de tránsito, Ley del Consumidor, cobranzas, conflictos vecinales y más. Primera consulta gratis. Santiago, Chile.">
<meta name="keywords" content="abogado JPL, juzgado policía local, multas de tránsito, ley del consumidor, abogado Santiago, Camilo Rojas, cobranzas JPL, infracciones municipales, accidentes de tránsito, abogado Chile">
<meta name="author" content="Camilo Alejandro Rojas Mosquera">
<meta name="robots" content="index, follow">

<!-- Open Graph (para cuando compartas el link en redes sociales o WhatsApp) -->
<meta property="og:title" content="Camilo Rojas | Abogado Especialista en JPL">
<meta property="og:description" content="Multas, consumo, cobranzas, conflictos vecinales — tu caso en el Juzgado de Policía Local tiene solución. Primera consulta gratis.">
<meta property="og:type" content="website">
<meta property="og:locale" content="es_CL">

<!-- Twitter Card -->
<meta name="twitter:card" content="summary">
<meta name="twitter:title" content="Camilo Rojas | Abogado JPL">
<meta name="twitter:description" content="Abogado especialista en Juzgados de Policía Local. Multas, Ley del Consumidor, cobranzas y más. Santiago, Chile.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&family=DM+Sans:ital,wght@0,300;0,400;0,500;1,400&display=swap" rel="stylesheet">
<style>
  *, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }

  :root {
    --teal: #0B6B5E;
    --teal-light: #0E8C7A;
    --teal-bg: #E8F5F2;
    --accent: #F27D42;
    --accent-light: #FFF0E8;
    --dark: #1A1A2E;
    --text: #3A3A4A;
    --text-light: #6E6E80;
    --bg: #FAFAF8;
    --white: #FFFFFF;
    --border: #E8E8EC;
    --card-shadow: 0 2px 20px rgba(11,107,94,0.06);
    --radius: 16px;
    --radius-sm: 10px;
  }

  html { scroll-behavior: smooth; }
  body {
    font-family: 'DM Sans', sans-serif;
    color: var(--text);
    line-height: 1.7;
    background: var(--bg);
  }

  /* ─── NAV ─── */
  nav {
    position: fixed; top: 0; left: 0; right: 0; z-index: 100;
    display: flex; align-items: center; justify-content: space-between;
    padding: 1rem 5%;
    background: rgba(250,250,248,0.85);
    backdrop-filter: blur(16px);
    border-bottom: 1px solid transparent;
    transition: all 0.3s;
  }
  nav.scrolled { border-bottom-color: var(--border); }

  .logo {
    font-family: 'Space Grotesk', sans-serif;
    font-weight: 700; font-size: 1.3rem;
    color: var(--dark); text-decoration: none;
  }
  .logo span { color: var(--teal); }

  .nav-links { display: flex; gap: 2rem; list-style: none; align-items: center; }
  .nav-links a {
    color: var(--text-light); text-decoration: none;
    font-size: 0.9rem; font-weight: 500;
    transition: color 0.3s;
  }
  .nav-links a:hover { color: var(--teal); }

  .nav-cta-btn {
    background: var(--teal) !important; color: var(--white) !important;
    padding: 0.6rem 1.5rem; border-radius: 50px;
    font-weight: 600 !important; font-size: 0.85rem !important;
    transition: all 0.3s !important;
  }
  .nav-cta-btn:hover { background: var(--teal-light) !important; transform: translateY(-1px); }

  .menu-toggle { display: none; background: none; border: none; cursor: pointer; }
  .menu-toggle span {
    display: block; width: 22px; height: 2px;
    background: var(--dark); margin: 5px 0; border-radius: 2px; transition: 0.3s;
  }

  /* ─── HERO ─── */
  .hero {
    min-height: 100vh;
    display: flex; align-items: center;
    padding: 7rem 5% 5rem;
    position: relative;
    overflow: hidden;
  }
  .hero-bg-shape {
    position: absolute; top: -200px; right: -150px;
    width: 700px; height: 700px;
    background: var(--teal-bg);
    border-radius: 50%;
    z-index: 0;
  }
  .hero-bg-shape2 {
    position: absolute; bottom: -100px; left: -100px;
    width: 400px; height: 400px;
    background: var(--accent-light);
    border-radius: 50%;
    z-index: 0;
  }

  .hero-inner {
    max-width: 1200px; margin: 0 auto; width: 100%;
    display: grid; grid-template-columns: 1.1fr 0.9fr;
    gap: 4rem; align-items: center;
    position: relative; z-index: 1;
  }

  .hero-badge {
    display: inline-flex; align-items: center; gap: 8px;
    background: var(--teal-bg); color: var(--teal);
    padding: 0.5rem 1rem; border-radius: 50px;
    font-size: 0.82rem; font-weight: 600;
    margin-bottom: 1.5rem;
  }
  .hero-badge::before {
    content: ''; width: 8px; height: 8px;
    background: var(--teal); border-radius: 50%;
  }

  .hero h1 {
    font-family: 'Space Grotesk', sans-serif;
    font-size: clamp(2.5rem, 5vw, 3.8rem);
    font-weight: 700; color: var(--dark);
    line-height: 1.15; margin-bottom: 1.5rem;
  }
  .hero h1 em {
    font-style: normal;
    background: linear-gradient(120deg, var(--teal), var(--teal-light));
    -webkit-background-clip: text; -webkit-text-fill-color: transparent;
    background-clip: text;
  }

  .hero p {
    color: var(--text-light); font-size: 1.1rem;
    max-width: 480px; margin-bottom: 2rem; line-height: 1.8;
  }

  .hero-actions { display: flex; gap: 1rem; flex-wrap: wrap; align-items: center; }

  .btn {
    display: inline-flex; align-items: center; gap: 8px;
    padding: 1rem 2rem; border-radius: 50px;
    text-decoration: none; font-size: 0.92rem;
    font-weight: 600; transition: all 0.3s; cursor: pointer; border: none;
    font-family: 'DM Sans', sans-serif;
  }
  .btn-main {
    background: var(--teal); color: var(--white);
    box-shadow: 0 4px 15px rgba(11,107,94,0.25);
  }
  .btn-main:hover { background: var(--teal-light); transform: translateY(-2px); box-shadow: 0 6px 20px rgba(11,107,94,0.3); }
  .btn-outline {
    background: transparent; color: var(--teal);
    border: 2px solid var(--border);
  }
  .btn-outline:hover { border-color: var(--teal); background: var(--teal-bg); }

  .hero-card {
    background: var(--white);
    border-radius: var(--radius);
    padding: 2.5rem;
    box-shadow: var(--card-shadow);
    border: 1px solid var(--border);
    position: relative;
  }
  .hero-card-tag {
    position: absolute; top: -12px; left: 2rem;
    background: var(--accent); color: var(--white);
    padding: 0.3rem 1rem; border-radius: 50px;
    font-size: 0.75rem; font-weight: 600;
    letter-spacing: 0.5px;
  }
  .hero-card h3 {
    font-family: 'Space Grotesk', sans-serif;
    font-size: 1.1rem; font-weight: 600;
    color: var(--dark); margin-bottom: 1.2rem;
  }
  .hero-card-list { list-style: none; display: grid; gap: 0.8rem; }
  .hero-card-list li {
    display: flex; align-items: center; gap: 10px;
    font-size: 0.92rem; color: var(--text);
  }
  .check {
    width: 22px; height: 22px; border-radius: 50%;
    background: var(--teal-bg); color: var(--teal);
    display: flex; align-items: center; justify-content: center;
    font-size: 0.7rem; flex-shrink: 0; font-weight: 700;
  }

  /* ─── SECTIONS ─── */
  section { padding: 5rem 5%; }
  .container { max-width: 1100px; margin: 0 auto; }

  .section-chip {
    display: inline-flex; align-items: center; gap: 8px;
    background: var(--teal-bg); color: var(--teal);
    padding: 0.4rem 1rem; border-radius: 50px;
    font-size: 0.78rem; font-weight: 600;
    letter-spacing: 0.5px; text-transform: uppercase;
    margin-bottom: 1rem;
  }

  .section-title {
    font-family: 'Space Grotesk', sans-serif;
    font-size: clamp(1.8rem, 3vw, 2.5rem);
    font-weight: 700; color: var(--dark);
    line-height: 1.2; margin-bottom: 1rem;
  }

  /* ─── JPL CASES ─── */
  .jpl { background: var(--white); }
  .jpl-header { text-align: center; max-width: 600px; margin: 0 auto 3rem; }
  .jpl-header p { color: var(--text-light); margin-top: 0.5rem; }

  .jpl-grid {
    display: grid; grid-template-columns: repeat(3, 1fr);
    gap: 1.5rem; max-width: 1100px; margin: 0 auto;
  }
  .jpl-card {
    background: var(--bg); padding: 2rem;
    border-radius: var(--radius); border: 1px solid var(--border);
    transition: all 0.3s; cursor: default;
  }
  .jpl-card:hover {
    transform: translateY(-4px);
    box-shadow: var(--card-shadow);
    border-color: var(--teal);
  }
  .jpl-card-icon {
    width: 50px; height: 50px; border-radius: var(--radius-sm);
    background: var(--teal-bg);
    display: flex; align-items: center; justify-content: center;
    font-size: 1.4rem; margin-bottom: 1.2rem;
  }
  .jpl-card h3 {
    font-family: 'Space Grotesk', sans-serif;
    font-size: 1.1rem; font-weight: 600;
    color: var(--dark); margin-bottom: 0.6rem;
  }
  .jpl-card p { color: var(--text-light); font-size: 0.88rem; line-height: 1.6; }

  /* ─── HOW IT WORKS ─── */
  .process { background: var(--bg); }
  .process-header { text-align: center; max-width: 550px; margin: 0 auto 3rem; }
  .process-header p { color: var(--text-light); margin-top: 0.5rem; }

  .process-steps {
    display: grid; grid-template-columns: repeat(4, 1fr);
    gap: 1.5rem; max-width: 1100px; margin: 0 auto;
    position: relative;
  }
  .process-steps::before {
    content: ''; position: absolute;
    top: 40px; left: 12.5%; right: 12.5%;
    height: 2px; background: var(--border);
    z-index: 0;
  }
  .step {
    text-align: center; position: relative; z-index: 1;
  }
  .step-num {
    width: 56px; height: 56px; border-radius: 50%;
    background: var(--teal); color: var(--white);
    display: flex; align-items: center; justify-content: center;
    font-family: 'Space Grotesk', sans-serif;
    font-size: 1.2rem; font-weight: 700;
    margin: 0 auto 1rem;
    box-shadow: 0 4px 12px rgba(11,107,94,0.2);
  }
  .step h4 {
    font-family: 'Space Grotesk', sans-serif;
    font-size: 1rem; font-weight: 600;
    color: var(--dark); margin-bottom: 0.4rem;
  }
  .step p { color: var(--text-light); font-size: 0.85rem; }

  /* ─── ABOUT ─── */
  .about {
    background: var(--white);
  }
  .about-inner {
    display: grid; grid-template-columns: 0.8fr 1.2fr;
    gap: 4rem; align-items: center;
    max-width: 1100px; margin: 0 auto;
  }
  .about-photo {
    aspect-ratio: 4/5;
    background: linear-gradient(145deg, var(--teal), var(--teal-light));
    border-radius: var(--radius);
    display: flex; align-items: center; justify-content: center;
    position: relative; overflow: hidden;
  }
  .about-initials {
    font-family: 'Space Grotesk', sans-serif;
    font-size: 5rem; font-weight: 700;
    color: rgba(255,255,255,0.15);
    letter-spacing: 8px;
  }
  .about-photo-label {
    position: absolute; bottom: 1.5rem; left: 1.5rem; right: 1.5rem;
    background: rgba(255,255,255,0.15);
    backdrop-filter: blur(10px);
    padding: 1rem 1.2rem; border-radius: var(--radius-sm);
    color: var(--white); font-size: 0.82rem;
    font-weight: 500; text-align: center;
  }
  .about-text p {
    color: var(--text); margin-bottom: 1.2rem; font-size: 1rem;
  }
  .about-highlights {
    display: grid; grid-template-columns: 1fr 1fr;
    gap: 1rem; margin-top: 2rem;
  }
  .highlight-card {
    background: var(--bg); padding: 1.2rem;
    border-radius: var(--radius-sm); border: 1px solid var(--border);
  }
  .highlight-num {
    font-family: 'Space Grotesk', sans-serif;
    font-size: 1.8rem; font-weight: 700; color: var(--teal);
    line-height: 1;
  }
  .highlight-label {
    font-size: 0.82rem; color: var(--text-light); margin-top: 0.3rem;
  }

  /* ─── TESTIMONIALS ─── */
  .testimonials { background: var(--teal); padding: 5rem 5%; }
  .testimonials-inner { max-width: 800px; margin: 0 auto; text-align: center; }
  .testimonials .section-chip { background: rgba(255,255,255,0.15); color: var(--white); }
  .testimonials .section-title { color: var(--white); }

  .testimonial-cards { display: grid; grid-template-columns: 1fr 1fr; gap: 1.5rem; margin-top: 2.5rem; text-align: left; }
  .t-card {
    background: rgba(255,255,255,0.1);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255,255,255,0.15);
    border-radius: var(--radius); padding: 2rem;
  }
  .t-card p {
    color: rgba(255,255,255,0.9); font-size: 0.95rem;
    font-style: italic; margin-bottom: 1.2rem; line-height: 1.7;
  }
  .t-card-author { color: var(--white); font-weight: 600; font-size: 0.9rem; }
  .t-card-role { color: rgba(255,255,255,0.6); font-size: 0.8rem; margin-top: 0.2rem; }
  .stars { color: #FFD166; font-size: 0.9rem; margin-bottom: 0.8rem; letter-spacing: 2px; }

  /* ─── CONTACT ─── */
  .contact { background: var(--bg); }
  .contact-inner {
    display: grid; grid-template-columns: 1fr 1fr;
    gap: 3rem; max-width: 1100px; margin: 0 auto;
  }
  .contact-info p { color: var(--text-light); margin-bottom: 2rem; font-size: 1rem; }

  .contact-cards { display: grid; gap: 1rem; }
  .c-card {
    display: flex; align-items: center; gap: 1rem;
    background: var(--white); padding: 1.2rem 1.5rem;
    border-radius: var(--radius-sm); border: 1px solid var(--border);
    transition: all 0.3s;
  }
  .c-card:hover { border-color: var(--teal); transform: translateX(4px); }
  .c-card-icon {
    width: 42px; height: 42px; border-radius: 10px;
    background: var(--teal-bg);
    display: flex; align-items: center; justify-content: center;
    font-size: 1.1rem; flex-shrink: 0;
  }
  .c-card h4 { font-size: 0.75rem; color: var(--text-light); text-transform: uppercase; letter-spacing: 1px; font-weight: 500; }
  .c-card p, .c-card a {
    font-size: 0.95rem; color: var(--dark); text-decoration: none; font-weight: 500;
  }
  .c-card a:hover { color: var(--teal); }

  .contact-form-box {
    background: var(--white); padding: 2.5rem;
    border-radius: var(--radius); border: 1px solid var(--border);
    box-shadow: var(--card-shadow);
  }
  .contact-form-box h3 {
    font-family: 'Space Grotesk', sans-serif;
    font-size: 1.2rem; font-weight: 600;
    color: var(--dark); margin-bottom: 1.5rem;
  }
  .form-grid { display: grid; gap: 1rem; }
  .form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; }

  .form-grid input,
  .form-grid textarea,
  .form-grid select {
    width: 100%; padding: 0.9rem 1.1rem;
    border: 1.5px solid var(--border); border-radius: var(--radius-sm);
    font-family: 'DM Sans', sans-serif;
    font-size: 0.9rem; color: var(--dark);
    background: var(--bg); transition: border-color 0.3s; outline: none;
  }
  .form-grid input:focus,
  .form-grid textarea:focus,
  .form-grid select:focus { border-color: var(--teal); background: var(--white); }
  .form-grid input::placeholder,
  .form-grid textarea::placeholder { color: #B0B0BA; }
  .form-grid textarea { resize: vertical; min-height: 110px; }

  .btn-submit { width: 100%; justify-content: center; margin-top: 0.5rem; }

  /* ─── WHATSAPP FLOAT ─── */
  .wa-float {
    position: fixed; bottom: 2rem; right: 2rem; z-index: 99;
    width: 60px; height: 60px; border-radius: 50%;
    background: #25D366; color: var(--white);
    display: flex; align-items: center; justify-content: center;
    font-size: 1.8rem; text-decoration: none;
    box-shadow: 0 4px 20px rgba(37,211,102,0.35);
    transition: all 0.3s;
  }
  .wa-float:hover { transform: scale(1.1); box-shadow: 0 6px 25px rgba(37,211,102,0.4); }

  /* ─── FOOTER ─── */
  footer {
    background: var(--dark); padding: 2.5rem 5%;
    display: flex; justify-content: space-between;
    align-items: center; flex-wrap: wrap; gap: 1rem;
  }
  .footer-brand {
    font-family: 'Space Grotesk', sans-serif;
    font-weight: 700; font-size: 1.1rem; color: var(--white);
  }
  .footer-brand span { color: var(--teal-light); }
  footer p { color: rgba(255,255,255,0.4); font-size: 0.8rem; }

  /* ─── RESPONSIVE ─── */
  @media (max-width: 968px) {
    .nav-links { display: none; }
    .menu-toggle { display: block; }
    .nav-links.active {
      display: flex; flex-direction: column;
      position: absolute; top: 100%; left: 0; right: 0;
      background: var(--white); padding: 1.5rem 5%;
      gap: 1rem; border-bottom: 1px solid var(--border);
    }
    .hero-inner { grid-template-columns: 1fr; }
    .hero-card { max-width: 450px; }
    .jpl-grid { grid-template-columns: repeat(2, 1fr); }
    .process-steps { grid-template-columns: repeat(2, 1fr); }
    .process-steps::before { display: none; }
    .about-inner { grid-template-columns: 1fr; }
    .about-photo { max-width: 350px; }
    .testimonial-cards { grid-template-columns: 1fr; }
    .contact-inner { grid-template-columns: 1fr; }
    .hero-bg-shape { width: 400px; height: 400px; top: -100px; right: -100px; }
  }

  @media (max-width: 600px) {
    .jpl-grid { grid-template-columns: 1fr; }
    .process-steps { grid-template-columns: 1fr; gap: 2rem; }
    .form-row { grid-template-columns: 1fr; }
    .about-highlights { grid-template-columns: 1fr; }
    section { padding: 3.5rem 5%; }
  }

  /* ─── ANIMATIONS ─── */
  @media (prefers-reduced-motion: no-preference) {
    .fade-in {
      opacity: 0; transform: translateY(20px);
      transition: opacity 0.6s ease, transform 0.6s ease;
    }
    .fade-in.visible { opacity: 1; transform: translateY(0); }
  }
</style>
</head>
<body>

<!-- NAV -->
<nav id="navbar">
  <a href="#" class="logo">Camilo<span>Rojas</span></a>
  <ul class="nav-links" id="navLinks">
    <li><a href="#inicio">Inicio</a></li>
    <li><a href="#casos">Casos JPL</a></li>
    <li><a href="#proceso">Cómo funciona</a></li>
    <li><a href="#sobre-mi">Sobre mí</a></li>
    <li><a href="#contacto" class="nav-cta-btn">Escríbeme →</a></li>
  </ul>
  <button class="menu-toggle" id="menuToggle" aria-label="Menú">
    <span></span><span></span><span></span>
  </button>
</nav>

<!-- HERO -->
<section class="hero" id="inicio">
  <div class="hero-bg-shape"></div>
  <div class="hero-bg-shape2"></div>
  <div class="hero-inner">
    <div>
      <div class="hero-badge">Abogado especialista JPL</div>
      <h1>Tu caso en el<br>Juzgado de Policía Local<br><em>tiene solución</em></h1>
      <p>Soy Camilo Rojas, abogado dedicado a defender tus derechos en juicios JPL. Multas, infracciones, cobranzas, problemas de consumo — hablemos y busquemos la mejor estrategia juntos.</p>
      <div class="hero-actions">
        <a href="#contacto" class="btn btn-main">Agenda tu consulta</a>
        <a href="#casos" class="btn btn-outline">Ver qué casos llevo</a>
      </div>
    </div>
    <div class="hero-card">
      <div class="hero-card-tag">Primera consulta gratis</div>
      <h3>¿Qué puedo hacer por ti?</h3>
      <ul class="hero-card-list">
        <li><div class="check">✓</div> Multas de tránsito y partes</li>
        <li><div class="check">✓</div> Reclamos de consumo (Ley del Consumidor)</li>
        <li><div class="check">✓</div> Infracciones municipales</li>
        <li><div class="check">✓</div> Cobranzas y deudas en JPL</li>
        <li><div class="check">✓</div> Accidentes de tránsito menores</li>
        <li><div class="check">✓</div> Denuncias por ruidos y molestias vecinales</li>
      </ul>
    </div>
  </div>
</section>

<!-- JPL CASES -->
<section class="jpl" id="casos">
  <div class="jpl-header">
    <div class="section-chip">Áreas de práctica</div>
    <h2 class="section-title">Casos que manejo en JPL</h2>
    <p>Los Juzgados de Policía Local resuelven conflictos cotidianos que afectan tu bolsillo y tu tranquilidad. Yo me encargo.</p>
  </div>
  <div class="jpl-grid">
    <div class="jpl-card fade-in">
      <div class="jpl-card-icon">🚗</div>
      <h3>Multas de Tránsito</h3>
      <p>Partes por exceso de velocidad, luces rojas, documentación y todo tipo de infracciones. Las impugnamos y buscamos la mejor salida.</p>
    </div>
    <div class="jpl-card fade-in">
      <div class="jpl-card-icon">🛒</div>
      <h3>Ley del Consumidor</h3>
      <p>Productos defectuosos, publicidad engañosa, cobros indebidos, garantías no respetadas. Tus derechos como consumidor valen.</p>
    </div>
    <div class="jpl-card fade-in">
      <div class="jpl-card-icon">💰</div>
      <h3>Cobranzas JPL</h3>
      <p>Demandas de cobro, pagarés, deudas impagas. Te defiendo o te ayudo a cobrar lo que te deben.</p>
    </div>
    <div class="jpl-card fade-in">
      <div class="jpl-card-icon">🏠</div>
      <h3>Conflictos Vecinales</h3>
      <p>Ruidos molestos, olores, obras irregulares y problemas entre vecinos que terminan en el juzgado.</p>
    </div>
    <div class="jpl-card fade-in">
      <div class="jpl-card-icon">⚠️</div>
      <h3>Accidentes de Tránsito</h3>
      <p>Choques menores, atropellos y colisiones sin lesiones graves. Defensa y representación ante el JPL.</p>
    </div>
    <div class="jpl-card fade-in">
      <div class="jpl-card-icon">📋</div>
      <h3>Infracciones Municipales</h3>
      <p>Permisos, patentes, aseo, ornato y cualquier infracción a ordenanzas municipales.</p>
    </div>
  </div>
</section>

<!-- PROCESS -->
<section class="process" id="proceso">
  <div class="process-header">
    <div class="section-chip">Paso a paso</div>
    <h2 class="section-title">Así trabajamos juntos</h2>
    <p>Simple, rápido y sin enredos legales. Tú me cuentas, yo me encargo.</p>
  </div>
  <div class="process-steps">
    <div class="step fade-in">
      <div class="step-num">1</div>
      <h4>Me escribes</h4>
      <p>Por WhatsApp, teléfono o el formulario. Cuéntame qué pasó.</p>
    </div>
    <div class="step fade-in">
      <div class="step-num">2</div>
      <h4>Evaluamos tu caso</h4>
      <p>Reviso los antecedentes y te digo las opciones reales que tienes.</p>
    </div>
    <div class="step fade-in">
      <div class="step-num">3</div>
      <h4>Armo la estrategia</h4>
      <p>Preparo la defensa o demanda con toda la documentación.</p>
    </div>
    <div class="step fade-in">
      <div class="step-num">4</div>
      <h4>Te represento</h4>
      <p>Voy al juzgado por ti y te mantengo informado en todo momento.</p>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section class="about" id="sobre-mi">
  <div class="about-inner">
    <div class="about-photo">
      <span class="about-initials">CR</span>
      <div class="about-photo-label">Camilo Alejandro Rojas Mosquera — Abogado</div>
    </div>
    <div class="about-text">
      <div class="section-chip">Sobre mí</div>
      <h2 class="section-title">Hola, soy Camilo Rojas</h2>
      <p>Soy abogado con vocación por la justicia cotidiana. Me especialicé en juicios ante Juzgados de Policía Local porque creo que los problemas del día a día merecen la misma atención profesional que los grandes litigios.</p>
      <p>Mi enfoque es simple: escucharte, explicarte todo en palabras claras y pelear tu caso con la misma energía que si fuera el mío. Nada de jerga legal innecesaria ni procesos eternos.</p>
      <div class="about-highlights">
        <div class="highlight-card">
          <div class="highlight-num">500+</div>
          <div class="highlight-label">Casos en JPL</div>
        </div>
        <div class="highlight-card">
          <div class="highlight-num">92%</div>
          <div class="highlight-label">Resultados favorables</div>
        </div>
        <div class="highlight-card">
          <div class="highlight-num">8+</div>
          <div class="highlight-label">Años de experiencia</div>
        </div>
        <div class="highlight-card">
          <div class="highlight-num">⭐ 4.9</div>
          <div class="highlight-label">Valoración clientes</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- TESTIMONIALS -->
<section class="testimonials">
  <div class="testimonials-inner">
    <div class="section-chip">Lo que dicen mis clientes</div>
    <h2 class="section-title">Historias reales, resultados reales</h2>
    <div class="testimonial-cards">
      <div class="t-card fade-in">
        <div class="stars">★★★★★</div>
        <p>"Me llegó un parte por una luz roja que yo no me pasé. Camilo presentó las pruebas y me absolvieron. Súper recomendado."</p>
        <div class="t-card-author">Roberto Sánchez</div>
        <div class="t-card-role">Multa de tránsito — Providencia</div>
      </div>
      <div class="t-card fade-in">
        <div class="stars">★★★★★</div>
        <p>"Compré un refrigerador que salió malo y la tienda no quería responder. Camilo ganó el caso y me devolvieron toda la plata."</p>
        <div class="t-card-author">Andrea Vega</div>
        <div class="t-card-role">Ley del Consumidor — Las Condes</div>
      </div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section class="contact" id="contacto">
  <div class="contact-inner">
    <div class="contact-info">
      <div class="section-chip">Contacto</div>
      <h2 class="section-title">¿Tienes un problema legal? Hablemos</h2>
      <p>La primera consulta es gratis y sin compromiso. Cuéntame tu caso y vemos juntos qué se puede hacer.</p>
      <div class="contact-cards">
        <div class="c-card">
          <div class="c-card-icon">📱</div>
          <div>
            <h4>WhatsApp</h4>
            <a href="https://wa.me/56912345678">+56 9 1234 5678</a>
          </div>
        </div>
        <div class="c-card">
          <div class="c-card-icon">📞</div>
          <div>
            <h4>Teléfono</h4>
            <a href="tel:+56912345678">+56 9 1234 5678</a>
          </div>
        </div>
        <div class="c-card">
          <div class="c-card-icon">✉️</div>
          <div>
            <h4>Email</h4>
            <a href="mailto:camilo@rojasabogado.cl">camilo@rojasabogado.cl</a>
          </div>
        </div>
        <div class="c-card">
          <div class="c-card-icon">📍</div>
          <div>
            <h4>Ubicación</h4>
            <p>Santiago, Chile</p>
          </div>
        </div>
      </div>
    </div>
    <div class="contact-form-box">
      <h3>Escríbeme directo 👇</h3>
      <div class="form-grid">
        <div class="form-row">
          <input type="text" placeholder="Tu nombre">
          <input type="tel" placeholder="Teléfono">
        </div>
        <input type="email" placeholder="Email">
        <select>
          <option value="" disabled selected>¿Qué tipo de caso tienes?</option>
          <option>Multa de tránsito</option>
          <option>Ley del Consumidor</option>
          <option>Cobranza</option>
          <option>Conflicto vecinal</option>
          <option>Accidente de tránsito</option>
          <option>Infracción municipal</option>
          <option>Otro</option>
        </select>
        <textarea placeholder="Cuéntame brevemente qué pasó..."></textarea>
        <button class="btn btn-main btn-submit" onclick="alert('¡Mensaje enviado! Te contactaré pronto, Camilo Rojas.')">Enviar mensaje →</button>
      </div>
    </div>
  </div>
</section>

<!-- WHATSAPP FLOAT -->
<a href="https://wa.me/56912345678" class="wa-float" target="_blank" aria-label="WhatsApp">💬</a>

<!-- FOOTER -->
<footer>
  <div class="footer-brand">Camilo<span>Rojas</span> — Abogado JPL</div>
  <p>&copy; 2026 Camilo Rojas Mosquera. Todos los derechos reservados.</p>
</footer>

<script>
  // Nav scroll
  window.addEventListener('scroll', () => {
    document.getElementById('navbar').classList.toggle('scrolled', window.scrollY > 50);
  });

  // Mobile menu
  document.getElementById('menuToggle').addEventListener('click', () => {
    document.getElementById('navLinks').classList.toggle('active');
  });

  // Fade in on scroll
  const obs = new IntersectionObserver((entries) => {
    entries.forEach(e => { if (e.isIntersecting) e.target.classList.add('visible'); });
  }, { threshold: 0.15 });
  document.querySelectorAll('.fade-in').forEach(el => obs.observe(el));

  // Smooth scroll
  document.querySelectorAll('a[href^="#"]').forEach(a => {
    a.addEventListener('click', e => {
      const t = document.querySelector(a.getAttribute('href'));
      if (t) { e.preventDefault(); t.scrollIntoView({ behavior: 'smooth' }); }
      document.getElementById('navLinks').classList.remove('active');
    });
  });
</script>

</body>
</html>
