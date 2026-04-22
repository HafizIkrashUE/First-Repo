<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: #f4f7fb;
            color: #333;
        }

        /* Navbar */
        nav {
            background: #222;
            color: white;
            padding: 15px 50px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav h2 {
            color: #4facfe;
        }

        nav ul {
            list-style: none;
            display: flex;
        }

        nav ul li {
            margin-left: 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            transition: 0.3s;
        }

        nav ul li a:hover {
            color: #4facfe;
        }

        /* Hero Section */
        .hero {
            height: 90vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            background: linear-gradient(135deg, #4facfe, #00f2fe);
            color: white;
        }

        .hero h1 {
            font-size: 48px;
        }

        .hero p {
            margin: 15px 0;
            font-size: 20px;
        }

        .hero button {
            padding: 10px 20px;
            border: none;
            background: white;
            color: #333;
            border-radius: 5px;
            cursor: pointer;
            transition: 0.3s;
        }

        .hero button:hover {
            background: #222;
            color: white;
        }

        /* Section */
        section {
            padding: 60px 50px;
            text-align: center;
        }

        h2 {
            margin-bottom: 20px;
            color: #4facfe;
        }

        /* About */
        .about p {
            max-width: 600px;
            margin: auto;
        }

        /* Skills */
        .skills .box {
            display: inline-block;
            padding: 15px 25px;
            margin: 10px;
            background: #4facfe;
            color: white;
            border-radius: 20px;
        }

        /* Projects */
        .projects .card {
            display: inline-block;
            width: 250px;
            margin: 15px;
            padding: 20px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        .projects .card h3 {
            margin-bottom: 10px;
        }

        /* Contact */
        .contact input, .contact textarea {
            width: 80%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }

        .contact button {
            padding: 10px 20px;
            border: none;
            background: #4facfe;
            color: white;
            border-radius: 5px;
            cursor: pointer;
        }

        .contact button:hover {
            background: #007bff;
        }

        /* Footer */
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 15px;
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <nav>
        <h2>MyPortfolio</h2>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Hero -->
    <div class="hero">
        <div>
            <h1>Hi, I'm Your Name</h1>
            <p>Web Developer | Student | Programmer</p>
            <button>View My Work</button>
        </div>
    </div>

    <!-- About -->
    <section id="about" class="about">
        <h2>About Me</h2>
        <p>
            I am a passionate developer who loves building websites and learning new technologies.
            Currently studying and improving my skills in web development.
        </p>
    </section>

    <!-- Skills -->
    <section id="skills" class="skills">
        <h2>My Skills</h2>
        <div class="box">HTML</div>
        <div class="box">CSS</div>
        <div class="box">JavaScript</div>
        <div class="box">C++</div>
    </section>

    <!-- Projects -->
    <section id="projects" class="projects">
        <h2>Projects</h2>
        <div class="card">
            <h3>Project 1</h3>
            <p>Online Voting System</p>
        </div>
        <div class="card">
            <h3>Project 2</h3>
            <p>Student Database System</p>
        </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="contact">
        <h2>Contact Me</h2>
        <input type="text" placeholder="Your Name"><br>
        <input type="email" placeholder="Your Email"><br>
        <textarea rows="4" placeholder="Your Message"></textarea><br>
        <button>Send Message</button>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 Your Name | All Rights Reserved</p>
    </footer>

</body>
</html>
