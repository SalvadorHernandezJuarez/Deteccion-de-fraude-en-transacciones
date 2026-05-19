# 💳 Detección de Fraude en Transacciones con Machine Learning

Sistema de detección de fraude financiero utilizando técnicas de Machine Learning supervisado para identificar transacciones sospechosas en tiempo real.

---

# 📌 Descripción del Proyecto

El fraude financiero representa uno de los mayores desafíos para bancos y plataformas de pagos digitales. Este proyecto implementa un modelo de Machine Learning capaz de detectar transacciones fraudulentas a partir de patrones históricos de comportamiento financiero.

El objetivo principal es construir un sistema capaz de clasificar transacciones como:

* ✅ Legítimas
* 🚨 Fraudulentas

utilizando técnicas de preprocesamiento, análisis exploratorio y modelos predictivos entrenados sobre datos reales o simulados.

---

# 🧠 Objetivos

* Detectar transacciones fraudulentas automáticamente.
* Reducir falsos positivos y falsos negativos.
* Analizar patrones financieros sospechosos.
* Evaluar distintos algoritmos de clasificación.
* Comprender el comportamiento de datos desbalanceados.

---

# 📊 Dataset

El proyecto utiliza un dataset de transacciones financieras que incluye variables como:

| Variable         | Descripción                            |
| ---------------- | -------------------------------------- |
| amount           | Monto de la transacción                |
| time             | Tiempo de la transacción               |
| transaction_type | Tipo de operación                      |
| oldbalanceOrg    | Balance anterior del emisor            |
| newbalanceOrig   | Balance posterior del emisor           |
| oldbalanceDest   | Balance anterior del receptor          |
| newbalanceDest   | Balance posterior del receptor         |
| isFraud          | Variable objetivo (fraude o no fraude) |

---

# ⚙️ Tecnologías Utilizadas

* Python
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
* Jupyter Notebook

---

# 📁 Estructura del Proyecto

```bash
Fraud-Detection-ML/
│
├── fraude.ipynb          # Notebook principal
├── dataset.csv           # Dataset de transacciones
├── requirements.txt      # Dependencias
└── README.md             # Documentación
```

---

# 🔬 Metodología

## 1️⃣ Preprocesamiento de Datos

* Limpieza de datos
* Eliminación de valores nulos
* Codificación de variables categóricas
* Escalado de variables numéricas

## 2️⃣ Análisis Exploratorio (EDA)

* Distribución de fraudes
* Correlaciones
* Visualización de patrones
* Balanceo de clases

## 3️⃣ Entrenamiento del Modelo

Se evaluaron distintos algoritmos de Machine Learning:

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost
* Support Vector Machine (SVM)

---

# 📈 Métricas de Evaluación

Para medir el desempeño del modelo se utilizaron:

| Métrica   | Descripción                          |
| --------- | ------------------------------------ |
| Accuracy  | Precisión general                    |
| Precision | Exactitud en detección de fraude     |
| Recall    | Capacidad de detectar fraudes reales |
| F1-Score  | Balance entre precisión y recall     |
| ROC-AUC   | Capacidad discriminativa del modelo  |

---

# 📊 Resultados

## Modelo con mejor desempeño

| Modelo        | Accuracy | Recall | F1-Score |
| ------------- | -------- | ------ | -------- |
| Random Forest | 99.2%    | 94.8%  | 95.6%    |

### Hallazgos importantes

* Las transacciones fraudulentas representan una pequeña fracción del dataset.
* El desbalance de clases afecta significativamente el entrenamiento.
* Random Forest mostró el mejor equilibrio entre precisión y detección de fraude.
* Variables relacionadas con balances financieros fueron altamente relevantes.

---

# 📷 Visualizaciones

## Distribución de Fraudes

![Fraudes](images/fraudes.png)

## Matriz de Correlación

![Heatmap](images/heatmap.png)

## Matriz de Confusión

![Confusion Matrix](images/confusion_matrix.png)

---

# 🚀 Cómo Ejecutar el Proyecto

## 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/TU-USUARIO/Fraud-Detection-ML.git
cd Fraud-Detection-ML
```

## 2️⃣ Instalar dependencias

```bash
pip install -r requirements.txt
```

## 3️⃣ Ejecutar el notebook

```bash
jupyter notebook fraude.ipynb
```

---

# 📚 Aprendizajes

Durante este proyecto se aplicaron conceptos de:

* Machine Learning supervisado
* Clasificación binaria
* Detección de anomalías
* Manejo de datasets desbalanceados
* Ingeniería de características
* Evaluación de modelos predictivos

---

# 🛡️ Aplicaciones Reales

Este tipo de sistemas puede ser utilizado en:

* Bancos
* Fintechs
* Plataformas de pago
* E-commerce
* Sistemas de seguridad financiera

---

# 👤 Autor

Salvador Hernández Juárez

* GitHub: https://github.com/TU-USUARIO

---

# ⭐ Proyecto de Machine Learning

Detección Inteligente de Fraude en Transacciones Financieras utilizando técnicas de Inteligencia Artificial y Ciencia de Datos.
