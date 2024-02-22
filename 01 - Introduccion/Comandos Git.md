# Comandos de Git 

## Comando para ver la version de Git
- git -v
- git --version

## Comandos para configuracion inicial de Git
- git config --global user.name "Juan Rendon"
- git config --global user.email "juanjoseflorezrendon124@gmail.com"

## Comando para editar o ver la configuracion de Git
- git config --global --edit
- git config --global --list
### Para salir del edit
- ctrl + O y ctrl + X
- y si es VIM  esc y : wq

## Como iniciar Git en un directorio
- git init

## Para borrar un archivo
- git rm nombre-del-archivo

## Pasos para crear una version de nuestro codigo
1. Agregar todos los archivos al commit
    - git add .
    Tambien puedo agregar un solo archivo
    - git add index.js
    O si solo quiero agregar todos los archivos de una extencion
    - git add \*.css

2. Tomar la foto del codigo (Crear una nueva version "commit")

- git commit -m "Nombre del commit"
- git commit -am "Nombre del commit"


## Como saber el como estan mis archivos
- Git status(el arvivo que aparezca verde esta añadido, el rojo esta por fuera);
- Si un archivo tiene una U es por que se puede perder, osea que no lo he guardado con el git add
- Si tienen una A es por que ya ha sido añadido
- Si tiene una M es por que ha sido modificado

## Comando para listar las versiones de mi proyecto(ver los commits)
- git log
- git log --oneline

## Comando para cambiar el nombre master
- git branch -m nombre-antiguo nombre-nuevo

## Comando para cambiar de version 
- git checkout <Id del commit y nombre de la rama para volver al presente>
<<<<<<< HEAD


## Para ver todo lo que he hecho ultimamente

- git config --global  alias.lg 'log --oneline',
- git lg
<!-- con esto acorto los comandos que le diga con el alias -->


<!-- 
Tengo que instalas estas extenciones
- Git Graph
- Git History
- Git Lens -->
=======
>>>>>>> rama-auxiliar
