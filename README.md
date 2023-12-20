<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Apoio a Mulheres</title>
</head>
<body>
    <header>
        <h1>Apoio a Mulheres</h1>
    </header>

    <nav>
        <!-- Adicione links para diferentes seções do site -->
        <ul>
            <li><a href="#sobre">Sobre Nós</a></li>
            <li><a href="#recursos">Recursos</a></li>
            <li><a href="#contato">Contato</a></li>
        </ul>
    </nav>

    <section id="sobre">
        <h2>Sobre Nós</h2>
        <!-- Adicione informações sobre a organização e sua missão -->
        <p>...</p>
    </section>

    <section id="recursos">
        <h2>Recursos</h2>
        <!-- Liste recursos disponíveis para mulheres vítimas de violência -->
        <ul>
            <li>Linhas de Ajuda</li>
            <li>Abrigos Seguros</li>
            <li>Guias de Autodefesa</li>
            <!-- Adicione mais recursos conforme necessário -->
        </ul>
    </section>

    <section id="contato">
        <h2>Contato</h2>
        <!-- Formulário de contato para mulheres que precisam de ajuda -->
        <form id="contactForm">
            <!-- Campos do formulário (nome, email, mensagem, etc.) -->
            <label for="name">Nome:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Mensagem:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit">Enviar Mensagem</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2023 Apoio a Mulheres</p>
    </footer>

    <!-- Adicione scripts JavaScript conforme necessário -->
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
}

header, nav, section, footer {
    margin: 20px;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav li {
    display: inline;
    margin-right: 20px;
}

form {
    display: flex;
    flex-direction: column;
    max-width: 400px;
    margin: auto;
}

footer {
    text-align: center;
}
