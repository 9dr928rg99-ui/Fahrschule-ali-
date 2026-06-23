# Fahrschule-ali-
<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Fahrschule Ali</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
scroll-behavior:smooth;
font-family:'Poppins',sans-serif;
}

body{
background:#f4f6f9;
color:#222;
}

nav{
position:fixed;
width:100%;
top:0;
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 8%;
background:rgba(15,23,42,.95);
color:white;
z-index:1000;
}

nav ul{
display:flex;
list-style:none;
gap:25px;
}

nav a{
color:white;
text-decoration:none;
font-size:15px;
}

.hero{
height:100vh;
background:
linear-gradient(rgba(0,0,0,.5),rgba(0,0,0,.5)),
url("https://images.unsplash.com/photo-1503376780353-7e6692767b70?q=80&w=1500");
background-size:cover;
background-position:center;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
color:white;
padding:20px;
}

.hero h1{
font-size:60px;
margin-bottom:20px;
}

.hero p{
font-size:22px;
margin-bottom:25px;
}

.btn{
padding:14px 30px;
background:#2563eb;
color:white;
text-decoration:none;
border-radius:30px;
font-weight:bold;
}

section{
padding:100px 8%;
}

.title{
font-size:35px;
margin-bottom:40px;
text-align:center;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:white;
padding:25px;
border-radius:20px;
box-shadow:0 5px 15px rgba(0,0,0,.1);
transition:.3s;
}

.card:hover{
transform:translateY(-10px);
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:20px;
}

.gallery img{
width:100%;
height:250px;
object-fit:cover;
border-radius:20px;
}

.contact{
background:#0f172a;
color:white;
border-radius:30px;
padding:40px;
}

footer{
padding:25px;
background:#0f172a;
color:white;
text-align:center;
}

</style>
</head>

<body>

<nav>
<h2>Fahrschule Ali</h2>

<ul>
<li><a href="#leistungen">Leistungen</a></li>
<li><a href="#bilder">Bilder</a></li>
<li><a href="#zeiten">Zeiten</a></li>
<li><a href="#kontakt">Kontakt</a></li>
</ul>

</nav>

<div class="hero">

<div>

<h1>Fahrschule Ali</h1>

<p>PKW & Motorrad Ausbildung</p>

<a class="btn" href="#kontakt">Jetzt anmelden</a>

</div>

</div>

<section id="leistungen">

<h2 class="title">Unsere Leistungen</h2>

<div class="cards">

<div class="card">
<h3>🚗 Klasse B</h3>
<p>Komplette PKW-Ausbildung mit Theorie und Praxis.</p>
</div>

<div class="card">
<h3>🏍 Klasse A</h3>
<p>Motorrad-Ausbildung für Anfänger und Fortgeschrittene.</p>
</div>

<div class="card">
<h3>👨‍🏫 Theorieunterricht</h3>
<p>Moderne Schulung mit verständlicher Erklärung.</p>
</div>

<div class="card">
<h3>⭐ Flexible Zeiten</h3>
<p>Passende Zeiten für Schüler und Berufstätige.</p>
</div>

</div>

</section>

<section id="bilder">

<h2 class="title">Fahrschul Galerie</h2>

<div class="gallery">

<img src="https://images.unsplash.com/photo-1552519507-da3b142c6e3d?q=80&w=1000">

<img src="https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?q=80&w=1000">

<img src="https://images.unsplash.com/photo-1449965408869-eaa3f722e40d?q=80&w=1000">

<img src="https://images.unsplash.com/photo-1558981806-ec527fa84c39?q=80&w=1000">

</div>

</section>

<section id="zeiten">

<h2 class="title">Büro & Unterrichtszeiten</h2>

<div class="cards">

<div class="card">
<h3>Bürozeiten</h3>

Montag – Freitag<br><br>

11:00–13:00 Uhr<br>
15:00–17:00 Uhr

</div>

<div class="card">
<h3>Klasse B</h3>

Montag<br>
18:30–20:00 Uhr

<br><br>

Mittwoch<br>
18:30–20:00 Uhr

</div>

<div class="card">
<h3>Klasse A</h3>

Freitag<br>
18:30–20:00 Uhr

</div>

</div>

</section>

<section id="kontakt">

<div class="contact">

<h2>Kontakt</h2>

<br>

📍 Oberhausener Straße 189<br>
45476 Mülheim an der Ruhr

<br><br>

📞 0208 / 7414545-0

<br><br>

✉ info@fahrschule-ali.de

<br><br>

🌐 www.fahrschule-ali.de

<br><br>

<a class="btn" href="tel:020874145450">Jetzt anrufen</a>

</div>

</section>

<footer>

© 2026 Fahrschule Ali

</footer>

</body>
</html>