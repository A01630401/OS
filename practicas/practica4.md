## Objetivo
Hacer un planificador de procesos basadps en prioridades.

El proceso a mayor prioridad se ejecuta primero.

Si hay dos o mas con prioridades iguales el primero de la lista.

## Herramientas
gcc

make

git

## Conceptos
1) Proceso (va a ser pregunta de examen)
   + Instancia de un programa.

2) Planificacion de procesos:
   + Es el mecanismo que el SO tiene para asignarle el CPU a un proceso.

3) Estados de un proceso

4) Cambio de contexto:
   + Ocurre cuando el CPU deja de ejecutar un proceso para ejecutar otro.
   + Guardar el PC y la direccion del stack del proceso actual.
   + Restaurar el PC y la direccion del nuevo proceso.

## Que aprendi
Con esta practica aprendi que hay procedimientos que hace el sistema operativo para que se puedan ejecutar varios procesos en concurrencia, haciendo que se ejecuten por partes por el CPU y dandoles cierto tiempo de CPU a cada proceso, con el planificador que implementamos se puso la prioridad a cada proceso y asi se puede decidir cual sera el que se ponga primero en CPU y cual sera el siguiente, haciendo que se ejecuten procesos mas importantes al principio y que les toque asi mas tiempo de CPU que procesos que no son tan importantes y pasan a segundo plano, un problema que tiene el planificador que implementamos es que si hay un proceso con una gran prioridad este se va a hacer hasta que se termine, mientras que un proceso con poca prioridad puede ser que nunca pase a CPU y muero por starvation.

## Url del commit
1) https://github.com/A01630401/OS/commit/c02cc59428629ffc4eca2eb0e5ec06536cf27b59
2) https://github.com/A01630401/OS/commit/58b93391f5654f75cb841b9560720bbc25a90f9a

## Como se relaciona con los conceptos anteriores
Llamadas a sistema, procesos (desarrollar)
