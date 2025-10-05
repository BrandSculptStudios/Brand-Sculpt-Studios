# Brand-Sculpt-Studios
Welcome to BrandSculpt – Transforming ideas into stunning designs! We create custom digital templates and online products that help brands stand out on social media or in print. Our templates make creating professional, eye-catching designs fast and easy.
BrandSculpt-Website/
│
├── index.html
├── style.css
└── images/
    └── placeholder.png
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BrandSculpt</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header -->
    <header>
        <h1>BrandSculpt</h1>
        <p>Transforming Ideas into Stunning Designs</p>
    </header>

    <!-- About Section -->
    <section id="about">
        <h2>About Us</h2>
        <p>We design custom digital templates and online products that help brands stand out on social media or in print. Our templates make creating professional, eye-catching designs fast and easy.</p>
    </section>

    <!-- Products Section -->
    <section id="products">
        <h2>Our Products</h2>
        <div class="product-grid">
            <div class="product">
                <img src="images/placeholder.png" alt="Social Media Template">
                <h3>Social Media Templates</h3>
                <p>Ready-to-use posts, announcements, and promotional graphics for Instagram, Facebook, and TikTok.</p>
            </div>
            <div class="product">
                <img src="images/placeholder.png" alt="Printable Template">
                <h3>Printable Templates</h3>
                <p>Beautifully designed thank-you cards, invitations, and print-ready products.</p>
            </div>
            <div class="product">
                <img src="images/placeholder.png" alt="Custom Templates">
                <h3>Customizable Designs</h3>
                <p>Easily personalize colors, text, and layouts using Canva or other editing tools.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: <a href="mailto:yourname@brandsculpt.com">yourname@brandsculpt.com</a></p>
        <p>Instagram: <a href="https://instagram.com/BrandSculptDesigns" target="_blank">@BrandSculptDesigns</a></p>
    </section>

    <footer>
        <p>&copy; 2025 BrandSculpt. All rights reserved.</p>
        /* General Styles */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
    color: #333;
}

header {
    background-color: #1e90ff;
    color: white;
    padding: 40px 20px;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 3em;
}

header p {
    font-size: 1.2em;
}

/* Sections */
section {
    padding: 40px 20px;
    max-width: 1000px;
    margin: auto;
}

section h2 {
    font-size: 2em;
    margin-bottom: 20px;
}

/* Product Grid */
.product-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
}

.product {
    background-color: white;
    padding: 20px;
    width: 300px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    text-align: center;
    border-radius: 10px;
}

.product img {
    max-width: 100%;
    border-radius: 5px;
}

/* Footer */
footer {
    background-color: #1e90ff;
    color: white;
    text-align: center;
    padding: 20px;
    margin-top: 40px;
}

    </footer>
</body>
</html>
