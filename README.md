# OLAOLA-AMALA-CANTEEN
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Ola-Ola Food Canteen | Authentic Nigerian Food</title>

<style>
:root {
    --primary: #113689;
    --accent: #f8c21a;
    --dark: #111;
    --light: #f7f8fb;
    --white: #fff;
    --green: #25D366;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}

html {
    scroll-behavior: smooth;
}

body {
    background: var(--light);
    color: #222;
    line-height: 1.6;
}

/* TOP BAR */

.top-bar {
    background: var(--accent);
    color: #000;
    text-align: center;
    padding: 9px;
    font-weight: bold;
    font-size: 14px;
}

/* NAVIGATION */

header {
    background: var(--primary);
    color: white;
    padding: 15px 5%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: sticky;
    top: 0;
    z-index: 1000;
    box-shadow: 0 3px 12px rgba(0,0,0,.2);
}

.logo h1 {
    color: var(--accent);
    font-size: 25px;
}

.logo p {
    font-size: 11px;
    text-transform: uppercase;
    letter-spacing: 2px;
}

.nav-links {
    display: flex;
    gap: 20px;
    align-items: center;
}

.nav-links a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

.nav-links a:hover {
    color: var(--accent);
}

.call-btn {
    background: var(--accent);
    color: #000 !important;
    padding: 9px 16px;
    border-radius: 20px;
}

/* HERO */

.hero {
    min-height: 520px;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: white;

    background:
        linear-gradient(rgba(17,54,137,.85), rgba(0,0,0,.75)),
        url("https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=1600&q=80")
        center/cover;
}

.hero-content {
    max-width: 800px;
    padding: 30px;
}

.hero h2 {
    color: var(--accent);
    font-size: 48px;
    margin-bottom: 15px;
}

.hero p {
    font-size: 19px;
    margin-bottom: 25px;
}

.buttons {
    display: flex;
    justify-content: center;
    gap: 12px;
    flex-wrap: wrap;
}

.btn {
    display: inline-block;
    padding: 13px 24px;
    border-radius: 6px;
    text-decoration: none;
    font-weight: bold;
}

.btn-yellow {
    background: var(--accent);
    color: #000;
}

.btn-white {
    border: 2px solid white;
    color: white;
}

.btn-green {
    background: var(--green);
    color: white;
}

/* GENERAL */

.section {
    padding: 60px 5%;
    max-width: 1200px;
    margin: auto;
}

.title {
    text-align: center;
    margin-bottom: 35px;
}

.title h2 {
    color: var(--primary);
    font-size: 34px;
}

.title p {
    color: #666;
}

/* MENU */

.menu-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.menu-card {
    background: white;
    padding: 22px;
    border-radius: 12px;
    box-shadow: 0 4px 15px rgba(0,0,0,.08);
    border-top: 5px solid var(--primary);
}

.menu-card h3 {
    color: var(--primary);
    margin-bottom: 15px;
    font-size: 22px;
}

.food-item {
    display: flex;
    justify-content: space-between;
    gap: 10px;
    padding: 11px 0;
    border-bottom: 1px solid #eee;
}

.food-name {
    font-weight: bold;
}

.price {
    color: var(--primary);
    font-weight: bold;
    white-space: nowrap;
}

/* ORDER BUTTON */

.order-btn {
    width: 100%;
    border: none;
    background: var(--green);
    color: white;
    padding: 11px;
    margin-top: 15px;
    border-radius: 6px;
    font-weight: bold;
    cursor: pointer;
    font-size: 15px;
}

.order-btn:hover {
    opacity: .85;
}

/* ABOUT */

.about {
    background: white;
}

.about-box {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 40px;
    align-items: center;
}

.about-box img {
    width: 100%;
    border-radius: 15px;
}

.about-text h2 {
    color: var(--primary);
    margin-bottom: 15px;
}

.about-text p {
    margin-bottom: 15px;
}

/* CATERING */

.catering {
    background: var(--primary);
    color: white;
    text-align: center;
    border-radius: 15px;
    padding: 50px 25px;
}

.catering h2 {
    color: var(--accent);
    font-size: 32px;
    margin-bottom: 15px;
}

.catering p {
    max-width: 700px;
    margin: auto auto 25px;
}

/* CONTACT */

.contact-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
    gap: 20px;
}

