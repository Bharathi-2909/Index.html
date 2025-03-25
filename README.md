<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bharathi K - Web Developer</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        .header {
            background-color: #a0d911;
            text-align: center;
            padding: 30px;
            font-size: 24px;
            font-weight: bold;
            color: white;
        }
        .header p {
            font-size: 16px;
            font-weight: normal;
        }
        .nav {
            background-color: #c70039;
            padding: 10px;
            text-align: center;
        }
        .nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            display: inline-block;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        .section {
            background: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 8px;
            box-shadow: 0px 0px 10px #ccc;
        }
        .resume-btn {
            display: block;
            width: 200px;
            margin: 20px auto;
            text-align: center;
            padding: 10px;
            background: black;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>Bharathi K</h1>
        <p>Web Developer</p>
    </div>

    <div class="nav">
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#resume">Resume</a>
    </div>

    <div class="container">
        
        <div id="about" class="section">
            <h2>About Me</h2>
            <p>I am currently pursuing my degree and have a passion for web development.</p>
        </div>

        <div id="education" class="section">
            <h2>Education</h2>
            <p>Madras University, BCA</p>
        </div>

        <div id="skills" class="section">
            <h2>Skills</h2>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>Python</li>
                <li>React.js</li>
            </ul>
        </div>

        <div id="projects" class="section">
            <h2>Projects</h2>
            <ul>
                <li>Hangman Game Program</li>
                <li>Digital Portfolio</li>
            </ul>
        </div>

        <div id="resume" class="section">
            <h2>Resume</h2>
            <a href="#" class="resume-btn">Download CV</a>
        </div>

    </div>

    <footer style="text-align:center; padding:20px; background:#c70039; color:white;">
        © 2024 Bharathi K
    </footer>

</body>
</html>
