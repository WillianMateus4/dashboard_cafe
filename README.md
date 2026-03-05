# ☕ Dashboard de Vendas de Café

![Power BI](https://img.shields.io/badge/Power_Bi-F2C811?style=flat-square&logo=codeforces&logoColor=black)

> 🚀 **Acesso Rápido:** [clique aqui para acessar o dashboard interativo online](https://app.powerbi.com/view?r=eyJrIjoiMDZiZDkwMDEtYjcxYy00YTU5LWIxNDgtOTVjNmJmMjJhZjQyIiwidCI6IjI3ODJkNTJlLWQ0ZTMtNDgzZC05OTk1LThiZDljY2UyZTM2NCJ9)

## 📌 Introdução
Este projeto é uma solução para acompanhar os resultados de vendas de uma rede de supermercados, com foco estratégico na categoria de Cafés. O objetivo principal é fornecer à gerência comercial uma ferramenta de tomada de decisão baseada em dados, permitindo a análise rápida de performance de produtos, preço médio e comportamento de marcas específicas.

## ⚙️ ETL
* **Limpeza:** Tratamento de colunas e linhas nulas, verificação de valores únicos na coluna ```Prod Codigo``` da tabela ```dimClassificacao```, além da remoção de números negativos na tabela ```fProdutos``` para garantir a fidelidade da receita.

## 🎯 Principais Funcionalidades

* **Visão Geral:** Visão 360º sobre os 3 principais indicadores (Receita, Volume e Preço Médio), análise de tendência dos últimos 7 dias e um ranking dinâmico por marca, categoria, família e grupo.
* **Detalhamento:** Visão detalhada sobre os indicadores, sendo que través de filtros interativos, o usuário poderá ter uma visão personalizada do que deseja analisar.
* **Informações do produto:** uma página dedicada a analisar os produtos individualmente e acompanhar seus resultados nos últimos 30 dias.
* **Dica de Ferramenta:** Ao passar o mouse sobre um dia específico do Gráfico de Colunas, o usuário acessa o detalhamento do dia, com comparativo (Month-over-Month) e YoY (Year-over-Year).


## 🚀 Futuras Implementações

* **Filtro de Período:** Inclusão de uma segmentação de dados na tela de **Visão Geral** para alterar o gráfico de colunas (ex: Últimos 7 dias, 30 Dias, 3 meses, 6 meses, 1 ano).
* **Filtro de Comparativo MoM e YoY:** Implementação de análises comparativas de MoM e YoY, permitindo a seleção via Parâmetros de Campo.

## 🛠️ Ferramentas e Tecnologias Utilizadas

* **Power BI:** Criação de visuais e montagem do Dashboard.
* **DAX:** Criação de medidas calculadas para as análises temporais (YoY, parâmetros, etc.).
* **Power Query:** Tratamento e limpeza dos dados (ETL).
* **Figma:** Criação de layout do Dashboard.

## 👤 Autor

**Willian Mateus** | *Data Analyst & BI*

 ℹ️ Para saber mais sobre mim, ver meus outros projetos ou entrar em contato, visite meu [Perfil do GitHub](https://github.com/WillianMateus4).
