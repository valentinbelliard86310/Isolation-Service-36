body {
  font-family: Arial, sans-serif;
  margin: 0;
  color: #222;
  line-height: 1.6;
}
header, footer {
  background: #0b3c5d;
  color: white;
  padding: 20px;
}
nav a {
  color: white;
  margin-right: 15px;
  text-decoration: none;
  font-weight: bold;
}
.container {
  max-width: 1100px;
  margin: auto;
  padding: 20px;
}
.btn {
  display: inline-block;
  background: #f39c12;
  color: white;
  padding: 12px 20px;
  text-decoration: none;
  border-radius: 4px;
}
form input, form textarea {
  width: 100%;
  padding: 10px;
  margin-bottom: 10px;
}
form button {
  background: #0b3c5d;
  color: white;
  border: none;
  padding: 12px;
  cursor: pointer;
}
footer {
  text-align: center;
}
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Isolation Service 36</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
<header>
  <nav>
    <a href="index.html">Accueil</a>
    <a href="prestations.html">Prestations</a>
    <a href="aides.html">Aides</a>
    <a href="apropos.html">À propos</a>
    <a href="contact.html">Contact</a>
  </nav>
</header>

<div class="container">
  <h1>Isolation Service 36</h1>
  <p>Spécialiste de l’isolation thermique dans l’Indre.</p>
  <a class="btn" href="contact.html">Demander un devis gratuit</a>
</div>

<footer>
  <p>contact@isolationservice.com</p>
</footer>
</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Prestations</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<header>
<nav>
<a href="index.html">Accueil</a>
<a href="contact.html">Contact</a>
</nav>
</header>

<div class="container">
<h1>Nos prestations</h1>
<ul>
<li><a href="combles.html">Isolation des combles</a></li>
<li><a href="murs.html">Isolation des murs</a></li>
</ul>
</div>

<footer><p>contact@isolationservice.com</p></footer>
</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Isolation des combles</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<header><nav><a href="index.html">Accueil</a></nav></header>

<div class="container">
<h1>Isolation des combles</h1>
<p>Solution la plus efficace pour réduire les pertes de chaleur.</p>
</div>

<footer><p>contact@isolationservice.com</p></footer>
</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Isolation des murs</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<header><nav><a href="index.html">Accueil</a></nav></header>

<div class="container">
<h1>Isolation des murs</h1>
<p>Améliorez durablement le confort thermique de votre logement.</p>
</div>

<footer><p>contact@isolationservice.com</p></footer>
</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Aides</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<header><nav><a href="index.html">Accueil</a></nav></header>

<div class="container">
<h1>Aides et subventions</h1>
<p>MaPrimeRénov’, CEE et aides locales selon éligibilité.</p>
</div>

<footer><p>contact@isolationservice.com</p></footer>
</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>À propos</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<header><nav><a href="index.html">Accueil</a></nav></header>

<div class="container">
<h1>Pourquoi nous choisir</h1>
<p>Entreprise locale, sérieuse et orientée résultats.</p>
</div>

<footer><p>contact@isolationservice.com</p></footer>
</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Contact</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<header><nav><a href="index.html">Accueil</a></nav></header>

<div class="container">
<h1>Contact / Devis gratuit</h1>

<form name="contact" method="POST" data-netlify="true">
<input type="hidden" name="form-name" value="contact">
<input type="text" name="nom" placeholder="Nom" required>
<input type="email" name="email" placeholder="Email" required>
<textarea name="message" placeholder="Votre demande" required></textarea>
<button type="submit">Envoyer</button>
</form>

</div>

<footer><p>contact@isolationservice.com</p></footer>
</body>
</html>
