Resumen 
Objetivo del proyecto:Analizar el comportamiento de los usuarios de ConnectaTel mediante técnicas de análisis exploratorio de datos (EDA), con el fin de identificar patrones de uso, detectar problemas en la calidad de los datos, segmentar clientes y generar recomendaciones para optimizar la oferta de planes de la compañía.

Datasets utilizados:
users: información demográfica y contractual de los usuarios (edad, ciudad, plan, fecha de registro, entre otros).
usage: registros de uso del servicio, incluyendo llamadas, mensajes, duración de llamadas y longitud de mensajes.

Etapas del análisis realizadas:
Exploración inicial de los datos.
Identificación y tratamiento de valores nulos y valores inconsistentes.
Conversión de variables al tipo de dato adecuado.
Creación de variables agregadas por usuario (mensajes, llamadas y minutos).
Integración de los datasets mediante merge().
Análisis estadístico descriptivo.
Visualización mediante histogramas y boxplots.
Detección de valores atípicos utilizando el método IQR.
Interpretación de resultados y formulación de recomendaciones para el negocio.

Cómo ejecutar el notebook:
El notebook puede ejecutarse en Google Colab o Jupyter Notebook. Solo es necesario cargar los archivos users.csv y usage.csv, ejecutar las celdas en orden y verificar que estén instaladas las librerías Pandas, Matplotlib y Seaborn.

Guía breve de reproducción
Abrir el notebook en Google Colab o Jupyter Notebook.
Importar las librerías requeridas (pandas, matplotlib.pyplot y seaborn).
Cargar los archivos users.csv y usage.csv.
Ejecutar las celdas en el orden establecido para reproducir el proceso de limpieza, transformación, análisis y visualización de los datos.
Revisar las tablas, gráficos y conclusiones obtenidas para interpretar el comportamiento de los usuarios y los segmentos identificados.
