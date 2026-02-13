<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Purrfectly Crafted</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', sans-serif;
}

body {
    background: linear-gradient(135deg, #ff758c, #ff7eb3);
    color: white;
    overflow-x: hidden;
}

nav {
    display: flex;
    justify-content: space-between;
    padding: 20px 10%;
    background: rgba(255,255,255,0.1);
    backdrop-filter: blur(10px);
    position: sticky;
    top: 0;
}

nav h2 {
    font-weight: 600;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
    transition: 0.3s;
}

nav a:hover {
    color: #222;
}

.hero {
    text-align: center;
    padding: 100px 20px;
}

.hero h1 {
    font-size: 60px;
    animation: fadeIn 1.5s ease-in-out;
}

.hero p {
    font-size: 20px;
    margin: 20px 0;
}

button {
    padding: 12px 25px;
    border: none;
    border-radius: 30px;
    background: white;
    color: #ff4f81;
    font-weight: bold;
    cursor: pointer;
    transition: 0.3s;
}

button:hover {
    transform: scale(1.1);
}

.section {
    padding: 80px 10%;
}

.card-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.card {
    background: rgba(255,255,255,0.15);
    padding: 25px;
    border-radius: 20px;
    backdrop-filter: blur(15px);
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-10px);
}

footer {
    text-align: center;
    padding: 30px;
    background: rgba(0,0,0,0.2);
}

@keyframes fadeIn {
    from {opacity: 0; transform: translateY(30px);}
    to {opacity: 1; transform: translateY(0);}
}
</style>
</head>

<body>

<nav>
    <h2>Purrfectly Crafted</h2>
    <div>
        <a href="#services">Services</a>
        <a href="#deal">Special Deal</a>
        <a href="#contact">Contact</a>
    </div>
</nav>

<div class="hero">
    <h1>Perfect pets. Perfect match. Just missing you.</h1>
    <p>Pre-trained animals ready for loving homes.</p>
    <button onclick="alert('Call 202-456-1111 to adopt today!')">Adopt Now</button>
</div>

<div class="section" id="services">
    <h2>Our Services</h2>
    <br><br>
    <div class="card-container">
        <div class="card">
            <h3>Pre-Trained Pets</h3>
            <p>Animals ready to join your family immediately.</p>
        </div>
        <div class="card">
            <h3>3 Free Months Supplies</h3>
            <p>Food, bedding, and starter kits included.</p>
        </div>
        <div class="card">
            <h3>Pet Insurance</h3>
            <p>Affordable coverage options for peace of mind.</p>
        </div>
        <div class="card">
            <h3>Animal Café Experience</h3>
            <p>Dinner, lunch, or breakfast date with 5 animals of your choice.</p>
        </div>
    </div>
</div>

<div class="section" id="deal">
    <h2>Special Flyer Deal</h2>
    <br>
    <p>See our flyer? Book a meal date with 5 animals of your choice — like a cat café!</p>
</div>

<div class="section" id="contact">
    <h2>Contact Us</h2>
    <br>
    <p><strong>Location:</strong> 5400 South Tryon Street</p>
    <p><strong>Phone:</strong> 202-456-1111</p>
    <p><strong>Website:</strong> www.purrfectlycrafted.com</p>
</div>

<footer>
    © 2026 Purrfectly Crafted | Giving Pets the Perfect Match
</footer>

</body>
</html>
