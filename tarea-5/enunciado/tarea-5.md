# TAREA 5

* Unidad: Modelación experimental
* Materia: Matemáticas para Ciencia de Datos
* Programa: Maestría en Ciencia de Datos e Información, INFOTEC
* Docente:  Juliho Castillo Colmenares, Sc.D.

## INSTRUCCIONES

1. Del libro "Cai, X., Tveito, A., Langtangen, H. P., Nielsen, B. F. (2010). Elements of Scientific Computing. Germany: Springer Berlin Heidelberg", revisa el capítulo 5 "The Method of Least Squares".
2. Reúnete con los miembros de tu equipo para comentar la lectura y la tarea.
3. Resuelvan el siguiente problema, desarrollando de manera clara todos y cada unos de los puntos.
4. Si incluyes bloque de código, coméntalos de manera concisa, enfatizando su relación con la solución.
5. Detalla la información auxiliar de las gráficas para que tu conclusión sea clara.  
6. Organiza tu documento, escribe de manera explícita el enunciado de cada inciso y sepáralos utilizando secciones.
7. Transcríbanlo a un archivo PDF y suban un único archivo por equipo. 
8. Se considerará un inciso como incorrecto si el resultado no es el esperado, y se considerará incompleto si el resultado no está debidamente justificado.

## PROBLEMA

En internet, podemos encontrar información acerca de carros usados. En la tabla de abajo, hemos listado el precio de autos BMW usados de la serie 3 en Noruega. Se indica el precio promedio para un carro de 1 a 5 años de usado.

| Años $t_i$   | 1 | 2 | 3 | 4 | 5 |
|--------------|---|---|---|---|---|
| Precio $y_i$ | 55.2 | 44.9 | 37.9 | 35.3 | 30.1 |

Los precios están dados en miles de euros.

### Inciso A

Construye un modelo lineal para los datos implementando en Python la fórmula 5.58 de la lectura, utilizando `Numpy` para realizar los cálculos. Grafica la regresión lineal comparando con los datos.

### Inciso B

Construye un modelo cuadrático para los datos implementando en Python la fórmula 5.65 de la lectura, utilizando `Numpy` para realizar los cálculos. Grafica la regresión lineal comparando con los datos.

### Inciso C

Ahora ajustaremos un modelo exponencial $p(t) = \alpha e^{\beta t}$ a los datos. Tomando el logaritmo natural de ambos lados obtenemos $\ln(p(t))= \ln(\alpha) + \beta t.$ Si definimos $q(t)=\ln(p(t))$ y $\gamma = \ln(\alpha)$, entonces obtenemos un modelos lineal. 

Calcula la tabla para  $(t_i, \ln(y_i)),$ y calcula los parámetros de un modelo lineal $q(t)=\gamma + \beta t$ para estos datos.

### Inciso D

Ya que $\ln(\alpha)=\gamma$, entonces $\alpha = e^{\gamma}$. Sustituye $\alpha$ y $\beta$ en el modelo exponencial y grafícalo junto con los datos, el modelo lineal y el cuadrático. 