# TAREA 5

* Unidad: Modelación experimental
* Materia: Matemáticas para Ciencia de Datos
* Programa: Maestría en Ciencia de Datos e Información, INFOTEC
* Docente:  Juliho Castillo Colmenares, Sc.D.

## Lectura asignada

Del libro "Cai, X., Tveito, A., Langtangen, H. P., Nielsen, B. F. (2010). Elements of Scientific Computing. Germany: Springer Berlin Heidelberg", revisa el capítulo 5 "The Method of Least Squares".

## Instrucciones

1. Organízate con los miembros de tu equipo para comentar la lectura y la tarea.
2. Resuelvan el siguiente problema, desarrollando de manera clara y concisa todos y cada unos de los puntos.
3. Transcríbanlo a un archivo PDF utilizando un editor de textos y suban un único archivo por equipo. 
4. No se aceptarán trabajos escritos a mano, aun cuando estén digitalizados. 
5. Puedes utilizar software para resolver los problemas, pero en este caso deberás incluir el código en tu documento.
6. En cualquier caso, incluye el desarrollo completo de la solución. No se aceptarán respuestas sin justificación. 
7. Se considerará un inciso como incorrecto si el resultado no es el esperado, y se considerará incompleto si el resultado no está debidamente justificado.
8. Para acreditar el punto correspondiente a cada inciso, este deberá estar completo y ser correcto.

## Planteamiento del problema

En Internet, podemos encontrar información acerca de carros usados. En la tabla de abajo, hemos listado el precio de autos BMW usados de la serie 3 en Noruega. Se indica el precio promedio para un carro de 1 a 5 años de usado.

| Años $t_i$   | 1 | 2 | 3 | 4 | 5 |
|--------------|---|---|---|---|---|
| Precio $y_i$ | 55.2 | 44.9 | 37.9 | 35.3 | 30.1 |

Los precios están dados en miles de euros.

### Inciso A

Construye un modelo lineal para los datos implementando en Python la fórmula 5.58 de la lectura, utilizando `Numpy` para realizar los cálculos.  Encuentra el modelo de regresión lineal para los datos de la tabla $(t_i, y_i)$. 

### Inciso B

Construye un modelo cuadrático para los datos implementando en Python la fórmula 5.65 de la lectura, utilizando `Numpy` para realizar los cálculos. Encuentra el modelo de regresión cuadrática para los datos de la tabla $(t_i, y_i)$.

### Inciso C

Ahora ajustaremos un modelo exponencial $p(t) = p_0 e^{\kappa t}$ a los datos. Tomando el logaritmo natural de ambos lados obtenemos $\ln(p(t))= \ln(p_0) + \kappa t.$ Si definimos $q(t)=\ln(p(t)), \lambda = \ln(p_0)$, entonces obtenemos un modelos lineal $q(t)=\lambda + \kappa t$. 

Calcula la tabla para  $(t_i, \ln(y_i)),$ y calcula los parámetros de una regresión lineal $q(t)=\lambda + \kappa t$ para los datos de esta nueva tabla. 

### Inciso D

Con los datos anteriores, determinar un modelo de regresión exponencial para los datos de la tabla $(t_i, y_i)$. 

## Notas

1.   No es necesario trazar la gráfica, pero si lo haces, podrás observar si tu modelo se ajusta a los datos. 
2.   Escribe de manera explicita los resultados obtenidos, es decir, los valores de los parámetros para cada inciso. 
3.   Debes desarrollar tu procedimiento, de acuerdo a lo establecido en el libro de texto.
4.   No se validarán resultados que se obtengan con el uso de librerías externas de modelado de datos.  