.contact-card {
    background: white;
    padding: 25px;
    text-align: center;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0,0,0,.07);
}

.contact-card h3 {
    color: var(--primary);
    margin-bottom: 10px;
}

.contact-card a {
    color: var(--primary);
    font-weight: bold;
    text-decoration: none;
}

/* FOOTER */

footer {
    background: var(--dark);
    color: white;
    text-align: center;
    padding: 35px 20px;
}

footer h2 {
    color: var(--accent);
    margin-bottom: 10px;
}

footer p {
    color: #ccc;
    margin: 5px 0;
}

.copyright {
    margin-top: 20px;
    font-size: 12px;
}

/* WHATSAPP FLOATING BUTTON */

.whatsapp {
    position: fixed;
    right: 20px;
    bottom: 20px;
    background: var(--green);
    color: white;
    width: 58px;
    height: 58px;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    text-decoration: none;
    font-size: 27px;
    box-shadow: 0 4px 15px rgba(0,0,0,.3);
    z-index: 999;
}

/* MOBILE */

@media(max-width: 700px) {

    .nav-links {
        display: none;
    }

    .hero {
        min-height: 480px;
    }

    .hero h2 {
        font-size: 35px;
    }

    .hero p {
        font-size: 16px;
    }

    .about-box {
        grid-template-columns: 1fr;
    }

    .section {
        padding: 45px 5%;
    }

    .title h2 {
        font-size: 28px;
    }
}
</style>
</head>

<body>

<!-- TOP BAR -->

<div class="top-bar">
    🍛 Fresh Nigerian Food • 🥘 Authentic Taste • 📍 Mushin, Lagos
</div>

<!-- HEADER -->

<header>

    <div class="logo">
        <h1>OLA-OLA</h1>
        <p>Food Canteen</p>
    </div>

    <nav class="nav-links">
        <a href="#home">Home</a>
        <a href="#menu">Menu</a>
        <a href="#about">About</a>
        <a href="#catering">Catering</a>
        <a href="#contact">Contact</a>

        <a class="call-btn" href="tel:+2348039222123">
            Call Now
        </a>
    </nav>

</header>

<!-- HERO -->

<section class="hero" id="home">

    <div class="hero-content">

        <h2>Taste Real Nigerian Food</h2>

        <p>
            Enjoy freshly prepared Amala, Eba, Pounded Yam,
            Jollof Rice, assorted soups, meat, fish and more.
        </p>

        <div class="buttons">

            <a class="btn btn-yellow"
               href="#menu">
                View Our Menu
            </a>

            <a class="btn btn-green"
               href="https://wa.me/2348039222123?text=Hello%20Ola-Ola%20Food%20Canteen,%20I%20want%20to%20place%20an%20order">
                Order on WhatsApp
            </a>

        </div>

    </div>

</section>

<!-- MENU -->

