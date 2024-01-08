# Práctica III de Inteligencia Artificial

### Objetivo de la práctica: 
Predicción de resultados a partir de datos preseleccionados suficientes como para aplicar algoritmos de aprendizaje automático.

## 1/ Elección del problema:
###### Detección del modelo óptimo de coche para un cliente que busque unas características concretas del vehículo en base a unas necesidades específicas.


## 2/ Fuente de datos seleccionada:
Podrá acceder a los datos empleados en la práctica aquí: [Link a la fuente de datos](https://github.com/lpfgarcia/ucipp/blob/master/uci/car-evaluation.arff).


### 3/ Identificación de los atributos y características relevantes de los mismos:

*  buying       v-high, high, med, low
*  maint        v-high, high, med, low
*  doors        2, 3, 4, 5-more
*  persons      2, 4, more
*  lug_boot     small, med, big
*  safety       low, med, high

### 4/ Ubicación de los archivos .arff :

Al abrir la carpeta podrá consultar los datos siguiendo la siguiente ruta:
[serializacionUsoModeloWeka/training_data/car-evaluation.arff]().

Siguiendo la ruta que se le proporciona a continuación podrá acceder al archivo test:
[serializacionUsoModeloWeka/test_data/testCarEv.arff]().

### 5/ Algoritmos trabajados:

| Algoritmo  | Observaciones destacadas |
| ------------- |:-------------:|
| J48     | Con el modelo original de datos se encontraron errores en el balanceo de datos por lo que se tuvo que balancear el archivo.|
|   NaiveBayes    |  No se observaron muchos cambios con respecto al modelo anterior.  |
| Random Forest     | A modo de comprobación empleamos Random Forest para realizar comparaciones con respecto a los datos anteriormente obtenidos. |

> La ubicación de los objetos persistentes creados se encuentra en la siguiente carpeta:
>
>> [serializacionUsoModeloWeka/models]().

![](![](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png){width='100px'}){width='100px'}
