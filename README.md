# 📊 Análise de Dashboard de Vendas no Power BI

Projeto desenvolvido para o desafio **Analisando dados de um Dashboard de Vendas no Power BI**, utilizando a base **Financial Sample**.

[![Power BI](https://img.shields.io/badge/Power%20BI-Desktop-F2C811?logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/desktop/)
[![GitHub](https://img.shields.io/badge/GitHub-Reposit%C3%B3rio-181717?logo=github)](https://github.com/)

## 🎯 Objetivo

Replicar e complementar um dashboard de vendas no Power BI, explorando indicadores de **vendas, lucro, unidades vendidas, segmentos, produtos e distribuição geográfica**.

A entrega também registra a construção da página **Análise Geográfica**, criada a partir do modelo do desafio.

## 🧰 Ferramentas e tecnologias

- **Power BI Desktop** — modelagem e visualização dos dados
- **Microsoft Excel** — base `Financial Sample.xlsx`
- **Git e GitHub** — versionamento e documentação do projeto

## 📁 Estrutura do repositório

```text
powerbi-analise-dashboard-vendas/
├── README.md
├── LICENSE
├── .gitignore
├── dados/
│   └── Financial Sample.xlsx
├── imagens/
│   ├── resultados-base.png
│   ├── erro-radar-chart.png
│   └── erro-chiclet-slicer.png
└── relatorio/
    └── Desafio_Analise_Dashboard_Vendas_PowerBI.pbix
```

## 👀 Visão geral

A base possui **700 registros** e 16 campos, com informações de segmento, país, produto, unidades vendidas, preços, vendas, custos, lucro e período.

![Resumo dos dados](imagens/resultados-base.png)

## 📊 Páginas do relatório

### Página 1 — Visão geral de vendas

Apresenta os principais indicadores comerciais e financeiros do conjunto de dados, permitindo observar o desempenho de vendas, custos, lucro e volume de unidades.

### Página 2 — Detalhamento

Explora os dados por diferentes dimensões, como produto e segmento, facilitando a comparação dos resultados.

### Página 3 — Análise Geográfica

Página criada para ampliar a análise com foco em localização e rentabilidade. Contém:

- mapa de **vendas e unidades vendidas por país**;
- mapa de **lucro por país**;
- gráfico de **lucro por segmento**;
- interação entre os visuais para facilitar análises cruzadas.

## 📈 Principais resultados da base

> Os números abaixo são calculados diretamente sobre a `Financial Sample.xlsx` usada no projeto. Eles representam a base de exemplo e não devem ser interpretados como dados reais de uma empresa.

| Indicador | Resultado |
|---|---:|
| Vendas totais | **US$ 118,73 milhões** |
| Lucro total | **US$ 16,89 milhões** |
| Unidades vendidas | **1,13 milhão** |
| País com maior volume de vendas | **Estados Unidos** — US$ 25,03 milhões |
| Segmento com maior volume de vendas | **Government** — US$ 52,50 milhões |
| Produto com maior volume de vendas | **Paseo** — US$ 33,01 milhões |

### Observações analíticas

- **Government** concentra o maior volume de vendas e também representa a maior parcela do lucro da base.
- **Paseo** é o produto com maior volume de vendas no conjunto analisado.
- Os resultados geográficos mostram diferenças relevantes de vendas e lucro entre os cinco países presentes na base.
- O segmento **Enterprise** apresenta **lucro agregado negativo** na base utilizada no desafio, apesar de possuir volume relevante de vendas.

## ▶️ Como usar o projeto

### 1. Instalar o Power BI Desktop

Baixe e instale o Power BI Desktop pelo site da Microsoft:

https://powerbi.microsoft.com/desktop/

### 2. Baixar o repositório

Clone o projeto:

```bash
git clone <URL-DO-SEU-REPOSITORIO>
cd powerbi-analise-dashboard-vendas
```

Ou faça o download do repositório em **Code → Download ZIP** no GitHub.

### 3. Abrir o relatório

Abra:

```text
relatorio/Desafio_Analise_Dashboard_Vendas_PowerBI.pbix
```

### 4. Conferir a fonte de dados

A base original está em:

```text
dados/Financial Sample.xlsx
```

Caso o Power BI solicite a localização do arquivo, aponte a fonte para essa planilha.

### 5. Interagir com o dashboard

Utilize os filtros, segmentações e elementos gráficos para analisar:

- vendas por país;
- lucro por país;
- desempenho por segmento;
- desempenho por produto;
- evolução por período;
- relação entre vendas, custos e lucro.

## 🖼️ Imagens do projeto

### Resumo da base

![Resumo da base](imagens/resultados-base.png)

### Registro de dependências de visuais personalizados

Durante a abertura do PBIX em determinados ambientes, podem ser exibidas solicitações para instalação de visuais personalizados.

![Erro Radar Chart](imagens/erro-radar-chart.png)

![Erro Chiclet Slicer](imagens/erro-chiclet-slicer.png)

Esses avisos estão relacionados aos visuais personalizados e **não à qualidade dos dados da Financial Sample**. Quando necessário, utilize **Obter mais visuais** no Power BI Desktop para instalar o visual solicitado.

## 🔎 Fonte do desafio

Repositório de referência utilizado no desafio:

https://github.com/julianazanelatto/power_bi_analyst

## 📌 Observação sobre a base

A `Financial Sample.xlsx` é uma base de exemplo. Os indicadores apresentados neste README foram calculados a partir dos registros disponíveis no arquivo e servem para documentar o projeto.

## 👩‍💻 Projeto

**Análise de Dashboard de Vendas — Power BI**

Desafio de formação em análise de dados e Business Intelligence.