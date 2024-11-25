<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Associação Natur Arte</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background: #3c6e71;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #284b63;
            padding: 0.5rem;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 2rem auto;
        }
        .about, .products, .contact, .history, .donate {
            margin-bottom: 2rem;
        }
        footer {
            text-align: center;
            padding: 1rem 0;
            background: #3c6e71;
            color: #fff;
        }
        .card {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }
        .card-item {
            flex: 1 1 calc(33.333% - 1rem);
            background: #fff;
            border: 1px solid #ccc;
            border-radius: 5px;
            padding: 1rem;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .card-item img {
            max-width: 100%;
            border-radius: 5px;
        }
        .social {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin-top: 1rem;
        }
        .social a {
            color: #3c6e71;
            text-decoration: none;
            font-size: 1.5rem;
        }
        .map {
            text-align: center;
        }
        .map iframe {
            width: 100%;
            height: 300px;
            border: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Associação Natur Arte</h1>
        <p>Transformando a natureza em arte com biojoias e artesanato amazônico</p>
    </header>
    <nav>
        <a href="#about">Sobre</a>
        <a href="#products">Produtos</a>
        <a href="#history">História</a>
        <a href="#donate">Doações</a>
        <a href="#contact">Contato</a>
    </nav>
    <main class="container">
        <section id="about" class="about">
            <h2>Sobre Nós</h2>
            <p>A Associação Natur Arte reúne artesãs de Barcarena comprometidas com a produção de biojoias e artesanato sustentável. Utilizando sementes e argilas da Amazônia, promovemos o empreendedorismo feminino e a valorização da cultura local.</p>
        </section>
        <section id="products" class="products">
            <h2>Nossos Produtos</h2>
            <div class="card">
                <div class="card-item">
                    <img src="produto1.jpg" alt="Colar de sementes">
                    <h3>Colar de Sementes</h3>
                    <p>Feito com sementes naturais da Amazônia, este colar é único e sustentável.</p>
                </div>
                <div class="card-item">
                    <img src="produto2.jpg" alt="Pulseira artesanal">
                    <h3>Pulseira Artesanal</h3>
                    <p>Pulseira delicada feita à mão com materiais orgânicos.</p>
                </div>
                <div class="card-item">
                    <img src="produto3.jpg" alt="Escultura em argila">
                    <h3>Escultura em Argila</h3>
                    <p>Peça artística criada com argila da Amazônia.</p>
                </div>
            </div>
        </section>
        <section id="history" class="history">
            <h2>Nossa História</h2>
            <p>Fundada em Barcarena, a Associação Natur Arte nasceu do sonho de valorizar a riqueza natural da Amazônia e promover a autonomia feminina. Desde 2016, temos impactado positivamente a vida de diversas famílias através do artesanato sustentável.</p>
        </section>
        <section id="donate" class="donate">
            <h2>Como Apoiar</h2>
            <p>Sua contribuição faz toda a diferença! Apoie nossos projetos e ajude a fortalecer o trabalho das artesãs de Barcarena.</p>
            <ul>
                <li>Pix: contato@naturarte.com</li>
                <li>Conta Bancária: Banco X, Agência 1234, Conta 56789-0</li>
            </ul>
        </section>
        <section id="contact" class="contact">
            <h2>Contato</h2>
            <p>Entre em contato conosco para saber mais sobre nossos produtos ou parcerias.</p>
            <ul>
                <li>Email: contato@naturarte.com</li>
                <li>Telefone: (91) 98499-5094</li>
                <li>Endereço: Rodovia Moura Carvalho, s/n, bairro Cafezal, Barcarena, Pará</li>
            </ul>
            <div class="social">
                <a href="https://facebook.com" target="_blank">Facebook</a>
                <a href="https://instagram.com" target="_blank">Instagram</a>
                <a href="https://twitter.com" target="_blank">Twitter</a>
            </div>
        </section>
        <section class="map">
            <h2>Localização</h2>
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3153.835434509104!2d-122.41941568468135!3d37.77492927975871!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMzfCsDQ2JzI5LjciTiAxMjLCsDI1JzA4LjQiVw!5e0!3m2!1sen!2sbr!4v1692839384941!5m2!1sen!2sbr" allowfullscreen=""></iframe>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Associação Natur Arte. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
