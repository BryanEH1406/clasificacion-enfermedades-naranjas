# Clasificación de enfermedades en naranjas

Aplicación de visión por computadora para segmentar naranjas mediante YOLO y clasificar su condición utilizando MobileNetV3 y características de color.

## Descripción

El proyecto utiliza un modelo YOLO para detectar y segmentar el fruto dentro de una fotografía. Posteriormente, la imagen segmentada es procesada por un modelo de clasificación basado en MobileNetV3 para identificar diferentes condiciones o enfermedades presentes en la naranja.

## Tecnologías utilizadas

- Python
- YOLO
- MobileNetV3
- TensorFlow / Keras
- OpenCV
- Gradio
- Google Colab

## Archivos del proyecto

El repositorio contiene:

- Notebooks de entrenamiento y evaluación.
- Aplicación para segmentación y clasificación.
- Imágenes con resultados de prueba.
- Reportes generados durante la evaluación de los modelos.
- Código utilizado para el procesamiento de imágenes.

## Dataset y archivos pesados

Debido al tamaño del conjunto de datos y de algunos modelos entrenados, estos archivos no se almacenan directamente en GitHub.

Los recursos completos del proyecto se encuentran disponibles en Google Drive:

[Acceder a la carpeta del proyecto en Google Drive](https://drive.google.com/drive/folders/1185ukYRqjvvhuEqbGa6RkCTtUIc1OUiL)

En esta carpeta se pueden almacenar:

- Dataset de imágenes.
- Máscaras de segmentación.
- Modelos entrenados.
- Resultados de clasificación.
- Notebooks complementarios.
- Archivos comprimidos del proyecto.

## Funcionamiento general

1. El usuario carga una fotografía de una naranja.
2. YOLO detecta y segmenta el fruto.
3. La imagen segmentada se prepara para el clasificador.
4. MobileNetV3 calcula las probabilidades de cada clase.
5. La aplicación muestra el resultado y la confianza obtenida.

## Ejecución

1. Descargar los archivos necesarios desde Google Drive.
2. Abrir el notebook de la aplicación en Google Colab.
3. Verificar las rutas de los modelos y del dataset.
4. Ejecutar las celdas en orden.
5. Abrir el enlace generado por Gradio.
6. Subir una imagen de una naranja para realizar la clasificación.

## Autor

Bryan Espinoza
Milton Robles
