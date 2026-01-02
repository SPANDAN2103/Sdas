<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spandan's Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Roboto', sans-serif;
        }
        body {
            line-height: 1.6;
            background: #f5f5f5;
            color: #333;
        }
        a {
            text-decoration: none;
            color: inherit;
        }

        /* Header / Navbar */
        header {
            background: #1e1e1e;
            color: white;
            padding: 20px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav {
            max-width: 1100px;
            margin: auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px;
        }
        nav .logo {
            font-size: 1.8rem;
            font-weight: bold;
            color: #00bcd4;
        }
        nav ul {
            display: flex;
            list-style: none;
        }
        nav ul li {
            margin-left: 25px;
        }
        nav ul li a:hover {
            color: #00bcd4;
        }

        /* Hero Section */
        .hero {
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            min-height: 80vh;
            background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e') center/cover no-repeat;
            color: white;
        }
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 20px;
        }
        .hero p {
            font-size: 1.2rem;
        }

        /* Sections */
        section {
            padding: 60px 20px;
            max-width: 1100px;
            margin: auto;
        }
        section h2 {
            text-align: center;
            font-size: 2.2rem;
            margin-bottom: 40px;
            color: #1e1e1e;
        }

        /* About Section */
        .about {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            gap: 40px;
        }
        .about img {
            width: 300px;
            border-radius: 10px;
        }
        .about .content {
            flex: 1;
        }

        /* Portfolio Section */
        .portfolio {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .portfolio .card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        .portfolio .card:hover {
            transform: translateY(-10px);
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 30px 20px;
            background: #1e1e1e;
            color: white;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .about {
                flex-direction: column;
                text-align: center;
            }
            .about img {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <!-- Header / Navbar -->
    <header>
        <nav>
            <div class="logo">Spandan</div>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div>
            <h1>Hello, I'm Spandan</h1>
            <p>A passionate web developer creating beautiful websites.</p>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <div class="about">
            <img src="https://images.unsplash.com/photo-1502767089025-6572583495b6" alt="Spandan">
            <div class="content">
                <p>Hi! I'm Spandan Das, a web developer who loves building modern and responsive websites. I enjoy working on projects that challenge my skills and allow me to learn new technologies.</p>
                <p>Skills: HTML, CSS, JavaScript, GitHub, Responsive Design, Web Development</p>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio">
        <h2>Portfolio</h2>
        <div class="portfolio">
            <div class="card">
                <h3>Project 1</h3>
                <p>A beautiful landing page built with HTML and CSS.</p>
            </div>
            <div class="card">
                <h3>Project 2</h3>
                <p>Responsive portfolio website for a client.</p>
            </div>
            <div class="card">
                <h3>Project 3</h3>
                <p>Interactive web app using JavaScript and DOM.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p style="text-align:center;">Email: <a href="mailto:spandan@example.com">spandan@example.com</a></p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 Spandan Das. All rights reserved.</p>
    </footer>
</body>
</html>
