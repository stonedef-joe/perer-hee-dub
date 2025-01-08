<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        nav {
            margin: 1em;
            text-align: center;
        }
        nav a {
            margin: 0 1em;
            text-decoration: none;
            color: #4CAF50;
        }
        main {
            padding: 2em;
        }
        section {
            margin-bottom: 2em;
        }
        footer {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
    </header>
    <nav>
        <a href="#projects">Projects</a>
        <a href="#resume">Resume</a>
        <a href="#contact">Contact</a>
    </nav>
    <main>
        <section id="projects">
            <h2>My Projects</h2>
            <p>Here are some of my recent projects:</p>
            <ul>
                <li>Project 1: <a href="link-to-project-1">View Project</a></li>
                <li>Project 2: <a href="link-to-project-2">View Project</a></li>
                <li>Project 3: <a href="link-to-project-3">View Project</a></li>
            </ul>
        </section>
        <section id="resume">
            <h2>My Resume</h2>
            <p>You can view my resume <a href="link-to-resume.pdf">here</a>.</p>
        </section>
        <section id="contact">
            <h2>Contact Me</h2>
            <p>If you would like to get in touch, please email me at <a href="mailto:your-email@example.com">your-email@example.com</a></p>
        </section>
    </main>
    <footer>
        &copy; 2025 My Portfolio
    </footer>
</body>
</html>
