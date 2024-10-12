<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile README</title>
    <style>
        body {
            font-family: 'Courier New', Courier, monospace;
            background-color: #300a24;
            color: #ffffff;
            line-height: 1.4;
            padding: 20px;
        }
        .terminal {
            background-color: #300a24;
            border-radius: 5px;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0,0,0,0.5);
        }
        .prompt {
            color: #4e9a06;
        }
        .command {
            color: #ffffff;
        }
        .output {
            color: #eeeeec;
            margin-left: 20px;
        }
        .section {
            margin-bottom: 20px;
        }
        .stats img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <div class="terminal">
        <div class="section">
            <span class="prompt">user@github:~$</span> 
            <span class="command">whois [Your Name]</span>
            <pre class="output">
Name: Nicollas "M1racle" Alcântara
Location: Unknown
Website: https://github.com/niklaz4
            </pre>
        </div>

        <div class="section">
            <span class="prompt">user@github:~$</span> 
            <span class="command">cat education.txt</span>
            <pre class="output">
[Degree] in Computer Science and Information Security 
Uninter and Universidade Cruzeiro do Sul
Graduation Year: 2025

[Degree] in Journalism for Universidade Federal de Ouro Preto [2024]
            </pre>
        </div>

        <div class="section">
            <span class="prompt">user@github:~$</span> 
            <span class="command">ls skills/</span>
            <pre class="output">
[Javascript/React]   [Python]   [Database(SQL, MongoDB, NoSQL)]
[Pentester]   [Application Security]   [CI/CD]
[Cloud]   [Network]   [Intermediary English]
            </pre>
        </div>

        <div class="section">
            <span class="prompt">user@github:~$</span> 
            <span class="command">cat career.txt</span>
            <pre class="output">
Current Role: IT Assistant
Company: Confidential

Area of Expertise: Offensive Security and Application Security

Professional Experience:
1. IT Customer Support at [NUBANK] (2021 - 2023)
2. Application Security Analyst (Volunteer) at Lacrei Saúde (2024-2024)
3. IT Assistant at [CONFIDENTIAL] (2024-)

            </pre>
        </div>

        <div class="section">
            <span class="prompt">user@github:~$</span> 
            <span class="command">github-stats</span>
            <pre class="output">
Fetching latest stats...
            </pre>
            <div class="stats">
                <img src="https://github-readme-stats.vercel.app/api?username=[Your GitHub Username]&show_icons=true&theme=radical" alt="GitHub Stats" />
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=[Your GitHub Username]&layout=compact&theme=radical" alt="Top Languages" />
            </div>
        </div>
    </div>
</body>
</html>
