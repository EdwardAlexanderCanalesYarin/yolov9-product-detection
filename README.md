# YOLOv9 Product Detection — Fine-tuning para Retail

Fine-tuning de YOLOv9 para detección multi-clase de productos 
en carrito de supermercado, desarrollado como proyecto del curso 
Computación Gráfica (UNI, 2024).

## Dataset
- Fuente: Roboflow
- 6 clases: bottles, clothes, fruits, snacks, vegetables, background

## Pipeline
- Descarga de pesos preentrenados (yolov9-e.pt)
- Entrenamiento: 25 épocas, batch 8, imagen 640px, GPU (Google Colab)
- Validación: mAP con IoU 0.7, matriz de confusión
- Inferencia en imagen y video

## Tecnologías
YOLOv9 · Roboflow · Google Colab · Python
