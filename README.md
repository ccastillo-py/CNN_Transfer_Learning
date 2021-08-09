# Caso práctico de Transfer Learning</br> 
### Clasificación de imágenes aplicando modelos convolucionales de referencia.
<p align="center">
<img src="https://www.researchgate.net/profile/Joseph-Lemley/publication/316748306/figure/fig2/AS:491777640669185@1494260334992/Illustration-of-transfer-learning-concept-where-the-rst-layers-in-network-A-and-network-B.png">
</p>
Partiendo del dataset “Dogs & Cats Images” de la plataforma Kaggle, se persigue generar modelos específicos a partir de la arquitectura de modelos convolucionales de referencia y, de este modo, realizar predicciones sobre las etiquetas de las imágenes que contiene para determinar si lo que se presenta se corresponde a un perro o a un gato. Se trata pues de un problema de clasificación binaria.</br> 
</br> 
Los modelos de referencia utilizados para la confección del transfer learning son:</br> 

- VGG16, red con más de 138 millones de parámetros
- MobilNet V2, red con más de 3,5 millones de parámetros
- ResNet V2, red con 23,5 millones de parámetros</br> 
