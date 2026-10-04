<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Mohamed Azeem | Computer Engineering</title>

    <meta name="description"
          content="Mohamed Azeem - Computer Engineering undergraduate, Full-Stack Developer and AI & ML Enthusiast.">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background: #0d1117;
            color: #e6edf3;
            line-height: 1.6;
        }

        a {
            color: inherit;
            text-decoration: none;
        }

        .container {
            width: 90%;
            max-width: 1100px;
            margin: auto;
        }

        /* NAVBAR */

        nav {
            position: sticky;
            top: 0;
            z-index: 100;
            background: rgba(13, 17, 23, 0.95);
            border-bottom: 1px solid #30363d;
            backdrop-filter: blur(10px);
        }

        .nav-container {
            height: 70px;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .logo {
            font-size: 22px;
            font-weight: bold;
        }

        .logo span {
            color: #58a6ff;
        }

        .nav-links {
            display: flex;
            gap: 28px;
            list-style: none;
        }

        .nav-links a {
            color: #8b949e;
            transition: 0.3s;
        }

        .nav-links a:hover {
            color: #58a6ff;
        }

        /* HERO */

        .hero {
            min-height: 90vh;
            display: flex;
            align-items: center;
            padding: 80px 0;
        }

        .hero-content {
            max-width: 850px;
        }

        .location {
            color: #8b949e;
            margin-bottom: 15px;
            font-size: 16px;
        }

        .hero h1 {
            font-size: clamp(45px, 7vw, 75px);
            line-height: 1.1;
            margin-bottom: 20px;
        }

        .hero h1 span {
            color: #58a6ff;
        }

        .hero h2 {
            font-size: 25px;
            color: #8b949e;
            font-weight: normal;
            margin-bottom: 25px;
        }

        .hero p {
            max-width: 700px;
            color: #8b949e;
            font-size: 18px;
            margin-bottom: 30px;
        }

        .buttons {
            display: flex;
            gap: 15px;
            flex-wrap: wrap;
        }

        .btn {
            padding: 12px 22px;
            border-radius: 8px;
            border: 1px solid #30363d;
            transition: 0.3s;
        }

        .btn-primary {
            background: #238636;
            border-color: #238636;
        }

        .btn-primary:hover {
            background: #2ea043;
        }

        .btn-secondary:hover {
            border-color: #58a6ff;
            color: #58a6ff;
        }

        /* SECTIONS */

        section {
            padding: 80px 0;
            border-top: 1px solid #21262d;
        }

        .section-title {
            font-size: 32px;
            margin-bottom: 40px;
        }

        .section-title span {
            color: #58a6ff;
        }

        .about-text {
            max-width: 850px;
            color: #8b949e;
            font-size: 17px;
        }

        .about-text p {
            margin-bottom: 18px;
        }

        /* SKILLS */

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
        }

        .skill-card {
            background: #161b22;
            border: 1px solid #30363d;
            border-radius: 10px;
            padding: 25px;
            transition: 0.3s;
        }

        .skill-card:hover {
            transform: translateY(-5px);
            border-color: #58a6ff;
        }

        .skill-card h3 {
            margin-bottom: 12px;
        }

        .skill-card p {
            color: #8b949e;
        }

        /* PROJECTS */

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }

        .project {
            background: #161b22;
            border: 1px solid #30363d;
            border-radius: 12px;
            padding: 25px;
            transition: 0.3s;
        }

        .project:hover {
            transform: translateY(-6px);
            border-color: #58a6ff;
        }

        .project h3 {
            margin-bottom: 12px;
        }

        .project p {
            color: #8b949e;
            margin-bottom: 18px;
        }

        .tech {
            color: #58a6ff;
            font-size: 14px;
        }

        /* FOCUS */

        .focus-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
        }

        .focus-item {
            padding: 18px;
            background: #161b22;
            border: 1px solid #30363d;
            border-radius: 8px;
        }

        /* EDUCATION */

        .education {
            background: #161b22;
            border: 1px solid #30363d;
            border-radius: 12px;
            padding: 30px;
            max-width: 800px;
        }

        .education h3 {
            color: #58a6ff;
            margin-bottom: 8px;
        }

        .education p {
            color: #8b949e;
        }

        /* CONTACT */

        .contact {
            text-align: center;
        }

        .contact p {
            color: #8b949e;
            margin-bottom: 25px;
        }

        .socials {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
        }

        /* FOOTER */

        footer {
            text-align: center;
            padding: 30px;
            border-top: 1px solid #21262d;
            color: #8b949e;
        }

        /* MOBILE */

        @media (max-width: 700px) {

            .nav-links {
                display: none;
            }

            .hero {
                min-height: 80vh;
            }

            .hero h1 {
                font-size: 45px;
            }

            .hero h2 {
                font-size: 20px;
            }
        }
    </style>
