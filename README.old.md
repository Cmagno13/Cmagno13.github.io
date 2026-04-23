<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Carlos Magno Ribeiro | Cientista de Dados</title>
  <style>
    /* 1. DEFINIÇÃO DE VARIÁVEIS GLOBAIS
      Centraliza cores, fontes e espaçamentos para fácil manutenção.
    */
    :root {
      --color-primary: #0077b5;
      --color-primary-hover: #005582;
      --color-success: #28a745;
      --color-success-hover: #1e7e34;
      --color-background-start: #1c1c1c;
      --color-background-end: #333;
      --color-surface: #222;
      --color-text: #f0f0f0;
      --color-text-muted: #aaa;
      --font-family-base: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      --border-radius-small: 8px;
      --border-radius-large: 15px;
      --shadow-color: rgba(0, 0, 0, 0.6);
    }

    /* 2. ESTILOS BASE E LAYOUT
      Usa padding no body e unidades 'rem' para um layout mais escalável.
    */
    body {
      font-family: var(--font-family-base);
      background: linear-gradient(to right, var(--color-background-start), var(--color-background-end));
      color: var(--color-text);
      margin: 0;
      padding: 2rem; /* Adiciona espaçamento nas bordas da tela */
      min-height: 100vh;
      text-align: center;
      box-sizing: border-box; /* Garante que o padding não cause overflow */
    }

    .container {
      display: flex;
      flex-wrap: wrap; /* Permite que as colunas quebrem em telas menores */
      justify-content: center; /* Centraliza as colunas */
      gap: 2rem; /* Espaço entre as colunas usando 'rem' */
      width: 100%;
      max-width: 1600px; /* Limite máximo para telas ultra-largas */
      margin: 0 auto; /* Centraliza o container */
    }

    .left-column, .right-column {
      background-color: var(--color-surface);
      padding: 2rem;
      border-radius: var(--border-radius-large);
      box-shadow: 0 0 20px var(--shadow-color);
      box-sizing: border-box;
      flex: 1; /* Permite que as colunas cresçam de forma flexível */
      min-width: 300px; /* Largura mínima antes de quebrar a linha */
      text-align: left; /* Alinha o texto à esquerda dentro das colunas */
    }

    /* 3. TIPOGRAFIA FLUÍDA
      Usa clamp() para que as fontes se ajustem ao tamanho da tela.
      clamp(MIN, IDEAL, MAX)
    */
    h1 {
      font-size: clamp(2rem, 5vw, 2.5rem); /* 32px -> 40px */
      margin-bottom: 0.5rem;
    }

    h2 {
      font-size: clamp(1.1rem, 2.5vw, 1.25rem); /* 18px -> 20px */
      color: var(--color-text-muted);
      margin-top: 0;
      margin-bottom: 1.5rem;
    }

    h3 {
       font-size: clamp(1.5rem, 4vw, 2rem);
       margin-bottom: 1.5rem;
       text-align: center;
    }

    h4 {
        font-size: clamp(1rem, 3vw, 1.15rem);
    }

    p {
      font-style: italic;
      font-size: clamp(0.9rem, 2vw, 1rem); /* 14.4px -> 16px */
      line-height: 1.6; /* Melhora a legibilidade */
      margin-bottom: 2rem;
    }
    
    .right-column p {
        font-style: normal;
    }

    /* 4. COMPONENTES: BOTÕES E PROJETOS
    */
    .buttons {
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }

    .buttons a {
      text-decoration: none;
      color: white;
      background-color: var(--color-primary);
      padding: 0.8rem 1rem;
      border-radius: var(--border-radius-small);
      font-weight: bold;
      transition: background-color 0.3s ease, transform 0.2s ease;
      text-align: center;
    }

    .buttons a:hover {
      background-color: var(--color-primary-hover);
      transform: translateY(-2px); /* Efeito de elevação sutil */
    }

    .buttons .cv {
      background-color: var(--color-success) !important;
    }

    .buttons .cv:hover {
      background-color: var(--color-success-hover) !important;
    }

    .project {
      margin-top: 2.5rem;
      background-color: #333;
      padding: 1.5rem;
      border-radius: var(--border-radius-large);
      transition: box-shadow 0.3s ease;
    }
    
    .project:hover {
        box-shadow: 0 0 15px rgba(0, 119, 181, 0.4);
    }

    .project img {
      max-width: 100%;
      height: auto;
      border-radius: var(--border-radius-small);
      margin-bottom: 1rem;
    }

    .project a {
      color: var(--color-primary);
      text-decoration: none;
      font-weight: bold;
    }

    .project a:hover {
      text-decoration: underline;
      color: var(--color-primary-hover);
    }
    
    /* 5. MEDIA QUERY PARA TELAS MENORES (MOBILE)
      Simplificado, pois o flex-wrap já cuida da quebra de linha.
    */
    @media (max-width: 768px) {
      body {
        padding: 1rem; /* Menos padding em telas pequenas */
        text-align: left; /* Ajusta o alinhamento geral */
      }
      
      .container {
        flex-direction: column;
        align-items: center;
      }

      .left-column, .right-column {
         width: 100%; /* Colunas ocupam toda a largura */
         min-width: unset; /* Remove a largura mínima */
      }
      
      h1, h2, h3 {
        text-align: center;
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
      <h3>Portfólio de Projetos</h3>

      <div class="project">
        <img src="https://github.com/Cmagno13/Portifoliio-Apache-Superset/blob/main/indicadores-pmrs-2025-02-21T17-00-45.393Z.jpg?raw=true" alt="Dashboard de Indicadores PMRS no Superset"/>
        <h4>Indicadores PMRS</h4>
        <p>Visualização de indicadores de performance utilizando Apache Superset, com integração ao Snowflake e outras fontes de dados.</p>
        <a href="https://github.com/Cmagno13/Portifoliio-Apache-Superset" target="_blank">Ver Projeto no GitHub</a>
      </div>

      <div class="project">
        <img src="https://github.com/Cmagno13/Portifoliio-Apache-Superset/blob/main/indicadores-pmrs-2025-02-21T17-01-02.734Z.jpg?raw=true" alt="Dashboard interativo com filtros dinâmicos no Superset"/>
        <h4>Dashboard Interativo</h4>
        <p>Dashboard interativo com filtros dinâmicos para análise detalhada de indicadores no Apache Superset.</p>
        <a href="https://github.com/Cmagno13/Portifoliio-Apache-Superset" target="_blank">Ver Projeto no GitHub</a>
      </div>

      <div class="project">
        <img src="https://github.com/Cmagno13/Portifoliio-Apache-Superset/blob/main/custo-de-producao-agricola-companhia-nacional-de-abastecimento-poc-004-2025-02-21T18-07-01.611Z.jpg?raw=true" alt="Análise de custo de produção agrícola para a CONAB"/>
        <h4>Custo de Produção Agrícola (CONAB)</h4>
        <p>Projeto de análise de custo de produção agrícola para a Companhia Nacional de Abastecimento (CONAB), utilizando Apache Superset e PostgreSQL.</p>
        <a href="https://github.com/Cmagno13/Portifoliio-Apache-Superset" target="_blank">Ver Projeto no GitHub</a>
      </div>
    </div>
  </div>
</body>
</html>
