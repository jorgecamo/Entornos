# ORDENES DE GIT BASICAS
---
Vamos a empezar con cofigurar el git, poniendo el nombre y el correo de la siguiente forma: 

`git config --global user.name "[name]"`

`git config --global user.email "[email address]"`

--- 

Para iniciar un repositorio tienes que usar la siguiente orden:

`git init [project-name]`

Para ver el estado del repositorio es :

`git status`

Para añadir los ficheros para hacer un commit es:

`git add [fichero] puedes poner un . para añadir todo lo del directorio actual`

Para guardar esa version es la orden: 

`git commit -m "mensaje que describa o nombre"`

Para borrar todos los commits hasta el especifico: 

`git reset [commit]`

Para borrar todo y que vuelva al commit especifico: 

`git reset --hard [commit]`

---

Para ver todas las ramas creadas es la orden: 

`git branch`

Y para crear una rama nueva la orden : 

`git branch [nombre]`

Para cambiar de ramas : 

`git checkout [nombre de rama que quieras cambiar]`

Para combinar ramas distintas: 

`git merge [nombre de la rama a combinar]`

Para borrar una rama :

`git branch -d [nombre de la rama]`

---

Para ver el historial:

`git log`

Para ver un historial mas detallado:

`git log --graph --all`

---

Para configurar un directorio remoto: 

`git remote add origin [directorio remoto]`

Para descargar el historial del directorio remoto:

`git pull`

Para subir todos los commits de la rama local:

`git push origin [nombre de la rama remota]`
