<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Home | Umer Mian Portfolio</title>
  <link rel="stylesheet" href="style.css" />
  <link rel="stylesheet" href="mediaqueries.css" />
</head>

<body>
  <!-- Navigation Bar -->
  <nav id="desktop-nav">
    <div class="logo">Umer Mian</div>
    <div>
      <ul class="nav-links">
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="experience.html">Experience</a></li>
        <li><a href="projects.html">Projects</a></li>
        <li><a href="skills.html">Skills</a></li>
        <li><a href="certifications.html">Certifications</a></li>
        <li><a href="awards.html">Awards</a></li>
        <li><a href="volunteering.html">Volunteering</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Home Section -->
  <section id="home">
    <div class="home-container">
      <div class="section__pic-container">
        <img src="./assets/profile-pic.jpg" alt="Umer Mian Profile Picture" class="profile-img"/>
      </div>
      <div class="section__text">
        <h1>Welcome to My Portfolio</h1>
        <p>I'm Umer Mian, an aspiring IT professional passionate about technology and innovation.</p>
        <div class="btn-container">
          <button class="btn btn-color-1" onclick="window.open('./assets/UmerMian-Resume.pdf')">Download Resume</button>
          <button class="btn btn-color-2" onclick="location.href='contact.html'">Contact Me</button>
        </div>
        <div id="socials-container">
          <img src="./assets/linkedin.png" alt="LinkedIn Icon" class="icon" onclick="location.href='https://linkedin.com/in/umermian'"/>
          <img src="./assets/github.png" alt="GitHub Icon" class="icon" onclick="location.href='https://github.com/umermian'"/>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <p>© 2025 Umer Mian. All Rights Reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
