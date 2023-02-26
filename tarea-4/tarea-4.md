# TAREA 4

* Unidad: Selección y calibración de modelos
* Materia: Matemáticas para Ciencia de Datos
* Programa: Maestría en Ciencia de Datos e Información, INFOTEC
* Docente:  Dr. Juliho Castillo Colmenares

## Lectura asignada

Del libro "Cai, X., Tveito, A., Langtangen, H. P., Nielsen, B. F. (2010). Elements of Scientific Computing. Germany: Springer Berlin Heidelberg", revisa el capítulo 4 "Nonlinear Algebraic Equations"

## Instrucciones

1. Organízate con los miembros de tu equipo para comentar la lectura y la tarea.
2. Resuelvan el siguiente problema, desarrollando de manera clara y concisa todos y cada unos de los puntos.
3. Transcríbanlo a un archivo PDF utilizando un editor de textos y suban un único archivo por equipo. 
4. No se aceptarán trabajos escritos a mano, aun cuando estén digitalizados. 
5. Puedes utilizar software para resolver los problemas, pero en este caso deberás incluir el código en tu documento.
6. En cualquier caso, incluye el desarrollo completo de la solución. No se aceptarán respuestas sin justificación. 
7. Se considerará un inciso como incorrecto si el resultado no es el esperado, y se considerará incompleto si el resultado no está debidamente justificado.
8. Para acreditar el punto correspondiente a cada inciso, este deberá estar completo y ser correcto.

## Planteamiento

### Inciso A

Establece $x_0=3$ y calcula $x_1,...,x_n$ en el método de Newton para aproximar la solución de 
$$
f(x) = 0,
$$
donde $f(x)=x^2-4$, de manera que el error absoluto entre las últimas iteraciones, es decir, $|x_{n-1}-x_n|$, sea menor a una tolerancia de $10^{-9}$. Imprime todos los valores y determina cuantas iteraciones son necesarias para alcanzar esta meta.

*Asegúrate que la solución de método de Newton realmente aproxime la solución exacta de la ecuación.*

### Inciso B

Crea una visualización de los resultados del método obtenidos en el inciso anterior. Utiliza como referencia la figura 4.5 en la lectura asignada.

### Inciso C
Establece $x_0=1$ y  y calcula $x_1,...,x_n$ en el método de Newton para aproximar la solución de 
$$
g(x) = 0,
$$
donde $g(x)=x^2$, de manera que el error absoluto entre las últimas iteraciones, es decir, $|x_{n-1}-x_n|$, sea menor a una tolerancia de $10^{-9}$. Imprime todos los valores y determina cuantas iteraciones son necesarias para alcanzar esta meta.

*Asegúrate que la solución de método de Newton realmente aproxime la solución exacta de la ecuación.*

### Inciso D
Crea una visualización de los resultados del método obtenidos en el inciso anterior. Utiliza como referencia la figura 4.5 en la lectura asignada. 

### Inciso E
Con base en los resultados anterior, determina que iteración converge más rápidamente y explica porque sucede esto.

