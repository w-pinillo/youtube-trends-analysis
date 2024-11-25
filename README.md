# YouTube Video Popularity Prediction
## Descripción del Proyecto
Este proyecto tiene como objetivo analizar los videos más populares en YouTube a través de un conjunto de datos que contiene registros diarios de los videos más tendencias de diferentes países. YouTube selecciona los videos más populares utilizando una combinación de factores como vistas, comentarios, compartidos y "likes". Sin embargo, estos videos no son necesariamente los más vistos de todo el año, sino aquellos que destacan por su tendencia durante un periodo específico.

El análisis se enfoca en explorar las características de los videos que influyen en su popularidad y en la creación de un modelo predictivo para estimar la cantidad de vistas o "likes" de los videos en función de estas características.

## Descripción del Conjunto de Datos
El dataset contiene información detallada sobre los videos más populares de YouTube, recopilada diariamente. Los datos incluyen variables como:

Título del video.
Número de vistas.
Número de "likes" y "dislikes".
Número de comentarios.
Fecha de publicación.
Categoría del video (e.g., música, entretenimiento, educación, etc.).
País de tendencia.
Este conjunto de datos permite analizar no solo el desempeño de los videos, sino también identificar patrones y características que los hacen destacar.

## Modelo Utilizado
Para abordar el problema de predicción de visitas en videos, se utilizó un modelo de regresión basado en un Perceptrón Multicapa (MLP). Este modelo de red neuronal fue entrenado utilizando el optimizador Adam con tasas de aprendizaje de 0.01, 0.03 y 0.05.

Los resultados obtenidos muestran que el modelo con una tasa de aprendizaje de 0.05 fue el más efectivo, alcanzando un valor de R² de 0.6636. Esto indica que el modelo explica el 67% de la variabilidad en los datos, lo que sugiere que las predicciones de visitas están bastante cerca de los valores reales. El Error Cuadrático Medio (MSE) es relativamente bajo, lo que refleja la capacidad predictiva del modelo.

## Objetivo del Análisis
El objetivo principal de este análisis es explorar las características de los videos más populares en YouTube y su relación con las interacciones de los usuarios. Específicamente, buscamos responder las siguientes preguntas:

¿Cuáles son las categorías de videos que reciben más vistas y "likes"?
¿Es posible encontrar patrones o agrupaciones entre los videos más populares?
¿Qué combinaciones de características (por ejemplo, duración del video, categoría, fecha de publicación) influyen en que un video se vuelva tendencia?
¿La temporada o fecha de publicación tiene alguna influencia en la popularidad de los videos?
¿Es posible predecir la cantidad de vistas o "likes" que un video tendrá en función de sus características?
Resultados Esperados
A través de este proyecto, se espera desarrollar un modelo predictivo capaz de estimar con razonable precisión las vistas o "likes" que un video en YouTube puede generar, basándose en las características que se recopilan en el dataset. Este modelo servirá como una base para comparar otros enfoques y mejorar la comprensión de qué hace que un video se vuelva popular en la plataforma.