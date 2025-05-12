# index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Game Portfolio</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
    header { background: #333; padding: 1rem; position: sticky; top: 0; }
    nav ul { list-style: none; margin: 0; padding: 0; display: flex; }
    nav li { margin-right: 1rem; }
    nav a { color: #fff; text-decoration: none; }
    section { padding: 4rem 1rem; }
    section:nth-child(even) { background: #f4f4f4; }
    h2 { margin-top: 0; }
    .work-gallery { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 1rem; }
    .work-item { border: 1px solid #ccc; padding: 0.5rem; }
    .work-item img { max-width: 100%; height: auto; }
  </style>
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About Me</a></li>
        <li><a href="#resume">Resume</a></li>
        <li><a href="#work">My Work</a></li>
      </ul>
    </nav>
  </header>

  <section id="home">
    <h2>Home</h2>
    <p>Welcome to my game portfolio! Here you can find information about me and my projects.</p>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>Hi, I'm [Your Name], a game developer with experience in Unity, C#, and game design. I love creating immersive experiences and challenging gameplay.</p>
  </section>

  <section id="resume">
    <h2>Resume</h2>
    <p>You can download my resume here:</p>
    <a href="resume.pdf" download>Download My Resume (PDF)</a>
  </section>

  <section id="work">
    <h2>My Work</h2>
    <div class="work-gallery">
      <!-- Project 1 -->
      <div class="work-item">
        <h3>Project Title 1</h3>
        <img src="project1.png" alt="Screenshot of Project 1">
        <p><a href="project1.zip" download>Download Game</a></p>
        <p><a href="gameplay1.mp4">Watch Gameplay Video</a></p>
      </div>
      <!-- Project 2 -->
      <div class="work-item">
        <h3>Project Title 2</h3>
        <img src="project2.png" alt="Screenshot of Project 2">
        <p><a href="project2.zip" download>Download Game</a></p>
        <p><a href="gameplay2.mp4">Watch Gameplay Video</a></p>
      </div>
      <!-- Add more projects as needed -->
    </div>
  </section>

</body>
</html>
