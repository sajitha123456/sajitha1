<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sajitha | My Portfolio</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
      font-family: Arial, sans-serif;
    }

    body {
      background: #fff5fb;
      color: #333;
    }

    /* Navbar */
    nav {
      width: 100%;
      padding: 20px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: white;
      position: fixed;
      top: 0;
      z-index: 1000;
      box-shadow: 0 2px 15px rgba(0,0,0,0.08);
    }

    .logo {
      font-size: 28px;
      font-weight: bold;
      color: #e91e63;
    }

    nav ul {
      display: flex;
      list-style: none;
      gap: 30px;
    }

    nav ul li a {
      text-decoration: none;
      color: #333;
      font-weight: 600;
      transition: 0.3s;
    }

    nav ul li a:hover {
      color: #e91e63;
    }

    /* Home */
    .home {
      min-height: 100vh;
      padding: 130px 8% 60px;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      background: linear-gradient(135deg, #ffe0ef, #f3e5ff);
    }

    .home-content h1 {
      font-size: 60px;
      color: #e91e63;
      margin-bottom: 15px;
    }

    .home-content h2 {
      font-size: 30px;
      color: #555;
      margin-bottom: 20px;
    }

    .home-content p {
      font-size: 18px;
      max-width: 600px;
      line-height: 1.7;
      margin: auto;
      color: #666;
    }

    .btn {
      display: inline-block;
      margin-top: 30px;
      padding: 14px 30px;
      background: #e91e63;
      color: white;
      text-decoration: none;
      border-radius: 30px;
      font-weight: bold;
      transition: 0.3s;
    }

    .btn:hover {
      background: #c2185b;
      transform: translateY(-3px);
    }

    /* Common Section */
    section {
      padding: 90px 8%;
    }

    .title {
      text-align: center;
      font-size: 38px;
      color: #e91e63;
      margin-bottom: 45px;
    }

    /* About */
    .about {
      background: white;
      text-align: center;
    }

    .about p {
      max-width: 750px;
      margin: auto;
      line-height: 1.8;
      font-size: 18px;
      color: #666;
    }

    /* Skills */
    .skills-container {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 25px;
    }

    .skill {
      background: white;
      width: 220px;
      padding: 30px 20px;
      text-align: center;
      border-radius: 20px;
      box-shadow: 0 5px 20px rgba(0,0,0,0.08);
      transition: 0.3s;
    }

    .skill:hover {
      transform: translateY(-10px);
    }

    .skill h3 {
      color: #e91e63;
      margin-bottom: 10px;
    }

    .skill p {
      color: #777;
    }

    /* Gallery */
    .gallery {
      background: #fff;
    }

    .gallery-container {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 25px;
    }

    .gallery-box {
      width: 250px;
      height: 180px;
      border-radius: 20px;
      background: linear-gradient(135deg, #ff9ac2, #b388ff);
      display: flex;
      justify-content: center;
      align-items: center;
      color: white;
      font-size: 22px;
      font-weight: bold;
      box-shadow: 0 5px 20px rgba(0,0,0,0.1);
    }

    /* Contact */
    .contact {
      text-align: center;
      background: linear-gradient(135deg, #ffe0ef, #f3e5ff);
    }

    .contact p {
      font-size: 18px;
      margin: 12px;
      color: #555;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 25px;
      background: #e91e63;
      color: white;
    }

    /* Mobile */
    @media (max-width: 700px) {
      nav {
        padding: 15px 5%;
      }

      .logo {
        font-size: 23px;
      }

      nav ul {
        gap: 12px;
      }

      nav ul li a {
        font-size: 13px;
      }

      .home-content h1 {
        font-size: 42px;
      }

      .home-content h2 {
        font-size: 23px;
      }

      .home-content p {
        font-size: 16px;
      }

      section {
        padding: 70px 5%;
      }

      .title {
        font-size: 30px;
      }

      .skill {
        width: 100%;
        max-width: 300px;
      }

      .gallery-box {
        width: 100%;
        max-width: 320px;
      }
    }
  </style>
</head>

<body>

  <!-- Navbar -->
  <nav>
    <div class="logo">Sajitha</div>

    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#gallery">Gallery</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- Home -->
  <section class="home" id="home">
    <div class="home-content">
      <h1>Hello, I'm Sajitha 💖</h1>
      <h2>Welcome to My Website</h2>
      <p>
        This is my personal website where you can know more
        about me, my skills and my interests.
      </p>

      <a href="#about" class="btn">Explore More</a>
    </div>
  </section>

  <!-- About -->
  <section class="about" id="about">
    <h2 class="title">About Me 🌸</h2>

    <p>
      Hi! My name is Sajitha. Welcome to my personal website.
      I am passionate about learning new things, exploring
      creative ideas and developing my skills.
      This website represents my personality and interests.
    </p>
  </section>

  <!-- Skills -->
  <section id="skills">
    <h2 class="title">My Skills ✨</h2>

    <div class="skills-container">

      <div class="skill">
        <h3>HTML</h3>
        <p>Creating beautiful web pages.</p>
      </div>

      <div class="skill">
        <h3>CSS</h3>
        <p>Designing attractive websites.</p>
      </div>

      <div class="skill">
        <h3>JavaScript</h3>
        <p>Making websites interactive.</p>
      </div>

      <div class="skill">
        <h3>Creative</h3>
        <p>Creative thinking and new ideas.</p>
      </div>

    </div>
  </section>

  <!-- Gallery -->
  <section class="gallery" id="gallery">
    <h2 class="title">My Gallery 📸</h2>

    <div class="gallery-container">

      <div class="gallery-box">
        Sajitha 💕
      </div>

      <div class="gallery-box">
        My Dreams ✨
      </div>

      <div class="gallery-box">
        My Life 🌸
      </div>

    </div>
  </section>

  <!-- Contact -->
  <section class="contact" id="contact">
    <h2 class="title">Contact Me 📞</h2>

    <p>📧 Email: sajitha@example.com</p>
    <p>📱 Phone: +91 XXXXX XXXXX</p>
    <p>📍 Tamil Nadu, India</p>

    <a href="mailto:sajitha@example.com" class="btn">
      Send Message
    </a>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2026 Sajitha. All Rights Reserved 💖</p>
  </footer>

</body>
</html>

