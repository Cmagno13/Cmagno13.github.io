<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio de Ciência de Dados</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        .portfolio {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .project {
            border: 1px solid #ccc;
            border-radius: 8px;
            padding: 15px;
        }
        .project img {
            max-width: 100%;
            border-radius: 8px;
        }
        .project h3 {
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <h1>Portfólio de Ciência de Dados e Visualização</h1>
    <div class="portfolio">
        <div class="project">
            <img src="images/projeto1.png" alt="Projeto 1">
            <h3>Projeto 1</h3>
            <p>Descrição breve do projeto.</p>
            <a href="https://github.com/Cmagno13/projeto1">Ver no GitHub</a>
        </div>
        <div class="project">
            <img src="images/projeto2.png" alt="Projeto 2">
            <h3>Projeto 2</h3>
            <p>Descrição breve do projeto.</p>
            <a href="https://github.com/Cmagno13/projeto2">Ver no GitHub</a>
        </div>
    </div>
</body>
</html>
