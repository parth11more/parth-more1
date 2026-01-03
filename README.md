# parth-more1
Build the Basic Structure (HTML) 1. Create an Index.html File:  Inside your project folder, create a new file called index.html. This file will be the main page of your website.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css"> <!-- Link to your CSS file -->
</head>
<body>
    <header>
        <h1>John Doe</h1>
        <p>Web Developer | Programmer</p>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>Brief introduction about yourself, your skills, and your interests.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Weather App</h3>
            <p>Description of the project</p>
            <a href="https://github.com/yourusername/weather-app">View on GitHub</a>
        </div>
        <!-- Add more projects here -->
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: johndoe@example.com</p>
        <p>LinkedIn: <a href="https://linkedin.com/in/johndoe">linkedin.com/in/johndoe</a></p>
    </section>

    <footer>
        <p>&copy; 2026 John Doe</p>
    </footer>
</body>
</html>
