<!DOCTYPE html>
<html>
<head>
    <title>Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #84a6e9;
        }

        header {
            background-color: #941919;
            color: #fff;
            text-align: center;
            padding: 2rem 0;
            position: relative; /* Add this */
        }

        .header-content h1 {
            font-size: 2.5rem;
        }

        /* Add styles for the round profile picture */
        .profile-picture {
            width: 100px; /* Adjust the size as needed */
            height: 100px;
            border-radius: 75%; /* Create a circular shape */
            object-fit: cover; /* To ensure the image fills the circular area */
            position: absolute; /* Add this */
            top: 75px; /* Adjust top position as needed */
            left: 75px; /* Adjust left position as needed */
        }

        nav {
            background-color: #333;
            color: #fff;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 20px;
        }

        nav ul li a {
            text-decoration: none;
            color: #fff;
        }

        .section-content {
            background-color: #fff;
            padding: 2rem;
            margin: 1rem;
            border-radius: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: justify;
        }

        .download-button {
            background-color: #333;
            color: #fff;
            padding: 0.5rem 1rem;
            text-decoration: none;
            border-radius: 20px;
            display: inline-block;
            margin-top: 10px;
            align-self: center;
        }

        .download-button:hover {
            background-color: #555;
        }

        footer {
            text-align: center;
            padding: 1rem 0;
            background-color: #333;
            color: #fff;
        }

        ul {
            list-style-type: disc;
            padding-left: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="header-content">
            <!-- Add your profile picture here -->
            <img src="1.jpg" alt="your profile photo" class="kiruba.pdf">
            <h1>kiruba M</h1>
            <p>Am computer engineer</p>
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#resume">Resume</a></li>
           
        </ul>
    </nav>

    <section id="about">
        <div class="section-content">
            <h2>About Me</h2>
            <p><b></b> Hi! I'm , a passionate II year student
            .I'm a speed typewriter(ENGLISH),
             problem solver.I've Leadership quality.
             I've specific talent in critical thinking. 
             I enjoy coding, problem solving, and continuosly 
             learning new technologies to enhance my skills towards my career.
             My goal is to build meaninful digital experiences that leave a lasting impact.
             Develop predictive models to analyze and intrept complex datasets.Implement 
             machine learning algorithm to improve desicion making and automation.Optimize 
             data processing pipelines for efficient data handling and and analysis.Work with 
             real world analysis tp gain insights drive businness intelligence.</p>

        </div>
    </section>

    <section id="education">
        <div class="section-content">
            <h2>Education</h2>
            <p>Government arts college  - Udumalpet</p>
            
            
        </div>
    </section>

    <section id="skills">
        <div class="section-content">
            <h2>Skills</h2>
            <ul>
                <li>HTML</li>
                <li>JAVASCRIPT</li>
                <li>CSS</li>
                <li>PYTHON</li>
                <li>C</li>
                <li>ML & AI</li>
                <li>JAVA</li>
                <li>C++</li>
                <li>NLP</li>
            </ul>
        </div>
    </section>

    <section id="projects">
        <div class="section-content">
            <h2>Projects</h2>
            <ul>
                <li><a href="#">Portfolio</a></li> 
                <!-- Add more project links here -->
            </ul>
        </div>
    </section>

    <section id="resume">
    
        <div class="section-content">
            <center>
            <h2>Resume</h2>
                <iframe href="kirubaresume.pdf" width="70%" height="500px"></iframe>
        </center>
        </div>
        
    </section>

    <footer>
        <p>&copy; 2025 kiruba M</p>
    </footer>

    <script>
        // Smooth scrolling to section when clicking on navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();

                const targetId = this.getAttribute('href').substring(1);
                const targetElement = document.getElementById(targetId);

                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop,
                        behavior: 'smooth'
                    });
                }
            });
        });
    </script>
</body>
</html>
