# Proyecto de Clasificación de Imágenes de Lenguaje de Señas con Deep Learning

Este proyecto es una implementación de clasificación de imágenes de lenguaje de señas utilizando diferentes técnicas de aprendizaje profundo en el framework de Deep Learning de Keras. El proyecto fue desarrollado en colaboración entre tres personas en el laboratorio de la materia de Visión Computacional con Deep Learning.

El proyecto consistió en la creación de un dataset a partir de la clonación del repositorio Sign Language Digits Dataset de Arda Mavi (https://github.com/ardamavi/Sign-Language-Digits-Dataset.git), la visualización y preprocesamiento de los datos, la implementación de clasificadores utilizando diferentes técnicas de aprendizaje profundo y la realización de pruebas para validar los modelos.

## Requerimientos

Este proyecto se realizó en Google Colab, por lo que se necesita una cuenta de Google y un acceso a Google Colab para poder ejecutar el código


## Métodos de Clasificación

- **Método Tradicional:** se utilizan detectores/descriptores, BoVW y ANN´s para clasificar las imágenes de números en lenguaje de señas.
- **CNN Básica:** se implementa una red neuronal convolucional básica para clasificar las imágenes.
- **CNN con Drop:** se mejora la red neuronal convolucional básica agregando una capa de Drop.
- **CNN con Drop y Regularización L2:** se añade una regularización tipo L2 junto con la capa de Drop para mejorar aún más la red neuronal convolucional.

## Pruebas
Se realizaron diferentes pruebas para validar el mejor modelo (modelo con capa de Drop). Para ello se utilizaron 20 imágenes propias que se encuentran en el repositorio de Visión Computacional. Los resultados de las pruebas se encuentran en https://github.com/Jessica-Arias/ComputerVision_DeepLearning/tree/main/CVwDL_20231/Prueba_lab1 fuera de la carpeta actual.

## Créditos
El dataset utilizado en este proyecto fue creado por Arda Mavi y se encuentra en https://github.com/ardamavi/Sign-Language-Digits-Dataset.git.
