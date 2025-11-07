# 📊 Projeto Final - Power BI

Este repositório contém o **dashboard final** desenvolvido como parte do projeto de análise de dados no Power BI.  
O objetivo foi transformar uma planilha de vendas bruta em um painel **interativo, visual e profissional**, que facilite a **tomada de decisões estratégicas** pela equipe de gestão.

---

## 🎯 Objetivo do Projeto

Fornecer uma visão clara e rápida sobre o **desempenho das vendas** da empresa, incluindo:
- Lucro total por país;
- Produtos mais lucrativos;
- Evolução temporal de lucros e vendas;
- Distribuição de vendas por segmento de mercado.

---

## 🧩 Indicadores e Visuais

O dashboard é composto pelos seguintes elementos:

### 1️⃣ Lucro Total (R$) por País e Segmento  
> **Tipo:** Mapa de bolhas  
> **Finalidade:** Identificar quais países e segmentos geram maior lucro.

### 2️⃣ Top 5 Produtos Mais Lucrativos (R$)  
> **Tipo:** Gráfico de barras horizontais  
> **Finalidade:** Destacar os produtos com maior rentabilidade.

### 3️⃣ Evolução de Lucro e Vendas ao Longo do Tempo  
> **Tipo:** Gráfico de linhas  
> **Finalidade:** Analisar tendências e sazonalidades mensais.

### 4️⃣ Distribuição das Vendas Totais (R$) por Segmento  
> **Tipo:** Gráfico de rosca  
> **Finalidade:** Mostrar a representatividade percentual de cada segmento no total das vendas.

---

## 💡 Recursos Adicionais

- **Medidas DAX** utilizadas:
  ```DAX
  Lucro Total R$ = SUM('Sheet1'[Lucro])
  Vendas Totais R$ = SUM('Sheet1'[Vendas Líquidas])
