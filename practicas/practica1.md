## Objetivo
Crear dos llamadas a sistema una para apagar y otra para reiniciar. 
Y crear sus respectivos programas.

## Herramientas
git

make

gcc

## Conceptos
1) Llamadas a sistema
+ La forma que el kernel (SO) da acceso al HardWare
+ Se implementan mediante interrupciones de software (trap), ie,
la aplicacion se interrumpe para que el kernel se ejecute

2) Mdodo kernel
+ Es bit/registro que activa el CPU para acceder al HardWare
+ Solo hay un programa que se ejecuta con este bit, es el kernel

3) Interrupciones
+ Es la forma que el HW interactua con el CPU


## Que aprendi
Aprendi cómo podemos hacer que se pueda mandar las intrucciones de apagado y de reinicio al HW desde la línea de comando por medio del kernel, ya que si lo hacemos sin el kernel no nos deja hacerlo por el modo seguro que se tiene.
Se tiene que hacer uso de varios comandos de escritura para que se pueda escribir directo en el chip y ahí se pueda ejecutar este comando, así cambiando de estado a la máquina como apagarse. Esto tiene que ser directo en el chip por medio de su espacio de memoria.

## Url del commit
https://github.com/A01630401/OS/commit/2de79614c0c3433ffdfab93a362c710b10302031

