#Análisis exploratorio de accidentes de aviación comercial (1908–2025)

Este proyecto forma parte de mi portafolio de análisis de datos y tiene como objetivo explorar la evolución de los accidentes de aviación comercial desde 1908 hasta 2025. A través de técnicas de limpieza, transformación y visualización de datos en R, analizo tendencias históricas, categorías de accidentes, fatalidades y patrones temporales para responder a una pregunta clave:
¿Qué tan seguro es volar?

Objetivos del proyecto
•	Limpiar y preparar una base de datos histórica de accidentes aéreos.
•	Analizar la frecuencia de accidentes y fatalidades a lo largo del tiempo.
•	Identificar outliers y eventos históricos relevantes.
•	Comparar categorías de accidentes (A1, A2, C1, etc.) y su severidad.
•	Evaluar la seguridad de la aviación comercial moderna (1990–2025).
•	Crear visualizaciones claras y profesionales con ggplot2 y plotly.

Tecnologías utilizadas
•	R
•	tidyverse
•	dplyr
•	ggplot2
•	plotly
•	lubridate
•	janitor
•	skimr

Metodología
1. Limpieza y preparación de datos
- Eliminé duplicados y registros inconsistentes.
- Reemplacé valores faltantes o no válidos en la columna de fecha.
- Convertí la fecha a un formato estándar utilizando múltiples estructuras posibles, ya que el dataset incluía formatos mixtos.
- Extraje variables temporales clave: año, mes y día.
- Realicé una revisión general de calidad de datos con skimr y janitor.
2. Filtrado de aviación comercial
- Excluí operadores militares, privados y no comerciales para centrar el análisis únicamente en vuelos comerciales.
- Eliminé el evento del 11 de septiembre de 2001 para evitar distorsiones estadísticas.
- Validé que los registros restantes correspondieran a operaciones civiles.
3. Análisis exploratorio (EDA)
- Analicé la evolución de los accidentes por año y por categoría.
- Comparé accidentes vs. fatalidades para evaluar la severidad a lo largo del tiempo.
- Identifiqué outliers históricos y los interpreté en su contexto.
- Exploré la distribución de categorías (A1, A2, C1, etc.) y su relación con la severidad.
- Realicé un análisis específico del periodo 1990–2025, donde se observa la mayor estabilidad y seguridad operacional.
4. Visualización de resultados
- Creé gráficos de líneas, barras y distribuciones con ggplot2.
- Generé visualizaciones interactivas con plotly para facilitar la exploración del usuario.
- Organicé los gráficos de forma narrativa para mostrar la evolución histórica y las mejoras en seguridad.


Principales hallazgos
•	La aviación comercial muestra una tendencia clara de mejora en seguridad, especialmente desde 1990.
•	Aunque los accidentes no desaparecen, las fatalidades disminuyen de forma más pronunciada, indicando mayor capacidad de supervivencia.
•	Las categorías A1 y A2 siguen siendo las más frecuentes, pero con menor severidad en décadas recientes.
•	Los picos históricos (como 1944) no se reflejan en fatalidades, lo que sugiere accidentes menos severos o registros incompletos.
•	Entre 1990 y 2025, la aviación comercial alcanza sus niveles más bajos de accidentes y muertes.

Reflexión final
Este análisis confirma que, a pesar de la percepción pública, volar es hoy más seguro que nunca. La combinación de tecnología, regulación, entrenamiento y cultura de seguridad ha transformado la aviación comercial en uno de los medios de transporte más confiables del mundo.


