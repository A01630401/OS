# Objetivo:
Investigar y practicar sobre hilos.

# Herramientas:
ggc

git

# Conceptos:
+ Hilos
  + Proceso ligero.
  + Solo tiene un stack y el codigo y el heap que lo comparte con el proceso prinicipal.
  + Si el proceso principal termina, los hilos terminan.
  
+ Lock:
  + Mecanismo de sincronizacion.
  + Variable global que soporta dos operaciones:
    + lock, el primer hilo que hace lock se adueña del lock, el resto queda esperando.
    + unlock, el hilo dueño del lock lo libera.
  + Ayuda para resolver el problema de la seccion critica.
  
+ Semaforos:
  + Mecanismo de sincronizacion.
  + Variable global que tiene un valor inicial mayor o igual a cero. Soporta dos operaciones.
    + wait/decrease. Si es mayor a 0 decrementa y continua, si es igual a 0 se suspende.
    + post/increase. Incrementa el valor del semaforo en uno.
  + Para asignar recursos.
  
+ Problemas de sincronizacion.
  + Condicion de carrera. Ocurre cuando el resultado depende del orden en que se ejecuten los hilos.
  + Deadlock: Cuando dos o mas hilos estan esperando por un recurso que no se libera.
  + Productor/Consumidor: Ocurre cuando los datos se pueden sobre-escribir.
  
# Url del commit
1. https://github.com/A01630401/OS/commit/e5789a639eef49c1ec1437581e56b66d1a074a20
2. https://github.com/A01630401/OS/commit/1b895228bd3734d82f64f4f0f0642cd88b74ef33

# Que aprendi:
Lo que aprendi con esta practica es la forma en la que funcionan los threads, los cuales son una alternativa mas comoda para crear varios procesos, ya que estos tienen una facil comunicacion por el hecho de que comparten el heap, mientras que el stack y el codigo solo tiene la parte que necesita este, haciendolo asi un elemento ligero y facil de controlor, pero tiene sus desventajas que es el buen manejo de los recursos para que se hagan las cosas en el orden que se requiere por lo que se usan locks asi como semaforos. Al final de cuentas estos se usan para que se puedan hacer varias cosas a la vez en un proceso y asi poder hacerlo mas rapido y eficiente, esto es posible ya que las computadoras actuales tinen normalmente mas de un nucleo por lo que puedan hacer varias operaciones a la vez.
