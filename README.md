<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>S Deepan Kumar - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>S Deepan Kumar</h1>
        <p>AI & Cybersecurity Enthusiast</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#certifications">Certifications</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <section id="about">
        <h2>About Me</h2>
        <p>I'm a BTech CSE student at SRM, passionate about AI-driven safety solutions, cybersecurity, and robotics.</p>
    </section>
    
    <section id="projects">
        <h2>Projects</h2>
        <div class="project-card">
            <h3>AI Emergency Response System</h3>
            <p>Multi-purpose AI for handling emergencies efficiently.</p>
        </div>
        <div class="project-card">
            <h3>Accident Detection System</h3>
            <p>Automatic accident detection with emergency call system.</p>
        </div>
        <div class="project-card">
            <h3>Cybersecurity Threat Detection</h3>
            <p>AI-driven system to identify and mitigate cyber threats.</p>
        </div>
    </section>
    
    <section id="skills">
        <h2>Skills & Certifications</h2>
        <ul>
            <li>Python</li>
            <li>Machine Learning & AI</li>
            <li>Cybersecurity</li>
            <li>Robotics</li>
            <li>Web Development</li>
        </ul>
    </section>
    
    <section id="certifications">
        <h2>Certifications</h2>
        <ul>
            <li>Certified in AI & Machine Learning</li>
            <li>Cybersecurity Fundamentals Certification</li>
            <li>Robotics Engineering Workshop Certificate</li>
            <li>Deep Learning Specialization (Coursera)</li>
        </ul>
    </section>
    
    <section id="contact">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:sk2718@srmist.edu.in">sk2718@srmist.edu.in</a></p>
        <p>GitHub: <a href="https://github.com/sdeepan19" target="_blank">github.com/sdeepan19</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/s-deepan-kumar-5b2016326" target="_blank">linkedin.com/in/s-deepan-kumar-5b2016326</a></p>
        
        <h3>Resume</h3>
        <p><a href="resume.pdf" download>Download My Resume (PDF)</a></p>
        
        <h3>Send Me a Message</h3>
        <form action="mailto:sk2718@srmist.edu.in" method="post" enctype="text/plain">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <input type="submit" value="Send Message">
        </form>
    </section>
    
    <footer>
        <p>&copy; 2025 S Deepan Kumar. All rights reserved.</p>
    </footer>
    
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            text-align: center;
        }
        header {
            background: #333;
            color: white;
            padding: 20px;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        section {
            padding: 20px;
            background: white;
            margin: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .project-card {
            background: #e0e0e0;
            padding: 15px;
            margin: 10px auto;
            border-radius: 8px;
            width: 80%;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }
        form {
            display: flex;
            flex-direction: column;
            align-items: center;
            max-width: 400px;
            margin: auto;
        }
        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        form input[type="submit"] {
            background: #333;
            color: white;
            cursor: pointer;
            border: none;
        }
        footer {
            background: #333;
            color: white;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</body>
</html>
