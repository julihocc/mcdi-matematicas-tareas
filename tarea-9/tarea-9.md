# TAREA 9

* Unidad: Programación entera
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

### Planteamiento del problema

El siguiente es problema para la asignación de recursos en lo referente a la programación  de los horarios de las enfermeras. Suponga un hospital que enfrenta constantemente problemas con el horario de trabajo de sus enfermeras. Se busca minimizar el número total de enfermeras durante cada periodo del día.

| Periodo | Turno del día | Número requerido de enfermeras |
|---------|---------------|--------------------------------|
| 1       | 8:00-10:00    | 10  |
| 2       | 10:00 - 12:00 | 8   |
| 3       | 12:00 - 14:00  | 9   |
| 4       | 14:00 - 16:00   | 11  | 
| 5       | 16:00 - 18:00   | 13  |
| 6       | 18:00 - 20:00   | 8   | 
| 7       | 20:00 - 22:00   | 5   |
| 8       | 10:00 - 24:00   | 3   |


Dado que cada enfermera trabaja jornadas de ocho horas diarias, cada una puede comenzar a trabajar al inicio de cualquiera de los primeros cinco turnos: 8:00, 10:00, 12:00, 14:00 o 16:00. Es importante resaltar, que en este caso no estamos considerando los periodos que comienzan en horas impares, como las 9:00, 11:00, etcétera. Como se puede apreciar, por definición no se necesita considerar que un turno comience después de las 4:00, dado que el horario se extendería hasta después de la medianoche, cuando las enfermeras ya no son necesarias. Por tanto, solo es necesario considerar cinco turnos. 

Se ha identificado el requerimiento específico de mano de obra en periodos de dos horas. De hecho, la definición de los cinco turnos mencionados previamente también es a intervalos de dos horas. Por tanto, cada enfermera que se presente a trabajar en el periodo t trabajará también: t + 1, t + 2 y t + 3; esto es, 8 horas consecutivas. La pregunta es: ¿cuántas enfermeras se deben reportar a trabajar durante cada periodo, de tal forma que se cumplan los requerimientos especificados en la tabla anterior de la manera más eficiente posible?


### Inciso A

Modela las restricciones para los cada turno.

### Inciso B

Modela la función objetivo, resuelve el problema y obtén los valores con los que se optimiza la función objetivo. 

### Inciso C

Con base en la solución anterior, explica tus conclusiones en términos del enunciado original del problema.
