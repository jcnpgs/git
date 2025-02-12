# Explicación de GIT
La primera vez que usamos GIT en una máquina debemos configurar el user y el email y comprobarlo.
Las ordenes son:
````shell
    git config --global user.name nombre_de_usuario_de_GitHub (entre comillas si tiene espacios)
    git config --global user.email email_de_usuario_de_Github
````

Para comprobar la configuración de GIT:
````shell
    git config --list
````

Para iniciar un repositorio:
````shell
    1º Abrimos la carpeta desde la consola GitBash
    2º Ejecutamos git init
````

Para hacer que GIT controle un archivo:
````shell
    git add nombre_fichero (en lugar de un fichero se puede poner . o -all para controle todos los de la carpeta actual)
````

Para confirmar los cambios:
````shell
    git commit -m "nombre_commit"
````

Para saber el estado de GIT:
````shell
    git status
````

Para crear una rama GIT:
````shell
    git branch nombre_rama
````

Para activar una rama GIT:
````shell
    git checkout nombre_rama
````

Para fusionar ramas de GIT:
````shell
    git merge nombre_rama (se mergea nombre_rama sobre la rama en la que estemos actualmente)
````