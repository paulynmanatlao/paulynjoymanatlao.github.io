<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Paulyn Joy Manatlao | Floral Portfolio</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Poppins:wght@300;500&display=swap" rel="stylesheet">

  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(to bottom, #fff1f7, #fdfcff);
      color: #4a4a4a;
      overflow-x: hidden;
    }

    /* Floral Background Overlay */
    body::before {
      content: '';
      position: fixed;
      inset: 0;
      background: url('https://i.ibb.co/5Fj5fYJ/floral-bg.png') repeat;
      opacity: 0.15;
      z-index: -1;
    }

    header {
      text-align: center;
      padding: 90px 20px 60px;
      background: rgba(255, 255, 255, 0.75);
      backdrop-filter: blur(6px);
      box-shadow: 0 10px 30px rgba(255, 182, 193, 0.3);
    }

    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 3rem;
      color: #c94f7c;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.1rem;
      color: #7a4a5a;
      letter-spacing: 1px;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 20px 0;
    }

    nav a {
      text-decoration: none;
      font-weight: 500;
      color: #c94f7c;
      transition: 0.3s;
    }

    nav a:hover {
      color: #ff85b3;
      text-shadow: 0 0 5px #ffb6c1;
    }

    section {
      max-width: 900px;
      margin: 50px auto;
      padding: 0 20px;
    }

    section h2 {
      text-align: center;
      font-family: 'Playfair Display', serif;
      font-size: 2rem;
      color: #c94f7c;
      margin-bottom: 30px;
    }

    .about, .projects, .contact {
      background: rgba(255, 255, 255, 0.8);
      padding: 35px;
      border-radius: 20px;
      box-shadow: 0 15px 30px rgba(255, 182, 193, 0.25);
    }

    .projects .project {
      background: #fff5f8;
      padding: 20px;
      border-radius: 15px;
      margin-bottom: 20px;
      border-left: 5px solid #ffb6c1;
    }

    .projects .project h3 {
      color: #b03a64;
      margin-bottom: 8px;
    }

    .contact {
      text-align: center;
    }

    .contact a {
      display: inline-block;
      margin: 10px;
      padding: 12px 28px;
      background: #c94f7c;
      color: #fff;
      text-decoration: none;
      border-radius: 30px;
      font-weight: 500;
      transition: 0.3s;
    }

    .contact a:hover {
      background: #ff85b3;
      box-shadow: 0 0 15px #ffb6c1;
    }

    footer {
      text-align: center;
      padding: 25px;
      color: #8a5a6a;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Paulyn Joy Manatlao</h1>
    <p>Web Enthusiast • Creative Thinker • Lifelong Learner</p>
  </header>

  <!-- Navigation -->
  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- About Section -->
  <section id="about" class="about">
    <h2>About Me</h2>
    <p>
      Hello! I'm Paulyn Joy Manatlao. I enjoy creating elegant and user-friendly web designs inspired by
      beauty, balance, and creativity. I believe technology and art can come together to create meaningful
      digital experiences.
    </p>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="projects">
    <h2>My Projects</h2>

    <div class="project">
      <h3>Floral Portfolio Website</h3>
      <p>A soft, aesthetic portfolio design focused on elegance and simplicity using HTML and CSS.</p>
    </div>

    <div class="project">
      <h3>Personal Web Page</h3>
      <p>A responsive personal website showcasing skills, interests, and contact information.</p>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>Let’s connect 💐</p>
    <a href="mailto:paulynjoynebresmanatlao@gmail.com">Email</a>
    <a href="#">GitHub</a>
    <a href="#">Facebook</a>
  </section>

  <footer>
    &copy; 2026 Paulyn Joy Manatlao. All rights reserved.
  </footer>

</body>
</html>
