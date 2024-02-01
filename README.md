# Comandos útiles de GitHub

1.  git init `va a inicializar mi repositorio`
2. git git branch -M main `permite cambiar el nombre de la rama master a main`
3.  git add . `toma todos los archivos desde el ultimo comit (en este caso desde el init) y los prepara para una fotografia`
4.  git reset . `revierte todo lo que hizo el git add .`
5.  git commit -m "mi primer commit" `toma la fotogrfia, es decir guarda todos los cambios que se hayan hecho`
6.  git checkout -- . `revierte todos los cambios que se hayan hecho hasta el ultimo commit`
7.  git log `permite ver todos los commit que se hayan hecho`
8.  git commit --amend 
    `- permite arreglar el ultimo commit - tiene variaciones para poder arreglar cualquier commit`
    `- se abrira otra seccion para editar, presionar i para poder editar el texto`
    `- para salir y guardar presionar la tecla esc -> luego escribimos :wq! + enter`
    `- de esta manera tendremos el mensaje del commit arreglado`
9.  git checkout -b rama-heroes `permite crear una nueva rama`
10.  git checkout nombreDeLaRama `permite moverse entre ramas`
11. git git merge rama-heroes `permite fusionar la rama actual a la rama especificada`
12. git branch -d rama-heroes `permite eliminar una rama`
13. git remote add origin urlDelRepositorioDeGit `configuro a que repositorio quiero desplegar mi proyecto`
14. git push -u origin main `despliego mi proyecto al repositorio origin en la rama main`

