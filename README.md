<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sobre Mim</title>
    <style>
        /* Reset básico */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Estilo do corpo */
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            color: #333;
        }

        /* Estilo do cabeçalho e navegação */
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
        }

        nav ul {
            list-style-type: none;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            padding: 5px 10px;
        }

        nav ul li a:hover {
            background-color: #555;
            color: white;
        }

        /* Estilo das seções */
        main {
            padding: 20px;
        }

        section {
            margin-bottom: 20px;
        }
    </style>
</head>
<body>

    <main>
        <section id="sobre-mim">
            <h1>Sobre Mim</h1>
            <p>Olá! Meu nome é Ayumi Chino, mas prefiro que me chamem apenas de Ayumi. Meus hobbies envolve bastante o "mundo geek", como por exemplo, gosto de jogar jogos online, ler, ver animes, filmes e séries. No meu tempo livre, pratico Muay Thai e pretendo competir futuramente.</p>
        </section>
    </main>
</body>
</html>

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formação</title>
</head>
<body>
    <main>
        <section id="formacao">
            <h1>Formação</h1>
            <h2>Educação</h2>
            <p>Comecei minha graduação em ADS (Análise e Desenvolvimento de Sistemas) na Una, e agora imigrei para a Uninter onde pretendo terminar minha graduação.</p>
            <h2>Idiomas</h2>
            <p>Eu falo inglês intermediário e japonês básico.</p>
        </section>
    </main>
</body>
</html>


<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contato</title>
</head>
<body>

    <main>
        <section id="contato">
            <h1>Contato</h1>
            <form action="ayumichino98@gmail.com" method="post" enctype="text/plain">
                <label for="nome">Nome:</label>
                <input type="text" id="nome" name="nome" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="mensagem">Mensagem:</label>
                <textarea id="mensagem" name="mensagem" required></textarea>
                <button type="submit">Enviar</
