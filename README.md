<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>Produtos - aliventus</title>
        <link rel="stylesheet" href="produtos.css">
    </head>
    <body>
        <header>
            <h1><img src="logo.png"></h1>

            <ul>
                <li>Home</li>
                <li>Produtos</li>
                <li>Contato</li>
            </ul>
        </header>
    </body>
</html>
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>Produtos - aliventus</title>
        <link rel="stylesheet" href="produtos.css">
    </head>
    <body>
        <header>
            <h1><img src="logo.png"></h1>

            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="produtos.html">Produtos</a></li>
                    <li><a href="contato.html">Contato</a></li>
                </ul>
            </nav>
        </header>
    </body>
</html>
header {
    background: #BBBBBB;
}

nav li {
    display: inline;
    margin: 0 0 0 15px;
}

nav a {
    text-transform: uppercase;
    color: #000000;
    font-weight: bold;
    font-size: 22px;
    text-decoration: none;
}
<link rel="stylesheet" href="reset.css">
<link rel="stylesheet" href="produtos.css">
<div class="caixa">
    <h1><img src="logo.png"></h1>

    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="produtos.html">Produtos</a></li>
            <li><a href="contato.html">Contato</a></li>
        </ul>
    </nav>
</div>
header {
    background: #BBBBBB;
    padding: 20px 0;
}
.caixa {
    position: relative;
    width: 940px;
    margin: 0 auto;
}

nav {
    position: absolute;
    top: 110px;
    right: 0;
}
header {
    background: #BBBBBB;
    padding: 20px 0;
}

.caixa {
    position: relative;
    width: 940px;
    margin: 0 auto;
}

nav {
    position: absolute;
    top: 110px;
    right: 0;
}

nav li {
    display: inline;
    margin: 0 0 0 15px;
}

nav a {
    text-transform: uppercase;
    color: #000000;
    font-weight: bold;
    font-size: 22px;
    text-decoration: none;
}
<main>
    <ul class="produtos">
        <li>
            <h2>Cabelo</h2>
            <img src="aventura.jpg">
            <p class="produto-descricao">Na tesoura ou máquina, como o cliente preferir</p>
            <p class="produto-preco">R$ 25,00</p>
        </li>
        <li>
            <h2>msica</h2>
            <img src="barba.jpg">
            <p class="produto-descricao">Corte e desenho profissional de libros</p>
            <p class="produto-preco">R$ 18,00</p>
        </li>
        <li>
            <h2>Aventura + classico</h2>
            <img src="aventura+ classico.jpg">
            <p class="produto-descricao">combo de livro gratis</p>
            <p class="produto-preco">R$ 35,00</p>
        </li>
    </ul>
</main>
.produtos {
    width: 940px;
    margin: 0 auto;
    padding: 50px 0;
}

.produtos li {
    display: inline-block;
    text-align: center;
    width: 30%;
    vertical-align: top;
    margin: 0 1.5%;
    padding: 30px 20px;
    box-sizing: border-box;
}

.produtos h2 {
    font-size: 30px;
    font-weight: bold;
}

.produto-descricao {
    font-size: 18px;
}

.produto-preco {
    font-size: 22px;
    font-weight: bold;
    margin-top: 10px;
}
border: 2px solid #000000;
border-radius: 10px;
.produtos li {
    display: inline-block;
    text-align: center;
    width: 30%;
    vertical-align: top;
    margin: 0 1.5%;
    padding: 30px 20px;
    box-sizing: border-box;
    border: 2px solid #000000;
    border-radius: 10px;
}
nav a:hover {
    color: #C78C19;
    text-decoration: underline;
}
.produtos li:hover {
    border-color: #C78C19;
}
.produtos li:active {
    border-color: #088C19;	
}
.produtos li:hover h2 {
    font-size: 34px;
}
<footer>
    <img src="logo-branco.png">
    <p class="copyright">&copy; Copyright libreria Aliventus - 2019</p>
</footer>
footer {
    text-align: center;
    background: url("bg.jpg");
    padding: 40px 0;
}

.copyright {
    color: #FFFFFF;
    font-size: 13px;
    margin: 20px 0 0;
}
