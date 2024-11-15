<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Simples</title>
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
            background-color: #f4f4f9;
            color: #333;
        }
        /* Estilo do cabeçalho */
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            /*padding: 20px 0;*/
            padding: 20px;
            margin: 20px;
            /*background-color: white;*/
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        /* Estilo do menu de navegação */
        nav ul {
            list-style: none;
            padding: 0;
            text-align: center;
            background-color: #333;
            /*margin-top: 20px;*/
            /*padding: 20px;*/
            margin: 20px;
            /**/
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        nav ul li {
            display: inline;
            margin-right: 20px;
        }
        nav ul li a {
            text-decoration: none;
            color: white;
            font-weight: bold;
            padding: 10px 20px;
        }
        nav ul li a:hover {
            background-color: #555;
            border-radius: 5px;
        }
        /* Estilo das seções */
        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        section h2 {
            margin-bottom: 15px;
            font-size: 1.8em;
        }
        section p {
            font-size: 1em;
            line-height: 1.6;
        }
        /* Estilo do rodapé */
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            margin-top: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <!-- Cabeçalho -->
    <header>
        <h1>Minha Página Simples</h1>
    </header>
    <!-- Menu de navegação -->
    <nav>
        <ul>
            <li><a href="#home">Início</a></li>
            <li><a href="#about">Sobre</a></li>
            <li><a href="#contact">Contato</a></li>
        </ul>
    </nav>
    <!-- Seção Início -->
    <section id="home">
        <h2>Bem-vindo ao Meu Site!</h2>
        <p>Esta é a seção de introdução do seu site. Você pode usar esse espaço para dar boas-vindas aos visitantes e explicar um pouco sobre o propósito do seu site.</p>
    </section>
    <!-- Seção Sobre -->
    <section id="about">
        <h2>Sobre</h2>
        <p>Aqui você pode contar um pouco sobre você, sobre o que fez o site ou qualquer outro detalhe importante. Pode ser um breve parágrafo ou até um pequeno resumo.</p>
    </section>
    <!-- Seção Contato -->
    <section id="contact">
        <h2>Contato</h2>
        <p>Se deseja ser contatado, você pode adicionar suas informações de contato aqui. Por exemplo:</p>
        <address>
            <p>Email: <a href="mailto:seuemail@dominio.com">seuemail@dominio.com</a></p>
            <p>Telefone: (11) 12345-6789</p>
        </address>
    </section>
    <!-- Rodapé -->
    <footer>
        <p>&copy; 2024 Minha Página Simples - Todos os direitos reservados.</p>
    </footer>

</body>
</html>
