<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sajitha | Front End Developer</title>

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  scroll-behavior:smooth;
  font-family:Arial,sans-serif;
}

body{
  background:#fff7fb;
  color:#333;
}

header{
  position:fixed;
  top:0;
  width:100%;
  background:#fff;
  box-shadow:0 3px 20px rgba(0,0,0,.08);
  z-index:1000;
}

nav{
  max-width:1200px;
  margin:auto;
  padding:18px 30px;
  display:flex;
  justify-content:space-between;
  align-items:center;
}

.logo{
  font-size:28px;
  font-weight:bold;
  color:#e91e63;
}

nav ul{
  display:flex;
  list-style:none;
  gap:30px;
}

nav ul a{
  text-decoration:none;
  color:#333;
  font-weight:bold;
  transition:.3s;
}

nav ul a:hover{
  color:#e91e63;
}

.menu{
  display:none;
  font-size:28px;
  color:#e91e63;
  cursor:pointer;
}

#home{
  min-height:100vh;
  padding:120px 8% 60px;
  display:flex;
  align-items:center;
  justify-content:center;
  background:linear-gradient(135deg,#ffe0ef,#eee2ff);
}

.hero{
  max-width:1100px;
  width:100%;
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:50px;
  align-items:center;
}

.hero h4{
  color:#e91e63;
  font-size:20px;
  margin-bottom:15px;
}

.hero h1{
  font-size:60px;
  margin-bottom:10px;
}

.hero h1 span{
  color:#e91e63;
}

.hero h2{
  color:#555;
  font-size:28px;
  margin-bottom:20px;
}

.hero p{
  color:#666;
  font-size:18px;
  line-height:1.7;
  max-width:550px;
}

.buttons{
  margin-top:30px;
  display:flex;
  gap:15px;
}

.btn{
  display:inline-block;
  padding:14px 28px;
  border-radius:30px;
  font-weight:bold;
  text-decoration:none;
  transition:.3s;
}

.primary{
  background:#e91e63;
  color:white;
}

.primary:hover{
  background:#c2185b;
  transform:translateY(-3px);
}

.secondary{
  border:2px solid #e91e63;
  color:#e91e63;
}

.secondary:hover{
  background:#e91e63;
  color:white;
}

.profile{
  width:350px;
  height:350px;
  margin:auto;
  border-radius:50%;
  background:linear-gradient(135deg,#ff80ab,#9c6cff);
  display:flex;
  justify-content:center;
  align-items:center;
  font-size:100px;
  box-shadow:0 20px 50px rgba(233,30,99,.25);
}

section{
  padding:90px 8%;
}

.title{
  text-align:center;
  margin-bottom:45px;
}

.title h2{
  font-size:40px;
  color:#e91e63;
  margin-bottom:10px;
}

.title p{
  color:#777;
}

#about{
  background:white;
}

.about{
  max-width:800px;
  margin:auto;
  text-align:center;
}

.about p{
  font-size:18px;
  color:#666;
  line-height:1.9;
}

.skills{
  max-width:1000px;
  margin:auto;
  display:grid;
  grid-template-columns:repeat(4,1fr);
  gap:25px;
}

.card{
  background:white;
  padding:35px 20px;
  text-align:center;
  border-radius:20px;
  box-shadow:0 8px 25px rgba(0,0,0,.08);
  transition:.3s;
}

.card:hover{
  transform:translateY(-10px);
}

.icon{
  font-size:45px;
  margin-bottom:15px;
}

.card h3{
  color:#e91e63;
  margin-bottom:10px;
}

.card p{
  color:#777;
  line-height:1.5;
}

#projects{
  background:white;
}

.projects{
  max-width:1100px;
  margin:auto;
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:25px;
}

.project{
  background:#fff7fb;
  padding:25px;
  border-radius:20px;
  box-shadow:0 8px 25px rgba(0,0,0,.08);
  transition:.3s;
}

.project:hover{
  transform:translateY(-8px);
}

