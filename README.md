
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#17120f">

  <title>Dor Dor Events and Services | Making Every Moment Special</title>
  <meta name="description" content="Dor Dor Events and Services helps you plan beautiful, memorable events. Contact us for event planning, decoration and special celebrations.">
  <meta name="keywords" content="Dor Dor Events, event planning, event decoration, wedding planner, birthday events, Nigeria">
  <meta property="og:title" content="Dor Dor Events and Services">
  <meta property="og:description" content="Your vision, our creativity. Let's make your next event unforgettable.">
  <meta property="og:type" content="website">

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Playfair+Display:wght@400;500;600;700&display=swap" rel="stylesheet">

  <style>
    :root {
      --dark: #17120f;
      --dark-soft: #241b16;
      --gold: #d6ae70;
      --gold-light: #f0d6a6;
      --cream: #faf6ef;
      --white: #ffffff;
      --muted: #a99b8e;
      --text: #332820;
      --radius: 18px;
      --shadow: 0 12px 40px rgba(0,0,0,.09);
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
      scroll-padding-top: 85px;
    }

    body {
      font-family: "DM Sans", sans-serif;
      color: var(--text);
      background: var(--cream);
      line-height: 1.7;
      overflow-x: hidden;
    }

    img {
      display: block;
      width: 100%;
      object-fit: cover;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    button, input, select, textarea {
      font: inherit;
    }

    button, a {
      -webkit-tap-highlight-color: transparent;
    }

    .container {
      width: min(1140px, 90%);
      margin: auto;
    }

    .section {
      padding: 95px 0;
    }

    .eyebrow {
      color: #a47a3e;
      font-size: .77rem;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 3px;
      margin-bottom: 12px;
    }

    .section-title {
      font-family: "Playfair Display", serif;
      font-size: clamp(2.1rem, 4vw, 3.3rem);
      line-height: 1.2;
      margin-bottom: 18px;
      color: var(--dark);
    }

    .section-intro {
      max-width: 620px;
      color: #76695f;
      margin-bottom: 42px;
    }

    .center {
      text-align: center;
    }

    .center .section-intro {
      margin-left: auto;
      margin-right: auto;
    }

    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 9px;
      border: 1px solid transparent;
      border-radius: 5px;
      padding: 14px 23px;
      font-weight: 700;
      font-size: .9rem;
      cursor: pointer;
      transition: .25s ease;
    }

    .btn-gold {
      color: var(--dark);
      background: var(--gold);
    }

    .btn-gold:hover {
      background: var(--gold-light);
      transform: translateY(-2px);
    }

    .btn-outline {
      border-color: rgba(255,255,255,.55);
      color: white;
      background: transparent;
    }

    .btn-outline:hover {
      background: white;
      color: var(--dark);
    }

    /* Navigation */

    .navbar {
      position: sticky;
      top: 0;
      z-index: 1000;
      background: rgba(23,18,15,.97);
      backdrop-filter: blur(12px);
      border-bottom: 1px solid rgba(214,174,112,.18);
    }

    .nav-inner {
      min-height: 78px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 25px;
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 11px;
      color: white;
      flex-shrink: 0;
    }

    .brand-mark {
      display: grid;
      place-items: center;
      width: 44px;
      height: 44px;
      border: 1px solid var(--gold);
      color: var(--gold);
      font-family: "Playfair Display", serif;
      font-size: 1.25rem;
    }

    .brand-name {
      font-family: "Playfair Display", serif;
      font-size: 1.08rem;
      line-height: 1.2;
    }

    .brand-name small {
      display: block;
      font-family: "DM Sans", sans-serif;
      font-size: .64rem;
      color: var(--gold);
      letter-spacing: 2px;
      text-transform: uppercase;
      margin-top: 4px;
    }

    .nav-links {
      display: flex;
      align-items: center;
      gap: 25px;
      list-style: none;
      color: #eee4d9;
      font-size: .85rem;
    }

    .nav-links a:hover {
      color: var(--gold);
    }

    .nav-cta {
      background: var(--gold);
      color: var(--dark) !important;
      padding: 10px 16px;
      border-radius: 4px;
      font-weight: 700;
    }

    .menu-toggle {
      display: none;
      border: 1px solid #635143;
      background: transparent;
      color: white;
      padding: 8px 12px;
      font-size: 1.35rem;
      cursor: pointer;
    }

    /* Hero */

    .hero {
      min-height: 650px;
      display: flex;
      align-items: center;
      color: white;
      background:
        linear-gradient(90deg, rgba(18,13,10,.91) 0%, rgba(18,13,10,.70) 48%, rgba(18,13,10,.22) 100%),
        url("https://images.unsplash.com/photo-1519167758481-83f550bb49b3?auto=format&fit=crop&w=2000&q=85")
        center 52% / cover no-repeat;
    }

    .hero-content {
      max-width: 720px;
      padding: 100px 0;
    }

    .hero .eyebrow {
      color: var(--gold-light);
    }

    .hero h1 {
      font-family: "Playfair Display", serif;
      font-size: clamp(3rem, 7vw, 5.5rem);
      line-height: 1.06;
      font-weight: 500;
      margin-bottom: 24px;
    }

    .hero h1 span {
      color: var(--gold-light);
      font-style: italic;
    }

    .hero p {
      max-width: 570px;
      color: #e4d8ce;
      margin-bottom: 30px;
      font-size: 1.03rem;
    }

    .hero-actions {
      display: flex;
      flex-wrap: wrap;
      gap: 14px;
    }

    .hero-note {
      display: flex;
      gap: 12px;
      align-items: center;
      margin-top: 45px;
      color: #e5d7c9;
      font-size: .83rem;
    }

    .hero-note span {
      color: var(--gold);
      font-size: 1.2rem;
    }

    /* Highlights */

    .highlights {
      background: var(--dark-soft);
      color: white;
    }

    .highlight-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
    }

    .highlight {
      text-align: center;
      padding: 30px 20px;
      border-right: 1px solid rgba(255,255,255,.13);
    }

    .highlight:last-child {
      border-right: 0;
    }

    .highlight strong {
      display: block;
      font-family: "Playfair Display", serif;
      color: var(--gold);
      font-size: 1.3rem;
      margin-bottom: 5px;
    }

    .highlight p {
      color: #d0c2b6;
      font-size: .85rem;
    }

    /* About */

    .about-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 70px;
      align-items: center;
    }

    .about-images {
      position: relative;
      padding: 0 25px 25px 0;
    }

    .about-images img {
      height: 490px;
      border-radius: 3px;
    }

    .about-stamp {
      position: absolute;
      right: 0;
      bottom: 0;
      width: 180px;
      padding: 24px 20px;
      background: var(--dark);
      color: white;
      text-align: center;
      border: 1px solid var(--gold);
    }

    .about-stamp strong {
      display: block;
      color: var(--gold);
      font-family: "Playfair Display", serif;
      font-size: 1.25rem;
    }

    .about-stamp small {
      font-size: .77rem;
    }

    .about-copy p {
      color: #74665a;
      margin-bottom: 17px;
    }

    .check-list {
      list-style: none;
      margin: 25px 0 30px;
    }

    .check-list li {
      margin-bottom: 12px;
      font-weight: 600;
    }

    .check-list li::before {
      content: "✓";
      color: #a47a3e;
      margin-right: 12px;
      font-weight: 700;
    }

    /* Services */

    .services {
      background: #f0e8dc;
    }

    .service-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 23px;
    }

    .service-card {
      background: white;
      padding: 32px 27px;
      border-bottom: 3px solid transparent;
      transition: .25s ease;
      box-shadow: 0 5px 22px rgba(0,0,0,.035);
    }

    .service-card:hover {
      transform: translateY(-6px);
      border-bottom-color: var(--gold);
      box-shadow: var(--shadow);
    }

    .service-icon {
      width: 54px;
      height: 54px;
      display: grid;
      place-items: center;
      background: #f7efe2;
      color: #8d652e;
      font-size: 1.5rem;
      margin-bottom: 22px;
      border-radius: 50%;
    }

    .service-card h3 {
      font-family: "Playfair Display", serif;
      font-size: 1.35rem;
      margin-bottom: 12px;
    }

    .service-card p {
      color: #796c61;
      font-size: .91rem;
      margin-bottom: 20px;
    }

    .service-link {
      color: #926a34;
      font-weight: 700;
      font-size: .87rem;
    }

    /* Gallery */

    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 17px;
    }

    .gallery-item {
      position: relative;
      overflow: hidden;
      min-height: 250px;
      background: #e3d8c9;
      cursor: pointer;
      border: 0;
      padding: 0;
      text-align: left;
    }

    .gallery-item img {
      height: 100%;
      min-height: 250px;
      position: absolute;
      inset: 0;
      transition: transform .5s ease;
    }

    .gallery-item:hover img {
      transform: scale(1.07);
    }

    .gallery-item::after {
      content: "";
      position: absolute;
      inset: 35% 0 0;
      background: linear-gradient(transparent, rgba(0,0,0,.78));
    }

    .gallery-caption {
      position: absolute;
      z-index: 1;
      left: 20px;
      right: 15px;
      bottom: 17px;
      color: white;
      font-family: "Playfair Display", serif;
      font-size: 1.25rem;
    }

    .gallery-caption small {
      display: block;
      color: var(--gold-light);
      font-family: "DM Sans", sans-serif;
      font-size: .72rem;
      letter-spacing: 1px;
      margin-bottom: 3px;
      text-transform: uppercase;
    }

    .gallery-item:nth-child(2),
    .gallery-item:nth-child(5) {
      transform: translateY(18px);
    }

    /* Process */

    .process {
      background: var(--dark);
      color: white;
    }

    .process .section-title {
      color: white;
    }

    .process .section-intro {
      color: #c7b9ad;
    }

    .process-grid {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 25px;
    }

    .process-step {
      border-top: 1px solid #6e5946;
      padding-top: 22px;
    }

    .step-number {
      color: var(--gold);
      font-family: "Playfair Display", serif;
      font-size: 2rem;
      margin-bottom: 15px;
    }

    .process-step h3 {
      font-size: 1.04rem;
      margin-bottom: 10px;
    }

    .process-step p {
      color: #c7b9ad;
      font-size: .87rem;
    }

    /* Testimonials */

    .testimonial-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
    }

    .testimonial {
      padding: 28px;
      background: white;
      border: 1px solid #eee4d7;
    }

    .stars {
      color: #b88842;
      letter-spacing: 3px;
      margin-bottom: 16px;
    }

    .testimonial blockquote {
      color: #6e6156;
      font-size: .94rem;
      margin-bottom: 20px;
    }

    .testimonial strong {
      font-size: .89rem;
    }

    .testimonial small {
      display: block;
      color: #a09184;
    }

    /* FAQs */

    .faq-list {
      max-width: 800px;
      margin: 0 auto;
    }

    .faq-item {
      border-bottom: 1px solid #e2d6c8;
    }

    .faq-question {
      width: 100%;
      padding: 22px 0;
      background: none;
      border: 0;
      color: var(--dark);
      display: flex;
      justify-content: space-between;
      gap: 20px;
      text-align: left;
      font-weight: 700;
      cursor: pointer;
    }

    .faq-question span:last-child {
      color: #a47a3e;
      font-size: 1.2rem;
    }

    .faq-answer {
      padding: 0 30px 22px 0;
      color: #74665a;
      font-size: .92rem;
    }

    [hidden] {
      display: none !important;
    }

    /* Contact */

    .contact {
      background: #eee5d9;
    }

    .contact-grid {
      display: grid;
      grid-template-columns: .85fr 1.15fr;
      gap: 55px;
      align-items: start;
    }

    .contact-copy p {
      color: #74665a;
      margin-bottom: 28px;
    }

    .contact-detail {
      display: flex;
      gap: 15px;
      align-items: flex-start;
      margin-bottom: 24px;
    }

    .contact-icon {
      width: 45px;
      height: 45px;
      display: grid;
      place-items: center;
      background: var(--dark);
      color: var(--gold);
      flex-shrink: 0;
      border-radius: 50%;
    }

    .contact-detail strong {
      display: block;
      margin-bottom: 3px;
    }

    .contact-detail a,
    .contact-detail span {
      color: #786a5f;
      font-size: .91rem;
      overflow-wrap: anywhere;
    }

    .contact-form {
      background: white;
      padding: 35px;
      box-shadow: var(--shadow);
    }

    .contact-form h3 {
      font-family: "Playfair Display", serif;
      font-size: 1.65rem;
      margin-bottom: 8px;
    }

    .form-note {
      color: #86786d;
      font-size: .84rem;
      margin-bottom: 23px;
    }

    .form-row {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 15px;
    }

    .form-group {
      margin-bottom: 17px;
    }

    .form-group label {
      display: block;
      font-weight: 700;
      font-size: .82rem;
      margin-bottom: 7px;
    }

    .form-group input,
    .form-group select,
    .form-group textarea {
      width: 100%;
      padding: 12px 13px;
      border: 1px solid #e1d7cb;
      background: #fdfbf8;
      border-radius: 4px;
      outline: none;
      color: var(--text);
    }

    .form-group input:focus,
    .form-group select:focus,
    .form-group textarea:focus {
      border-color: #ad854c;
      box-shadow: 0 0 0 2px rgba(214,174,112,.18);
    }

    .form-group textarea {
      min-height: 115px;
      resize: vertical;
    }

    .contact-form .btn {
      width: 100%;
    }

    .privacy-note {
      color: #86786d;
      font-size: .75rem;
      margin-top: 12px;
      text-align: center;
    }

    /* Final CTA */

    .final-cta {
      padding: 75px 0;
      text-align: center;
      color: white;
      background:
        linear-gradient(rgba(25,18,13,.86), rgba(25,18,13,.86)),
        url("https://images.unsplash.com/photo-1464366400600-7168b8af9bc3?auto=format&fit=crop&w=1800&q=80")
        center / cover no-repeat;
    }

    .final-cta h2 {
      font-family: "Playfair Display", serif;
      font-size: clamp(2.2rem, 4vw, 3.6rem);
      margin-bottom: 15px;
    }

    .final-cta p {
      color: #e0d2c4;
      margin-bottom: 25px;
    }

    /* Footer */

    footer {
      background: #110d0a;
      color: #d2c5b9;
      padding: 45px 0 20px;
    }

    .footer-grid {
      display: grid;
      grid-template-columns: 1.3fr 1fr 1fr;
      gap: 40px;
      padding-bottom: 32px;
    }

    .footer-about p {
      margin-top: 16px;
      max-width: 350px;
      color: #a99b8e;
      font-size: .87rem;
    }

    footer h4 {
      color: white;
      margin-bottom: 15px;
    }

    .footer-links {
      list-style: none;
    }

    .footer-links li {
      margin-bottom: 9px;
      font-size: .87rem;
    }

    .footer-links a:hover {
      color: var(--gold);
    }

    .copyright {
      padding-top: 20px;
      border-top: 1px solid #352920;
      display: flex;
      justify-content: space-between;
      gap: 15px;
      flex-wrap: wrap;
      color: #958578;
      font-size: .79rem;
    }

    /* Floating WhatsApp */

    .whatsapp-float {
      position: fixed;
      right: 20px;
      bottom: 22px;
      z-index: 900;
      width: 60px;
      height: 60px;
      display: grid;
      place-items: center;
      border-radius: 50%;
      background: #25d366;
      color: white;
      font-size: 1.7rem;
      box-shadow: 0 6px 22px rgba(0,0,0,.22);
      transition: transform .2s;
    }

    .whatsapp-float:hover {
      transform: scale(1.08);
    }

    /* Gallery lightbox */

    .lightbox {
      position: fixed;
      inset: 0;
      z-index: 2000;
      background: rgba(0,0,0,.91);
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 25px;
    }

    .lightbox img {
      max-width: min(100%, 1000px);
      max-height: 80vh;
      width: auto;
      height: auto;
      object-fit: contain;
    }

    .lightbox-close {
      position: absolute;
      top: 18px;
      right: 24px;
      border: 0;
      background: none;
      color: white;
      font-size: 2.5rem;
      cursor: pointer;
    }

    /* Scroll reveal */

    .reveal {
      opacity: 0;
      transform: translateY(20px);
      transition: opacity .6s ease, transform .6s ease;
    }

    .reveal.visible {
      opacity: 1;
      transform: translateY(0);
    }

    @media (prefers-reduced-motion: reduce) {
      *, *::before, *::after {
        scroll-behavior: auto !important;
        transition-duration: .01ms !important;
        animation-duration: .01ms !important;
      }

      .reveal {
        opacity: 1;
        transform: none;
      }
    }

    /* Mobile */

    @media (max-width: 900px) {
      .nav-links {
        gap: 15px;
        font-size: .8rem;
      }

      .about-grid {
        gap: 35px;
      }

      .service-grid {
        grid-template-columns: repeat(2, 1fr);
      }

      .process-grid {
        grid-template-columns: repeat(2, 1fr);
      }

      .contact-grid {
        gap: 30px;
      }
    }

    @media (max-width: 700px) {
      .section {
        padding: 70px 0;
      }

      .nav-inner {
        min-height: 70px;
      }

      .menu-toggle {
        display: block;
      }

      .nav-links {
        display: none;
        position: absolute;
        top: 70px;
        left: 0;
        right: 0;
        padding: 22px 5% 27px;
        background: var(--dark);
        flex-direction: column;
        align-items: stretch;
        gap: 0;
        border-top: 1px solid #403024;
      }

      .nav-links.open {
        display: flex;
      }

      .nav-links li a {
        display: block;
        padding: 12px 0;
      }

      .nav-links .nav-cta {
        text-align: center;
        margin-top: 8px;
      }

      .hero {
        min-height: 590px;
        background-position: 58% center;
      }

      .hero-content {
        padding: 75px 0;
      }

      .hero h1 {
        font-size: clamp(2.8rem, 12vw, 4.2rem);
      }

      .highlight {
        padding: 23px 10px;
      }

      .highlight strong {
        font-size: 1.02rem;
      }

      .highlight p {
        font-size: .73rem;
      }

      .about-grid,
      .contact-grid {
        grid-template-columns: 1fr;
      }

      .about-images img {
        height: 360px;
      }

      .service-grid,
      .gallery-grid,
      .testimonial-grid {
        grid-template-columns: 1fr;
      }

      .gallery-item,
      .gallery-item img {
        min-height: 300px;
      }

      .gallery-item:nth-child(2),
      .gallery-item:nth-child(5) {
        transform: none;
      }

      .process-grid {
        grid-template-columns: 1fr 1fr;
      }

      .footer-grid {
        grid-template-columns: 1fr;
        gap: 25px;
      }

      .contact-form {
        padding: 24px 19px;
      }

      .form-row {
        grid-template-columns: 1fr;
        gap: 0;
      }

      .whatsapp-float {
        width: 55px;
        height: 55px;
        right: 14px;
        bottom: 15px;
      }
    }

    @media (max-width: 380px) {
      .brand-name {
        font-size: .93rem;
      }

      .brand-mark {
        width: 38px;
        height: 38px;
      }

      .process-grid {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>

<body>

  <!-- Navigation -->
  <header class="navbar">
    <div class="container nav-inner">
      <a class="brand" href="#home" aria-label="Dor Dor Events homepage">
        <span class="brand-mark">DD</span>
        <span class="brand-name">
          Dor Dor
          <small>Events &amp; Services</small>
        </span>
      </a>

      <button class="menu-toggle" id="menuToggle"
        aria-label="Open navigation menu"
        aria-expanded="false" aria-controls="navLinks">☰</button>

      <nav aria-label="Main navigation">
        <ul class="nav-links" id="navLinks">
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About Us</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#gallery">Gallery</a></li>
          <li><a href="#faq">FAQs</a></li>
          <li><a class="nav-cta" href="#contact">Plan Your Event ↗</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main>
    <!-- Hero -->
    <section class="hero" id="home">
      <div class="container">
        <div class="hero-content">
          <div class="eyebrow">Your moments deserve the best</div>

          <h1>Making Every Moment <span>Special.</span></h1>

          <p>
            From beautiful celebrations to unforgettable gatherings,
            Dor Dor Events and Services helps turn your ideas into
            memorable experiences. Your vision, our creativity.
          </p>

          <div class="hero-actions">
            <a href="#contact" class="btn btn-gold">Plan Your Event ↗</a>
            <a href="#services" class="btn btn-outline">Explore Our Services</a>
          </div>

          <div class="hero-note">
            <span>✦</span>
            Thoughtful planning. Beautiful details. Lasting memories.
          </div>
        </div>
      </div>
    </section>

    <!-- Highlights -->
    <section class="highlights" aria-label="Our values">
      <div class="container highlight-grid">
        <div class="highlight">
          <strong>Personalised</strong>
          <p>Events designed around your vision</p>
        </div>
        <div class="highlight">
          <strong>Detail-Focused</strong>
          <p>Care in every special touch</p>
        </div>
        <div class="highlight">
          <strong>Memorable</strong>
          <p>Celebrations worth remembering</p>
        </div>
      </div>
    </section>

    <!-- About -->
    <section class="section" id="about">
      <div class="container about-grid">
        <div class="about-images reveal">
          <img
            src="https://images.unsplash.com/photo-1511795409834-ef04bbd61622?auto=format&fit=crop&w=1000&q=85"
            alt="Elegant event venue decorated for a special occasion"
            loading="lazy">
          <div class="about-stamp">
            <strong>Dor Dor</strong>
            <small>Making your moments meaningful</small>
          </div>
        </div>

        <div class="about-copy reveal">
          <div class="eyebrow">A little about us</div>
          <h2 class="section-title">Every celebration has a story.</h2>

          <p>
            At Dor Dor Events and Services, we believe that the best
            celebrations are the ones that feel personal. Every detail
            matters, from the first idea to the final finishing touch.
          </p>

          <p>
            Our goal is to help you bring your vision to life with
            creativity, thoughtful organisation and attention to the
            details that make an occasion unique.
          </p>

          <ul class="check-list">
            <li>Creative ideas tailored to your occasion</li>
            <li>Attention to details and presentation</li>
            <li>Planning around your needs and budget</li>
            <li>A friendly, personalised experience</li>
          </ul>

          <a class="btn btn-gold" href="#contact">Let's Talk About Your Event</a>
        </div>
      </div>
    </section>

    <!-- Services -->
    <section class="section services" id="services">
      <div class="container">
        <div class="center reveal">
          <div class="eyebrow">What we do</div>
          <h2 class="section-title">Our Services</h2>
          <p class="section-intro">
            Whatever the occasion, let's create an experience that
            reflects your style, your story and your budget.
          </p>
        </div>

        <div class="service-grid">
          <article class="service-card reveal">
            <div class="service-icon">✧</div>
            <h3>Event Planning</h3>
            <p>
              Thoughtful coordination and organisation to help your
              celebration run smoothly from beginning to end.
            </p>
            <a href="#contact" class="service-link"
              data-service="Event Planning">Enquire about this service →</a>
          </article>

          <article class="service-card reveal">
            <div class="service-icon">❀</div>
            <h3>Event Decoration</h3>
            <p>
              Beautiful themes, carefully selected details and
              attractive spaces tailored to your occasion.
            </p>
            <a href="#contact" class="service-link"
              data-service="Event Decoration">Enquire about this service →</a>
          </article>

          <article class="service-card reveal">
            <div class="service-icon">♡</div>
            <h3>Weddings &amp; Engagements</h3>
            <p>
              Celebrate your love with a special occasion planned
              around your vision and preferences.
            </p>
            <a href="#contact" class="service-link"
              data-service="Wedding or Engagement">Enquire about this service →</a>
          </article>

          <article class="service-card reveal">
            <div class="service-icon">🎂</div>
            <h3>Birthdays &amp; Celebrations</h3>
            <p>
              Make birthdays, anniversaries and milestones feel
              extra special with a personal touch.
            </p>
            <a href="#contact" class="service-link"
              data-service="Birthday or Celebration">Enquire about this service →</a>
          </article>

          <article class="service-card reveal">
            <div class="service-icon">♧</div>
            <h3>Corporate Events</h3>
            <p>
              Give your business gatherings, launches and special
              occasions a polished, professional feel.
            </p>
            <a href="#contact" class="service-link"
              data-service="Corporate Event">Enquire about this service →</a>
          </article>

          <article class="service-card reveal">
            <div class="service-icon">✦</div>
            <h3>Other Event Services</h3>
            <p>
              Have a different occasion in mind? Tell us what you
              need, and let's discuss how we can help.
            </p>
            <a href="#contact" class="service-link"
              data-service="Other Event Service">Tell us what you need →</a>
          </article>
        </div>

        <p class="center" style="margin-top:30px;color:#796c61;font-size:.82rem">
          Please enquire to confirm available services, packages and pricing.
        </p>
      </div>
    </section>

    <!-- Gallery -->
    <section class="section" id="gallery">
      <div class="container">
        <div class="center reveal">
          <div class="eyebrow">Visual inspiration</div>
          <h2 class="section-title">Ideas Worth Celebrating</h2>
          <p class="section-intro">
            Explore a few event inspirations. Replace these sample
            photographs with pictures of your own work to make this
            gallery truly yours.
          </p>
        </div>

        <div class="gallery-grid">
          <button class="gallery-item reveal" type="button"
            data-full="https://images.unsplash.com/photo-1519167758481-83f550bb49b3?auto=format&fit=crop&w=1600&q=90"
            aria-label="View wedding reception inspiration">
            <img src="https://images.unsplash.com/photo-1519167758481-83f550bb49b3?auto=format&fit=crop&w=800&q=80"
              alt="Elegant wedding reception setup" loading="lazy">
            <span class="gallery-caption"><small>01 / Weddings</small>Elegant Celebrations</span>
          </button>

          <button class="gallery-item reveal" type="button"
            data-full="https://images.unsplash.com/photo-1530103862676-de8c9debad1d?auto=format&fit=crop&w=1600&q=90"
            aria-label="View party decoration inspiration">
            <img src="https://images.unsplash.com/photo-1530103862676-de8c9debad1d?auto=format&fit=crop&w=800&q=80"
              alt="Colourful celebration and party decorations" loading="lazy">
            <span class="gallery-caption"><small>02 / Parties</small>Joyful Moments</span>
          </button>

          <button class="gallery-item reveal" type="button"
            data-full="https://images.unsplash.com/photo-1464366400600-7168b8af9bc3?auto=format&fit=crop&w=1600&q=90"
            aria-label="View table styling inspiration">
            <img src="https://images.unsplash.com/photo-1464366400600-7168b8af9bc3?auto=format&fit=crop&w=800&q=80"
              alt="Beautifully styled event table" loading="lazy">
            <span class="gallery-caption"><small>03 / Styling</small>Beautiful Details</span>
          </button>

          <button class="gallery-item reveal" type="button"
            data-full="https://images.unsplash.com/photo-1470229722913-7c0e2dbbafd3?auto=format&fit=crop&w=1600&q=90"
            aria-label="View live event inspiration">
            <img src="https://images.unsplash.com/photo-1470229722913-7c0e2dbbafd3?auto=format&fit=crop&w=800&q=80"
              alt="Lights and atmosphere at a live event" loading="lazy">
            <span class="gallery-caption"><small>04 / Experiences</small>Unforgettable Nights</span>
          </button>

          <button class="gallery-item reveal" type="button"
            data-full="https://images.unsplash.com/photo-1511795409834-ef04bbd61622?auto=format&fit=crop&w=1600&q=90"
            aria-label="View formal event venue inspiration">
            <img src="https://images.unsplash.com/photo-1511795409834-ef04bbd61622?auto=format&fit=crop&w=800&q=80"
              alt="Formal event venue with elegant styling" loading="lazy">
            <span class="gallery-caption"><small>05 / Venues</small>Refined Atmosphere</span>
          </button>

          <button class="gallery-item reveal" type="button"
            data-full="https://images.unsplash.com/photo-1519741497674-611481863552?auto=format&fit=crop&w=1600&q=90"
            aria-label="View wedding celebration inspiration">
            <img src="https://images.unsplash.com/photo-1519741497674-611481863552?auto=format&fit=crop&w=800&q=80"
              alt="Romantic wedding celebration inspiration" loading="lazy">
            <span class="gallery-caption"><small>06 / Special Days</small>Moments to Treasure</span>
          </button>
        </div>
      </div>
    </section>

    <!-- Process -->
    <section class="section process">
      <div class="container">
        <div class="eyebrow">Simple and stress-free</div>
        <h2 class="section-title">How It Works</h2>
        <p class="section-intro">
          Getting started is easy. Tell us your idea, and we can
          discuss the next steps together.
        </p>

        <div class="process-grid">
          <div class="process-step reveal">
            <div class="step-number">01</div>
            <h3>Tell Us Your Vision</h3>
            <p>Share your occasion, ideas, preferred date and budget.</p>
          </div>
          <div class="process-step reveal">
            <div class="step-number">02</div>
            <h3>Discuss Your Plan</h3>
            <p>We'll discuss your requirements and available options.</p>
          </div>
          <div class="process-step reveal">
            <div class="step-number">03</div>
            <h3>Confirm the Details</h3>
            <p>Agree on the services, costs, timing and arrangements.</p>
          </div>
          <div class="process-step reveal">
            <div class="step-number">04</div>
            <h3>Celebrate Your Day</h3>
            <p>Enjoy your special occasion with the agreed plan in place.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Testimonials -->
    <section class="section" id="testimonials">
      <div class="container">
        <div class="center">
          <div class="eyebrow">Client experiences</div>
          <h2 class="section-title">A Word From Our Clients</h2>
          <p class="section-intro">
            Your customers' experiences help new clients feel confident
            about choosing your business.
          </p>
        </div>

        <!-- Replace these sample quotes with genuine client reviews. -->
        <div class="testimonial-grid">
          <article class="testimonial">
            <div class="stars" aria-label="Five stars">★★★★★</div>
            <blockquote>
              “[Add a genuine review from a client about their event
              and what they appreciated most.]”
            </blockquote>
            <strong>Client Name</strong>
            <small>Event type</small>
          </article>

          <article class="testimonial">
            <div class="stars" aria-label="Five stars">★★★★★</div>
            <blockquote>
              “[Add another real client's feedback about the service,
              organisation or event decoration.]”
            </blockquote>
            <strong>Client Name</strong>
            <small>Event type</small>
          </article>

          <article class="testimonial">
            <div class="stars" aria-label="Five stars">★★★★★</div>
            <blockquote>
              “[Add an honest review from a customer who has worked
              with Dor Dor Events and Services.]”
            </blockquote>
            <strong>Client Name</strong>
            <small>Event type</small>
          </article>
        </div>
      </div>
    </section>

    <!-- FAQ -->
    <section class="section" id="faq" style="background:#f0e8dc">
      <div class="container">
        <div class="center">
          <div class="eyebrow">Good to know</div>
          <h2 class="section-title">Frequently Asked Questions</h2>
          <p class="section-intro">
            Here are some useful things to know before making an enquiry.
          </p>
        </div>

        <div class="faq-list">
          <div class="faq-item">
            <button class="faq-question" aria-expanded="false">
              <span>What types of events do you handle?</span>
              <span>+</span>
            </button>
            <div class="faq-answer" hidden>
              We welcome enquiries for weddings, birthdays, engagements,
              corporate gatherings and other special occasions. Contact
              us to confirm the services available for your event.
            </div>
          </div>

          <div class="faq-item">
            <button class="faq-question" aria-expanded="false">
              <span>How much do your services cost?</span>
              <span>+</span>
            </button>
            <div class="faq-answer" hidden>
              Pricing depends on the type of event, your requirements,
              guest numbers, location and budget. Contact us for a
              personalised discussion and quotation.
            </div>
          </div>

          <div class="faq-item">
            <button class="faq-question" aria-expanded="false">
              <span>How early should I book?</span>
              <span>+</span>
            </button>
            <div class="faq-answer" hidden>
              Booking early is recommended, especially for busy dates.
              Send us your preferred date so we can discuss availability.
            </div>
          </div>

          <div class="faq-item">
            <button class="faq-question" aria-expanded="false">
              <span>How do I make an enquiry?</span>
              <span>+</span>
            </button>
            <div class="faq-answer" hidden>
              Complete the enquiry form below and continue to WhatsApp.
              Your event details will be prepared in a message for you
              to review and send to us.
            </div>
          </div>

          <div class="faq-item">
            <button class="faq-question" aria-expanded="false">
              <span>Can I request a customised event?</span>
              <span>+</span>
            </button>
            <div class="faq-answer" hidden>
              Yes, you can describe your ideas and preferences in your
              enquiry. We'll discuss what can be arranged for your occasion.
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section class="section contact" id="contact">
      <div class="container">
        <div class="contact-grid">
          <div class="contact-copy">
            <div class="eyebrow">Let's create something special</div>
            <h2 class="section-title">Tell Us About Your Event</h2>
            <p>
              Have an upcoming celebration or a special idea? Get in touch
              with Dor Dor Events and Services. We'd love to hear what
              you're planning.
            </p>

            <div class="contact-detail">
              <div class="contact-icon">☎</div>
              <div>
                <strong>Call Us</strong>
                <a href="tel:+2348088404569">0808 840 4569</a>
              </div>
            </div>

            <div class="contact-detail">
              <div class="contact-icon">✉</div>
              <div>
                <strong>Email Us</strong>
                <a href="mailto:preciousbakor7@gmail.com">
                  preciousbakor7@gmail.com
                </a>
              </div>
            </div>

            <div class="contact-detail">
              <div class="contact-icon">◉</div>
              <div>
                <strong>WhatsApp</strong>
                <a href="https://wa.me/2348088404569"
                  target="_blank" rel="noopener noreferrer">
                  Chat with us directly
                </a>
              </div>
            </div>

            <p style="font-size:.83rem">
              Tell us your event date and requirements so we can
              understand how best to assist you.
            </p>
          </div>

          <form class="contact-form" id="eventForm">
            <h3>Event Enquiry Form</h3>
            <p class="form-note">
              Fill in your details to prepare your WhatsApp enquiry.
            </p>

            <div class="form-row">
              <div class="form-group">
                <label for="customerName">Your Full Name *</label>
                <input id="customerName" name="customerName"
                  type="text" autocomplete="name" required
                  maxlength="100" placeholder="Enter your name">
              </div>

              <div class="form-group">
                <label for="customerPhone">Your Phone Number *</label>
                <input id="customerPhone" name="customerPhone"
                  type="tel" autocomplete="tel" required
                  maxlength="25" placeholder="e.g. 08012345678">
              </div>
            </div>

            <div class="form-group">
              <label for="eventType">Type of Event *</label>
              <select id="eventType" name="eventType" required>
                <option value="">Select an event</option>
                <option>Wedding</option>
                <option>Engagement</option>
                <option>Birthday</option>
                <option>Anniversary</option>
                <option>Corporate Event</option>
                <option>Private Party</option>
                <option>Event Decoration</option>
                <option>Other</option>
              </select>
            </div>

            <div class="form-row">
              <div class="form-group">
                <label for="eventDate">Preferred Event Date</label>
                <input id="eventDate" name="eventDate" type="date">
              </div>

              <div class="form-group">
                <label for="guestCount">Expected Guests</label>
                <select id="guestCount" name="guestCount">
                  <option value="">Select number</option>
                  <option>Under 50</option>
                  <option>50–100</option>
                  <option>101–200</option>
                  <option>201–500</option>
                  <option>More than 500</option>
                  <option>Not sure yet</option>
                </select>
              </div>
            </div>

            <div class="form-group">
              <label for="eventBudget">Estimated Budget (₦)</label>
              <input id="eventBudget" name="eventBudget"
                type="text" maxlength="60"
                placeholder="e.g. ₦200,000 or flexible">
            </div>

            <div class="form-group">
              <label for="eventLocation">Event Location</label>
              <input id="eventLocation" name="eventLocation"
                type="text" maxlength="150"
                placeholder="Town or venue">
            </div>

            <div class="form-group">
              <label for="eventDetails">Tell Us More About Your Plans</label>
              <textarea id="eventDetails" name="eventDetails"
                maxlength="1500"
                placeholder="Describe your theme, preferred colours or services..."></textarea>
            </div>

            <button type="submit" class="btn btn-gold">
              Send Enquiry on WhatsApp ↗
            </button>

            <p class="privacy-note">
              Your enquiry opens WhatsApp. Review the message and
              press Send there to submit it.
            </p>
          </form>
        </div>
      </div>
    </section>

    <!-- Final CTA -->
    <section class="final-cta">
      <div class="container">
        <div class="eyebrow">Your next celebration starts here</div>
        <h2>Let's Make It Unforgettable.</h2>
        <p>Every great event starts with a conversation.</p>
        <a href="https://wa.me/2348088404569?text=Hello%20Dor%20Dor%20Events%20and%20Services%2C%20I%20would%20like%20to%20make%20an%20enquiry."
          class="btn btn-gold" target="_blank"
          rel="noopener noreferrer">Chat With Us on WhatsApp ↗</a>
      </div>
    </section>
  </main>

  <!-- Footer -->
  <footer>
    <div class="container">
      <div class="footer-grid">
        <div class="footer-about">
          <a class="brand" href="#home">
            <span class="brand-mark">DD</span>
            <span class="brand-name">
              Dor Dor
              <small>Events &amp; Services</small>
            </span>
          </a>
          <p>
            Making your special moments more beautiful, personal
            and memorable. Let's bring your next event to life.
          </p>
        </div>

        <div>
          <h4>Quick Links</h4>
          <ul class="footer-links">
            <li><a href="#about">About Us</a></li>
            <li><a href="#services">Our Services</a></li>
            <li><a href="#gallery">Gallery</a></li>
            <li><a href="#faq">FAQs</a></li>
            <li><a href="#contact">Contact Us</a></li>
          </ul>
        </div>

        <div>
          <h4>Get In Touch</h4>
          <ul class="footer-links">
            <li><a href="tel:+2348088404569">0808 840 4569</a></li>
            <li><a href="mailto:preciousbakor7@gmail.com">preciousbakor7@gmail.com</a></li>
            <li><a href="https://wa.me/2348088404569"
              target="_blank" rel="noopener noreferrer">WhatsApp Us ↗</a></li>
          </ul>
        </div>
      </div>

      <div class="copyright">
        <span>© <span id="currentYear"></span> Dor Dor Events and Services.</span>
        <span>Made with care for life's special moments.</span>
      </div>
    </div>
  </footer>

  <!-- Floating WhatsApp button -->
  <a class="whatsapp-float"
    href="https://wa.me/2348088404569?text=Hello%20Dor%20Dor%20Events%20and%20Services%2C%20I%20would%20like%20to%20make%20an%20enquiry."
    target="_blank" rel="noopener noreferrer"
    aria-label="Chat with Dor Dor Events and Services on WhatsApp"
    title="Chat with us on WhatsApp">
    <svg width="29" height="29" viewBox="0 0 24 24"
      fill="none" stroke="currentColor" stroke-width="1.8"
      stroke-linecap="round" stroke-linejoin="round"
      aria-hidden="true">
      <path d="M21 11.5a8.4 8.4 0 0 1-.9 3.8 8.5 8.5 0 0 1-7.6 4.7 8.4 8.4 0 0 1-3.8-.9L3 21l1.9-5.7a8.4 8.4 0 0 1-.9-3.8 8.5 8.5 0 0 1 4.7-7.6 8.4 8.4 0 0 1 3.8-.9h.5a8.5 8.5 0 0 1 8 8z"/>
      <path d="M8.5 9.5c.4 2.1 2 3.7 4.1 4.1"/>
    </svg>
  </a>

  <!-- Image lightbox -->
  <div class="lightbox" id="lightbox" hidden
    role="dialog" aria-modal="true" aria-label="Gallery image">
    <button class="lightbox-close" id="lightboxClose"
      type="button" aria-label="Close image viewer">×</button>
    <img id="lightboxImage" src="" alt="">
  </div>

  <script>
    "use strict";

    // Business WhatsApp number in international format.
    // Nigerian number: 0808 840 4569 -> 2348088404569
    const BUSINESS_WHATSAPP = "2348088404569";

    // Mobile navigation
    const menuToggle = document.getElementById("menuToggle");
    const navLinks = document.getElementById("navLinks");

    menuToggle.addEventListener("click", () => {
      const isOpen = navLinks.classList.toggle("open");
      menuToggle.setAttribute("aria-expanded", String(isOpen));
      menuToggle.setAttribute(
        "aria-label",
        isOpen ? "Close navigation menu" : "Open navigation menu"
      );
      menuToggle.textContent = isOpen ? "×" : "☰";
    });

    navLinks.querySelectorAll("a").forEach(link => {
      link.addEventListener("click", () => {
        navLinks.classList.remove("open");
        menuToggle.setAttribute("aria-expanded", "false");
        menuToggle.setAttribute("aria-label", "Open navigation menu");
        menuToggle.textContent = "☰";
      });
    });

    // Current year in the footer
    document.getElementById("currentYear").textContent =
      new Date().getFullYear();

    // Prevent selecting a date in the past.
    // This is a convenience only; confirm availability with the business.
    const eventDateInput = document.getElementById("eventDate");
    const localToday = new Date();
    const localDateString = [
      localToday.getFullYear(),
      String(localToday.getMonth() + 1).padStart(2, "0"),
      String(localToday.getDate()).padStart(2, "0")
    ].join("-");

    eventDateInput.min = localDateString;

    // Event enquiry form: create a WhatsApp message.
    // The website does not need a paid server or database for this feature.
    document.getElementById("eventForm").addEventListener("submit", event => {
      event.preventDefault();

      const getValue = id =>
        document.getElementById(id).value.trim();

      const customerName = getValue("customerName");
      const customerPhone = getValue("customerPhone");
      const eventType = getValue("eventType");

      if (!customerName || !customerPhone || !eventType) {
        alert("Please complete your name, phone number and event type.");
        return;
      }

      const dateValue = getValue("eventDate");
      let readableDate = "Not specified";

      if (dateValue) {
        const parts = dateValue.split("-");
        readableDate = `${parts[2]}/${parts[1]}/${parts[0]}`;
      }

      const details = [
        "Hello Dor Dor Events and Services! 👋",
        "",
        "I'd like to make an event enquiry.",
        "",
        `Name: ${customerName}`,
        `Phone: ${customerPhone}`,
        `Event type: ${eventType}`,
        `Preferred date: ${readableDate}`,
        `Expected guests: ${getValue("guestCount") || "Not specified"}`,
        `Estimated budget: ${getValue("eventBudget") || "Not specified"}`,
        `Location: ${getValue("eventLocation") || "Not specified"}`,
        `Additional details: ${getValue("eventDetails") || "None provided"}`,
        "",
        "Please let me know your available services and pricing. Thank you!"
      ];

      const message = encodeURIComponent(details.join("\n"));
      const whatsappUrl =
        `https://wa.me/${BUSINESS_WHATSAPP}?text=${message}`;

      // Open WhatsApp in a new tab/window.
      // The customer must press Send in WhatsApp to submit the enquiry.
      const whatsappWindow = window.open(whatsappUrl, "_blank");

      if (whatsappWindow) {
        whatsappWindow.opener = null;
      } else {
        // Fallback if the browser blocks the new window.
        window.location.href = whatsappUrl;
      }
    });

    // Service enquiry links preselect the event type when possible.
    document.querySelectorAll("[data-service]").forEach(link => {
      link.addEventListener("click", () => {
        const service = link.dataset.service;
        const select = document.getElementById("eventType");

        const options = Array.from(select.options);
        const match = options.find(option =>
          option.text.toLowerCase() === service.toLowerCase()
        );

        if (match) {
          select.value = match.value;
        } else if (service === "Event Planning" ||
                   service === "Event Decoration") {
          select.value = "Event Decoration";
        } else {
          select.value = "Other";
        }
      });
    });

    // Accessible FAQ accordion.
    document.querySelectorAll(".faq-question").forEach(button => {
      button.addEventListener("click", () => {
        const answer = button.nextElementSibling;
        const isExpanded =
          button.getAttribute("aria-expanded") === "true";

        button.setAttribute("aria-expanded", String(!isExpanded));
        answer.hidden = isExpanded;
        button.lastElementChild.textContent = isExpanded ? "+" : "−";
      });
    });

    // Gallery lightbox
    const lightbox = document.getElementById("lightbox");
    const lightboxImage = document.getElementById("lightboxImage");
    const lightboxClose = document.getElementById("lightboxClose");
    let previousFocus = null;

    function closeLightbox() {
      lightbox.hidden = true;
      lightboxImage.src = "";
      if (previousFocus) previousFocus.focus();
    }

    document.querySelectorAll(".gallery-item").forEach(item => {
      item.addEventListener("click", () => {
        previousFocus = item;
        const image = item.querySelector("img");

        lightboxImage.src = item.dataset.full;
        lightboxImage.alt = image.alt;
        lightbox.hidden = false;
        lightboxClose.focus();
      });
    });

    lightboxClose.addEventListener("click", closeLightbox);

    lightbox.addEventListener("click", event => {
      if (event.target === lightbox) closeLightbox();
    });

    document.addEventListener("keydown", event => {
      if (event.key === "Escape" && !lightbox.hidden) {
        closeLightbox();
      }
    });

    // Reveal elements as they enter the viewport.
    // A fallback keeps content visible if IntersectionObserver is unavailable.
    const revealElements = document.querySelectorAll(".reveal");

    if ("IntersectionObserver" in window) {
      const observer = new IntersectionObserver(entries => {
        entries.forEach(entry => {
          if (entry.isIntersecting) {
            entry.target.classList.add("visible");
            observer.unobserve(entry.target);
          }
        });
      }, { threshold: 0.12 });

      revealElements.forEach(element => observer.observe(element));
    } else {
      revealElements.forEach(element => element.classList.add("visible"));
    }
  </script>

</body>
</html>
