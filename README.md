
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mon Portfolio</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background: #111;
    color: white;
}

header {
    background: #000;
    padding: 20px 10%;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav a {
    color: white;
    text-decoration: none;
    transition: 0.3s;
}

nav a:hover {
    color: #00adb5;
}

.hero {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 80px 10%;
    flex-wrap: wrap;
}

.hero-text {
    max-width: 500px;
}

.hero-text span {
    color: #00adb5;
}

.btn {
    display: inline-block;
    margin-top: 20px;
    padding: 10px 20px;
    background: #00adb5;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    transition: 0.3s;
}

.btn:hover {
    background: #019ca3;
}

.hero-image img {
    width: 250px;
    border-radius: 50%;
    border: 4px solid #00adb5;
}

section {
    padding: 60px 10%;
}

.projects {
    background: #1a1a1a;
}

.project-card {
    background: #222;
    padding: 20px;
    margin-top: 20px;
    border-radius: 10px;
    transition: 0.3s;
}

.project-card:hover {
    transform: scale(1.05);
    background: #333;
}

footer {
    text-align: center;
    padding: 20px;
    background: #000;
    margin-top: 40px;
}

/* Responsive */
@media (max-width: 768px) {
    .hero {
        flex-direction: column;
        text-align: center;
    }

    .hero-image {
        margin-top: 20px;
    }
}
</style>

</head>
<body>

<header>
    <nav>
        <h1 class="logo">MonPortfolio</h1>
        <ul>
            <li><a href="#about">À propos</a></li>
            <li><a href="#projects">Projets</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<section class="hero">
    <div class="hero-text">
        <h2>Salut, je suis <span>Tsiory</span></h2>
        <p>Développeur Web & Designer</p>
        <a href="#contact" class="btn">Me contacter</a>
    </div>
    <div class="hero-image">
        <!-- Mets ton image dans le même dossier que index.html -->
        <img src="profile.jpg" alt="Photo de profil">
    </div>
</section>

<section id="about" class="about">
    <h2>À propos</h2>
    <p>
        Je suis passionné par le développement web.
        Je crée des sites modernes, responsives et élégants.
    </p>
</section>

<section id="projects" class="projects">
    <h2>Mes Projets</h2>

    <div class="project-card">
        <h3>Projet 1</h3>
        <p>Description du projet.</p>
    </div>

    <div class="project-card">
        <h3>Projet 2</h3>
        <p>Description du projet.</p>
    </div>

</section>

<section id="contact" class="contact">
    <h2>Contact</h2>
    <p>Email : exemple@email.com</p>
</section>

<footer>
    <p>© 2026 Mon Portfolio</p>
</footer>

</body>
</html>

