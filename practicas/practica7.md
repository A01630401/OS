# Objetivo:
Validar que los directorios son realmente archivos que contienen el nombre de otros archivos y su referencia (inode)

# Herramientas
gcc

git

# Conceptos:
+ Archivos
  + Grupo de bytes almacenado que forma una entidad.
  + Formato: txt, jpg, png, bin, etc.
  + La extension (.exe, .dat, .jpg, .bat, .doc) es opcional y puede no coincidir con el contenido.
  
+ Directorios:
  + Es un tipo especial de archivo que contiene el nombre de otros archivos y sus referencias.
  
# Url del commit
https://github.com/A01630401/OS/commit/1f77fc3cfcbd4d9fc999be8ef10cd4f46de52a14

# Que aprendi:
Lo que aprendi en esta practica fue como funciona el sistema de archivos de un sistema operativo, como para poder tener archivos muy grandes estos se tienen que segmentar y poner referencias para cada segmento de estos. Tambien aprendi que un directorio no es otra cosa que otro tipo de archivo con informacion de los archivos que tienen dentro y referencias a estos, asi como referencias a si mismo y al directorio padre de este para poder navegar entre ellos.
