<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>quiz pedro </title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }

        header h1 {
            font-size: 2rem;
        }

        nav ul {
            list-style: none;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 1.1rem;
            cursor: pointer;
        }

        section {
            padding: 20px;
            text-align: center;
        }

        .products h2 {
            font-size: 2rem;
            margin-bottom: 20px;
        }

        .product-card {
            display: inline-block;
            width: 30%;
            margin: 10px;
            text-align: center;
            background-color: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 15px;
            border-radius: 8px;
            transition: transform 0.3s, box-shadow 0.3s;
            text-decoration: none;
            color: black;
        }

        .product-card:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
        }

        .product-card img {
            width: 100%;
            height: auto;
            border-radius: 4px;
        }

        .product-card p {
            font-size: 1.1rem;
            margin: 10px 0;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>musicas</h1>
    </header>

    <section class="products">
        <h2>minhas musicas favoridas</h2>

        <!-- Produto 1 -->
        <a href="https://www.youtube.com/watch?v=TJAfLE39ZZ8" target="_blank" class="product-card">
            <img src="https://th.bing.com/th/id/OIP.U1aPhKXNJVoOZERCJjsj4wHaLH?rs=1&pid=ImgDetMain" alt="Halteres de Ferro">
            <p>black to black</p>
            
        </a>

        <!-- Produto 2 -->
        <a href="https://www.youtube.com/watch?v=qU9mHegkTc4&list=RDqU9mHegkTc4&start_radio=1" target="_blank" class="product-card">
            <img src="https://th.bing.com/th/id/R.068cf8d8c93143863dd387f2cd19c7d8?rik=FHpDykGt53%2bzQg&pid=ImgRaw&r=0" alt="Equipamento de Ginástica">
            <p>505</p>
          
        </a>

        <!-- Produto 3 -->
        <a href="https://www.youtube.com/watch?v=HyHNuVaZJ-k" target="_blank" class="product-card">
            <img src="https://th.bing.com/th/id/OIP.qHd-YSMT7BzxxvLu3jis2wHaHa?rs=1&pid=ImgDetMain" alt="Roupas Esportivas">
            <p>feel good inc</p>
           
        </a>
    </section>

    <footer>
        <p>&copy; 2025 musicas do pedro  atulizado.</p>
    </footer>
</body>
</html>
