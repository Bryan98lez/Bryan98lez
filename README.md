<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Distribuidora ISSA </title>
    <style>
        /* Estilos globales */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f9f9f9;
        }
        header {
            background-color: #FF6F61;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #FFC107;
            padding: 1rem;
        }
        nav a {
            color: #333;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        .banner {
            background: url('https://example.com/banner-Productos.jpg') no-repeat center;
            background-size: cover;
            height: 300px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            font-size: 2rem;
            font-weight: bold;
            text-align: center;
        }
        .section {
            padding: 2rem;
            text-align: center;
        }
        .section h2 {
            color: #FF6F61;
        }
        .products, .contact {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .product, .contact-form {
            background-color: #fff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 1rem;
            padding: 1rem;
            border-radius: 8px;
            width: 250px;
            text-align: center;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }
        button {
            background-color: #FF6F61;
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            border-radius: 4px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #e05a50;
        }
    </style>
</head>
<body>
    <header>
        <h1>Distribuidora ISSA </h1>
        <p>¡</p>
    </header>
    <nav>
        <a href="#productos">Productos</a>
        <a href="#nosotros">Nosotros</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <section class="banner">
        <p>¡</p>
    </section>
    <section id="productos" class="section">
        <h2>Nuestros Productos</h2>
        <div class="products">
            <div class="product">
                <h3>Golosinas</h3>
                <p>Variedad de caramelos, chocolates y más.</p>
            </div>
            <div class="product">
                <h3>Dulces</h3>
                <p>Chocolates, bombones y dulces .</p>
            </div>
            <div class="product">
                <h3></h3>
                <p>.</p>
            </div>
        </div>
    </section>
    <section id="nosotros" class="section">
        <h2>Sobre Nosotros</h2>
        <p>Somos una distribuidora comprometida en ofrecer productos de calidad, con un excelente servicio para que siempre tengas una dulce experiencia.</p>
    </section>
    <section id="contacto" class="section">
        <h2>Contacto</h2>
        <div class="contact">
            <form class="contact-form">
                <h3>Contáctanos</h3>
                <label for="name">Nombre</label><br>
                <input type="text" id="name" name="name" required><br><br>
                <label for="email">Email</label><br>
                <input type="email" id="email" name="email" required><br><br>
                <label for="message">Mensaje</label><br>
                <textarea id="message" name="message" required></textarea><br><br>
                <button type="submit">Enviar</button>
            </form>
        </div>
    </section>
    <footer>
        <p>&copy; 2023 Distribuidora de Golosinas. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
