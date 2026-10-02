<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Talleres Rafael Ramírez Quero | La Rambla, Córdoba</title>

<meta name="description" content="Talleres Rafael Ramírez Quero. Taller mecánico en La Rambla, Córdoba. Reparación, mantenimiento, frenos, neumáticos, revisiones y recambios.">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    color: #1f2937;
    background: #ffffff;
    line-height: 1.6;
}

a {
    text-decoration: none;
}

.container {
    width: 92%;
    max-width: 1100px;
    margin: auto;
}

/* CABECERA */

header {
    background: #111827;
    color: white;
    position: sticky;
    top: 0;
    z-index: 100;
}

nav {
    min-height: 70px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 20px;
}

.logo {
    color: white;
    font-size: 18px;
    font-weight: bold;
}

.logo span {
    color: #ef3b32;
}

.menu {
    display: flex;
    gap: 25px;
}

.menu a {
    color: white;
    font-size: 15px;
}

.menu a:hover {
    color: #ef3b32;
}

.btn {
    display: inline-block;
    background: #e6392f;
    color: white;
    padding: 13px 20px;
    border-radius: 8px;
    font-weight: bold;
}

.btn:hover {
    background: #c92e26;
}

/* HERO */

.hero {
    min-height: 620px;
    display: flex;
    align-items: center;
    color: white;

    background:
        linear-gradient(
            rgba(10,15,23,.78),
            rgba(10,15,23,.82)
        ),
        linear-gradient(135deg,#111827,#374151);
}

.hero-content {
    max-width: 750px;
    padding: 80px 0;
}

.badge {
    display: inline-block;
    padding: 8px 14px;
    border-radius: 30px;
    background: rgba(239,59,50,.15);
    border: 1px solid rgba(239,59,50,.5);
    color: #ff8078;
    font-weight: bold;
    margin-bottom: 20px;
}

.hero h1 {
    font-size: clamp(42px,7vw,76px);
    line-height: 1;
    margin-bottom: 25px;
}

.hero p {
    font-size: 19px;
    color: #e5e7eb;
    max-width: 680px;
    margin-bottom: 30px;
}

.hero-buttons {
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
}

.btn-outline {
    display: inline-block;
    padding: 13px 20px;
    border: 1px solid rgba(255,255,255,.5);
    border-radius: 8px;
    color: white;
    font-weight: bold;
}

.btn-outline:hover {
    background: white;
    color: #111827;
}

/* SECCIONES */

section {
    padding: 80px 0;
}

.section-title {
    text-align: center;
    max-width: 720px;
    margin: 0 auto 45px;
}

.section-title h2 {
    font-size: 36px;
    margin-bottom: 12px;
}

.section-title p {
    color: #64748b;
}

/* SERVICIOS */

.services {
    display: grid;
    grid-template-columns: repeat(3,1fr);
    gap: 20px;
}

.card {
    padding: 30px;
    border: 1px solid #e5e7eb;
    border-radius: 15px;
    background: white;
    box-shadow: 0 8px 25px rgba(15,23,42,.05);
}

.card-icon {
    font-size: 38px;
    margin-bottom: 15px;
}

.card h3 {
    margin-bottom: 10px;
    font-size: 20px;
}

.card p {
    color: #64748b;
}

/* SOBRE EL TALLER */

.dark {
    background: #111827;
    color: white;
}

.dark .section-title p {
    color: #cbd5e1;
}

.about {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 35px;
    align-items: center;
}

.about-text h2 {
    font-size: 38px;
    margin-bottom: 15px;
}

.about-text p {
    color: #d1d5db;
    font-size: 17px;
}

.features {
    background: #1f2937;
    border-radius: 15px;
    padding: 30px;
}

.feature {
    display: flex;
    gap: 12px;
    margin: 18px 0;
}

.feature strong {
    color: #ff6258;
}

/* CONTACTO */

.contact {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 25px;
}

.contact-box {
    border: 1px solid #e5e7eb;
    border-radius: 15px;
    padding: 30px;
}

.contact-box h3 {
    font-size: 23px;
    margin-bottom: 12px;
}

.contact-box p {
    color: #64748b;
    margin-bottom: 10px;
}

.phone {
    display: block;
    font-size: 28px;
    color: #e6392f;
    font-weight: bold;
    margin: 15px 0;
}

.map-button {
    display: inline-block;
    background: #111827;
    color: white;
    padding: 12px 18px;
    border-radius: 8px;
    font-weight: bold;
    margin-top: 10px;
}

/* CTA */

.cta {
    background: linear-gradient(135deg,#e6392f,#a91f1a);
    color: white;
    text-align: center;
}

.cta h2 {
    font-size: 38px;
    margin-bottom: 12px;
}

.cta p {
    max-width: 650px;
    margin: auto;
    margin-bottom: 25px;
    color: #ffe5e2;
}

.cta .btn {
    background: white;
    color: #c52b25;
}

/* FOOTER */

footer {
    background: #090e16;
    color: #9ca3af;
    text-align: center;
    padding: 25px;
}

/* MÓVIL */

@media(max-width:800px) {

    .menu {
        display: none;
    }

    .services {
        grid-template-columns: 1fr;
    }

    .about {
        grid-template-columns: 1fr;
    }

    .contact {
        grid-template-columns: 1fr;
    }

    .hero {
        min-height: 570px;
    }

    section {
        padding: 60px 0;
    }

    .hero h1 {
        font-size: 48px;
    }
}
</style>
</head>

<body>

<!-- CABECERA -->

<header>
<div class="container">

<nav>

<a href="#inicio" class="logo">
Talleres <span>Rafael Ramírez Quero</span>
</a>

<div class="menu">
<a href="#servicios">Servicios</a>
<a href="#taller">El taller</a>
<a href="#contacto">Contacto</a>
</div>

<a class="btn" href="tel:+34957684827">
Llamar
</a>

</nav>

</div>
</header>


<!-- INICIO -->

<section class="hero" id="inicio">

<div class="container">

<div class="hero-content">

<div class="badge">
Taller mecánico · La Rambla, Córdoba
</div>

<h1>
Tu coche,<br>
en buenas manos.
</h1>

<p>
En Talleres Rafael Ramírez Quero cuidamos de tu vehículo
con un trato cercano y profesional. Reparaciones,
mantenimiento y revisiones para que puedas volver a la
carretera con tranquilidad.
</p>

<div class="hero-buttons">

<a class="btn" href="tel:+34957684827">
📞 957 684 827
</a>

<a class="btn-outline" href="#contacto">
Ver contacto
</a>

</div>

</div>

</div>

</section>


<!-- SERVICIOS -->

<section id="servicios">

<div class="container">

<div class="section-title">

<h2>
Servicios para tu vehículo
</h2>

<p>
Te ayudamos con el mantenimiento y las reparaciones
que tu vehículo necesita.
</p>

</div>


<div class="services">


<div class="card">

<div class="card-icon">🔧</div>

<h3>
Reparaciones
</h3>

<p>
Diagnóstico y reparación de averías para ayudarte
a volver a la carretera con seguridad y tranquilidad.
</p>

</div>


<div class="card">

<div class="card-icon">🛠️</div>

<h3>
Mantenimiento
</h3>

<p>
Revisiones, cambios de aceite y mantenimiento
general para cuidar tu vehículo.
</p>

</div>


<div class="card">

<div class="card-icon">🚗</div>

<h3>
Frenos y neumáticos
</h3>

<p>
Revisión y sustitución de elementos de desgaste
para mantener tu vehículo en buenas condiciones.
</p>

</div>


<div class="card">

<div class="card-icon">⚙️</div>

<h3>
Recambios y piezas
</h3>

<p>
Sustitución de piezas y recambios necesarios
para reparar y mantener tu vehículo.
</p>

</div>


<div class="card">

<div class="card-icon">🏍️</div>

<h3>
Coche y moto
</h3>

<p>
Soluciones de mantenimiento y reparación
adaptadas a diferentes vehículos.
</p>

</div>


<div class="card">

<div class="card-icon">🔍</div>

<h3>
Revisiones
</h3>

<p>
¿Notas algo extraño en tu vehículo?
Consúltanos y veremos qué necesita.
</p>

</div>


</div>

</div>

</section>


<!-- TALLER -->

<section class="dark" id="taller">

<div class="container">

<div class="about">

<div class="about-text">

<h2>
Un taller para volver a circular tranquilo
</h2>

<p>
Cuando tu coche necesita atención, lo importante es
saber qué ocurre y encontrar una solución.

En Talleres Rafael Ramírez Quero apostamos por un
trato cercano y directo con nuestros clientes.

</p>

</div>


<div class="features">

<div class="feature">
<strong>✓</strong>
<span>Atención cercana y directa.</span>
</div>

<div class="feature">
<strong>✓</strong>
<span>Mantenimiento y reparación.</span>
</div>

<div class="feature">
<strong>✓</strong>
<span>Revisiones y puesta a punto.</span>
</div>

<div class="feature">
<strong>✓</strong>
<span>Frenos y neumáticos.</span>
</div>

<div class="feature">
<strong>✓</strong>
<span>Recambios y sustitución de piezas.</span>
</div>

<div class="feature">
<strong>✓</strong>
<span>Estamos en La Rambla, Córdoba.</span>
</div>

</div>

</div>

</div>

</section>


<!-- CONTACTO -->

<section id="contacto">

<div class="container">

<div class="section-title">

<h2>
¿Necesitas pasar por el taller?
</h2>

<p>
Llámanos y cuéntanos qué le ocurre a tu vehículo.
</p>

</div>


<div class="contact">


<div class="contact-box">

<h3>
📞 Llámanos
</h3>

<p>
Para consultas, información o para saber cuándo
puedes acercarte al taller:
</p>

<a class="phone" href="tel:+34957684827">
957 684 827
</a>

<a class="btn" href="tel:+34957684827">
Llamar al taller
</a>

</div>


<div class="contact-box">

<h3>
📍 Dónde estamos
</h3>

<p>
<strong>
Talleres Rafael Ramírez Quero
</strong>
</p>

<p>
Carretera de Montalbán, km 0,300<br>
Zona La Matallana<br>
14540 La Rambla, Córdoba
</p>

<a
class="map-button"
target="_blank"
rel="noopener"
href="https://www.google.com/maps/search/?api=1&query=Talleres+Rafael+Ramirez+Quero,+La+Rambla,+Cordoba">

Cómo llegar

</a>

</div>


</div>

</div>

</section>


<!-- LLAMADA A LA ACCIÓN -->

<section class="cta">

<div class="container">

<h2>
¿Tu coche necesita una revisión?
</h2>

<p>
No esperes a que una pequeña señal se convierta
en una avería mayor. Ponte en contacto con nosotros
y cuéntanos qué necesitas.
</p>

<a class="btn" href="tel:+34957684827">
📞 Hablar con el taller
</a>

</div>

</section>


<!-- PIE -->

<footer>

<p>
© Talleres Rafael Ramírez Quero · La Rambla, Córdoba
</p>

</footer>


</body>
</html>
