# PORTFOLIO...-OBINAS
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio | Hackathon Edition</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Poppins', sans-serif;
      background: #f4f6f9;
      color: #1f2937;
      line-height: 1.6;
    }
    .container {
      max-width: 1100px;
      margin: auto;
      padding: 2rem;
    }
    header {
      background: #111827;
      color: #fff;
      padding: 1.5rem 0;
    }
    .logo {
      font-size: 1.8rem;
      font-weight: 600;
    }
    nav {
      margin-top: 1rem;
    }
    nav a {
      margin-right: 1.5rem;
      text-decoration: none;
      color: #d1d5db;
      font-weight: 300;
      transition: 0.3s;
    }
    nav a:hover {
      color: #facc15;
    }
    .hero {
      background: #4f46e5;
      color: white;
      text-align: center;
      padding: 4rem 2rem;
    }
    .hero h1 {
      font-size: 2.8rem;
    }
    .hero p { 
      font-size: 1.2rem;
      margin-top: 1rem;
    }
    section {
      padding: 4rem 2rem;
    }
    h2 {
      text-align: center;
      margin-bottom: 2rem;
      color: #111827;
    }
    .about p, .education p, .interests p, .languages ul, .projects .project-card {
      max-width: 800px;
      margin: auto;
      font-size: 1.05rem;
      color: #374151;
    }
    .languages ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding-top: 1rem;
    }
    .languages li {
      background: #e5e7eb;
      padding: 0.6rem 1.2rem;
      border-radius: 8px;
      font-weight: 500;
    }
    .project-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    .project-card {
      background: #fff;
      padding: 1.5rem;
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.08);
      transition: transform 0.3s;
    }
    .project-card:hover {
      transform: translateY(-5px);
    }
    footer {
      text-align: center;
      background: #111827;
      color: #d1d5db;
      padding: 2rem;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <div class="container">
      <div class="logo">My  Portfolio</div>
      <nav>
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#languages">Languages</a>
        <a href="#interests">Interests</a>
        <a href="#projects">Projects</a>
      </nav>
    </div>
  </header>
 
  <section class="hero">
    <h1>Hello, I'm <span style="color: #facc15;">DAVID OBINA😍</span></h1>
    <p>A passionate Full-Stack Developer | Python • C • CSS</p>
  </section>

  <section id="about" class="about">
    <h2>About Me</h2>
    <p>
      I'm a highly motivated IT student currently exploring the world of full-stack development.
      My passion lies in building clean, scalable, and user-focused web applications.
      What drives me is the thrill of solving real-world problems using code and continuously learning new technologies.
      <
   
    </p>
  </section>

  <section id="education" class="education">
    <h2>Educational Background</h2>
    <p>
      I am currently pursuing a Bachelor’s degree in Information Technology at Jomo Kenyatta University of Agriculture and Technology (JKUAT).
      I graduated from Gedi High School with a B+ in my KCSE. My education has laid a solid foundation in programming and system design.
    </p>
  </section>

  <section id="languages" class="languages">
    <h2>Programming Languages</h2>
    <ul>
      <li>Python</li>
      <li>CSS</li>
      <li>C</li>
    </ul>
  </section>

  <section id="interests" class="interests">
    <h2>Interests in Full-Stack Development</h2>
    <p>
      I'm deeply interested in both front-end and back-end development.
      I enjoy building responsive user interfaces, integrating APIs, managing databases,
      and deploying apps that are fast and reliable. Technologies like React, Node.js, Flask, and Firebase excite me.
      <a href=""
    </p>
  </section>

  <section id="projects" class="projects">
    <h2>Sample Projects</h2>
    <div class="project-grid">
      <div class="project-card">
        <h3>Student Management System</h3>
        <p>Developed a Python-based CLI tool to manage student data with features like record creation, search, and grade analysis.</p>
      </div>
      <div class="project-card">
        <h3>Personal Portfolio Website</h3>
        <p>Built a responsive personal website using HTML, CSS, and a touch of JS for smooth interactions and animations.</p>
      </div>
      <div class="project-card">
        <h3>Weather Dashboard (API)</h3>
        <p>Created a weather app that fetches real-time data using a weather API and displays it using clean UI components.</p>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 DAVID OBINA | Designed for Hackathon Success 🚀</p>
  </footer>

</body>
</html>
