# Objetivo
Modificar al programa init para que muestre un programa de bienvenida.

# Herramientas
gcc

make

git

# Conceptos

1) Proceso

+ Instancia de un programa.
+ Tiene tres partes:
  + Stack: variables y llamadas a funciones.
  + Heap: memoria dinámica (malloc o new).
  + Código.

+ Se crea mediante dos llamadas a sistema:
  + fork clona
  + exec cambia el código

+ Tiene un estado:
  + Corriendo
  + Durmiendo (Listo)
  + Espera
  + Completado
  + Zombie

2) Programa init
+ Es el proceso encargado de inicializar el SO para dejarlo listo para usarse
+ Es el unico proceso que crea el SO

# Que aprendi
Aprendi que cada proceso tiene un stack, un heap y el código del programa que se quiere ejecutar. En el stack se ponen las variables que se van a utilizar y las funciones con sus propias variables, cuando una función se termina el return limpia la memoria y regresa el dato al CPU para que este se pueda quedar en la memoria donde fue llamada la función. En el heap se crean los objetos por lo que en el heap están las direcciones de memoria que se pidieron, dependiendo del tamaño que se haya pedido, se necesita limpiar la memoria de estos para que después se use por otros.

# Url del commit
https://github.com/A01630401/OS/commit/5754486a77d43f0ed3ba37e750e6c1d7fee137d3
