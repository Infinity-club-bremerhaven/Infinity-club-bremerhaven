<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Infinity Club Bremerhaven</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src= https://i.postimg.cc/G2CBXm9h/IMG-2788.jpg alt="Infinity Club Logo" class="logo">
        <h1>Infinity Club Bremerhaven</h1>
        <p>Adresse: Bürgermeister-Kirschbaum-Platz 7-10, 27580 Bremerhaven</p>
        <p>Telefonnummern: 0152/03924855 | 0176/31292627</p>
    </header>

    <section class="events">
        <h2>Nächste Clubnächte</h2>
        <ul>
            <li>Clubnacht: 28. Oktober 2024 - DJ Ray</li>
            <li>Clubnacht: 4. November 2024 - DJ Lisa</li>
            <li>Clubnacht: 11. November 2024 - DJ Chris</li>
        </ul>
        <a href="#" class="buy-tickets">Tickets kaufen</a>
    </section>

    <section class="gallery">
        <h2>Bilder von der letzten Clubnacht</h2>
        <div class="images">
            <img src="image1.jpg" alt="Clubnacht Bild 1">
            <img src="image2.jpg" alt="Clubnacht Bild 2">
            <img src="image3.jpg" alt="Clubnacht Bild 3">
        </div>
    </section>

    <section class="social-media">
        <h2>Folge uns auf Social Media</h2>
        <a href="https://www.instagram.com/INFINITY_CLUB_BREMERHAVEN" target="_blank">@INFINITY_CLUB_BREMERHAVEN</a>
    </section>

    <footer>
        <p>&copy; 2024 Infinity Club Bremerhaven. Alle Rechte vorbehalten.</p>
    </footer>
</body>
</html>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: black;
    color: white;
    text-align: center;
}

header {
    padding: 20px;
    background-color: #2a003e;
}

.logo {
    width: 150px;
    height: auto;
}

h1 {
    font-size: 2.5em;
    color: #b88aff;
}

.events, .gallery, .social-media {
    padding: 30px;
}

h2 {
    color: #b88aff;
}

ul {
    list-style: none;
    padding: 0;
    font-size: 1.2em;
}

ul li {
    margin: 10px 0;
}

.buy-tickets {
    display: inline-block;
    margin-top: 20px;
    padding: 10px 20px;
    background-color: #b88aff;
    color: black;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
}

.buy-tickets:hover {
    background-color: #ffffff;
    color: black;
}

.gallery .images {
    display: flex;
    justify-content: center;
    gap: 15px;
}

.gallery .images img {
    width: 200px;
    height: 150px;
    object-fit: cover;
    border: 2px solid #b88aff;
}

.social-media a {
    display: inline-block;
    margin-top: 10px;
    color: #b88aff;
    text-decoration: none;
    font-size: 1.5em;
}

.social-media a:hover {
    color: white;
}

footer {
    background-color: #2a003e;
    padding: 10px 0;
    color: white;
    font-size: 0.9em;
}
