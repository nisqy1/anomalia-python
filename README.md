# 🚨 Detecção de Anomalias em Transações em Python

Projeto de Machine Learning desenvolvido para detectar transações financeiras fraudulentas utilizando técnicas de classificação, balanceamento de dados e explicabilidade de modelos.

---

## 📌 Objetivo

O objetivo deste projeto é identificar anomalias em transações financeiras, diferenciando operações legítimas de possíveis fraudes.

O notebook aborda todo o pipeline de Data Science:

- Pré-processamento de dados
- Balanceamento de classes
- Treinamento de modelos
- Avaliação de desempenho
- Explicabilidade com SHAP

---

# 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Imbalanced-learn (SMOTE)
- XGBoost
- SHAP

---

# 📂 Dataset

O conjunto de dados contém registros de transações financeiras com:

- Variáveis anonimizadas
- Valor da transação (`Amount`)
- Classe alvo (`Class`)

### Classes:

| Classe | Descrição |
|---|---|
| 0 | Transação normal |
| 1 | Fraude |

---

# 📊 Etapas do Projeto

## 🔹 1. Carregamento dos Dados

Importação e análise inicial do dataset.

## 🔹 2. Análise Exploratória

- Distribuição das classes
- Identificação de desbalanceamento
- Visualizações estatísticas

## 🔹 3. Pré-processamento

- Padronização
- Engenharia de atributos
- Tratamento de dados

## 🔹 4. Balanceamento dos Dados

Aplicação de técnicas como:

- SMOTE
- UnderSampling

## 🔹 5. Treinamento dos Modelos

Modelos utilizados:

- Logistic Regression
- Random Forest
- XGBoost

## 🔹 6. Avaliação

Métricas utilizadas:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC AUC

## 🔹 7. Explicabilidade

Uso da biblioteca SHAP para interpretação das previsões do modelo.

---

# 📈 Resultados Esperados

- Melhor detecção de fraudes
- Redução de falsos negativos
- Melhor desempenho em dados desbalanceados

---

# ▶️ Como Executar

## 1️⃣ Clone o repositório

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git

## 2️⃣ Instale as dependências

pip install pandas numpy matplotlib scikit-learn imbalanced-learn xgboost shap

## 3️⃣ Execute o notebook

Abra o arquivo .ipynb em:

- Jupyter Notebook
- Google Colab
- VS Code

## 📁 Estrutura do Projeto
📁 projeto/
 ├── Detecção_de_Anomalias_em_Transações_em_Python.ipynb
 └── README.md

```

## 🧠 Conceitos Abordados
- Machine Learning
- Classificação Binária
- Detecção de Fraudes
- Dados Desbalanceados
- Feature Engineering
- Explainable AI (XAI)

## 🚀 Melhorias Futuras
- Deploy do modelo via API
- Dashboard interativo
- Detecção em tempo real
- Otimização de hiperparâmetros
- Implementação com Deep Learning
  
## 👨‍💻 Autor
- Aneliza Barbero Parussulo
- Projeto desenvolvido para estudos em Ciência de Dados e Machine Learning.
