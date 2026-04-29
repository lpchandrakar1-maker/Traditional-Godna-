# Traditional-Godna-
Godna is a traditional tattoo art deeply rooted in Indian tribal culture it. 
<!DOCTYPE html><html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Traditional Godna</title><link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet"><style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body {
    background: #fff8f2;
}

/* HEADER */
header {
    background: #4a1f07;
    color: white;
    padding: 15px;
    text-align: center;
}

nav {
    background: #7a3b12;
    display: flex;
    justify-content: center;
    gap: 20px;
    padding: 10px;
}

nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

nav a:hover {
    color: yellow;
}

/* HERO */
.hero {
    height: 90vh;
    background: url('https://images.unsplash.com/photo-1603415526960-f7e0328c63b1') no-repeat center/cover;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    text-align: center;
}

.hero h1 {
    font-size: 40px;
    background: rgba(0,0,0,0.5);
    padding: 15px;
    border-radius: 10px;
}

/* SECTION */
.section {
    padding: 40px 20px;
    text-align: center;
}

.section h2 {
    margin-bottom: 20px;
}

/* GALLERY */
.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 15px;
}

.gallery img {
    width: 100%;
    border-radius: 10px;
    transition: 0.3s;
}

.gallery img:hover {
    transform: scale(1.05);
}

/* CONTACT */
form {
    max-width: 400px;
    margin: auto;
}

input, textarea {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border-radius: 5px;
    border: 1px solid gray;
}

button {
    background: #7a3b12;
    color: white;
    border: none;
    padding: 10px;
    cursor: pointer;
    width: 100%;
}

button:hover {
    background: #4a1f07;
}

/* FOOTER */
footer {
    background: #4a1f07;
    color: white;
    text-align: center;
    padding: 10px;
}
</style></head><body><header>
    <h1>Traditional Godna</h1>
    <p>Ancient Tribal Tattoo Art</p>
</header><nav>
    <a href="#">Home</a>
    <a href="#about">About</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
</nav><div class="hero">
    <h1>Discover the Beauty of Godna Art</h1>
</div><section class="section" id="about">
    <h2>About Godna</h2>
    <p>
        Godna is a traditional tattoo art deeply rooted in Indian tribal culture.
        It represents identity, spirituality, and heritage passed through generations.
    </p>
</section><section class="section" id="gallery">
    <h2>Godna Designs</h2>
    <div class="gallery">
        <img src="https://images.unsplash.com/photo-1596461404969-9ae70f2830c1">
        <img src="https://images.unsplash.com/photo-1589987607627-3b4c3a7c4b4d">
        <img src="https://images.unsplash.com/photo-1600185365926-3a2ce3cdb9eb">
        <img src="https://images.unsplash.com/photo-1611078489935-0cb964de46d6">
    </div>
</section><section class="section" id="contact">
    <h2>Contact Us</h2>
    <form>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea rows="4" placeholder="Your Message"></textarea>
        <button type="submit">Send Message</button>
    </form>
</section><footer>
    <p>© 2026 Traditional Godna | Designed by You</p>
</footer></body>
</html>
