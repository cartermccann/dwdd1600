# about.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="Carter McCann">
    <meta name="description" content="About Pump Protein">
    <title>Pump Protein - About</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <header class="header">
            <h1>About <span>Pump Protein</span></h1>
            <p>Your trusted brand for peak performance drinks.</p>
        </header>

        <nav class="nav">
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
            </ul>
        </nav>

        <main class="main">
            <div class="about-container">
                <div class="about-header">
                    <h1>About <span>Pump Protein</span></h1>
                    <p>Your trusted brand for peak performance drinks.</p>
                </div>
            
                <div class="about-mission">
                    <h2>Our Mission</h2>
                    <p>At Pump Protein, we aim to combine <strong>premium protein</strong> with cutting-edge science for unparalleled results.</p>
                </div>
            
                <div class="about-features">
                    <h2>Why Choose Us?</h2>
                    <p>Pump Protein is scientifically formulated to give you:</p>
                    <ul>
                        <li>Unmatched energy and focus</li>
                        <li>Muscle recovery support</li>
                        <li>Premium ingredients with proven results</li>
                    </ul>
                </div>
            
                <div class="about-values">
                    <h2>Our Promise</h2>
                    <p>We use only the finest ingredients to ensure our products deliver on their promise to fuel your body and mind.</p>
                    <ol>
                        <li>Quality you can trust</li>
                        <li>Transparency in every formula</li>
                        <li>Designed for peak performance</li>
                    </ol>
                </div>
            
                <div class="about-contact">
                    <h2>Contact Us</h2>
                    <address>
                        <strong>Email:</strong> support@pumpprotein.com<br>
                        <strong>Phone:</strong> <a href="tel:253-514-2771">253-514-2771</a>
                    </address>
                </div>
            </div>
            
        </main>

        <footer class="footer">
            <p>&copy; 2025 Pump Protein &#8226; Call us at <a href="tel:253-514-2771">253-514-2771</a></p>
        
        </footer>
    </div>
</body>
</html>

```

# index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="Carter McCann">
    <meta name="description" content="Learn more about Pump Protein, the ultimate energy drink for body and mind.">
    <title>Pump Protein - Home</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    
        <header class="header">
            <h1>Welcome to <span>Pump Protein</span></h1>
            <p> <strong>fueling the body</strong> and <em> the mind</em>.</p>
        </header>
        <nav class="nav">
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
            </ul>
        </nav>

        <main class="main">
            <div class="hero">
                <div class="hero-text">
                    <h1>Fuel Your Performance</h1>
                    <h3>With 30g of protein and premium nootropics.</h3>
                </div>
                <img src="hero.jpg" alt="Pump Protein Drink">
            </div>

            <section class="features">
                <h2>Our Ingredients</h2>
                <dl>
                    <dt>30g of Protein</dt>
                    <dd>Muscle-fueling power to support your fitness goals.</dd>
                    <dt>300mg Alpha-GPC</dt>
                    <dd>Enhances cognitive function for focus and clarity.</dd>
                    <dt>1500mg L-Carnitine</dt>
                    <dd>Boosts energy production and fat metabolism.</dd>
                </dl>
            </section>

            <h2>Get Started</h2>
            <p>Click <a href="about.html">here</a> to learn more about us!</p>
    
            <div class="quick-links">
                <h2>Quick Links</h2>
                <p>Need gym equipment? Check out these resources:</p>
                <ul>
                    <li><a href="https://www.roguefitness.com" target="_blank">Rogue Fitness</a></li>
                    <li><a href="https://www.myprotein.com" target="_blank">MyProtein</a></li>
                </ul>
            </div>            
        </main>

        <footer class="footer">
            <p>&copy; 2025 Pump Protein &bull; Call us at <a href="tel:253-514-2771">253-514-2771</a></p>
        
        </footer>
   
</body>
</html>

```

# style.css

