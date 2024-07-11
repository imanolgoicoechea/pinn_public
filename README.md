# Phisics Informed Neural Networks

En este directorio encontrarás código para entrenar modelos de aprendizaje automático, redes neuronales y redes neuronales informadas por la física. También encontrarás código para probar esos modelos con datos generados artificialmente para un péndulo simple, y para comparar los resultados. 

## Subajuste y sobreajuste

Nombre del archivo: `01_underoverfitting_neural_network.ipynb`

A partir de datos generados artificialmente, entrena $3$ redes neuronales distintas, variando sus funciones de activación, número de épocas y regularización para poder mostrar así $3$ gráficas, una de ellas con subajuste, otra con un buen ajuste y la última con sobreajuste.

## Aprendizaje automático

Nombre del archivo: `02_pendulum_machine_learning.ipynb`

Genera datos artificiales para un péndulo simple en función de los parámetros aportados por el usuario. Realiza un ajuste con distintos métodos de aprendizaje automático. En cada uno de los casos realiza una gráfica en la que se muestra la comparación entre los datos reales y la predicción, así como el error cuadrático medio.

## Redes neuronales

Nombre del archivo: `03_pendulum_neural_network.ipynb`

Genera datos artificiales para un péndulo simple en función de los parámetros aportados por el usuario. Entrena $2$ redes neuronales distintas, una de ellas con función de activación tanh y la otra con función de activación seno. Realiza una gráfica para comparar el ajuste frente a los datos de entrenamiento.

## Resolución de ecuaciones

Nombre del archivo: `04_pendulum_pinn_solve.ipynb`

Genera datos artificiales para un péndulo simple en función de los parámetros aportados por el usuario. Entrena una red neuronal informada por la física y un modelo de aprendizaje automático con el objetivo de estudiar la precisión del ajuste. Compara los resultados de estos métodos junto con los métodos de las secciones anteriores.

## Descubrimiento de ecuaciones

Nombre del archivo: `05_pendulum_pinn_discovery.ipynb`

Genera datos artificiales para un péndulo simple en función de los parámetros aportados por el usuario. Entrena una red neuronal informada por la física y un modelo de aprendizaje automático con el objetivo de descubrir cuáles son las ecuaciones que gobiernan los datos artificialmente generados, y compara los resultados entre los modelos y frente a los datos reales. Esto lo hace también generando ruido a los datos generados artificialmente. Almacena los resultados de los modelos en la carpeta de `discovery_pickles`, dado que su ejecución es lenta.

## Estimación de parámetros

Nombre del archivo: `06_pendulum_pinn_estimate.ipynb`

Genera datos artificiales para un péndulo simple en función de los parámetros aportados por el usuario. Entrena una red neuronal informada por la física y un modelo de aprendizaje automático con el objetivo de estimar los parámetros de los datos artificialmente generados, y compara los resultados entre los modelos y frente a los datos reales. Esto lo hace también generando ruido a los datos generados artificialmente. Almacena los resultados de los modelos en la carpeta de `estimation_pickles`, dado que su ejecución es lenta.
