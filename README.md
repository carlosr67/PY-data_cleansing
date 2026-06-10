🐍 Análisis Exploratorio y Limpieza de Datos con Python
Descripción del Proyecto

Este proyecto fue desarrollado en Google Colab utilizando Python con el objetivo de realizar un proceso completo de análisis exploratorio de datos (EDA - Exploratory Data Analysis) y limpieza de información.

A partir de un conjunto de datos de ventas, se aplicaron diferentes técnicas para identificar registros inconsistentes, valores nulos, tipos de datos incorrectos y posibles anomalías que pudieran afectar la calidad del análisis.

Posteriormente, los datos fueron transformados y preparados para generar visualizaciones que permitieran comprender mejor el comportamiento de las ventas, la distribución geográfica de los registros y las relaciones entre variables.

 Objetivos del Proyecto
Comprender la estructura general del dataset.
Identificar problemas de calidad en los datos.
Detectar valores nulos o faltantes.
Validar tipos de datos.
Estandarizar y preparar la información para el análisis.
Generar visualizaciones para extraer insights relevantes.
Analizar correlaciones entre variables numéricas.

 Proceso de Análisis
1. Carga y Exploración Inicial

Se realizó una revisión general del conjunto de datos para comprender su estructura:

Dimensiones del dataset.
Número de registros.
Número de columnas.
Visualización de registros iniciales.
Descripción general de variables.

2. Validación de Calidad de Datos

Durante esta etapa se identificaron:

Valores nulos.
Registros duplicados.
Tipos de datos incorrectos.
Valores atípicos.
Inconsistencias en campos categóricos.

3. Limpieza y Transformación

Las actividades realizadas incluyeron:

Eliminación de duplicados.
Tratamiento de datos faltantes.
Conversión de tipos de datos.
Normalización de valores categóricos.
Preparación de variables para análisis posteriores.

4. Análisis Exploratorio de Datos (EDA)

Se analizaron diferentes características del dataset mediante estadísticas descriptivas:

Promedio de ventas.
Ventas máximas.
Ventas mínimas.
Mediana.
Distribución de registros.
Comportamiento de variables numéricas.
 Visualizaciones Generadas

El proyecto incluye diferentes gráficos desarrollados con Python para facilitar la interpretación de los datos:

Distribución de Ventas
Histogramas.
Gráficos de densidad.
Distribución por rangos de ventas.
Análisis por Ubicación
Ventas por ciudad.
Ventas por región.
Comparación entre ubicaciones.
Análisis Comparativo
Gráficos de barras.
Gráficos de columnas.
Ranking de categorías.
Correlación de Variables

Se generó una matriz de correlación para identificar relaciones entre variables numéricas y comprender qué factores podrían influir en el comportamiento de las ventas.

Tecnologías Utilizadas
Python
Google Colab
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
 Librerías Principales
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

Análisis Realizados
Información General del Dataset
Número total de registros.
Número total de columnas.
Tipos de datos.
Estadísticas descriptivas.
Calidad de Datos
Conteo de valores nulos.
Porcentaje de datos faltantes.
Detección de duplicados.
Validación de consistencia.
Estadísticas Descriptivas
Promedio de ventas.
Venta mínima.
Venta máxima.
Desviación estándar.
Cuartiles.
Correlaciones
Relación entre variables numéricas.
Identificación de patrones.
Posibles dependencias entre métricas.

📂 Estructura del Proyecto
📁 Python-Data-Cleaning-EDA
│
├── 📄 Data_Cleaning_EDA.ipynb
├── 📁 Data
│   └── ventas_dataset.csv
├── 📁 Images
│   ├── sales_distribution.png
│   ├── sales_by_location.png
│   └── correlation_matrix.png
├── requirements.txt
└── README.md
 Resultados Obtenidos

A través de este proyecto se logró:

Mejorar la calidad de los datos.
Identificar registros inconsistentes.
Detectar información faltante.
Comprender el comportamiento general de las ventas.
Encontrar patrones mediante análisis visual.
Analizar relaciones entre variables utilizando correlaciones.
Generar información útil para la toma de decisiones basada en datos.

 Habilidades Demostradas
Data Cleaning.
Data Wrangling.
Exploratory Data Analysis (EDA).
Data Visualization.
Statistical Analysis.
Data Quality Assessment.
Python Programming.
Business Analytics.


Carlos restrepo Vanegas

Ingeniero de Sistemas | Analista de Datos

Stack Tecnológico
Python
Pandas
NumPy
Matplotlib
Seaborn
SQL
Power BI
Excel
Data Analytics
Business Intelligence
