## Introducción.

La industria de drones se encuentra en crecimiento constante. Según un estudio publicado en la página de “statista.com”,  el mercado en México creció 20 veces de 2016 a 2019. En este reporte con datos extraídos el día 23 de Octubre de 2023 analizaremos las características de los drones más vendidos y los mejor puntuados en Mercado Libre.

## Metodología.

Se realizo Web Scrapping al catálogo de Mercado Libre utilizando la herramienta Beautiful Soup de Python con lo cual se extrajeron datos como el precio, puntaje, ventas y características del drone como la resolución de la cámara, si es FPV o no, etc... Con lo cual se construyo un dataset de 500 productos que fueron analizados mediante Pandas y SQL queries. Finalmente los gráficos se realizaron mediante Plotly.

## Resultados.

Algunos resultados remarcables son que el precio de los 2 más vendidos es de $400 y el promedio de los 18 más vendidos de $798. Sin embargo el presente análisis nos muestra que la correlación entre precio y ventas en general es del 4.2% a favor de los más baratos. Finalmente la relación calidad ventas es de solo el 5%. Lo que significa que mejorar la calidad no mejora las ventas. De hecho la gamma baja vende más. 

![drones](https://github.com/itzecloud/Analisis-Drones-en-Mercado-Libre/assets/148586659/038a4064-8d69-4fe4-bff4-c54bcc9dc84b)
