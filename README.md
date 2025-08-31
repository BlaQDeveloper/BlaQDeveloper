<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Maduemezia Ikechukwu David - Frontend Developer</title>
    <style>
        :root {
            --primary-color: #4a6fa5;
            --secondary-color: #6b8cae;
            --accent-color: #5d7592;
            --text-color: #333;
            --light-bg: #f8f9fa;
            --dark-bg: #343a40;
            --transition: all 0.3s ease;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--light-bg);
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            text-align: center;
            padding: 2rem 0;
            margin-bottom: 2rem;
            border-bottom: 1px solid #eaeaea;
        }
        
        h1 {
            color: var(--primary-color);
            margin-bottom: 0.5rem;
        }
        
        h2 {
            color: var(--secondary-color);
            margin: 1.5rem 0 1rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid var(--accent-color);
        }
        
        h3 {
            color: var(--accent-color);
            margin: 1rem 0 0.5rem;
        }
        
        .tagline {
            font-size: 1.2rem;
            color: var(--secondary-color);
            margin-bottom: 1rem;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin: 1rem 0;
        }
        
        .social-links a {
            color: var(--primary-color);
            text-decoration: none;
            transition: var(--transition);
        }
        
        .social-links a:hover {
            color: var(--accent-color);
            text-decoration: underline;
        }
        
        section {
            margin-bottom: 2.5rem;
        }
        
        .about, .skills, .projects, .goals, .contact {
            background: white;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 1rem;
            margin-top: 1rem;
        }
        
        .skill-category {
            background: var(--light-bg);
            padding: 1rem;
            border-radius: 6px;
        }
        
        .skill-category h4 {
            margin-bottom: 0.5rem;
            color: var(--primary-color);
        }
        
        .skill-list {
            list-style-type: none;
        }
        
        .skill-list li {
            padding: 0.2rem 0;
        }
        
        .skill-list li::before {
            content: "▹ ";
            color: var(--accent-color);
        }
        
        .project {
            margin-bottom: 1.5rem;
            padding-bottom: 1.5rem;
            border-bottom: 1px solid #eaeaea;
        }
        
        .project:last-child {
            border-bottom: none;
        }
        
        .project-links {
            display: flex;
            gap: 1rem;
            margin-top: 0.5rem;
        }
        
        .project-links a {
            color: var(--primary-color);
            text-decoration: none;
            transition: var(--transition);
        }
        
        .project-links a:hover {
            color: var(--accent-color);
            text-decoration: underline;
        }
        
        .goals-list {
            list-style-type: none;
        }
        
        .goals-list li {
            margin-bottom: 0.8rem;
            padding-left: 1.5rem;
            position: relative;
        }
        
        .goals-list li::before {
            content: "🎯";
            position: absolute;
            left: 0;
        }
        
        footer {
            text-align: center;
            padding: 2rem 0;
            margin-top: 2rem;
            border-top: 1px solid #eaeaea;
            color: var(--secondary-color);
        }
        
        @media (max-width: 768px) {
            .skills-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Maduemezia Ikechukwu David</h1>
        <p class="tagline">ALX Frontend Program Learner | Mental Health App Developer</p>
        <div class="social-links">
            <a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a> •
            <a href="https://twitter.com/Oracle_Nexora" target="_blank">Twitter</a> •
            <a href="mailto:ikechukwudavid331@gmail.com">Email</a>
        </div>
    </header>

    <main>
        <section class="about">
            <h2>👋 About Me</h2>
            <p>Hello! I'm a frontend developer passionate about building solid, established web applications that make a real difference. My journey into software engineering was inspired by the potential of technology to solve real-world problems, particularly in the mental health space.</p>
            <p>I'm currently enhancing my skills through the ALX Frontend Program, with a specific focus on creating mental healthcare web applications that address the needs of young Africans. I believe in the power of clean, accessible, and user-centered design to create impactful digital experiences.</p>
        </section>

        <section class="skills">
            <h2>🛠️ Technical Skills</h2>
            <div class="skills-grid">
                <div class="skill-category">
                    <h4>Frontend Development</h4>
                    <ul class="skill-list">
                        <li>HTML5 & CSS3</li>
                        <li>JavaScript (ES6+)</li>
                        <li>React.js</li>
                        <li>Responsive Design</li>
                        <li>CSS Preprocessors (SASS)</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h4>Tools & Practices</h4>
                    <ul class="skill-list">
                        <li>Git & GitHub</li>
                        <li>Webpack</li>
                        <li>RESTful APIs</li>
                        <li>UI/UX Principles</li>
                        <li>Agile Methodology</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h4>Learning Next</h4>
                    <ul class="skill-list">
                        <li>TypeScript</li>
                        <li>Next.js</li>
                        <li>Testing (Jest, Cypress)</li>
                        <li>Progressive Web Apps</li>
                        <li>Accessibility Standards</li>
                    </ul>
                </div>
            </div>
        </section>

        <section class="projects">
            <h2>💼 Projects</h2>
            
            <div class="project">
                <h3>MindfulAfrica - Mental Health Platform</h3>
                <p>A web application designed to provide mental health resources and support for young Africans. Features include self-assessment tools, resource library, and community forum.</p>
                <div class="project-links">
                    <a href="https://github.com/yourusername/mindfulafrica" target="_blank">View Code</a>
                    <a href="https://yourusername.github.io/mindfulafrica" target="_blank">Live Demo</a>
                </div>
            </div>
            
            <div class="project">
                <h3>WellnessTracker</h3>
                <p>A mood and wellness tracking application that helps users monitor their mental health journey with visualization tools and personalized insights.</p>
                <div class="project-links">
                    <a href="https://github.com/yourusername/wellnesstracker" target="_blank">View Code</a>
                    <a href="https://yourusername.github.io/wellnesstracker" target="_blank">Live Demo</a>
                </div>
            </div>
            
            <div class="project">
                <h3>CommunityConnect</h3>
                <p>An open-source platform connecting mental health professionals with communities in need across Africa. (In development)</p>
                <div class="project-links">
                    <a href="https://github.com/yourusername/communityconnect" target="_blank">View Code</a>
                    <a href="#">Coming Soon</a>
                </div>
            </div>
        </section>

        <section class="goals">
            <h2>🎯 Goals & Interests</h2>
            <ul class="goals-list">
                <li>Build accessible mental healthcare web applications for young Africans</li>
                <li>Contribute to open-source projects focused on mental health technology</li>
                <li>Develop MVP solutions that can be tested and implemented in real-world scenarios</li>
                <li>Collaborate with healthcare professionals to create effective digital tools</li>
                <li>Mentor other aspiring developers from Africa interested in health tech</li>
            </ul>
        </section>

        <section class="contact">
            <h2>📫 Let's Connect</h2>
            <p>I'm always interested in connecting with fellow developers, mental health advocates, and potential collaborators. Feel free to reach out if you'd like to discuss:</p>
            <ul>
                <li>Open-source projects in the mental health space</li>
                <li>Frontend development opportunities</li>
                <li>Collaborations on African-focused tech solutions</li>
                <li>Or just to chat about tech and mental health innovation!</li>
            </ul>
            <p>Email: <a href="mailto:ikechukwudavid331@gmail.com">ikechukwudavid331@.com</a></p>
        </section>
    </main>

    <footer>
        <p>Made with ❤️ for the mental health community</p>
        <p>© 2025 Maduemezia Ikechukwu David. All rights reserved.</p>
    </footer>
</body>
</html>

<!---
BlaQDeveloper/BlaQDeveloper is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
