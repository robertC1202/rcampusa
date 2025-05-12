# Robert Campusano
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-scale=1.0">
  <title>Robert Campusano | Portfolio</title>
  <style>
    body { margin:0; font-family: sans-serif; line-height:1.6; }
    header { position: fixed; width:100%; background: #333; padding:10px 0; z-index:100; }
    nav { max-width:900px; margin:0 auto; text-align:center; }
    nav a {
      color:#fff; margin:0 15px; text-decoration:none; font-weight:500;
    }
    nav a:hover { text-decoration: underline; }
    section { padding:80px 20px 40px; max-width:900px; margin:0 auto; }
    h1,h2 { margin-bottom:10px; }
    .btn { display:inline-block; padding:8px 15px; background:#007ACC; color:#fff; text-decoration:none; border-radius:4px; }
    .projects { list-style:none; padding:0; }
    .project { margin-bottom:30px; }
    .project img { max-width:100%; height:auto; display:block; margin-top:10px; }
    footer { text-align:center; padding:20px 0; background:#f4f4f4; margin-top:40px; }
  </style>
</head>
<body>

  <header>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About Me</a>
      <a href="#resume">Resume</a>
      <a href="#work">My Work</a>
    </nav>
  </header>

  <section id="home">
    <h1>Welcome</h1>
    <p>Hi there! I’m <strong>Robert Campusano</strong>, a junior Computer Scientist at George Mason University. Please use the nav above to learn more about me and my projects.</p>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>Hi, I'm Robert Campusano, a junior computer scientist at George Mason University. I’m passionate about software development, data structures, and game programming, and I have hands-on experience with languages such as Java, C#, and Python.</p>
  </section>

  <section id="resume">
    <h2>Resume</h2>
    <p>
      <a
        class="btn"
        href="file:///Users/robertcampusa/Downloads/Robert’s%20Resume(1).pdf"
        target="_blank"
        >Download My Resume (PDF)</a
      >
    </p>
  </section>

  <section id="work">
    <h2>My Work</h2>
    <ul class="projects">
      <li class="project">
        <h3>Unity Game Prototype</h3>
        <p>
          I collaborated with classmates to develop a game prototype using Unity and C#.
        </p>
        <!-- Example screenshot; replace path with your own -->
        <img src="images/unity-prototype-screenshot.jpg" alt="Unity prototype screenshot">
      </li>

      <li class="project">
        <h3>Duck Souls Prototype</h3>
        <p>
          An action-adventure “Souls-like” starring a brave duck. Built in Unity, featuring
          2D→3D world transitions and challenging boss encounters.
        </p>
        <!-- Replace with your actual playable build or demo link -->
        <p><a class="btn" href="downloads/duck-souls-demo.zip" download>Download Demo</a></p>
        <!-- Example gameplay video; replace source with your video -->
        <video controls width="100%" src="videos/duck-souls-demo.mp4">
          Your browser doesn’t support HTML5 video.
        </video>
      </li>

      <li class="project">
        <h3>Credit Reporting System</h3>
        <p>
          In this project, I created a system to load raw credit data files from various banks and produce comprehensive individual credit reports.
          The system processes CSV files submitted by credit-card institutions, validates data to avoid errors, and generates reports efficiently.
        </p>
        <p>
          Data structures used:
          Linked Lists, Stacks, Queues, and Hash Tables for effective
          data retrieval, sorting, and reporting.
        </p>
        <!-- If you have a screenshot or link, add here -->
      </li>
    </ul>
  </section>

  <footer>
    <p>&copy; 2025 Robert Campusano</p>
  </footer>

</body>
</html>




