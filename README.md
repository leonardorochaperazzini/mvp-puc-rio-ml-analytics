# MVP — Machine Learning & Analytics

**PUC-Rio | Pós-graduação em Ciência de Dados e Analytics**  
Disciplina: Sprint: Machine Learning & Analytics (40530010056_20260_01)

---

## Sobre o Projeto

Modelagem preditiva sobre o dataset **Chicago Crimes (2012–2017)**, com o objetivo de prever se um crime resultará em prisão.

- **Problema:** Classificação binária — prever se houve prisão (`Arrest = True/False`)
- **Dataset:** Chicago Crimes 2012–2017 (~1,45 milhão de registros, 22 atributos)
- **Fonte:** [Kaggle — Crimes in Chicago](https://www.kaggle.com/datasets/currie32/crimes-in-chicago)

Este MVP é uma continuação do trabalho desenvolvido na Sprint de Análise de Dados e Boas Práticas, avançando para a etapa de modelagem, otimização e avaliação crítica de modelos de Machine Learning.

---

## Estrutura do Repositório

```
mvp-puc-rio-ml-analytics/
├── data/
│   └── Chicago_Crimes_2012_to_2017_sample.csv   # Amostra de 20% do dataset (~291k registros)
├── mvp_chicago_crimes_ml.ipynb                   # Notebook principal (Google Colab)
└── README.md
```

> O dataset completo (~1,45M registros, ~300 MB) ultrapassa o limite de arquivo do GitHub. Por isso o repositório inclui apenas a **amostra estratificada de 20%** utilizada no notebook, gerada com `random_state=42`.

---

## Como Executar

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leonardorochaperazzini/mvp-puc-rio-ml-analytics/blob/main/mvp_chicago_crimes_ml.ipynb)

1. Clique no badge acima ou no badge **Open in Colab** no topo do notebook
2. No Colab, vá em **Runtime → Run all**
3. O notebook carrega automaticamente a amostra do repositório — sem necessidade de download externo

---

## Modelos Avaliados

| Modelo | Tipo |
|---|---|
| DummyClassifier (most_frequent) | Baseline |
| Regressão Logística | Candidato |
| Random Forest | Candidato |
| Gradient Boosting | Candidato |

---

## Disciplina Anterior

O MVP de Análise de Dados e Boas Práticas está disponível em:  
[mvp-puc-rio-analise-de-dados](https://github.com/leonardorochaperazzini/mvp-puc-rio-analise-de-dados)
