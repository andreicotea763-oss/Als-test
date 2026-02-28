<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meine Website</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #111;
            color: white;
        }

        header {
            background: black;
            padding: 15px;
            text-align: center;
            font-size: 24px;
            font-weight: bold;
        }

        nav {
            background: #222;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: #ff0000;
        }

        section {
            padding: 40px;
            text-align: center;
        }

        .button {
            display: inline-block;
            padding: 12px 20px;
            background: red;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 10px;
        }

        .button:hover {
            background: darkred;
        }

        form {
            max-width: 400px;
            margin: auto;
        }

        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: none;
            border-radius: 5px;
        }

        footer {
            background: black;
            text-align: center;
            padding: 15px;
            margin-top: 40px;
        }
    </style>
</head>

<body>

<header>
    Meine Website
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">Über uns</a>
    <a href="#contact">Kontakt</a>
</nav>

<section id="home">
    <h1>Willkommen auf meiner Website</h1>
    <p>Hier findest du alle wichtigen Informationen.</p>
</section>

<section id="about">
    <h1>Über uns</h1>
    <p>Wir sind ein kreatives Projekt und bauen coole Sachen.</p>
</section>

<section id="contact">
    <h1>Kontakt</h1>

    <p>Du kannst uns direkt eine E-Mail senden:</p>
    <a class="button" href="mailto:andreicotea763@gmail.com">
        E-Mail senden
    </a>

    <h2>Oder schreibe uns hier:</h2>

    <form action="mailto:andreicotea763@gmail.com" method="post" enctype="text/plain">
        <input type="text" name="Name" placeholder="Dein Name" required>
        <input type="email" name="Email" placeholder="Deine E-Mail" required>
        <textarea name="Nachricht" rows="5" placeholder="Deine Nachricht" required></textarea>
        <input type="submit" value="Senden">
    </form>
</section>

<footer>
    © 2026 Meine Website | Alle Rechte vorbehalten
</footer>

</body>
</html>
