# Portfolio-challenge-
Safaricom hackathons 
x<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>S-Hook Portfolio Challenge</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #6a11cb, #2575fc);
            color: #fff;
        }

        /* Header Styles */
        header {
            text-align: center;
            padding: 20px 10px;
            background: rgba(0, 0, 0, 0.6);
            color: #f9f9f9;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            color: #ffdc62;
        }

        header p {
            font-size: 1.2rem;
        }

        /* Main Container */
        main {
            max-width: 900px;
            margin: 20px auto;
            padding: 20px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 12px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        }

        section {
            margin-bottom: 30px;
            padding: 10px 20px;
        }

        section h2 {
            font-size: 1.8rem;
            margin-bottom: 10px;
            color: #ffdc62;
            border-bottom: 2px solid #ffdc62;
            display: inline-block;
        }

        section p, section ul {
            font-size: 1.1rem;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        ul li {
            margin: 5px 0;
            background: rgba(0, 0, 0, 0.4);
            padding: 10px;
            border-radius: 8px;
        }

        /* Button Styles */
        button {
            display: inline-block;
            padding: 10px 20px;
            margin-top: 10px;
            background: #ffdc62;
            color: #333;
            border: none;
            border-radius: 6px;
            font-size: 1rem;
            cursor: pointer;
            transition: transform 0.3s, background-color 0.3s;
        }

        button:hover {
            transform: scale(1.1);
            background: #f4c500;
        }

        /* Form Styles */
        form {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        form label {
            font-weight: bold;
        }

        form input, form textarea, form button {
            padding: 10px;
            border: none;
            border-radius: 6px;
            font-size: 1rem;
        }

        form input, form textarea {
            background: #fff;
            color: #333;
        }

        form button {
            background: #2575fc;
            color: #fff;
        }

        form button:hover {
            background: #1c5edc;
        }

        /* Footer Styles */
        footer {
            text-align: center;
            padding: 10px 0;
            background: rgba(0, 0, 0, 0.6);
            color: #ffdc62;
        }

        footer p {
            font-size: 1rem;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }

            section h2 {
                font-size: 1.5rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>S-Hook Hackathon 1: Portfolio Challenge 🚀</h1>
        <p>Welcome to the S-Hook Portfolio Challenge! 🎉</p>
    </header>


    <main>
        <section id="overview">
            <h2>🌟 Project Overview</h2>
            <p>Your challenge is to build a personal portfolio website that showcases your skills, background, and achievements. Your portfolio should include:</p>
            <ul>
                <li>Programming Languages: <strong>C,C++,a little bit of java</strong></li>
                <li>About section:<strong>Am a student of pwani university studying bachelor of science in computer science</strong></li>
                <li>Educational Background:
                    <p>2010-2018 :wajir primary school</p>
                    <p>2019-2022 :wajir high school</p>
                    <p>2023-present :pwani universIty</p>
                </li>
                <li>Interests:<strong>I want to specalise cyber security</strong></li>
                <li>Projects:<strong>this is my first project</strong></li>
                <li>Contact Form
                    <strong>contact me form
                        <p>phone number:0727759982</p>
                        <p>email:isaackalasssheikh@gmail.com</p>
                    </strong>
                </li>
                

    
                
            </ul>
        </section>

        <section id="about">
            <h2>📝 About Me</h2>
            <p>Hi! I’m <strong>ISAACK ALASS SHEIKH</strong>, a passionate web developer with a love for creating functional and beautiful web experiences.</p>
        </section>

        <section id="education">
            <h2>🎓 Educational Background</h2>
            <p>I am studying a degree in computer science from <strong>pwani university</strong>.</p>
            <button onclick="downloadCV()">Download My CV</button>
        </section>

        <section id="interests">
            <h2>💡 Interests</h2>
            <ul>
                <li>Web Development: Exploring modern frameworks and best practices.</li>
                <li>Tech Innovations: Keeping up with emerging trends in technology.</li>
                <li>python programming:curious in building and designing new revolution in technology</li>
            </ul>
        </section>

        <section id="projects">
            <h2>🛠 Projects</h2>
            <ul>
                <li><strong>Project 1:</strong> my project entails my portfolio.</li>
                <li><strong>Project 2:</strong> This is a portfolio challenge as safaricom will their first Hackathon.</li>
            </ul>
        </section>

        <section id="contact">
            <h2>📬 Contact Me</h2>
            <form id="contact-form">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="5" required></textarea>

                <button type="submit">Send</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 S-Hook Hackathon Portfolio Challenge</p>
    </footer>

    <script>
        // Simulate CV download
        function downloadCV() {
            alert("CV download functionality coming soon!");
        }

        // Handle contact form submission
        document.getElementById('contact-form').addEventListener('submit', function (event) {
            event.preventDefault();
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const message = document.getElementById('message').value;

            if (name && email && message) {
                alert(Thank you, ${name}! Your message has been sent.);
                this.reset();
            } else {
                alert('Please fill in all fields.');
            }
        });
    </script>
</body>
</html>
