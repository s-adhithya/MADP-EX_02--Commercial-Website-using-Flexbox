# Ex02 Commercial Website

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
### INDEX.HTML:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ghost's Shop - Dark Mode</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header -->
    <header class="header">
        <div class="logo">Ghost's Shop</div>
        <nav class="nav">
            <a href="#">Home</a>
            <a href="#">Products</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
        </nav>
    </header>

    <!-- Hero Banner -->
    <section class="hero">
        <div class="hero-text">
            <h1>Premium Style</h1>
            <p>Luxury you can afford. Shop the latest in fashion.</p>
            <a href="#" class="btn">Shop Now</a>
        </div>
    </section>

    <!-- Featured Products -->
    <section class="products">
        <h2>Featured Products</h2>
        <div class="product-grid">
            
            <!-- FIXED PRODUCT 1 IMAGE -->
            <div class="product-card">
                <img src="https://images.pexels.com/photos/428340/pexels-photo-428340.jpeg" alt="Product 1">
                <h3>Shirts From</h3>
                <p>₹999</p>                      
                <button>Shop</button>
            </div>

            <div class="product-card">
                <img src="https://images.pexels.com/photos/1598507/pexels-photo-1598507.jpeg" alt="Product 2">
                <h3>Pants From</h3>
                <p>₹799</p>
                <button>Shop</button>
            </div>

            <div class="product-card">
                <img src="https://www.nuffrespekt.com/media/towary/big/d8/d8be02e8b2141fd2.jpg" alt="Product 3">
                <h3>T-Shirts From</h3>
                <p>₹499</p>
                <button>Shop</button>
            </div>

            <div class="product-card">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSO13vPllqgZNChVad50RTYXUlKE9aQ1MDjqw&s" alt="Product 4">
                <h3>Shoes From</h3>
                <p>₹649</p>
                <button>Shop</button>
            </div>

        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <p>&copy; 2025 Ghost's Shop | All Rights Reserved</p>
    </footer>

</body>
</html>

### STYLE.CSS:
```
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #111; /* Dark background */
    color: #fff;
}

.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 30px;
    background-color: #222;
}

.logo {
    font-size: 1.5rem;
    font-weight: bold;
}

.nav a {
    color: #fff;
    text-decoration: none;
    margin-left: 20px;
}

.nav a:hover {
    color: #ff9800; /* Accent hover */
}

.hero {
    background: url('https://images.pexels.com/photos/1670770/pexels-photo-1670770.jpeg') center/cover no-repeat;
    padding: 100px 30px;
    text-align: center;
}

.hero-text h1 {
    font-size: 3rem;
    margin-bottom: 10px;
}

.hero-text p {
    font-size: 1.2rem;
    margin-bottom: 20px;
}

.btn {
    background-color: #ff9800;
    color: #fff;
    padding: 10px 20px;
    border-radius: 25px;
    text-decoration: none;
    font-weight: bold;
}

.btn:hover {
    background-color: #e68900;
}

.products {
    padding: 40px 20px;
    text-align: center;
}

.product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    margin-top: 20px;
}

.product-card {
    background: #222;
    border-radius: 10px;
    padding: 15px;
    text-align: center;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.product-card img {
    width: 100%;
    height: 250px; /* Fixed height */
    object-fit: cover; /* Uniform crop */
    border-radius: 8px;
    display: block;
}

.product-card h3 {
    margin: 15px 0 5px;
}

.product-card p {
    font-size: 1.1rem;
    margin-bottom: 10px;
    color: #ff9800; /* Price highlight */
}

.product-card button {
    background-color: #ff9800;
    color: #fff;
    padding: 8px 15px;
    border: none;
    border-radius: 20px;
    cursor: pointer;
    font-weight: bold;
}

.product-card button:hover {
    background-color: #e68900;
}

.footer {
    background-color: #222;
    text-align: center;
    padding: 15px;
    margin-top: 40px;
    font-size: 0.9rem;
}
```

## OUTPUT


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
