# Análisis Estadístico sobre hábitos saludables en jóvenes universitarios
Inferencia Estadística

Descripción del Proyecto
Este estudio analiza los hábitos de vida y la productividad de estudiantes universitarios utilizando el conjunto de datos "Ultimate Student Productivity Dataset", el cual cuenta con 5000 registros. El objetivo central es aplicar herramientas de inferencia estadística para comprender la distribución de estos hábitos y evaluar patrones de comportamiento académico.
Objetivos
Aplicar el método científico a la estadística (observación, hipótesis, análisis e interpretación).
Evaluar la relación entre variables como horas de estudio, sueño, uso de redes sociales y burnout con respecto al rendimiento académico (puntaje de examen).
Validar conceptos estadísticos clave como el Teorema del Límite Central y realizar pruebas de significancia.
Tecnologías Utilizadas
El análisis se desarrolló íntegramente en Python dentro del entorno Google Colab, utilizando las siguientes librerías:
Pandas: Para la manipulación y exploración de la base de datos.
NumPy: Para cálculos numéricos y manejo de muestras.
Matplotlib: Para la generación de histogramas y gráficos de dispersión.
Scipy.stats: Para el cálculo de intervalos de confianza y ejecución de pruebas t de una muestra.
Estructura del Análisis
Exploración de Datos: Carga del dataset y descripción de variables cuantitativas (ej. study_hours, exam_score) y cualitativas (ej. gender).
Análisis de Probabilidades: Cálculo de eventos aleatorios, intersecciones y uniones sobre los hábitos de los estudiantes.
Distribuciones: Modelado de variables mediante la distribución normal.
Inferencia Estadística:
Verificación empírica del Teorema del Límite Central mediante múltiples muestras.
Construcción de intervalos de confianza al 90%, 95% y 99%.
Test de Hipótesis: Prueba t para evaluar si el promedio del puntaje de examen difiere significativamente de un valor hipotético.
Hallazgos Principales
Relación Positiva: Se observa que un mayor tiempo dedicado al estudio tiende a asociarse con mejores resultados en los exámenes.
Significancia Estadística: El test de hipótesis resultó en un valor p de 0.0, lo que llevó a rechazar la hipótesis nula, confirmando que el promedio observado es significativamente distinto al valor de referencia.
Distribución de los Datos: Las variables clave tienden a agruparse cerca de la media, siguiendo un patrón consistente con una distribución normal.

--------------------------------------------------------------------------------
Este proyecto fue realizado como parte del módulo de Inferencia Estadística por la estudiante Cintia García Ortega
