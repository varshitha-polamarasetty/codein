# <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Codein - Learn Coding</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Poppins:wght@300;600&display=swap');

        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #1a1a2e, #16213e);
            color: white;
            text-align: center;
        }
        header {
            background: linear-gradient(90deg, #ff00ff, #00ffff);
            padding: 40px;
            font-size: 2em;
            font-family: 'Orbitron', sans-serif;
            animation: glow 2s infinite alternate;
        }
        @keyframes glow {
            from {
                text-shadow: 0 0 10px #fff, 0 0 20px #ff00ff, 0 0 30px #00ffff;
            }
            to {
                text-shadow: 0 0 20px #fff, 0 0 30px #ff00ff, 0 0 40px #00ffff;
            }
        }
        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            background: rgba(0, 0, 0, 0.9);
            font-size: 1.5em;
        }
        nav ul li {
            padding: 20px;
        }
        nav ul li a {
            color: #0ff;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }
        nav ul li a:hover {
            color: #ff00ff;
            text-shadow: 0 0 15px #ff00ff, 0 0 30px #ff00ff;
        }
        section {
            margin: 50px auto;
            padding: 40px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            box-shadow: 0 0 15px rgba(0, 255, 255, 0.7);
            width: 80%;
            font-size: 1.5em;
            transition: transform 0.3s;
        }
        section:hover {
            transform: scale(1.02);
            box-shadow: 0 0 25px #ff00ff;
        }
        .course {
            margin: 30px;
            padding: 25px;
            border: 2px solid #0ff;
            background: rgba(0, 0, 0, 0.8);
            border-radius: 15px;
            display: inline-block;
            width: 350px;
            transition: 0.3s;
            font-size: 1.3em;
        }
        .course:hover {
            transform: rotate(3deg) scale(1.1);
            box-shadow: 0 0 20px #ff00ff;
        }
        .course img {
            width: 100%;
            border-radius: 15px;
        }
        .register-btn {
            display: inline-block;
            margin-top: 15px;
            padding: 12px 25px;
            background: linear-gradient(90deg, #ff00ff, #00ffff);
            color: black;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
            transition: 0.3s;
            font-size: 1.2em;
        }
        .register-btn:hover {
            background: linear-gradient(90deg, #00ffff, #ff00ff);
            box-shadow: 0 0 20px #ff00ff, 0 0 30px #ff00ff;
        }
        footer {
            background: rgba(0, 0, 0, 0.9);
            color: white;
            padding: 20px;
            font-size: 1.5em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Codein</h1>
        <p>Learn coding professionally at an affordable price</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#courses">Courses</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <section id="about">
        <h2>About Us</h2>
        <p>Codein is a platform dedicated to making coding education accessible to everyone at minimal costs.</p>
    </section>
    
    <section id="courses">
        <h2>Courses Available</h2>
        <div class="course">
            <img src="https://res.cloudinary.com/dxcwpasvu/image/upload/v1741789554/Learn_webde_z1gnzy.png" alt="Front End Web Development">
            <h3>Front End Web Development</h3>
            <p>Learn HTML, CSS, and JavaScript to build stunning websites.</p>
            <a href="https://forms.gle/gmuZ2eRHDWrcK7uVA" class="register-btn">Register Now</a>
        </div>
        <div class="course">
            <img src="https://res.cloudinary.com/dxcwpasvu/image/upload/v1741789393/Learn_webde_1_og5u4y.png" alt="Data Structures">
            <h3>Data Structures</h3>
            <p>Master the fundamentals of data structures to enhance your coding skills.</p>
            <a href="https://forms.gle/NRBxACHUWYSqUTVC8" class="register-btn">Register Now</a>
        </div>
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: varshithapolamarasetty@gmail.com</p>
        <p>Phone: 9290314151</p>
    </section>
    
    <footer>
        <p>&copy; 2025 Codein. All rights reserved.</p>
    </footer>
</body>
</html>
