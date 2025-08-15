# Clasificación de Imágenes de Perros y Gatos

Este proyecto utiliza redes neuronales convolucionales (CNN) con TensorFlow/Keras para clasificar imágenes de perros y gatos. El flujo de trabajo incluye la preparación de los datos, la construcción de modelos, el entrenamiento, la evaluación y la visualización de resultados.

## Estructura del Proyecto
- `dogs-vs-cats/`: Carpeta con las imágenes del dataset [Dogs-vs-Cats](https://www.kaggle.com/c/dogs-vs-cats/data?select=train.zip). Se debe descargar el dataset y colocar las imágenes deben en una subcarpeta llamada `train`.
- `models/`: Almacena los modelos entrenados en formato `.keras`.
- `notebooks/01-main.ipynb`: Notebook principal con el código para procesamiento, entrenamiento y evaluación.

## Principales Componentes
- **Submuestreo de datos**: Selección y transferencia de imágenes a carpetas específicas para entrenamiento, validación y prueba.
- **Arquitectura de la red**: Se implementan varias arquitecturas CNN, incluyendo variantes con data augmentation y dropout.
- **Entrenamiento y evaluación**: Los modelos se entrenan y evalúan usando métricas de precisión y pérdida.
- **Visualización**: Se grafican los resultados de entrenamiento y validación.

## Requisitos

Este proyecto utiliza un entorno Conda. Para instalar los requisitos, ejecuta:

```bash
conda env create -f environment.yml
conda activate tf_env
```

Principales dependencias:
- Python 3.10.14
- TensorFlow 2.18.1
- Numpy 2.0.2
- Matplotlib 3.10.1
- Scikit-learn 1.7.1
- Pandas
- ipykernel

## Ejecución
Abre el notebook `notebooks/01-main.ipynb` y ejecuta las celdas en orden para preparar los datos, entrenar los modelos y visualizar los resultados.

## Licencia
Este proyecto es solo para fines educativos.
