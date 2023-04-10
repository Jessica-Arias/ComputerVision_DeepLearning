# Detección y conteo de piñas usando YOLOv7
Este es un proyecto de colab que utiliza YOLOv7 para la detección y conteo de piñas en imágenes aéreas tomadas con un dron. El dataset fue creado con la herramienta de etiquetado de Roboflow y se utilizó data augmentation para mejorar el rendimiento del modelo.

## Dataset
El dataset se carga directamente en el cuaderno de colab y consta de imágenes de alta calidad tomadas en dos días distintos con diferencias de luz. La detección se realizó manualmente con la herramienta de etiquetado de Roboflow.

## Entrenamiento
Se utilizó YOLOv7 para entrenar el modelo, el cual se guarda en el drive. El entrenamiento se ejecutó durante varias épocas para asegurar que el modelo tuviera un buen rendimiento en imágenes nuevas.

## Resultados
El resultado de la detección y conteo de piñas se guarda en el drive y se carga en el cuaderno de colab para su visualización. Además, se añade un caption en la parte inferior de cada imagen con el número de piñas detectadas. El modelo entrenado también se prueba con un video de prueba que se encuentra en el drive mencionado anteriormente.

## Archivos
- piñas.mp4: video de prueba original
- video_salida.mp4: video de prueba con la detección y conteo de piñas realizada, donde se muestra el número de piñas por frame del video.
- train.zip: el modelo entrenado guardado en el drive
- timesbd.ttf: herramienta para descargar el tipo de letra de los caption.

## Acceso a los archivos
Todos los archivos mencionados anteriormente se pueden encontrar en el siguiente drive: https://drive.google.com/drive/folders/1BiToA92SmvroAl2NFvTliwVARzkViFhl?usp=sharing

