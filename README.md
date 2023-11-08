# Segmentación según rentabilidad de clientes (BBVA 🏦)

_A través de un resumen de los movimientos de los clientes del banco y otras características ( excluyendo la rentabilidad ). Se realizó una segmentación en pocos grupos, cuyas rentabilidades son diferenciadas entre ellos pero comunes a miembros del mismo grupo. 

Los resultados podrían ser útiles para mejorar la oferta de productos y servicios bancarios, así como para diseñar estrategias de marketing más efectivas y personalizadas._

# Herramientas 🛠️

* Python
* Pandas
* Numpy
* Matplotlib
* Umap
* Sklearn

#  Limpieza e Ingeniería de características  ⚙️

_En primera instancia es necesario limpiar el dataset provisto. Ya que contamos con una gran cantidad de datos es factible eliminar aquellas instancias que tengan datos faltantes para una primera aproximación. Posteriormente se podrán llenar los espacios faltantes con la media o la mayoría de la columna respectiva. 

Además es necesario realizar la ingeniería de características, transformando la data al espacio de representación numérico más idóneo para su posterior procesamiento._

# Segmentación 🔮

_Con la data correctamente tratada, aplicamos un algoritmo de Machine Learning especializado en la separación de grupos, denominado UMAP por sus siglas en inglés (Uniform Manifold Approximation and Projection). Posteriormente definimos los clusters a través de DBSCAN. Todo este proceso, junto con el tratamiento de los datos, puede seguirse en el NoteBook **segmentacion_graficos.ipynb**._
