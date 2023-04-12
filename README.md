# Modelo para el análisis de sentimiento de reseñas de películas utilizando aprendizaje automático en la plataforma Film Junky Union

## Introducción

El uso de modelos de aprendizaje automático que clasifiquen texto se ha convertido en un tema de gran interés y está siendo ampliamente utilizado por muchas empresas que, a partir de clasificadores automáticos, reúnen información sobre textos o mensajes escritos en diferentes plataformas como Twitter o Facebook. Al entrenar estos modelo se puede llegar a saber cosas como si un mensaje es racista, si el texto habla de política o tecnología, o si un comentario es positivo o negativo, incluso hasta el idioma en que se encuentra un texto. 

Film Junky Union, una nueva comunidad vanguardista para los aficionados de las películas clásicas, está desarrollando un sistema para filtrar y categorizar reseñas de películas. Para lo cual, busca entrenar un modelo que permita detectar las críticas negativas de forma automática y distinguirlas de las críticas positivas. Se cuenta con un conjunto de datos de reseñas de películas de IMDB con leyendas de polaridad, a partir del cual se construirá un modelo para clasificar las reseñas positivas y negativas, utilizando el puntaje F1 para evaluar el rendimiento de los modelos. 

### Objetivos

1. Entrenar varios modelos de aprendizaje automático que clasifiquen reseñas positivas y negativas, utilizando diferentes alternativas de preprocesamiento de textos.
2. Establecer el mejor modelo que alcance un valor F1 de al menos 0.85.
