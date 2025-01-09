## Introducción.

La industria de drones se encuentra en crecimiento constante. Según un estudio publicado en la página de “statista.com”,  el mercado en México creció 20 veces de 2016 a 2019. En este reporte con datos extraídos el día 23 de Octubre de 2023 analizaremos las características de los drones más vendidos y los mejor puntuados en Mercado Libre.

## Metodología.

Se realizo Web Scrapping al catálogo de Mercado Libre utilizando la herramienta Beautiful Soup de Python con lo cual se extrajeron datos como el precio, puntaje, ventas y características del drone como la resolución de la cámara, si es FPV o no, etc... Con lo cual se construyo un dataset de 500 productos que fueron analizados mediante Pandas y SQL queries. Finalmete se utilizó Power BI y DAX para el reporte.

## Resultados.

Algunos resultados remarcables son que el precio de los 2 más vendidos es de $400 y el promedio de los 18 más vendidos de $798. Sin embargo el presente análisis nos muestra que la correlación entre precio y ventas en general es del 4.2% a favor de los más baratos. Finalmente la relación calidad ventas es de solo el 5%. Lo que significa que mejorar la calidad no mejora las ventas. De hecho la gamma baja vende más. 

Nota: Para poder visualizar el reporte es necesario tener instalado Power BI y descargar el archivo cleaned_drones.csv en la carpeta Documentos.

Puedes ver el reporte completo aquí: https://app.powerbi.com/view?r=eyJrIjoiNTZiZDEzOWEtZTY2OC00NzliLTlkZmMtN2QxMDI5YzQ2N2I0IiwidCI6ImE4MGU0MjRhLTUzYzMtNGJlYS04NzdhLTc1YmZkMDZlZjIwMyJ9
Y una explicación de como se creo aquí: https://github.com/itzecloud/Analisis-Drones-en-Mercado-Libre/blob/main/Estudio%20de%20Mercado%20sobre%20Drones..pdf

![foto5](https://github.com/user-attachments/assets/02634892-b91a-4ee1-a4ad-d6a64efd6a9e)
![foto6](https://github.com/user-attachments/assets/a57f5aff-f7f3-4f14-9f10-597062b4658b)
![foto7](https://github.com/user-attachments/assets/a32b270d-d73b-416f-a764-8eb913a4bd00)
