# Práctica 03: El Perceptrón

Implementación manual desde cero de un perceptrón simple en Python para clasificación binaria linealmente separable, desarrollado como parte de la asignatura de **Inteligencia Artificial** en la **Universidad Politécnica Salesiana (UPS)**.

## Enlaces del Proyecto
* **Repositorio GitHub:** [https://github.com/Alejandro120325/Practica_03_El_Perceptron](https://github.com/Alejandro120325/Practica_03_El_Perceptron)
* **Notebook en Google Colab:** [Abrir en Colab](https://colab.research.google.com/github/Alejandro120325/Practica_03_El_Perceptron/blob/main/Practica_03_El_Perceptron.ipynb)

## Contenido de la Práctica
1. **Exploración del Dataset:** Inspección manual de 23 instancias bidimensionales $(X_1, X_2)$ con etiquetas bipolares $y \in \{-1, 1\}$ y visualización de su distribución en el plano.
2. **Modelo del Perceptrón:** Implementación de inicialización aleatoria de pesos ($w_0, w_1, w_2$), función de activación escalón bipolar y cálculo de salida sin librerías de *machine learning*.
3. **Visualización de Frontera:** Graficación de la recta separadora $w_0 + w_1 x_1 + w_2 x_2 = 0$.
4. **Entrenamiento y Convergencia:** Regla de actualización iterativa con registro de tasa de error y evolución de pesos por época.
5. **Predicción y Evaluación:** Clasificación de nuevas instancias (`[5, 5]`, `[10, 6]`, `[6, 10]`) y visualización del dataset extendido.
6. **Análisis Comparativo:** Evaluación del impacto de distintas tasas de aprendizaje (`lr = 0.3`, `0.5` y `0.8`) partiendo de los mismos pesos iniciales.

## Tecnologías Utilizadas
* Python 3 (estructuras básicas: listas, ciclos y condicionales)
* Matplotlib (visualización de datos, fronteras de decisión y curvas de error)
* Google Colab

## Autor
* **Jairo Alejandro Ojeda Herrera** — Carrera de Ingeniería en Ciencias de la Computación (UPS)
