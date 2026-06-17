# Fluxo
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Apresentação do Fluxo abate em terceiro </title>

  <style>
    :root {
      --primary: #123c69;
      --secondary: #1f6f8b;
      --accent: #f2a900;
      --bg: #f4f6f9;
      --card: #ffffff;
      --text: #1f2937;
      --muted: #6b7280;
      --border: #e5e7eb;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Segoe UI", Arial, sans-serif;
    }

    body {
      background: var(--bg);
      color: var(--text);
    }

    header {
      background: linear-gradient(135deg, var(--primary), var(--secondary));
      color: white;
      padding: 32px 50px;
      border-bottom: 5px solid var(--accent);
    }

    header h1 {
      font-size: 30px;
      margin-bottom: 8px;
    }

    header p {
      font-size: 15px;
      opacity: 0.9;
    }

    .container {
      max-width: 1280px;
      margin: 30px auto;
      padding: 0 24px;
    }

    .intro {
      background: var(--card);
      border-radius: 16px;
      padding: 26px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.06);
      border-left: 6px solid var(--accent);
      margin-bottom: 24px;
    }

    .intro h2 {
      color: var(--primary);
      font-size: 22px;
      margin-bottom: 10px;
    }

    .intro p {
      color: var(--muted);
      line-height: 1.6;
      font-size: 15px;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 18px;
      margin-bottom: 24px;
    }

    .card {
      background: var(--card);
      border-radius: 14px;
      padding: 20px;
      border: 1px solid var(--border);
      box-shadow: 0 6px 16px rgba(0,0,0,0.04);
    }

    .card h3 {
      font-size: 16px;
      color: var(--primary);
      margin-bottom: 8px;
    }

    .card p {
      font-size: 14px;
      color: var(--muted);
      line-height: 1.5;
    }

    .miro-section {
      background: var(--card);
      border-radius: 18px;
      padding: 22px;
      box-shadow: 0 10px 28px rgba(0,0,0,0.08);
      border: 1px solid var(--border);
    }

    .miro-header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-bottom: 16px;
      gap: 16px;
    }

    .miro-header h2 {
      font-size: 20px;
      color: var(--primary);
    }

    .badge {
      background: rgba(242, 169, 0, 0.15);
      color: #8a5f00;
      padding: 8px 14px;
      border-radius: 999px;
      font-size: 13px;
      font-weight: 600;
      white-space: nowrap;
    }

    .miro-frame {
      width: 100%;
      height: 650px;
      border-radius: 14px;
      overflow: hidden;
      border: 1px solid var(--border);
      background: #eef2f7;
    }

    .miro-frame iframe {
      width: 100%;
      height: 100%;
      border: none;
    }

    footer {
      text-align: center;
      padding: 22px;
      font-size: 13px;
      color: var(--muted);
    }

    @media (max-width: 900px) {
      header {
        padding: 26px 24px;
      }

      .cards {
        grid-template-columns: 1fr;
      }

      .miro-header {
        flex-direction: column;
        align-items: flex-start;
      }

      .miro-frame {
        height: 520px;
      }
    }
  </style>
</head>

<body>

  <header>
    <h1>Apresentação do Fluxo abate em terceiro</h1>
    <p>Visualização organizacional do processo de abate em terceiro</p>
  </header>

  <main class="container">

    <section class="intro">
      <h2>Objetivo da Apresentação</h2>
      <p>
        Apresentar o fluxo operacional de forma clara, visual e padronizada,
        facilitando o entendimento das etapas, responsabilidades, pontos de controle
        e oportunidades de melhoria no processo.
      </p>
    </section>

    <section class="cards">
      <div class="card">
        <h3>📌 Escopo</h3>
        <p>Fluxo desenhado para análise e tomada de decisão.</p>
      </div>

      <div class="card">
        <h3>🔎 Visão do Processo</h3>
        <p>Permite acompanhar as etapas do processo de ponta a ponta com maior clareza.</p>
      </div>

      <div class="card">
        <h3>✅ Resultado Esperado</h3>
        <p>Padronização, redução de falhas e melhor governança operacional e visão de melhoria de processo.</p>
      </div>
    </section>

    <section class="miro-section">
      <div class="miro-header">
        <h2>Fluxo Interativo</h2>
        <span class="badge">Modo visualização</span>
      </div>

      <div class="miro-frame">
        <iframe 
          src="https://miro.com/app/live-embed/uXjVHEmw8x4=/?embedMode=view_only_without_ui&moveToViewport=-1442,-334,3657,1735&embedId=378639256697"
          scrolling="no"
          allow="fullscreen; clipboard-read; clipboard-write"
          allowfullscreen>
        </iframe>
      </div>
    </section>

  </main>

  <footer>
    Desenvolvido para apresentação corporativa de fluxo operacional
  </footer>

</body>
</html>
