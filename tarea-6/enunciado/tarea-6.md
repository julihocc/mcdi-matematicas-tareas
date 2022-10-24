# TAREA 6

* Unidad: Introducción a la probabilidad
* Materia: Matemáticas para Ciencia de Datos
* Programa: Maestría en Ciencia de Datos e Información, INFOTEC
* Docente:  Juliho Castillo Colmenares, Sc.D.

## INSTRUCCIONES

1. Completa las lecturas propuestas para esta actividad y reúnete con los miembros de tu equipo para comentar las lecturas y la tarea.
3. Resuelvan el siguiente problema, desarrollando de manera clara todos y cada unos de los puntos.
4. Si incluyes bloque de código, coméntalos de manera concisa, enfatizando su relación con la solución.
5. Detalla la información auxiliar de las gráficas para que tu conclusión sea clara.  
6. Organiza tu documento, escribe de manera explícita el enunciado de cada inciso y sepáralos utilizando secciones.
7. Transcríbanlo a un archivo PDF y suban un único archivo por equipo. 
8. Se considerará un inciso como incorrecto si el resultado no es el esperado, y se considerará incompleto si el resultado no está debidamente justificado.


## PROBLEMA

Vamos a simular el siguiente juego: De una baraja inglesa, se selecciona una mano (5 cartas, sin reemplazo). Si la mano es no es un full-house pierdes $1.5, pero si la mano es un full-house, la casa te paga un monto acordado.

*Para realizar tus simulaciones emplea el paquete `Numpy`. De manera particular, si utilizas números (pseudo-aleatorio), fija el generador usando la línea de código `numpy.random.seed(0)`.*

### Inciso A

¿Cuál sería un monto justo para que tu ganancia esperada sea cero? Determina una cantidad justificando tu respuesta.

*Sugerencia: [Revisa la lista de manos de póquer que se encuentra en la Wikipedia](https://es.wikipedia.org/wiki/P%C3%B3quer).* 

### Inciso B

Define una función que realice una simulación de 10,000 de manos; y devuelva la frecuencia absoluta con la que aparece un **full** (*full house* en inglés). 

### Inciso C

Repite la simulación 1000 veces y registra los resultados. Con esta información, crea un histograma que refleje la frecuencia absoluta de cada resultado. 

### Inciso D

Con la información anterior, calcula la media y la desviación estándar de las ganancias de todas las simulaciones. Interpreta este resultado usando la [regla empírica.](https://en.wikipedia.org/wiki/68%E2%80%9395%E2%80%9399.7_rule)

### Inciso E

Determina un valor $P_5$ en el rango de los resultados de tu simulación tal que, aproximadamente, el 5% de los resultados sean menores o iguales que este valor, y calcula la ganancia o perdida esperada para este valor. Interpreta este resultado en términos del [VaR (Value at Risk, por sus siglas en inglés).](https://en.wikipedia.org/wiki/Value_at_risk)

*Nota: Al valor $P_5$ se le llama 5-percentil*.