<section class="section" id="menu">

    <div class="title">

        <h2>Our Menu</h2>

        <p>
            Freshly prepared meals at Ola-Ola Food Canteen
        </p>

    </div>

    <div class="menu-grid">

        <!-- RICE -->

        <div class="menu-card">

            <h3>🍚 Rice & Meals</h3>

            <div class="food-item">
                <span class="food-name">White Rice</span>
                <span class="price">₦200</span>
            </div>

            <div class="food-item">
                <span class="food-name">Jollof Rice</span>
                <span class="price">₦200</span>
            </div>

            <div class="food-item">
                <span class="food-name">Spaghetti</span>
                <span class="price">₦200</span>
            </div>

            <div class="food-item">
                <span class="food-name">Yam</span>
                <span class="price">₦200</span>
            </div>

            <div class="food-item">
                <span class="food-name">Yam Porridge</span>
                <span class="price">₦300</span>
            </div>

            <button class="order-btn"
                onclick="order('Rice & Meals')">
                Order This Category
            </button>

        </div>

        <!-- SWALLOW -->

        <div class="menu-card">

            <h3>🥘 Swallow</h3>

            <div class="food-item">
                <span class="food-name">Eba</span>
                <span class="price">₦200</span>
            </div>

            <div class="food-item">
                <span class="food-name">Semolina</span>
                <span class="price">₦200</span>
            </div>

            <div class="food-item">
                <span class="food-name">Amala</span>
                <span class="price">₦200</span>
            </div>

            <div class="food-item">
                <span class="food-name">Pounded Yam</span>
                <span class="price">₦300</span>
            </div>

            <button class="order-btn"
                onclick="order('Swallow')">
                Order This Category
            </button>

        </div>

        <!-- SOUPS -->

        <div class="menu-card">

            <h3>🍲 Soups</h3>

            <div class="food-item">
                <span class="food-name">Egusi / Melon Soup</span>
            </div>

            <div class="food-item">
                <span class="food-name">Vegetable Soup</span>
            </div>

            <div class="food-item">
                <span class="food-name">Okra Soup</span>
            </div>

            <div class="food-item">
                <span class="food-name">Ewedu</span>
            </div>

            <div class="food-item">
                <span class="food-name">Beans Soup</span>
            </div>

            <button class="order-btn"
                onclick="order('Soups')">
                Ask About Soups
            </button>

        </div>

        <!-- PROTEINS -->

        <div class="menu-card">

            <h3>🍖 Proteins</h3>

            <div class="food-item">
                <span class="food-name">Meat</span>
                <span class="price">₦200</span>
            </div>

            <div class="food-item">
                <span class="food-name">Egg</span>
                <span class="price">₦300</span>
            </div>

            <div class="food-item">
                <span class="food-name">Fish</span>
                <span class="price">₦500+</span>
            </div>

            <div class="food-item">
                <span class="food-name">Cow Leg</span>
                <span class="price">₦1,000</span>
            </div>

            <div class="food-item">
                <span class="food-name">Goat Meat</span>
                <span class="price">₦2,000</span>
            </div>

            <button class="order-btn"
                onclick="order('Proteins')">
                Order Protein
            </button>

        </div>

        <!-- BREAD -->

        <div class="menu-card">

            <h3>🍞 Bread</h3>

            <div class="food-item">
                <span class="food-name">Bread</span>
                <span class="price">₦300</span>
            </div>

            <div class="food-item">
                <span class="food-name">Bread</span>
                <span class="price">₦400</span>
            </div>

            <div class="food-item">
                <span class="food-name">Bread</span>
                <span class="price">₦500</span>
            </div>

            <div class="food-item">
                <span class="food-name">Bread</span>
                <span class="price">₦700</span>
            </div>

            <button class="order-btn"
                onclick="order('Bread')">
                Order Bread
            </button>

        </div>

        <!-- DRINKS -->

        <div class="menu-card">

            <h3>🥤 Drinks</h3>

            <div class="food-item">
                <span class="food-name">Bottled Water</span>
                <span class="price">₦200</span>
            </div>

            <div class="food-item">
                <span class="food-name">Soft Drinks</span>
                <span class="price">₦500</span>
            </div>

            <button class="order-btn"
                onclick="order('Drinks')">
                Order Drinks
            </button>

        </div>

    </div>

</section>

<!-- ABOUT -->

