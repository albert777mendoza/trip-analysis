# Trip Data Analysis

Análisis de viajes para evaluar el impacto de condiciones climáticas
en la duración y comportamiento de los viajes.

**Herramientas:** SQL, PostgreSQL, Python


Trip Data Analysis
📌 Objetivo del proyecto
Analizar datos de viajes en taxi para evaluar el impacto de factores externos, especialmente las condiciones climáticas, en la duración de los viajes.

El análisis se enfoca en identificar patrones de comportamiento y apoyar la toma de decisiones basada en datos.

📊 Dataset
Los datos fueron proporcionados durante el bootcamp TripleTen y contienen:

Número de viajes por empresa de taxis
Promedio de viajes finalizados por barrio
Duración de viajes desde el barrio Loop hasta el Aeropuerto O'Hare
Condiciones climáticas asociadas a cada viaje
⚠️ Nota: Los datasets se cargan desde la plataforma de TripleTen y no están incluidos directamente en este repositorio.

🔍 Proceso de análisis
El proyecto se desarrolló siguiendo estos pasos:

Importación y exploración inicial de los datasets
Análisis exploratorio de datos (EDA)
Identificación de las principales empresas de taxis por número de viajes
Análisis de los barrios con mayor cantidad de finalizaciones
Evaluación del impacto del clima en la duración de los viajes
Prueba de hipótesis estadística (t-test)
📈 Análisis y visualizaciones
Se generaron visualizaciones para:

Distribución del número de viajes por empresa
Top 10 barrios por promedio de viajes finalizados
Comparación de la duración de viajes en sábados lluviosos vs no lluviosos
Estas visualizaciones permiten identificar patrones clave y diferencias estadísticamente significativas.

🧪 Prueba de hipótesis
Hipótesis nula (H₀):
La duración promedio de los viajes desde el Loop hasta el Aeropuerto O'Hare es la misma en sábados lluviosos y no lluviosos.

Hipótesis alternativa (H₁):
La duración promedio de los viajes cambia en sábados lluviosos.

Se utilizó una prueba t de Welch con un nivel de significación del 5%.

🛠️ Herramientas utilizadas
Python
Pandas
Matplotlib
SciPy
SQL
PostgreSQL
Jupyter Notebook
📂 Contenido del repositorio
trip_analysis.ipynb → Notebook con el análisis completo y visualizaciones
README.md → Documentación del proyecto
✅ Conclusiones
El análisis mostró que las condiciones climáticas influyen en la duración de los viajes, encontrándose una diferencia estadísticamente significativa en los sábados lluviosos en comparación con los no lluviosos.

Estos resultados pueden ser utilizados para mejorar la planificación operativa y la toma de decisiones estratégicas.
