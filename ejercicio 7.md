## Problemas resueltos en clase con diagramas de flujo
### ejercicio
Obtener el promedio de las calificaciones aprobatorias y la cantidad de alumnos reprobados. La calificación esta entre 0 y 10, y el máximo de alumnos es de 15.
 #### 1.1 analisis 
Dentro del simbolo de proceso se utiliza un vector A[15], luego se usa ciclo for para limitarlo hasta 15 alumnos, luego entrada de datos para registrar las calificaciones de los alumnos, luego una condicion para verificar que su calificacion sea mayor a 6 y en caso de no serlo imprimir reprobado, si es mayor se registra en un vector, al final se una salida de datos para mostrar el promedio.
#### 1.2 Diagrama de flujo de datos

#### 1.3 Codigos
https://postimg.cc/T53cdSvC
#### 1.4 prueba de escritorio
|entrada|proceso|salida|
|------------|-------------|----------|
|      4,5,6,7,...      |  reprobo, reprobo, a[6],a[7],...           |    prom     |

#### 1.5 entradas
cal
#### 1.6 salidas
P_A y C_A
