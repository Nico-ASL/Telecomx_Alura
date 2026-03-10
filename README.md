# Telecomx_Alura
Telecom X - Análisis de Evasión de Clientes (Churn)
Descripción del Proyecto

Este proyecto tiene como objetivo analizar la evasión de clientes (Churn) en Telecom X utilizando técnicas de análisis de datos en Python. A través de la limpieza, transformación y exploración de los datos, se busca identificar patrones y factores que influyen en la cancelación del servicio.

El análisis realizado permite generar información relevante que puede apoyar estrategias de retención de clientes y servir como base para futuros modelos predictivos.

Objetivos del Análisis

Importar y procesar datos desde una API en formato JSON.

Realizar limpieza y tratamiento de los datos.

Aplicar análisis exploratorio de datos (EDA).

Identificar factores asociados a la evasión de clientes.

Generar insights que apoyen la toma de decisiones.

Fuente de Datos

Los datos utilizados en este proyecto provienen del siguiente repositorio:

https://github.com/ingridcristh/challenge2-data-science-LATAM

Archivo utilizado:

TelecomX_Data.json

Tecnologías Utilizadas

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook / Google Colab

Proceso de Análisis
1. Extracción de Datos

Los datos fueron obtenidos desde una API pública en formato JSON y cargados en Python utilizando la biblioteca Pandas.

2. Limpieza y Preparación de Datos

Durante esta etapa se realizaron las siguientes acciones:

Normalización de la estructura del archivo JSON.

Conversión de variables a tipos de datos adecuados.

Identificación y tratamiento de valores nulos.

Eliminación de registros duplicados.

Creación de la variable Cuentas_Diarias a partir del cargo mensual.

3. Análisis Exploratorio de Datos

Se realizaron estadísticas descriptivas y visualizaciones para comprender el comportamiento de los clientes y detectar patrones asociados al churn.

Se analizaron variables categóricas y numéricas como:

Género

Tipo de contrato

Método de pago

Servicio de internet

Antigüedad del cliente

Cargos mensuales y totales

4. Principales Hallazgos

El análisis permitió identificar algunos factores relevantes asociados a la evasión de clientes:

Los clientes con contratos mensuales presentan mayor tasa de churn.

Los clientes con menor antigüedad tienen mayor probabilidad de cancelar el servicio.

Los cargos mensuales más altos se asocian a una mayor tendencia de cancelación.

Los clientes que cancelan acumulan menor gasto total debido a su menor permanencia.

5. Recomendaciones

A partir del análisis realizado, se proponen las siguientes acciones:

Implementar estrategias de retención durante los primeros meses del cliente.

Incentivar contratos de mayor duración.

Analizar el impacto de los cargos mensuales en la satisfacción del cliente.

Utilizar estos datos para desarrollar modelos predictivos de churn.

Estructura del Proyecto
TelecomX-Churn-Analysis
│
├── TelecomX_Data.json
├── TelecomX_Churn_Analysis.ipynb
└── README.md
Conclusión

El análisis permitió identificar patrones importantes en el comportamiento de los clientes que cancelan el servicio. Estos hallazgos pueden ayudar a Telecom X a comprender mejor los factores que influyen en la evasión y a diseñar estrategias más efectivas para mejorar la retención de clientes.
