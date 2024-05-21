
Git es un sistema de control de versiones, como el nombre lo indica permite el gestionamiento 
de versiones en distintas applicaciones


---Git Init: 
Para inicializar un repositorio de git en un directorio utilizamos git init o tambien se puede realizar mediante
la interfaz de Ide

--Commits:
Los commits son screenshots o una captura de nuestra app, cada cambio que se agrega como commit funciona como versionamiento, digase 
subimos una applicacion que registra estudiantes le hacemos commit de los cambios actuales, luego agregamos la func. de eliminar estudiantes, entonces tendriamos dos commits
Por lo tanto si quisieramos 

--Ramas(Branches):
Las ramas son derivados de tu repositorio donde se agregaran los cambios de algun archivo/app.
En estas podemos subir nuestros cambios y gestionar versiones a traves de los commits
main -> commit -- commit -- commit Es la rama principal o usualmente tambien vemos la rama master, cada commit se realiza sobre la rama en la que estamos
Dev -> commit -- commit -- commit 
Test -> commit -- commit -- commit
- Para cambiar de rama debemos de utilizar el comando 'switch'
- Podemos volver a cualquier commit realizado para ver los cambios o si bien para volver a esa version

1==Para inicializar un repositorio utilizamos 
git init o lo podemos realizar via el IDE

2--Para agregar un archivo/cambio podemos realizarlo de dos formas:
Git Add -- via consola de comandos
Agregarlos a la zona de staging via el ide, la zona de staging es una zona previa antes de realizar un commit

3- Para configurar nuestro usuario y contrasena con git utilizamos:
--Git config --global user.name  "Name"
--Git config --global user.email  "Email"

4- Podemos utilizar git status para ver cambios u archivos borrados y demas
 git-restore "Archivo borrado" - Para recuperar un archivo

 5- Podemos descartar cambios via el ide, lo que hara sera regresar al ultimo commit
 