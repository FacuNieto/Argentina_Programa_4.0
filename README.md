<p align="center">
  <img src="assets/rotulo_IALAB.png" alt="rotulo">
</p>

## Argentina_Programa_4.0. Tramo 3. Módulo 4.

Este repositorio contiene el código comentado para el material de trabajo del curso "Data Science y Data Analytics" del programa Argentina Programa 4.0. Este repositorio se enfoca en el módulo de Data Science y Machine Learning y aborda dos ejemplos sobre la utilización de arboles de decisión. Este material corresponde especificamente al modulo 4 del tramo 3.

En esta clase se vieron dos ejemplos de aplicación de arboles de decisión y sus usos en la industria. 

---

### Ejemplo 1️⃣: Clasificación de componentes vegetales utilizando visión artificial 🌸📸

En este ejemplo, se presenta un caso en el que una pequeña farmacéutica produce una medicación basada en componentes vegetales y busca mejorar el proceso de clasificación de las plantas utilizadas. Para ello, se ha desarrollado un sistema de visión artificial que calcula las características de los componentes vegetales.

#### Código 

El código para este ejemplo se encuentra en la primera sección del archivo `Demo_Practica_Arboles.ipynb`. A continuación, se resumen las secciones principales del código:

1. Carga de librerías: Se importan las librerías necesarias, como `numpy`, `pandas`, `matplotlib`, así como las clases y funciones relacionadas con el algoritmo de árbol de decisión.

2. Carga, análisis y visualización del dataset: Se carga el dataset de iris utilizando la función `load_iris` de `sklearn.datasets`. Luego, se visualiza el dataset en un dataframe y se realiza una exploración inicial de los datos.

3. Generación de datos de entrenamiento y prueba: Se divide el dataset en datos de entrenamiento y prueba utilizando la función `train_test_split` de `sklearn.model_selection`.

4. Carga y entrenamiento del modelo: Se crea una instancia del clasificador de árbol de decisión y se entrena con los datos de entrenamiento. Luego, se realiza la predicción con los datos de prueba y se evalúa la precisión del modelo utilizando métricas como el accuracy.

---

### Ejemplo 2️⃣: Predicción de resultados en partidos de fútbol de Messi ⚽💻

En este ejemplo, se utiliza un dataset que contiene información sobre los goles y resultados de partidos de fútbol de Lionel Messi. El objetivo es crear un modelo de árbol de decisión que pueda predecir el resultado de un partido en función de diferentes variables, como el minuto en el que Messi hizo el gol, el tipo de gol, el resultado a favor y en contra, etc.

#### Código

El código para este ejemplo se encuentra en la segunda sección del archivo `Demo_Practica_Arboles.ipynb`. A continuación, se resumen las secciones principales del código:

1. Clonado del repositorio y lectura del dataset: Se clona un repositorio que contiene el dataset de Messi y se lee el archivo CSV correspondiente.

2. Limpieza de datos: Se realizan diversas tareas de limpieza y preparación de los datos, como la corrección del formato de la fecha, la reducción de tipos de goles, la generación de columnas de victoria, la corrección de la posición de Messi, etc.

3. Encoding de variables: Se aplica one-hot encoding a las variables categóricas, como Venue y Playing_Position, utilizando la función `get_dummies` de `pandas`.

4. Creación y entrenamiento del modelo: Se divide el dataset en datos de entrenamiento y prueba. Luego, se crea una instancia del clasificador de árbol de decisión y se entrena con los datos de entrenamiento. Se evalúa la precisión del modelo utilizando métricas como el accuracy.

5. Predicción de resultado: Se proporciona un formulario interactivo donde se ingresan los datos del partido, como el minuto del último gol de Messi, el día, el mes, el tipo de gol, etc. Utilizando el modelo entrenado, se realiza una predicción del resultado (victoria o derrota).

---

## Referencias adicionales 🎓💻

A continuación se mencionan algunos enlaces relevantes y fuentes de datos utilizadas en los ejemplos. 

- https://scikit-learn.org/stable/datasets/toy_dataset.html

- https://es.wikipedia.org/wiki/Conjunto_de_datos_flor_iris

- https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html

## Consideraciones 👀🧐

- Los datos de Iris fueron tomados el mismo día, con lo que eso implica (poca generalización).

- El dataset de Messi tiene clases desbalanceadas. Los árboles son sensibles a datos desbalanceados!

- Por cuestiones de tiempos no hablamos de métricas

Si tienes alguna pregunta o comentario, no dudes en contactarme!
