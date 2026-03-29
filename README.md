# 🏀 T1-NBA — Análise de Desempenho e Salários

**Disciplina:** Métodos Quantitativos para Computação  
**Instituição:** Universidade de Fortaleza — UNIFOR  
**Professor:** Prof. Me. Ricardo Carubbi

---

## 👥 Integrantes do Grupo

| Nome | Matrícula |
|------|-----------|
| João Victor Cunha de Castro | 2410377 |
| Heitor Cunha Damasceno | 2422975 |



---

## 🏆 Equipe Analisada

**Milwaukee Bucks (MIL)**

---

## 📅 Temporadas Analisadas

| Temporada | Jogadores no dataset |
|-----------|----------------------|
| 2022      | 14                   |
| 2023      | 6                    |

---

## ❓ Pergunta de Pesquisa

> Que padrões podem ser observados, entre duas temporadas, na variação do desempenho dos jogadores e de seus salários no Milwaukee Bucks?

---

## 📊 Análises Realizadas

1. **Estatísticas descritivas** — média, mediana, Q1 e Q3 de pontos, rebotes, assistências e salário nas duas temporadas
2. **Média vs Mediana** — comparação visual entre as duas métricas por temporada
3. **Distribuição de pontos por posição** — boxplot comparativo 2022 vs 2023
4. **Distribuição de salário por posição** — boxplot comparativo 2022 vs 2023
5. **Dispersão pontos vs salário** — correlação entre desempenho e remuneração
6. **Variação individual** — evolução dos jogadores presentes nas duas temporadas

---

## 📁 Estrutura do Repositório

```
T1-NBA/
├── dataset/
│   └── nba_stats_preprocessed.csv   # Dataset tratado
├── 1_analises_MIL_2022_2023.ipynb   # Notebook com a análise completa
└── README.md
```

---

## 🎥 Vídeo Explicativo

🔗 (adicionar link do vídeo aqui)

---

## 🔍 Principais Conclusões

- Em 2023, o MIL apresentou **médias superiores** em pontos, rebotes e assistências em relação a 2022
- A **mediana salarial quase dobrou** entre as temporadas, indicando um elenco mais valorizado em 2023
- A distribuição de salários é **assimétrica à direita** — a média supera a mediana em ambas as temporadas, evidenciando contratos milionários que puxam a média para cima
- Existe **correlação positiva** entre pontuação e salário nas duas temporadas
- Jogadores que pontuaram menos em 2023 ainda receberam **aumentos salariais**, indicando que contratos de longo prazo e valor de mercado têm peso independente do desempenho anual