</head>

<body>

<!-- NAVIGATION -->

<nav>
    <div class="container nav-container">

        <div class="logo">
            <span>M</span>A
        </div>

        <ul class="nav-links">
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#focus">Focus</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>

    </div>
</nav>


<!-- HERO -->

<header class="hero">

    <div class="container">

        <div class="hero-content">

            <div class="location">
                🇱🇰 Sri Lanka based
            </div>

            <h1>
                Hi, I'm <span>Mohamed Azeem</span>
            </h1>

            <h2>
                Computer Engineering Undergraduate
            </h2>

            <p>
                Full-Stack Developer | AI & ML Enthusiast |
                Problem Solver
            </p>

            <p>
                I build practical software solutions and I'm currently
                expanding my knowledge in Machine Learning, Generative AI,
                LLM Engineering and modern software development.
            </p>

            <div class="buttons">

                <a
                    href="https://github.com/mohamadazeem"
                    target="_blank"
                    class="btn btn-primary">
                    GitHub
                </a>

                <a
                    href="YOUR_LINKEDIN_URL"
                    target="_blank"
                    class="btn btn-secondary">
                    LinkedIn
                </a>

                <a
                    href="#projects"
                    class="btn btn-secondary">
                    View Projects
                </a>

            </div>

        </div>

    </div>

</header>


<!-- ABOUT -->

<section id="about">

    <div class="container">

        <h2 class="section-title">
            👨‍💻 <span>About Me</span>
        </h2>

        <div class="about-text">

            <p>
                I'm a 2nd-year Computer Engineering undergraduate
                at the University of Ruhuna, passionate about software
                development, artificial intelligence and building
                practical solutions.
            </p>

            <p>
                I enjoy developing web applications, working with
                backend systems and databases, and exploring emerging
                technologies in Artificial Intelligence and Machine Learning.
            </p>

            <p>
                My current goal is to strengthen my Full-Stack Development
                skills while progressing toward AI Engineering,
                Generative AI and LLM application development.
            </p>

        </div>

    </div>

</section>


<!-- SKILLS -->

<section id="skills">

    <div class="container">

        <h2 class="section-title">
            🛠️ <span>Technologies & Tools</span>
        </h2>

        <div class="skills-grid">

            <div class="skill-card">
                <h3>💻 Programming</h3>
                <p>
                    C • C++ • Python • JavaScript • TypeScript
                </p>
            </div>

            <div class="skill-card">
                <h3>🌐 Frontend</h3>
                <p>
                    HTML5 • CSS3 • Vue.js • Tailwind CSS • Vite
                </p>
            </div>

            <div class="skill-card">
                <h3>⚙️ Backend</h3>
                <p>
                    Node.js • Express.js • REST APIs
                </p>
            </div>

            <div class="skill-card">
                <h3>🗄️ Database</h3>
                <p>
                    PostgreSQL
                </p>
            </div>

            <div class="skill-card">
                <h3>🤖 AI & ML</h3>
                <p>
                    Python • Pandas • NumPy • Scikit-learn
                </p>
            </div>

            <div class="skill-card">
                <h3>🔧 Tools</h3>
                <p>
                    Git • GitHub • VS Code • Postman
                </p>
            </div>

        </div>

    </div>

