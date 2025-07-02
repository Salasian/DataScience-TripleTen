## ¿Qué pasos del plan se realizaron y qué pasos se omitieron (explica por qué)?

Dentro del plan de trabajo aplicado al proyecto, se desarrollaron los siguientes pasos:

- Identificación y manejo de datos nulos, duplicados
- Gráficos y desarrollaro de conclusiones sobre los datos
- Trato de datos atípicos los datos atípicos registrados
- Búsqueda de las correlaciones entre todos los datos del cliente
- Definición de características categóricas y numéricas
- Construcción y separación para los datos de entrenamiento y de prueba del modelo
- Establecer un objetivo el cual predecir
- Establecer métricas de medida para determinar la meta de negocio (AUC-ROC, F1, Accuracy, etc.)
- Analizar la comparación de métricas.
- Ajustar los hiperparámetros de cada modelo en cuestión.
- Interpretación de los resultados: ¿qué variables aportan más al modelo? Para así poder escoger el modelo en su versión final, y encajar mejor en la meta de negocio

También se agregarón nuevos pasos pasos durante el proceso como:

- Formatéo de Columnas a los tipos correctos
- Matríz de Correlación
- Detallado de las columnas binarias
- Análisis de las inscripciones por mes
- Adición de modelo LightGBM

## ¿Qué dificultades encontraste y cómo lograste resolverlas?

Las dificultades que encontre fueron:

- En el filtrado de datos, en un principio no logré asignar un buen valor para la columna EndDate, ya que no sabía si se quería conservar la fecha en la que los clientes dieron de baja el servicio. Y no fue hasta depués que entendí, que necesitabamos como variable binaria la columna, lo cual ayudó a aclarar el análisis posteriormente.
- Otra dificultad que encontré, fue la de no dar con el 88% requerido para obtener una puntuación alta en el modelo de LinearRegression, investigué sobre que más alternativas podría lograr, y logré decifrar que quizas necesitaba apoyarme con un modelo de Gradient Boosting como fue LightGBM.

## ¿Cuáles fueron algunos de los pasos clave para resolver la tarea?

Creo que algunos pasos clave para resolver la tarea fueron:

- Reconocer bien mis variables features y mi variable objetivo
- Estandarizar los precios a número más bajos para aumentar la eficiencia del modelo
- Identificar los tipos de mis columnas y percatarme que todas podían ser numéricas, lo cual aumento la eficacia del modelo
- Cambiar de modelo de Machine Learning para lograr puntajes más altos en la métrica necesitada

## Cuál es tu modelo final y qué nivel de calidad tiene?

Mi modelo final es LightGBM, y su nivel de calidad es de 0.92% en el score AUC-ROC para la predictibilidad de las bajas de clientes
