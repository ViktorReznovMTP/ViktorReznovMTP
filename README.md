<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Viktor Galuh MT. Panditha Reznov - Web Developer</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            background-color: #0D1117;
            color: #ffffff;
            font-family: 'JetBrains Mono', 'Courier New', monospace;
            line-height: 1.6;
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .container {
            background: linear-gradient(135deg, #0D1117 0%, #161B22 100%);
            border: 1px solid #30363d;
            border-radius: 10px;
            padding: 30px;
            margin: 20px 0;
        }
        
        .header {
            text-align: center;
            padding: 40px 20px;
            border-bottom: 2px solid #00ff00;
            margin-bottom: 30px;
        }
        
        .gif-container {
            margin: 20px 0;
        }
        
        .gif-container img {
            max-width: 200px;
            border-radius: 10px;
            border: 2px solid #00ff00;
        }
        
        .terminal {
            background-color: #000000;
            border: 1px solid #00ff00;
            border-radius: 5px;
            padding: 20px;
            margin: 20px 0;
            font-family: 'Courier New', monospace;
        }
        
        .command {
            color: #00ff00;
        }
        
        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin: 20px 0;
        }
        
        .badge {
            display: inline-block;
            padding: 8px 16px;
            background-color: #161B22;
            border: 1px solid #30363d;
            border-radius: 5px;
            font-size: 14px;
            margin: 5px;
        }
        
        .project {
            background-color: #161B22;
            border: 1px solid #30363d;
            border-radius: 8px;
            padding: 20px;
            margin: 15px 0;
        }
        
        .project h3 {
            color: #00ff00;
            margin-bottom: 10px;
        }
        
        .stats-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }
        
        .stat-box {
            background-color: #161B22;
            border: 1px solid #30363d;
            border-radius: 8px;
            padding: 20px;
            text-align: center;
        }
        
        .contact-links {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
            margin: 30px 0;
        }
        
        .contact-btn {
            display: inline-block;
            padding: 12px 24px;
            background-color: #161B22;
            border: 1px solid #00ff00;
            border-radius: 5px;
            color: #00ff00;
            text-decoration: none;
            transition: all 0.3s ease;
        }
        
        .contact-btn:hover {
            background-color: #00ff00;
            color: #000000;
        }
        
        h1, h2, h3 {
            color: #00ff00;
            margin: 20px 0 10px 0;
        }
        
        h1 {
            font-size: 2.5em;
            text-align: center;
        }
        
        h2 {
            font-size: 1.8em;
            border-bottom: 1px solid #30363d;
            padding-bottom: 10px;
        }
        
        code {
            background-color: #000000;
            color: #00ff00;
            padding: 2px 6px;
            border-radius: 3px;
            font-family: 'Courier New', monospace;
        }
        
        pre {
            background-color: #000000;
            border: 1px solid #30363d;
            border-radius: 5px;
            padding: 15px;
            overflow-x: auto;
            margin: 15px 0;
        }
        
        .footer {
            text-align: center;
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid #30363d;
            color: #8b949e;
        }
        
        @media (max-width: 768px) {
            body {
                padding: 10px;
            }
            
            .container {
                padding: 15px;
            }
            
            h1 {
                font-size: 2em;
            }
            
            .stats-container {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header Section -->
        <div class="header">
            <h1>🖥 Viktor Galuh MT. Panditha Reznov</h1>
            <div class="gif-container">
                <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" alt="Matrix Code" width="200">
            </div>
            <p style="font-size: 1.2em; margin: 20px 0;">
                <strong>Junior Web Developer | Dark Theme Enthusiast | Code Alchemist</strong>
            </p>
            <div class="terminal">
                <span class="command">$ whoami</span><br>
                Viktor Galuh MT. Panditha Reznov - Building Digital Experiences With Precision
            </div>
        </div>

        <!-- Mission Statement -->
        <h2>🎯 // Mission Statement</h2>
        <div class="terminal">
            <pre><code>const developer = {
  code: ["PHP", "JavaScript", "HTML", "CSS", "SQL"],
  tools: ["Laravel", "Bootstrap", "MySQL", "Git"],
  architecture: ["MVC", "RESTful APIs", "Responsive Design"],
  philosophy: "Build it right, or don't build it at all",
  currentFocus: "Mastering Laravel Ecosystem & OOP Principles",
  status: "AlwaysLearning()"
};</code></pre>
        </div>

        <!-- Tech Stack -->
        <h2>⚡ Tech Arsenal</h2>
        
        <h3>Frontend Operations</h3>
        <div class="tech-stack">
            <span class="badge">HTML5</span>
            <span class="badge">CSS3</span>
            <span class="badge">JavaScript</span>
            <span class="badge">Bootstrap</span>
        </div>

        <h3>Backend Systems</h3>
        <div class="tech-stack">
            <span class="badge">PHP</span>
            <span class="badge">Laravel</span>
            <span class="badge">MySQL</span>
        </div>

        <h3>Development Environment</h3>
        <div class="tech-stack">
            <span class="badge">VS Code</span>
            <span class="badge">Git</span>
            <span class="badge">Figma</span>
        </div>

        <!-- Projects -->
        <h2>🚀 Active Missions</h2>
        
        <div class="project">
            <h3>[CLASSIFIED] SkyAntara Airlines</h3>
            <p><strong>Airline Ticket Reservation System</strong></p>
            <div class="terminal">
                <code>Status: OPERATIONAL</code><br>
                <code>Tech Stack: Laravel • MySQL • Bootstrap • Blade</code><br>
                <code>Access: https://github.com/ViktorReznovMTP/airline</code>
            </div>
        </div>

        <div class="project">
            <h3>[CONFIDENTIAL] SuaraKita Voting System</h3>
            <p><strong>School Election Quick-Count Platform</strong></p>
            <div class="terminal">
                <code>Status: DEPLOYED</code><br>
                <code>Tech Stack: PHP • MySQL • JavaScript • CSS3</code><br>
                <code>Access: https://github.com/hanakhaii/SuaraKita</code>
            </div>
        </div>

        <div class="project">
            <h3>[RESTRICTED] ArcadiaBook Management</h3>
            <p><strong>Library Management System</strong></p>
            <div class="terminal">
                <code>Status: ACTIVE</code><br>
                <code>Tech Stack: PHP • MySQL • HTML5 • CSS3</code><br>
                <code>Access: https://github.com/hanakhaii/arcadiabooks</code>
            </div>
        </div>

        <!-- GitHub Stats -->
        <h2>📊 System Analytics</h2>
        <div class="stats-container">
            <div class="stat-box">
                <h3>GitHub Stats</h3>
                <img src="https://github-readme-stats.vercel.app/api?username=ViktorReznovMTP&show_icons=true&theme=react-dark&hide_border=true&bg_color=0D1117&title_color=00ff00&icon_color=00ff00&text_color=ffffff" alt="GitHub Stats">
            </div>
            <div class="stat-box">
                <h3>Top Languages</h3>
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ViktorReznovMTP&layout=compact&theme=react-dark&hide_border=true&bg_color=0D1117&title_color=00ff00&text_color=ffffff" alt="Top Languages">
            </div>
        </div>

        <!-- Developer Console -->
        <h2>🎮 Developer Console</h2>
        <div class="terminal">
            <code># Current Session</code><br>
            <code>$ git status</code><br>
            <code>On branch main</code><br>
            <code>Working tree clean</code><br><br>
            
            <code>$ node current-projects.js</code><br>
            <code>→ Building scalable web applications</code><br>
            <code>→ Learning advanced Laravel patterns</code><br>
            <code>→ Mastering API development</code><br><br>
            
            <code>$ ./deploy-new-skills.sh</code><br>
            <code>Deploying: Advanced OOP, System Architecture, UI/UX Principles</code>
        </div>

        <!-- Contact -->
        <h2>📡 Establish Connection</h2>
        <div class="contact-links">
            <a href="mailto:galuhmtp1606@gmail.com" class="contact-btn">📧 ENCRYPTED MAIL</a>
            <a href="https://www.linkedin.com/in/galuh-maheswara-tahta-panditha-31aa15340/" class="contact-btn">💼 PROFESSIONAL NETWORK</a>
            <a href="https://instagram.com/galu_h16" class="contact-btn">📱 DIGITAL FOOTPRINT</a>
        </div>

        <!-- System Status -->
        <h2>🔒 System Status</h2>
        <div class="terminal">
            <pre><code>// SYSTEM DIAGNOSTICS
struct DeveloperStatus {
    availability: Status::AvailableForCollaboration,
    learning_curve: Status::Steep,
    project_capacity: Status::AcceptingChallenges,
    coffee_level: Status::Optimal,
    last_update: Timestamp::Now,
}

impl DeveloperStatus {
    fn new() -> Self {
        Self {
            availability: Status::AvailableForCollaboration,
            learning_curve: Status::Steep,
            project_capacity: Status::AcceptingChallenges,
            coffee_level: Status::Optimal,
            last_update: Timestamp::Now,
        }
    }
    
    fn collaborate(&self) -> ProjectResult {
        ProjectResult::Success
    }
}</code></pre>
        </div>

        <!-- Footer -->
        <div class="footer">
            <p>"Code doesn't lie. Comments sometimes do." - Ron Jeffries</p>
            <p><strong>© 2024 Viktor G.M.T.P.R. | SYSTEMS ONLINE</strong></p>
            <div style="margin-top: 20px;">
                <img src="https://komarev.com/ghpvc/?username=ViktorReznovMTP&color=00ff00&style=flat-square&label=TERMINAL+ACCESSES" alt="Visitor Count">
            </div>
        </div>
    </div>
</body>
</html>
