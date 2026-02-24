index.html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Portfolio - Ton Nom</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <nav>
            <h1 class="logo">TonNom</h1>
            <ul class="nav-links">
                <li><a href="#about">À propos</a></li>
                <li><a href="#projects">Projets</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-content">
            <h2>Bonjour, je suis <span>Ton Nom</span></h2>
            <p>Étudiant en informatique passionné par le développement web et la création d'expériences modernes.</p>
            <a href="#projects" class="btn">Voir mes projets</a>
        </div>
    </section>

    <section id="about" class="about">
        <h2>À propos de moi</h2>
        <p>
            Je suis étudiant en informatique, motivé et curieux.
            Je développe des sites web modernes, responsives et performants.
            Je suis actuellement à la recherche d’un stage pour mettre en pratique mes compétences.
        </p>
    </section>

    <section id="projects" class="projects">
        <h2>Mes Projets</h2>
        <div class="project-grid">
            <div class="project-card">
                <h3>Projet 1</h3>
                <p>Application web réalisée avec HTML, CSS et JavaScript.</p>
            </div>

            <div class="project-card">
                <h3>Projet 2</h3>
                <p>Site responsive moderne avec design professionnel.</p>
            </div>

            <div class="project-card">
                <h3>Projet 3</h3>
                <p>Projet personnel pour améliorer mes compétences frontend.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <h2>Contact</h2>
        <p>Email : tonemail@email.com</p>
        <p>LinkedIn : linkedin.com/in/tonprofil</p>
    </section>

    <footer>
        <p>© 2026 Ton Nom - Tous droits réservés</p>
    </footer>

</body>
</html>
