# Equipo_3_Proyecto_Final


# Analítica Deportiva usando Modelos de Deep Learning
Descripción del Proyecto
Este proyecto se enfoca en la analítica deportiva utilizando técnicas de Deep Learning y Visión por Computadora para la detección de jugadores y balón de fútbol a partir de videos aéreos.

El notebook implementa un pipeline completo de Machine Learning utilizando la arquitectura YOLOv11 del framework Ultralytics. El proyecto incluye:

* Preprocesamiento de video y extracción de fotogramas usando OpenCV
* Preparación del dataset y flujos de trabajo de anotación
* División de datos para entrenamiento, validación y pruebas
* Optimización de hiperparámetros con Optuna
* Entrenamiento del modelo usando YOLOv11
* Validación y pruebas del modelo entrenado
* Visualización de resultados de detección
  
El objetivo principal es desarrollar un sistema de detección de objetos capaz de identificar jugadores de fútbol y el balón en grabaciones deportivas aéreas.


# Tecnologías Utilizadas

* Python 3.10+
* OpenCV
* Ultralytics YOLOv11
* Optuna
* Scikit-learn
* Google Colab
* PyTorch


# Ejecutar con Google Colab

* Sube el notebook a Google Colab.
* Sube el dataset a Google Drive.
* Ejecuta las celdas en orden.
  
El notebook ya incluye integración con Google Drive.


# Preparación del Dataset

El proyecto espera un dataset que contenga:

* Jugadores de fútbol
* Balón de fútbol
* El video para extraer los frames
* Labels e imágenes de entrenamiento
  
Las imágenes deben estar anotadas en formato YOLO.

Ejemplo de anotación YOLO:

```text
0 0.512 0.421 0.120 0.210
