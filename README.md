# Solucion-de-problemas-

EL objetivo es predecir la calificación final de estudiantes a partir de información demográfica, hábitos de estudio y calificaciones previas, utilizando un modelo de regresión lineal múltiple. 

La base proviene del dataset Student Performance Data Set (UCI Machine Learning Repository). Cada fila representa un estudiante, con las siguientes variables:

• Escuela - Escuela de procedencia (GP o MS).

• Sexo - F (mujer) o H (hombre).

• Edad - Edad del estudiante en años.

• HorasDeEstudio - Rango de horas de estudio (1 = <2h, 4 = >10h).

• Reprobadas - Número de materias reprobadas anteriormente.

• Internet - Acceso a internet en casa (yes/no).

• Faltas - Número de inasistencias.

• G1 - Calificación primer periodo (0–20)

• G2 - Calificación segundo periodo (0–20).

• G3 - Calificación final (0–20).

Pasos a realizar: 

1. Importar datos

2. Transformar variables categóricas: Convertir a variables dummy para usarlas en regresión.

3. Identificar valores atípicos: Detectar outliers en Faltas usando el método de Tukey (k=3)

4. Analizar correlaciones: Construir matriz de correlación y visualizar con un heatmap
   
5. Incluir términos de interacción: Crear al menos dos interacciones entre variables relevantes.

6. Modelo de regresión: Dividir datos (80% entrenamiento, 20% prueba). Ajustar modelo OLS, revisar resumen de resultados. Predecir sobre datos de prueba y comparar valores reales vs. estimados en un scatter plot.

La actividad va de 3 documentos:

[reporte html](A1.5_652911.html)

[reporte ipynb](A1.5_652911.ipynb)

[reporte Calificaciones.cvs](Calificaciones.csv)

