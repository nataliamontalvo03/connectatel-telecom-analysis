# ConnectaTel – Análisis de datos de telecomunicaciones

1. Objetivo del proyecto

Analizar el comportamiento de los clientes de ConnectaTel, una empresa de telecomunicaciones, con el propósito de identificar patrones de consumo, segmentar usuarios según su edad y nivel de uso, y generar recomendaciones comerciales que permitan mejorar la oferta de planes y fortalecer la relación con los clientes.

2. Datasets utilizados

El análisis utiliza tres conjuntos de datos:

plans.csv: información sobre los planes de telecomunicaciones disponibles.

users_latam.csv: información de los usuarios, incluyendo edad, ciudad, fecha de registro, plan contratado y fecha de cancelación.

usage.csv: registros de actividad de los usuarios, incluyendo llamadas, mensajes, duración y fechas de uso.

3. Etapas del análisis

El proyecto se desarrolló en las siguientes etapas:

Exploración de datos: revisión de la estructura, dimensiones, tipos de datos y estadísticas descriptivas de los datasets.

Limpieza y preparación: identificación y tratamiento de valores nulos, registros inconsistentes y valores centinela.

Análisis exploratorio: estudio de las variables de edad, mensajes, llamadas y minutos de consumo.

Visualización de datos: elaboración de histogramas y diagramas de caja (boxplots) para identificar distribuciones y valores atípicos.

Análisis de valores atípicos: aplicación del método del rango intercuartílico (IQR) para identificar valores extremos y evaluar su pertinencia.

Segmentación de clientes: clasificación de usuarios por grupos de edad y nivel de uso (bajo, medio y alto).

Análisis ejecutivo: interpretación de los resultados y elaboración de recomendaciones comerciales basadas en los hallazgos.

4. Herramientas utilizadas

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

GitHub

5. Cómo ejecutar el proyecto

El análisis se encuentra documentado en el notebook sprint7-final-project.ipynb.

Para ejecutarlo:

Acceder al repositorio de GitHub.

Abrir el archivo sprint7-final-project.ipynb.

Seleccionar la opción para abrirlo en Google Colab o descargarlo y cargarlo directamente en Colab.

Asegurarse de contar con los tres archivos CSV (plans.csv, users_latam.csv y usage.csv).

Cargar los datasets en el entorno de ejecución y verificar que las rutas de lectura coincidan con su ubicación.

Ejecutar las celdas del notebook en orden, desde la importación de librerías hasta las conclusiones finales.

6. Guía de reproducción

Para reproducir los resultados:

Utilizar Python 3 y tener instaladas las librerías Pandas, NumPy, Matplotlib y Seaborn.

Disponer de los tres datasets originales.

Mantener la estructura y los nombres de los archivos o actualizar las rutas correspondientes en el notebook.

Ejecutar todas las celdas secuencialmente para reproducir la limpieza, transformación, análisis, visualizaciones y segmentación.

Revisar la sección final del notebook para consultar los hallazgos y recomendaciones comerciales.

7. Principales hallazgos

Los adultos representan el grupo de edad más numeroso, con 2.018 usuarios (50,45 %), seguidos por los adultos mayores con 1.222 (30,55 %) y los jóvenes con 760 (19 %).

El 73,58 % de los clientes pertenece al segmento de uso medio, mientras que el 19,48 % corresponde a bajo uso y el 6,95 % a alto uso.

El uso medio predomina en los tres grupos de edad.

Se identificaron usuarios con niveles elevados de consumo, que representan oportunidades para evaluar beneficios y paquetes adicionales.

Se conservaron los valores atípicos de las variables de actividad, ya que no se encontró evidencia suficiente para considerarlos errores en los datos.

8. Autoría

Proyecto desarrollado como parte de la formación en análisis de datos de TripleTen.
