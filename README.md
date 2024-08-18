# Redes-neuronales
Las redes neuronales son un tipo fundamental de algoritmo de Machine Learning que está inspirado en la estructura y funcionamiento del cerebro humano. Se utilizan ampliamente en una variedad de aplicaciones, desde el reconocimiento de imágenes y voz hasta la predicción de series temporales y juegos. Las redes neuronales son la base de lo que hoy conocemos como "Deep Learning".

Conceptos Clave en Redes Neuronales
Neuronas y Capas:

Neurona: La unidad básica de una red neuronal, que toma una entrada, realiza una operación matemática (generalmente una combinación lineal seguida de una función de activación), y produce una salida.
Capa de Entrada: Recibe las características del conjunto de datos.
Capas Ocultas: Capas intermedias entre la entrada y la salida, donde ocurre el aprendizaje. Puede haber múltiples capas ocultas (redes profundas).
Capa de Salida: Produce la predicción final.
Función de Activación:

Introduce no linealidad en el modelo, permitiendo a la red neuronal aprender patrones complejos.
Ejemplos comunes incluyen la función sigmoide, tanh, y ReLU (Rectified Linear Unit).
Propagación Adelante (Forward Propagation):

El proceso de calcular la salida de la red neuronal, desde la capa de entrada, a través de las capas ocultas, hasta la capa de salida.
Propagación hacia Atrás (Backpropagation):

Es el proceso de ajustar los pesos de la red neuronal para minimizar el error de predicción. Esto se hace calculando el gradiente del error con respecto a los pesos y actualizándolos usando el descenso de gradiente.
Función de Pérdida:

Mide qué tan lejos están las predicciones de los valores reales. Ejemplos incluyen el error cuadrático medio (MSE) para regresión y la entropía cruzada para clasificación.
Optimización (Descenso de Gradiente):

Un algoritmo que ajusta los pesos de la red para minimizar la función de pérdida. El descenso de gradiente estocástico (SGD) y Adam son algoritmos de optimización populares.
