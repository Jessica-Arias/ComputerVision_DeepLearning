## Proyecto de detección de armas utilizando FasterRCNN

Este proyecto tiene como objetivo la detección de armas en imágenes y videos utilizando la red neuronal FasterRCNN. Para el entrenamiento y prueba de la red se utiliza un dataset de armas que se encuentra en un archivo .zip dentro de la carpeta del proyecto.

## Requerimientos

Este proyecto se realizó en Google Colab, por lo que se necesita una cuenta de Google y un acceso a Google Colab para poder ejecutar el código

## Cómo correr el código
1. Sube el archivo "gunniest.zip" a tu carpeta de Colab.
2. Ejecuta el notebook "Faster_RCNN_Armas.ipynb" en Colab.
3. El código descomprimirá automáticamente el archivo "gunniest.zip".
4. Sigue las instrucciones del notebook para entrenar y evaluar el modelo.
5. Una vez que el modelo esté entrenado, se puede usar para detectar armas en imágenes o videos.

## Cómo probar el modelo con un video
1. Sube el archivo arma.mp4 a tu carpeta de Colab.
2. Ejecuta la última celda del notebook para probar el modelo con el video.
3. El resultado de la prueba se guardará en el archivo result.avi en el content del colab.

El resultado del entrenamiento realizado previamente, se muestra ne el archivo result.avi que se encuentra subido en esta carpeta.

## Sobre el modelo
El modelo Faster R-CNN utilizado en este proyecto es una red neuronal convolucional profunda que utiliza una arquitectura de dos etapas para la detección de objetos. En la primera etapa, se usa una red convolucional para extraer características de la imagen. En la segunda etapa, se utiliza una red de regiones de interés (RoI) para seleccionar las regiones más prometedoras de la imagen y aplicar una red completamente conectada para clasificar y ajustar los cuadros delimitadores de los objetos.

Este modelo se entrenó utilizando TensorFlow y se utilizó la GPU de Colab para acelerar el entrenamiento.
