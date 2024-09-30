<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=3.0">
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header>
        <div class="container header-content">
            <div class="profile-pic">
                <img src="low res white background.jpg">
            </div>
            <div class="header-text">
                <h1>Nisura Perera</h1>
                <p>Biotechnology Student at Sri Lankan Institute of Information Technology</p>
            </div>
        </div>
    </header>

  <nav>
        <ul>
            <li><a href="#about">About Me</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#awards">Awards & Achievements</a></li>
            <li><a href="#hobbies">Hobbies</a></li> <!-- Updated Navigation -->
            <li><a href="#resume">Resume</a></li>
            <li><a href="#other-details">Other Details</a></li>
        </ul>
    </nav>

  <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>
                Hello! I am Nisura Perera, currently studying Biotechnology at the Sri Lankan Institute of Information Technology. Born on the 7th of November 2003, I completed my primary and secondary education at Maliyadeva College, Kurunegala.
                My passion for genetic engineering and biotechnology drives me to contribute to groundbreaking advancements in the field. I am motivated by a desire to improve global health and sustainability, with the hope of applying my knowledge to develop innovative solutions for a better world.
            </p>
        </div>
    </section>

  <section id="education">
        <div class="container">
            <h2>Education</h2>
            <ul>
                <li>
                    <strong>Bachelor’s Degree in Biotechnology (Ongoing)</strong> <br>
                    Faculty of Humanities and Sciences, Sri Lankan Institute of Information Technology (SLIIT), Sri Lanka
                </li>
                <li>
                    <strong>Advanced Level – Biological Science Stream</strong> <br>
                    Physics: C, Biology: C, Chemistry: C
                </li>
                <li>
                    <strong>Ordinary Level</strong> <br>
                    A passes in: Science, Mathematics, English, History, Sinhala, Health Science, Commerce <br>
                    B passes in: Buddhism, Oriental Music
                </li>
            </ul>
        </div>
    </section>

  <section id="skills">
        <div class="container">
            <h2>Skills & Technical Proficiency</h2>
            <div class="skill">
                <p>Adobe Photoshop</p>
                <div class="progress-bar">
                    <div class="progress" style="width: 85%;"></div>
                </div>
            </div>
            <div class="skill">
                <p>Adobe Premiere</p>
                <div class="progress-bar">
                    <div class="progress" style="width: 85%;"></div>
                </div>
            </div>
            <div class="skill">
                <p>Adobe Lightroom</p>
                <div class="progress-bar">
                    <div class="progress" style="width: 80%;"></div>
                </div>
            </div>
            <div class="skill">
                <p>Blender</p>
                <div class="progress-bar">
                    <div class="progress" style="width: 50%;"></div>
                </div>
            </div>
        </div>
    </section>

  <section id="awards">
        <div class="container">
            <h2>Awards & Achievements</h2>
            <ul>
                <li>Winner (Wildlife Category) - Prabhaseya All Island Photographic Competition</li>
                <li>Winner (Monochrome) - Specular Photo Marathon 2021</li>
                <li>2nd Runner-up - Tennis Carlton Cup</li>
                <li>2nd Runner-up - Tharkaye Andaheraya (Debating Competition)</li>
            </ul>
        </div>
    </section>

  <section id="hobbies"> <!-- New Hobbies Section -->
        <div class="container">
            <h2>Hobbies</h2>
            <ul>
                <li>Photography - Capturing moments and nature's beauty.</li>
                <li>Tennis - Enjoying the game and competing in tournaments.</li>
                <li>Chess - Engaging in strategic thinking and competitions.</li>
                <li>Traveling - Exploring new places and cultures.</li>
                <li>Reading - Delving into books about science and fiction.</li>
            </ul>
        </div>
    </section>

  <section id="resume">
        <div class="container">
            <h2>Resume</h2>
            <p>You can view and download my resume below:</p>
            <a href="resume.pdf" download="Nisura_Perera_Resume.pdf" class="btn">Download Resume</a>
        </div>
    </section>

   <section id="other-details">
        <div class="container">
            <h2>Other Details</h2>
            <p>I actively participate in extracurricular activities. I am a member of the Photographic Society of Sri Lanka, the Sri Lanka Wildlife Conservation Society, and have been part of my school's Tennis and Chess teams. Additionally, I have held leadership positions, including President of the Photographic Society and Assistant Secretary of the Debating Society at Maliyadeva College.</p>
            <p>You can contact me via email: <a href="mailto:nisuraperera123@gmail.com">nisuraperera123@gmail.com</a> or phone: +94 924 6429</p>
        </div>
    </section>

  <footer>
        <div class="container">
            <p>&copy; 2024 Nisura Perera. All rights reserved. | Address: 116/52, North Lake Road, Kurunegala</p>
        </div>
    </footer>

   <style>
        /* styles.css */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f0f4f8;
            color: #333;
        }

        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px;
        }

        header {
            background: #005f73;
            color: #fff;
            padding: 40px 0;
            text-align: center;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .header-content {
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .profile-pic img {
            border-radius: 50%;
            width: 130px;
            height: 130px;
            object-fit: cover;
            border: 4px solid #fff;
        }

        nav {
            background: #0a9396;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0;
            padding: 0;
        }

        nav ul li a {
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            background: #94d2bd;
            color: #005f73;
            transition: background 0.3s, color 0.3s;
        }

        section {
            background: #fff;
            margin: 20px 0;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #005f73;
        }

        .skill {
            margin-bottom: 20px;
        }

        .progress-bar {
            background: #e0e0e0;
            border-radius: 8px;
            overflow: hidden;
            height: 20px;
        }

        .progress {
            background: #0a9396;
            height: 100%;
            transition: width 0.5s ease-in-out;
        }

        .btn {
            background: #005f73;
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 4px;
            display: inline-block;
            font-weight: bold;
        }

        .btn:hover {
            background: #0a9396;
            transition: background 0.3s;
       
