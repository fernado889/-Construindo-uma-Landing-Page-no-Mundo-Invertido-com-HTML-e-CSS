# -Construindo-uma-Landing-Page-no-Mundo-Invertido-com-HTML-e-CSS
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mundo Invertido - Landing Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>Bem-vindo ao Mundo Invertido</h1>
            <p>Explore o desconhecido e descubra os mistérios que nos cercam.</p>
            <a href="#cta" class="btn">Saiba Mais</a>
        </header>
        <section class="content">
            <h2>O que é o Mundo Invertido?</h2>
            <p>Uma dimensão alternativa onde tudo é um pouco diferente. Explore as possibilidades e enfrente seus medos!</p>
        </section>
        <section id="cta" class="cta">
            <h2>Pronto para a aventura?</h2>
            <a href="#" class="btn">Comece Agora</a>
        </section>
        <footer>
            <p>&copy; 2024 Mundo Invertido. Todos os direitos reservados.</p>
        </footer>
    </div>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: #1a1a1a;
    color: #ffffff;
}

.container {
    max-width: 1200px;
    margin: auto;
    padding: 20px;
}

header {
    text-align: center;
    margin-bottom: 50px;
}

header h1 {
    font-size: 3rem;
    text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
}

header p {
    font-size: 1.2rem;
    margin: 20px 0;
}

.btn {
    display: inline-block;
    background-color: #ff4c4c;
    color: #ffffff;
    padding: 10px 20px;
    border-radius: 5px;
    text-decoration: none;
    transition: background-color 0.3s;
}

.btn:hover {
    background-color: #e63939;
}

.content, .cta {
    margin: 40px 0;
    padding: 20px;
    background-color: #2e2e2e;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
}

footer {
    text-align: center;
    margin-top: 50px;
    font-size: 0.8rem;
}
