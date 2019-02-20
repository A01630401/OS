## Objetivo
Modificar el programa sh.c para ejecutar al comando anterior.

## Herramientas
git

make

gcc

## Conceptos
1) Como se crean nuevos procesos
+ Un programa padre (sh.c) ejecuta la llamada a sistema fork
+ La llamada a sistema fork clona al proceso padre
+ El proceso hijo madna a llamar a exec para ejecutar otro codigo


## Que aprendi


## Url del commit

## Como se relaciona con los conceptos anteriores
Se usan las llamadas al sistema para que se pueda hacer uso de la memoria RAM, usar el sistema de almacenamiento para que se ecuentre el codigo que se va a usar en el exec.
El sistema operativo es el encargado de crear los procesos, ya que se necesita el modo kernel para poder ejecutar el fork y exec.
