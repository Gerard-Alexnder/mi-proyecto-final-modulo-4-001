# Proyecto Final - Predicción del Abandono de Clientes (Customer Churn)

## Nombre: Gerard Almanzar
## Descripción del proyecto

Este proyecto tiene como objetivo preparar un conjunto de datos de clientes de una empresa de telecomunicaciones para un futuro modelo de Machine Learning capaz de predecir el abandono de clientes (Customer Churn). Se aplicaron técnicas de limpieza, transformación y análisis exploratorio para identificar patrones que ayuden a la empresa a tomar mejores decisiones de retención.

---

## Dataset utilizado

Se utilizó el dataset **Telco Customer Churn** descargado desde Kaggle.com

---

## Pasos realizados

Durante el desarrollo del proyecto se siguió el siguiente flujo de trabajo:

1. Exploración y diagnóstico inicial del dataset.
2. Limpieza de datos.
   - Tratamiento de valores nulos.
   - Conversión de tipos de datos.
   - Eliminación de registros incompletos.
   - Verificación de registros duplicados.
3. Feature Engineering.
   - Creación de la variable **TenureGroup**.
   - Creación de la variable **TotalServices**.
4. Análisis Exploratorio de Datos (EDA).
5. Preparación para Machine Learning.
   - Separación de variables X e y.
   - Train/Test Split.
   - One-Hot Encoding.
   - Escalado de variables numéricas mediante StandardScaler.

---

## Hallazgos principales

Durante el análisis exploratorio se identificaron varios patrones importantes:

- Los clientes con contratos mensuales presentan una mayor tasa de abandono.
- Los clientes con menor antigüedad tienden a abandonar con mayor frecuencia.
- Los clientes con una mayor cantidad de servicios contratados muestran una menor tendencia a abandonar la empresa.
- Algunas variables relacionadas con el contrato y la antigüedad presentan una relación importante con la variable **Churn**.

---

## Decisión de negocio

La empresa podría utilizar un modelo de Machine Learning basado en este dataset para identificar clientes con alta probabilidad de abandonar el servicio antes de que ocurra. Esto permitiría implementar campañas de fidelización, promociones personalizadas o mejoras en el servicio enfocadas en los clientes con mayor riesgo, reduciendo así la pérdida de clientes y aumentando los ingresos.