</section>


<!-- PROJECTS -->

<section id="projects">

    <div class="container">

        <h2 class="section-title">
            🚀 <span>Featured Projects</span>
        </h2>

        <div class="projects">

            <div class="project">

                <h3>🛒 E-Commerce Product Store</h3>

                <p>
                    A modern e-commerce single-page application
                    featuring product browsing, search, filtering,
                    shopping cart, wishlist and persistent local data.
                </p>

                <div class="tech">
                    Vue 3 • TypeScript • Tailwind CSS • Vite • REST API
                </div>

            </div>


            <div class="project">

                <h3>📚 Student Task Manager</h3>

                <p>
                    A full-stack application designed to help students
                    manage tasks, deadlines, priorities and progress.
                </p>

                <div class="tech">
                    Node.js • Express.js • PostgreSQL • REST API
                </div>

            </div>


            <div class="project">

                <h3>🤖 AI & Machine Learning Projects</h3>

                <p>
                    Exploring machine learning and AI techniques
                    to develop practical solutions for real-world
                    problems.
                </p>

                <div class="tech">
                    Python • Pandas • NumPy • Scikit-learn
                </div>

            </div>


            <div class="project">

                <h3>🔌 Digital Systems & FPGA</h3>

                <p>
                    Digital design projects using Verilog and FPGA
                    technologies as part of Computer Engineering studies.
                </p>

                <div class="tech">
                    Verilog • Digital Logic • FPGA
                </div>

            </div>

        </div>

    </div>

</section>


<!-- CURRENT FOCUS -->

<section id="focus">

    <div class="container">

        <h2 class="section-title">
            🎯 <span>Current Focus</span>
        </h2>

        <div class="focus-list">

            <div class="focus-item">
                🌐 Full-Stack Development
            </div>

            <div class="focus-item">
                🤖 Machine Learning & AI
            </div>

            <div class="focus-item">
                🧠 Generative AI & LLM Engineering
            </div>

            <div class="focus-item">
                ⚙️ Backend & Database Development
            </div>

            <div class="focus-item">
                🚀 DevOps & Cloud Technologies
            </div>

            <div class="focus-item">
                🔌 FPGA & Digital System Design
            </div>

        </div>

    </div>

</section>


<!-- EDUCATION -->

<section>

    <div class="container">

        <h2 class="section-title">
            🎓 <span>Education</span>
        </h2>

        <div class="education">

            <h3>
                B.Sc. Eng. (Hons) in Computer Engineering
            </h3>

            <p>
                University of Ruhuna — Faculty of Engineering
            </p>

            <p>
                2nd Year Undergraduate
            </p>

        </div>

    </div>

</section>


<!-- CONTACT -->

<section id="contact">

    <div class="container contact">

        <h2 class="section-title">
            🤝 <span>Let's Connect</span>
        </h2>

        <p>
            I'm interested in collaborating on AI, Machine Learning,
            Full-Stack and open-source projects.
        </p>

        <div class="socials">

            <a
                href="https://github.com/mohamadazeem"
                target="_blank"
                class="btn btn-secondary">
                GitHub
            </a>

            <a
                href="https://www.linkedin.com/in/mohamed-azeem-973b882b5/?isSelfProfile=true"
                target="_blank"
                class="btn btn-secondary">
                LinkedIn
            </a>

            <a
                href="azeemmuneer665@gmail.com"
                class="btn btn-secondary">
                Email
            </a>

        </div>

    </div>

</section>


<!-- FOOTER -->

<footer>

    <p>
        © 2026 Mohamed Azeem • Built with HTML & CSS
    </p>

</footer>

</body>
</html>
