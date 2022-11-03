#  Implementación de un modelo de deep learning
### Anotaciones de los modelos

Se realizaron las clasificaciones de los datasets presentados en dos modelos diferentes, uno previamente configurado disponible en el hub de tensorflow,

así como también uno con la arquitectura desde 0, así como ligeros ajustes de hiperparametros y validaciones de los distintos subsets, se eligieron aquellos que presentaron mejores resultados,

Cabe aclarar que me pareció interesante la idea de probar con dos data sets difreferentes con la finalidad de ver la afectación que estos podían presentar en el accuracy,

en el caso de los pandas contra osos, sin duda se muestra un mejor resultado y esto puede deberse a que las fotos de los pandas y osos realmente son de clasificación binaria,

ya que no se presentan diferencias significativas en cuanto a los tipos de pandas y osos entre sí, es decir un panda no es muy diferente de otro panda,

mismo caso para los osos.

Pero en el caso de los perros y gatos, realmente se tienen muchas diferencias entre los tipos de gatos y perros que existen, por lo tanto, es mucho más difícil conseguir un mejor performance del modelo,

ya que se tiene que fijar en muchos más patrones, teniendo aun así esto en cuenta, la verdad es que los resultados fueron bastante satisfactorios.
