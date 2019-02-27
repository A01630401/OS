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
+ El proceso hijo manda a llamar a exec para ejecutar otro codigo

## Que aprendi
Aprendi que para poder crear un proceso primero se necesita clonar al proceso de donde este fue ejecutado, dejando a este como proceso padre, despues haciendo el exec para del codigo del nuevo proceso se quede en el proceso clonado para que este ya empiece como el nuevo proceso. Como se toma el proceso padre para poder empezar otro siempre va a estar como el primer padre el proceso de init, ya que este es el que primero comienza en una computadora.

## Url del commit
https://github.com/A01630401/OS/commit/4b1394f3dc64dd3411d28b27b2ab804eaace0ebf

## Como se relaciona con los conceptos anteriores
Se usan las llamadas al sistema para que se pueda hacer uso de la memoria RAM, usar el sistema de almacenamiento para que se ecuentre el codigo que se va a usar en el exec.
El sistema operativo es el encargado de crear los procesos, ya que se necesita el modo kernel para poder ejecutar el fork y exec.
