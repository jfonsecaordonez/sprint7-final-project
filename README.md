# Proyecto: Análisis de una empresa de telecomunicaciones – ConnectaTel

# Objetivo del proyecto

Analizar el comportamiento de los clientes de ConnectaTel, empresa de telecomunicaciones con operaciones en México y Colombia, a partir de sus características demográficas y patrones de consumo de llamadas y mensajes.

El objetivo es identificar tendencias de uso, detectar valores atípicos y comprender las diferencias entre segmentos de clientes, con el fin de generar insights y recomendaciones que contribuyan a optimizar la oferta comercial y mejorar la experiencia del usuario.

# Datasets utilizados

El análisis utiliza tres fuentes de información:

plans.csv: contiene información de los planes comerciales, incluyendo precios, minutos y datos incluidos, y costos por consumo adicional.

users_latam.csv: contiene información de los clientes, como edad, ciudad, fecha de registro, plan contratado y fecha de cancelación del servicio (churn).

usage.csv: registra la actividad de los usuarios, incluyendo llamadas, duración y mensajes.

# Herramientas utilizadas

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

Google Colab

# Etapas del análisis

El proyecto se desarrolló siguiendo las siguientes etapas:

- Exploración inicial: revisión de la estructura, dimensiones, tipos de datos y características generales de los tres datasets.

- Evaluación de calidad: identificación de valores nulos, sentinels, duplicados, inconsistencias y fechas fuera de rango.

- Limpieza y preparación: tratamiento de valores faltantes, corrección de tipos de datos y validación de la información.

- Análisis estadístico: cálculo de estadísticas descriptivas para comprender la distribución y el comportamiento de las variables.

- Visualización y detección de outliers: elaboración de histogramas y boxplots para identificar distribuciones, sesgos y valores atípicos mediante el método IQR.

- Integración y segmentación: consolidación de la información de clientes y consumo, y clasificación de usuarios según características demográficas y niveles de uso.

- Análisis de resultados: interpretación de patrones de consumo y diferencias entre segmentos para identificar oportunidades comerciales.

- Conclusiones y recomendaciones: elaboración de insights orientados a la optimización de los planes y la experiencia del cliente.

# Cómo ejecutar el proyecto

El análisis está desarrollado en un notebook de Jupyter (.ipynb).

Para ejecutarlo en Google Colab:

1. Descarga este repositorio.

2. Ingresa a Google Colab.

3. Selecciona Archivo → Subir notebook.

4. Carga el notebook del proyecto.

5. Descarga y carga los tres archivos CSV en el entorno de trabajo.

6. Verifica las rutas de acceso a los datasets.

7. Ejecuta las celdas en orden, desde el inicio hasta el final.

# Guía de reproducción

Para reproducir el análisis y obtener los resultados:

Utilizar los datasets originales: plans.csv, users_latam.csv y usage.csv.

Instalar las librerías necesarias si el entorno no las tiene disponibles.

Mantener las estructuras y nombres de las columnas originales.

Ejecutar las celdas secuencialmente para garantizar que las transformaciones y variables se generen correctamente.

Revisar que las rutas de los archivos coincidan con su ubicación en el entorno de ejecución.

Las tablas, estadísticas y visualizaciones se generan durante la ejecución del notebook.



Proyecto: Proyecto 6 – ConnectaTel
Área: Análisis de datos
Herramientas principales: Python, Pandas, NumPy y Seaborn.
