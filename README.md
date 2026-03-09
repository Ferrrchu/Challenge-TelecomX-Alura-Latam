# Challenge Telecom X - Análisis de Evasión de Clientes (Churn)

## Descripción del proyecto

Este proyecto tiene como objetivo analizar la evasión de clientes (**Churn**) en Telecom X, identificando patrones y factores que pueden estar relacionados con la cancelación del servicio.

A través de un proceso de limpieza, tratamiento y análisis exploratorio de datos, se busca comprender el comportamiento de los clientes y generar insights que ayuden a la empresa a tomar decisiones estratégicas para mejorar la retención.

## Objetivo

El objetivo principal es explorar los datos de clientes de Telecom X para responder preguntas como:

- ¿Qué proporción de clientes cancela el servicio?
- ¿Qué variables categóricas están más asociadas al churn?
- ¿Qué variables numéricas muestran diferencias entre clientes que cancelan y los que permanecen?
- ¿Qué acciones podrían ayudar a reducir la evasión?

## Dataset

Los datos utilizados provienen de una API en formato JSON:

```python
https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/refs/heads/main/TelecomX_Data.json
```

## Estructura del análisis

El notebook incluye las siguientes etapas:

1. Importación de datos
  - Carga de datos desde la API y normalización del JSON.
2. Limpieza y tratamiento de datos
  - Renombrado de columnas
  - Conversión de tipos de datos
  - Tratamiento de valores nulos
  - Estandarización de variables categóricas
3. Análisis exploratorio de datos (EDA)
  - Distribución de la variable churn
  - Análisis de variables categóricas
  - Análisis de variables numéricas
  - Visualización de patrones relevantes
4. Conclusiones e insights
  - Resumen de hallazgos y observaciones principales.
5. Recomendaciones
  - Sugerencias estratégicas basadas en el análisis realizado.

## Cómo ejecutar el proyecto
1. Clonar o descargar el proyecto.
2. Instalar las dependencias.
3. Abrir el notebook en Jupyter.
4. Ejecutar todas las celdas en orden.
