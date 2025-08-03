# 🏆 Análise Histórica do Campeonato Brasileiro (2003–2024) – Power BI

Este projeto explora dados do Campeonato Brasileiro Série A de 2003 a 2024, com foco em visualizações interativas, desempenho por clube, gols e artilheiros. Foi desenvolvido como parte de um portfólio pessoal com Power BI.

---

## 📂 Fonte dos Dados

Base pública do Kaggle:  
🔗 [Campeonato Brasileiro de Futebol – Kaggle](https://www.kaggle.com/datasets/adaoduque/campeonato-brasileiro-de-futebol/data)

Arquivos utilizados:
- `campeonato-brasileiro-full.csv`
- `campeonato-brasileiro-estatisticas-full.csv`
- `campeonato-brasileiro-gols.csv`

---

## 🔍 Perguntas Respondidas pelo Dashboard
Com o objetivo de entender a evolução dos clubes desde o início da era por pontos corridos do campeonato brasileiro, surgem as seguintes perguntas:

- Qual clube teve mais vitórias entre 2003 e 2024?
- Qual foi o aproveitamento dos clubes ao longo dos anos?
- Como variam os gols marcados por rodada e por temporada?
- Os mandantes ou visitantes têm o melhor desempenho?
- Quais foram os maiores artilheiros desde 2014?
- Quais rodadas tiveram maior média de gols por jogo?
- Qual a evolução dos gols por partida ao longo dos anos?

---
## 🪜 ETAPAS

### 1. ETL
  - Tratamento e transformação no Power Query: exclusão de colunas irrelevantes para análise
  - Criação de colunas como `Temporada = YEAR([data])`
  - Criação de uma tabela auxiliar de clubes


### 2. Métricas em DAX
  - Gols por rodada, por partida, visitantes e mandantes e por jogador
  - Vitórias e aproveitamento (%)
---

## 📊 Estrutura do Dashboard

### 1️⃣ Visão Geral (2003–2024)
**KPIs:**
- Total de partidas, total de gols, gols por partida, clube com mais vitórias e total de empates
  
**Filtros:**
- Temporadas e clubes 

**Gráficos:**
- 🥇 Vitórias por clube 
- 🎯 Aproveitamento por clube
- 🏠 vs 🛫 Aproveitamento mandante x visitante


<img width="1327" height="767" alt="image" src="https://github.com/user-attachments/assets/ebee4d37-44a8-4fd1-b2aa-85b6283a8896" />

---

### 2️⃣ Visão de Gols (2003–2024)

**KPIs:**
- Total de gols, gols por partida

**Gráficos:**
- 📈 Gols por partida ao longo do tempo
- 🆚 Gols mandante vs visitante por temporada
- 📊 Gols por rodada por jogo (média)
- 👟 Maiores artilheiros (2014–2024)
  
<img width="1329" height="767" alt="image" src="https://github.com/user-attachments/assets/8e9504b0-9479-4de9-9c1e-3c5514b834a4" />

---

## 🚀 Possíveis Expansões 

- Análise por jogador (gols, cartões, minutos)
- Gráfico de localização geográfica dos jogos
- Tabelas de classificação por temporada

---

## 🎓 Aprendizados

Durante o desenvolvimento deste projeto, aprofundei meus conhecimentos em:
- Modelagem de dados no Power BI
- Criação de medidas complexas em DAX
- Visualizações interativas
- Integração de diferentes fontes de dados 

Este projeto também serviu como prática real para a construção de um portfólio de análise de dados.

---

## ✅ Considerações Finais

Este dashboard tem como objetivo fornecer uma visão histórica abrangente do Campeonato Brasileiro, permitindo explorar tendências, destaques e desempenho dos clubes ao longo dos anos. É um excelente exemplo do potencial do Power BI aplicado a contextos esportivos, unindo análise estatística, storytelling visual e facilidade de uso para o usuário final.

---

## 👤 Autor

Projeto desenvolvido por **Caio Yuji Simonoe** como parte de um portfólio em análise de dados com Power BI.


