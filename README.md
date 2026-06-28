# Tech Challenge - Predição de Risco de Ataque Cardíaco

## 📖 Sobre o projeto

Este projeto foi desenvolvido como parte do Tech Challenge da pós-graduação em Machine Learning da FIAP.

O objetivo é construir um modelo de classificação capaz de prever o risco de ataque cardíaco a partir de características clínicas e hábitos de vida dos pacientes.

Durante o desenvolvimento foram realizadas as etapas de análise exploratória dos dados, pré-processamento, engenharia de atributos, treinamento de diferentes algoritmos de Machine Learning e comparação dos resultados.

---

## 🛠 Tecnologias utilizadas

* Python 3
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📊 Fluxo do projeto

* Análise exploratória dos dados
* Tratamento das variáveis categóricas
* Engenharia de atributos
* Preparação dos dados
* Divisão entre treino e teste utilizando
* Treinamento dos modelos
* Comparação das métricas
* Escolha do modelo final
* Avaliação através da matriz de confusão

---

## 🤖 Modelos avaliados

* Logistic Regression
* Decision Tree
* Random Forest
* K-Nearest Neighbors
* Support Vector Machine (SVM)
* Gradient Boosting

---

## 📈 Métrica de avaliação

Embora a acurácia tenha sido analisada, a métrica principal utilizada foi o **Recall**, pois o objetivo é minimizar a quantidade de pacientes em risco classificados incorretamente como saudáveis (Falsos Negativos).

---

## 📁 Estrutura do projeto

```text
.
├── heart_attack_prediction.ipynb
├── heart_attack_prediction_dataset.csv
├── README.md
└── requirements.txt
```

---

## 🚀 Como executar

```bash
git clone https://github.com/AndreVicenteW/fiap_tech_challenge_1

cd fiap_tech_challenge_1

pip install -r requirements.txt

jupyter notebook
```

Abra o notebook `heart_attack_prediction.ipynb` e execute as células em sequência.

---

## 👨‍💻 Autor

André Vicente
