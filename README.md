#  🖼️ Convertir Pintura en Imagen Usando Redes Generativas Antagónicas Condicionales (cGAN)
Este proyecto utiliza una red generativa antagónica condicional (cGAN) para transformar pinturas en imágenes realistas, aplicando técnicas avanzadas de visión por computadora y aprendizaje profundo. Las pinturas de las imágenes fueron realizadas con apoyo de la librería cv2 para posteriormente ser guardadas en una carpeta y realizar el entrenamiento del modelo neuronal.

![Resultados del Modelo](results/output_model_1.png)
![Resultados del Modelo](results/output_model_2.png)
![Resultados del Modelo](results/output_model_4.png)


## 📖 Descripción del Proyecto
El proyecto implementa un modelo cGAN para realizar la tarea de transformar pinturas simples en imágenes detalladas y realistas. Utiliza técnicas de procesamiento de imágenes, redes neuronales profundas y frameworks modernos para optimizar el rendimiento del modelo.

### 🛠 Tecnologías Utilizadas
- Red Neuronal: Conditional GAN (cGAN).
- Lenguaje de Programación: Python (Jupyter Notebook).
- Librerías:
    - Numpy
    - Matplotlib
    - PIL (Python Imaging Library)
    - PyTorch
    - TensorFlow
    - tqdm
    - os

### 🎯 Características Principales
- Conjunto de Datos:
    - Imágenes sin augmentation: 150
    - Imágenes con augmentation (Rotación, Rotación Horizontal y Blur): 450
    - Total imágenes: 600
    - Imágenes para entrenamiento: 500
    - Imágenes para test: 100
    - Tamaño Batch: 1
    - Tasa de Aprendizaje: 2e-4
    - Épocas: 5000

- Transformación de imágenes originales a pintura con cv2:
    - Filtro Bilateral (cv2.bilateralFilter)
    - Detección de Bordes (cv2.Canny)
    - Combinar efectos para resultado (cv2.bitwise_and)


### 📦 Instalación

```
# Clonar el Repositorio
git clone https://github.com/DonLuisM/Vehicles_detection_YOLO.git
```

### 🚀 Próximos Pasos

- Mejorar la calidad de las imágenes generadas con técnicas avanzadas de ajuste de hiperparámetros y batchsize.
- Incrementar el conjunto de datos de entrenamiento para lograr resultados más consistentes.

### 🤝 Contribuciones
¡Las contribuciones son bienvenidas! Si deseas colaborar en este proyecto, siéntete libre.