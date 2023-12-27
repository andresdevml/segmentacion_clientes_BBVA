# Segmentación de clientes BBVA 🏦

A través de un resumen de los movimientos de los clientes del banco y otras características ( excluyendo la rentabilidad ). Se realizó una segmentación en pocos grupos, cuyas rentabilidades son diferenciadas entre ellos pero comunes a miembros del mismo grupo. 

Los resultados podrían ser útiles para mejorar la oferta de productos y servicios bancarios, así como para diseñar estrategias de marketing personalizadas.

# Herramientas 🛠️

* Python
* Pandas
* Numpy
* Matplotlib
* Umap
* Sklearn

#  Limpieza e Ingeniería de características  ⚙️

En primera instancia es necesario limpiar el dataset provisto. Ya que contamos con una gran cantidad de datos es factible eliminar aquellas instancias que tengan datos faltantes para una primera aproximación. Posteriormente se podrán llenar los espacios faltantes con la media o la mayoría de la columna respectiva. 

Además es necesario realizar la ingeniería de características, transformando la data al espacio de representación numérico más idóneo para su posterior procesamiento.

# Segmentación 🔮

Con la data correctamente tratada, aplicamos un algoritmo de Machine Learning especializado en la separación de grupos, denominado UMAP por sus siglas en inglés (Uniform Manifold Approximation and Projection). Posteriormente definimos los clusters a través de DBSCAN. Todo este proceso, junto con el tratamiento de los datos, puede seguirse en el Notebook _**segmentacion_graficos.ipynb**_.

![clusters](https://github.com/huachibigote/segmentacion_clientes/assets/61852105/d2c37078-35fd-4500-a1e0-c3f74b1cf2ac)

Calculando el ratio de rentabilidad para cada grupo obtenemos que cada uno de los grupos posee una rentabilidad diferenciada. 

![rentabilidad](https://github.com/huachibigote/segmentacion_clientes/assets/61852105/d337a571-b147-4b08-963d-0ad23ea11adc)



