<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Jesika Narvariya | Portfolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', sans-serif;
        }

        body {
            background-color: #f4f6f9;
            color: #333;
        }

        header {
            background-color: #0d1b2a;
            color: white;
            padding: 40px 20px;
            text-align: center;
        }

        header h1 {
            font-size: 36px;
        }

        header p {
            font-size: 18px;
            margin-top: 10px;
            opacity: 0.9;
        }

        nav {
            margin-top: 15px;
        }

        nav a {
            color: #1cc88a;
            text-decoration: none;
            margin: 0 15px;
            font-weight: 500;
        }

        section {
            max-width: 900px;
            margin: 50px auto;
            padding: 20px;
        }

        h2 {
            color: #0d1b2a;
            margin-bottom: 15px;
            border-left: 4px solid #1cc88a;
            padding-left: 10px;
        }

        .card {
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
            margin-bottom: 30px;
        }

        .skills-list {
            display: flex;
            flex-wrap: wrap;
            gap: 12px;
        }

        .skill {
            background: #e9f7f1;
            color: #0d1b2a;
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 14px;
            font-weight: 500;
        }

        .contact a {
            display: inline-block;
            margin-right: 15px;
            margin-top: 10px;
            text-decoration: none;
            background: #0d1b2a;
            color: white;
            padding: 10px 18px;
            border-radius: 5px;
            transition: 0.3s;
        }

        .contact a:hover {
            background: #1cc88a;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #0d1b2a;
            color: white;
            margin-top: 40px;
        }
    </style>
</head>

<body>

<header>
    <h1>Jesika Narvariya</h1>
    <p>Electronics and Communication Engineering Student</p>
    <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section id="about">
    <h2>Professional Summary</h2>
    <div class="card">
        <p>
            I am an Electronics and Communication Engineering student with a strong interest in 
            technology, problem-solving, and innovation. I am passionate about web development 
            and electronics systems. I continuously work on improving my technical skills and 
            aim to contribute effectively to an organization through dedication, adaptability, 
            and a strong learning mindset.
        </p>
    </div>
</section>

<section id="skills">
    <h2>Technical Skills</h2>
    <div class="card">
        <div class="skills-list">
            <div class="skill">HTML</div>
            <div class="skill">CSS</div>
            <div class="skill">JavaScript</div>
            <div class="skill">C Programming</div>
            <div class="skill">Basic Python</div>
            <div class="skill">Electronics Fundamentals</div>
            <div class="skill">Digital Communication</div>
            <div class="skill">Problem Solving</div>
        </div>
    </div>
</section>

<section id="contact">
    <h2>Contact Information</h2>
    <div class="card contact">
        <p><strong>Email:</strong> jesikan001@gmail.com</p>
        <a href="mailto:jesikan001@gmail.com">Send Email</a>
        <a href="https://www.linkedin.com/in/Jesika Narvariya" target="_blank">LinkedIn</a>
        <a href="https://github.com/jesikanarvariya21" target="_blank">GitHub</a>
    </div>
</section>

<footer>
    © 2026 Jesika Narvariya | Portfolio Website
</footer>

</body>
</html>