# **Face_Emotion**
En este repositorio trabajaremos el entrenamiento de una red neuronal convolucional para la clasificación de emociones y la detección en tiempo real usando una cámara web. 

## Entrenamiento en google colab

El entrenamiento lo realizaremos en google colab. Vamos a configurar un entorno para trabajar con las siguientes versiones de librerías:
    
*     Tensorflow = 2.17.0
      Keras = 3.4.1

En el siguiente enlace encuentras el código para ejecutar el entrenamiento en colab.

[FaceEmotion.ipynb](https://github.com/DavidReveloLuna/Face_Emotion/blob/master/FaceEmotion.ipynb)

## Prueba en tiempo real
### Preparación del entorno

$ conda create -n FaceEmotion
$ conda activate FaceEmotion
$ conda install python=3.7
$ pip install tensorflow==2.17.0
$ pip install keras==3.4.1
$ pip install imutils opencv-python h5py
$ pip install matplotlib 

    
### Usando WebCam

Ejecutar el archivo FaceEmotionVideo.py

    $ python FaceEmotionVideo.py

