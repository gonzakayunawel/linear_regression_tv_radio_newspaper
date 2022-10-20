# Modelo de Regresión Lineal Simple usando ScikitLearn

# Regresión Lineal Simple

La regresión lineal simple consiste en generar un modelo de regresión (ecuación de una recta) que permita explicar la relación lineal que existe entre dos variables. A la variable dependiente o respuesta se le identifica como Y y a la variable predictora o independiente como X.

![](https://i.imgur.com/r0WJWB8.png)

### Correlación lineal

Para estudiar la relación lineal existente entre dos variables continuas es necesario disponer de parámetros que permitan cuantificar dicha relación.

Para ello calculamos el coeficiente de Correlación R de Pearson, el cual nos explica cuanta relación tienen ambas variables.

Siendo +1 una correlación positiva perfecta y -1 una correlación negativa perfecta.

Se emplean como medida de fuerza de asociación (tamaño del efecto):

*   0: asociación nula.
*   0.1: asociación pequeña.
*   0.3: asociación mediana.
*   0.5: asociación moderada.
*   0.7: asociación alta.
*   0.9: asociación muy alta.

### Problema modelado

El departamento de ventas de una empresa quiere estudiar la influencia que tiene la publicidad a través de distintos canales sobre el número de ventas de un producto. Se dispone de un conjunto de datos que contiene los ingresos (en millones) conseguido por ventas en 200 regiones, así como la cantidad de presupuesto, también en millones, destinado a anuncios por radio, TV y periódicos en cada una de ellas.

Se realizan 3 modelos de regresión lineal simple para comparar las alternativas.

### Módulos

Se utilizan los módulos Pandas, Numpy, Matplotlib y ScikitLearn.

### Conclusión
Desde el punto de vista de los modelos analizados, se concluye que desde una perspectiva lineal, la inversión que se haga en el Presupuesto de TV tiene un mejor ajuste, y con este modelo es más preciso predecir cuanto sería el ingreso esperado, no obstante, no es posible excluir de la inversión a los otros modelos debido a que existe la posibilidad de que otros modelos de regresión y/o algoritmos se ajusten mejor a dichos datos y nos permitan obtener un mayor retorno sumado a una mejor precisión.
Sin embargo, con la información disponible, se recomienda invertir en el Presupuesto de TV en primera instancia.

