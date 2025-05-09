<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css" />
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Brief introduction and your background.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project Title</h3>
            <p>Description of the project.</p>
            <a href="https://github.com/yourusername/project">View Code</a>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: your.email@example.com</p>
        <p>LinkedIn: <a href="https://linkedin.com/in/yourprofile">Your Profile</a></p>
    </section>

    <footer>
        <p>&copy; 2025 Your Name</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>


---

3. CSS (style.css)

body {
    font-family: Arial, sans-serif;
    margin: 0;
    line-height: 1.6;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem 2rem;
    text-align: center;
}

nav a {
    color: #fff;
    margin: 0 1rem;
    text-decoration: none;
}

section {
    padding: 2rem;
}

.project {
    background: #f4f4f4;
    padding: 1rem;
    margin-bottom: 1rem;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem;
}



