# TAREA 3

* Unidad: Simulaciones
* Materia: Matemáticas para Ciencia de Datos
* Programa: Maestría en Ciencia de Datos e Información, INFOTEC
* Docente:  Juliho Castillo Colmenares, Sc.D.

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
\begin{equation}
	\begin{split}
		F' & = (2-S)F, & F(0) & = F_0\\
		S'& = (F-1)S, & S(0) & = S_0
	\end{split}
\end{equation}
$$

y el esquema numérico
$$
\begin{equation}
\begin{split}
F_{n+1} = F_n + \Delta t (2-S_n) F_n \\
S_{n+1} = S_n + \Delta t (F_n-1) S_n
\end{split}
\end{equation}
$$

### Inciso A

Escribe una función que implemente el esquema (2) y que deberá:

*   Aceptar $S_0$, $F_0$ y $\Delta t$ como entradas.
*   Calcular la solución numérica para $t$ variando desde $t=0$ hasta $t=10$.
*   Devolver el rango para $t$, y los valores para $F$ y $S$.

### Inciso B

Crea una función que reciba como entrada los valores anteriores y trace las gráficas de la solución numérica tanto como una función de $t$ como en el espacio de estados (en el sistema coordenado $F\times S$).

### Inciso C

Usa tu programa para estimar un valor de $\Delta t$ suficientemente pequeño, tal que para valores más pequeños de $\Delta t$ no existe una diferencia perceptible en las gráficas generadas con la función del inciso anterior. En estos cálculos usa $F_0 = 1.9, S_0=0.1$.

### Inciso D

Con el valor de $\Delta t$ que elegiste en el inciso anterior, varía tus parámetros en el conjunto
$$
F_0 = 0.5:0.5:1.5,\\ S_0=1.5:0.5:2.5
$$
y determina si todas las soluciones son periódicas. 

### Inciso E

 De manera particular, determina, analiza y discute las condiciones iniciales en que el sistema permanece estático.  Con base en el sistema (1), ¿cómo explicas el comportamiento del sistema para estas condiciones iniciales? 

## Notas

*   La notación $a:h:b$ denotará la sucesión de valores desde $a$ hasta $b$ con un paso de longitud $h$. Abusando de la notación, $x=a:h:b$ indicará que $x$ variará de manera creciente en el conjunto correspondiente. Esta notación es común en lenguajes como `MATLAB` y `Julia.` El equivalente en `Python` sería la función `numpy.arange`, pero esta función sigue la convención de no incluir el límite superior. 
