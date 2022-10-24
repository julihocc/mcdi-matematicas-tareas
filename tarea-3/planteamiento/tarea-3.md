# TAREA 3

* Unidad: Simulaciones
* Materia: Matemáticas para Ciencia de Datos
* Programa: Maestría en Ciencia de Datos e Información, INFOTEC
* Docente:  Dr. Juliho Castillo Colmenares

## INSTRUCCIONES

1. Del libro "Cai, X., Tveito, A., Langtangen, H. P., Nielsen, B. F. (2010). Elements of Scientific Computing. Germany: Springer Berlin Heidelberg", revisa el capítulo 3 "System of Ordinary Differential Equations"
2. Reúnete con los miembros de tu equipo para comentar la lectura y la tarea.
3. Resuelvan el siguiente problema, desarrollando de manera clara todos y cada unos de los puntos.
3. Si incluyes bloque de código, coméntalos de manera concisa, enfatizando su relación con la solución. 
3. Organiza tu documento, escribe de manera explícita el enunciado de cada inciso y sepáralos utilizando secciones.
3. Transcríbanlo a un archivo PDF y suban un único archivo por equipo. 
4. Se considerará un inciso como incorrecto si el resultado no es el esperado, y se considerará incompleto si el resultado no está debidamente justificado.
5. Para acreditar el punto correspondiente a cada inciso, este deberá estar completo y ser correcto.

## PROBLEMA

Considera el sistema
$$
F' & = (2-S)F, & F(0) & = F_0\\
S'& = (F-1)S, & S(0) & = S_0
$$

y el esquema numérico
$$
F_{n+1} = F_n + \Delta t (2-S_n) F_n \\
S_{n+1} = S_n + \Delta t (F_n-1) S_n
$$

### Inciso A

Escribe una función que implemente el esquema (2) y que deberá:

*   Aceptar $S_0$, $F_0$ y $\Delta t$ como entradas.
*   Calcular la solución numérica para $t$ variando desde $t=0$ hasta $t=10$ con un tamaño de paso $\Delta t$.
*   Devolver tres listas, cada una con los valores de $t$, $F$ y $S$ generados por la iteración del esquema numérico.

Utiliza tu función con los parámetros $F_0=1.9, S_0=0.1, \Delta t=0.1$ y guarda las listas resultantes como `t_range`, `F` y `S`.

### Inciso B

Crea una función que reciba como entrada las anteriores y trace las gráficas de la solución numérica tanto como una función de $t$ como en el espacio de estados (en el sistema coordenado $F\times S$).

### Inciso C

Utiliza las funciones anteriores, para graficar las soluciones del sistema con $F_0 = 1.9, S_0=0.1$ fijo, pero con $\Delta t = 0.001$

### Inciso D

Utiliza las funciones anteriores para generar las gráficas de las soluciones con $F_0 = 1, S_0=2, \Delta t = 0.001$.

### Inciso E

Partiendo del sistema de ecuaciones diferenciales, explica porque el comportamiento anterior de las soluciones con $F_0 = 1, S_0=2, \Delta t = 0.001$ es diferente al de las soluciones en incisos anteriores.

