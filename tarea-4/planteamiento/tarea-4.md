# TAREA 4

* Unidad: Selección y calibración de modelos
* Materia: Matemáticas para Ciencia de Datos
* Programa: Maestría en Ciencia de Datos e Información, INFOTEC
* Docente:  Juliho Castillo Colmenares, Sc.D.

## INSTRUCCIONES

1. Del libro "Cai, X., Tveito, A., Langtangen, H. P., Nielsen, B. F. (2010). Elements of Scientific Computing. Germany: Springer Berlin Heidelberg", revisa el capítulo 4 "Nonlinear Algebraic Equations"
2. Reúnete con los miembros de tu equipo para comentar la lectura y la tarea.
3. Resuelvan el siguiente problema, desarrollando de manera clara todos y cada unos de los puntos.
3. Si incluyes bloque de código, coméntalos de manera concisa, enfatizando su relación con la solución. 
3. Organiza tu documento, escribe de manera explícita el enunciado de cada inciso y sepáralos utilizando secciones.
3. Transcríbanlo a un archivo PDF y suban un único archivo por equipo. 
4. Se considerará un inciso como incorrecto si el resultado no es el esperado, y se considerará incompleto si el resultado no está debidamente justificado.
5. Para acreditar el punto correspondiente a cada inciso, este deberá estar completo y ser correcto.

## PROBLEMA

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