```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
    font-family: 'Inter', sans-serif;
    background-color: #121212;
    color: #f4f4f4;
    font-size: 16px;
}

body {
    line-height: 1.6;
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

.container {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    min-height: 100vh;
}

.header {
    background: linear-gradient(90deg, #007bff, #0056b3);
    padding: 1.5rem 2rem;
    text-align: center;
}

.header h1 {
    font-size: 2.5rem;
    font-weight: 700;
    letter-spacing: 0.1rem;
    color: #fff;
}

.nav {
    background-color: #1e1e1e;
    padding: 1rem;
    display: flex;
    justify-content: center;
}

.nav ul {
    list-style: none;
    display: flex;
    gap: 2rem;
}

.nav ul li a {
    color: #f4f4f4;
    text-decoration: none;
    font-size: 1rem;
    font-weight: 500;
    position: relative;
    padding: 0.5rem 0;
    transition: color 0.3s ease-in-out;
}

.nav ul li a::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    height: 2px;
    width: 0;
    background: #007bff;
    transition: width 0.3s ease-in-out;
}

.nav ul li a:hover {
    color: #007bff;
}

.nav ul li a:hover::after {
    width: 100%;
}

.main {
    padding: 2rem;
    text-align: center;
}

.hero {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 4rem 2rem;
    background: linear-gradient(135deg, #232526, #414345);
    border-radius: 1rem;
    box-shadow: 0px 4px 20px rgba(0, 0, 0, 0.6);
    color: #fff;
    animation: fadeIn 1s ease-in-out;
    gap: 2rem; 
}

.hero h1 {
    font-size: 3rem;
    font-weight: 700;
    letter-spacing: 0.1rem;
    margin-bottom: 1rem;
}

.hero h3 {
    font-size: 1.5rem;
    margin-bottom: 2rem;
    color: #007bff;
}

.hero img {
    border-radius: 0.5rem;
    max-width: 50%; 
    height: auto;
}

.footer {
    background: #1e1e1e;
    padding: 2rem;
    text-align: center;
    font-size: 0.9rem;
    color: #a1a1a1;
}

.footer h1 {
    font-weight: 400;
    color: #f4f4f4;
}

.features {
    padding: 2rem;
    background: linear-gradient(135deg, #1e1e1e, #2b2b2b);
    color: #f4f4f4;
    border-radius: 1rem;
    max-width: 800px;
    margin: 2rem auto;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
}

.features h2 {
    text-align: center;
    font-size: 2rem;
    margin-bottom: 1.5rem;
    color: #007bff;
}

dl {
    display: grid;
    grid-template-columns: 1fr;
    gap: 1rem;
}

dt {
    font-weight: 700;
    font-size: 1.2rem;
    color: #007bff;
}

dd {
    margin-left: 1rem;
    font-size: 1rem;
    line-height: 1.5;
    color: #d4d4d4;
}

@keyframes fadeIn {
    from {
        opacity: 0;
        transform: translateY(20px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}
a[href^="tel:"] {
    color: #007bff; 
    text-decoration: none;
    font-weight: 600; 
    transition: color 0.3s ease-in-out;
    border-bottom: 1px dashed transparent; 
}

a[href^="tel:"]:hover {
    color: #0056b3; 
    border-bottom: 1px dashed #0056b3; 
    cursor: pointer;
}


.about-container {
    padding: 2rem;
    background: linear-gradient(135deg, #1e1e1e, #2b2b2b);
    color: #f4f4f4;
    border-radius: 1rem;
    max-width: 800px;
    margin: 2rem auto;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
}

.about-header {
    text-align: center;
    margin-bottom: 2rem;
}

.about-header h1 {
    font-size: 2.5rem;
    font-weight: 700;
    color: #007bff;
}

.about-header span {
    color: #0056b3;
}

.about-header p {
    font-size: 1.2rem;
    margin-top: 0.5rem;
    color: #d4d4d4;
}

.about-mission, .about-features, .about-values, .about-contact {
    margin-bottom: 2rem;
}

.about-mission h2, .about-features h2, .about-values h2, .about-contact h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
    color: #007bff;
}

.about-mission p, .about-features p, .about-values p {
    font-size: 1.2rem;
    line-height: 1.6;
    color: #d4d4d4;
}

.about-features ul, .about-values ol {
    margin: 1rem 0;
    padding-left: 2rem; 
    list-style-position: outside;
}

.about-features li, .about-values li {
    margin-bottom: 0.5rem; 
    color: #d4d4d4;
}

.about-values ol {
    list-style-type: decimal; 
}


.about-contact address {
    font-style: normal;
    line-height: 1.6;
    font-size: 1.2rem;
    color: #d4d4d4;
}

.about-contact a {
    color: #007bff;
    text-decoration: none;
    font-weight: 600;
}

.about-contact a:hover {
    color: #0056b3;
    text-decoration: underline;
}
.quick-links {
    padding: 1.5rem;
    margin: 2rem auto;
    max-width: 600px;
    background: linear-gradient(135deg, #1e1e1e, #2b2b2b);
    border-radius: 1rem;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
    text-align: center;
    color: #f4f4f4;
}

.quick-links h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
    color: #007bff;
}

.quick-links p {
    font-size: 1.2rem;
    margin-bottom: 1rem;
    color: #d4d4d4;
}

.quick-links ul {
    list-style-type: disc;
    list-style-position: inside;
    padding: 0;
    margin: 0;
}

.quick-links ul li {
    margin-bottom: 0.5rem;
    font-size: 1.1rem;
}

.quick-links ul li a {
    color: #007bff;
    text-decoration: none;
    transition: color 0.3s ease-in-out;
}

.quick-links ul li a:hover {
    color: #0056b3;
    text-decoration: underline;
}

```

