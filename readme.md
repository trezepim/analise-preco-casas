# Projeto: Decifrando o que faz uma casa valer mais em Ames

Projeto desenvolvido para a disciplina de **Análise de dados aplicada a computação**, com o objetivo de aplicar técnicas de análise de dados e aprendizado de máquina utilizando um conjunto de dados real do mercado imobiliário.

## 📖 Sobre o Projeto

O mercado imobiliário apresenta grandes variações de preço entre imóveis aparentemente semelhantes. Neste projeto, buscamos responder à seguinte pergunta:

> Existe uma lógica por trás dos preços das casas em Ames, Iowa, ou eles dependem apenas de negociação e fatores subjetivos?

Para responder a essa questão, foram aplicadas técnicas de análise exploratória de dados, engenharia de atributos, aprendizado supervisionado e aprendizado não supervisionado, permitindo identificar os fatores mais relevantes para a formação dos preços dos imóveis.

---

## 🎯 Objetivos

* Analisar os fatores que influenciam o preço das residências.
* Identificar padrões e correlações presentes nos dados.
* Construir modelos capazes de prever preços de imóveis.
* Classificar imóveis em categorias de alto e baixo valor.
* Descobrir agrupamentos naturais entre os imóveis.
* Detectar padrões ocultos, associações e possíveis outliers.
* Comparar diferentes abordagens de Machine Learning.

---

## 📊 Dataset Utilizado

Foi utilizado o dataset **House Prices: Advanced Regression Techniques**, disponibilizado pelo Kaggle.

### Fonte

https://www.kaggle.com/c/house-prices-advanced-regression-techniques

### Arquivos utilizados

| Arquivo               | Descrição                                                                                       |
| --------------------- | ----------------------------------------------------------------------------------------------- |
| train.csv             | Conjunto de treinamento contendo as características dos imóveis e o valor de venda (SalePrice). |
| test.csv              | Conjunto de teste contendo as características dos imóveis sem a variável alvo.                  |
| sample_submission.csv | Arquivo de exemplo disponibilizado pela competição.                                             |

### Informações gerais

* 1460 registros para treinamento.
* 79 variáveis explicativas.
* Variável alvo: **SalePrice**.
* Dados referentes a imóveis da cidade de Ames, Iowa (EUA).

---

## 🛠️ Técnicas Aplicadas

### Análise Exploratória de Dados (EDA)

* Estatísticas descritivas
* Distribuição dos preços
* Identificação de valores ausentes
* Identificação de outliers
* Correlação entre variáveis
* Visualização de dados

### Feature Engineering

* Tratamento de valores faltantes
* Codificação de variáveis categóricas
* Criação de novas características
* Padronização e normalização quando necessário

### Aprendizagem Supervisionada

#### Regressão

* Regressão Linear
* Avaliação utilizando:

  * MAE
  * RMSE
  * R²

#### Classificação

* Árvore de Decisão

* Classificação dos imóveis em:

  * Alto valor
  * Baixo valor

* Avaliação utilizando:

  * Accuracy
  * Precision
  * Recall
  * F1-Score

### Aprendizagem Não Supervisionada

#### Clusterização

* K-Means

#### Redução de Dimensionalidade

* PCA (Principal Component Analysis)

#### Regras de Associação

* Apriori

#### Detecção de Outliers

* Local Outlier Factor (LOF)

---

## 📁 Estrutura do repositório

```text
house-prices/
│
├── data/
│   ├── train.csv
│   ├── test.csv
│   └── sample_submission.csv
│
├── notebooks/
│   └── analise-preco-casas.ipynb
│
├── images/
│   ├── apriori.png
│   ├── coef_regression.png
│   ├── correlations.png
│   ├── decision_tree_eval.png
│   ├── decision_tree_viz.png
│   ├── dist_saleprice.png
│   ├── elbow_method.png
│   ├── grlivarea_scatter.png
│   ├── heatmap_corr.png
│   ├── kmeans_clusters.png
│   ├── lof_outliers.png
│   ├── missing_values.png
│   ├── neighborhood_analysis.png
│   ├── final_dashboard.png
│   ├── insights_dashboard.png
│   ├── pca_2d.png
│   ├── pca_variance.png
│   ├── quality_vs_price.png
│   └── regression_eval.png
│
├── requirements.txt
│
└── README.md
---

## 📚 Bibliotecas utilizadas

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* mlxtend
* jupyter

---

## 👥 Grupo

* Rafael Pim Santos
* Vittor Mariano Loyola
