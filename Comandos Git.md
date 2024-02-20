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

## Pasos para crear una version de nuestro codigo
1. Agregar todos los archivos al commit
    - git add .
2. Tambien puedo agregar un solo archivo
    - git add index.js
3. O si solo quiero agregar todos los archivos de una extencion
    - git add *.css