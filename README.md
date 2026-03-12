<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ChartCart Store</title>

    <style>
        /* Pura page setup */
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #f8f9fa;
            text-align: center;
        }

        /* Navigation Bar (Buttons ka container) */
        .header {
            background: #222;
            padding: 15px 5px;
            display: flex;          /* Buttons ko ek line mein laane ke liye */
            justify-content: center; /* Buttons ko beech mein rakhne ke liye */
            flex-wrap: wrap;        /* Mobile par buttons ko automatic niche lane ke liye */
            gap: 12px;              /* Buttons ke beech barabar jagah */
            box-shadow: 0 2px 10px rgba(0,0,0,0.2);
        }

        /* Sabhi Buttons ki common design */
        .header a {
            color: white;
            text-decoration: none;
            padding: 12px 20px;
            background: #25D366;
            border-radius: 6px;
            font-size: 14px;
            font-weight: 600;
            transition: all 0.3s ease;
            display: inline-block;
            min-width: 90px;        /* Sabhi buttons ka size barabar dikhega */
            border: none;
        }

        /* Jab mouse button par le jayein */
        .header a:hover {
            background: #1ebd5a;
            transform: translateY(-2px); /* Halki si unchai */
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }

        /* WhatsApp button ko thoda alag color diya hai */
        .whatsapp-btn {
            background: #075E54 !important;
        }

        /* Heading aur Text */
        .content {
            padding: 40px 20px;
        }

        h1 {
            color: #222;
            margin-bottom: 10px;
            font-size: 2.2rem;
        }

        p {
            color: #666;
            font-size: 1.1rem;
        }
    </style>
</head>
<body>

    <nav class="header">
        <a href="index.html">Home</a>
        <a href="products.html">Products</a>
        <a href="cart.html">Cart</a>
        <a href="contact.html">Contact</a>
        <a href="https://wa.me/919931203143" class="whatsapp-btn" target="_blank">Order on WhatsApp</a>
    </nav>

    <div class="content">
        <h1>Welcome to ChartCart Store</h1>
        <p>Your Professional WhatsApp Ecommerce Store</p>
    </div>

</body>
</html>
