<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        section {
            padding: 2em;
            max-width: 800px;
            margin: auto;
        }
        h2 {
            border-bottom: 2px solid #333;
            padding-bottom: 0.5em;
        }
        a {
            color: #007bff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        form label {
            display: block;
            margin-bottom: 0.5em;
        }
        form input, form textarea {
            width: 100%;
            padding: 0.5em;
            margin-bottom: 1em;
            border: 1px solid #ccc;
        }
        form button {
            background-color: #007bff;
            color: white;
            padding: 0.7em 1em;
            border: none;
            cursor: pointer;
        }
        footer {
            text-align: center;
            padding: 1em 0;
            background-color: #f0f0f0;
        }
    </style>
</head>
<body>

    <header>
        <h1>My Personal Portfolio</h1>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I'm a passionate developer with a strong interest in building innovative and user-friendly applications. I'm driven by the desire to learn new technologies and solve challenging problems. I enjoy the creative process of turning ideas into functional software, and I'm always looking for opportunities to expand my skills and contribute to meaningful projects.</p>
    </section>

    <section id="languages">
        <h2>Programming Languages</h2>
        <ul>
            <li>Python</li>
            <li>JavaScript</li>
            <li>SQL</li>
            <li>HTML/CSS</li>
        </ul>
    </section>

    <section id="education">
        <h2>Educational Background</h2>
        <p>Bachelor of Science in Computer Science, University of Example, 2020-2024.</p>
        <p><a href="path/to/your/cv.pdf" download>Download CV</a></p>
    </section>

    <section id="interests">
        <h2>Interests</h2>
        <p>I'm particularly interested in web development, data science, and artificial intelligence. I enjoy exploring new frameworks and libraries, and I'm always eager to learn about the latest trends in the tech industry. I also have a keen interest in contributing to open-source projects and collaborating with other developers.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <ul>
            <li>
                <a href="https://example.com/project1">Project 1: Web Application</a> - A web application built using Python and Flask.
            </li>
            <li>
                <a href="https://example.com/project2">Project 2: Data Analysis Project</a> - A data analysis project using Python and Pandas.
            </li>
            <li>
                <a href="https://example.com/project3">Project 3: JavaScript Game</a> - A simple game built with JavaScript and HTML5 Canvas.
            </li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form action="mailto:your.email@example.com" method="post" enctype="text/plain">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 My Portfolio</p>
    </footer>

</body>
</html>
