<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfólio de Ciência de Dados</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      background: linear-gradient(to right, #1c1c1c, #333);
      color: #f0f0f0;
    }

    h1 {
      text-align: center;
      color: #f0f0f0;
    }

    .portfolio {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .project {
      border: 1px solid #444;
      border-radius: 8px;
      padding: 15px;
      background-color: #222;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
    }

    .project img {
      max-width: 100%;
      border-radius: 8px;
    }

    .project h3 {
      margin: 10px 0;
      color: #ffffff;
    }

    .project p {
      color: #cccccc;
    }

    .project a {
      display: inline-block;
      margin-top: 10px;
      text-decoration: none;
      color: white;
      background-color: #007bff;
      padding: 8px 12px;
      border-radius: 4px;
      font-weight: bold;
    }

    .project a:hover {
      background-color: #0056b3;
    }

    @media (max-width: 480px) {
      h1 {
        font-size: 24px;
      }
      .project {
        padding: 10px;
      }
    }
  </style>
</head>
<body>
  <h1>Portfólio de Ciência de Dados</h1>
  <div class="portfolio">
    
    <div class="project">
      <img src="images/Snowflake Dashboard.png" alt="Snowflake Dashboard" />
      <h3>Snowflake Dashboard</h3>
      <p>Dashboard interativo construído a partir de dados do Google Analytics integrados ao Snowflake, com visualizações em ferramentas de BI.</p>
      <a href="https://github.com/Cmagno13/Full-Cycle-ETL-Analytics-with-Google-Analytics-and-Snowflake-main" target="_blank">Ver Projeto no GitHub</a>
    </div>

  </div>
</body>
</html>