<section class="section about" id="about">

    <div class="about-box">

        <img
        src="https://images.unsplash.com/photo-1547592180-85f173990554?auto=format&fit=crop&w=900&q=80"
        alt="Nigerian food">

        <div class="about-text">

            <h2>About Ola-Ola Food Canteen</h2>

            <p>
                Ola-Ola Food Canteen serves delicious Nigerian
                meals prepared with authentic ingredients and
                traditional cooking methods.
            </p>

            <p>
                From Amala and Eba to Jollof Rice, Pounded Yam,
                soups, meat and fish, we aim to provide tasty,
                affordable meals for our customers.
            </p>

            <a class="btn btn-yellow"
               href="https://wa.me/2348039222123?text=Hello%20Ola-Ola%20Food%20Canteen">
                Chat With Us
            </a>

        </div>

    </div>

</section>

<!-- CATERING -->

<section class="section" id="catering">

    <div class="catering">

        <h2>🎉 Outdoor Catering</h2>

        <p>
            Planning a wedding, birthday, party, meeting,
            corporate event or private celebration?
            Ola-Ola Food Canteen provides catering services
            for events across Lagos.
        </p>

        <a class="btn btn-yellow"
           href="tel:+2349080335696">
            Book Catering Service
        </a>

    </div>

</section>

<!-- CONTACT -->

<section class="section" id="contact">

    <div class="title">

        <h2>Contact Ola-Ola</h2>

        <p>We are ready to serve you.</p>

    </div>

    <div class="contact-grid">

        <div class="contact-card">

            <h3>📞 Call Us</h3>

            <a href="tel:+2348039222123">
                +234 803 922 2123
            </a>

            <br>

            <a href="tel:+2349080335696">
                +234 908 033 5696
            </a>

        </div>

        <div class="contact-card">

            <h3>💬 WhatsApp</h3>

            <a href="https://wa.me/2348039222123">
                Chat on WhatsApp
            </a>

        </div>

        <div class="contact-card">

            <h3>📍 Location</h3>

            <p>
                2, Oluaina Street,<br>
                Off Isolo Road,<br>
                Mushin, Lagos
            </p>

        </div>

    </div>

</section>

<!-- FOOTER -->

<footer>

    <h2>OLA-OLA FOOD CANTEEN</h2>

    <p>
        Authentic Nigerian Food • Fresh • Affordable • Delicious
    </p>

    <p>
        📍 2, Oluaina Street, Off Isolo Road, Mushin, Lagos
    </p>

    <p>
        📞 +234 803 922 2123
    </p>

    <p>
        📞 +234 908 033 5696
    </p>

    <p class="copyright">
        © 2026 Ola-Ola Food Canteen. All Rights Reserved.
    </p>

</footer>

<!-- FLOATING WHATSAPP -->

<a class="whatsapp"
   href="https://wa.me/2348039222123?text=Hello%20Ola-Ola%20Food%20Canteen,%20I%20want%20to%20place%20an%20order"
   aria-label="WhatsApp">
    💬
</a>

<!-- JAVASCRIPT -->

<script>

function order(category) {

    const message =
        "Hello Ola-Ola Food Canteen 👋%0A%0A" +
        "I want to order from the " +
        category +
        " category.%0A%0A" +
        "Please send me the available options.";
images/
├── white-rice.jpg
├── jollof-rice.jpg
├── amala.jpg
├── eba.jpg
├── semolina.jpg
├── beans.jpg
├── yam.jpg
├── yam-porridge.jpg
├── pounded-yam.jpg
├── spaghetti.jpg
├── egg.jpg
├── meat.jpg
├── fish.jpg
├── goat-meat.jpg
├── cow-leg.jpg
├── egusi-soup.jpg
├── vegetable-soup.jpg
├── okra-soup.jpg
├── ewedu.jpg
├── beans-soup.jpg
├── bread.jpg
├── soft-drink.jpg
└── water.jpg
    window.location.href =
        "https://wa.me/2348039222123?text=" + message;
}

</script>

</body>
</html>