# 📊 Análise de Dashboard de Vendas no Power BI

Projeto desenvolvido para o desafio **Analisando dados de um Dashboard de Vendas no Power BI**, utilizando a base **Financial Sample**.

## 🎯 Objetivo

Replicar e complementar um dashboard de vendas no Power BI, explorando indicadores de **vendas, lucro, unidades vendidas, segmentos, produtos e distribuição geográfica**.

A entrega também registra a construção da página **Análise Geográfica**, criada a partir do modelo do desafio.

## 🧰 Ferramentas e tecnologias

- **Power BI Desktop** — modelagem e visualização dos dados
- **Microsoft Excel** — base `Financial Sample.xlsx`
- **GitHub** — versionamento e documentação do projeto

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