# Modelo_Machine_Learning_Supervisionado_Agronegocio

# Conclusão do Projeto

Este projeto teve como objetivo prever a produtividade agrícola (Yield per Hectare) utilizando técnicas de Machine Learning supervisionado com o algoritmo de Árvore de Decisão (Decision Tree Regressor). A solução foi desenvolvida a partir da base de dados Smart Farming Crop Yield 2024, contemplando todas as etapas do ciclo de um projeto de Ciência de Dados.

Durante o desenvolvimento, foram realizadas atividades de tratamento e preparação dos dados, conversão de datas, criação de atributos derivados, análise exploratória, identificação de correlações e construção de pipelines para processamento de variáveis numéricas e categóricas. Em seguida, foi realizado o treinamento, teste e avaliação do modelo por meio de métricas como MAE, RMSE e R².

Os resultados demonstraram que a Árvore de Decisão é capaz de identificar padrões relevantes entre fatores ambientais, características do cultivo e produtividade agrícola, fornecendo previsões úteis para apoiar a tomada de decisão no agronegócio. Além disso, a análise de importância das variáveis permitiu compreender quais fatores exercem maior influência sobre a produtividade das culturas.

Este projeto evidencia como a aplicação de técnicas de Data Science e Machine Learning pode transformar dados agrícolas em informações estratégicas, contribuindo para uma agricultura mais eficiente, sustentável e orientada por dados.

## Bibliotecas Utilizadas

* **Pandas** – Manipulação e tratamento de dados.
* **NumPy** – Operações matemáticas e computação numérica.
* **Matplotlib** – Criação de gráficos e visualizações.
* **Seaborn** – Visualização estatística e análise exploratória.
* **Scikit-Learn** – Construção do pipeline de Machine Learning, pré-processamento, treinamento e avaliação do modelo.

  * DecisionTreeRegressor
  * Pipeline
  * ColumnTransformer
  * SimpleImputer
  * OneHotEncoder
  * train_test_split
  * mean_absolute_error
  * mean_squared_error
  * r2_score

## Tecnologias

* Python 3.x
* Jupyter Notebook
* Machine Learning Supervisionado
* Decision Tree Regression
* Data Analysis & Data Visualization

## Estrutura do Projeto

```text
Projeto/
│
├── Smart_Farming_Crop_Yield_2024.csv
├── Modelo.ipynb
├── README.md
│
└── Resultados
    ├── Análise Exploratória
    ├── Correlação
    ├── Avaliação do Modelo
    └── Importância das Variáveis
```

Este projeto demonstra a aplicação prática de Ciência de Dados para previsão de produtividade agrícola, combinando análise exploratória, engenharia de atributos e modelagem preditiva em um fluxo completo de Machine Learning.