.project-img{
  height:160px;
  border-radius:15px;
  background:linear-gradient(135deg,#ff9ac2,#b388ff);
  display:flex;
  justify-content:center;
  align-items:center;
  font-size:55px;
  margin-bottom:20px;
}

.project h3{
  color:#e91e63;
  margin-bottom:10px;
}

.project p{
  color:#777;
  line-height:1.6;
}

#contact{
  text-align:center;
  background:linear-gradient(135deg,#ffe0ef,#eee2ff);
}

.contact p{
  margin:12px;
  font-size:18px;
  color:#555;
}

footer{
  background:#e91e63;
  color:white;
  text-align:center;
  padding:25px;
}

@media(max-width:900px){

  .hero{
    grid-template-columns:1fr;
    text-align:center;
  }

  .hero p{
    margin:auto;
  }

  .buttons{
    justify-content:center;
  }

  .skills{
    grid-template-columns:repeat(2,1fr);
  }

  .projects{
    grid-template-columns:1fr;
  }

  .profile{
    width:250px;
    height:250px;
    font-size:70px;
  }
}

@media(max-width:700px){

  nav{
    padding:15px 20px;
  }

  .menu{
    display:block;
  }

  nav ul{
    display:none;
    position:absolute;
    top:70px;
    left:0;
    width:100%;
    background:white;
    flex-direction:column;
    text-align:center;
    padding:20px;
  }

  nav ul.active{
    display:flex;
  }

  .hero h1{
    font-size:42px;
  }

  .hero h2{
    font-size:23px;
  }

  .skills{
    grid-template-columns:1fr;
  }

  .buttons{
    flex-direction:column;
    align-items:center;
  }

  .btn{
    width:200px;
    text-align:center;
  }

  .title h2{
    font-size:32px;
  }
}
</style>
</head>

<body>

<header>
<nav>
  <div class="logo">Sajitha</div>

  <div class="menu" onclick="menu()">☰</div>

  <ul id="nav">
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>
</header>

<section id="home">
<div class="hero">

<div>
  <h4>Hello 👋 I'm</h4>
  <h1>Sajitha <span>❤️</span></h1>
  <h2>Front End Developer</h2>

  <p>
    I create beautiful, responsive and user-friendly
    websites using modern front-end technologies.
  </p>

  <div class="buttons">
    <a href="#projects" class="btn primary">View Projects</a>
    <a href="#contact" class="btn secondary">Contact Me</a>
  </div>
</div>

<div>
  <div class="profile">👩🏻‍💻</div>
</div>

</div>
</section>

<section id="about">
<div class="title">
  <h2>About Me 🌸</h2>
  <p>Get to know me</p>
</div>

<div class="about">
<p>
Hi! My name is Sajitha. I am a passionate Front End Developer
who loves creating modern and attractive websites.
I enjoy learning new technologies and improving my skills.
</p>
</div>
</section>

<section id="skills">
<div class="title">
  <h2>My Skills ✨</h2>
  <p>Technologies I work with</p>
</div>

<div class="skills">

<div class="card">
  <div class="icon">🌐</div>
  <h3>HTML</h3>
  <p>Building clean and semantic web pages.</p>
</div>

<div class="card">
  <div class="icon">🎨</div>
  <h3>CSS</h3>
  <p>Creating beautiful and responsive designs.</p>
</div>

<div class="card">
  <div class="icon">⚡</div>
  <h3>JavaScript</h3>
  <p>Adding interactive features to websites.</p>
</div>

<div class="card">
  <div class="icon">💡</div>
  <h3>Creative</h3>
  <p>Creating unique ideas and experiences.</p>
</div>

</div>
</section>

<section id="projects">
<div class="title">
  <h2>My Projects 💻</h2>
  <p>Some of my works</p>
</div>

<div class="projects">

<div class="project">
  <div class="project-img">🛍️</div>
  <h3>Shopping Website</h3>
  <p>A modern responsive online shopping website.</p>
</div>

<div class="project">
  <div class="project-img">🍔</div>
  <h3>Food Website</h3>
  <p>An attractive food website with a clean interface.</p>
</div>

<div class="project">
  <div class="project-img">👩🏻‍💻</div>
  <h3>Portfolio Website</h3>
  <p>My personal portfolio showcasing my skills.</p>
</div>

</div>
</section>

<section id="contact">
<div class="title">
  <h2>Contact Me 📞</h2>
  <p>Let's connect together</p>
</div>

<div class="contact">
  <p>📧 sajitha@example.com</p>
  <p>📱 +91 XXXXX XXXXX</p>
  <p>📍 Tamil Nadu, India</p>
</div>

<a href="mailto:sajitha@example.com" class="btn primary">
Send Message
</a>
</section>

<footer>
<p>© 2026 Sajitha | Front End Developer 💖</p>
</footer>

<script>
function menu(){
  document.getElementById("nav").classList.toggle("active");
}

document.querySelectorAll("#nav a").forEach(function(link){
  link.addEventListener("click",function(){
    document.getElementById("nav").classList.remove("active");
  });
});
</script>

</body>
</html>
