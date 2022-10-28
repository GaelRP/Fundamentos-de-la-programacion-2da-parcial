## Problemas resueltos en clase con diagramas de flujo
### ejercicio
Capture n números en el rango [Li,Ls] donde: -Li = Limite inferior -Ls limite superior para li<ls y l0, obtenga: Cantidad de números pares y su promedio, Cantidad de números impares y su promedio y ¿Qué promedio es mayor?
 #### 1.1 analisis 
En un proceso digitamos las variables, luego con salidad de datos preguntamos li y ls y los guardamos en una entrada de datos, despues usamos condicionales para verificar que respeten los limites establecidos que pusimos mediante unas condiciones, luego preguntamos cuantos numeros ingresan y los digitan en una entrada de datos y se verifica que sea mayor a 0 mediante una condicion y si se cumplen los requisitos pasa al la siguiente figura donde se le va sumando a c=c+1 (en un proceso), luego se preguntan los numeros y se verifica que esten dentro de los limites establecidos, li y ls, si no se cumple se vuelve a preguntar y si es correcto el numero pasa por la condicion NUM%2=0 y asi hasta que c=n, despues ingresamos el pp y el pi y mediante una condion vemos si  pp>pi y dependiendo el resultado cambia la salida de datos
#### 1.2 Diagrama de flujo de datos
while: https://postimg.cc/64WRK63y
do/while: https://postimg.cc/kB58h5zH
#### 1.3 Codigos
https://postimg.cc/WhDH0DxS
#### 1.4 prueba de escritorio
|entrada|proceso|salida|
|------------|-------------|----------|
|      3, 50, 60      |  3<li, 50>li y <ls, 60>li y <ls            |   ls, li, "p_p es mayor"|

#### 1.5 entradas
li, ls,n, num, pp, pi.
#### 1.6 salidas
limite inferior, limite superior, pp mayor a pi y pi mayor a pp
