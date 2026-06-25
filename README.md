Intern ID:CITS3168
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Personal Portfolio</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
    scroll-behavior:smooth;
}

body{
    background:#f4f4f4;
    color:#333;
}

header{
    background:#222;
    color:white;
    padding:20px 0;
    position:sticky;
    top:0;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
    width:90%;
    margin:auto;
}

nav ul{
    list-style:none;
    display:flex;
}

nav ul li{
    margin-left:20px;
}

nav ul li a{
    color:white;
    text-decoration:none;
}

.hero{
    height:100vh;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    background:linear-gradient(to right,#4facfe,#00f2fe);
    color:white;
    text-align:center;
}

.hero h1{
    font-size:50px;
}

.hero p{
    font-size:22px;
    margin:15px 0;
}

.btn{
    display:inline-block;
    padding:12px 25px;
    background:white;
    color:#333;
    text-decoration:none;
    border-radius:5px;
    font-weight:bold;
}

section{
    padding:60px 10%;
}

h2{
    text-align:center;
    margin-bottom:30px;
}

.about, .contact{
    text-align:center;
}

.skills{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(150px,1fr));
    gap:20px;
}

.skill{
    background:white;
    padding:20px;
    text-align:center;
    border-radius:10px;
    box-shadow:0 2px 10px rgba(0,0,0,0.1);
}

.projects{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.project{
    background:white;
    padding:20px;
    border-radius:10px;
    box-shadow:0 2px 10px rgba(0,0,0,0.1);
}

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:20px;
}
</style>
</head>

<body>

<header>
    <nav>
        <h2>My Portfolio</h2>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<section class="hero">
    <h1>Your Name</h1>
    <p>Front-End Developer | Web Designer</p>
    <a href="#contact" class="btn">Hire Me</a>
</section>

<section id="about" class="about">
    <h2>About Me</h2>
    <p>
        Hello! I'm a Front-End Developer passionate about creating
        responsive and user-friendly websites using HTML, CSS, and JavaScript.
    </p>
</section>

<section id="skills">
    <h2>My Skills</h2>
    <div class="skills">
        <div class="skill">HTML</div>
        <div class="skill">CSS</div>
        <div class="skill">JavaScript</div>
        <div class="skill">Bootstrap</div>
        <div class="skill">React</div>
        <div class="skill">Git & GitHub</div>
    </div>
</section>

<section id="projects">
    <h2>Projects</h2>
    <div class="projects">
        <div class="project">
            <h3>Weather App</h3>
            <p>A responsive weather forecast application.</p>
        </div>

        <div class="project">
            <h3>Portfolio Website</h3>
            <p>A personal portfolio website showcasing skills and projects.</p>
        </div>

        <div class="project">
            <h3>E-Commerce Website</h3>
            <p>An online shopping website with modern UI.</p>
        </div>
    </div>
</section>

<section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>Email: yourname@email.com</p>
    <p>Phone: +91 9876543210</p>
    <p>LinkedIn: linkedin.com/in/yourname</p>
</section>

<footer>
    <p>© 2026 Your Name. All Rights Reserved.</p>
</footer>

</body>
</html>
<img width="1905" height="1061" alt="Screenshot 2026-06-25 224534" src="https://github.com/user-attachments/assets/d0312f06-cdb8-46d2-8dbf-fdcb28ccc816" />
<img width="1911" height="1062" alt="Screenshot 2026-06-25 224334" src="https://github.com/user-attachments/assets/a717a62f-c803-4319-ae80-018838c53c2f" />
