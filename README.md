<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Ecolove Garden transforma espaços urbanos em áreas verdes sustentáveis, utilizando tecnologias avançadas e promovendo práticas de sustentabilidade e paisagismo biofílico.">
    <title>Ecolove Garden | Sustentabilidade e Paisagismo Biofílico</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap">
    <style>
        /* Estilo Global */
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }

        /* Cabeçalho */
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1.5em 0;
            text-align: center;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }

        /* Navegação */
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 0.5em 0;
            margin-top: 60px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            padding: 0.5em 1em;
            transition: background 0.3s;
            aria-label: "Navegação Principal";
        }

        nav a:hover {
            background-color: #4CAF50;
            border-radius: 5px;
        }

        /* Seções */
        section {
            padding: 20px;
            max-width: 900px;
            margin: auto;
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.5s, transform 0.5s;
        }

        section.in-view {
            opacity: 1;
            transform: translateY(0);
        }

        h2 {
            color: #4CAF50;
            margin-top: 0;
        }

        /* Botões */
        .btn {
            display: inline-block;
            padding: 10px 20px;
            margin: 10px 0;
            background-color: #4CAF50;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s;
        }

        .btn:hover {
            background-color: #45a049;
        }

        /* Imagens */
        img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        /* Equipe */
        .team {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .team-member {
            flex: 1 1 300px;
            margin: 10px;
            text-align: center;
        }

        .team-member img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 2em 0;
        }

        footer p, footer a {
            color: #f1f1f1;
            font-size: 0.9em;
            margin: 0;
        }

        footer a {
            text-decoration: none;
            color: #4CAF50;
            transition: color 0.3s;
        }

        footer a:hover {
            color: #fff;
        }

        .social-icons a {
            display: inline-block;
            margin: 0 10px;
            color: #4CAF50;
            font-size: 1.5em;
        }

        .social-icons a:hover {
            color: #fff;
        }

        /* Responsivo */
        @media (max-width: 600px) {
            nav {
                flex-direction: column;
            }
            nav a {
                margin: 5px 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Ecolove Garden</h1>
        <p>Conectando Sustentabilidade, Tecnologia e Natureza</p>
    </header>

    <nav>
        <a href="#proposta">Proposta e Valores</a>
        <a href="#tecnologias">Tecnologias</a>
        <a href="#impacto">Impacto Ambiental</a>
        <a href="#projetos">Projetos em Destaque</a>
        <a href="#equipe">Equipe</a>
        <a href="#contato">Contato</a>
    </nav>

    <section id="proposta" class="section">
        <h2>Proposta e Valores</h2>
        <p>A Ecolove Garden transforma espaços urbanos em áreas verdes sustentáveis, promovendo um futuro mais equilibrado e sustentável. Estamos comprometidos com práticas de sustentabilidade, alinhados com os Objetivos de Desenvolvimento Sustentável (ODS) e focados em criar ambientes que beneficiem tanto as pessoas quanto o planeta.</p>
    </section>

    <section id="tecnologias" class="section">
        <h2>Tecnologias</h2>
        <p>Utilizamos tecnologias da Indústria 4.0, como IoT, inteligência artificial e anális# ecolovegarden