<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Desihut Restaurant | Hyderabad</title>

<style>

/* General */
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #f8f8f8;
}

h2 {
    color: #b22222;
}

/* Navbar */
nav {
    background-color: #b22222;
    padding: 15px;
    position: sticky;
    top: 0;
}

nav h1 {
    color: white;
    display: inline;
}

nav ul {
    list-style: none;
    float: right;
}

nav ul li {
    display: inline;
    margin-left: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

/* Hero */
.hero {
    background: url('restaurant.jpg') center/cover no-repeat;
    height: 400px;
    color: white;
    text-align: center;
    padding-top: 150px;
}

.hero h2 {
    font-size: 40px;
    color: white;
}

.hero button {
    padding: 12px 25px;
    background-color: #ff4500;
    border: none;
    color: white;
    font-size: 16px;
    cursor: pointer;
}

/* Sections */
section {
    padding: 40px;
    text-align: center;
}

/* Menu Gallery */
.menu-gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.menu-image {
    background: white;
    margin: 15px;
    padding: 10px;
    border-radius: 10px;
    width: 250px;
}

.menu-image img {
    width: 100%;
    border-radius: 10px;
}

/* Services */
.services-box {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.service {
    background: white;
    margin: 10px;
    padding: 20px;
    width: 250px;
    border-radius: 10px;
}

/* Contact */
.contact {
    background-color: #eee;
}

/* Footer */
footer {
    background-color: #b22222;
    color: white;
    padding: 15px;
}

/* Mobile */
@media(max-width:768px){

nav ul {
float:none;
text-align:center;
margin-top:10px;
}

nav ul li {
display:block;
margin:10px 0;
}

.hero {
height:300px;
padding-top:100px;
}

}

</style>

</head>

<body>

<!-- Navbar -->

<nav>

<h1>Desihut Restaurant</h1>

<ul>
<li><a href="#">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#menu">Menu</a></li>
<li><a href="#gallery">Gallery</a></li>
<li><a href="#services">Services</a></li>
<li><a href="#contact">Contact</a></li>
</ul>

</nav>

<!-- Hero -->

<div class="hero">

<h2>Welcome to Desihut Restaurant</h2>

<p>Authentic Pakistani, BBQ & Chinese Cuisine</p>

<button onclick="location.href='#menu'">
View Menu
</button>

</div>

<!-- About -->

<section id="about">

<h2>About Us</h2>

<p>
Welcome to Desihut Restaurant — one of the popular family dining restaurants in Hyderabad.
We serve delicious Pakistani, BBQ, Chinese, and fast food dishes made with fresh ingredients.
Perfect for family dinners, birthdays, and gatherings.
</p>

</section>

<!-- Menu -->

<section id="menu">

<h2>Our Menu</h2>

<p>Explore our delicious dishes.</p>

<div class="menu-gallery">

<div class="menu-image">
<img src="menu1.jpg">
<p>Biryani & Rice Menu</p>
</div>

<div class="menu-image">
<img src="menu2.jpg">
<p>BBQ & Pakistani Menu</p>
</div>

<div class="menu-image">
<img src="menu3.jpg">
<p>Chinese Menu</p>
</div>

<div class="menu-image">
<img src="menu4.jpg">
<p>Fast Food Menu</p>
</div>

<div class="menu-image">
<img src="menu5.jpg">
<p>Desserts Menu</p>
</div>

</div>

</section>

<!-- Gallery -->

<section id="gallery">

<h2>Food Gallery</h2>

<div class="menu-gallery">

<div class="menu-image">
<img src="biryani.jpg">
<p>Chicken Biryani</p>
</div>

<div class="menu-image">
<img src="bbq.jpg">
<p>BBQ Platter</p>
</div>

<div class="menu-image">
<img src="karahi.jpg">
<p>Mutton Karahi</p>
</div>

<div class="menu-image">
<img src="burger.jpg">
<p>Zinger Burger</p>
</div>

</div>

</section>

<!-- Services -->

<section id="services">

<h2>Our Services</h2>

<div class="services-box">

<div class="service">
<h3>Dine-In</h3>
<p>Enjoy meals in a comfortable family environment.</p>
</div>

<div class="service">
<h3>Takeaway</h3>
<p>Order food and enjoy at home.</p>
</div>

<div class="service">
<h3>Birthday Parties</h3>
<p>Celebrate special events with us.</p>
</div>

<div class="service">
<h3>Family Dining</h3>
<p>Spacious seating for families.</p>
</div>

</div>

</section>

<!-- Contact -->

<section id="contact" class="contact">

<h2>Contact Us</h2>

<p>
📍 Address:<br>
Banglow No A/2, Auto Bahn Road, Latifabad Unit #3, Hyderabad
</p>

<p>
📞 Phone:<br>
0314-3666277
</p>

<p>
🕒 Opening Hours:<br>
12:00 PM – 12:30 AM
</p>

<!-- Google Map -->

<iframe
src="https://www.google.com/maps?q=Desihut%20Restaurant%20Hyderabad&output=embed"
width="100%"
height="300"
style="border:0;"
allowfullscreen=""
loading="lazy">
</iframe>

</section>

<!-- Footer -->

<footer>

<p>
© 2026 Desihut Restaurant | All Rights Reserved
</p>

</footer>

</body>

</html>
restaurant.jpg
menu1.jpg
menu2.jpg
menu3.jpg
menu4.jpg
menu5.jpg

biryani.jpg
bbq.jpg
karahi.jpg
burger.jpg
