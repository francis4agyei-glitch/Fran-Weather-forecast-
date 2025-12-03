<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Francis Automobile</title>
    
    <style>
        body {
            font-family: sans-serif;
            margin: 0;
            padding: 0;
            background-color: #FFFFFF;
            color: #000080;
            
            /* 🚗 BACKGROUND IMAGE CODE: Using the full image URL */
            background-image: url('http://googleusercontent.com/generated_image_content/0'); 
            background-size: cover; 
            background-attachment: fixed; 
            background-repeat: no-repeat;
            background-position: center center; 
        }

        /* Added opacity to the main content area for readability over the background image */
        main {
            background-color: rgba(255, 255, 255, 0.9); /* White with 90% opacity */
            padding: 0 50px;
            max-width: 1200px;
            margin: 0 auto;
            box-shadow: 0 0 20px rgba(0,0,0,0.2);
        }

        header {
            background-color: #FFFFFF;
            padding: 15px 50px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .logo {
            font-size: 1.5em;
            font-weight: bold;
            color: #000080;
        }

        nav a {
            color: #333;
            text-decoration: none;
            margin-left: 20px;
            font-weight: 500;
        }

        /* Hero Section (Sale Banner) */
        .hero {
            background-color: #87CEEB;
            text-align: center;
            padding: 100px 20px;
            margin-bottom: 20px;
        }

        .hero h1 {
            font-size: 2.5em;
            color: #000080;
            margin-bottom: 10px;
        }

        .btn {
            display: inline-block;
            background-color: #0000FF;
            color: white;
            padding: 10px 30px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 20px;
            font-weight: bold;
            transition: background-color 0.3s;
        }

        .btn:hover {
            background-color: #000080;
        }

        /* Sections Styling */
        .products h2, .welcome h2, .why-us h2 {
            text-align: center;
            color: #0000FF;
            margin-top: 30px;
        }

        /* Product Grid */
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); 
            gap: 30px;
            margin-top: 20px;
            padding-bottom: 30px;
        }

        .product-card {
            background-color: white;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            text-align: center;
        }
        
        /* CSS for Product Images */
        .product-card img {
            width: 100%; 
            height: 200px; 
            object-fit: cover; 
            border-radius: 4px;
            margin-bottom: 10px;
        }

        .product-card .price {
            color: #000000;
            font-weight: bold;
            margin: 5px 0 10px;
        }

        .product-card button {
            background-color: #000080;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .product-card button:hover {
            background-color: #87CEEB;
        }

        /* Why Us Section */
        .why-us ul {
            list-style-type: '🚗 ';
            padding-left: 0;
            max-width: 600px;
            margin: 20px auto 50px;
        }

        .why-us li {
            padding: 8px 0;
            text-align: center;
        }

        /* Footer */
        footer {
            background-color: #FFFAFA;
            color: #000080;
            text-align: center;
            padding: 20px 0;
            margin-top: 0;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Francis Automobile</div>
        <nav>
            <a href="#">Home</a>
            <a href="#">Products</a>
            <a href="#">Contact</a>
        </nav>
    </header>

    <section class="hero">
        <h1>Holiday Sale! 10% off all items</h1>
        <p>Hurry up — limited time offer!</p>
        <a href="#" class="btn">Shop Now</a>
    </section>

    <main>
        <section class="welcome">
            <h2>Welcome to Francis Automobile</h2>
            <p>Your one-stop shop for exclusive automobiles and parts.</p>
        </section>

        <section class="products">
            <h2>Featured Products</h2>
            <div class="product-grid">
                
                <div class="product-card">
                    <img src="http://googleusercontent.com/image_generation_content/1" alt="Mercedez Benz"> 
                    <h3>Mercedez Benz</h3>
                    <p class="price">$50000</p>
                    <button>Add to Cart</button>
                </div>
                
                <div class="product-card">
                    <img src="http://googleusercontent.com/image_generation_content/2" alt="B.M.W.">
                    <h3>B.M.W.</h3>
                    <p class="price">$2200.00</p>
                    <button>Add to Cart</button>
                </div>

                <div class="product-card">
                    <img src="http://googleusercontent.com/image_generation_content/3" alt="RANGE ROVER">
                    <h3>RANGE ROVER</h3>
                    <p class="price">$150000.00</p>
                    <button>Add to Cart</button>
                </div>

            </div>
        </section>

        <section class="why-us">
            <h2>Why Choose Francis Automobile?</h2>
            <ul>
                <li>Top Quality Automobile</li>
                <li>Affordable Prices</li>
                <li>Fast and Reliable Shipping</li>
                <li>Secure Shipping Experience</li>
            </ul>
        </section>
    </main>

    <footer>
        &copy; 2025 Francis Automobile - All Rights Reserved
    </footer>
</body>
</html>
