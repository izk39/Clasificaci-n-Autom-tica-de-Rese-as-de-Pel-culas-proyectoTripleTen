# Clasificaci-n-Autom-tica-de-Rese-as-de-Pel-culas-proyectoTripleTen
Proyecto para desarrollar un modelo de clasificación que detecte automáticamente críticas negativas en reseñas de películas de IMDB, este es un proyecto del bootcamp de TripleTen

🎬 Film Junky Union — Clasificación Automática de Reseñas de Películas
Proyecto para desarrollar un modelo de clasificación que detecte automáticamente críticas negativas en reseñas de películas de IMDB. La meta es alcanzar un valor F1 mínimo de 0.85 para garantizar una detección precisa.

📁 Archivo de datos
imdb_reviews.tsv: conjunto de datos con reseñas etiquetadas.

review: texto de la reseña.

pos: etiqueta objetivo (0 = negativo, 1 = positivo).

ds_part: indica si la fila corresponde a entrenamiento o prueba.

🧪 Objetivo del proyecto
Cargar y preprocesar los datos textuales para su vectorización.

Realizar un análisis exploratorio para entender la distribución y posible desequilibrio de clases.

Entrenar al menos tres modelos diferentes de clasificación para predecir la polaridad de las reseñas.

Evaluar los modelos utilizando métricas adecuadas, priorizando el F1-score.

Clasificar reseñas escritas manualmente con los modelos entrenados y comparar resultados.

Analizar y explicar las diferencias en desempeño de los modelos.

Mantener un código limpio, organizado y reproducible.

🛠️ Proceso desarrollado
1. Preparación y análisis de datos
Carga y exploración del archivo imdb_reviews.tsv.

Análisis exploratorio para detectar desequilibrio de clases y características del texto.

Limpieza y preprocesamiento del texto (tokenización, limpieza, vectorización).

2. Modelado predictivo
Definición y entrenamiento de al menos tres modelos, incluyendo:

Regresión logística

Potenciación del gradiente (Gradient Boosting)

Otros modelos probados según conveniencia

Evaluación con el conjunto de prueba usando métricas clave: precisión, recall y F1.

3. Evaluación y conclusiones
Clasificación de reseñas escritas manualmente para validar modelos.

Comparación detallada del rendimiento y explicación de diferencias.

Discusión sobre hallazgos y recomendaciones.

⚠️ Nota sobre BERT
Aunque la plantilla incluye funciones para convertir textos en embeddings con BERT, el uso completo de BERT no es obligatorio debido a su alta demanda computacional y lentitud en CPU. Se puede usar para un subconjunto pequeño para pruebas experimentales, siempre dejando claro en el código.

🧠 Herramientas utilizadas
Python (Pandas, NumPy, Scikit-learn)

Jupyter Notebook

Técnicas de NLP para preprocesamiento y vectorización

Evaluación con métricas estándar para clasificación binaria

✅ Resultados esperados
Modelos entrenados que superen el umbral mínimo de F1-score (0.85).

Análisis claro de la distribución de clases y comportamiento del modelo.

Código reproducible y limpio, siguiendo buenas prácticas.