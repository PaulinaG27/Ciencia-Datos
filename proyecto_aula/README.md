# Análisis exploratorio de los factores determinantes del precio de arrendamiento residencial en India

## Descripción general
Este proyecto aplica las tres primeras fases del marco CRISP-DM sobre el 
House Rent Prediction Dataset, un conjunto de datos públicos con 4.746 
registros de propiedades en arrendamiento en seis ciudades de India: Mumbai, 
Delhi, Bangalore, Hyderabad, Chennai y Kolkata.

El análisis incluye:
- Análisis exploratorio univariado, bivariado y multivariado
- Detección de outliers mediante estrategia de consenso (IQR, Z-score, 
  Isolation Forest y LOF)
- Imputación de valores faltantes con KNN Imputer
- Transformación logarítmica, escalamiento estándar y codificación 
  de variables categóricas

Los resultados se documentan en el manuscrito `articulo.pdf`, elaborado 
en formato de artículo científico.

## Instrucciones para ejecutar el notebook
1. Abrir el archivo `sp_final_Julian_Isaza_Marin_Paulina_Garcia_Aristizabal.ipynb` 
   en Google Colab
2. Ejecutar la celda 0 para instalar `kagglehub` y descargar el dataset 
   automáticamente desde Kaggle
3. Ejecutar las celdas en orden secuencial de principio a fin
4. Los resultados, gráficos y tablas se generan inline en el notebook

> **Nota:** Se requiere una cuenta de Kaggle activa para la descarga 
> automática del dataset vía `kagglehub`.

## Autores
| Nombre | Correo institucional |
|---|---|
| Julián Isaza Marín | julian.isazam@udea.edu.co |
| Paulina García Aristizábal | paulina.garcia1@udea.edu.co |

**Curso:** Fundamentos de Ciencia de Datos  
**Facultad de Ingeniería — Universidad de Antioquia, 2026**  
**Docente:** María Bernarda Salazar Sánchez, Ph.D.

## Dependencias y librerías requeridas
| Librería | Uso |
|---|---|
| `pandas` | Manipulación y análisis de datos |
| `numpy` | Operaciones numéricas |
| `matplotlib` | Visualización base |
| `seaborn` | Visualización estadística |
| `scipy` | Pruebas estadísticas (KS, Shapiro-Wilk, Kruskal-Wallis) |
| `scikit-learn` | PCA, KNN Imputer, Isolation Forest, LOF |
| `kagglehub` | Descarga automática del dataset |

Instalación:
```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn kagglehub
```

## Dataset
**House Rent Prediction Dataset** — Sourav Banerjee (2022)  
https://www.kaggle.com/datasets/iamsouravbanerjee/house-rent-prediction-dataset
