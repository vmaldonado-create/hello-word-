<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Veronica Maldonado | Personal Portfolio</title>
</head>
<body>

    <header>
        <h1>Veronica Maldonado</h1>
        <p>Student | Future Web Developer | Lifelong Learner</p>

        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>

        <section id="about">
            <h2>About Me</h2>

            <article>
                <h3>Who I Am</h3>

                <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?w=600"
                     alt="Student studying on a laptop at a desk">

                <p>
                    Hello! My name is Veronica Maldonado. I am currently a college student
                    learning web development and computer technology. I enjoy solving
                    problems, learning new programming skills, and creating websites.
                </p>
            </article>
        </section>

        <section id="education">
            <h2>Education</h2>

            <article>
                <h3>Current Studies</h3>

                <p>
                    I am working toward completing my college degree while building
                    experience in HTML, CSS, JavaScript, and other web technologies.
                </p>
            </article>
        </section>

        <section id="projects">
            <h2>Projects</h2>

            <article>
                <h3>Current Portfolio Project</h3>

                <p>
                    This website is the first milestone of my personal portfolio.
                    Future milestones will add CSS styling, responsive layouts,
                    JavaScript interactivity, accessibility improvements, and
                    deployment to the web.
                </p>
            </article>
        </section>

        <section id="skills">
            <h2>Skills</h2>

            <ul>
                <li>HTML</li>
                <li>Problem Solving</li>
                <li>Critical Thinking</li>
                <li>Microsoft Office</li>
                <li>Teamwork</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Contact</h2>

            <p>Email: yourname@email.com</p>

            <h3>Future Portfolio Plans</h3>

            <ol>
                <li>Add CSS styling.</li>
                <li>Create responsive layouts.</li>
                <li>Add JavaScript features.</li>
                <li>Improve accessibility.</li>
                <li>Publish the portfolio online.</li>
            </ol>
        </section>
        33898
        <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&family=Lora:wght@400;600&display=swap" rel="stylesheet">

<link rel="stylesheet" href="style.css">
/* Google Font Styling */

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Poppins', sans-serif;
    background:#F4F4F4;
    color:#333;
    line-height:1.6;
}

/* Headings */

h1,h2,h3{
    font-family:'Lora', serif;
    color:#1E3A5F;
    margin-bottom:16px;
}

/* Paragraphs */

p{
    margin-bottom:16px;
}

/* Navigation */

nav{
    background:#1E3A5F;
    padding:16px;
}

nav ul{
    list-style:none;
    display:flex;
    justify-content:center;
    gap:24px;
}

nav a{
    color:white;
    text-decoration:none;
    font-weight:600;
}

nav a:hover{
    color:#E9C46A;
}

/* Header */

header{
    background:#2A9D8F;
    color:white;
    text-align:center;
    padding:40px 20px;
}

/* Sections */

section{
    background:white;
    margin:24px auto;
    padding:24px;
    max-width:1100px;
    border-radius:10px;
    box-shadow:0 4px 10px rgba(0,0,0,.1);
}

/* Images */

img{
    max-width:100%;
    height:auto;
    border-radius:8px;
}

/* Buttons */

button{
    background:#2A9D8F;
    color:white;
    border:none;
    padding:12px 24px;
    border-radius:6px;
    cursor:pointer;
}

button:hover{
    background:#1E3A5F;
}

/* Footer */

footer{
    background:#1E3A5F;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:40px;
}<!-- Google Fonts -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&family=Merriweather:wght@400;700&display=swap" rel="stylesheet">

<!-- Your CSS -->
<link rel="stylesheet" href="style.css">
:root{
    --primary:#1E3A5F;
    --secondary:#2A9D8F;
    --accent:#E9C46A;
    --background:#F5F7FA;
    --surface:#FFFFFF;
    --text:#333333;
}
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Poppins', sans-serif;
    background:var(--background);
    color:var(--text);
    line-height:1.6;
}

h1,h2,h3,h4{
    font-family:'Merriweather', serif;
    color:var(--primary);
    margin-bottom:16px;
}

p{
    margin-bottom:16px;
}

header{
    background:var(--primary);
    color:white;
    padding:40px 20px;
    text-align:center;
}

nav{
    background:var(--secondary);
    padding:16px;
}

nav ul{
    display:flex;
    justify-content:center;
    gap:24px;
    list-style:none;
}

nav a{
    color:white;
    text-decoration:none;
    font-weight:600;
}

nav a:hover{
    color:var(--accent);
}

section{
    background:var(--surface);
    margin:24px auto;
    padding:24px;
    max-width:1100px;
    border-radius:8px;
}

footer{
    background:var(--primary);
    color:white;
    text-align:center;
    padding:20px;
}
<header>
    <h1>Project Milestone 1</h1>
</header>

<nav>
    <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html">Contact</a></li>
    </ul>
</nav>

<main>
    <section>
        <h2>Welcome</h2>
        <p>This website demonstrates responsive web design using HTML and CSS.</p>
    </section>
</main>

<footer>
    <p>&copy; 2026 Veronica Maldonado</p>
</footer>
    </main>
<main>

    <section class="hero">
        <h1>Welcome to My Website</h1>
        <p>This project demonstrates responsive web design using HTML and CSS.</p>
    </section>

    <section class="card-container">

        <article class="card">
            <h2>About Me</h2>
            <p>Learn about my background, interests, and goals.</p>
        </article>

        <article class="card">
            <h2>Projects</h2>
            <p>View the assignments and projects I have completed.</p>
        </article>

        <article class="card">
            <h2>Contact</h2>
            <p>Find ways to get in touch with me.</p>
        </article>

    </section>

</main>
    <footer>
        <p>&copy; 2026 Veronica Maldonado. All rights reserved.</p>
    </footer>
/* Main Content */
main{
    max-width:1200px;
    margin:0 auto;
    padding:24px;
}

/* Hero Section */
.hero{
    text-align:center;
    padding:40px 20px;
}

/* Flexbox Layout */
.card-container{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:24px;
    margin-top:32px;
}

/* Cards */
.card{
    flex:1 1 300px;
    background:#ffffff;
    padding:24px;
    border-radius:10px;
    box-shadow:0 4px 10px rgba(0,0,0,0.1);
    transition:transform .3s ease;
}

.card:hover{
    transform:translateY(-5px);
}

.card h2{
    margin-bottom:16px;
}

.card p{
    margin-bottom:0;
}/* Tablet */
@media (max-width:768px){

    nav ul{
        flex-direction:column;
        align-items:center;
    }

    .card-container{
        flex-direction:column;
    }
/* Tablet Layout - 768px and below */
@media screen and (max-width: 768px) {

    header {
        padding: 32px 16px;
    }

    nav ul {
        flex-direction: column;
        align-items: center;
        gap: 16px;
    }

    .card-container {
        flex-direction: column;
        gap: 16px;
    }

    .card {
        width: 100%;
    }

    h1 {
        font-size: 32px;
    }

    h2 {
        font-size: 24px;
    }

}/* Mobile Layout - 320px and below */
@media screen and (max-width: 480px) {

    body {
        font-size: 15px;
    }

    main {
        padding: 16px;
    }

    header {
        padding: 24px 12px;
    }

    nav {
        padding: 12px;
    }

    nav ul {
        gap: 12px;
    }

    .hero {
        padding: 24px 12px;
    }

    .card {
        padding: 16px;
        border-radius: 6px;
    }

    img {
        width: 100%;
        height: auto;
    }

    h1 {
        font-size: 26px;
    }

    h2 {
        font-size: 20px;
    }

}
}
</body>
</html>
