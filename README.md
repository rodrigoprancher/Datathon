# Datathon

## Proyecto individual 2

En este proyecto hacemos una limpieza de datos y un modelo de Machine Learning para predecir si el precio de un inmueble del país de Colombia es caro o barato.

## Tecnologías usadas:

- Python.
- - Pandas. 
- - Numpy.
- - Geopandas.
- - Folium.
- - Seaborn.
- - cmath

## Limpieza

Durante el proceso de limpieza creamos una columna llamada 'target' la cual contiene los datos de la columna 'price', que esta contiene los precios de los inmuebles, pero con dos números que definen si son caros (1) o baratos (0).

Luego vemos la correlación entre las columnas: 'lat', 'lon', 'rooms', 'bedrooms', 'bathrooms', 'surface_total', 'sorface_covered' y 'target'.

<img width="428" alt="Captura de pantalla 2022-11-04 092817" src="https://user-images.githubusercontent.com/105827215/199972744-6556c126-b30f-4bfb-8aaa-3575069be97f.png">

También rellenamos valores nulos y sacamos los outliers que pueden hacer que falle nuestro modelo.
En las columnas 'lat' y 'lon' se encontraban dos outliers que daban como coordenada a Chile y Estados Unidos siendo estas removidas y quedando solo las coordenadas de Colombia. 

<img width="728" alt="asd" src="https://user-images.githubusercontent.com/105827215/199974696-1da94790-f421-4f84-817b-b96ff2ff9e88.png">
