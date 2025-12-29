# Portfolio-site

<!DOCTYPE html>
<html lang="uz">
<head>
  <meta charset="UTF-8">
  <title>Full-Stack Developer | Portfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <!-- Bootstrap -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

  <!-- AOS Animation -->
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

  <style>
    body {
      scroll-behavior: smooth;
    }
    .hero {
      height: 100vh;
      background: linear-gradient(120deg, #0f2027, #203a43, #2c5364);
      color: white;
    }
    .badge-skill {
      font-size: 1rem;
      margin: 5px;
    }
  </style>
</head>
<body>

<!-- NAVBAR -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
  <div class="container">
    <a class="navbar-brand" href="#">Full-Stack Dev</a>
    <button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#menu">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div id="menu" class="collapse navbar-collapse">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
        <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
        <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- HERO -->
<section class="hero d-flex align-items-center text-center">
  <div class="container" data-aos="fade-up">
    <h1 class="display-4">Salom, men Full-Stack Dasturchiman 👋</h1>
    <p class="lead">Frontend + Backend + Database</p>
    <a href="#projects" class="btn btn-success btn-lg mt-3">Loyihalarim</a>
  </div>
</section>

<!-- ABOUT -->
<section id="about" class="py-5">
  <div class="container" data-aos="fade-right">
    <h2>Men haqimda</h2>
    <p>
      Men zamonaviy web-ilovalar yaratadigan full-stack dasturchiman.
      Frontend va backend bilan ishlayman, to‘liq loyiha qilish tajribam bor.
    </p>
  </div>
</section>

<!-- SKILLS -->
<section id="skills" class="py-5 bg-light">
  <div class="container" data-aos="zoom-in">
    <h2>Texnologiyalar</h2>

    <h5 class="mt-3">Frontend</h5>
    <span class="badge bg-primary badge-skill">HTML</span>
    <span class="badge bg-primary badge-skill">CSS</span>
    <span class="badge bg-primary badge-skill">Bootstrap</span>
    <span class="badge bg-primary badge-skill">JavaScript</span>
    <span class="badge bg-primary badge-skill">React</span>

    <h5 class="mt-4">Backend</h5>
    <span class="badge bg-success badge-skill">Node.js</span>
    <span class="badge bg-success badge-skill">Express</span>
    <span class="badge bg-success badge-skill">Python</span>
    <span class="badge bg-success badge-skill">Django</span>

    <h5 class="mt-4">Database</h5>
    <span class="badge bg-dark badge-skill">MongoDB</span>
    <span class="badge bg-dark badge-skill">MySQL</span>
  </div>
</section>

<!-- PROJECTS -->
<section id="projects" class="py-5">
  <div class="container" data-aos="fade-up">
    <h2>Loyihalar</h2>

    <div class="row">
      <div class="col-md-4">
        <div class="card mb-3">
          <div class="card-body">
            <h5>Online Shop</h5>
            <p>Full-stack e-commerce sayt</p>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card mb-3">
          <div class="card-body">
            <h5>Chat App</h5>
            <p>Real-time chat ilova</p>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card mb-3">
          <div class="card-body">
            <h5>Portfolio</h5>
            <p>Shaxsiy portfolio web-sayt</p>
          </div>
        </div>
      </div>
    </div>

  </div>
</section>

<!-- CONTACT -->
<section id="contact" class="py-5 bg-dark text-white">
  <div class="container text-center" data-aos="fade-up">
    <h2>Alo
