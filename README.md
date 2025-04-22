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
      justify-content: center; /* Mantido para centralizar o bloco, ajuste se quiser alinhar à esquerda */
      align-items: flex-start; /* Ajustado para alinhar o conteúdo no topo em vez de centralizar verticalmente */
      min-height: 100vh;
      text-align: center;
    }

    .container {
      display: flex;
      justify-content: space-between;
      width: 95%; /* Aumente a porcentagem para usar mais da largura da tela */
      max-width: 1600px; /* Aumente o max-width ou remova esta linha para não ter um limite fixo */
      gap: 40px; /* Opcional: Aumentar o espaço entre as colunas */
      margin-top: 30px; /* Adiciona um pouco de espaço no topo para não colar */
      margin-bottom: 30px; /* Adiciona um pouco de espaço na parte inferior */
    }

    .left-column {
      width: 48%; /* Aumente a porcentagem */
      background-color: #222;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.6);
      box-sizing: border-box; /* Inclui padding e border no cálculo da largura */
    }

    .right-column {
      width: 48%; /* Aumente a porcentagem */
      background-color: #222;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.6);
      box-sizing: border-box; /* Inclui padding e border no cálculo da largura */
    }

    h1 {
      font-size: 32px; /* Exemplo: aumentar o tamanho do título principal */
      margin-bottom: 10px;
    }

    h2 {
      font-size: 20px; /* Exemplo: aumentar o tamanho do subtítulo */
      color: #aaa;
      margin-bottom: 20px;
    }

    p {
      font-style: italic;
      font-size: 16px; /* Exemplo: aumentar o tamanho do parágrafo */
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

    .project {
      margin-top: 40px;
      background-color: #333;
      padding: 20px;
      border-radius: 10px;
    }

    .project img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }

    .project a {
      color: #0077b5;
      text-decoration: none;
      font-weight: bold;
    }

    .project a:hover {
      color: #005582;
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

    @media (max-width: 768px) {
      .container {
        flex-direction: column;
        align-items: center;
        width: 95%; /* Garante que use uma boa parte da tela menor */
        gap: 30px; /* Espaço entre as colunas na visão mobile */
      }

      .left-column, .right-column {
        width: 95%; /* Ocupa quase toda a largura na visão mobile */
      }
    }

  </style>
</head>
<body>
  <div class="container">
    <div class="left-column">
      <h1>Carlos Magno Ribeiro</h1>
      <h2>Cientista de Dados | Especialista em DataViz</h2>
      <p>Transformando dados em decisões com visualizações inteligentes. Com experiência em ETL, BI e análise de dados, busco soluções inovadoras para negócios.</p>

      <div class="buttons">
        <a href="https://www.linkedin.com/in/carlos-magno-ribeiro-a6b7b043/" target="_blank">🔗 LinkedIn</a>
        <a href="Carlos_Magno_Ribeiro_CV.pdf" class="cv" download>📄 Baixar Currículo (PDF)</a>
      </div>
    </div>

    <div class="right-column">
      <h3>Portfólio</h3>

      <div class="project">
        <img src="https://github.com/Cmagno13/Portifoliio-Apache-Superset/blob/main/indicadores-pmrs-2025-02-21T17-00-45.393Z.jpg?raw=true" alt="Projeto 1"/>
        <h4>Indicadores PMRS</h4>
        <p>Visualização de indicadores de performance utilizando Apache Superset, com integração ao Snowflake e outras fontes de dados.</p>
        <a href="https://github.com/Cmagno13/Portifoliio-Apache-Superset" target="_blank">Ver Projeto no GitHub</a>
      </div>

      <div class="project">
        <img src="https://github.com/Cmagno13/Portifoliio-Apache-Superset/blob/main/indicadores-pmrs-2025-02-21T17-01-02.734Z.jpg?raw=true" alt="Projeto 2"/>
        <h4>Indicadores PMRS - 2ª Imagem</h4>
        <p>Mais uma visualização de indicadores no Apache Superset, com dashboard interativo e filtros dinâmicos.</p>
        <a href="https://github.com/Cmagno13/Portifoliio-Apache-Superset" target="_blank">Ver Projeto no GitHub</a>
      </div>

      <div class="project">
        <img src="https://github.com/Cmagno13/Portifoliio-Apache-Superset/blob/main/custo-de-producao-agricola-companhia-nacional-de-abastecimento-poc-004-2025-02-21T18-07-01.611Z.jpg?raw=true" alt="Projeto 3"/>
        <h4>Custo de Produção Agrícola</h4>
        <p>Projeto de análise de custo de produção agrícola para a Companhia Nacional de Abastecimento, utilizando Apache Superset e PostgreSQL.</p>
        <a href="https://github.com/Cmagno13/Portifoliio-Apache-Superset" target="_blank">Ver Projeto no GitHub</a>
      </div>
    </div>
  </div>
</body>
</html>
