# TAREA 8

* Unidad: Programación lineal
* Materia: Matemáticas para Ciencia de Datos
* Programa: Maestría en Ciencia de Datos e Información, INFOTEC
* Docente:  Juliho Castillo Colmenares, Sc.D.

## INSTRUCCIONES

1. Completa las lecturas propuestas para esta actividad y reúnete con los miembros de tu equipo para comentar las lecturas y la tarea.
2. Resuelvan el siguiente problema, desarrollando de manera clara todos y cada unos de los puntos.
3. Si incluyes bloque de código, coméntalos de manera concisa, enfatizando su relación con la solución.
4. Detalla la información auxiliar de las gráficas para que tu conclusión sea clara.  
5. Organiza tu documento, escribe de manera explícita el enunciado de cada inciso y sepáralos utilizando secciones.
6. Transcríbanlo a un archivo PDF y suban un único archivo por equipo. 
7. Se considerará un inciso como incorrecto si el resultado no es el esperado, y se considerará incompleto si el resultado no está debidamente justificado.
8. Modela el problema usando Google OR-Tools y resuélvelo usando este módulo. 

## Problemas de mezcla de productos

Una compañía fabrica tres productos: crema corporal, crema facial y crema para bebés. Los tres productos
comparten ingredientes en su elaboración: mezcla base, aceite de almendras, vitamina E y manteca
de karité. En la siguiente tabla se presenta información acerca de los porcentajes de composición de cada
uno de los tres productos:

| <space> | Mezcla base | Aceite de Almendras | Vitamina E | Manteca de karité |
|---|-------------|---------------------|------------|-------------------|
|Crema Corporal| 90% | 4% | 1% | 5% |
|Crema facial  | 85% | 8% | 2.5% | 4.5% |
|Crema para bebé | 80% | 10% | 0% | 10% |

#### Restricciones

Cada día, la compañía cuenta con 
* 500 litros de la mezcla base, 
* 50 litros de aceite de almendras, 
* 5 litros de vitamina E y 
* 30 litros de manteca de karité. 

Adicionalmente, se tiene la siguiente información sobre costos y precios de venta.

| Ingrediente | Costo por litro |
|-------------|-----------------|
|Mezcla base  | \$20 |
|Aceite de almendras | \$500 |
|Vitamina E | \$1500 |
|Manteca de karité | \$200 |



| Producto | Precio de venta (\$/L) |
|----------|------------------------|
|Crema corporal | \$80 |
|Crema facial | \$120 |
|Crema para bebé | \$100 |



La demanda diaria de la 
* crema corporal es de 200 litros; 
* de la crema facial, 150 litros; y 
* de la crema para bebé, de 250 litros. 
* Por políticas de la empresa, se deben fabricar al menos 50 litros de crema facial.

¿Cuánto de cada producto deberá producir la compañía para maximizar su utilidad?

### Inciso A

Modela las restricciones para los insumos.

### Inciso B

Modela las restricciones para los productos. 

### Inciso C

Modela la función objetivo, resuelve el problema y obtén los valores con los que se optimiza la función objetivo. 

### Inciso D

Con base en la solución anterior, explica tus conclusiones en términos del enunciado original del problema.