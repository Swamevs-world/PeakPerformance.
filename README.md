# PeakPerformance.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Swamev Suryawanshi - Gym Clothing and Fashion</title>
    <meta name="description" content="Swamev Suryawanshi’s gym clothing and fashion store. Discover stylish and high-quality gym wear for all your workout needs.">
    <meta name="keywords" content="gym clothing, fitness apparel, workout gear, athletic wear, gym fashion">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f4f8;
            color: #333;
        }
        header {
            background-color: #1a1a1a;
            color: #fff;
            padding: 30px 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            margin: 5px 0 0;
            font-size: 1.2em;
        }
        main {
            padding: 20px;
            max-width: 900px;
            margin: 0 auto;
        }
        section {
            margin-bottom: 50px;
        }
        h2 {
            border-bottom: 3px solid #ff6f61;
            padding-bottom: 10px;
            margin-bottom: 20px;
            font-size: 2em;
            color: #333;
        }
        .portfolio img, .product-grid img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            transition: transform 0.3s ease;
        }
        .portfolio img:hover, .product-grid img:hover {
            transform: scale(1.05);
        }
        .contact-info, .social-media {
            list-style: none;
            padding: 0;
        }
        .contact-info li, .social-media li {
            margin: 10px 0;
        }
        .contact-info a {
            color: #ff6f61;
            text-decoration: none;
        }
        .contact-info a:hover {
            text-decoration: underline;
        }
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
        }
        .product {
            background-color: #fff;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
            border-radius: 10px;
            text-align: center;
            transition: box-shadow 0.3s ease;
        }
        .product:hover {
            box-shadow: 0 6px 12px rgba(0,0,0,0.3);
        }
        .product h3 {
            margin: 10px 0;
            font-size: 1.5em;
        }
        .product p {
            margin: 5px 0;
            font-size: 1.1em;
            color: #666;
        }
        .paypal-button-container {
            margin-top: 15px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #1a1a1a;
            color: #fff;
            box-shadow: 0 -4px 8px rgba(0,0,0,0.2);
        }
        form {
            display: flex;
            flex-direction: column;
        }
        form label {
            margin: 5px 0;
        }
        form input, form textarea {
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        form button {
            background-color: #ff6f61;
            color: #fff;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        form button:hover {
            background-color: #e55b50;
        }
        @media (max-width: 768px) {
            .product-grid {
                grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            }
        }
        @media (max-width: 480px) {
            header h1 {
                font-size: 2em;
            }
            header p {
                font-size: 1em;
            }
        }
    </style>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap">
</head>
<body>
    <header>
        <h1>Swamev Suryawanshi</h1>
        <p>Gym Clothing and Fashion Enthusiast</p>
    </header>
    <main>
        <section>
            <h2>About Me</h2>
            <p>Welcome! I am Swamev Suryawanshi, a passionate enthusiast in the realm of gym clothing and fashion. My journey is driven by a dedication to blend comfort and style, ensuring that you look and feel your best during every workout session.</p>
        </section>
        <section>
            <h2>Portfolio</h2>
            <div class="portfolio">
                <img src="https://via.placeholder.com/600x400?text=Portfolio+Item+1" alt="Portfolio Item 1">
                <img src="https://via.placeholder.com/600x400?text=Portfolio+Item+2" alt="Portfolio Item 2">
                <img src="https://via.placeholder.com/600x400?text=Portfolio+Item+3" alt="Portfolio Item 3">
            </div>
        </section>
        <section>
            <h2>Products</h2>
            <div class="product-grid">
                <div class="product">
                    <img src="https://via.placeholder.com/400x300?text=Gym+Shoes" alt="Gym Shoes">
                    <h3>Gym Shoes</h3>
                    <p>Comfortable and stylish gym shoes for all your workouts.</p>
                    <div class="paypal-button-container" id="paypal-button-shoes"></div>
                </div>
                <div class="product">
                    <img src="https://via.placeholder.com/400x300?text=Gym+T-Shirt" alt="Gym T-Shirt">
                    <h3>Gym T-Shirt</h3>
                    <p>Breathable and sweat-wicking T-shirts to keep you cool.</p>
                    <div class="paypal-button-container" id="paypal-button-tshirt"></div>
                </div>
                <div class="product">
                    <img src="https://via.placeholder.com/400x300?text=Gym+Hoodie" alt="Gym Hoodie">
                    <h3>Gym Hoodie</h3>
                    <p>Stay warm and stylish with our premium gym hoodies.</p>
                    <div class="paypal-button-container" id="paypal-button-hoodie"></div>
                </div>
                <div class="product">
                    <img src="https://via.placeholder.com/400x300?text=Gym+Shoes+2" alt="Gym Shoes">
                    <h3>Gym Shoes</h3>
                    <p>Comfortable and stylish gym shoes for all your workouts.</p>
                    <div class="paypal-button-container" id="paypal-button-shoes-2"></div>
                </div>
                <div class="product">
                    <img src="https://via.placeholder.com/400x300?text=Gym+T-Shirt+2" alt="Gym T-Shirt">
                    <h3>Gym T-Shirt</h3>
                    <p>Breathable and sweat-wicking T-shirts to keep you cool.</p>
                    <div class="paypal-button-container" id="paypal-button-tshirt-2"></div>
                </div>
                <div class="product">
                    <img src="https://via.placeholder.com/400x300?text=Gym+Hoodie+2" alt="Gym Hoodie">
                    <h3>Gym Hoodie</h3>
                    <p>Stay warm and stylish with our premium gym hoodies.</p>
                    <div class="paypal-button-container" id="paypal-button-hoodie-2"></div>
                </div>
            </div>
        </section>
        <section>
            <h2>Contact Information</h2>
            <ul class="contact-info">
                <li>Email: <a href="mailto:swamev@example.com">swamev@example.com</a></li>
                <li>Phone: +123 456 7890</li>
            </ul>
        </section>
        <section>
            <h2>Follow Me</h2>
            <ul class="social-media">
                <li><a href="https://facebook.com/swamev" target="_blank">Facebook</a></li>
                <li><a href="https://instagram.com/swamev" target="_blank">Instagram</a></li>
                <li><a href="https://twitter.com/swamev" target="_blank">Twitter</a></li>
            </ul>
        </section>
        <section>
            <h2>Contact Me</h2>
            <form action="mailto:swamev@example.com" method="post" enctype="text/plain">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4" required></textarea>
                <button type="submit">Send</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Swamev Suryawanshi. All rights reserved.</p>
    </footer>
    <!-- PayPal Buttons Integration -->
    <script src="https://www.paypal.com/sdk/js?client-id=YOUR_PAYPAL_CLIENT_ID"></script>
    <script>
        paypal.Buttons({
            createOrder: function(data, actions) {
                return actions.order.create({
                    purchase_units: [{
                        description: 'Gym Shoes',
                        amount: {
                            value: '55.00'  // Updated price
                        }
                    }]
                });
            },
            onApprove: function(data, actions) {
                return actions.order.capture().then(function(details) {
                    alert('Transaction completed by ' + details.payer.name.given_name);
                });
            },
            onError: function(err) {
                console.error(err);
            }
        }).render('#paypal-button-shoes');

        paypal.Buttons({
            createOrder: function(data, actions) {
                return actions.order.create({
                    purchase_units: [{
                        description: 'Gym T-Shirt',
                        amount: {
                            value: '25.00'  // Updated price
                        }
                    }]
                });
            },
            onApprove: function(data, actions) {
                return actions.order.capture().then(function(details) {
                    alert('Transaction completed by ' + details.payer.name.given_name);
                });
            },
            onError: function(err) {
                console.error(err);
            }
        }).render('#paypal-button-tshirt');

        paypal.Buttons({
            createOrder: function(data, actions) {
                return actions.order.create({
                    purchase_units: [{
                        description: 'Gym Hoodie',
                        amount: {
                            value: '45.00'  // Updated price
                        }
                    }]
                });
            },
            onApprove: function(data, actions) {
                return actions.order.capture().then(function(details) {
                    alert('Transaction completed by ' + details.payer.name.given_name);
                });
            },
            onError: function(err) {
                console.error(err);
            }
        }).render('#paypal-button-hoodie');

        paypal.Buttons({
            createOrder: function(data, actions) {
                return actions.order.create({
                    purchase_units: [{
                        description: 'Gym Shoes',
                        amount: {
                            value: '55.00'  // Updated price
                        }
                    }]
                });
            },
            onApprove: function(data, actions) {
                return actions.order.capture().then(function(details) {
                    alert('Transaction completed by ' + details.payer.name.given_name);
                });
            },
            onError: function(err) {
                console.error(err);
            }
        }).render('#paypal-button-shoes-2');

        paypal.Buttons({
            createOrder: function(data, actions) {
                return actions.order.create({
                    purchase_units: [{
                        description: 'Gym T-Shirt',
                        amount: {
                            value: '25.00'  // Updated price
                        }
                    }]
                });
            },
            onApprove: function(data, actions) {
                return actions.order.capture().then(function(details) {
                    alert('Transaction completed by ' + details.payer.name.given_name);
                });
            },
            onError: function(err) {
                console.error(err);
            }
        }).render('#paypal-button-tshirt-2');

        paypal.Buttons({
            createOrder: function(data, actions) {
                return actions.order.create({
                    purchase_units: [{
                        description: 'Gym Hoodie',
                        amount: {
                            value: '45.00'  // Updated price
                        }
                    }]
                });
            },
            onApprove: function(data, actions) {
                return actions.order.capture().then(function(details) {
                    alert('Transaction completed by ' + details.payer.name.given_name);
                });
            },
            onError: function(err) {
                console.error(err);
            }
        }).render('#paypal-button-hoodie-2');

        // Smooth Scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Google Analytics
        window.dataLayer = window.dataLayer || [];
        function gtag(){dataLayer.push(arguments);}
        gtag('js', new Date());
        gtag('config', 'YOUR_GOOGLE_ANALYTICS_ID');
    </script>
</body>
</html>

