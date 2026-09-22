# Jigsaw Puzzle Solver - Neural Network 🧩

Este proyecto utiliza redes neuronales profundas (Deep Learning) en TensorFlow/Keras para resolver rompecabezas (*Jigsaw puzzles*) a partir de parches de imágenes del dataset **STL-10**.

## 🚀 Características
- **Dataset:** STL-10 (imágenes reescaladas a parches de 28x28x3).
- **Tarea:** Predecir la permutación/orden correcto de 9 piezas para reconstruir la imagen original (96x96x3).
- **Framework:** TensorFlow / Keras en Google Colab.

## 📂 Estructura del proyecto
- `jigsaw_puzzle_ULT.ipynb`: Cuaderno Jupyter con la carga de datos, arquitectura del modelo, entrenamiento y visualización de resultados.

## 📊 Resultados
El cuaderno incluye visualizaciones de las reconstrucciones y las curvas de pérdida y precisión (*loss / accuracy*) durante el entrenamiento.
