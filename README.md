<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Carlos Magno Ribeiro | Cientista de Dados</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(to right, #1c1c1c, #333);
      color: #f0f0f0;
      margin: 0;
      padding: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
    }

    .card {
      background-color: #222;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.6);
      max-width: 400px;
      width: 90%;
    }

    h1 {
      font-size: 28px;
      margin-bottom: 10px;
    }

    h2 {
      font-size: 18px;
      color: #aaa;
      margin-bottom: 20px;
    }

    p {
      font-style: italic;
      margin-bottom: 30px;
    }

    .buttons {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }

    .buttons a {
      text-decoration: none;
      color: white;
      background-color: #0077b5;
      padding: 12px;
      border-radius: 8px;
      font-weight: bold;
      transition: background-color 0.3s ease;
    }

    .buttons a:hover {
      background-color: #005582;
    }

    .cv {
      background-color: #28a745 !important;
    }

    .cv:hover {
      background-color: #1e7e34 !important;
    }

    .viz-icons {
      margin-top: 40px;
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      gap: 20px;
    }

    .viz-icons img {
      width: 50px;
      height: 50px;
      opacity: 0.9;
    }

    @media (max-width: 480px) {
      h1 {
        font-size: 24px;
      }
      h2 {
        font-size: 16px;
      }
      .buttons a {
        font-size: 14px;
      }
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>Carlos Magno Ribeiro</h1>
    <h2>Cientista de Dados | Especialista em DataViz</h2>
    <p>Transformando dados em decisões com visualizações inteligentes.</p>
    
    <div class="buttons">
      <a href="https://www.linkedin.com/in/carlos-magno-ribeiro-a6b7b043/" target="_blank">🔗 LinkedIn</a>
      <a href="Carlos_Magno_Ribeiro_CV.pdf" class="cv" download>📄 Baixar Currículo (PDF)</a>
    </div>

    <div class="viz-icons">
      <img src="https://img.icons8.com/ios-filled/50/ffffff/combo-chart.png" alt="Gráfico 1"/>
      <img src="https://img.icons8.com/ios-filled/50/ffffff/pie-chart.png" alt="Gráfico 2"/>
      <img src="https://img.icons8.com/ios-filled/50/ffffff/bar-chart.png" alt="Gráfico 3"/>
    </div>
  </div>
</body>
</html>
