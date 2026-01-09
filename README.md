<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Paulyn Joy Manatlao | Floral Portfolio</title>

  <!-- Google Fonts -->
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
      background:
        radial-gradient(circle at top left, #ffe4ef 0%, transparent 50%),
        radial-gradient(circle at bottom right, #fcd6e6 0%, transparent 50%),
        linear-gradient(to bottom, #fff1f7, #ffffff);
      color: #4a4a4a;
      overflow-x: hidden;
    }

    header {
      text-align: center;
      padding: 90px 20px 60px;
      background: rgba(255, 255, 255, 0.8);
      backdrop-filter: blur(8px);
      box-shadow: 0 10px 30px rgba(255, 182, 193, 0.35);
    }

    .profile-pic {
      width: 150px;
      height: 150px;
      margin: 0 auto 25px;
      border-radius: 50%;
      overflow: hidden;
      border: 5px solid #ffb6c1;
      box-shadow: 0 10px 25px rgba(255, 182, 193, 0.45);
    }

    .profile-pic img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 2rem;
      color: #c94f7c;
      margin-bottom: 8px;
    }

    /* Motto */
    .motto {
      font-size: 0.9rem;
      font-style: italic;
      color: #9a5a72;
      max-width: 600px;
      margin: 0 auto 8px;
      line-height: 1.5;
    }

    .warrior {
      font-size: 0.85rem;
      font-weight: 500;
      color: #c94f7c;
      margin-bottom: 12px;
    }

    header p {
      font-size: 0.9rem;
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
      color: #ff6fa5;
      text-shadow: 0 0 6px #ffc1d9;
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

    .about, .skills, .contact {
      background: rgba(255, 255, 255, 0.85);
      padding: 35px;
      border-radius: 22px;
      box-shadow: 0 15px 35px rgba(255, 182, 193, 0.3);
    }

    .skills-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }

    .skill {
      background: #fff3f8;
      padding: 20px;
      border-radius: 15px;
      text-align: center;
      font-weight: 500;
      color: #b03a64;
      box-shadow: 0 8px 20px rgba(255, 182, 193, 0.25);
    }

    .contact {
      text-align: center;
    }

    .contact a {
      display: inline-block;
      margin: 10px;
      padding: 12px 30px;
      background: linear-gradient(135deg, #c94f7c, #ff85b3);
      color: #fff;
      text-decoration: none;
      border-radius: 30px;
      font-weight: 500;
      transition: 0.3s;
    }

    .contact a:hover {
      transform: translateY(-3px);
      box-shadow: 0 0 20px #ffb6c1;
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
    <div class="profile-pic">
      <img src="https://uploads.onecompiler.io/44a2gqpwf/44a3vxvb4/1000008314.jpg" alt="Paulyn Joy Manatlao">
    </div>

    <h1>Paulyn Joy Manatlao</h1>

    <div class="motto">
      “Despite pain and challenge, strength and hope will lead you to victory.”
    </div>
    <div class="warrior">– Lupus Warrior</div>

    <p>Web Enthusiast • Creative Thinker • Lifelong Learner</p>
  </header>

  <!-- Navigation -->
  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- About -->
  <section id="about" class="about">
    <h2>About Me</h2>
    <p>
      I am Paulyn Joy Manatlao, a creative individual who believes that resilience, passion, and purpose
      can turn challenges into strength. Living with lupus has taught me patience, determination, and the
      value of hope. Through web design and creative expression, I strive to build meaningful digital
      experiences while continuously learning and growing—both personally and professionally.
    </p>
  </section>

  <!-- Skills -->
  <section id="skills" class="skills">
    <h2>My Skills</h2>

    <div class="skills-list">
      <div class="skill">HTML & CSS</div>
      <div class="skill">Basic JavaScript</div>
      <div class="skill">Responsive Design</div>
      <div class="skill">Creative UI Design</div>
      <div class="skill">Beginner Web Development</div>
      <div class="skill">Content Layout & Styling</div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>Let’s connect 💐</p>

    <a href="mailto:paulynjoynebresmanatlao@gmail.com">Email</a>
    <a href="https://github.com/YOUR-GITHUB-USERNAME" target="_blank">GitHub</a>
    <a href="https://facebook.com/YOUR-FACEBOOK-USERNAME" target="_blank">Facebook</a>
  </section>

  <footer>
    &copy; 2026 Paulyn Joy Manatlao. All rights reserved.
  </footer>

</body>
</html>
