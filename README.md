<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Hi I'm Tashrib Nur</title>

<!-- Google Font -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body {
    background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
    color: white;
    overflow-x: hidden;
}

/* Floating Background Glow */
body::before {
    content: "";
    position: fixed;
    width: 600px;
    height: 600px;
    background: radial-gradient(circle, rgba(255,0,150,0.4), transparent 70%);
    top: -200px;
    left: -200px;
    filter: blur(120px);
    z-index: -1;
}

/* Header */
header {
    display: flex;
    justify-content: space-between;
    padding: 20px 10%;
    backdrop-filter: blur(10px);
    background: rgba(255,255,255,0.05);
    position: sticky;
    top: 0;
}

header h1 {
    font-weight: 600;
    letter-spacing: 2px;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 25px;
    position: relative;
    transition: 0.3s;
}

nav a::after {
    content: "";
    width: 0%;
    height: 2px;
    background: #ff4ecd;
    position: absolute;
    bottom: -5px;
    left: 0;
    transition: 0.3s;
}

nav a:hover::after {
    width: 100%;
}

/* Hero */
.hero {
    height: 90vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
}

.hero h2 {
    font-size: 48px;
}

.hero span {
    background: linear-gradient(90deg, #ff4ecd, #6a5af9);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}

.hero p {
    margin: 20px 0;
    max-width: 600px;
    opacity: 0.8;
}

/* Button */
.btn {
    padding: 12px 30px;
    border-radius: 50px;
    background: linear-gradient(90deg, #ff4ecd, #6a5af9);
    color: white;
    text-decoration: none;
    transition: 0.4s;
    box-shadow: 0 0 15px rgba(255, 78, 205, 0.6);
}

.btn:hover {
    transform: scale(1.05);
    box-shadow: 0 0 25px rgba(255, 78, 205, 0.9);
}

/* Sections */
section {
    padding: 100px 10%;
}

.section-title {
    text-align: center;
    margin-bottom: 50px;
    font-size: 30px;
    background: linear-gradient(90deg, #ff4ecd, #6a5af9);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}

/* Glass Cards */
.projects {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 30px;
}

.card {
    background: rgba(255,255,255,0.05);
    border-radius: 20px;
    padding: 25px;
    backdrop-filter: blur(15px);
    transition: 0.4s;
    border: 1px solid rgba(255,255,255,0.1);
}

.card:hover {
    transform: translateY(-10px);
    box-shadow: 0 0 25px rgba(106, 90, 249, 0.5);
}

/* Footer */
footer {
    text-align: center;
    padding: 30px;
    background: rgba(255,255,255,0.05);
    backdrop-filter: blur(10px);
    margin-top: 50px;
}
</style>
</head>

<body>

<header>
    <h1>Nypho</h1>
    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<div class="hero">
    <h2>Hi, I'm <span>Tashrib Nur</span></h2>
    <p>I create normal Edits based on my mood</p>
    <a href="#projects" class="btn">Explore My Work</a>
</div>

<section id="about">
    <h2 class="section-title">About Me</h2>
    <p style="text-align:center; max-width:700px; margin:auto; opacity:0.85;">
        Passionate editor who crates crappy edits than only i enjoy
    </p>
</section>

<section id="projects">
    <h2 class="section-title">Projects</h2>
    <div class="projects">
        <div class="card">
            <h3>Project One</h3>
            <p>Idk vro check ny Instagram</p>
        </div>
        <div class="card">
            <h3>Project Two</h3>
            <p>Check Instagram >:3 </p>
        </div>
        <div class="card">
            <h3>Project Three</h3>
            <p>You should definitely checkout my Instagram </p>
        </div>
    </div>
</section>

<section id="contact">
    <h2 class="section-title">Contact</h2>
    <p style="text-align:center;">
        Email: femboytwinkieballss@email.com <br><br>
        Instagram: @imsooinlovewithroza
    </p>
</section>

<footer></footer>
    © Sybau nga shush
</footer>

</body>
</html>
