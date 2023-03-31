

### Lab 8

#### Desarrollado por:
- Alejandro Gómez
- Roberto Vallecillos
- Paola de León

#### Respuestas a las preguntas del lab:
 
##### Número de clusters: 

El número de clusters seleccionado fue: 3


##### ¿Podría PCA ayudarle a mejorar sus clusters? ¿Por qué?

En este caso, podemos decir que el PCA podría llegar a reducir la complejidad del algoritmo pues, aunque contemos con la misma cantidad de muestras, se unifican variables para reducir la cantidad de dimensiones del mismo.

Esto debido a que mediante el PCA eliminamos redundancia y hace que las variables sean más relevantes para la contrucción de los clusters; lograndolos definir de una forma más clara y precisa.


##### Gráfico que muestre como se dividen los datos en los clusters:

El gráfico que se realizó para mostrar como se divideron los datos en clusters fue: plot_contours.

Este gráfico es comunmente utilizado para la visualización de diferentes cartegorías en un espacio bidimensional.


##### Features seleccionados: 

Se seleccionaron los siguientes features:
 __ CustAccountBalance
 __ TransactionAmount (INR)

 Se eligieron las mismas después de analizar el contexto de la información y observar los datos; calculando la correlación entre variables y su significacia.


##### Investigación de PCA:

Como se mencionó anteriormente, PCA es una algoritmo para la reducción de dimensiones de un modelo. Mediante este algoritmo se busca unificar features para evitar la redundancia o el hacer un análisis con variables irrelevantes. Esto es logrado através de una transformación de los datos originales a conjunto de variables no correlacionadas que explican la mayor cantidad posible de la variabilidad de los datos originales.


##### Métrica de desempeño y justifcación:

Para este laboratorio se seleccionó la siguiente métrica de desempeño: log likelihood.

Esta métrica evalúa la calidad del modelo y nos dice qué tan bien se ajusta el mismo a los datos.

##### Comparación con resultados del lab 7:

- ¿Cúal es mejor? ¿Por qué?

##### ¿Cuándo usar Mixture Models y K-Means?

##### ¿Cuál implementación fue mejor? ¿Por qué? (Responda como parte del readme de su repositorio)
