
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sharda Yadav - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to right, #e3f2fd, #bbdefb);
            color: #333;
        }
        header {
            background: linear-gradient(135deg, #1e3c72, #2a5298);
            color: #fff;
            padding: 100px 20px 60px;
            text-align: center;
            position: relative;
        }
        .profile-pic {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            position: absolute;
            top: 20px;
            left: 50%;
            transform: translateX(-50%);
            border: 4px solid #fff;
        }
        header h1 {
            font-size: 3em;
            margin-top: 160px;
        }
        header h2 {
            font-size: 1.5em;
            margin-top: 15px;
        }
        .container {
            max-width: 1100px;
            margin: 30px auto;
            background: #fff;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
        }
        .section-title {
            text-align: center;
            font-size: 2em;
            margin-bottom: 20px;
            color: #1e3c72;
        }
        .project, .skills {
            border: 1px solid #ddd;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 15px;
            background: #f9f9f9;
            transition: 0.3s;
        }
        .project:hover, .skills:hover {
            transform: scale(1.02);
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }
        .skills {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .skill {
            margin: 8px;
            padding: 10px 18px;
            background: #1e3c72;
            color: white;
            border-radius: 5px;
            font-weight: bold;
        }
        footer {
            background: #1e3c72;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
            font-size: 1.1em;
        }
    </style>
</head>
<body>
    <header>
        <img src="profile.jpg" alt="Sharda Yadav" class="profile-pic">
        <h1>Sharda Yadav</h1>
        <h2>Backend Developer | Problem Solver</h2>
    </header>

    <div class="container">
        <h3 class="section-title">Profile Summary</h3>
        <p>Passionate Backend Developer with a strong background in programming, problem-solving, and software development. Proficient in modern backend technologies with a keen interest in scalable and efficient software solutions.</p>

        <h3 class="section-title">Academic Projects</h3>
        <div class="project">
            <h3>Jarvis Automation</h3>
            <p><strong>Tools:</strong> Python, Speech Recognition, WebDriver, OS</p>
            <p>Developed an AI assistant for automating daily system tasks efficiently.</p>
        </div>
        <div class="project">
            <h3>Security Camera</h3>
            <p><strong>Tools:</strong> Python, OpenCV, Facial Recognition</p>
            <p>Built a security system that detects intruders and alerts the user.</p>
        </div>

        <h3 class="section-title">Technical Skills</h3>
        <div class="skills">
            <div class="skill">Java</div>
            <div class="skill">Python</div>
            <div class="skill">Go</div>
            <div class="skill">SQL</div>
            <div class="skill">MySQL</div>
            <div class="skill">Data Structures</div>
            <div class="skill">Agile Development</div>
            <div class="skill">Debugging</div>
        </div>

        <h3 class="section-title">Contact</h3>
        <p>Email: <a href="mailto:sharda9696018592@gmail.com">sharda9696018592@gmail.com</a></p>
        <p>Phone: 8726701002</p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/sharda-yadav-713925272">Sharda Yadav</a></p>
    </div>

    <footer>
        <p>&copy; 2024 Sharda Yadav | All Rights Reserved</p>
    </footer>
</body>
</html>
