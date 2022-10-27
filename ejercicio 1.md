## Problemas resueltos en clase con diagramas de flujo
### ejercicio 1
Contar del 1 al 10 y sumar los valores.
#### 1.1 analisis 
usas una sumatioria y un contador, solo respetas las reglas de el tipo de estructura repetitiva
#### 1.2 Diagrama de flujo de datos
https://postimg.cc/SJ8JwzfZ
#### 1.3 prueba de escritorio
|entrada|proceso|salida|
|------------|-------------|----------|
|           |     1+2+3+4+5+6+7+8+9+10     |      55   |

#### 1.4 entradas
ninguna
#### 1.5 salidas}
### codigo
void main(List<String> args) {
  int s = 0;
  for (var i = 1; i <= 10; i++) {
    s += i;
  }
  print("La suma de los valores es: $s");
}
