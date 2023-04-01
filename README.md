
![UVG](https://res.cloudinary.com/webuvg/image/upload/f_auto/v1551291412/WEB/institucional/logouvg.png) <br>
Facultad de Ingeniería <br>
Departamento de Ciencias de la Computación <br>
CC3085 Inteligencia Artificial <br>


# IA_Laboratorio1

- ¿Podría PCA ayudarle a mejorar sus clusters? ¿Por qué?

La técnica de análisis de componentes principales (PCA) puede mejorar la agrupación de datos en modelos de mezcla, que son utilizados para identificar grupos en datos multivariados. La reducción de la dimensionalidad a través de PCA puede facilitar la identificación de patrones y agrupaciones en los datos, además de mejorar la interpretación y eficiencia computacional del modelo de mezcla. Sin embargo, es importante tener en cuenta que la reducción de dimensionalidad puede llevar a una pérdida de información en los datos y, en algunos casos, puede no mejorar la agrupación. Por lo tanto, es necesario realizar una evaluación cuidadosa del rendimiento del modelo después de la reducción de dimensionalidad. En este caso no podria ser debido a que cómo se puede apreciar en los gráficas de las tablas siguientes el modelo producido con la implementación sin librerias al tener definidos dos clusters se muestra en la gráfica su separación, pero cómo se puede apreciar, esta no tiene mayor diferencia debido a la manera en que trabaja Mixture Models, por lo que en general PCA si permite una mejora pero dependiendo del dataset con el que se este trabajando.

- Del laboratorio 8 ¿Cuál implementación fue mejor? ¿Por qué? 

En este caso se considera que la mejor implementación fue la de la libreria pero por detalles mínimos, en la tabla se puede apreciar que lo más marcado entre diferencias corresponde a la identifcación de centroides y unos cuantos clusters. Y esto se puede deber a la manera en que trabajo Mixture models que subidivide el dataset para luego alanizar estos y proeceder aplicarles un modelo para luego unificarlos, pero en este caso puede estar afectando el resultado debido a la manera en que los datos estan descritos y acumulados en la esquina inferior izquierda.

| Gráfica Laboratorio 8 sin librerias| Gráfica Laboratorio 8 con librerias |
|-----------|-----------|
| ![image](https://user-images.githubusercontent.com/60375344/229259903-e158fdd7-9cde-425c-8890-7d3deeb0736c.png) | ![image](https://user-images.githubusercontent.com/60375344/229258859-893af976-2b0d-44a1-9cde-4887f55f8a45.png)|

- Comparación de resultados con laboratorio 7

Al momento de comparar gráficas, estadisticas, scores y clusters, se puede apreciar que existe una diferencia significativa entre el Laboratorio 7 y 8. Basaandonoes en las gráficas de librerias para que el facto de error de implementación no venga al caso. Se puede apreciar en las siguientes gráficas que el la g del laboratorio 7 tiene mejores definiciones de clusters a comparación del laboratorio 8.

| Gráfica Laboratorio 7 | Gráfica Laboratorio 8 |
|-----------|-----------|
| ![image](https://user-images.githubusercontent.com/60375344/229258846-2d099356-221f-4ca1-80e9-588098b300eb.png) | ![image](https://user-images.githubusercontent.com/60375344/229258859-893af976-2b0d-44a1-9cde-4887f55f8a45.png)|


