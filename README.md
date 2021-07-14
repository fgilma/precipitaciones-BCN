
# Precipitaciones Barcelona (1920-2020)

Este proyecto analiza los datos sobre la lluvia caída en Barcelona en los últimos 100 años. El **objetivo principal** es evaluar si existen cambios en el comportamiento de las precipitaciones en las últimas dos décadas respecto a años anteriores.

Los datos proceden de la estación meteorológica del **Observatori Fabra** situado en la montaña del Tibidabo.


![Vista Barcelona desde Observatori Fabra](observatori.jpg)
## Plan de proyecto:

1. **Análisis exploratorio** 
- Se realiza un análisis a diferentes niveles de agregación: diario, mensual y anual. Para cada nivel se muestran sus valores **estadísticos típicos, boxplot e histograma.**
- A nivel diario se estudia además si han aumentado la frecuencia de días sin lluvia o las precipitaciones extremas en los últimos años.
- A nivel mensual se realiza también un **análisis multivariante** entre el nivel de precipitación y los meses del año para evaluar posibles diferencias entre periodos.
- Además, se muestra, por año, la **serie histórica** de las precipitaciones, su tendencia y estacionalidad.

2. **Clustering**
En este caso se usa el algoritmo **KMeans** a nivel mensual, para detectar similitudes entre los meses y agruparlos en clusters, analizando sus semejanzas y diferencias.

3. **Regresión**
Se aplican dos algoritmos distintos: **regresión lineal múltiple y Random Forest** para evaluar la capacidad de otras magnitudes, principalmente temperatura, presión y humedad relativa,  para explicar y predecir las precipitaciones.
4. **Conclusiones**
Resumen con los datos y resultados obtenidos.
