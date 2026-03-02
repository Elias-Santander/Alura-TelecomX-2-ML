# Alura-TelecomX-2-ML
# 📊 Desafío Telecom X — Predicción de Cancelación de Clientes (Churn Prediction)
Proyecto de **Machine Learning** enfocado en predecir la cancelación de clientes (Churn) para la empresa ficticia **Telecom X**, utilizando técnicas de análisis de datos, preprocesamiento, modelado predictivo e interpretación de resultados para generar insights estratégicos de negocio.
---

## 🎯 Objetivo del Proyecto
Desarrollar modelos predictivos capaces de identificar clientes con alta probabilidad de cancelar sus servicios, permitiendo a la empresa anticiparse mediante estrategias de retención basadas en datos.
---

## 🧠 Problema de Negocio
La cancelación de clientes impacta directamente en los ingresos y crecimiento de una empresa de telecomunicaciones.

El objetivo es responder:
* ¿Qué clientes tienen mayor riesgo de cancelar?
* ¿Qué factores influyen en la cancelación?
* ¿Qué acciones estratégicas pueden reducir el churn?
---

## ⚙️ Tecnologías Utilizadas
* **Python**
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook
---

## 🔄 Pipeline de Machine Learning
El proyecto sigue un flujo completo de ciencia de datos:

### 1️⃣ Preparación de Datos
* Limpieza y estandarización
* Eliminación de identificadores irrelevantes
* Codificación One-Hot Encoding
* Análisis de balance de clases
* Aplicación de técnicas de balanceo (SMOTE)

### 2️⃣ Análisis Exploratorio (EDA)
* Matriz de correlación
* Análisis de variables clave:
  * Tiempo de contrato vs Cancelación
  * Gasto total vs Cancelación
* Visualización de patrones de comportamiento

### 3️⃣ Preprocesamiento
* Normalización para modelos sensibles a escala
* División Train/Test (80/20)

### 4️⃣ Modelado
Se entrenaron múltiples modelos:
* ✅ Regresión Logística
* ✅ Random Forest
---

## 📈 Evaluación de Modelos
Métricas utilizadas:
* Accuracy
* Precision
* Recall
* F1-score
* Matriz de confusión

## 🔍 Variables Más Importantes
Los modelos identificaron como principales factores de cancelación:
* Bajo tiempo de permanencia (Tenure)
* Contratos mensuales
* Bajo gasto acumulado
* Cargos mensuales elevados

Esto indica que el churn ocurre principalmente en etapas tempranas del ciclo del cliente.
---

## 🚀 Resultados
El proyecto demuestra cómo la analítica predictiva permite:
* Anticipar cancelaciones.
* Comprender el comportamiento del cliente.
* Convertir datos en decisiones estratégicas.
---

## ▶️ Cómo Ejecutar el Proyecto
1. Clonar repositorio.
2. Instalar dependencias.
3. Ejecutar el notebook.
---

## 📌 Autor
**Elias Santander**
Software Engineer | Backend Developer | Data Analyst
---

## 📄 Licencia
Este proyecto fue desarrollado con fines educativos.
