# Sesiones Prácticas
**Autores:** 
Julián Isaza Marín [julian.isazam@udea.edu.co]() / 
Paulina García Aristizábal [paulina.garcia1@udea.edu.co]()<br>
## Práctica 1: Definición de la base de datos y visualización básica
### Descripción general
Este proyecto presenta un análisis exploratorio de datos pertenecientes a una base de datos de propiedades en renta en distintas ciudades de la india.

El objetivo principal es identificar patrones, tendencias y relaciones entre las variables que influyen en el precio de renta tales como:

<li>Ciudad (city)</li>
<li>Tamaño del inmueble (Size en sqft)</li>
<li>Número de habitaciones (BHK)</li>
<li>Estado de amueblado (Furnishing Status)</li>
<li>Precio de renta(rent)</li><br>

A través de diferentes visualizaciones como Histogramas, Boxplots y Regplots; con el fin de analizar distribuciones, valores atípicos y posibles correlaciones entre variables.

### Instrucciones para ejecutar el notebook
1. Subir el archivo `.ipynb` del proyecto a Colab o abrirlo desde GitHub.
2. Ejecutar la celda inicial donde:
   <li> Se importan librerías</li>  
   <li>Se descarga el dataset desde Kaggle</li>
   <li>Se crea la carpeta `data` </li>
   <li>Se crea el archivo donde va a estar la base de datos</li>
   <li>Se carga el dataset con pandas</li>
3. Ejecutar las demás celdas en orden para reproducir el análisis exploratorio y las visualizaciones.

### Dependencias Requeridas
Este notebook utiliza dependencias como: `numpy`, `pandas`, `matplotlib`, `seaborn`, `kagglehub`, `os`, `shutil` y `warnings`, las cuales en Colab la mayoría ya vienen instaladas.
