Empezando con la terminal
=========================

Basado en: [La terminal](https://www.aluracursos.com/blog/empezando-con-la-terminal-manejando-archivos-y-carpetas)

- La Terminal existe en todos los sistemas operativos: windows, linux, mac

## Ventajas

1. Mas rápido
2. Más directo
3. Se pueden personalizar y automatizar los comandos
4. Se puede hacer todo los que se hace en el entorno gráfico y mas


## Desventajas

1. Menos intuitiva
2. 

## Primeros pasos

1. Directorio Home, en linux y mac es el directorio del usuario logeado.
2. `~` indica en la terminal que estamos en el directorio de inicio.
3. `pwd` muestra el directorio actual en el que se esta.
4. `ls` `list` muestra el listado de archivos en el directorio actual
5. `ls Documents/` muestra los archivos que estan dentro de ese directorio, con camino relativo ya que no es necesario pasar la ruta absoluta si estamos en el directorio que contiene esa carpeta por ejemplo.
6. `cd Documents/` nos movemos a ese directorio
7. `ls -a` nos muestra los archivos incluyendo los archivos ocultos del directorio actual
8. `cd ..` nos lleva al directorio padre

## Manipulación de archivos

1. Crear un archivo `touch estudios.py`
2. Crear un directorio `mkdir estudios` crea una carpeta llamada estudios
3. Mover un archivo `mv estudios.py estudios ` mueve el archivo estudios.py a la carpeta estudios
4. `mv` tambien se usa para renombrar un archivo, `mv estdios.py recolectando_datos.py` le cambia el nombre al archivo
5. Eliminar un archivo `rm recolectando_datos.py` elimina ese archivo
6. Eliminar un directorio `rm estudios` elimina esa carpeta siempre y cuando este *vacia*
7. Eliminar un directorio completo o eliminación recursiva `rm -R estudios`
8. Leer el contenido de un archivo `cat wordpress.txt` muestra el contenido de ese archivo
9. Limpiar la pantalla `clear`