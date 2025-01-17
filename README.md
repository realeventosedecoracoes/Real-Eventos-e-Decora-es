<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio Profissional</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background-color: black;
            color: white;
        }
        header {
            background-color: black;
            padding: 20px;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }
        header nav ul {
            display: flex;
            list-style: none;
            justify-content: center;
            padding: 0;
        }
        header nav ul li {
            margin: 0 15px;
        }
        header nav ul li a {
            text-decoration: none;
            color: white;
            font-weight: bold;
            font-size: 18px;
            padding: 10px;
            transition: color 0.3s ease;
        }
        header nav ul li a:hover {
            color: gold;
        }
        section {
            padding: 60px 20px;
            margin-top: 80px;
        }
        .hero {
            height: 80vh;
            background: url('event-banner.jpg') no-repeat center center/cover;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: gold;
            background-blend-mode: multiply;
        }
        .hero h1 {
            font-family: serif;
            font-size: 50px;
            margin: 0;
        }
        .services, .portfolio, .products, .testimonials, .about, .contact {
            background-color: #111;
            padding: 40px 0;
        }
        .services h2, .portfolio h2, .products h2, .testimonials h2, .about h2, .contact h2 {
            color: gold;
            text-align: center;
            font-size: 36px;
            margin-bottom: 20px;
        }
        .gallery img, .products img {
            width: 100%;
            height: auto;
            border: 2px solid gold;
        }
        .gallery, .products {
            display: flex;
            gap: 20px;
            justify-content: center;
        }
        .services ul {
            list-style: none;
            text-align: center;
        }
        .services ul li {
            padding: 10px;
            font-size: 20px;
        }
        .services ul li:before {
            content: "• ";
            color: gold;
        }
        .contact form {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .contact input, .contact textarea {
            width: 80%;
            padding: 10px;
            margin: 10px 0;
            border: 2px solid gold;
            background-color: black;
            color: white;
        }
        .contact button {
            background-color: gold;
            color: black;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
        .contact button:hover {
            background-color: white;
            color: gold;
            border: 2px solid gold;
        }
    </style>
</head>
<body>

    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#portfolio">Portfólio</a></li>
                <li><a href="#services">Serviços</a></li>
                <li><a href="#products">Produtos</a></li>
                <li><a href="#testimonials">Depoimentos</a></li>
                <li><a href="#about">Sobre</a></li>
                <li><a href="#contact">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero" id="home">
        <h1>Transformando Sonhos em Realidade!</h1>
        <button>Saiba Mais</button>
    </section>

    <section class="services" id="services">
        <h2>Serviços Oferecidos</h2>
        <ul>
            <li>Decoração para Casamentos</li>
            <li>Decoração para Aniversários</li>
            <li>Decoração Corporativa</li>
            <li>Decoração para Formaturas</li>
        </ul>
    </section>

    <section class="portfolio" id="portfolio">
        <h2>Portfólio de Eventos</h2>
        <div class="gallery">
            <img src="casamento.jpg" alt="Casamento">
            <img src="aniversario.jpg" alt="Aniversário">
            <img src="corporativo.jpg" alt="Corporativo">
        </div>
    </section>

    <section class="products" id="products">
        <h2>Produtos</h2>
        <div class="products">
            <img src="produto1.jpg" alt="Arranjo Floral">
            <img src="produto2.jpg" alt="Decoração de Mesa">
            <img src="produto3.jpg" alt="Peças Personalizadas">
        </div>
    </section>

    <section class="testimonials" id="testimonials">
        <h2>Depoimentos</h2>
        <p>"O evento foi perfeito, superou todas as nossas expectativas!" - Cliente Satisfeito</p>
        <p>"Transformaram o nosso sonho em realidade com cada detalhe incrível." - Cliente Feliz</p>
    </section>

    <section class="about" id="about">
        <h2>Sobre Nós</h2>
        <p>Somos uma empresa dedicada à criação de momentos inesquecíveis, especializada em transformar ambientes com sofisticação e elegância para todos os tipos de eventos.</p>
    </section>

    <section class="contact" id="contact">
        <h2>Entre em Contato</h2>
        <form action="#">
            <input type="text" placeholder="Seu Nome">
            <input type="email" placeholder="Seu Email">
            <textarea placeholder="Sua Mensagem"></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

</body>
</html>
