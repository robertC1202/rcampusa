# Robert Campusano
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Robert Campusano - Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <style>
        html {
            scroll-behavior: smooth;
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-900">
    <!-- Navigation -->
    <nav class="bg-blue-600 text-white p-4 fixed w-full top-0 z-50">
        <div class="container mx-auto flex justify-between items-center">
            <div class="text-xl font-bold">Robert Campusano</div>
            <div class="space-x-4">
                <a href="#home" class="hover:text-blue-200">Home</a>
                <a href="#about" class="hover:text-blue-200">About</a>
                <a href="#resume" class="hover:text-blue-200">Resume</a>
                <a href="#work" class="hover:text-blue-200">My Work</a>
            </div>
        </div>
    </nav>

    <!-- Home Section -->
    <section id="home" class="h-screen flex items-center justify-center bg-gradient-to-br from-blue-500 to-purple-600 text-white pt-16">
        <div class="text-center">
            <h1 class="text-5xl font-bold mb-4">Robert Campusano</h1>
            <p class="text-xl">Computer Science Student | Software Developer | Game Programmer</p>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-10">About Me</h2>
            <div class="max-w-2xl mx-auto text-center">
                <p class="text-lg">
                    Hi, I'm Robert Campusano, a junior computer scientist at George Mason University. I'm passionate about software development, data structures, and game programming, and I have hands-on experience with languages such as Java, C#, and Python.
                </p>
            </div>
        </div>
    </section>

    <!-- Resume Section -->
    <section id="resume" class="py-20 bg-gray-100">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-10">Resume</h2>
            <div class="max-w-4xl mx-auto bg-white p-8 rounded-lg shadow-md">
                <h3 class="text-2xl font-semibold mb-4">Robert Campusano</h3>
                <p>Arlington, VA 22204 | rcampusa@gmu.edu | (571) 634-0735</p>
                
                <h4 class="text-xl font-bold mt-6 mb-4">Education</h4>
                <div>
                    <p class="font-semibold">George Mason University - College of Engineering and Computing</p>
                    <p>Bachelor of Science Computer Science, Expected May 2026</p>
                    <p>GPA: 3.7</p>
                </div>
                <div class="mt-4">
                    <p class="font-semibold">Northern Virginia Community College</p>
                    <p>Associate Degree in Computer Science, May 2024</p>
                    <p>Magna Cum Laude, GPA: 3.7</p>
                </div>

                <h4 class="text-xl font-bold mt-6 mb-4">Skills</h4>
                <ul class="list-disc list-inside">
                    <li>Programming Languages: Java, Python, C</li>
                    <li>Technical Skills: Data Structures & Algorithms</li>
                    <li>Tools: Microsoft Word, Office, Teams, Excel</li>
                    <li>Language Proficiency: Spanish</li>
                </ul>

                <a href="Robert_Campusano_Resume.pdf" download class="inline-block mt-6 bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">
                    Download Full Resume
                </a>
            </div>
        </div>
    </section>

    <!-- Work Section -->
    <section id="work" class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-10">My Projects</h2>
            
            <div class="max-w-4xl mx-auto space-y-8">
                <div class="bg-gray-100 p-6 rounded-lg shadow-md">
                    <h3 class="text-2xl font-semibold mb-4">Unity Game Prototype</h3>
                    <div class="grid md:grid-cols-2 gap-4">
                        <div>
                            <p class="mb-4">I collaborated with classmates to develop a game prototype using Unity and C#.</p>
                            <div class="space-y-2">
                                <img src="duck-souls-title.png" alt="Duck Souls Game Title" class="w-full rounded-lg">
                                <img src="game-prototype-screenshot.png" alt="Game Prototype Screenshot" class="w-full rounded-lg">
                            </div>
                        </div>
                        <div>
                            <h4 class="text-xl font-bold mb-2">Game Screenshots</h4>
                            <p>These images showcase the game prototype, highlighting the unique pixel art style and game environment.</p>
                        </div>
                    </div>
                </div>

                <div class="bg-gray-100 p-6 rounded-lg shadow-md">
                    <h3 class="text-2xl font-semibold mb-4">Credit Reporting System</h3>
                    <p>In this project, I created a system to load raw credit data files from various banks and produce comprehensive individual credit reports.</p>
                    <p class="mt-2">The system processes CSV files submitted by credit-card institutions, validates data to avoid errors, and generates reports efficiently.</p>
                    <p class="mt-2">To achieve this, I implemented data structures including Linked Lists, Stacks, Queues, and Hash Tables for effective data retrieval, sorting, and reporting.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-6">
        <div class="container mx-auto text-center">
            <p>&copy; 2025 Robert Campusano. All Rights Reserved.</p>
            <div class="mt-4 space-x-4">
                <a href="mailto:rcampusa@gmu.edu" class="hover:text-blue-400">Email</a>
                <a href="https://github.com/robertC1202" target="_blank" class="hover:text-blue-400">GitHub</a>
            </div>
        </div>
    </footer>
</body>
</html>

