# TAREA 2

* Materia: Matemáticas para Ciencia de Datos
* Programa: Maestría en Ciencia de Datos e Información, INFOTEC
* Docente:  Juliho Castillo Colmenares, Sc.D.

## INSTRUCCIONES

1. Del libro "Cai, X., Tveito, A., Langtangen, H. P., Nielsen, B. F. (2010). Elements of Scientific Computing. Germany: Springer Berlin Heidelberg", revisa el capítulo 2 "Differential Equations: First Steps"
2. Reúnete con los miembros de tu equipo para comentar la lectura y la tarea.
3. Resuelvan el siguiente problema, desarrollando de manera clara todos y cada unos de los puntos.
3. Si incluyes bloque de código, coméntalos de manera concisa, enfatizando su relación con la solución. 
3. Organiza tu documento de manera que su lectura sea sencilla, utilizando secciones para cada inciso.
3. Transcríbanlo a un archivo PDF y suban un único archivo por equipo. 
4. Se considerará un inciso como incorrecto si el resultado no es el esperado, y se considerará incompleto si el resultado no está debidamente justificado.
5. Para acreditar el punto correspondiente a cada inciso, este deberá estar completo y ser correcto.

## PROBLEMA

Considera el problema de valor inicial 

$$
r'(t) = 1 + 4r(t), r(0)=0, t \in [0,T]
$$.

1. Encuentra la solución exacta del problema. 
2. Encuentra un esquema explícita para la solución utilizando el método de Euler hacia adelante. Las iteraciones de este esquema se denotarán por $y_i$ donde $y_0=r(0)=0$.
3. Encuentra un esquema implícito de la solución utilizando el esquema de Euler hacia atrás. Las iteraciones de este esquema se denotarán por $z_i$​​ donde $z_0=r(0)=0$​​.
4. Define $\Delta t=1/10$, calcula  $y_1, y_2, y_3$ y compara estos con los valores $r(\Delta t)$, $r(2\Delta t)$ y $r(3\Delta t)$, respectivamente.
5. Repite el paso anterior, para  $z_1, z_2, z_3$.
6. Escribe un programa de cómputo para el esquema explícito. Los parámetros deben ser el número de paso $N$ y el tiempo $T$, de manera que $$\Delta t = T/N.$$
7. Repite el paso anterior para el esquema implícito.
8. Estima el comportamiento asintótico del error absoluto $E$ para $T=1$ fijo y $N \in \left\{10^p | p=0,1,2,3,4,5 \right\}$.

## NOTAS

* La ecuación diferencial es lineal, por lo que puedes ocupar el método correspondiente para resolverla.
* Escribe de manera explicita los esquemas, explicando el significado de todas las variables y parámetros, y explica como es que se han obtenido.
