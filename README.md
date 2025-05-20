# Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Portfolio</title>
  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
      background-color: #f9f9fb;
      color: #2c3e50;
      scroll-behavior: smooth;
    }

    nav {
      background-color: #1f2937;
      color: #fff;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 15px 0;
      position: sticky;
      top: 0;
      width: 100%;
      z-index: 1000;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }

    nav h1 {
      font-size: 22px;
      margin: 0;
      font-weight: 700;
      padding-left: 30px;
    }

    nav ul {
      list-style: none;
      display: flex;
      margin: 0;
      padding: 0;
      justify-content: center;
    }

    nav ul li {
      margin-left: 30px;
    }

    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-weight: 500;
    }

    nav ul li a:hover {
      text-decoration: underline;
    }

    .container {
      text-align: center;
      padding: 2rem;
    }

    .profile-pic {
      width: 140px;
      border-radius: 50%;
      margin-top: 20px;
      box-shadow: 0 0 10px rgba(0,0,0,0.15);
    }

    .hero {
      background: linear-gradient(to right, #2c3e50, #34495e);
      color: #fff;
      padding: 80px 20px;
    }

    section {
      padding: 50px 20px;
      background: #ffffff;
      margin: 20px auto;
      border-radius: 10px;
      width: 90%;
      max-width: 900px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
    }

    section h2 {
      color: #1f2937;
      font-size: 26px;
      margin-bottom: 20px;
      border-bottom: 2px solid #e1e1e1;
      display: inline-block;
      padding-bottom: 5px;
    }

    ul.skills-list {
      list-style: none;
      padding: 0;
      margin: 0;
    }

    ul.skills-list li {
      background: #e8ecf0;
      color: #2c3e50;
      margin: 5px;
      padding: 10px 15px;
      display: inline-block;
      border-radius: 6px;
      font-weight: 500;
    }

    .project, .achievement {
      margin-bottom: 20px;
      text-align: left;
    }

    .project h3, .achievement h3 {
      margin-bottom: 5px;
      color: #34495e;
    }

    .project a, .achievement a {
      text-decoration: none;
      color: #2980b9;
      font-weight: bold;
    }

    a:hover {
      text-decoration: underline;
    }

    form label {
      display: block;
      margin-bottom: 5px;
      font-weight: 600;
    }

    form input[type="email"],
    form input[type="url"] {
      width: 100%;
      padding: 10px;
      margin-bottom: 20px;
      border-radius: 5px;
      border: 1px solid #ccc;
      font-family: 'Poppins', sans-serif;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #1f2937;
      color: #fff;
    }

    @media (max-width: 600px) {
      nav ul {
        flex-direction: column;
        align-items: flex-start;
      }

      nav ul li {
        margin: 5px 0;
      }

      .profile-pic {
        width: 100px;
      }

      section {
        padding: 20px;
        width: 95%;
      }
    }
  </style>
</head>
<body>

  <!-- Navigation Bar -->
  <nav>
    <h1>Portfolio</h1>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#achievements">Achievements</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <header class="hero" id="home">
    <div class="container">
      <img src="https://via.placeholder.com/150" alt="Profile Picture" class="profile-pic"/>
      <h1>Hi, I'm a Web Developer</h1>
      <p>Web Developer | Frontend Enthusiast | Problem Solver</p>
    </div>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>I’m a passionate web developer with a background in computer science. I graduated from [Your University] and have worked on several frontend and backend projects using technologies like HTML, CSS, JavaScript, and React.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Portfolio Website</h3>
      <p>A responsive personal portfolio to showcase my web development work.</p>
      <a href="#">View Project</a>
    </div>
    <div class="project">
      <h3>Todo App</h3>
      <p>A simple JavaScript app to manage tasks with localStorage.</p>
      <a href="#">View Project</a>
    </div>
    <div class="project">
      <h3>Weather App</h3>
      <p>App that uses OpenWeatherMap API to display live weather info.</p>
      <a href="#">View Project</a>
    </div>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul class="skills-list">
      <li>HTML5</li>
      <li>CSS3</li>
      <li>JavaScript</li>
      <li>React</li>
      <li>Git & GitHub</li>
      <li>Responsive Design</li>
    </ul>
  </section>

  <section id="achievements">
    <h2>Achievements</h2>
    <div class="achievement">
      <h3>Google Developer Certificate</h3>
      <p>Completed the Google Web Development Certification with distinction.</p>
    </div>
    <div class="achievement">
      <h3>Hackathon Winner - TechFest 2024</h3>
      <p>Won 1st place in a 48-hour coding hackathon for developing a productivity app.</p>
    </div>
    <div class="achievement">
      <h3>Top 10% on LeetCode Global Ranking</h3>
      <p>Ranked among the top 10% developers worldwide on LeetCode.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <form action="mailto:youremail@example.com" method="POST" enctype="text/plain">
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" autocomplete="email" required>

      <label for="github">GitHub:</label>
      <input type="url" id="github" name="github" placeholder="https://github.com/yourusername" autocomplete="url">

      <label for="linkedin">LinkedIn:</label>
      <input type="url" id="linkedin" name="linkedin" placeholder="https://linkedin.com/in/yourusername" autocomplete="url">
    </form>
  </section>

  <footer>
    <p>© 2025 Your Name. All rights reserved.</p>
  </footer>

</body>
</html>

