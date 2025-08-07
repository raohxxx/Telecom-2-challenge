# 📉 Telecom X – Predicción de Cancelación de Clientes (Churn)

Este proyecto forma parte de un desafío de análisis predictivo para la empresa ficticia **Telecom X**. Después de realizar un análisis exploratorio exitoso, el objetivo ahora es construir modelos de Machine Learning que permitan predecir qué clientes tienen mayor probabilidad de cancelar sus servicios.

## 🎯 Objetivo del Proyecto

Desarrollar un pipeline de Machine Learning que permita:

- Preprocesar y preparar los datos de clientes.
- Seleccionar las variables más relevantes.
- Entrenar y comparar distintos modelos de clasificación.
- Evaluar el rendimiento de los modelos.
- Interpretar los resultados para ofrecer insights accionables al negocio.

## 🧰 Tecnologías y Herramientas

- Python 3.x
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- XGBoost / LightGBM (opcional)
- SHAP (para interpretabilidad)
- Jupyter Notebook / Google Colab

## 🛠️ Estructura del Repositorio

```
📁 telecom-x-churn-prediction/
├── data/
│   └── telecom_x_data.csv
├── notebooks/
│   ├── 01_exploracion_datos.ipynb
│   ├── 02_preprocesamiento.ipynb
│   ├── 03_modelado.ipynb
│   └── 04_evaluacion_resultados.ipynb
├── src/
│   └── utils.py
├── outputs/
│   ├── modelos_guardados/
│   └── visualizaciones/
├── README.md
└── requirements.txt
```

## 🔍 Fases del Proyecto

### 1. Exploración de Datos
- Análisis univariado y multivariado
- Visualización de distribución de clases (`Churn`)
- Detección de valores atípicos y datos faltantes

### 2. Preprocesamiento
- Codificación de variables categóricas
- Imputación de datos faltantes
- Normalización de variables numéricas
- Separación de datos en entrenamiento y prueba

### 3. Modelado
- Entrenamiento de múltiples clasificadores:
  - Regresión Logística
  - Random Forest
  - XGBoost
- Búsqueda de hiperparámetros (GridSearchCV)

### 4. Evaluación
- Métricas: Accuracy, Precision, Recall, F1-score, AUC
- Matriz de confusión
- Curva ROC
- Importancia de variables (SHAP y modelos de árbol)

### 5. Conclusiones y Recomendaciones
- Identificación de factores clave en la cancelación
- Propuesta de acciones para mejorar la retención

## 📌 Resultados Destacados

- **Mejor modelo**: Random Forest con AUC = 0.89
- **Principales variables** que predicen el churn:
  - Tiempo como cliente
  - Tipo de contrato
  - Uso de servicios adicionales
  - Quejas registradas

## 🤖 Próximos pasos

- Implementar modelo en entorno productivo
- Automatizar el pipeline completo
- Crear dashboard interactivo para el equipo comercial

## 📄 Licencia

Este proyecto es parte de un desafío de aprendizaje y no contiene datos reales. Uso libre con fines educativos.
