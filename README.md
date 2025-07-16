<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Metaleks Style Website</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            color: #333;
            background: #f5f5f5;
        }
        header {
            background: #111;
            color: white;
            padding: 20px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-weight: 500;
        }
        .hero {
            background: url('https://via.placeholder.com/1500x600') center/cover no-repeat;
            height: 600px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-shadow: 0 2px 4px rgba(0,0,0,0.7);
        }
        .hero h1 {
            font-size: 48px;
        }
        .content {
            max-width: 1200px;
            margin: 40px auto;
            padding: 0 20px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .card {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        footer {
            background: #111;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div><strong>METALEKS</strong></div>
        <nav>
            <a href="#">Home</a>
            <a href="#">Products</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
        </nav>
    </header>
    <section class="hero">
        <h1>Premium Metal Prints</h1>
    </section>
    <section class="content">
        <div class="card">
            <h2>Modern Design</h2>
            <p>Elegant metal prints perfect for your home or office wall decor.</p>
        </div>
        <div class="card">
            <h2>Custom Artwork</h2>
            <p>Upload your own artwork and get high-quality metal print results.</p>
        </div>
        <div class="card">
            <h2>Durable Quality</h2>
            <p>UV-protected and magnetic-friendly metal sheets for long-lasting beauty.</p>
        </div>
    </section>
    <footer>
        &copy; 2025 METALEKS. All rights reserved.
    </footer>
</body>
</html>
