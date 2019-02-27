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
++ Stack: variables y llamadas a funciones.
++ Heap: memoria dinámica (malloc o new).
++ Código.

+ Se crea mediante dos llamadas a sistema:
++ fork clona
++ exec cambia el código

+ Tiene un estado:
++ Corriendo
++ Durmiendo (Listo)
++ Espera
++ Completado
++ Zombie

2) Programa init
+ Es el proceso encargado de inicializar el SO para dejarlo listo para usarse
+ Es el unico proceso que crea el SO

# Que aprendi

# Url del commit
