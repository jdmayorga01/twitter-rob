# Twitter-rob: Caracterización de los robos en Bogotá utilizando el API de Twitter 

En el año 2021 aumentaron los delitos en Colombia y no solo es una cuestión de percepción. Según la Corporación Excelencia en la Justicia (CEJ), el hurto a personas para el año 2021 fue de 166.858 casos, lo que representa alrededor de 687 hechos cada día, un aumento de casi el 30% con respecto al año pasado. Esto es preocupante porque muestra que la inseguridad ha crecido, especialmente en las ciudades. Por ejemplo, según el CEJ, en Bogotá se presentaron el 37% de los hurtos de celulares del país, lo cual es una cifra alarmante. 

Adicionalmente, además del efecto de la pandemia, existe una fuerte percepción de que los migrantes han sido responsables del aumento de los robos en el país. Esto es un sentimiento que incluso la alcaldesa Claudia Lopez en múltiples ocasiones a promovido. Sin embargo, según El Tiempo, en 2020 los venezolanos solo representaron el 2% de los hurtos en Bogotá. Por tanto, es importante explorar mas a fondo si esto es una percepción general o solo para un grupo especifico de la población.
Por lo tanto, este proyecto utilizará la API de Twitter para descargar tweets relacionados a robos en Bogotá y buscará caracterizarlos para dar respuesta a las siguientes preguntas: 

-	¿Cuál es la percepción de los bogotanos con respecto a los robos? – análisis de sentimientos
-	¿Cuáles son las palabras mas comunes a la hora de hablar de robos?
-	¿En que momento se comparten más tweets relacionados a robos? Esto es importante porque puede dar una percepción de las horas mas críticas de la inseguridad en la ciudad.
-	¿La migración cómo responsable? El 15 de septiembre de 2021 la alcaldesa Claudia Lopez culpó a los venezolanos por ola de inseguridad en Bogotá. ¿Este sentimiento es compartido por los ciudadanos? 

Algunas de las metodologías que serán utilizadas para este proyecto serán las siguientes: 
1.	Twitter API para descargar datos de los tweets publicados por los bogotanos. 
2.	Análisis de texto (Regex) para limpiar y análisis los textos de lo tweets
3.	Procesamiento y análisis en pandas 
4.	Hacer mapas en QGIS para ubicar las direcciones de los robos que son publicados en Twitter. 
