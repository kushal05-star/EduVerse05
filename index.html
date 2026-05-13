<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>EduVerse — Learn Without Limits</title>
<link href="https://fonts.googleapis.com/css2?family=Clash+Display:wght@400;500;600;700&family=Syne:wght@400;600;700;800&family=DM+Sans:ital,wght@0,300;0,400;0,500;1,300&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #04060f;
    --bg2: #070d1e;
    --card: #0c1428;
    --accent1: #4f8eff;
    --accent2: #00e5c0;
    --accent3: #ff5c8a;
    --accent4: #f7c948;
    --text: #e8eeff;
    --muted: #7888aa;
    --border: rgba(79,142,255,0.15);
    --glow1: rgba(79,142,255,0.25);
    --glow2: rgba(0,229,192,0.2);
  }

  *, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'DM Sans', sans-serif;
    overflow-x: hidden;
    cursor: none;
  }

  /* CUSTOM CURSOR */
  #cursor {
    width: 12px; height: 12px;
    background: var(--accent1);
    border-radius: 50%;
    position: fixed; top: 0; left: 0;
    pointer-events: none; z-index: 9999;
    transition: transform 0.1s, background 0.2s;
    mix-blend-mode: screen;
  }
  #cursor-ring {
    width: 40px; height: 40px;
    border: 1.5px solid rgba(79,142,255,0.5);
    border-radius: 50%;
    position: fixed; top: 0; left: 0;
    pointer-events: none; z-index: 9998;
    transition: transform 0.18s cubic-bezier(.25,.46,.45,.94), border-color 0.2s;
  }

  /* STAR BACKGROUND */
  #stars-canvas {
    position: fixed; top: 0; left: 0;
    width: 100%; height: 100%;
    z-index: 0; pointer-events: none;
  }

  /* NAV */
  nav {
    position: fixed; top: 0; left: 0; right: 0; z-index: 100;
    padding: 20px 60px;
    display: flex; align-items: center; justify-content: space-between;
    background: rgba(4,6,15,0.7);
    backdrop-filter: blur(20px);
    border-bottom: 1px solid var(--border);
    transition: padding 0.3s;
  }
  nav.scrolled { padding: 14px 60px; }

  .nav-logo {
    font-family: 'Syne', sans-serif;
    font-weight: 800; font-size: 1.5rem;
    background: linear-gradient(135deg, var(--accent1), var(--accent2));
    -webkit-background-clip: text; -webkit-text-fill-color: transparent;
    letter-spacing: -0.5px;
  }
  .nav-logo span { color: var(--accent3); -webkit-text-fill-color: var(--accent3); }

  .nav-links { display: flex; gap: 36px; list-style: none; }
  .nav-links a {
    color: var(--muted); text-decoration: none;
    font-size: 0.9rem; font-weight: 500; letter-spacing: 0.02em;
    transition: color 0.2s; position: relative;
  }
  .nav-links a::after {
    content: ''; position: absolute; bottom: -4px; left: 0;
    width: 0; height: 1.5px; background: var(--accent2);
    transition: width 0.3s;
  }
  .nav-links a:hover { color: var(--text); }
  .nav-links a:hover::after { width: 100%; }

  .nav-cta {
    padding: 10px 24px;
    background: linear-gradient(135deg, var(--accent1), #2960cc);
    border: none; border-radius: 50px;
    color: white; font-size: 0.88rem; font-weight: 600;
    cursor: none; transition: transform 0.2s, box-shadow 0.2s;
    font-family: 'DM Sans', sans-serif;
    box-shadow: 0 4px 20px rgba(79,142,255,0.3);
  }
  .nav-cta:hover { transform: translateY(-2px); box-shadow: 0 8px 30px rgba(79,142,255,0.5); }

  /* HERO */
  .hero {
    min-height: 100vh;
    display: flex; align-items: center; justify-content: center;
    flex-direction: column; text-align: center;
    padding: 120px 40px 80px;
    position: relative; z-index: 1;
  }

  .hero-badge {
    display: inline-flex; align-items: center; gap: 8px;
    background: rgba(79,142,255,0.1);
    border: 1px solid rgba(79,142,255,0.3);
    padding: 6px 18px; border-radius: 50px;
    font-size: 0.8rem; font-weight: 600; color: var(--accent1);
    letter-spacing: 0.1em; text-transform: uppercase; margin-bottom: 32px;
    opacity: 0; animation: fadeUp 0.8s 0.2s forwards;
  }
  .hero-badge .dot {
    width: 6px; height: 6px; background: var(--accent2);
    border-radius: 50%; animation: pulse 2s infinite;
  }

  @keyframes pulse { 0%,100%{opacity:1;transform:scale(1)} 50%{opacity:0.4;transform:scale(0.8)} }

  .hero h1 {
    font-family: 'Syne', sans-serif;
    font-size: clamp(3rem, 8vw, 7rem);
    font-weight: 800; line-height: 1.0;
    letter-spacing: -0.03em;
    opacity: 0; animation: fadeUp 0.9s 0.4s forwards;
  }
  .hero h1 .line { display: block; }
  .hero h1 .gradient-text {
    background: linear-gradient(135deg, var(--accent1) 0%, var(--accent2) 50%, var(--accent3) 100%);
    -webkit-background-clip: text; -webkit-text-fill-color: transparent;
    background-size: 200% 200%; animation: gradShift 4s ease infinite;
  }
  @keyframes gradShift { 0%,100%{background-position:0% 50%} 50%{background-position:100% 50%} }

  .hero p {
    max-width: 560px; margin: 28px auto 0;
    font-size: 1.15rem; line-height: 1.7; color: var(--muted);
    font-weight: 300;
    opacity: 0; animation: fadeUp 0.9s 0.6s forwards;
  }

  .hero-buttons {
    display: flex; gap: 16px; margin-top: 44px; flex-wrap: wrap; justify-content: center;
    opacity: 0; animation: fadeUp 0.9s 0.8s forwards;
  }

  .btn-primary {
    padding: 16px 40px; border-radius: 50px;
    background: linear-gradient(135deg, var(--accent1), var(--accent2));
    color: #04060f; font-weight: 700; font-size: 1rem;
    border: none; cursor: none; text-decoration: none;
    transition: transform 0.2s, box-shadow 0.3s;
    box-shadow: 0 0 30px rgba(79,142,255,0.4);
    position: relative; overflow: hidden;
  }
  .btn-primary::before {
    content: ''; position: absolute; top: -50%; left: -60%;
    width: 40%; height: 200%; background: rgba(255,255,255,0.3);
    transform: skewX(-20deg); transition: left 0.5s;
  }
  .btn-primary:hover::before { left: 130%; }
  .btn-primary:hover { transform: translateY(-3px); box-shadow: 0 0 50px rgba(79,142,255,0.6); }

  .btn-ghost {
    padding: 16px 40px; border-radius: 50px;
    background: transparent; border: 1.5px solid var(--border);
    color: var(--text); font-weight: 500; font-size: 1rem;
    cursor: none; text-decoration: none;
    transition: border-color 0.3s, background 0.3s, transform 0.2s;
    backdrop-filter: blur(10px);
  }
  .btn-ghost:hover { border-color: var(--accent1); background: rgba(79,142,255,0.08); transform: translateY(-3px); }

  .hero-stats {
    display: flex; gap: 60px; margin-top: 70px; flex-wrap: wrap; justify-content: center;
    opacity: 0; animation: fadeUp 0.9s 1s forwards;
  }
  .stat { text-align: center; }
  .stat-num {
    font-family: 'Syne', sans-serif; font-size: 2.4rem; font-weight: 800;
    background: linear-gradient(135deg, var(--accent1), var(--accent2));
    -webkit-background-clip: text; -webkit-text-fill-color: transparent;
  }
  .stat-label { font-size: 0.82rem; color: var(--muted); margin-top: 4px; letter-spacing: 0.06em; text-transform: uppercase; }

  @keyframes fadeUp { from{opacity:0;transform:translateY(30px)} to{opacity:1;transform:translateY(0)} }

  /* FLOATING ORBS */
  .orb {
    position: absolute; border-radius: 50%;
    filter: blur(80px); pointer-events: none; z-index: 0;
  }
  .orb1 { width: 500px; height: 500px; background: rgba(79,142,255,0.12); top: -100px; right: -100px; animation: floatOrb 8s ease-in-out infinite; }
  .orb2 { width: 400px; height: 400px; background: rgba(0,229,192,0.1); bottom: 0; left: -100px; animation: floatOrb 10s ease-in-out infinite reverse; }
  .orb3 { width: 300px; height: 300px; background: rgba(255,92,138,0.1); top: 40%; left: 50%; animation: floatOrb 12s ease-in-out infinite 2s; }
  @keyframes floatOrb { 0%,100%{transform:translate(0,0)} 50%{transform:translate(30px,-40px)} }

  /* SECTION COMMON */
  section { position: relative; z-index: 1; }
  .section-label {
    font-size: 0.78rem; font-weight: 700; letter-spacing: 0.15em;
    text-transform: uppercase; color: var(--accent2);
    display: flex; align-items: center; gap: 10px; margin-bottom: 16px;
  }
  .section-label::before { content: ''; display: block; width: 30px; height: 1.5px; background: var(--accent2); }

  .section-title {
    font-family: 'Syne', sans-serif; font-size: clamp(2rem, 4vw, 3.2rem);
    font-weight: 800; line-height: 1.1; letter-spacing: -0.02em;
  }
  .section-title em { font-style: normal; color: var(--accent1); }

  /* CATEGORIES */
  .categories {
    padding: 100px 60px;
    background: var(--bg2);
  }
  .categories-header { text-align: center; margin-bottom: 60px; }

  .categories-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: 16px; max-width: 1100px; margin: 0 auto;
  }
  .cat-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 20px;
    padding: 32px 20px; text-align: center;
    cursor: none; transition: transform 0.3s, border-color 0.3s, box-shadow 0.3s;
    position: relative; overflow: hidden;
  }
  .cat-card::before {
    content: ''; position: absolute; inset: 0;
    background: var(--cat-color, var(--accent1));
    opacity: 0; transition: opacity 0.3s;
    border-radius: 20px;
  }
  .cat-card:hover { transform: translateY(-8px); border-color: var(--cat-color, var(--accent1)); box-shadow: 0 20px 40px rgba(0,0,0,0.4); }
  .cat-card:hover::before { opacity: 0.06; }

  .cat-icon {
    font-size: 2.4rem; margin-bottom: 14px; display: block;
    transition: transform 0.3s;
  }
  .cat-card:hover .cat-icon { transform: scale(1.2) rotate(-5deg); }
  .cat-name { font-weight: 600; font-size: 0.95rem; color: var(--text); margin-bottom: 6px; }
  .cat-count { font-size: 0.8rem; color: var(--muted); }

  /* COURSES */
  .courses { padding: 100px 60px; }
  .courses-header {
    display: flex; align-items: flex-end; justify-content: space-between;
    margin-bottom: 50px; flex-wrap: wrap; gap: 20px;
    max-width: 1200px; margin-left: auto; margin-right: auto;
  }
  .courses-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
    gap: 24px; max-width: 1200px; margin: 0 auto;
  }

  .course-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 24px; overflow: hidden;
    cursor: none; transition: transform 0.3s, box-shadow 0.3s;
    position: relative;
  }
  .course-card:hover { transform: translateY(-10px); box-shadow: 0 30px 60px rgba(0,0,0,0.5); }

  .course-thumb {
    height: 180px; position: relative; overflow: hidden;
    display: flex; align-items: center; justify-content: center;
    font-size: 4rem;
  }
  .course-thumb-bg {
    position: absolute; inset: 0;
    background: var(--thumb-bg);
    transition: transform 0.4s;
  }
  .course-card:hover .course-thumb-bg { transform: scale(1.08); }

  .course-badge {
    position: absolute; top: 14px; left: 14px;
    padding: 4px 12px; border-radius: 50px; font-size: 0.72rem;
    font-weight: 700; letter-spacing: 0.06em; text-transform: uppercase;
    background: var(--badge-bg); color: var(--badge-color);
  }

  .course-body { padding: 24px; }
  .course-cat { font-size: 0.75rem; font-weight: 600; color: var(--accent2); letter-spacing: 0.08em; text-transform: uppercase; margin-bottom: 8px; }
  .course-title { font-family: 'Syne', sans-serif; font-size: 1.1rem; font-weight: 700; line-height: 1.3; margin-bottom: 12px; }
  .course-desc { font-size: 0.86rem; color: var(--muted); line-height: 1.6; margin-bottom: 20px; }

  .course-meta { display: flex; gap: 16px; margin-bottom: 20px; }
  .meta-item { display: flex; align-items: center; gap: 5px; font-size: 0.8rem; color: var(--muted); }
  .meta-icon { font-size: 0.85rem; }

  .course-footer {
    display: flex; align-items: center; justify-content: space-between;
    padding-top: 16px; border-top: 1px solid var(--border);
  }
  .course-price { font-family: 'Syne', sans-serif; font-size: 1.3rem; font-weight: 800; color: var(--accent2); }
  .course-price .original { font-size: 0.85rem; color: var(--muted); text-decoration: line-through; font-family: 'DM Sans', sans-serif; font-weight: 400; margin-left: 6px; }
  .enroll-btn {
    padding: 9px 22px; border-radius: 50px;
    background: var(--accent1); border: none; color: white;
    font-size: 0.84rem; font-weight: 600; cursor: none;
    transition: background 0.2s, transform 0.2s;
    font-family: 'DM Sans', sans-serif;
  }
  .enroll-btn:hover { background: var(--accent2); color: #04060f; transform: scale(1.05); }

  .stars { color: var(--accent4); font-size: 0.82rem; }
  .rating-num { font-size: 0.82rem; color: var(--muted); margin-left: 4px; }

  /* TABS */
  .filter-tabs {
    display: flex; gap: 10px; flex-wrap: wrap;
  }
  .tab {
    padding: 9px 22px; border-radius: 50px; border: 1px solid var(--border);
    background: transparent; color: var(--muted);
    font-size: 0.85rem; font-weight: 500; cursor: none;
    transition: all 0.2s; font-family: 'DM Sans', sans-serif;
  }
  .tab.active, .tab:hover {
    background: var(--accent1); border-color: var(--accent1);
    color: white;
  }

  /* FEATURES / HOW IT WORKS */
  .features {
    padding: 100px 60px;
    background: var(--bg2);
  }
  .features-grid {
    display: grid; grid-template-columns: 1fr 1fr; gap: 80px;
    max-width: 1100px; margin: 60px auto 0; align-items: center;
  }

  .feature-visual {
    position: relative; height: 450px;
  }
  .fv-card {
    position: absolute; background: var(--card);
    border: 1px solid var(--border); border-radius: 20px; padding: 20px;
    box-shadow: 0 20px 50px rgba(0,0,0,0.5);
  }
  .fv-main { inset: 0; display: flex; flex-direction: column; justify-content: center; align-items: center; gap: 16px; }
  .fv-main .big-icon { font-size: 5rem; animation: float 4s ease-in-out infinite; }
  @keyframes float { 0%,100%{transform:translateY(0)} 50%{transform:translateY(-12px)} }

  .fv-overlay1 { bottom: 20px; left: -30px; padding: 14px 18px; min-width: 180px; animation: floatCard 5s ease-in-out infinite; }
  .fv-overlay2 { top: 30px; right: -20px; padding: 14px 18px; min-width: 160px; animation: floatCard 6s ease-in-out infinite reverse; }
  @keyframes floatCard { 0%,100%{transform:translateY(0)} 50%{transform:translateY(-10px)} }

  .fv-label { font-size: 0.72rem; color: var(--muted); font-weight: 500; margin-bottom: 4px; }
  .fv-value { font-family: 'Syne', sans-serif; font-weight: 700; font-size: 1.1rem; color: var(--accent2); }
  .progress-bar { height: 6px; background: rgba(255,255,255,0.08); border-radius: 3px; margin-top: 10px; overflow: hidden; }
  .progress-fill { height: 100%; background: linear-gradient(90deg, var(--accent1), var(--accent2)); border-radius: 3px; animation: fillBar 3s ease forwards 1s; }
  @keyframes fillBar { from{width:0} to{width:var(--fill)} }

  .features-list { display: flex; flex-direction: column; gap: 28px; }
  .feat-item { display: flex; gap: 18px; align-items: flex-start; opacity: 0; transform: translateX(30px); transition: opacity 0.6s, transform 0.6s; }
  .feat-item.visible { opacity: 1; transform: translateX(0); }
  .feat-icon {
    width: 50px; height: 50px; border-radius: 14px; flex-shrink: 0;
    display: flex; align-items: center; justify-content: center; font-size: 1.4rem;
    background: var(--feat-bg); border: 1px solid var(--feat-border);
  }
  .feat-text h4 { font-family: 'Syne', sans-serif; font-weight: 700; margin-bottom: 6px; }
  .feat-text p { font-size: 0.88rem; color: var(--muted); line-height: 1.6; }

  /* TESTIMONIALS */
  .testimonials { padding: 100px 60px; }
  .testi-header { text-align: center; margin-bottom: 60px; }
  .testi-grid {
    display: grid; grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 24px; max-width: 1100px; margin: 0 auto;
  }
  .testi-card {
    background: var(--card); border: 1px solid var(--border);
    border-radius: 24px; padding: 28px;
    transition: transform 0.3s, box-shadow 0.3s;
    position: relative;
  }
  .testi-card:hover { transform: translateY(-6px); box-shadow: 0 20px 40px rgba(0,0,0,0.4); }
  .testi-quote { font-size: 3rem; color: var(--accent1); line-height: 1; margin-bottom: 14px; font-family: 'Syne', sans-serif; }
  .testi-text { font-size: 0.92rem; line-height: 1.7; color: var(--muted); margin-bottom: 20px; }
  .testi-author { display: flex; align-items: center; gap: 12px; }
  .testi-avatar {
    width: 44px; height: 44px; border-radius: 50%;
    display: flex; align-items: center; justify-content: center;
    font-size: 1.3rem; font-weight: 700;
    background: var(--av-bg); color: var(--av-color);
    font-family: 'Syne', sans-serif;
  }
  .testi-name { font-weight: 600; font-size: 0.9rem; }
  .testi-role { font-size: 0.78rem; color: var(--muted); }

  /* PRICING */
  .pricing {
    padding: 100px 60px;
    background: var(--bg2);
  }
  .pricing-header { text-align: center; margin-bottom: 60px; }
  .pricing-grid {
    display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 24px; max-width: 900px; margin: 0 auto;
  }
  .price-card {
    background: var(--card); border: 1px solid var(--border);
    border-radius: 28px; padding: 36px 30px;
    position: relative; overflow: hidden;
    transition: transform 0.3s, box-shadow 0.3s;
  }
  .price-card.popular {
    border-color: var(--accent1);
    background: linear-gradient(145deg, rgba(79,142,255,0.1), var(--card));
    box-shadow: 0 0 40px rgba(79,142,255,0.2);
  }
  .price-card:hover { transform: translateY(-8px); box-shadow: 0 30px 60px rgba(0,0,0,0.4); }

  .popular-badge {
    position: absolute; top: 20px; right: 20px;
    background: var(--accent1); color: white;
    padding: 4px 14px; border-radius: 50px; font-size: 0.72rem; font-weight: 700;
  }
  .price-plan { font-size: 0.8rem; font-weight: 700; letter-spacing: 0.1em; text-transform: uppercase; color: var(--muted); margin-bottom: 16px; }
  .price-amount { font-family: 'Syne', sans-serif; font-size: 3rem; font-weight: 800; margin-bottom: 6px; }
  .price-amount span { font-size: 1.2rem; font-weight: 400; color: var(--muted); }
  .price-desc { font-size: 0.85rem; color: var(--muted); margin-bottom: 28px; line-height: 1.5; }

  .price-features { list-style: none; margin-bottom: 32px; display: flex; flex-direction: column; gap: 12px; }
  .price-features li { display: flex; align-items: center; gap: 10px; font-size: 0.88rem; }
  .check { color: var(--accent2); font-size: 1rem; }
  .cross { color: var(--muted); font-size: 1rem; }
  .price-features li.inactive { color: var(--muted); }

  .price-btn {
    width: 100%; padding: 14px;
    border-radius: 50px; font-size: 0.9rem; font-weight: 600;
    cursor: none; border: none; font-family: 'DM Sans', sans-serif;
    transition: transform 0.2s, box-shadow 0.2s;
  }
  .price-btn-outline {
    background: transparent; border: 1.5px solid var(--border); color: var(--text);
  }
  .price-btn-outline:hover { border-color: var(--accent1); color: var(--accent1); }
  .price-btn-filled {
    background: linear-gradient(135deg, var(--accent1), var(--accent2));
    color: #04060f;
    box-shadow: 0 8px 24px rgba(79,142,255,0.4);
  }
  .price-btn-filled:hover { transform: translateY(-2px); box-shadow: 0 12px 32px rgba(79,142,255,0.6); }

  /* CTA BANNER */
  .cta-banner {
    padding: 100px 60px; text-align: center; position: relative; overflow: hidden;
  }
  .cta-banner::before {
    content: ''; position: absolute; inset: 0;
    background: radial-gradient(ellipse at center, rgba(79,142,255,0.12) 0%, transparent 70%);
  }
  .cta-banner h2 {
    font-family: 'Syne', sans-serif; font-size: clamp(2rem, 5vw, 4rem);
    font-weight: 800; line-height: 1.1; letter-spacing: -0.02em; margin-bottom: 20px;
  }
  .cta-banner p { font-size: 1.1rem; color: var(--muted); margin-bottom: 40px; }

  /* FOOTER */
  footer {
    padding: 60px 60px 30px;
    border-top: 1px solid var(--border);
    background: var(--bg);
  }
  .footer-grid {
    display: grid; grid-template-columns: 2fr 1fr 1fr 1fr;
    gap: 50px; margin-bottom: 50px;
  }
  .footer-brand p { font-size: 0.88rem; color: var(--muted); margin-top: 14px; line-height: 1.7; max-width: 280px; }
  .footer-col h5 { font-weight: 700; font-size: 0.9rem; margin-bottom: 18px; letter-spacing: 0.05em; }
  .footer-col ul { list-style: none; display: flex; flex-direction: column; gap: 10px; }
  .footer-col a { color: var(--muted); text-decoration: none; font-size: 0.87rem; transition: color 0.2s; }
  .footer-col a:hover { color: var(--text); }
  .footer-bottom { display: flex; justify-content: space-between; align-items: center; color: var(--muted); font-size: 0.82rem; padding-top: 24px; border-top: 1px solid var(--border); }

  /* SCROLL REVEAL */
  .reveal { opacity: 0; transform: translateY(40px); transition: opacity 0.7s, transform 0.7s; }
  .reveal.visible { opacity: 1; transform: translateY(0); }

  /* COUNTER ANIMATION */
  .count-up { display: inline-block; }

  /* SCROLL INDICATOR */
  .scroll-indicator {
    position: absolute; bottom: 40px; left: 50%; transform: translateX(-50%);
    display: flex; flex-direction: column; align-items: center; gap: 8px;
    color: var(--muted); font-size: 0.75rem; letter-spacing: 0.1em;
    text-transform: uppercase; animation: fadeUp 1s 1.5s forwards; opacity: 0;
  }
  .scroll-mouse {
    width: 24px; height: 38px; border: 1.5px solid rgba(255,255,255,0.2);
    border-radius: 12px; position: relative;
  }
  .scroll-wheel {
    width: 3px; height: 8px; background: var(--accent1);
    border-radius: 2px; position: absolute; top: 6px; left: 50%; transform: translateX(-50%);
    animation: scrollWheel 2s infinite;
  }
  @keyframes scrollWheel { 0%{top:6px;opacity:1} 100%{top:22px;opacity:0} }

  /* SEARCH BAR */
  .hero-search {
    display: flex; align-items: center;
    background: rgba(255,255,255,0.05); border: 1px solid var(--border);
    border-radius: 50px; padding: 8px 8px 8px 24px;
    max-width: 500px; width: 100%; margin: 32px auto 0;
    backdrop-filter: blur(10px);
    opacity: 0; animation: fadeUp 0.9s 0.7s forwards;
    transition: border-color 0.3s;
  }
  .hero-search:focus-within { border-color: var(--accent1); }
  .hero-search input {
    flex: 1; background: transparent; border: none; outline: none;
    color: var(--text); font-size: 0.9rem; font-family: 'DM Sans', sans-serif;
  }
  .hero-search input::placeholder { color: var(--muted); }
  .search-btn {
    padding: 10px 24px; border-radius: 50px; border: none;
    background: var(--accent1); color: white; font-weight: 600;
    font-size: 0.85rem; cursor: none; font-family: 'DM Sans', sans-serif;
    transition: background 0.2s;
  }
  .search-btn:hover { background: var(--accent2); color: #04060f; }

  /* NAV LOGIN */
  .nav-login {
    padding: 10px 22px; border-radius: 50px;
    background: transparent; border: 1.5px solid var(--border);
    color: var(--text); font-size: 0.88rem; font-weight: 500;
    cursor: none; transition: border-color 0.2s, color 0.2s;
    font-family: 'DM Sans', sans-serif;
  }
  .nav-login:hover { border-color: var(--accent1); color: var(--accent1); }

  /* AUTH OVERLAY */
  #auth-overlay {
    position: fixed; inset: 0; z-index: 1000;
    background: rgba(4,6,15,0.85);
    backdrop-filter: blur(18px);
    display: flex; align-items: center; justify-content: center;
    opacity: 0; pointer-events: none;
    transition: opacity 0.4s;
  }
  #auth-overlay.open { opacity: 1; pointer-events: all; }

  .auth-modal {
    position: relative;
    width: 100%; max-width: 460px;
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 32px; overflow: hidden;
    box-shadow: 0 40px 80px rgba(0,0,0,0.6), 0 0 60px rgba(79,142,255,0.12);
    transform: translateY(40px) scale(0.96);
    transition: transform 0.4s cubic-bezier(.34,1.56,.64,1);
  }
  #auth-overlay.open .auth-modal { transform: translateY(0) scale(1); }

  /* Glowing top border */
  .auth-modal::before {
    content: '';
    position: absolute; top: 0; left: 0; right: 0; height: 2px;
    background: linear-gradient(90deg, var(--accent1), var(--accent2), var(--accent3));
    background-size: 200% 100%;
    animation: borderShift 3s linear infinite;
  }
  @keyframes borderShift { 0%{background-position:0%} 100%{background-position:200%} }

  .auth-close {
    position: absolute; top: 18px; right: 18px;
    width: 34px; height: 34px; border-radius: 50%;
    background: rgba(255,255,255,0.06); border: 1px solid var(--border);
    color: var(--muted); font-size: 1rem; cursor: none;
    display: flex; align-items: center; justify-content: center;
    transition: background 0.2s, color 0.2s;
  }
  .auth-close:hover { background: rgba(255,92,138,0.15); color: var(--accent3); }

  /* TABS */
  .auth-tabs {
    display: flex; padding: 28px 32px 0;
    gap: 0; border-bottom: 1px solid var(--border);
  }
  .auth-tab {
    flex: 1; padding: 0 0 16px; background: none; border: none;
    font-family: 'Syne', sans-serif; font-size: 1rem; font-weight: 700;
    color: var(--muted); cursor: none; position: relative;
    transition: color 0.25s; letter-spacing: -0.01em;
  }
  .auth-tab.active { color: var(--text); }
  .auth-tab::after {
    content: ''; position: absolute; bottom: -1px; left: 0; right: 0;
    height: 2px; background: var(--accent1);
    transform: scaleX(0); transition: transform 0.3s cubic-bezier(.34,1.56,.64,1);
    border-radius: 2px;
  }
  .auth-tab.active::after { transform: scaleX(1); }

  /* PANELS */
  .auth-panels { position: relative; overflow: hidden; }
  .auth-panel {
    padding: 32px 32px 36px;
    position: absolute; top: 0; left: 0; width: 100%;
    opacity: 0; transform: translateX(30px);
    transition: opacity 0.35s, transform 0.35s;
    pointer-events: none;
  }
  .auth-panel.active {
    position: relative; opacity: 1; transform: translateX(0);
    pointer-events: all;
  }
  .auth-panel.slide-left { transform: translateX(-30px); opacity: 0; }

  .auth-logo {
    font-family: 'Syne', sans-serif; font-weight: 800; font-size: 1.1rem;
    margin-bottom: 6px;
    background: linear-gradient(135deg, var(--accent1), var(--accent2));
    -webkit-background-clip: text; -webkit-text-fill-color: transparent;
  }
  .auth-logo span { -webkit-text-fill-color: var(--accent3); }

  .auth-heading {
    font-family: 'Syne', sans-serif; font-size: 1.55rem; font-weight: 800;
    letter-spacing: -0.02em; margin-bottom: 6px;
  }
  .auth-sub { font-size: 0.86rem; color: var(--muted); margin-bottom: 28px; line-height: 1.5; }

  /* SOCIAL BUTTONS */
  .social-btns { display: flex; gap: 12px; margin-bottom: 22px; }
  .social-btn {
    flex: 1; padding: 11px; border-radius: 14px;
    background: rgba(255,255,255,0.04); border: 1px solid var(--border);
    color: var(--text); font-size: 0.85rem; font-weight: 500;
    cursor: none; transition: background 0.2s, border-color 0.2s;
    display: flex; align-items: center; justify-content: center; gap: 8px;
    font-family: 'DM Sans', sans-serif;
  }
  .social-btn:hover { background: rgba(255,255,255,0.08); border-color: rgba(255,255,255,0.2); }
  .social-icon { font-size: 1.1rem; }

  .auth-divider {
    display: flex; align-items: center; gap: 12px;
    margin-bottom: 22px; color: var(--muted); font-size: 0.8rem;
  }
  .auth-divider::before, .auth-divider::after {
    content: ''; flex: 1; height: 1px; background: var(--border);
  }

  /* FORM FIELDS */
  .auth-field { margin-bottom: 16px; }
  .auth-field label {
    display: block; font-size: 0.8rem; font-weight: 600;
    color: var(--muted); margin-bottom: 7px; letter-spacing: 0.04em;
  }
  .field-wrap {
    position: relative; display: flex; align-items: center;
  }
  .field-icon {
    position: absolute; left: 14px; font-size: 1rem;
    pointer-events: none; opacity: 0.5;
    transition: opacity 0.2s;
  }
  .auth-input {
    width: 100%; padding: 12px 14px 12px 40px;
    background: rgba(255,255,255,0.04); border: 1.5px solid var(--border);
    border-radius: 14px; color: var(--text);
    font-size: 0.9rem; font-family: 'DM Sans', sans-serif;
    outline: none; transition: border-color 0.25s, background 0.25s, box-shadow 0.25s;
  }
  .auth-input:focus {
    border-color: var(--accent1);
    background: rgba(79,142,255,0.06);
    box-shadow: 0 0 0 4px rgba(79,142,255,0.1);
  }
  .auth-input:focus + .field-icon, .field-wrap:focus-within .field-icon { opacity: 1; }
  .auth-input::placeholder { color: rgba(120,136,170,0.6); }

  /* Password toggle */
  .pwd-toggle {
    position: absolute; right: 14px; background: none; border: none;
    color: var(--muted); cursor: none; font-size: 1rem;
    transition: color 0.2s;
  }
  .pwd-toggle:hover { color: var(--text); }

  /* Strength bar */
  .strength-bar {
    height: 4px; background: rgba(255,255,255,0.06);
    border-radius: 2px; margin-top: 8px; overflow: hidden;
  }
  .strength-fill {
    height: 100%; width: 0; border-radius: 2px;
    transition: width 0.4s, background 0.4s;
  }
  .strength-label { font-size: 0.72rem; color: var(--muted); margin-top: 4px; }

  /* Row */
  .auth-row {
    display: flex; justify-content: space-between; align-items: center;
    margin-bottom: 22px; flex-wrap: wrap; gap: 8px;
  }
  .auth-check { display: flex; align-items: center; gap: 8px; cursor: none; }
  .auth-check input[type=checkbox] {
    width: 16px; height: 16px; accent-color: var(--accent1); cursor: none;
  }
  .auth-check label { font-size: 0.82rem; color: var(--muted); cursor: none; }
  .auth-forgot { font-size: 0.82rem; color: var(--accent1); text-decoration: none; }
  .auth-forgot:hover { text-decoration: underline; }

  /* Submit btn */
  .auth-submit {
    width: 100%; padding: 14px; border-radius: 50px;
    background: linear-gradient(135deg, var(--accent1), var(--accent2));
    border: none; color: #04060f; font-size: 0.95rem; font-weight: 700;
    cursor: none; font-family: 'Syne', sans-serif;
    transition: transform 0.2s, box-shadow 0.3s;
    box-shadow: 0 6px 24px rgba(79,142,255,0.4);
    position: relative; overflow: hidden; letter-spacing: 0.01em;
  }
  .auth-submit::before {
    content: ''; position: absolute; top: -50%; left: -60%;
    width: 40%; height: 200%; background: rgba(255,255,255,0.25);
    transform: skewX(-20deg); transition: left 0.5s;
  }
  .auth-submit:hover::before { left: 130%; }
  .auth-submit:hover { transform: translateY(-2px); box-shadow: 0 10px 32px rgba(79,142,255,0.6); }
  .auth-submit:active { transform: scale(0.98); }

  /* Loading state */
  .auth-submit.loading {
    pointer-events: none; opacity: 0.8;
  }
  .auth-submit.loading::after {
    content: ''; display: inline-block;
    width: 14px; height: 14px; border: 2px solid rgba(0,0,0,0.3);
    border-top-color: #04060f; border-radius: 50%;
    animation: spin 0.7s linear infinite; margin-left: 8px; vertical-align: middle;
  }
  @keyframes spin { to{transform:rotate(360deg)} }

  /* Success state */
  .auth-success {
    text-align: center; padding: 20px 0 10px;
    display: none;
  }
  .auth-success .success-icon {
    font-size: 3.5rem; animation: bounceIn 0.6s cubic-bezier(.34,1.56,.64,1);
    display: block; margin-bottom: 14px;
  }
  @keyframes bounceIn { from{transform:scale(0);opacity:0} to{transform:scale(1);opacity:1} }
  .auth-success h3 { font-family:'Syne',sans-serif; font-size:1.3rem; font-weight:800; margin-bottom:8px; }
  .auth-success p { color:var(--muted); font-size:0.88rem; }

  .auth-switch { text-align: center; margin-top: 20px; font-size: 0.85rem; color: var(--muted); }
  .auth-switch a { color: var(--accent1); font-weight: 600; text-decoration: none; cursor: none; }
  .auth-switch a:hover { text-decoration: underline; }

  /* Terms */
  .auth-terms { font-size: 0.75rem; color: var(--muted); text-align: center; margin-top: 14px; line-height: 1.5; }
  .auth-terms a { color: var(--accent1); text-decoration: none; }

  /* Error shake */
  @keyframes shake { 0%,100%{transform:translateX(0)} 20%,60%{transform:translateX(-6px)} 40%,80%{transform:translateX(6px)} }
  .shake { animation: shake 0.4s ease; }

  /* Input error state */
  .auth-input.error { border-color: var(--accent3); box-shadow: 0 0 0 4px rgba(255,92,138,0.15); }
  .field-error { font-size: 0.75rem; color: var(--accent3); margin-top: 5px; display: none; }
  .field-error.show { display: block; }

  @media(max-width:768px) {
    nav { padding: 16px 24px; }
    .nav-links { display: none; }
    .hero { padding: 100px 24px 60px; }
    .categories, .courses, .features, .testimonials, .pricing, .cta-banner { padding: 70px 24px; }
    .features-grid { grid-template-columns: 1fr; }
    .feature-visual { height: 300px; }
    .footer-grid { grid-template-columns: 1fr 1fr; }
  }
</style>
</head>
<body>

<canvas id="stars-canvas"></canvas>
<div id="cursor"></div>
<div id="cursor-ring"></div>

<!-- NAV -->
<nav id="navbar">
  <div class="nav-logo">Edu<span>Verse</span></div>
  <ul class="nav-links">
    <li><a href="#courses">Courses</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#testimonials">Stories</a></li>
    <li><a href="#pricing">Pricing</a></li>
  </ul>
  <div style="display:flex;gap:12px;align-items:center">
    <button class="nav-login" onclick="openAuth('login')">Log In</button>
    <button class="nav-cta" onclick="openAuth('signup')">Get Started Free</button>
  </div>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="orb orb1"></div>
  <div class="orb orb2"></div>
  <div class="orb orb3"></div>

  <div class="hero-badge">
    <span class="dot"></span>
    New: AI-Powered Learning Paths Just Launched
  </div>

  <h1>
    <span class="line">Master Any Skill</span>
    <span class="line gradient-text">Learn Without Limits</span>
  </h1>

  <div class="hero-search">
    <input type="text" id="searchInput" placeholder="Search 1,200+ courses...">
    <button class="search-btn" onclick="handleSearch()">🔍 Search</button>
  </div>

  <p>Join 2.4 million learners mastering web dev, design, data science, AI, and more — with expert-led courses and real projects.</p>

  <div class="hero-buttons">
    <a href="#courses" class="btn-primary">Explore Courses ✦</a>
    <a href="#features" class="btn-ghost">See How It Works →</a>
  </div>

  <div class="hero-stats">
    <div class="stat">
      <div class="stat-num"><span class="count-up" data-target="2400000" data-suffix="M+" data-short="2.4">2.4M+</span></div>
      <div class="stat-label">Active Learners</div>
    </div>
    <div class="stat">
      <div class="stat-num"><span class="count-up" data-target="1200" data-suffix="+" data-short="1,200">1,200+</span></div>
      <div class="stat-label">Expert Courses</div>
    </div>
    <div class="stat">
      <div class="stat-num"><span class="count-up" data-target="98" data-suffix="%" data-short="98">98%</span></div>
      <div class="stat-label">Satisfaction Rate</div>
    </div>
    <div class="stat">
      <div class="stat-num"><span class="count-up" data-target="180" data-suffix="+" data-short="180">180+</span></div>
      <div class="stat-label">Countries Reached</div>
    </div>
  </div>

  <div class="scroll-indicator">
    <div class="scroll-mouse"><div class="scroll-wheel"></div></div>
    Scroll
  </div>
</section>

<!-- CATEGORIES -->
<section class="categories" id="categories">
  <div class="categories-header reveal">
    <div class="section-label">Browse by Topic</div>
    <h2 class="section-title">Find Your <em>Learning Path</em></h2>
  </div>
  <div class="categories-grid">
    <div class="cat-card reveal" style="--cat-color:#4f8eff"><span class="cat-icon">💻</span><div class="cat-name">Web Development</div><div class="cat-count">240+ Courses</div></div>
    <div class="cat-card reveal" style="--cat-color:#00e5c0"><span class="cat-icon">🎨</span><div class="cat-name">UI/UX Design</div><div class="cat-count">120+ Courses</div></div>
    <div class="cat-card reveal" style="--cat-color:#ff5c8a"><span class="cat-icon">📊</span><div class="cat-name">Data Science</div><div class="cat-count">180+ Courses</div></div>
    <div class="cat-card reveal" style="--cat-color:#f7c948"><span class="cat-icon">🤖</span><div class="cat-name">Artificial Intelligence</div><div class="cat-count">95+ Courses</div></div>
    <div class="cat-card reveal" style="--cat-color:#a78bfa"><span class="cat-icon">📱</span><div class="cat-name">Mobile Dev</div><div class="cat-count">88+ Courses</div></div>
    <div class="cat-card reveal" style="--cat-color:#fb923c"><span class="cat-icon">☁️</span><div class="cat-name">Cloud & DevOps</div><div class="cat-count">110+ Courses</div></div>
    <div class="cat-card reveal" style="--cat-color:#34d399"><span class="cat-icon">🔐</span><div class="cat-name">Cybersecurity</div><div class="cat-count">75+ Courses</div></div>
    <div class="cat-card reveal" style="--cat-color:#60a5fa"><span class="cat-icon">🎮</span><div class="cat-name">Game Development</div><div class="cat-count">60+ Courses</div></div>
  </div>
</section>

<!-- COURSES -->
<section class="courses" id="courses">
  <div class="courses-header reveal">
    <div>
      <div class="section-label">Top Picks</div>
      <h2 class="section-title">Featured <em>Courses</em></h2>
    </div>
    <div class="filter-tabs" id="filterTabs">
      <button class="tab active" data-filter="all">All</button>
      <button class="tab" data-filter="dev">Development</button>
      <button class="tab" data-filter="design">Design</button>
      <button class="tab" data-filter="data">Data & AI</button>
      <button class="tab" data-filter="business">Business</button>
    </div>
  </div>
  <div class="courses-grid" id="coursesGrid">
    <!-- Rendered by JS -->
  </div>
</section>

<!-- FEATURES -->
<section class="features" id="features">
  <div class="features-grid">
    <div class="feature-visual">
      <div class="fv-card fv-main">
        <div class="big-icon">🚀</div>
        <div style="font-family:'Syne',sans-serif;font-size:1.2rem;font-weight:700;text-align:center">Your Learning Dashboard</div>
        <div style="width:80%;background:rgba(255,255,255,0.05);border-radius:12px;padding:12px 16px">
          <div style="font-size:0.75rem;color:var(--muted);margin-bottom:8px">Weekly Goal</div>
          <div class="progress-bar"><div class="progress-fill" style="--fill:74%"></div></div>
          <div style="font-size:0.75rem;color:var(--accent2);margin-top:6px">74% Complete — Keep Going! 🔥</div>
        </div>
      </div>
      <div class="fv-card fv-overlay1">
        <div class="fv-label">🏆 Achievement</div>
        <div class="fv-value">Top 5% Learner</div>
        <div style="display:flex;gap:4px;margin-top:8px">⭐⭐⭐⭐⭐</div>
      </div>
      <div class="fv-card fv-overlay2">
        <div class="fv-label">⚡ Streak</div>
        <div class="fv-value">42 Days</div>
        <div style="font-size:0.75rem;color:var(--muted);margin-top:4px">Personal best!</div>
      </div>
    </div>
    <div>
      <div class="section-label reveal">Why EduVerse?</div>
      <h2 class="section-title reveal">Built For <em>Real</em> Learners</h2>
      <p class="reveal" style="color:var(--muted);margin:16px 0 36px;line-height:1.7;font-size:0.95rem">We combine expert instruction, hands-on projects, and AI guidance to accelerate your growth from beginner to professional.</p>
      <div class="features-list">
        <div class="feat-item" style="--feat-bg:rgba(79,142,255,0.12);--feat-border:rgba(79,142,255,0.2)">
          <div class="feat-icon">🎯</div>
          <div class="feat-text">
            <h4>Personalized AI Learning Paths</h4>
            <p>Our AI analyzes your goals, skill level, and learning style to create a custom curriculum just for you.</p>
          </div>
        </div>
        <div class="feat-item" style="--feat-bg:rgba(0,229,192,0.1);--feat-border:rgba(0,229,192,0.2)">
          <div class="feat-icon">🛠️</div>
          <div class="feat-text">
            <h4>Hands-On Real Projects</h4>
            <p>Build a portfolio of actual projects as you learn. Employers notice people who ship real work.</p>
          </div>
        </div>
        <div class="feat-item" style="--feat-bg:rgba(255,92,138,0.1);--feat-border:rgba(255,92,138,0.2)">
          <div class="feat-icon">🌐</div>
          <div class="feat-text">
            <h4>Live Mentorship Sessions</h4>
            <p>Get live 1-on-1 sessions with industry mentors who have worked at top tech companies.</p>
          </div>
        </div>
        <div class="feat-item" style="--feat-bg:rgba(247,201,72,0.1);--feat-border:rgba(247,201,72,0.2)">
          <div class="feat-icon">📜</div>
          <div class="feat-text">
            <h4>Verified Certificates</h4>
            <p>Earn blockchain-verified certificates that employers can instantly validate online.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- TESTIMONIALS -->
<section class="testimonials" id="testimonials">
  <div class="testi-header reveal">
    <div class="section-label">Student Stories</div>
    <h2 class="section-title">Real People, <em>Real Results</em></h2>
  </div>
  <div class="testi-grid" id="testiGrid"></div>
</section>

<!-- PRICING -->
<section class="pricing" id="pricing">
  <div class="pricing-header reveal">
    <div class="section-label">Simple Pricing</div>
    <h2 class="section-title">Choose Your <em>Plan</em></h2>
    <p style="color:var(--muted);margin-top:14px;font-size:0.95rem">No hidden fees. Cancel anytime.</p>
  </div>
  <div class="pricing-grid">
    <div class="price-card reveal">
      <div class="price-plan">Starter</div>
      <div class="price-amount">Free <span>/ forever</span></div>
      <div class="price-desc">Perfect for exploring and getting started with your learning journey.</div>
      <ul class="price-features">
        <li><span class="check">✓</span> 20 Free Courses</li>
        <li><span class="check">✓</span> Community Access</li>
        <li><span class="check">✓</span> Mobile App</li>
        <li class="inactive"><span class="cross">✕</span> Certificates</li>
        <li class="inactive"><span class="cross">✕</span> Mentorship</li>
      </ul>
      <button class="price-btn price-btn-outline">Get Started Free</button>
    </div>
    <div class="price-card popular reveal">
      <div class="popular-badge">Most Popular</div>
      <div class="price-plan">Pro</div>
      <div class="price-amount">₹999 <span>/ month</span></div>
      <div class="price-desc">Full access for serious learners who want to level up fast.</div>
      <ul class="price-features">
        <li><span class="check">✓</span> All 1,200+ Courses</li>
        <li><span class="check">✓</span> Verified Certificates</li>
        <li><span class="check">✓</span> 2 Mentorship Sessions/mo</li>
        <li><span class="check">✓</span> AI Learning Path</li>
        <li class="inactive"><span class="cross">✕</span> Priority Support</li>
      </ul>
      <button class="price-btn price-btn-filled">Start Pro — ₹999/mo</button>
    </div>
    <div class="price-card reveal">
      <div class="price-plan">Team</div>
      <div class="price-amount">₹2,499 <span>/ month</span></div>
      <div class="price-desc">For teams and organizations who want to upskill together.</div>
      <ul class="price-features">
        <li><span class="check">✓</span> Everything in Pro</li>
        <li><span class="check">✓</span> Up to 20 Seats</li>
        <li><span class="check">✓</span> Team Analytics</li>
        <li><span class="check">✓</span> Unlimited Mentorship</li>
        <li><span class="check">✓</span> Priority Support</li>
      </ul>
      <button class="price-btn price-btn-outline">Contact Sales</button>
    </div>
  </div>
</section>

<!-- CTA BANNER -->
<section class="cta-banner">
  <div class="orb orb1" style="opacity:0.5"></div>
  <h2 class="reveal">Ready to Start Your <span style="color:var(--accent2)">Learning Journey?</span></h2>
  <p class="reveal">Join 2.4 million learners who are already building the future.</p>
  <div class="hero-buttons reveal" style="justify-content:center;opacity:1;animation:none">
    <a href="#" class="btn-primary">Join for Free Today ✦</a>
    <a href="#courses" class="btn-ghost">Browse Courses →</a>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-grid">
    <div class="footer-brand">
      <div class="nav-logo" style="font-size:1.6rem">Edu<span>Verse</span></div>
      <p>Empowering millions of learners worldwide with expert-led, AI-powered online education that actually gets results.</p>
    </div>
    <div class="footer-col">
      <h5>Courses</h5>
      <ul>
        <li><a href="#">Web Development</a></li>
        <li><a href="#">UI/UX Design</a></li>
        <li><a href="#">Data Science</a></li>
        <li><a href="#">Cybersecurity</a></li>
      </ul>
    </div>
    <div class="footer-col">
      <h5>Company</h5>
      <ul>
        <li><a href="#">About Us</a></li>
        <li><a href="#">Careers</a></li>
        <li><a href="#">Blog</a></li>
        <li><a href="#">Press</a></li>
      </ul>
    </div>
    <div class="footer-col">
      <h5>Support</h5>
      <ul>
        <li><a href="#">Help Center</a></li>
        <li><a href="#">Community</a></li>
        <li><a href="#">Contact</a></li>
        <li><a href="#">Privacy</a></li>
      </ul>
    </div>
  </div>
  <div class="footer-bottom">
    <span>© 2026 EduVerse. All rights reserved.</span>
    <span>Made with ❤️ for lifelong learners</span>
  </div>
</footer>

<!-- AUTH MODAL -->
<div id="auth-overlay" onclick="handleOverlayClick(event)">
  <div class="auth-modal" id="authModal">
    <button class="auth-close" onclick="closeAuth()">✕</button>

    <div class="auth-tabs">
      <button class="auth-tab active" id="tab-login" onclick="switchTab('login')">Sign In</button>
      <button class="auth-tab" id="tab-signup" onclick="switchTab('signup')">Create Account</button>
    </div>

    <div class="auth-panels">

      <!-- LOGIN PANEL -->
      <div class="auth-panel active" id="panel-login">
        <div class="auth-logo">Edu<span>Verse</span></div>
        <div class="auth-heading">Welcome back 👋</div>
        <div class="auth-sub">Sign in to continue your learning journey.</div>

        <div class="social-btns">
          <button class="social-btn" onclick="socialLogin('Google')"><span class="social-icon">🌐</span> Google</button>
          <button class="social-btn" onclick="socialLogin('GitHub')"><span class="social-icon">🐙</span> GitHub</button>
        </div>
        <div class="auth-divider">or continue with email</div>

        <div id="login-form">
          <div class="auth-field">
            <label>Email Address</label>
            <div class="field-wrap">
              <input class="auth-input" type="email" id="login-email" placeholder="you@example.com" oninput="clearError(this)">
              <span class="field-icon">✉️</span>
            </div>
            <div class="field-error" id="login-email-err">Please enter a valid email.</div>
          </div>
          <div class="auth-field">
            <label>Password</label>
            <div class="field-wrap">
              <input class="auth-input" type="password" id="login-pwd" placeholder="••••••••" oninput="clearError(this)">
              <span class="field-icon">🔒</span>
              <button class="pwd-toggle" onclick="togglePwd('login-pwd', this)" type="button">👁</button>
            </div>
            <div class="field-error" id="login-pwd-err">Password is required.</div>
          </div>
          <div class="auth-row">
            <label class="auth-check">
              <input type="checkbox" id="rememberMe">
              <label for="rememberMe">Remember me</label>
            </label>
            <a href="#" class="auth-forgot">Forgot password?</a>
          </div>
          <button class="auth-submit" id="login-btn" onclick="handleLogin()">Sign In to EduVerse</button>
          <div class="auth-success" id="login-success">
            <span class="success-icon">🎉</span>
            <h3>Welcome Back!</h3>
            <p>Redirecting to your dashboard...</p>
          </div>
        </div>

        <div class="auth-switch">Don't have an account? <a onclick="switchTab('signup')">Sign up free →</a></div>
      </div>

      <!-- SIGNUP PANEL -->
      <div class="auth-panel" id="panel-signup">
        <div class="auth-logo">Edu<span>Verse</span></div>
        <div class="auth-heading">Start learning today ✦</div>
        <div class="auth-sub">Join 2.4M+ learners. Free forever, upgrade anytime.</div>

        <div class="social-btns">
          <button class="social-btn" onclick="socialLogin('Google')"><span class="social-icon">🌐</span> Google</button>
          <button class="social-btn" onclick="socialLogin('GitHub')"><span class="social-icon">🐙</span> GitHub</button>
        </div>
        <div class="auth-divider">or fill in the form</div>

        <div id="signup-form">
          <div class="auth-field">
            <label>Full Name</label>
            <div class="field-wrap">
              <input class="auth-input" type="text" id="signup-name" placeholder="Priya Sharma" oninput="clearError(this)">
              <span class="field-icon">👤</span>
            </div>
            <div class="field-error" id="signup-name-err">Please enter your name.</div>
          </div>
          <div class="auth-field">
            <label>Email Address</label>
            <div class="field-wrap">
              <input class="auth-input" type="email" id="signup-email" placeholder="you@example.com" oninput="clearError(this)">
              <span class="field-icon">✉️</span>
            </div>
            <div class="field-error" id="signup-email-err">Please enter a valid email.</div>
          </div>
          <div class="auth-field">
            <label>Password</label>
            <div class="field-wrap">
              <input class="auth-input" type="password" id="signup-pwd" placeholder="Min. 8 characters" oninput="updateStrength(this)" onchange="clearError(this)">
              <span class="field-icon">🔒</span>
              <button class="pwd-toggle" onclick="togglePwd('signup-pwd', this)" type="button">👁</button>
            </div>
            <div class="strength-bar"><div class="strength-fill" id="strength-fill"></div></div>
            <div class="strength-label" id="strength-label">Enter a password</div>
            <div class="field-error" id="signup-pwd-err">Password must be at least 8 characters.</div>
          </div>
          <button class="auth-submit" id="signup-btn" onclick="handleSignup()" style="margin-top:8px">Create Free Account</button>
          <div class="auth-success" id="signup-success">
            <span class="success-icon">🚀</span>
            <h3>You're In!</h3>
            <p>Check your email to verify your account.</p>
          </div>
        </div>

        <div class="auth-terms">By signing up, you agree to our <a href="#">Terms of Service</a> & <a href="#">Privacy Policy</a>.</div>
        <div class="auth-switch">Already have an account? <a onclick="switchTab('login')">Sign in →</a></div>
      </div>

    </div>
  </div>
</div>

<script>
// ─── STARS CANVAS ───────────────────────────────────────────────────
const canvas = document.getElementById('stars-canvas');
const ctx = canvas.getContext('2d');
let stars = [];

function resizeCanvas() {
  canvas.width = window.innerWidth;
  canvas.height = window.innerHeight;
}

function initStars() {
  stars = [];
  for (let i = 0; i < 200; i++) {
    stars.push({
      x: Math.random() * canvas.width,
      y: Math.random() * canvas.height,
      r: Math.random() * 1.5 + 0.3,
      alpha: Math.random() * 0.7 + 0.1,
      speed: Math.random() * 0.3 + 0.05,
      twinkle: Math.random() * Math.PI * 2
    });
  }
}

function drawStars() {
  ctx.clearRect(0, 0, canvas.width, canvas.height);
  stars.forEach(s => {
    s.twinkle += 0.02;
    const alpha = s.alpha * (0.6 + 0.4 * Math.sin(s.twinkle));
    ctx.beginPath();
    ctx.arc(s.x, s.y, s.r, 0, Math.PI * 2);
    ctx.fillStyle = `rgba(160,200,255,${alpha})`;
    ctx.fill();
  });
  requestAnimationFrame(drawStars);
}

resizeCanvas(); initStars(); drawStars();
window.addEventListener('resize', () => { resizeCanvas(); initStars(); });

// ─── CUSTOM CURSOR ───────────────────────────────────────────────────
const cursor = document.getElementById('cursor');
const ring = document.getElementById('cursor-ring');
let mx = 0, my = 0, rx = 0, ry = 0;

document.addEventListener('mousemove', e => { mx = e.clientX; my = e.clientY; });

function animateCursor() {
  cursor.style.transform = `translate(${mx - 6}px, ${my - 6}px)`;
  rx += (mx - rx - 20) * 0.12;
  ry += (my - ry - 20) * 0.12;
  ring.style.transform = `translate(${rx}px, ${ry}px)`;
  requestAnimationFrame(animateCursor);
}
animateCursor();

document.addEventListener('mousedown', () => {
  cursor.style.transform += ' scale(0.7)';
  ring.style.borderColor = 'var(--accent2)';
});
document.addEventListener('mouseup', () => {
  ring.style.borderColor = 'rgba(79,142,255,0.5)';
});

// ─── NAVBAR SCROLL ───────────────────────────────────────────────────
window.addEventListener('scroll', () => {
  document.getElementById('navbar').classList.toggle('scrolled', scrollY > 40);
});

// ─── SCROLL REVEAL ───────────────────────────────────────────────────
const observer = new IntersectionObserver(entries => {
  entries.forEach(e => {
    if (e.isIntersecting) {
      e.target.classList.add('visible');
      if (e.target.classList.contains('feat-item')) {
        const delay = [...e.target.parentElement.children].indexOf(e.target) * 120;
        e.target.style.transitionDelay = delay + 'ms';
      }
    }
  });
}, { threshold: 0.12 });

document.querySelectorAll('.reveal, .feat-item').forEach(el => observer.observe(el));

// ─── COURSES DATA ───────────────────────────────────────────────────
const courses = [
  { title: "Complete Web Development Bootcamp", cat: "Web Dev", catFilter: "dev", desc: "From HTML to full-stack React apps. Build 15+ real projects.", icon: "💻", thumbBg: "linear-gradient(135deg,#0f2044,#1a4080)", badge: "Bestseller", badgeBg: "#f7c948", badgeColor: "#04060f", price: "₹1,299", original: "₹4,999", rating: "4.9", reviews: "12.4k", duration: "62h", level: "Beginner" },
  { title: "UI/UX Design: Zero to Pro", cat: "Design", catFilter: "design", desc: "Figma, design systems, and user research for modern products.", icon: "🎨", thumbBg: "linear-gradient(135deg,#1a0828,#3d1060)", badge: "New", badgeBg: "#ff5c8a", badgeColor: "white", price: "₹999", original: "₹3,499", rating: "4.8", reviews: "8.2k", duration: "38h", level: "All Levels" },
  { title: "Python for Data Science & AI", cat: "Data & AI", catFilter: "data", desc: "Pandas, NumPy, ML models, and deep learning with TensorFlow.", icon: "🤖", thumbBg: "linear-gradient(135deg,#001a1a,#006060)", badge: "Top Rated", badgeBg: "#00e5c0", badgeColor: "#04060f", price: "₹1,499", original: "₹5,999", rating: "4.9", reviews: "21k", duration: "78h", level: "Intermediate" },
  { title: "React + Next.js Mastery", cat: "Web Dev", catFilter: "dev", desc: "Build production-grade React apps with Next.js 14 & TypeScript.", icon: "⚛️", thumbBg: "linear-gradient(135deg,#061230,#0e2d6e)", badge: "Trending", badgeBg: "#4f8eff", badgeColor: "white", price: "₹1,199", original: "₹4,499", rating: "4.8", reviews: "6.1k", duration: "45h", level: "Intermediate" },
  { title: "Digital Marketing Masterclass", cat: "Business", catFilter: "business", desc: "SEO, ads, email, social media & analytics all in one course.", icon: "📈", thumbBg: "linear-gradient(135deg,#1a0a00,#7a3800)", badge: "Popular", badgeBg: "#fb923c", badgeColor: "white", price: "₹799", original: "₹2,999", rating: "4.7", reviews: "9.8k", duration: "30h", level: "Beginner" },
  { title: "Ethical Hacking & Cybersecurity", cat: "Security", catFilter: "dev", desc: "Penetration testing, network security & CEH exam prep.", icon: "🔐", thumbBg: "linear-gradient(135deg,#001408,#006030)", badge: "Advanced", badgeBg: "#34d399", badgeColor: "#04060f", price: "₹1,699", original: "₹6,499", rating: "4.8", reviews: "5.4k", duration: "55h", level: "Advanced" },
];

function renderCourses(filter = 'all') {
  const grid = document.getElementById('coursesGrid');
  const filtered = filter === 'all' ? courses : courses.filter(c => c.catFilter === filter);
  grid.innerHTML = '';
  filtered.forEach((c, i) => {
    const card = document.createElement('div');
    card.className = 'course-card reveal';
    card.style.transitionDelay = (i * 80) + 'ms';
    card.innerHTML = `
      <div class="course-thumb" style="--thumb-bg:${c.thumbBg}">
        <div class="course-thumb-bg"></div>
        <span style="position:relative;z-index:1;font-size:3.5rem">${c.icon}</span>
        <div class="course-badge" style="background:${c.badgeBg};color:${c.badgeColor}">${c.badge}</div>
      </div>
      <div class="course-body">
        <div class="course-cat">${c.cat}</div>
        <div class="course-title">${c.title}</div>
        <div class="course-desc">${c.desc}</div>
        <div class="course-meta">
          <span class="meta-item"><span class="meta-icon">⏱</span>${c.duration}</span>
          <span class="meta-item"><span class="meta-icon">📶</span>${c.level}</span>
          <span class="stars">★★★★★</span><span class="rating-num">${c.rating} (${c.reviews})</span>
        </div>
        <div class="course-footer">
          <div class="course-price">${c.price}<span class="original">${c.original}</span></div>
          <button class="enroll-btn" onclick="enrollCourse(this)">Enroll Now</button>
        </div>
      </div>`;
    grid.appendChild(card);
    setTimeout(() => observer.observe(card), 50);
  });
}

renderCourses();

document.getElementById('filterTabs').addEventListener('click', e => {
  if (!e.target.classList.contains('tab')) return;
  document.querySelectorAll('.tab').forEach(t => t.classList.remove('active'));
  e.target.classList.add('active');
  renderCourses(e.target.dataset.filter);
});

function enrollCourse(btn) {
  btn.textContent = '✓ Added!';
  btn.style.background = 'var(--accent2)';
  btn.style.color = '#04060f';
  setTimeout(() => { btn.textContent = 'Enroll Now'; btn.style.background = ''; btn.style.color = ''; }, 2000);
}

// ─── TESTIMONIALS ────────────────────────────────────────────────────
const testimonials = [
  { text: "EduVerse completely changed my career. I went from zero coding knowledge to landing a job at a startup in just 8 months. The projects and mentorship made all the difference.", name: "Priya Sharma", role: "Junior Frontend Dev @ TechCorp", av: "PS", avBg: "linear-gradient(135deg,#4f8eff,#2d60cc)", avColor: "white" },
  { text: "The AI-powered learning path is genuinely magical. It knew what I needed before I did. I cleared my AWS certification on the first attempt thanks to EduVerse.", name: "Arjun Patel", role: "Cloud Engineer @ Infosys", av: "AP", avBg: "linear-gradient(135deg,#00e5c0,#009980)", avColor: "#04060f" },
  { text: "As a designer, I was skeptical about online courses. But the UI/UX program here is world-class — real projects, great feedback, and a community that actually helps.", name: "Meera Nair", role: "Product Designer @ Razorpay", av: "MN", avBg: "linear-gradient(135deg,#ff5c8a,#cc2255)", avColor: "white" },
  { text: "The data science curriculum is incredibly comprehensive. I use what I learned every single day at work. Best investment I've made in my education by far.", name: "Rohan Mehta", role: "Data Analyst @ Flipkart", av: "RM", avBg: "linear-gradient(135deg,#f7c948,#c49a00)", avColor: "#04060f" },
  { text: "I enrolled in the cybersecurity course with zero experience. Now I'm a certified ethical hacker and working in a security firm. The course content is unmatched.", name: "Kavya Reddy", role: "Security Analyst @ Wipro", av: "KR", avBg: "linear-gradient(135deg,#a78bfa,#6d4fc0)", avColor: "white" },
  { text: "Learning React and Next.js here prepared me better than my computer science degree. Practical, current, and incredibly well-structured content.", name: "Vivek Kumar", role: "Full Stack Dev @ Zomato", av: "VK", avBg: "linear-gradient(135deg,#fb923c,#c45000)", avColor: "white" },
];

const tg = document.getElementById('testiGrid');
testimonials.forEach((t, i) => {
  const card = document.createElement('div');
  card.className = 'testi-card reveal';
  card.style.transitionDelay = (i * 80) + 'ms';
  card.innerHTML = `
    <div class="testi-quote">"</div>
    <div class="testi-text">${t.text}</div>
    <div class="testi-author">
      <div class="testi-avatar" style="background:${t.avBg};color:${t.avColor}">${t.av}</div>
      <div><div class="testi-name">${t.name}</div><div class="testi-role">${t.role}</div></div>
    </div>`;
  tg.appendChild(card);
  setTimeout(() => observer.observe(card), 50);
});

// ─── SEARCH ──────────────────────────────────────────────────────────
function handleSearch() {
  const q = document.getElementById('searchInput').value.trim();
  if (!q) return;
  document.getElementById('courses').scrollIntoView({ behavior: 'smooth' });
  const filtered = courses.filter(c => c.title.toLowerCase().includes(q.toLowerCase()) || c.cat.toLowerCase().includes(q.toLowerCase()) || c.desc.toLowerCase().includes(q.toLowerCase()));
  const grid = document.getElementById('coursesGrid');
  if (filtered.length === 0) {
    grid.innerHTML = `<div style="grid-column:1/-1;text-align:center;padding:60px;color:var(--muted)">
      <div style="font-size:3rem;margin-bottom:16px">🔍</div>
      <div style="font-family:'Syne',sans-serif;font-size:1.3rem;margin-bottom:8px">No courses found for "${q}"</div>
      <div>Try a different keyword</div>
    </div>`;
  } else {
    renderCourses('all');
  }
}

document.getElementById('searchInput').addEventListener('keydown', e => {
  if (e.key === 'Enter') handleSearch();
});

// ─── COUNTER ANIMATION ────────────────────────────────────────────────
function animateCounter(el) {
  const short = el.dataset.short;
  el.textContent = short;
}

const statObserver = new IntersectionObserver(entries => {
  entries.forEach(e => {
    if (e.isIntersecting) {
      animateCounter(e.target);
      statObserver.unobserve(e.target);
    }
  });
}, { threshold: 0.5 });

document.querySelectorAll('.count-up').forEach(el => statObserver.observe(el));

// ─── PARALLAX ORBS ────────────────────────────────────────────────────
document.addEventListener('mousemove', e => {
  const x = (e.clientX / window.innerWidth - 0.5) * 20;
  const y = (e.clientY / window.innerHeight - 0.5) * 20;
  document.querySelectorAll('.orb').forEach((orb, i) => {
    const factor = (i + 1) * 0.5;
    orb.style.transform = `translate(${x * factor}px, ${y * factor}px)`;
  });
});// ─── AUTH MODAL ───────────────────────────────────────────────────────
function openAuth(tab = 'login') {
  document.getElementById('auth-overlay').classList.add('open');
  document.body.style.overflow = 'hidden';
  switchTab(tab);
}

function closeAuth() {
  document.getElementById('auth-overlay').classList.remove('open');
  document.body.style.overflow = '';
}

function handleOverlayClick(e) {
  if (e.target === document.getElementById('auth-overlay')) closeAuth();
}

document.addEventListener('keydown', e => { if (e.key === 'Escape') closeAuth(); });

let currentTab = 'login';
function switchTab(tab) {
  const oldPanel = document.getElementById('panel-' + currentTab);
  const newPanel = document.getElementById('panel-' + tab);
  const oldTab = document.getElementById('tab-' + currentTab);
  const newTabEl = document.getElementById('tab-' + tab);

  oldPanel.classList.remove('active');
  oldPanel.classList.add('slide-left');
  setTimeout(() => oldPanel.classList.remove('slide-left'), 350);

  newPanel.classList.add('active');
  oldTab.classList.remove('active');
  newTabEl.classList.add('active');
  currentTab = tab;
}

function togglePwd(id, btn) {
  const input = document.getElementById(id);
  if (input.type === 'password') { input.type = 'text'; btn.textContent = '🙈'; }
  else { input.type = 'password'; btn.textContent = '👁'; }
}

function clearError(input) {
  input.classList.remove('error');
  const errEl = document.getElementById(input.id + '-err');
  if (errEl) errEl.classList.remove('show');
}

function showError(id, msg) {
  const input = document.getElementById(id);
  const err = document.getElementById(id + '-err');
  input.classList.add('error');
  if (err) { err.textContent = msg; err.classList.add('show'); }
  input.closest('.auth-panel') && input.closest('.auth-panel').querySelector('.auth-modal') 
    && input.closest('.auth-modal').classList.add('shake');
  document.getElementById('authModal').classList.add('shake');
  setTimeout(() => document.getElementById('authModal').classList.remove('shake'), 400);
}

function updateStrength(input) {
  const val = input.value;
  const fill = document.getElementById('strength-fill');
  const label = document.getElementById('strength-label');
  let score = 0;
  if (val.length >= 8) score++;
  if (/[A-Z]/.test(val)) score++;
  if (/[0-9]/.test(val)) score++;
  if (/[^A-Za-z0-9]/.test(val)) score++;
  const levels = [
    { w: '0%', bg: 'transparent', txt: 'Enter a password' },
    { w: '25%', bg: '#ff5c8a', txt: 'Weak' },
    { w: '50%', bg: '#f7c948', txt: 'Fair' },
    { w: '75%', bg: '#4f8eff', txt: 'Good' },
    { w: '100%', bg: '#00e5c0', txt: '💪 Strong!' },
  ];
  const l = levels[Math.min(score, 4)];
  fill.style.width = l.w;
  fill.style.background = l.bg;
  label.textContent = l.txt;
  label.style.color = l.bg || 'var(--muted)';
}

function handleLogin() {
  const email = document.getElementById('login-email').value.trim();
  const pwd = document.getElementById('login-pwd').value;
  let valid = true;
  if (!email || !/\S+@\S+\.\S+/.test(email)) { showError('login-email', 'Enter a valid email address.'); valid = false; }
  if (!pwd) { showError('login-pwd', 'Password is required.'); valid = false; }
  if (!valid) return;

  const btn = document.getElementById('login-btn');
  btn.classList.add('loading');
  btn.textContent = 'Signing in...';

  setTimeout(() => {
    btn.classList.remove('loading');
    document.getElementById('login-form').style.display = 'none';
    const suc = document.getElementById('login-success');
    suc.style.display = 'block';
    suc.style.animation = 'fadeUp 0.5s ease';
    setTimeout(closeAuth, 2200);
    setTimeout(() => {
      document.getElementById('login-form').style.display = '';
      suc.style.display = 'none';
      btn.textContent = 'Sign In to EduVerse';
    }, 2800);
  }, 1800);
}

function handleSignup() {
  const name = document.getElementById('signup-name').value.trim();
  const email = document.getElementById('signup-email').value.trim();
  const pwd = document.getElementById('signup-pwd').value;
  let valid = true;
  if (!name) { showError('signup-name', 'Please enter your full name.'); valid = false; }
  if (!email || !/\S+@\S+\.\S+/.test(email)) { showError('signup-email', 'Enter a valid email address.'); valid = false; }
  if (!pwd || pwd.length < 8) { showError('signup-pwd', 'Password must be at least 8 characters.'); valid = false; }
  if (!valid) return;

  const btn = document.getElementById('signup-btn');
  btn.classList.add('loading');
  btn.textContent = 'Creating account...';

  setTimeout(() => {
    btn.classList.remove('loading');
    document.getElementById('signup-form').style.display = 'none';
    const suc = document.getElementById('signup-success');
    suc.style.display = 'block';
    suc.style.animation = 'fadeUp 0.5s ease';
    setTimeout(closeAuth, 2500);
    setTimeout(() => {
      document.getElementById('signup-form').style.display = '';
      suc.style.display = 'none';
      btn.textContent = 'Create Free Account';
    }, 3000);
  }, 2000);
}

function socialLogin(provider) {
  const btn = event.target.closest('.social-btn');
  const original = btn.innerHTML;
  btn.innerHTML = `<span style="display:inline-block;width:14px;height:14px;border:2px solid var(--muted);border-top-color:var(--text);border-radius:50%;animation:spin 0.7s linear infinite"></span> Connecting...`;
  btn.style.pointerEvents = 'none';
  setTimeout(() => {
    btn.innerHTML = `✓ Connected!`;
    btn.style.color = 'var(--accent2)';
    btn.style.borderColor = 'var(--accent2)';
    setTimeout(() => { btn.innerHTML = original; btn.style.color = ''; btn.style.borderColor = ''; btn.style.pointerEvents = ''; }, 1800);
  }, 1400);
}
</script>
</body>
</html>
