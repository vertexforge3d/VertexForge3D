<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Vertex Forge 3D Printing</title>
  <meta name="description" content="Vertex Forge 3D Printing – Local custom 3D printing for Junction City, Oregon and surrounding areas." />
  <style>
    :root {
      --bg: #05070a;
      --card: rgba(15, 20, 30, 0.9);
      --accent: #1fa2ff;
      --accent-soft: rgba(31, 162, 255, 0.25);
      --text: #f5f7fa;
      --muted: #b0b8c4;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      background: #05070a;
      color: var(--text);
      line-height: 1.6;
    }

    /* HERO WITH LOGO BACKGROUND */
    header {
      position: relative;
      padding: 120px 20px;
      text-align: center;
      overflow: hidden;
    }

    header::before {
      content: "";
      position: absolute;
      inset: 0;
      background: url("vertexforge-logo.png") center/600px no-repeat;
      opacity: 0.12;
      filter: drop-shadow(0 0 40px rgba(31,162,255,0.4));
      z-index: 0;
    }

    header::after {
      content: "";
      position: absolute;
      inset: 0;
      background: radial-gradient(circle at top, rgba(31,162,255,0.15), transparent 60%);
      z-index: 1;
    }

    header * {
      position: relative;
      z-index: 2;
    }

    header h1 {
      font-size: 3.2rem;
      letter-spacing: 2px;
      color: var(--accent);
    }

    header p {
      max-width: 760px;
      margin: 25px auto 0;
      color: var(--muted);
      font-size: 1.15rem;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 32px;
      padding: 18px;
      background: #070a10;
      border-bottom: 1px solid rgba(31,162,255,0.15);
      position: sticky;
      top: 0;
      z-index: 20;
    }

    nav a {
      color: var(--text);
      text-decoration: none;
      font-weight: bold;
      transition: color 0.2s ease;
    }

    nav a:hover {
      color: var(--accent);
    }

    section {
      padding: 90px 20px;
      max-width: 1150px;
      margin: auto;
    }

    .section-title {
      font-size: 2.4rem;
      margin-bottom: 20px;
      text-align: center;
      color: var(--accent);
    }

    .section-sub {
      text-align: center;
      color: var(--muted);
      max-width: 700px;
      margin: 0 auto 40px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 28px;
      margin-top: 40px;
    }

    .card {
      background: var(--card);
      padding: 32px;
      border-radius: 18px;
      border: 1px solid rgba(31,162,255,0.15);
      box-shadow: 0 15px 35px rgba(0,0,0,0.6);
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    .card:hover {
      transform: translateY(-6px);
      box-shadow: 0 25px 50px rgba(0,0,0,0.8);
    }

    .card h3 {
      margin-bottom: 12px;
      color: var(--accent);
    }

    .card p {
      color: var(--muted);
    }

    .highlight {
      background: linear-gradient(135deg, rgba(31,162,255,0.15), rgba(31,162,255,0.05));
      border: 1px solid rgba(31,162,255,0.25);
    }

    .cta {
      text-align: center;
      margin-top: 55px;
    }

    .cta a {
      display: inline-block;
      padding: 16px 40px;
      border-radius: 50px;
      background: var(--accent);
      color: #020409;
      font-weight: bold;
      text-decoration: none;
      letter-spacing: 0.5px;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    .cta a:hover {
      transform: translateY(-3px);
      box-shadow: 0 12px 30px rgba(31,162,255,0.5);
    }

    footer {
      background: #070a10;
      padding: 45px 20px;
      text-align: center;
      color: var(--muted);
      font-size: 0.9rem;
      border-top: 1px solid rgba(31,162,255,0.15);
    }

    footer strong {
      color: var(--text);
    }
  </style>
</head>
<body>

  <header>
    <h1>VERTEX FORGE 3D PRINTING</h1>
    <p>Local, precision-built 3D printing for Junction City, Oregon and surrounding areas. Functional parts, prototypes, toys, and custom designs — forged for real-world use.</p>
  </header>

  <nav>
    <a href="#services">Services</a>
    <a href="#local">Local Delivery</a>
    <a href="#process">Process</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="services">
    <h2 class="section-title">Our Services</h2>
    <p class="section-sub">High-quality custom 3D printing for practical, creative, and one-off needs.</p>
    <div class="grid">
      <div class="card">
        <h3>Custom 3D Printing</h3>
        <p>Made-to-order prints from your files or ideas. Strong, accurate, and clean results.</p>
      </div>
      <div class="card">
        <h3>Functional Parts & Prototypes</h3>
        <p>Replacement parts and prototypes designed to be used, tested, and trusted.</p>
      </div>
      <div class="card">
        <h3>Toys & Models</h3>
        <p>Figurines, models, and custom designs printed with sharp detail.</p>
      </div>
      <div class="card">
        <h3>Design Help</h3>
        <p>No model? No problem. We can help prep or refine designs for printing.</p>
      </div>
    </div>
  </section>

  <section id="local">
    <h2 class="section-title">Local Delivery Only</h2>
    <p class="section-sub">We focus on fast, reliable service for our local community.</p>
    <div class="grid">
      <div class="card highlight">
        <h3>Service Area</h3>
        <p>We currently offer local delivery and pickup only in <strong>Junction City, Oregon</strong> and surrounding areas.</p>
      </div>
      <div class="card">
        <h3>Why Local?</h3>
        <p>Local service means better communication, faster turnaround, and dependable quality.</p>
      </div>
    </div>
  </section>

  <section id="process">
    <h2 class="section-title">Our Process</h2>
    <div class="grid">
      <div class="card">
        <h3>1. Send Your Idea</h3>
        <p>Files, sketches, or descriptions — we’ll take it from there.</p>
      </div>
      <div class="card">
        <h3>2. Review & Quote</h3>
        <p>Material, strength, and pricing are reviewed before printing.</p>
      </div>
      <div class="card">
        <h3>3. Print & Deliver</h3>
        <p>Your print is inspected and delivered locally, ready to use.</p>
      </div>
    </div>

    <div class="cta">
      <a href="#contact">Request a Quote</a>
    </div>
  </section>

  <section id="contact">
    <h2 class="section-title">Request a Quote</h2>
    <div class="card" style="max-width: 700px; margin: auto;">
      <p style="text-align:center; margin-bottom:20px;">All services are <strong>local delivery or pickup only</strong> in Junction City, Oregon and surrounding areas.</p>
      <form action="mailto:vertexforge3dprints@gmail.com" method="post" enctype="text/plain">
        <label>Name<br />
          <input type="text" name="Name" required style="width:100%; padding:12px; margin:8px 0 16px; border-radius:8px; border:none;" />
        </label>
        <label>Email<br />
          <input type="email" name="Email" required style="width:100%; padding:12px; margin:8px 0 16px; border-radius:8px; border:none;" />
        </label>
        <label>Project Description<br />
          <textarea name="Project" rows="5" required style="width:100%; padding:12px; margin:8px 0 16px; border-radius:8px; border:none;"></textarea>
        </label>
        <label>Do you have a file? (STL/OBJ)<br />
          <input type="text" name="File" placeholder="Yes / No" style="width:100%; padding:12px; margin:8px 0 20px; border-radius:8px; border:none;" />
        </label>
        <div style="text-align:center;">
          <button type="submit" style="padding:14px 36px; border-radius:40px; background:var(--accent); color:#020409; font-weight:bold; border:none; cursor:pointer;">Submit Quote Request</button>
        </div>
      </form>
      <p style="margin-top:20px; text-align:center; color:var(--muted);">Or email us directly at <a href="mailto:vertexforge3dprints@gmail.com" style="color:var(--accent); text-decoration:none; font-weight:bold;">vertexforge3dprints@gmail.com</a></p>
    </div>
  </section>

  <footer>
    <p>© 2026 <strong>Vertex Forge 3D Printing</strong>. Local service only — Junction City, OR.</p>
  </footer>

</body>
</html>
