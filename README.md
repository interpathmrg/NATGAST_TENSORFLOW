# NATGAST_TENSORFLOW
Script de Python para demostrar el uso de Tensorflow y redes neuronales para predecir el precio del gas natural
# Modelo de Predicción del Precio del Gas Natural Usando Redes Neuronales

Este proyecto utiliza un modelo de red neuronal para predecir el precio del gas natural en función de varias características. El modelo está entrenado con datos de precios históricos mejorados, con el objetivo de predecir los precios de manera precisa utilizando técnicas de machine learning y deep learning.

**Desarrollado por**: Miguel Raúl González y ChatGPT4  
**Maestría**: ENEB - Inteligencia Artificial Aplicada  
**Fecha**: 10 Noviembre 2024  

### Dataset

- **Fuente**: [Kaggle - Natural Gas Prices](https://www.kaggle.com/datasets/joebeachcapital/natural-gas-prices?resource=download)
- El dataset fue mejorado con características adicionales (como medias móviles y etiquetas de tendencia) para mejorar el rendimiento del modelo.

### Descripción del Proyecto

Este modelo de red neuronal utiliza el dataset para aprender patrones históricos en los precios del gas natural y hacer predicciones. El modelo utiliza técnicas avanzadas como regularización L2 para evitar el sobreajuste, early stopping y un scheduler de tasa de aprendizaje para mejorar el proceso de entrenamiento. También incluye una función para calcular la importancia de cada característica mediante permutación, así como gráficos para evaluar el rendimiento del modelo.

---

## Instalación

### Requisitos

- Python 3.7 o superior
- Las siguientes bibliotecas de Python:

```bash
pip install pandas numpy scikit-learn tensorflow matplotlib
