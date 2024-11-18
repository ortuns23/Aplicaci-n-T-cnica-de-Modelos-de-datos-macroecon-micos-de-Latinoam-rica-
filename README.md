# Aplicacion Tecnica de Modelos de datos macroecon micos de Latinoamerica.

# Capstone Project: Aplicación de Modelos de Machine Learning e Inteligencia Artificial a Datos Macroeconómicos de Latinoamérica



Análisis Exploratorio de Datos Macroeconómicos del FLAR
Este proyecto realiza un análisis exploratorio de datos (EDA) sobre los indicadores macroeconómicos proporcionados por el Fondo Latinoamericano de Reservas (FLAR) a través de su Sistema de Información Económica (SIE).
Resumen de Hallazgos Iniciales
Nuestro análisis exploratorio inicial ha revelado varios patrones interesantes en los datos macroeconómicos de Latinoamérica:
Se observan tendencias similares en indicadores económicos clave entre grupos de países, sugiriendo posibles clusters regionales.
Existe una alta correlación entre ciertos indicadores económicos, como el PIB y la inversión extranjera directa.
Se detectaron algunas anomalías en las series temporales, particularmente en períodos de crisis económicas conocidas.
La completitud de los datos varía significativamente entre países y indicadores, lo que requerirá estrategias de manejo de datos faltantes.
Archivos del Proyecto
Preproceso_scripts.py
Este script contiene las funciones y procedimientos utilizados para la limpieza y preparación inicial de los datos del FLAR. Incluye:
Carga y formateo de datos brutos
Manejo de valores faltantes y atípicos
Normalización y estandarización de variables
Creación de nuevas características derivadas
FLARSIE_EDA_revision.py
Este archivo presenta el análisis exploratorio de datos completo. Características principales:
Visualizaciones detalladas de distribuciones de variables clave
Análisis de correlaciones entre indicadores económicos
Exploración de tendencias temporales por país y región
Identificación preliminar de posibles agrupaciones de países
Objetivos del Análisis
Agrupación de Países: Explorar similitudes entre países latinoamericanos basadas en sus indicadores macroeconómicos para identificar posibles clusters.
Predicción de Indicadores: Analizar las series temporales de indicadores clave para establecer las bases de futuros modelos predictivos.
Identificación de Patrones: Descubrir relaciones y patrones en los datos que puedan proporcionar insights valiosos para el FLAR.
Próximos Pasos
Profundizar en el análisis de clusters utilizando técnicas de machine learning no supervisado.
Desarrollar modelos predictivos para indicadores económicos clave.
Realizar un análisis comparativo más detallado entre países miembros y no miembros del FLAR.
Este proyecto es parte del Capstone Project para el curso de Data Science. Para más información sobre el FLAR y el SIE, visite www.flar.net.
