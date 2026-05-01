
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Ariel Gino Gallon | Portfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #0f172a;
      color: #fff;
    }

    header {
      text-align: center;
      padding: 80px 20px;
      background: linear-gradient(135deg, #1e293b, #020617);
    }

    header h1 {
      font-size: 40px;
      margin-bottom: 10px;
    }

    header p {
      color: #94a3b8;
      margin-bottom: 25px;
    }

    .buttons {
      display: flex;
      justify-content: center;
      gap: 15px;
      flex-wrap: wrap;
    }

    .btn {
      padding: 12px 25px;
      background: #22c55e;
      color: #000;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
      transition: 0.3s;
    }

    .btn:hover {
      background: #16a34a;
      transform: translateY(-2px);
    }

    .hero-img {
      width: 100%;
      height: 250px;
      object-fit: cover;
      border-bottom: 3px solid #22c55e;
    }

    .container {
      padding: 30px;
      max-width: 1000px;
      margin: auto;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
    }

    .card {
      background: #1e293b;
      padding: 20px;
      border-radius: 12px;
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    h2 {
      margin-bottom: 10px;
      color: #22c55e;
    }

    .skills span {
      display: inline-block;
      background: #22c55e;
      color: #000;
      padding: 6px 10px;
      margin: 5px;
      border-radius: 20px;
      font-size: 13px;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #020617;
      color: #94a3b8;
      margin-top: 40px;
    }
  </style>
</head>

<body>

<!-- HERO IMAGE -->
<img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f" class="hero-img" alt="Professional Banner">

<header>
  <h1>ARIEL GINO D. GALLON</h1>
  <p>Information Systems Graduate | IT & Operations Professional</p>

  <div class="buttons">
    <a href="mailto:Ginobarreda111@gmail.com" class="btn">Email Me</a>
    <a href="resume.pdf" download class="btn">Download Resume</a>
    <a href="https://www.facebook.com/arielgino.gallon.5/" target="_blank" class="btn">Facebook</a>
  </div>
</header>

<div class="container">

  <div class="grid">

    <div class="card">
      <h2>About Me</h2>
      <p>
        A motivated and dependable graduate eager to begin a professional career. Strong in adaptability,
        organization, and continuous learning across IT, administration, and customer service.
      </p>
    </div>

    <div class="card">
      <h2>Experience</h2>
      <p><strong>Head Technician (2026–Present)</strong></p>
      <p>Leads team operations, logistics, and inventory systems.</p>
      <p><strong>DICT Intern (2025)</strong></p>
      <p>System testing, documentation, and client coordination.</p>
    </div>

    <div class="card">
      <h2>Education</h2>
      <p>BS Information Systems (2021–2025)</p>
      <p>CCDI Sorsogon</p>
    </div>

    <div class="card">
      <h2>Skills</h2>
      <div class="skills">
        <span>C#</span><span>Python</span><span>SQL</span><span>Java</span>
        <span>Figma</span><span>Canva</span><span>Excel</span>
        <span>Customer Service</span>
      </div>
    </div>

    <div class="card">
      <h2>Languages</h2>
      <p>English | Tagalog | Bicol</p>
    </div>

    <div class="card">
      <h2>Contact</h2>
      <p>Email: Ginobarreda111@gmail.com</p>
    </div>

  </div>

</div>

<footer>
  © 2026 Ariel Gino Gallon | Portfolio
</footer>

</body>
</html>
