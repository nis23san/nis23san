<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Nisarga NS | Java Full Stack Developer</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: "Segoe UI", sans-serif;
            background: #f2f4f8;
            color: #333;
            animation: fadeIn 1.2s ease-in;
        }

        /* Header */
        header {
            background: linear-gradient(270deg, #1e88e5, #42a5f5);
            background-size: 400% 400%;
            color: white;
            padding: 40px 20px;
            text-align: center;
            animation: gradientMove 8s ease infinite;
        }

        header h1 {
            font-size: 2.5rem;
        }

        header p {
            margin-top: 10px;
            font-size: 1.2rem;
            opacity: 0.9;
        }

        /* Container */
        .container {
            max-width: 900px;
            margin: auto;
            padding: 30px;
        }

        /* Sections */
        .section {
            background: white;
            padding: 25px;
            margin-bottom: 25px;
            border-radius: 10px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.05);
            animation: slideUp 1s ease forwards;
            opacity: 0;
        }

        .section:nth-child(1) { animation-delay: 0.2s; }
        .section:nth-child(2) { animation-delay: 0.4s; }
        .section:nth-child(3) { animation-delay: 0.6s; }
        .section:nth-child(4) { animation-delay: 0.8s; }
        .section:nth-child(5) { animation-delay: 1s; }

        .section h2 {
            margin-bottom: 15px;
            color: #1e88e5;
        }

        ul {
            line-height: 1.8;
            padding-left: 20px;
        }

        /* Skills badges */
        .skills span {
            display: inline-block;
            background: #e3f2fd;
            color: #1e88e5;
            padding: 8px 12px;
            margin: 6px;
            border-radius: 20px;
            font-size: 14px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .skills span:hover {
            transform: translateY(-4px);
            box-shadow: 0 6px 15px rgba(0,0,0,0.15);
        }

        /* Links */
        a {
            color: #1e88e5;
            text-decoration: none;
            font-weight: 500;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px;
            color: #777;
            font-size: 14px;
        }

        /* Animations */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes slideUp {
            from {
                transform: translateY(30px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        @keyframes gradientMove {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
    </style>
</head>

<body>

<header>
    <h1>Nisarga NS</h1>
    <p>Java Full Stack Developer | BE Graduate 2026</p>
</header>

<div class="container">

    <div class="section">
        <h2>About Me</h2>
        <p>
            I am a BE graduate (2026) and a Java Full Stack Developer Intern at <b>JSpiders</b>.
            Passionate about developing scalable web applications using Java, Spring Boot,
            and modern frontend technologies.
        </p>
    </div>

    <div class="section">
        <h2>Technical Skills</h2>
        <div class="skills">
            <span>Java</span>
            <span>Spring Boot</span>
            <span>Hibernate</span>
            <span>REST APIs</span>
            <span>HTML</span>
            <span>CSS</span>
            <span>JavaScript</span>
            <span>React</span>
            <span>Oracle SQL</span>
            <span>MySQL</span>
            <span>Git & GitHub</span>
            <span>Postman</span>
        </div>
    </div>

    <div class="section">
        <h2>Projects</h2>
        <ul>
            <li><b>My Art Gallery</b> – Web Technologies (only HTML5)</li>
        </ul>
    </div>

    <div class="section">
        <h2>Internship</h2>
        <p>
            <b>Java Full Stack Developer Intern – JSpiders</b><br>
            Worked on backend API development, frontend integration,
            and database operations using industry practices.
        </p>
    </div>

    <div class="section">
        <h2>Contact</h2>
        <p>
            📧 Email: yourmail@gmail.com <br>
            💼 LinkedIn:
            <a href="https://linkedin.com/in/yourlinkedin">linkedin.com/in/yourlinkedin</a><br>
            🐙 GitHub:
            <a href="https://github.com/yourusername">github.com/yourusername</a>
        </p>
    </div>

</div>

<footer>
    © 2026 Nisarga NS | Java Full Stack Developer
</footer>

</body>
</html>
