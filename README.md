<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>MindShelf | Build Your Mind</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background: #f3f5f9;
}

/* HERO SECTION */
.hero {
    position: relative;
    height: 85vh;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    overflow: hidden;
}

.hero h1 {
    font-size: 50px;
    margin-bottom: 10px;
    z-index: 2;
}

.hero p {
    font-size: 20px;
    width: 70%;
    z-index: 2;
}

/* SLIDER BACKGROUND */
.slides {
    position: absolute;
    width: 100%;
    height: 100%;
    z-index: 1;
}

.slides img {
    position: absolute;
    width: 100%;
    height: 100%;
    object-fit: cover;
    animation: fade 15s infinite;
    opacity: 0;
}

.slides img:nth-child(1) { animation-delay: 0s; }
.slides img:nth-child(2) { animation-delay: 5s; }
.slides img:nth-child(3) { animation-delay: 10s; }

@keyframes fade {
    0% {opacity: 0;}
    10% {opacity: 1;}
    30% {opacity: 1;}
    40% {opacity: 0;}
    100% {opacity: 0;}
}

/* Overlay */
.hero::after {
    content: "";
    position: absolute;
    width: 100%;
    height: 100%;
    background: rgba(0,0,0,0.6);
    top: 0;
    left: 0;
    z-index: 1;
}

/* CATEGORY SECTION */
.category-title {
    text-align: center;
    margin-top: 50px;
    font-size: 28px;
}

.products {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 20px;
}

.card {
    background: white;
    width: 260px;
    margin: 15px;
    border-radius: 12px;
    box-shadow: 0 6px 18px rgba(0,0,0,0.1);
    overflow: hidden;
    text-align: center;
    transition: transform 0.3s ease;
}

.card:hover {
    transform: translateY(-8px);
}

.card img {
    width: 100%;
    height: 350px;
    object-fit: cover;
}

.card h3 {
    padding: 10px 10px 0 10px;
}

.card p {
    padding: 0 15px;
    font-size: 14px;
}

.btn {
    display: inline-block;
    margin: 15px;
    padding: 10px 15px;
    background: #ff9900;
    color: black;
    text-decoration: none;
    border-radius: 6px;
    font-weight: bold;
}

footer {
    background: #111;
    color: white;
    text-align: center;
    padding: 20px;
    margin-top: 50px;
}
</style>
</head>

<body>

<!-- HERO SECTION WITH SLIDES -->
<section class="hero">
    <div class="slides">
        <img src="https://images.unsplash.com/photo-1512820790803-83ca734da794">
        <img src="https://images.unsplash.com/photo-1495446815901-a7297e633e8d">
        <img src="https://images.unsplash.com/photo-1507842217343-583bb7270b66">
    </div>

    <h1>MindShelf</h1>
    <p>"A reader lives a thousand lives before he dies. The man who never reads lives only one."  
    <br><br>Build your mindset. Grow your knowledge. Transform your life.</p>
</section>


<h2 class="category-title">💰 Finance Books</h2>

<section class="products">

<div class="card">
<img src="https://m.media-amazon.com/images/I/81bsw6fnUiL.jpg">
<h3>Rich Dad Poor Dad</h3>
<p>Master financial mindset and wealth principles.</p>
<a href="YOUR_AFFILIATE_LINK" class="btn" target="_blank">View on Amazon</a>
</div>

<div class="card">
<img src="https://m.media-amazon.com/images/I/71g2ednj0JL.jpg">
<h3>The Psychology of Money</h3>
<p>Understand how behavior influences money success.</p>
<a href="YOUR_AFFILIATE_LINK" class="btn" target="_blank">View on Amazon</a>
</div>

</section>


<h2 class="category-title">🔥 Motivational Books</h2>

<section class="products">

<div class="card">
<img src="https://m.media-amazon.com/images/I/81wgcld4wxL.jpg">
<h3>Atomic Habits</h3>
<p>Build powerful habits and transform your life.</p>
<a href="YOUR_AFFILIATE_LINK" class="btn" target="_blank">View on Amazon</a>
</div>

<div class="card">
<img src="https://m.media-amazon.com/images/I/71aFt4+OTOL.jpg">
<h3>Think and Grow Rich</h3>
<p>Timeless principles for success and achievement.</p>
<a href="YOUR_AFFILIATE_LINK" class="btn" target="_blank">View on Amazon</a>
</div>

</section>


<footer>
<p>Disclosure: As an Amazon Associate, I earn from qualifying purchases.</p>
</footer>

</body>
</html>
