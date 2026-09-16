# Laboratorio de IA ética

El notebook [main.ipynb](main.ipynb) desarrolla un modelo base de supervivencia del Titanic con un pipeline de preprocesamiento y Random Forest.

## Ejecución en Google Colab

[Abre el notebook en Colab](https://colab.research.google.com/github/memo124/Laboratorio_IA_etica/blob/main/main.ipynb) y ejecuta las celdas en orden. La primera celda de código instala las dependencias adicionales para el encoding y la búsqueda con Optuna.

El notebook lee `train.csv` desde el directorio de trabajo; si no existe, lo descarga desde el dataset público de Data Science Dojo y guarda una copia en el entorno de ejecución.

Los datos se dividen en entrenamiento (60 %), validación (20 %) y prueba (20 %). El preprocesamiento se ajusta solo con entrenamiento y el modelo se evalúa sobre validación; prueba queda reservado para una evaluación final posterior.
