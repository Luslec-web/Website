<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>LenteraOne Insurance — Asuransi Kredit Terpercaya</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --navy: #0B1F3A;
    --navy-mid: #162D50;
    --navy-light: #1E3D6B;
    --gold: #C9A84C;
    --gold-light: #E8C97A;
    --gold-pale: #F5EDD6;
    --cream: #FAF7F2;
    --white: #FFFFFF;
    --text-dark: #0B1F3A;
    --text-mid: #3D5370;
    --text-muted: #7A90AA;
    --border: rgba(11,31,58,0.10);
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    font-family: 'DM Sans', sans-serif;
    background: var(--cream);
    color: var(--text-dark);
    overflow-x: hidden;
  }

  /* NAVIGATION */
  nav {
    position: fixed; top: 0; left: 0; right: 0; z-index: 100;
    background: rgba(11,31,58,0.96);
    backdrop-filter: blur(12px);
    display: flex; align-items: center; justify-content: space-between;
    padding: 0 5%;
    height: 72px;
    border-bottom: 1px solid rgba(201,168,76,0.2);
  }

  .nav-logo {
    display: flex; align-items: center; gap: 12px;
    text-decoration: none;
  }

  .nav-logo-mark {
    width: 38px; height: 38px;
    background: linear-gradient(135deg, var(--gold) 0%, var(--gold-light) 100%);
    border-radius: 8px;
    display: flex; align-items: center; justify-content: center;
    font-family: 'Cormorant Garamond', serif;
    font-size: 20px; font-weight: 600; color: var(--navy);
  }

  .nav-logo-text {
    display: flex; flex-direction: column;
    line-height: 1.1;
  }

  .nav-logo-text .brand { font-family: 'Cormorant Garamond', serif; font-size: 18px; font-weight: 600; color: var(--white); letter-spacing: 0.02em; }
  .nav-logo-text .tagline { font-size: 10px; color: var(--gold); letter-spacing: 0.12em; text-transform: uppercase; font-weight: 300; }

  .nav-links { display: flex; align-items: center; gap: 36px; }
  .nav-links a { color: rgba(255,255,255,0.75); text-decoration: none; font-size: 14px; font-weight: 400; transition: color 0.2s; letter-spacing: 0.02em; }
  .nav-links a:hover { color: var(--gold-light); }

  .nav-cta {
    background: transparent;
    border: 1px solid var(--gold);
    color: var(--gold) !important;
    padding: 8px 22px;
    border-radius: 4px;
    transition: all 0.2s !important;
  }
  .nav-cta:hover { background: var(--gold) !important; color: var(--navy) !important; }

  /* HERO */
  .hero {
    min-height: 100vh;
    background: var(--navy);
    display: grid;
    grid-template-columns: 1fr 1fr;
    align-items: center;
    padding: 72px 5% 0;
    position: relative;
    overflow: hidden;
  }

  .hero::before {
    content: '';
    position: absolute; top: 0; right: 0;
    width: 55%; height: 100%;
    background: url("data:image/svg+xml,%3Csvg width='600' height='800' viewBox='0 0 600 800' xmlns='http://www.w3.org/2000/svg'%3E%3Cdefs%3E%3CradialGradient id='rg' cx='60%25' cy='40%25' r='60%25'%3E%3Cstop offset='0%25' stop-color='%231E3D6B' stop-opacity='1'/%3E%3Cstop offset='100%25' stop-color='%230B1F3A' stop-opacity='1'/%3E%3C/radialGradient%3E%3C/defs%3E%3Crect width='600' height='800' fill='url(%23rg)'/%3E%3Cg opacity='0.06'%3E%3Ccircle cx='300' cy='200' r='180' fill='none' stroke='%23C9A84C' stroke-width='1'/%3E%3Ccircle cx='300' cy='200' r='280' fill='none' stroke='%23C9A84C' stroke-width='0.5'/%3E%3Ccircle cx='300' cy='200' r='380' fill='none' stroke='%23C9A84C' stroke-width='0.5'/%3E%3C/g%3E%3C/svg%3E") center/cover;
    opacity: 1;
  }

  .hero-grid-bg {
    position: absolute; inset: 0;
    background-image:
      linear-gradient(rgba(201,168,76,0.03) 1px, transparent 1px),
      linear-gradient(90deg, rgba(201,168,76,0.03) 1px, transparent 1px);
    background-size: 60px 60px;
  }

  .hero-left {
    position: relative; z-index: 2;
    padding-right: 5%;
    animation: fadeUp 0.9s ease both;
  }

  .hero-eyebrow {
    display: inline-flex; align-items: center; gap: 10px;
    background: rgba(201,168,76,0.12);
    border: 1px solid rgba(201,168,76,0.3);
    border-radius: 100px;
    padding: 6px 16px;
    margin-bottom: 32px;
    font-size: 12px; letter-spacing: 0.14em; text-transform: uppercase;
    color: var(--gold-light); font-weight: 400;
  }

  .hero-eyebrow::before { content: ''; width: 6px; height: 6px; border-radius: 50%; background: var(--gold); display: block; }

  h1 {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(42px, 5.5vw, 72px);
    font-weight: 300;
    color: var(--white);
    line-height: 1.08;
    margin-bottom: 24px;
    letter-spacing: -0.01em;
  }

  h1 em {
    font-style: italic;
    color: var(--gold-light);
  }

  .hero-desc {
    font-size: 16px; color: rgba(255,255,255,0.6);
    line-height: 1.8; max-width: 440px;
    margin-bottom: 44px; font-weight: 300;
  }

  .hero-actions { display: flex; gap: 16px; align-items: center; }

  .btn-primary {
    background: var(--gold);
    color: var(--navy);
    padding: 14px 32px;
    border-radius: 4px;
    font-size: 14px; font-weight: 500; letter-spacing: 0.04em;
    text-decoration: none;
    transition: all 0.25s;
    display: inline-block;
  }
  .btn-primary:hover { background: var(--gold-light); transform: translateY(-1px); }

  .btn-ghost {
    color: rgba(255,255,255,0.7);
    font-size: 14px; text-decoration: none;
    display: flex; align-items: center; gap: 8px;
    transition: color 0.2s;
  }
  .btn-ghost:hover { color: var(--gold-light); }
  .btn-ghost .arrow { font-size: 18px; transition: transform 0.2s; }
  .btn-ghost:hover .arrow { transform: translateX(4px); }

  .hero-stats {
    display: flex; gap: 48px;
    margin-top: 64px;
    padding-top: 40px;
    border-top: 1px solid rgba(255,255,255,0.08);
  }

  .stat-item .num {
    font-family: 'Cormorant Garamond', serif;
    font-size: 38px; font-weight: 300;
    color: var(--gold-light);
    line-height: 1;
  }

  .stat-item .label {
    font-size: 12px; color: rgba(255,255,255,0.45);
    letter-spacing: 0.06em; text-transform: uppercase;
    margin-top: 6px; font-weight: 300;
  }

  .hero-right {
    position: relative; z-index: 2;
    display: flex; justify-content: center; align-items: center;
    padding: 80px 0;
    animation: fadeUp 0.9s 0.2s ease both;
  }

  .hero-card-stack { position: relative; width: 340px; height: 400px; }

  .policy-card {
    position: absolute;
    width: 300px;
    background: rgba(255,255,255,0.05);
    border: 1px solid rgba(201,168,76,0.2);
    border-radius: 16px;
    padding: 28px;
    backdrop-filter: blur(20px);
  }

  .policy-card.main {
    top: 40px; left: 20px;
    background: rgba(30,61,107,0.9);
    border-color: rgba(201,168,76,0.4);
    z-index: 3;
    box-shadow: 0 32px 64px rgba(0,0,0,0.4);
  }

  .policy-card.back1 {
    top: 20px; left: 30px;
    z-index: 2;
    transform: rotate(3deg);
    opacity: 0.5;
  }

  .policy-card.back2 {
    top: 0; left: 40px;
    z-index: 1;
    transform: rotate(6deg);
    opacity: 0.25;
  }

  .card-chip {
    width: 44px; height: 32px;
    background: linear-gradient(135deg, var(--gold) 0%, var(--gold-light) 100%);
    border-radius: 6px; margin-bottom: 28px;
    position: relative; overflow: hidden;
  }
  .card-chip::before {
    content: ''; position: absolute;
    top: 50%; left: 0; right: 0; height: 1px;
    background: rgba(11,31,58,0.3);
    transform: translateY(-50%);
  }

  .card-label { font-size: 10px; color: rgba(255,255,255,0.4); letter-spacing: 0.14em; text-transform: uppercase; margin-bottom: 4px; }
  .card-value { font-family: 'Cormorant Garamond', serif; font-size: 20px; color: var(--white); font-weight: 400; margin-bottom: 20px; }

  .card-footer { display: flex; justify-content: space-between; align-items: flex-end; margin-top: 12px; }
  .card-brand { font-family: 'Cormorant Garamond', serif; font-size: 16px; color: var(--gold-light); font-style: italic; }

  .card-status { display: flex; align-items: center; gap: 6px; font-size: 11px; color: #4ADE80; }
  .card-status::before { content: ''; width: 6px; height: 6px; border-radius: 50%; background: #4ADE80; display: block; }

  /* SECTION BASE */
  section { padding: 100px 5%; }

  .section-label {
    display: flex; align-items: center; gap: 12px;
    font-size: 11px; letter-spacing: 0.18em; text-transform: uppercase;
    color: var(--gold); font-weight: 500;
    margin-bottom: 16px;
  }
  .section-label::before { content: ''; width: 28px; height: 1px; background: var(--gold); display: block; }

  h2 {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(32px, 3.5vw, 52px);
    font-weight: 300;
    color: var(--text-dark);
    line-height: 1.15;
    letter-spacing: -0.01em;
  }

  h2 em { font-style: italic; color: var(--navy-light); }

  /* ABOUT */
  .about {
    background: var(--white);
    display: grid; grid-template-columns: 1fr 1fr;
    gap: 80px; align-items: center;
  }

  .about-visual {
    position: relative;
    height: 480px;
  }

  .about-img-frame {
    position: absolute; top: 0; left: 0;
    width: 78%; height: 88%;
    background: linear-gradient(135deg, var(--navy) 0%, var(--navy-light) 100%);
    border-radius: 4px;
    overflow: hidden;
    display: flex; align-items: center; justify-content: center;
  }

  .building-svg { opacity: 0.5; }

  .about-accent-box {
    position: absolute; bottom: 0; right: 0;
    width: 52%; background: var(--gold-pale);
    border: 1px solid rgba(201,168,76,0.3);
    padding: 28px; border-radius: 4px;
  }

  .about-accent-box .big-num {
    font-family: 'Cormorant Garamond', serif;
    font-size: 52px; font-weight: 300; color: var(--navy);
    line-height: 1;
  }

  .about-accent-box .big-label {
    font-size: 13px; color: var(--text-mid);
    margin-top: 8px; line-height: 1.5; font-weight: 300;
  }

  .about-text .lead {
    font-size: 17px; color: var(--text-mid); line-height: 1.8;
    margin: 24px 0 32px; font-weight: 300;
  }

  .about-pillars { display: flex; flex-direction: column; gap: 20px; }

  .pillar {
    display: flex; gap: 16px; align-items: flex-start;
    padding: 20px; border-radius: 4px;
    border: 1px solid var(--border);
    transition: all 0.25s;
  }
  .pillar:hover { border-color: rgba(201,168,76,0.4); background: var(--gold-pale); }

  .pillar-icon {
    width: 40px; height: 40px; flex-shrink: 0;
    background: var(--navy);
    border-radius: 8px;
    display: flex; align-items: center; justify-content: center;
    font-size: 18px; color: var(--gold);
  }

  .pillar-text h4 { font-size: 15px; font-weight: 500; color: var(--navy); margin-bottom: 4px; }
  .pillar-text p { font-size: 13px; color: var(--text-muted); line-height: 1.6; font-weight: 300; }

  /* PRODUCTS */
  .products { background: var(--cream); }
  .products-header { text-align: center; max-width: 560px; margin: 0 auto 64px; }
  .products-header .section-label { justify-content: center; }
  .products-header .section-label::before { display: none; }
  .products-header .section-label::after { content: ''; width: 28px; height: 1px; background: var(--gold); display: block; }

  .products-grid {
    display: grid; grid-template-columns: repeat(3, 1fr);
    gap: 24px;
  }

  .product-card {
    background: var(--white);
    border: 1px solid var(--border);
    border-radius: 4px;
    padding: 36px 28px;
    transition: all 0.3s;
    position: relative; overflow: hidden;
  }

  .product-card::before {
    content: '';
    position: absolute; top: 0; left: 0; right: 0;
    height: 3px;
    background: linear-gradient(90deg, var(--gold) 0%, var(--gold-light) 100%);
    transform: scaleX(0); transform-origin: left;
    transition: transform 0.3s;
  }
  .product-card:hover { transform: translateY(-4px); box-shadow: 0 20px 48px rgba(11,31,58,0.1); }
  .product-card:hover::before { transform: scaleX(1); }

  .product-card.featured {
    background: var(--navy);
    border-color: transparent;
    color: var(--white);
  }
  .product-card.featured::before { transform: scaleX(1); }

  .product-icon {
    width: 52px; height: 52px;
    border-radius: 12px;
    display: flex; align-items: center; justify-content: center;
    font-size: 24px;
    margin-bottom: 24px;
    background: var(--gold-pale);
  }
  .product-card.featured .product-icon { background: rgba(201,168,76,0.15); }

  .product-card h3 {
    font-family: 'Cormorant Garamond', serif;
    font-size: 22px; font-weight: 400;
    color: var(--navy); margin-bottom: 12px;
  }
  .product-card.featured h3 { color: var(--white); }

  .product-card p { font-size: 14px; color: var(--text-muted); line-height: 1.7; font-weight: 300; }
  .product-card.featured p { color: rgba(255,255,255,0.6); }

  .product-features { margin-top: 24px; display: flex; flex-direction: column; gap: 10px; }
  .feature-item {
    display: flex; align-items: center; gap: 10px;
    font-size: 13px; color: var(--text-mid);
  }
  .feature-item::before { content: '✓'; color: var(--gold); font-weight: 500; font-size: 14px; }
  .product-card.featured .feature-item { color: rgba(255,255,255,0.7); }

  .product-cta {
    display: inline-flex; align-items: center; gap: 8px;
    margin-top: 28px; font-size: 13px; font-weight: 500;
    color: var(--gold); text-decoration: none;
    letter-spacing: 0.04em;
    transition: gap 0.2s;
  }
  .product-cta:hover { gap: 12px; }

  /* NUMBERS */
  .numbers {
    background: var(--navy);
    padding: 80px 5%;
    display: grid; grid-template-columns: repeat(4,1fr);
    gap: 2px;
  }

  .number-box {
    padding: 48px 40px;
    border-right: 1px solid rgba(255,255,255,0.06);
    text-align: center;
    position: relative;
  }
  .number-box:last-child { border-right: none; }

  .number-box .big {
    font-family: 'Cormorant Garamond', serif;
    font-size: 60px; font-weight: 300;
    color: var(--gold-light); line-height: 1;
    display: block;
  }

  .number-box .unit {
    font-family: 'Cormorant Garamond', serif;
    font-size: 32px; color: var(--gold); vertical-align: super; font-weight: 300;
  }

  .number-box .desc {
    font-size: 13px; color: rgba(255,255,255,0.45);
    letter-spacing: 0.08em; text-transform: uppercase;
    margin-top: 12px; font-weight: 300;
  }

  /* HOW IT WORKS */
  .how { background: var(--white); }
  .how-header { margin-bottom: 64px; }

  .steps-row {
    display: grid; grid-template-columns: repeat(4,1fr);
    gap: 0; position: relative;
  }

  .steps-row::before {
    content: '';
    position: absolute; top: 32px; left: 10%; right: 10%;
    height: 1px;
    background: linear-gradient(90deg, transparent, var(--gold), var(--gold), transparent);
    opacity: 0.3;
  }

  .step { padding: 0 24px; text-align: center; }

  .step-num {
    width: 64px; height: 64px;
    border-radius: 50%;
    border: 1px solid var(--gold);
    display: flex; align-items: center; justify-content: center;
    font-family: 'Cormorant Garamond', serif;
    font-size: 22px; color: var(--gold); font-weight: 300;
    margin: 0 auto 24px;
    background: var(--white);
    position: relative; z-index: 1;
  }

  .step h4 { font-size: 16px; font-weight: 500; color: var(--navy); margin-bottom: 10px; }
  .step p { font-size: 13px; color: var(--text-muted); line-height: 1.7; font-weight: 300; }

  /* TESTIMONIALS */
  .testimonials { background: var(--cream); }
  .testi-header { margin-bottom: 56px; }

  .testi-grid {
    display: grid; grid-template-columns: repeat(3,1fr);
    gap: 24px;
  }

  .testi-card {
    background: var(--white);
    border: 1px solid var(--border);
    border-radius: 4px;
    padding: 32px;
    position: relative;
  }

  .testi-card::before {
    content: '"';
    font-family: 'Cormorant Garamond', serif;
    font-size: 80px; color: var(--gold-pale);
    position: absolute; top: 12px; left: 24px;
    line-height: 1;
  }

  .testi-text {
    font-size: 15px; color: var(--text-mid);
    line-height: 1.8; font-weight: 300;
    font-style: italic;
    margin-bottom: 24px;
    padding-top: 24px;
  }

  .testi-author { display: flex; gap: 14px; align-items: center; }
  .testi-avatar {
    width: 44px; height: 44px; border-radius: 50%;
    background: var(--navy);
    display: flex; align-items: center; justify-content: center;
    font-family: 'Cormorant Garamond', serif;
    font-size: 18px; color: var(--gold); font-weight: 400;
  }
  .testi-info .name { font-size: 14px; font-weight: 500; color: var(--navy); }
  .testi-info .role { font-size: 12px; color: var(--text-muted); margin-top: 2px; }
  .testi-stars { color: var(--gold); font-size: 13px; margin-top: 4px; }

  /* PARTNERS */
  .partners {
    background: var(--white);
    padding: 60px 5%;
    text-align: center;
  }

  .partners p { font-size: 12px; letter-spacing: 0.16em; text-transform: uppercase; color: var(--text-muted); margin-bottom: 40px; }

  .partners-row {
    display: flex; align-items: center; justify-content: center;
    gap: 48px; flex-wrap: wrap;
  }

  .partner-logo {
    font-family: 'Cormorant Garamond', serif;
    font-size: 22px; font-weight: 600;
    color: var(--text-muted);
    letter-spacing: 0.05em;
    opacity: 0.5; transition: opacity 0.2s;
  }
  .partner-logo:hover { opacity: 0.9; }

  /* CTA BANNER */
  .cta-banner {
    background: linear-gradient(135deg, var(--navy) 0%, var(--navy-light) 100%);
    padding: 100px 5%;
    text-align: center;
    position: relative; overflow: hidden;
  }

  .cta-banner::before {
    content: '';
    position: absolute; top: -50%; left: -10%;
    width: 400px; height: 400px;
    border-radius: 50%;
    border: 1px solid rgba(201,168,76,0.1);
  }

  .cta-banner::after {
    content: '';
    position: absolute; bottom: -30%; right: 5%;
    width: 300px; height: 300px;
    border-radius: 50%;
    border: 1px solid rgba(201,168,76,0.08);
  }

  .cta-banner h2 { color: var(--white); max-width: 600px; margin: 0 auto 16px; }
  .cta-banner p { color: rgba(255,255,255,0.55); font-size: 16px; margin-bottom: 40px; font-weight: 300; }

  .cta-actions { display: flex; gap: 16px; justify-content: center; }

  .btn-outline {
    border: 1px solid rgba(255,255,255,0.3);
    color: rgba(255,255,255,0.8);
    padding: 14px 32px; border-radius: 4px;
    font-size: 14px; text-decoration: none;
    transition: all 0.2s;
  }
  .btn-outline:hover { border-color: var(--white); color: var(--white); }

  /* FOOTER */
  footer {
    background: #07131F;
    padding: 72px 5% 40px;
    color: rgba(255,255,255,0.45);
  }

  .footer-grid {
    display: grid; grid-template-columns: 2fr 1fr 1fr 1fr;
    gap: 48px; margin-bottom: 56px;
  }

  .footer-brand .logo-text {
    font-family: 'Cormorant Garamond', serif;
    font-size: 22px; color: var(--white); font-weight: 400;
    margin-bottom: 16px; display: block;
  }

  .footer-brand p { font-size: 13px; line-height: 1.8; max-width: 280px; font-weight: 300; }

  .footer-col h5 {
    font-size: 11px; letter-spacing: 0.14em; text-transform: uppercase;
    color: var(--gold); font-weight: 500;
    margin-bottom: 20px;
  }

  .footer-col a {
    display: block;
    color: rgba(255,255,255,0.4); text-decoration: none;
    font-size: 13px; margin-bottom: 12px;
    transition: color 0.2s; font-weight: 300;
  }
  .footer-col a:hover { color: rgba(255,255,255,0.8); }

  .footer-contact-item {
    display: flex; gap: 10px;
    font-size: 13px; margin-bottom: 14px; line-height: 1.5;
    align-items: flex-start;
  }

  .contact-icon { color: var(--gold); flex-shrink: 0; font-size: 15px; margin-top: 1px; }

  .footer-bottom {
    padding-top: 32px;
    border-top: 1px solid rgba(255,255,255,0.06);
    display: flex; justify-content: space-between; align-items: center;
    font-size: 12px;
  }

  .footer-legal { display: flex; gap: 28px; }
  .footer-legal a { color: rgba(255,255,255,0.3); text-decoration: none; transition: color 0.2s; }
  .footer-legal a:hover { color: rgba(255,255,255,0.6); }

  .ojk-badge {
    display: inline-flex; align-items: center; gap: 8px;
    background: rgba(201,168,76,0.1); border: 1px solid rgba(201,168,76,0.25);
    border-radius: 4px; padding: 8px 14px;
    font-size: 11px; color: var(--gold); letter-spacing: 0.06em;
    margin-top: 20px;
  }

  /* ANIMATIONS */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(24px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .fade-up { opacity: 0; animation: fadeUp 0.7s ease forwards; }

  /* MOBILE RESPONSIVE */
  @media (max-width: 900px) {
    .hero { grid-template-columns: 1fr; }
    .hero-right { display: none; }
    .about { grid-template-columns: 1fr; }
    .about-visual { height: 260px; }
    .products-grid { grid-template-columns: 1fr; }
    .numbers { grid-template-columns: repeat(2,1fr); }
    .steps-row { grid-template-columns: repeat(2,1fr); gap: 32px; }
    .steps-row::before { display: none; }
    .testi-grid { grid-template-columns: 1fr; }
    .footer-grid { grid-template-columns: 1fr 1fr; }
    .nav-links { display: none; }
  }

  /* Scroll animations */
  .reveal {
    opacity: 0;
    transform: translateY(20px);
    transition: opacity 0.6s ease, transform 0.6s ease;
  }
  .reveal.visible {
    opacity: 1;
    transform: translateY(0);
  }
</style>
</head>
<body>

<!-- NAVIGATION -->
<nav>
  <a href="#" class="nav-logo">
    <div class="nav-logo-mark">L</div>
    <div class="nav-logo-text">
      <span class="brand">LenteraOne</span>
      <span class="tagline">Insurance</span>
    </div>
  </a>
  <div class="nav-links">
    <a href="#tentang">Tentang Kami</a>
    <a href="#produk">Produk</a>
    <a href="#cara-kerja">Cara Kerja</a>
    <a href="#testimoni">Testimoni</a>
    <a href="#kontak" class="nav-cta">Hubungi Kami</a>
  </div>
</nav>

<!-- HERO -->
<section class="hero" id="beranda">
  <div class="hero-grid-bg"></div>
  <div class="hero-left">
    <div class="hero-eyebrow">Terdaftar &amp; Diawasi OJK</div>
    <h1>Lindungi <em>Kredit</em> Anda dengan Keyakinan Penuh</h1>
    <p class="hero-desc">LenteraOne Insurance hadir sebagai mitra strategis yang menjamin portofolio kredit Anda tetap aman dari risiko gagal bayar dan ketidakpastian finansial.</p>
    <div class="hero-actions">
      <a href="#produk" class="btn-primary">Lihat Produk Kami</a>
      <a href="#cara-kerja" class="btn-ghost">Cara Kerja <span class="arrow">→</span></a>
    </div>
    <div class="hero-stats">
      <div class="stat-item">
        <div class="num">Rp 12T<span style="font-size:20px;color:var(--gold)">+</span></div>
        <div class="label">Total Perlindungan</div>
      </div>
      <div class="stat-item">
        <div class="num">850<span style="font-size:20px;color:var(--gold)">+</span></div>
        <div class="label">Mitra Bank &amp; Lembaga</div>
      </div>
      <div class="stat-item">
        <div class="num">98<span style="font-size:20px;color:var(--gold)">%</span></div>
        <div class="label">Tingkat Penyelesaian Klaim</div>
      </div>
    </div>
  </div>
  <div class="hero-right">
    <div class="hero-card-stack">
      <div class="policy-card back2"></div>
      <div class="policy-card back1"></div>
      <div class="policy-card main">
        <div class="card-chip"></div>
        <div class="card-label">Nomor Polis</div>
        <div class="card-value">L1 — 2024 — 008 — 4721</div>
        <div class="card-label">Tertanggung</div>
        <div class="card-value" style="font-size:16px;margin-bottom:8px">PT Mitra Andalan Sejahtera</div>
        <div class="card-label">Nilai Pertanggungan</div>
        <div class="card-value" style="font-size:17px;color:var(--gold-light)">Rp 2.500.000.000</div>
        <div class="card-footer">
          <div>
            <div class="card-label">Berlaku s/d</div>
            <div style="font-size:14px;color:rgba(255,255,255,0.7)">31 Des 2025</div>
          </div>
          <div class="card-brand">LenteraOne</div>
          <div class="card-status">Aktif</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section class="about" id="tentang">
  <div class="about-visual reveal">
    <div class="about-img-frame">
      <svg width="200" height="280" viewBox="0 0 200 280" class="building-svg" fill="none" xmlns="http://www.w3.org/2000/svg">
        <rect x="60" y="40" width="80" height="220" rx="2" fill="rgba(201,168,76,0.2)" stroke="rgba(201,168,76,0.5)" stroke-width="1"/>
        <rect x="70" y="55" width="15" height="20" rx="1" fill="rgba(201,168,76,0.4)"/>
        <rect x="90" y="55" width="15" height="20" rx="1" fill="rgba(201,168,76,0.4)"/>
        <rect x="110" y="55" width="15" height="20" rx="1" fill="rgba(201,168,76,0.4)"/>
        <rect x="70" y="85" width="15" height="20" rx="1" fill="rgba(201,168,76,0.4)"/>
        <rect x="90" y="85" width="15" height="20" rx="1" fill="rgba(201,168,76,0.6)"/>
        <rect x="110" y="85" width="15" height="20" rx="1" fill="rgba(201,168,76,0.4)"/>
        <rect x="70" y="115" width="15" height="20" rx="1" fill="rgba(201,168,76,0.4)"/>
        <rect x="90" y="115" width="15" height="20" rx="1" fill="rgba(201,168,76,0.4)"/>
        <rect x="110" y="115" width="15" height="20" rx="1" fill="rgba(201,168,76,0.6)"/>
        <rect x="70" y="145" width="15" height="20" rx="1" fill="rgba(201,168,76,0.4)"/>
        <rect x="90" y="145" width="15" height="20" rx="1" fill="rgba(201,168,76,0.4)"/>
        <rect x="110" y="145" width="15" height="20" rx="1" fill="rgba(201,168,76,0.4)"/>
        <rect x="85" y="195" width="30" height="65" rx="2" fill="rgba(201,168,76,0.3)"/>
        <line x1="100" y1="40" x2="100" y2="20" stroke="rgba(201,168,76,0.6)" stroke-width="2"/>
        <polygon points="100,10 90,20 110,20" fill="rgba(201,168,76,0.7)"/>
        <rect x="20" y="120" width="35" height="140" rx="2" fill="rgba(201,168,76,0.1)" stroke="rgba(201,168,76,0.3)" stroke-width="1"/>
        <rect x="145" y="100" width="35" height="160" rx="2" fill="rgba(201,168,76,0.1)" stroke="rgba(201,168,76,0.3)" stroke-width="1"/>
      </svg>
    </div>
    <div class="about-accent-box">
      <div class="big-num">2008</div>
      <div class="big-label">Berdiri sejak tahun 2008 — lebih dari satu dekade melindungi kredit Indonesia</div>
      <div class="ojk-badge">✦ Terdaftar OJK No. KEP-125/D.05/2019</div>
    </div>
  </div>

  <div class="about-text reveal">
    <div class="section-label">Tentang Kami</div>
    <h2>Menerangi Jalan Menuju <em>Keuangan yang Aman</em></h2>
    <p class="lead">LenteraOne Insurance adalah perusahaan asuransi kredit terkemuka di Indonesia yang didedikasikan untuk melindungi institusi keuangan, korporasi, dan individu dari risiko kredit yang tidak terduga.</p>
    <div class="about-pillars">
      <div class="pillar">
        <div class="pillar-icon">🛡</div>
        <div class="pillar-text">
          <h4>Perlindungan Komprehensif</h4>
          <p>Mencakup seluruh spektrum risiko kredit dari kredit konsumer hingga kredit korporasi berskala besar.</p>
        </div>
      </div>
      <div class="pillar">
        <div class="pillar-icon">⚡</div>
        <div class="pillar-text">
          <h4>Klaim Cepat &amp; Transparan</h4>
          <p>Proses klaim yang efisien dengan target penyelesaian 14 hari kerja, didukung tim profesional berpengalaman.</p>
        </div>
      </div>
      <div class="pillar">
        <div class="pillar-icon">🏆</div>
        <div class="pillar-text">
          <h4>Peringkat Keuangan Terpercaya</h4>
          <p>Memiliki peringkat idAA dari Pefindo, mencerminkan kemampuan finansial dan kredibilitas kami.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- NUMBERS -->
<div class="numbers">
  <div class="number-box reveal">
    <span class="big"><span class="unit">Rp</span> 12T</span>
    <div class="desc">Portofolio Terjamin</div>
  </div>
  <div class="number-box reveal">
    <span class="big">850<span class="unit">+</span></span>
    <div class="desc">Mitra Lembaga Keuangan</div>
  </div>
  <div class="number-box reveal">
    <span class="big">98<span class="unit">%</span></span>
    <div class="desc">Rasio Penyelesaian Klaim</div>
  </div>
  <div class="number-box reveal">
    <span class="big">16<span class="unit">+</span></span>
    <div class="desc">Tahun Berpengalaman</div>
  </div>
</div>

<!-- PRODUCTS -->
<section class="products" id="produk">
  <div class="products-header reveal">
    <div class="section-label">Produk Kami</div>
    <h2>Solusi Asuransi untuk Setiap <em>Kebutuhan Kredit</em></h2>
  </div>
  <div class="products-grid">
    <div class="product-card reveal">
      <div class="product-icon">🏦</div>
      <h3>Asuransi Kredit Perbankan</h3>
      <p>Perlindungan menyeluruh bagi bank dan lembaga keuangan terhadap risiko gagal bayar debitur pada kredit konsumer, KPR, dan kredit kendaraan.</p>
      <div class="product-features">
        <div class="feature-item">Kredit konsumtif &amp; produktif</div>
        <div class="feature-item">KPR dan KPA</div>
        <div class="feature-item">Kredit kendaraan bermotor</div>
      </div>
      <a href="#" class="product-cta">Pelajari lebih lanjut →</a>
    </div>

    <div class="product-card featured reveal">
      <div class="product-icon">🏢</div>
      <h3>Asuransi Kredit Korporasi</h3>
      <p>Solusi premium untuk perlindungan kredit modal kerja dan investasi korporasi skala menengah hingga besar dengan limit pertanggungan fleksibel.</p>
      <div class="product-features">
        <div class="feature-item">Kredit modal kerja</div>
        <div class="feature-item">Kredit investasi</div>
        <div class="feature-item">Limit hingga Rp 500 miliar</div>
      </div>
      <a href="#" class="product-cta" style="color:var(--gold-light)">Pelajari lebih lanjut →</a>
    </div>

    <div class="product-card reveal">
      <div class="product-icon">🌐</div>
      <h3>Asuransi Kredit Ekspor</h3>
      <p>Lindungi transaksi perdagangan internasional Anda dari risiko non-pembayaran oleh pembeli asing akibat risiko komersial maupun politik.</p>
      <div class="product-features">
        <div class="feature-item">Risiko komersial &amp; politik</div>
        <div class="feature-item">Multi-valuta</div>
        <div class="feature-item">Lebih dari 80 negara tujuan</div>
      </div>
      <a href="#" class="product-cta">Pelajari lebih lanjut →</a>
    </div>

    <div class="product-card reveal">
      <div class="product-icon">📱</div>
      <h3>Asuransi Kredit Digital</h3>
      <p>Dirancang khusus untuk platform fintech, paylater, dan pembiayaan digital dengan integrasi API yang mudah dan premi kompetitif.</p>
      <div class="product-features">
        <div class="feature-item">Integrasi API real-time</div>
        <div class="feature-item">Premi berbasis risiko</div>
        <div class="feature-item">Paylater &amp; BNPL</div>
      </div>
      <a href="#" class="product-cta">Pelajari lebih lanjut →</a>
    </div>

    <div class="product-card reveal">
      <div class="product-icon">🤝</div>
      <h3>Surety Bond</h3>
      <p>Jaminan pelaksanaan proyek dan kontrak untuk sektor konstruksi, pengadaan pemerintah, dan proyek infrastruktur nasional.</p>
      <div class="product-features">
        <div class="feature-item">Jaminan penawaran</div>
        <div class="feature-item">Jaminan pelaksanaan</div>
        <div class="feature-item">Jaminan pemeliharaan</div>
      </div>
      <a href="#" class="product-cta">Pelajari lebih lanjut →</a>
    </div>

    <div class="product-card reveal">
      <div class="product-icon">🔄</div>
      <h3>Reasuransi Kredit</h3>
      <p>Layanan reasuransi kredit untuk perusahaan asuransi yang ingin mendistribusikan risiko portofolio kredit mereka dengan struktur yang terkelola.</p>
      <div class="product-features">
        <div class="feature-item">Treaty &amp; facultative</div>
        <div class="feature-item">Kapasitas besar</div>
        <div class="feature-item">Solusi portofolio</div>
      </div>
      <a href="#" class="product-cta">Pelajari lebih lanjut →</a>
    </div>
  </div>
</section>

<!-- HOW IT WORKS -->
<section class="how" id="cara-kerja">
  <div class="how-header reveal">
    <div class="section-label">Cara Kerja</div>
    <h2>Proses <em>Sederhana</em>, Perlindungan Maksimal</h2>
  </div>
  <div class="steps-row">
    <div class="step reveal">
      <div class="step-num">01</div>
      <h4>Konsultasi &amp; Analisis</h4>
      <p>Tim ahli kami menganalisis profil kredit dan kebutuhan perlindungan spesifik Anda secara menyeluruh.</p>
    </div>
    <div class="step reveal">
      <div class="step-num">02</div>
      <h4>Penawaran Polis</h4>
      <p>Kami menyajikan proposal polis yang disesuaikan dengan struktur kredit, eksposur, dan anggaran Anda.</p>
    </div>
    <div class="step reveal">
      <div class="step-num">03</div>
      <h4>Penerbitan Polis</h4>
      <p>Setelah persetujuan, polis diterbitkan secara digital dengan masa berlaku yang jelas dan dapat diakses kapan saja.</p>
    </div>
    <div class="step reveal">
      <div class="step-num">04</div>
      <h4>Klaim &amp; Penyelesaian</h4>
      <p>Klaim diproses secara transparan dengan target penyelesaian 14 hari kerja sejak dokumen lengkap diterima.</p>
    </div>
  </div>
</section>

<!-- TESTIMONIALS -->
<section class="testimonials" id="testimoni">
  <div class="testi-header reveal">
    <div class="section-label">Testimoni</div>
    <h2>Dipercaya oleh <em>Pemimpin Industri</em></h2>
  </div>
  <div class="testi-grid">
    <div class="testi-card reveal">
      <p class="testi-text">LenteraOne telah menjadi mitra asuransi kredit kami selama 7 tahun. Responsivitas tim mereka dalam penanganan klaim sungguh luar biasa—tercepat di industri ini.</p>
      <div class="testi-author">
        <div class="testi-avatar">AS</div>
        <div class="testi-info">
          <div class="name">Ahmad Suryanto</div>
          <div class="role">Direktur Risiko Kredit — Bank Nusantara</div>
          <div class="testi-stars">★★★★★</div>
        </div>
      </div>
    </div>
    <div class="testi-card reveal">
      <p class="testi-text">Integrasi API untuk produk kredit digital kami berjalan mulus. Premi yang kompetitif dan tim underwriting yang sangat profesional dan cepat merespons.</p>
      <div class="testi-author">
        <div class="testi-avatar">RW</div>
        <div class="testi-info">
          <div class="name">Ratna Widiastuti</div>
          <div class="role">Chief Risk Officer — FinanceIn Digital</div>
          <div class="testi-stars">★★★★★</div>
        </div>
      </div>
    </div>
    <div class="testi-card reveal">
      <p class="testi-text">Untuk proyek konstruksi kami, surety bond dari LenteraOne memberikan kepercayaan penuh kepada mitra kontraktor dan pemberi proyek pemerintah.</p>
      <div class="testi-author">
        <div class="testi-avatar">BH</div>
        <div class="testi-info">
          <div class="name">Budi Hartono</div>
          <div class="role">Direktur Keuangan — PT Graha Nusantara Tbk</div>
          <div class="testi-stars">★★★★★</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- PARTNERS -->
<div class="partners">
  <p>Dipercaya oleh lembaga-lembaga keuangan terkemuka</p>
  <div class="partners-row">
    <div class="partner-logo">NUSANTARA BANK</div>
    <div class="partner-logo">ARTHA FINANCE</div>
    <div class="partner-logo">MITRA INVESTAMA</div>
    <div class="partner-logo">FINANCEIN</div>
    <div class="partner-logo">GRAHA TBKINDO</div>
  </div>
</div>

<!-- CTA BANNER -->
<section class="cta-banner" id="kontak">
  <div class="reveal">
    <div class="section-label" style="justify-content:center;color:var(--gold-light)"><span style="background:var(--gold);width:28px;height:1px;display:inline-block"></span> Mulai Hari Ini</div>
    <h2>Siap Melindungi Portofolio <em style="color:var(--gold-light)">Kredit Anda?</em></h2>
    <p>Konsultasikan kebutuhan asuransi kredit Anda dengan tim ahli kami. Gratis, tanpa komitmen.</p>
    <div class="cta-actions">
      <a href="mailto:customerservice@lenteraone.co.id" class="btn-primary">Jadwalkan Konsultasi</a>
      <a href="tel:+622150001234" class="btn-outline">☎ (021) 5000-1234</a>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer id="footer">
  <div class="footer-grid">
    <div class="footer-brand">
      <span class="logo-text">LenteraOne Insurance</span>
      <p>Perusahaan asuransi kredit terpercaya yang menerangi jalan menuju keamanan finansial bagi lembaga keuangan, korporasi, dan individu Indonesia.</p>
      <div class="ojk-badge" style="margin-top:20px">✦ Terdaftar &amp; Diawasi OJK</div>
    </div>
    <div class="footer-col">
      <h5>Produk</h5>
      <a href="#">Asuransi Kredit Perbankan</a>
      <a href="#">Asuransi Kredit Korporasi</a>
      <a href="#">Asuransi Kredit Ekspor</a>
      <a href="#">Asuransi Kredit Digital</a>
      <a href="#">Surety Bond</a>
      <a href="#">Reasuransi Kredit</a>
    </div>
    <div class="footer-col">
      <h5>Perusahaan</h5>
      <a href="#">Tentang Kami</a>
      <a href="#">Manajemen</a>
      <a href="#">Laporan Tahunan</a>
      <a href="#">Karir</a>
      <a href="#">Berita &amp; Artikel</a>
      <a href="#">Hubungi Kami</a>
    </div>
    <div class="footer-col">
      <h5>Kontak</h5>
      <div class="footer-contact-item">
        <span class="contact-icon">📍</span>
        <span>Gedung LenteraOne Tower, Jl. Jenderal Sudirman Kav. 52, Jakarta 12190</span>
      </div>
      <div class="footer-contact-item">
        <span class="contact-icon">📞</span>
        <span>(021) 5000-1234</span>
      </div>
      <div class="footer-contact-item">
        <span class="contact-icon">✉</span>
        <span>customerservice@lenteraone.co.id</span>
      </div>
      <div class="footer-contact-item">
        <span class="contact-icon">🕐</span>
        <span>Senin–Jumat: 08.00–17.00 WIB</span>
      </div>
    </div>
  </div>
  <div class="footer-bottom">
    <span>© 2024 PT Lentera Kredit Indonesia. Seluruh hak dilindungi.</span>
    <div class="footer-legal">
      <a href="#">Kebijakan Privasi</a>
      <a href="#">Syarat &amp; Ketentuan</a>
      <a href="#">Peta Situs</a>
    </div>
  </div>
</footer>

<script>
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('visible');
      }
    });
  }, { threshold: 0.1, rootMargin: '0px 0px -40px 0px' });

  document.querySelectorAll('.reveal').forEach(el => observer.observe(el));

  document.querySelectorAll('a[href^="#"]').forEach(link => {
    link.addEventListener('click', e => {
      const target = document.querySelector(link.getAttribute('href'));
      if (target) {
        e.preventDefault();
        target.scrollIntoView({ behavior: 'smooth', block: 'start' });
      }
    });
  });
</script>
</body>
</html>
