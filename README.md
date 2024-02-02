your-repo/
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
├── index.html
└── README.md
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/style.css">
    <title>Online Store</title>
</head>
<body>
    <h1>Welcome to Our Online Store</h1>
    <div id="products-container">
        <!-- Product listings go here -->
    </div>
    <script src="js/script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 20px;
}

#products-container {
    display: flex;
    flex-wrap: wrap;
}

.product {
    border: 1px solid #ddd;
    padding: 10px;
    margin: 10px;
}
