
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MindShelf | Build Your Mind</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', sans-serif;
    background: #f4f6f9;
}

/* NAVBAR */
nav {
    background: #111;
    color: white;
    padding: 15px 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav h2 {
    font-size: 24px;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 14px;
}

/* HERO */
.hero {
    height: 90vh;
    background: url('https://images.unsplash.com/photo-1512820790803-83ca734da794') center/cover no-repeat;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
    position: relative;
}

.hero::after {
    content: "";
    position: absolute;
    width: 100%;
    height: 100%;
    background: rgba(0,0,0,0.6);
    top: 0;
    left: 0;
}

.hero-content {
    position: relative;
    z-index: 2;
    max-width: 700px;
}

.hero h1 {
    font-size: 50px;
    margin-bottom: 15px;
}

.hero p {
    font-size: 18px;
    margin-bottom: 20px;
}

.btn-primary {
    background: #ff9900;
    padding: 12px 20px;
    text-decoration: none;
    color: black;
    font-weight: bold;
    border-radius: 6px;
}

/* ABOUT SECTION */
.about {
    padding: 60px 20px;
    text-align: center;
    max-width: 800px;
    margin: auto;
}

.about h2 {
    margin-bottom: 15px;
}

/* BOOK SECTION */
.section-title {
    text-align: center;
    margin-top: 50px;
    font-size: 28px;
}

.books {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 30px;
}

.card {
    background: white;
    width: 260px;
    margin: 15px;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 6px 18px rgba(0,0,0,0.1);
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-8px);
}

.card img {
    width: 100%;
    height: 350px;
    object-fit: cover;
}

.card-content {
    padding: 15px;
    text-align: center;
}

.card-content h3 {
    margin-bottom: 10px;
}

.card-content p {
    font-size: 14px;
    margin-bottom: 10px;
}

footer {
    background: #111;
    color: white;
    text-align: center;
    padding: 25px;
    margin-top: 60px;
    font-size: 14px;
}
</style>
</head>

<body>

<nav>
    <h2>MindShelf</h2>
    <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Finance</a></li>
        <li><a href="#">Motivation</a></li>
        <li><a href="#">Mystery</a></li>
        <li><a href="#">Contact</a></li>
    </ul>
</nav>

<section class="hero">
    <div class="hero-content">
        <h1>Build Your Mind. One Book at a Time.</h1>
        <p>Discover powerful books on finance, growth, productivity and mindset transformation.</p>
        <a href="#" class="btn-primary">Explore Books</a>
    </div>
</section>

<section class="about">
    <h2>About MindShelf</h2>
    <p>MindShelf curates high-impact books that improve financial intelligence, productivity, mindset and success thinking. Our mission is simple — help you grow smarter through reading.</p>
</section>

<h2 class="section-title">💰 Finance Picks</h2>

<section class="books">

<div class="card">
<img src="https://m.media-amazon.com/images/I/81bsw6fnUiL.jpg">
<div class="card-content">
<h3>Rich Dad Poor Dad</h3>
<p>Essential lessons for financial independence.</p>
<a href="YOUR_AFFILIATE_LINK" class="btn-primary" target="_blank">View</a>
</div>
</div>

<div class="card">
<img src="https://m.media-amazon.com/images/I/71g2ednj0JL.jpg">
<div class="card-content">
<h3>The Psychology of Money</h3>
<p>Understand money behaviour deeply.</p>
<a href="YOUR_AFFILIATE_LINK" class="btn-primary" target="_blank">View</a>
</div>
</div>

</section>

<footer>
<p>© 2026 MindShelf | Disclosure: As an Amazon Associate, I earn from qualifying purchases.</p>
</footer>

</body>
</html>
