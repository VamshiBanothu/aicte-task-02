<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Webpage Example</title>
    <style>
        body, h1, h2, p, ul, li {
            margin: 0;
            padding: 0;
            list-style: none;
        }
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1em 0;
            text-align: center;
            margin-bottom: 20px;
        }
        nav ul {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav ul li {
            margin: 0 10px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            display: block;
        }
        nav ul li a:hover {
            background-color: #575757;
        }
        main {
            padding: 20px;
        }
        section {
            margin-bottom: 20px;
            padding: 20px;
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            margin-bottom: 10px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }

            nav ul li {
                margin: 10px 0;
            }
            main {
                padding: 15px;
            }
        }
        @media (max-width: 480px) {
            header {
                padding: 10px 0;
            }
            header h1 {
                font-size: 24px;
            }
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            nav ul li {
                margin: 8px 0;
            }
            main {
                padding: 10px;
            }
            main section {
                margin-bottom: 15px;
            }
            footer {
                padding: 8px 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Simple Webpage</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home">
            <h2>Home</h2>
            <p>Welcome to my simple webpage. This is a demonstration of HTML and CSS for creating a well-structured and styled website.</p>
        </section>
        <section id="about">
            <h2>About</h2>
            <p>This section provides information about the purpose of the webpage and its creator.</p>
        </section>
        <section id="services">
            <h2>Services</h2>
            <p>Details about the services offered are listed here.</p>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>This section provides the contact details.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Simple Webpage</p>
    </footer>
</body>
</html>
