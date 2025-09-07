# Trabajo Práctico Integrador – Probabilidad y Estadística

Alumno: Daniel Alberto Jimenez Valderrama
Comisión: 12

# Descripción del proyecto

Este trabajo práctico consiste en la carga, procesamiento y análisis de datos de un cuestionario estudiantil, con foco en dos variables principales: 
- horas semanales de estudio y nivel de satisfacción con la carrera.
- Se aplican técnicas de estadística descriptiva.
-  construcción de tablas de frecuencia y representaciones gráficas para interpretar los resultados.

# Tecnologías utilizadas (Lenguaje R)

# Librerías: readxl, dplyr, ggplot2

# Funcionalidades principales:

1. Carga y preparación de datos

- Se importa un archivo Excel con los datos de los estudiantes.
- Se renombran las columnas para facilitar el manejo.
- Se eliminan valores faltantes (NA) de las variables analizadas.

2. Análisis de horas de estudio

- Se calcula el tamaño muestral válido y se determina la cantidad óptima de intervalos usando la regla de Sturges.
- Se construye una tabla de frecuencias con: frecuencia absoluta, relativa, porcentajes y acumuladas.
- Se calculan medidas descriptivas: media, mediana, moda, cuartiles, rango, varianza, desviación estándar y coeficiente de variación.
- Se genera un histograma con densidad sobrepuesta.

3. Análisis del nivel de satisfacción

- Se convierte la variable ordinal “satisfacción” en factor ordenado (1 = Muy satisfecho, …, 4 = Muy insatisfecho).
- Se construye una tabla de frecuencias con valores absolutos, relativos, porcentajes y acumulados.
- Se calculan medidas descriptivas: moda, mediana y cuartiles.
- Se representa gráficamente con un diagrama circular que muestra la proporción de cada categoría.

4. Representación gráfica

- Histograma de horas de estudio con curva de densidad.
- Diagrama circular de satisfacción con colores distintivos y etiquetas de porcentaje.

Objetivo

El proyecto permite resumir y visualizar información relevante sobre los hábitos de estudio y la satisfacción de los estudiantes, 
facilitando la interpretación de datos cuantitativos y cualitativos de manera clara y efectiva.
