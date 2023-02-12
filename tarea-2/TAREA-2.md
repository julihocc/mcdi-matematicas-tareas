# TAREA 2

* Materia: Matemáticas para Ciencia de Datos
* Programa: Maestría en Ciencia de Datos e Información, INFOTEC
* Docente:  Juliho Castillo Colmenares, Sc.D.

## Lectura asignada

Del libro "Cai, X., Tveito, A., Langtangen, H. P., Nielsen, B. F. (2010). Elements of Scientific Computing. Germany: Springer Berlin Heidelberg", revisa el capítulo 2 "Differential Equations: First Steps"

## Instrucciones

1. Organízate con los miembros de tu equipo para comentar la lectura y la tarea.
2. Resuelvan el siguiente problema, desarrollando de manera clara y concisa todos y cada unos de los puntos.
3. Transcríbanlo a un archivo PDF utilizando un editor de textos y suban un único archivo por equipo. 
4. No se aceptarán trabajos escritos a mano, aun cuando estén digitalizados. 
5. Puedes utilizar software para resolver los problemas, pero en este caso deberás incluir el código en tu documento.
6. En cualquier caso, incluye el desarrollo completo de la solución. No se aceptarán respuestas sin justificación. 
7. Se considerará un inciso como incorrecto si el resultado no es el esperado, y se considerará incompleto si el resultado no está debidamente justificado.
8. Para acreditar el punto correspondiente a cada inciso, este deberá estar completo y ser correcto.

## PROBLEMA

Considera el problema de valor inicial 

$$
r'(t) = 1 + 4r(t), r(0)=0, t \in [0,T]
$$.

1. Encuentra la solución exacta del problema. 
2. Encuentra un esquema explícita para la solución utilizando el método de Euler hacia adelante. Las iteraciones de este esquema se denotarán por $y_i$ donde $y_0=r(0)=0$.
3. Calcula $y_{100}$ utilizando $\Delta t =0.01$. 
4. Calcula el error relativo de $y_{100}$​ respecto a la solución exacta.
5. Encuentra un esquema implícito para la solución utilizando el método de Euler hacia atras. Las iteraciones de este esquema se denotarán por $z_i$ donde $z_0=r(0)=0$.
6. Calcula $z_{100}$ utilizando $\Delta t =0.01$. 
7. Calcula el error relativo de $z_{100}$ respecto a la solución exacta.
8. ¿Cuál de los dos métodos es mejor para si el número de pasos es mucho mayor?

## NOTAS

* La ecuación diferencial es lineal, por lo que puedes ocupar el método correspondiente para resolverla. Tambi'en puedes resolverla usando la libreria `Sympy`.
* Escribe de manera explicita los esquemas, explicando el significado de todas las variables y parámetros, y explica como es que se han obtenido.
