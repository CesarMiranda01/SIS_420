#  LABORATORIO 5 EURISTICAS PARA RESOLVER ROMPECABEZAS
#  MIRANDA GUTIERREZ CESAR ALVARO

EL Primer ejercicio es el resuelve un numero N de elementos de un rompezabesas, pero aveces si sale muchos pasos
puede exceder la capacidad de resolucion.
Se usa la funcion random para generar un estado inicial del rompecabezas

La primera heurística cuenta el número de números que están en la posición final deseada. 
Esta heurística es la menos eficiente, ya que puede ser engañosa. Por ejemplo, el estado [1, 2, 4, 3] 
tiene una calidad de 2, mientras que el estado [1, 2, 3, 4] tiene una calidad de 4. Sin embargo, el estado [1, 2, 3, 4] es la solución al problema.

La segunda heurística suma la distancia entre cada número y su posición final deseada. 
Esta heurística es más eficiente que la primera, pero no tiene en cuenta la restricción 
de que los intercambios solo pueden hacerse con números adyacentes. Por ejemplo, el estado [1, 2, 4, 3]
tiene una calidad de 4, mientras que el estado [2, 1, 4, 3] tiene una calidad de 4. Sin embargo, el estado [2, 1, 4, 3] 
no es la solución al problema.

La tercera heurística suma la distancia entre cada número y su posición final deseada, 
y que tienen el valor correcto, y que tienen la posición incorrecta. Esta heurística es la más eficiente, 
ya que es más precisa y tiene en cuenta la restricción de que los intercambios solo pueden hacerse con números adyacentes. 
Por ejemplo, el estado [1, 2, 4, 3] tiene una calidad de 4, mientras que el estado [2, 1, 4, 3] tiene una calidad de 3. 
Sin embargo, el estado [2, 1, 4, 3] es un estado intermedio que conduce a la solución

GIT HUB:
https://github.com/CesarMiranda01/SIS_420/tree/main/LABORATORIOS/laboratorio5

DRIVE:
https://drive.google.com/drive/folders/1ge_p5Z53PyQYMCiX_uyTvcu9YkW5TEI7?usp=share_link


