# Predição de Preços de Imóveis - Kaggle Competition

Este repositório contém um projeto desenvolvido para a competição **"House Prices: Advanced Regression Techniques"** do [Kaggle](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques). O objetivo é prever o preço final de casas usando técnicas de aprendizado de máquina e análise de dados.

---

## Objetivo do Projeto
O projeto visa:
- Aplicar técnicas de aprendizado de máquina para resolver um problema de regressão.
- Utilizar ferramentas de análise exploratória de dados (EDA) para entender o conjunto de dados.
- Construir um modelo preditivo eficiente para estimar o preço de imóveis com base em diferentes variáveis.

---

## Estrutura do Repositório

- **`notebooks/`**: Contém os notebooks utilizados no projeto, organizados por etapa do desenvolvimento.
- **`data/`**: Diretório para armazenamento de dados brutos e processados (não incluídos por questões de política do Kaggle).
- **`models/`**: Contém os modelos treinados para predições.
- **`README.md`**: Este arquivo, com a descrição geral do projeto.

---

## Tecnologias Utilizadas

- **Linguagem**: Python
- **Bibliotecas principais**:
  - `pandas` e `numpy` para manipulação e análise de dados.
  - `matplotlib` e `seaborn` para visualizações.
  - `scikit-learn` para criação e avaliação de modelos de aprendizado de máquina.

---

## Etapas do Projeto

1. **Análise Exploratória de Dados (EDA):**
   - Exploração do conjunto de dados.
   - Identificação de valores ausentes e outliers.
   - Criação de visualizações para identificar padrões.

2. **Processamento de Dados:**
   - Tratamento de valores ausentes.
   - Codificação de variáveis categóricas.
   - Normalização e padronização de variáveis.

3. **Construção do Modelo:**
   - Modelos testados: Regressão Linear, Árvore de Decisão, Random Forest, XGBoost e KNN.
   - Validação usando cross-validation.

4. **Avaliação do Modelo:**
   - Métrica utilizada: Root Mean Squared Error (RMSE).
   - Comparativo de desempenho entre os modelos.

5. **Predições:**
   - Geração do arquivo final para submissão no Kaggle.

---

