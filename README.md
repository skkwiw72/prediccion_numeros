# prediccion_numeros
# Visualización y Clasificación de Dígitos Escritos a Mano

Este programa carga un conjunto de datos de dígitos escritos a mano utilizando la biblioteca `sklearn.datasets`. Luego, muestra una selección de imágenes de dígitos en una fila de subgráficos. Cada imagen se acompaña de su etiqueta correspondiente que indica el dígito representado.

A continuación, los datos se dividen en conjuntos de entrenamiento y prueba mediante la función `train_test_split` de `sklearn.model_selection`.

Se utiliza un clasificador de Bosque Aleatorio (`RandomForestClassifier`) para entrenar un modelo capaz de clasificar los dígitos. Posteriormente, se evalúa el desempeño del modelo utilizando métricas como la matriz de confusión y el informe de clasificación.

Finalmente, se importa la matriz de confusión y el informe de clasificación desde `sklearn.metrics`.
