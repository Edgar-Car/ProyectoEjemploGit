# Tarea1_introduccion a Git

##Descripcion
- Objetivo: Repasar los comandos básicos de Git y crear un repositorio en GitHub.
- Git: Es un sistema de control de versiones distribuido que permite a los desarrolladores gestionar y realizar un seguimiento
de los cambios en el código de un proyecto.
- GitHub: Es una plataforma de alojamiento de código basada en la web que utiliza Git para gestionar los proyectos.
GitHub facilita la colaboración, permitiendo a varios desarrolladores trabajar en el mismo proyecto, compartir y revisar código.

## **Instrucciones de uso:** El programa se ejecuta primero con la compilacion de
la siguiente manera:
'javac HolaMundo.java' 
Y para ejecutar de la siguiente manera: 'java HolaMundo'

## Comandos Utilizados:
1. git config --global user.name "Nombre"
2. git config --global user.gmail "correo"
3. cd "Direccion de la carpeta"
4. ls -al
5. git init
6. git remote add Origin Url-del-repositorio
7. git remote -v
8. touch .gitignore
9. git add -A
10. git commit -m "Comentarios"
11. git push Origin master
12. git status
13. git check-ignore nombre-del-archivo

## Notas sobre el archivo `.gitignore`
+ Se creo con el proposito de ignorar ciertos archivos que no son necesarios en el repositorio
Se ignoran los archivos '/proyecto.project' ya que fue mi primera prueba del gitignore y 'debug.log' que es el archivo que se pide ignorar
+ El programa debe de mostrar "Hola Git"
+ Para verificar que se ignora 'debug.log' se usa el comando en Git Bash: ` git check-ignore debug.log `
