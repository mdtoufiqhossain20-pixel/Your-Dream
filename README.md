<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Beautiful Website</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f5f5f5;
        }
        header {
            background: #2b2d42;
            color: red;
            padding: 20px;
            text-align: center;
        }
        nav {
            background: #8d99ae;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        .hero {
            background: url('https://picsum.photos/1200/500') no-repeat center/cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: rainbow;
            text-shadow: 1px 1px 3px black;
            font-size: 40px;
            font-weight: bold;
        }
        .section {
            padding: 40px;
            text-align: center;
        }
        .cards {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        .card {
            background: gray;
            padding: 20px;
            width: 300px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        footer {
            background: #2b2d42;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
        <p>Simple, Clean, and Beautiful Design</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="hero">Your Dream Website</div>

    <section class="section" id="about">
        <h2>About Me</h2>
        <p>I am a beginner web designer learning HTML, CSS, and creating beautiful layouts.</p>
    </section>

    <section class="section" id="services">
        <h2>Our Services</h2>
        <div class="cards">
            <div class="card">
                <h3>Web Design</h3>
                <p>Modern and responsive web design using HTML & CSS.</p>
            </div>
            <div class="card">
                <h3>UI/UX Design</h3>
                <p>Beautiful and clean interface designs using Figma.</p>
            </div>
            <div class="card">
                <h3>Landing Pages</h3>
                <p>High‑quality landing pages for business and personal use.</p>
            </div>
        </div>
    </section>

    <section class="section" id="contact">
        <h2>Contact</h2>
       <p>Email: mdtoufiqhossain20@gmail.com</p>
        <p>Phone: +8801860601220</p>
    </section>

    <footer>
        <p>© 2025 My Website. All rights reserved.</p>
    </footer>
</body>
</html>
