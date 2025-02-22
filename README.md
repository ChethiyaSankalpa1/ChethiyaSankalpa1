# Hi there 👋 I'm Chethiya Sankalpa

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Chethiya Sankalpa | GitHub Profile</title>
    <style>
        :root {
            --primary-color: #2d2d2d;
            --secondary-color: #58a6ff;
            --bg-color: #0d1117;
        }

        body {
            font-family: 'Segoe UI', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: var(--bg-color);
            color: #c9d1d9;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
        }

        .header {
            text-align: center;
            margin-bottom: 40px;
        }

        .stats-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
        }

        .badge-container {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin: 20px 0;
        }

        .badge {
            padding: 6px 12px;
            border-radius: 4px;
            font-size: 0.9em;
            background: var(--primary-color);
            color: white;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 5px;
        }

        .badge img {
            height: 16px;
        }

        .projects-table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }

        .projects-table th, .projects-table td {
            border: 1px solid #30363d;
            padding: 12px;
            text-align: left;
        }

        .contact-buttons {
            display: flex;
            gap: 15px;
            margin-top: 30px;
            flex-wrap: wrap;
        }

        .contact-button {
            padding: 10px 20px;
            border-radius: 6px;
            text-decoration: none;
            font-weight: 500;
            transition: transform 0.2s;
        }

        .linkedin { background: #0A66C2; color: white; }
        .portfolio { background: #000000; color: white; }
        .email { background: #EA4335; color: white; }
        .twitter { background: #1DA1F2; color: white; }
    </style>
</head>
<body>
    <div class="container">
        <header class="header">
            <h1>👋 Hi there! I'm Chethiya Sankalpa</h1>
            <div class="stats-container">
                <img src="https://github-readme-stats.vercel.app/api?username=chethiyasankalpa&show_icons=true&theme=dark" alt="GitHub Stats">
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=chethiyasankalpa&layout=compact&theme=dark" alt="Top Languages">
            </div>
        </header>

        <section>
            <h2>🚀 About Me</h2>
            <ul>
                <li>🔭 Currently working on AI-powered applications</li>
                <li>🌱 Learning Cloud Architecture & DevOps</li>
                <li>👯 Looking to collaborate on innovative projects</li>
                <li>⚡ Fun fact: I automate everything I can!</li>
            </ul>
        </section>

        <section>
            <h2>🛠️ Tech Stack</h2>
            <div class="badge-container">
                <!-- Frontend -->
                <a class="badge"><img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white"> HTML5</a>
                <a class="badge"><img src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white"> CSS3</a>
                <a class="badge"><img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black"> JavaScript</a>
                <a class="badge"><img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black"> React</a>
                
                <!-- Backend -->
                <a class="badge"><img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white"> Python</a>
                <a class="badge"><img src="https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white"> Node.js</a>
                
                <!-- Databases -->
                <a class="badge"><img src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white"> MySQL</a>
                <a class="badge"><img src="https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white"> MongoDB</a>
            </div>
        </section>

        <section>
            <h2>🌟 Featured Projects</h2>
            <table class="projects-table">
                <tr>
                    <th>Project</th>
                    <th>Description</th>
                    <th>Tech Stack</th>
                </tr>
                <tr>
                    <td><a href="#">AI Chatbot</a></td>
                    <td>Intelligent conversational agent</td>
                    <td>Python, TensorFlow, Flask</td>
                </tr>
                <tr>
                    <td><a href="#">E-commerce Platform</a></td>
                    <td>Full-stack shopping solution</td>
                    <td>React, Node.js, MongoDB</td>
                </tr>
            </table>
        </section>

        <section>
            <h2>🤝 Connect With Me</h2>
            <div class="contact-buttons">
                <a href="#" class="contact-button linkedin">LinkedIn</a>
                <a href="#" class="contact-button portfolio">Portfolio</a>
                <a href="mailto:your@email.com" class="contact-button email">Email</a>
                <a href="#" class="contact-button twitter">Twitter</a>
            </div>
        </section>

        <footer style="margin-top: 50px; text-align: center;">
            <p>⭐ From <a href="https://github.com/chethiyasankalpa">chethiyasankalpa</a></p>
            <img src="https://profile-counter.glitch.me/chethiyasankalpa/count.svg" alt="Visitor Counter">
        </footer>
    </div>
</body>
</html>
