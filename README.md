# Robert Campusano
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Robert Campusano - Game & CS Portfolio</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
    header { background: #333; padding: 1rem; position: sticky; top: 0; }
    nav ul { list-style: none; margin: 0; padding: 0; display: flex; }
    nav li { margin-right: 1rem; }
    nav a { color: #fff; text-decoration: none; }
    section { padding: 4rem 1rem; }
    section:nth-child(even) { background: #f4f4f4; }
    h2 { margin-top: 0; }
    .work-gallery { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 1rem; }
    .work-item { border: 1px solid #ccc; padding: 1rem; }
    .work-item img { max-width: 100%; height: auto; display: block; margin-bottom: 0.5rem; }
    .work-item p { margin: 0.5rem 0; }
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
    <p>Welcome to my portfolio! Explore my background, projects, and work in computer science.</p>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>Hi, I'm Robert Campusano, a junior computer scientist at George Mason University. I’m passionate about software development, data structures, and game programming, and I have hands-on experience with languages such as Java, C#, and Python.</p>
    <p>My coursework has included Data Structures, Algorithms, and Software Engineering, where I've learned to design efficient solutions and collaborate on complex codebases. Beyond the classroom, I enjoy participating in hackathons, contributing to open-source projects, and exploring new technologies.</p>
    <p>In my free time, I like to prototype interactive applications, solve algorithmic challenges, and stay active in the tech community through workshops and meetups. I'm always eager to learn and take on projects that push my skills further.</p>
  </section>

  <section id="resume">
    <h2>Resume</h2>
    <p>Download my resume here:</p>
    <a href="Robert%27s%20Resume%201.pdf" download target="_blank">Download My Resume (PDF)</a>
  </section>

  <section id="work">
    <h2>My Work</h2>
    <div class="work-gallery">
      <!-- Unity Game Prototype -->
      <div class="work-item">
        <h3>Unity Game Prototype</h3>
        <p>I collaborated with classmates to develop a game prototype using Unity and C#.</p>
        <img src="Duck%20Soul%20Image.jpeg" alt="In-game screenshot of Duck Souls prototype">
        <img src="Duck%20Soul%20Image%202.jpeg" alt="Alternative in-game screenshot of Duck Souls prototype">
      </div>
      <!-- Credit Reporting System -->
      <div class="work-item">
        <h3>Credit Reporting System</h3>
        <p>In this project, I created a system to load raw credit data files from various banks and produce comprehensive individual credit reports.</p>
        <p>The system processes CSV files submitted by credit-card institutions, validates data to avoid errors, and generates reports efficiently.</p>
        <p>To achieve this, I implemented data structures including Linked Lists, Stacks, Queues, and Hash Tables for effective data retrieval, sorting, and reporting.</p>
      </div>
    </div>
  </section>

</body>
</html>



