<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TRAPODS - AirPods pour les jeunes</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>TRAPODS</h1>
        <nav>
            <ul>
                <li><a href="#accueil">Accueil</a></li>
                <li><a href="#produits">Produits</a></li>
                <li><a href="#about">À propos</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="accueil">
        <h2>Des AirPods stylés pour la génération connectée</h2>
        <p>Qualité, style et performance. Découvrez notre collection exclusive !</p>
        <a href="#produits" class="btn">Voir les produits</a>
    </section>

    <section id="produits">
        <h2>Nos Produits</h2>
        <div class="produit">
            <img src="https://via.placeholder.com/200" alt="AirPods 1">
            <h3>Trapods V1</h3>
            <p>Son immersif et design épuré.</p>
            <span class="prix">99€</span>
        </div>
        <div class="produit">
            <img src="https://via.placeholder.com/200" alt="AirPods 2">
            <h3>Trapods V2</h3>
            <p>Encore plus de basses et d’autonomie.</p>
            <span class="prix">129€</span>
        </div>
    </section>

    <section id="about">
        <h2>À propos de TRAPODS</h2>
        <p>Nous avons créé TRAPODS pour offrir des écouteurs sans fil de haute qualité, adaptés aux jeunes qui veulent du style et du son.</p>
    </section>

    <section id="contact">
        <h2>Contactez-nous</h2>
        <form>
            <input type="text" placeholder="Votre nom" required>
            <input type="email" placeholder="Votre email" required>
            <textarea placeholder="Votre message"></textarea>
            <button type="submit">Envoyer</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 TRAPODS - Tous droits réservés.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #111;
    color: #fff;
    text-align: center;
}

header {
    background-color: #222;
    padding: 15px;
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;
}

header h1 {
    margin: 0;
    font-size: 24px;
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
    color: #fff;
    text-decoration: none;
}

section {
    padding: 80px 20px;
}

#accueil {
    background: url('https://via.placeholder.com/1200x400') no-repeat center center/cover;
    padding: 150px 20px;
}

.btn {
    display: inline-block;
    background: #e60000;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
}

.produit {
    display: inline-block;
    background: #222;
    padding: 20px;
    margin: 10px;
    width: 250px;
    border-radius: 5px;
}

.produit img {
    width: 100%;
}

.prix {
    font-weight: bold;
    color: #e60000;
}

form input, form textarea {
    display: block;
    width: 80%;
    margin: 10px auto;
    padding: 10px;
}

button {
    background: #e60000;
    color: #fff;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
}

footer {
    background: #222;
    padding: 10px;
}
