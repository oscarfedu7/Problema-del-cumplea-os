# Problema-del-cumpleaños
El problema del cumpleaños, también llamado paradoja del cumpleaños, establece que de un conjunto de 23 personas, hay una probabilidad del 50,7% de que al menos dos de ellas cumplan años el mismo día. Para 57 o más personas la probabilidad es mayor del 99,666%.

En este código se da una solución haciendo muchas simulaciones y sacando los promedios de los miles de resultados dados.
Sacar la probabilidad usando combinatoria en muy sencillo, para n=23,  P = 1-((365*354*363*...*343)/(365^23)) = 50.7%.
Donde experimentalmente nos da un número muy cercano a 50.7 (por teorema del límite central).
