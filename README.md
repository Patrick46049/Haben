# Haben<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dein Online-Marktplatz</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .product {
            display: flex;
            margin-bottom: 20px;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 8px;
        }
        .product img {
            max-width: 150px;
            border-radius: 8px;
        }
        .product-details {
            margin-left: 20px;
        }
        .product-details h2 {
            margin: 0;
            font-size: 1.5rem;
            color: #333;
        }
        .product-details p {
            margin: 5px 0;
            color: #666;
        }
        .product-details .price {
            color: #28a745;
            font-weight: bold;
            font-size: 1.2rem;
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #333;
            color: white;
            margin-top: 20px;
        }
        .buy-button {
            margin-top: 10px;
            background-color: #007bff;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .buy-button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <header>
        <h1>Dein Online-Marktplatz</h1>
        <p>Kaufe und verkaufe Produkte einfach und schnell!</p>
    </header>
    <div class="container">
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Produktbild">
            <div class="product-details">
                <h2>Produktname 1</h2>
                <p>Kurze Beschreibung des Produkts.</p>
                <p class="price">€50,00</p>
                <button class="buy-button">Jetzt kaufen</button>
            </div>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Produktbild">
            <div class="product-details">
                <h2>Produktname 2</h2>
                <p>Kurze Beschreibung des Produkts.</p>
                <p class="price">€30,00</p>
                <button class="buy-button">Jetzt kaufen</button>
            </div>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Produktbild">
            <div class="product-details">
                <h2>Produktname 3</h2>
                <p>Kurze Beschreibung des Produkts.</p>
                <p class="price">€70,00</p>
                <button class="buy-button">Jetzt kaufen</button>
            </div>
        </div>
    </div>
    <footer>
        <p>© 2025 Dein Online-Marktplatz. Alle Rechte vorbehalten.</p>
        <p>Zahlungsmethoden: PayPal, Kreditkarte</p>
    </footer>
</body>
</html>
