<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Personal Portfolio</title>

    <!-- FONT AWESOME ICONS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

    <style>
        html {
            scroll-behavior: smooth;
        }

        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: radial-gradient(circle at top, #0f2027, #000000);
            color: #e0e0e0;
        }

        nav {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(0, 0, 0, 0.85);
            padding: 12px 0;
            box-shadow: 0 0 15px #00ffff55;
            z-index: 1000;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 30px;
            margin: 0;
            padding: 0;
        }

        nav a {
            color: #00ffff;
            text-decoration: none;
            font-weight: bold;
            letter-spacing: 1px;
            font-size: 0.95em;
        }

        nav a i {
            margin-right: 6px;
        }

        nav a:hover {
            text-shadow: 0 0 8px #00ffff;
        }

        header {
            text-align: center;
            padding: 120px 20px 60px;
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            box-shadow: 0 0 20px #00ffff55;
        }

        header img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #00ffff;
            box-shadow: 0 0 25px #00ffff;
            margin-bottom: 20px;
        }

        header h1 {
            font-size: 1.5em;
            margin: 10px 0 5px;
            letter-spacing: 2px;
        }

        header p {
            color: #00ffff;
            font-size: 0.80em;
        }

        .quote {
            font-style: italic;
            font-size: 1.10em;
            color: #c9ffff;
            max-width: 600px;
            margin: 15px auto 0;
            line-height: 1.6;
        }

        .quote span {
            display: block;
            margin-top: 6px;
            color: #00ffff;
            font-weight: bold;
        }

        section {
            margin: 30px auto;
            max-width: 900px;
            background: rgba(255, 255, 255, 0.05);
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 0 15px #00ffff22;
        }

        h2 {
            color: #00ffff;
            border-bottom: 2px solid #00ffff;
            padding-bottom: 10px;
            letter-spacing: 1px;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        ul li::before {
            content: "▹ ";
            color: #00ffff;
        }

        footer {
            text-align: center;
            padding: 20px;
            color: #777;
            font-size: 0.9em;
        }

        a {
            color: #00ffff;
            text-decoration: none;
        }

        a:hover {
            text-shadow: 0 0 5px #00ffff;
        }
    </style>
</head>
<body>

    <nav>
        <ul>
            <li><a href="#home"><i class="fas fa-house"></i>HOME</a></li>
            <li><a href="#about"><i class="fas fa-user"></i>ABOUT ME</a></li>
            <li><a href="#skills"><i class="fas fa-code"></i>SKILLS</a></li>
            <li><a href="#contact"><i class="fas fa-envelope"></i>CONTACT</a></li>
        </ul>
    </nav>

    <header id="home">
        <img src="https://uploads.onecompiler.io/44a2gqpwf/44a3an3gg/1000002594.jpg" alt="Profile Picture">
        <h1>Paulyn Joy Manatlao</h1>

        <div class="quote">
            “Despite pain and challenge, strength and hope will lead you to victory”
            <span>- Lupus Warrior</span>
        </div>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>
            I am a dedicated and motivated student with a strong interest in modern web technologies.
            I enjoy creating futuristic, clean, and user-friendly designs that combine creativity and functionality.
        </p>
        <p>
            My personal journey has taught me resilience, patience, and strength — values that I bring into
            my studies, projects, and future career in technology.
        </p>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Critical Thinking</li>
            <li>Problem Solving</li>
            <li>Attention to Detail</li>
            <li>Analytical Thinking</li>
            <li>Willingness to Learn New Technologies</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: <a href="#">paulynjoynebresmanatlao@gmail.com</a></p>
        <p>Facebook: <a href="#">facebook.com/yourprofile</a></p>
        <p>GitHub: <a href="#">github.com/yourusername</a></p>
    </section>

    <footer>
        <p>© 2026 Paulyn Joy Manatlao</p>
    </footer>

</body>
</html>
