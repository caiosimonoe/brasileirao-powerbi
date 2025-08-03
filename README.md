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
Com o objetivo de entender a evolução dos clubes desde o início da era por pontos corridos do campoeonato brasileiro, surgem as seguintes perguntas:

- Qual clube teve mais vitórias entre 2003 e 2024?
- Qual foi o aproveitamento dos clubes ao longo dos anos?
- Como variam os gols marcados por rodada e por temporada?
- Os mandantes ou visitantes têm melhor desempenho?
- Quais foram os maiores artilheiros desde 2014?
- Quais rodadas tiveram maior média de gols por jogo?
- Qual a evolução dos gols por partida ao longo dos anos?

---
## 🔄 ETAPAS

1. ETL
- Tratamento e transformação no Power Query: exclusão de colunas irrelevantes para análise
- Criação de colunas como `Temporada = YEAR([data])`
- Unificação de nomes de clubes em tabela auxiliar

---

## 📊 Estrutura do Dashboard

### 1️⃣ Visão Geral (2003–2024)
**KPIs:**
- Total de partidas
- Total de gols
- Gols por partida
- Clube com mais vitórias
- Clube com melhor aproveitamento
- Aproveitamento mandante vs visitante

**Gráficos:**
- 🥇 Vitórias por clube 
- 🎯 Aproveitamento por clube
- 🏠 vs 🛫 Aproveitamento mandante x visitante

---

### 2️⃣ Visão de Gols (2003–2024)

**KPIs:**
- Total de gols
- Gols por partida

**Gráficos:**
- 📈 Gols por partida ao longo do tempo
- 🆚 Gols mandante vs visitante por temporada
- 📊 Gols por rodada por jogo (média)
- 👟 Maiores artilheiros (2014–2024)
--

## 🚀 Possíveis Expansões

- Análise por jogador (gols, cartões, minutos)
- Gráfico de localização geográfica dos jogos
- Simulações de ranking Elo ou classificação dinâmica

---

## 👤 Autor

Projeto desenvolvido por **caiosimonoe** como parte de um portfólio em análise de dados com Power BI.

---

## 📜 Licença

Dados públicos do Kaggle. Projeto sem fins lucrativos, para fins educacionais e demonstrativos.


