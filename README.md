
<img width="225" height="225" alt="image" src="https://github.com/user-attachments/assets/8adf4027-86f5-4908-b7d3-9bfe580538a0" />

#  Modelo de Clasificación con PySpark  :)
## Predicción de Compra de Depósitos Bancarios

<p align="center">
  <img src="https://img.shields.io/badge/PySpark-Big%20Data-orange?style=for-the-badge&logo=apachespark" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Clasificación-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Dataset-UCI%20Bank%20Marketing-green?style=for-the-badge" />
</p>

---

# ✨ Descripción del Proyecto

Este proyecto desarrolla un **pipeline completo de Machine Learning con PySpark** para predecir si un cliente contratará o no un depósito bancario a término.

El cuaderno incluye:

- 📥 Carga y procesamiento de datos
- 🔍 Exploración y análisis estadístico
- 📈 Visualización de variables
- 🧹 Limpieza y transformación de datos
- ⚖️ Balanceo de clases
- 🤖 Entrenamiento de modelos de clasificación
- 📊 Evaluación comparativa de rendimiento

Todo el flujo fue desarrollado utilizando herramientas de **Big Data y Machine Learning distribuido**.

---

# 🧠 Objetivo del Modelo

Predecir si un cliente realizará una suscripción a un depósito bancario utilizando variables demográficas, financieras y de interacción con campañas de marketing.

La variable objetivo es:

| Variable | Descripción |
|---|---|
| `y` | Indica si el cliente compró (`yes`) o no (`no`) el depósito |

---

# 🗂️ Dataset Utilizado

## 📊 Bank Marketing Dataset (UCI)

Dataset clásico de campañas de marketing bancario utilizado para problemas de clasificación supervisada.

### Variables importantes

- Edad
- Trabajo
- Estado civil
- Nivel educativo
- Balance bancario
- Tipo de contacto
- Duración de llamada
- Número de contactos previos
- Resultado de campañas anteriores

---

# ⚙️ Tecnologías Utilizadas

| Herramienta | Uso |
|---|---|
| 🟠 PySpark | Procesamiento distribuido |
| 🐍 Python | Desarrollo general |
| 📊 Matplotlib / Seaborn | Visualización |
| 🧮 Scikit-learn | Métricas y apoyo ML |
| 📁 Pandas / NumPy | Manipulación de datos |

---

# 🔍 Exploración de Datos

Durante el análisis exploratorio se realizaron:

- Distribución de variables numéricas
- Distribución de variables categóricas
- Matriz de correlación
- Análisis respecto a la variable objetivo
- Identificación de sesgos
- Verificación de valores nulos

---

# 🧹 Procesamiento y Calidad de Datos

Se aplicaron distintas estrategias de preparación:

## ✔️ Transformaciones realizadas

- Conversión de variables categóricas
- Eliminación de variables sesgadas
- Balanceo de clases
- Limpieza de datos inconsistentes
- Ingeniería básica de variables

## ⚠️ Variables tratadas especialmente

| Variable | Motivo |
|---|---|
| `duration` | Puede generar fuga de información |
| `pdays` | Alta cantidad de valores atípicos |
| `default` | Sesgo en la distribución |

---

# 🤖 Modelos Implementados

El notebook compara múltiples algoritmos de clasificación:

| Modelo | Descripción |
|---|---|
| Regresión Logística | Modelo lineal probabilístico |
| Decision Tree | Árbol de decisión |
| Random Forest | Ensamble de árboles |
| Gradient Boosted Trees | Boosting secuencial |
| Support Vector Machine | Clasificador por hiperplanos |

---

# 📈 Evaluación de Modelos

Los modelos fueron evaluados utilizando métricas como:

- Accuracy
- ROC Curve
- Área bajo la curva (AUC)
- Comparación de desempeño
- Matriz de confusión

---

# 🚀 Ejecución del Proyecto

## 1️⃣ Clonar repositorio

```bash
git clone <repositorio>
```

## 2️⃣ Instalar dependencias

```bash
pip install pyspark pandas numpy matplotlib seaborn scikit-learn
```

## 3️⃣ Ejecutar Jupyter Notebook

```bash
jupyter notebook
```

---

# 📚 Contenido del Notebook

- **Procesamiento de Alto Volumen de Datos**
- Taller: **Modelo de clasificacion - PySpark**
- Importar bibliotecas generales
- Levantamiento de sesión spark
- Lectura de los datos y entendimiento del negocio.
- 📊 Dataset: Bank Marketing (UCI)
- 🧾 Tabla de Variables
- Aspectos a tener en cuenta
- Objetivo del modelo
- Exploracion de datos
- Comentarios (numericas)
- Matriz de correlación.
- Distribución de las variables categóricas
- Comentarios (discretas)
- Variables numéricas respecto a la variable objetivo
- A tener en cuenta: Factores y desiciones de calidad de datos
- Modelos de aprendizaje de máquina



---

# 📌 Resultados Esperados

El proyecto permite:

✅ Comprender un flujo completo de Machine Learning distribuido  
✅ Aplicar clasificación supervisada con PySpark  
✅ Comparar múltiples modelos predictivos  
✅ Trabajar con datasets reales de marketing bancario  
✅ Evaluar desempeño mediante métricas robustas  

---

# 👨‍💻 Autor

Se usan técnicas de:

- Big Data
- Data Science
- Machine Learning
- Clasificación Supervisada
- Procesamiento distribuido con Spark

---

# ⭐ Recomendaciones

- Asegurese de usar el notebook en entorno con Apache Spark configurado
- Probar ajuste de hiperparámetros para optimización

---

<p align="center">
  <b>📊 Machine Learning + Big Data + PySpark 🚀</b>
</p>
