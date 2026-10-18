
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Calculadora Avançada – JLS SOFT AI FACTORY</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

<header id="app-header">
  <div class="logo">🧮</div>
  <div>
    <h1>Calculadora Avançada com Impressão</h1>
    <p>JLS SOFT AI FACTORY — Operações em coluna, data/hora ajustável e impressão profissional</p>
  </div>
</header>

<main id="app-main">

  <div id="painel-esquerdo">

    <div class="card" style="margin-bottom:18px">
      <h2>📄 Documento</h2>
      <div class="form-group">
        <label for="input-titulo">Título / Identificação <span style="font-weight:400;color:#888">(opcional — padrão: CÁLCULO, máx. 50 caracteres recomendados)</span></label>
        <input type="text" id="input-titulo" placeholder="Ex: Orçamento, Relatório, Cálculo..." maxlength="80" />
        <span id="msg-titulo-longo">⚠ Títulos com mais de 50 caracteres podem ser cortados ou quebrar o layout na impressão.</span>
      </div>
      <div class="dh-row">
        <div class="form-group">
