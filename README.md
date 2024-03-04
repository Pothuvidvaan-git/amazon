# amazon
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon-like Product Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #232f3e;
            color: white;
            padding: 10px;
            text-align: center;
        }

        main {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .product {
            display: flex;
            margin-bottom: 20px;
            border-bottom: 1px solid #ddd;
            padding-bottom: 20px;
        }

        .product img {
            max-width: 100px;
            margin-right: 20px;
        }

        .product-details {
            flex-grow: 1;
        }

        h2 {
            margin-top: 0;
        }

        p {
            margin: 0;
        }

        .price {
            font-size: 1.2em;
            color: #b12704;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Amazon-like Product Page</h1>
    </header>
    <main>
        <div class="product">
            <img src="product1.jpg" alt="Product 1">
            <div class="product-details">
                <h2>Product 1</h2>
                <p>Description of Product 1.</p>
                <p class="price">$19.99</p>
            </div>
        </div>

        <div class="product">
            <img src="product2.jpg" alt="Product 2">
            <div class="product-details">
                <h2>Product 2</h2>
                <p>Description of Product 2.</p>
                <p class="price">$29.99</p>
            </div>
        </div>
        <!-- Add more product entries as needed -->
    </main>
</body>
</html>
