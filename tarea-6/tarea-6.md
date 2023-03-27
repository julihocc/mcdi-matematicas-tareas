# TAREA 6

* Unidad: Introducción a la probabilidad
* Materia: Matemáticas para Ciencia de Datos
* Programa: Maestría en Ciencia de Datos e Información, INFOTEC
* Docente:  Juliho Castillo Colmenares, Sc.D.

## Lectura asignada

Taha, H. A. (2017). Operations Research an Introduction. United Kingdom: Pearson. Chapter 14, "Review of Basic Probability".

## Instrucciones

1. Organízate con los miembros de tu equipo para comentar la lectura y la tarea.
2. Resuelvan el siguiente problema, desarrollando de manera clara y concisa todos y cada unos de los puntos.
3. Transcríbanlo a un archivo PDF utilizando un editor de textos y suban un único archivo por equipo. 
4. No se aceptarán trabajos escritos a mano, aun cuando estén digitalizados. 
5. Puedes utilizar software para resolver los problemas, pero en este caso deberás incluir el código en tu documento.
6. En cualquier caso, incluye el desarrollo completo de la solución. No se aceptarán respuestas sin justificación. 
7. Se considerará un inciso como incorrecto si el resultado no es el esperado, y se considerará incompleto si el resultado no está debidamente justificado.
8. 

Planteamiento del problema

María von Savant es conocida por haber resuelto un problema de probabilidad en la columna "Ask Marilyn" de la revista Parade en 1990. El problema se llamaba "El problema de Monty Hall", y se basaba en un juego de televisión llamado "Let's Make a Deal" en el que un concursante debe elegir una de tres puertas, detrás de una de las cuales hay un premio, mientras que las otras dos puertas esconden algo sin valor. Después de que el concursante elija una puerta, el presentador, Monty Hall, que sabe qué hay detrás de cada puerta, abrirá una de las dos puertas restantes que no ha sido elegida por el concursante, revelando que no hay un premio detrás de ella. Luego, Monty le ofrece al concursante la oportunidad de cambiar su elección original por la otra puerta restante.

El problema se preguntaba si era mejor para el concursante cambiar su elección original después de que Monty abriera una puerta sin premio. Muchas personas intuitivamente creen que no importa si cambian o no, y que tienen una probabilidad del 50% de ganar el premio independientemente de lo que hagan. Sin embargo, Maria von Savant argumentó que cambiar de puerta duplica las posibilidades de ganar, y que la probabilidad de ganar si se cambia de puerta es del 2/3, mientras que si se mantiene la elección original, la probabilidad de ganar es del 1/3.

La respuesta de von Savant causó controversia en ese momento, y algunos matemáticos y estadísticos se opusieron a ella, argumentando que estaba equivocada. Sin embargo, con el tiempo se ha demostrado que su respuesta es correcta y que el cambio de puerta en realidad aumenta las posibilidades de ganar el premio.

La respuesta de von Savant al problema de Monty Hall puede ser demostrada mediante el uso de la teoría de probabilidad y la ley de Bayes. A continuación se presenta una explicación de cómo se puede llegar a la conclusión de que cambiar de puerta aumenta las posibilidades de ganar el premio:

Primero, es importante reconocer que hay tres posibles puertas que el concursante puede elegir, y solo una de ellas contiene el premio. Por lo tanto, la probabilidad inicial de ganar el premio es del 1/3.

Después de que el concursante hace su elección inicial, el presentador Monty Hall abre una de las dos puertas restantes que no tienen el premio detrás. Esto no cambia la probabilidad de que la puerta elegida por el concursante contenga el premio, que sigue siendo del 1/3.

Sin embargo, el hecho de que Monty abra una de las dos puertas restantes proporciona información adicional al concursante. En particular, revela que una de las puertas restantes no tiene el premio detrás. Como resultado, la probabilidad de que la puerta no elegida por el concursante contenga el premio se convierte en 2/3, ya que solo hay dos posibles puertas que no han sido elegidas.

Por lo tanto, si el concursante cambia de puerta después de que Monty haya abierto una de las dos puertas restantes, la probabilidad de ganar el premio aumenta a 2/3. Si el concursante decide quedarse con su elección original, la probabilidad de ganar sigue siendo del 1/3.

En resumen, la respuesta de von Savant es correcta porque si el concursante cambia de puerta después de que Monty abra una de las dos puertas restantes, la probabilidad de ganar el premio aumenta del 1/3 inicial a 2/3. Esta conclusión se puede demostrar matemáticamente utilizando la teoría de probabilidad y la ley de Bayes.

A continuación, diseñarás un experimento numérico que verifique el resultado anterior. 

### Inciso A

Escribe una función para similar un juego de Monty Hall que realice las siguientes instrucciones:

1.   Crea un lista con las tres puertas
2.   Escondemos el premio detrás de una de las puertas de manera aleatoria    
3.   Monty abre una puerta que no tiene el premio ni ha sido elegida por el concursante
4.   Si el concursante cambia de puerta, elegimos la puerta que no ha sido elegida y que no ha sido abierta por Monty
5.   Si el concursante cambia de puerta, elegimos la puerta que no ha sido elegida y que no ha sido abierta por Monty 
6.   Devolvemos True si el concursante ha ganado el premio, False en caso contrario 

### Inciso B

1.   Escribe una función para simular varios juegos de Monty Hall y calcular la probabilidad de ganar el premio
2.   Simula 10,000 juegos de Monty Hall
3.   Calcula la probabilidad de ganar el premio sin cambiar de puerta
4.   Calcula la probabilidad de ganar el premio cambiando de puerta

## Notas

1.   Calcula las probabilidades de manera separada, de manera que verifiques que la suma de ambas es 100%. 
2.   Las probabilidades obtenidas en la simulación deben ser muy cercanas a las que se predicen teóricamente. 

