<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Boulangerie Le Pain d'Or</title>
    <style>
        /* CSS pour le style de la page */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }

        header {
            background-color: #d4a373;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }

        h1 {
            margin: 0;
        }

        nav {
            background-color: #b88a61;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        .section {
            padding: 20px;
            max-width: 800px;
            margin: auto;
        }

        .products {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .product-item {
            background-color: #fff;
            padding: 15px;
            width: 45%;
            margin: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .product-item img {
            width: 100%;
            border-radius: 5px;
            margin-bottom: 10px;
        }

        footer {
            background-color: #d4a373;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }

        .contact-form {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        .contact-form input, .contact-form textarea {
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        .contact-form button {
            padding: 10px;
            background-color: #b88a61;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }

        .contact-form button:hover {
            background-color: #8e6c50;
        }
    </style>
</head>
<body>

    <header>
        <h1>Boulangerie Le Pain d'Or</h1>
        <p>Artisan boulanger depuis 1985</p>
    </header>

    <nav>
        <a href="#about">À propos</a>
        <a href="#products">Nos Produits</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about" class="section">
        <h2>À propos de nous</h2>
        <p>Bienvenue à la Boulangerie Le Pain d'Or, où chaque pain est fait avec passion et tradition. Nous utilisons des ingrédients de qualité pour vous offrir le meilleur des pains, viennoiseries, et pâtisseries.</p>
    </section>

    <section id="products" class="section">
        <h2>Nos Produits</h2>
        <div class="products">
            <div class="product-item">
                <img src="https://via.placeholder.com/150" alt="Baguette Tradition">
                <h3>Baguette Tradition</h3>
                <p>Notre baguette traditionnelle croustillante et moelleuse à l'intérieur.</p>
            </div>
            <div class="product-item">
                <img src="https://via.placeholder.com/150" alt="Croissant">
                <h3>Croissant</h3>
                <p>Un croissant au beurre, feuilleté et doré à la perfection.</p>
            </div>
            <div class="product-item">
                <img src="https://via.placeholder.com/150" alt="Pain au Chocolat">
                <h3>Pain au Chocolat</h3>
                <p>Délicieux pain au chocolat, idéal pour le petit-déjeuner.</p>
            </div>
            <div class="product-item">
                <img src="https://via.placeholder.com/150" alt="Tarte aux Pommes">
                <h3>Tarte aux Pommes</h3>
                <p>Notre tarte aux pommes maison, un dessert classique et savoureux.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="section">
        <h2>Contactez-nous</h2>
        <form class="contact-form" onsubmit="event.preventDefault(); alert('Merci pour votre message !');">
            <input type="text" name="name" placeholder="Votre nom" required>
            <input type="email" name="email" placeholder="Votre email" required>
            <textarea name="message" rows="4" placeholder="Votre message" required></textarea>
            <button type="submit">Envoyer</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2023 Boulangerie Le Pain d'Or - Tous droits réservés</p>
        <p>123 Rue de la Boulangerie, Paris, France</p>
    </footer>

</body>
</html>
