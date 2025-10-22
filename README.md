# laboratorio-git
esto es una prueba sofia
esto es una prueba hecha por emily
<<<<<<< HEAD
test rebase emily
=======
test rebase emily

Tarea Emily
Conceptos:
git branch:Se usa para gestionar las branchs (ramas) en Git, permiten trabajar en distintas versiones del proyecto al mismo tiempo.
git checkout -b (nombre de la branch): Sirve para crear nuestra propia branch o rama, si se usa solo "git checkout", se usa para cambiar a una existente.
git status: Nos ayuda a saber cuales archivos se han modificado, cuales se estan trabajando o cuales estan listos para confirmar.
git add . : Lo que hace es agregar todos los archivos que tengan cambios a la cola.
git commit -m "mensaje x": Sirve para guardar los cambios que se hicieron en el archivo de la branch  que se creo con un comentario.
git push origin (nombre de la branch): Lo que hace este comando es enviar los commit al repositorio github y luego se pone el nombre de branch (rama) en la que se hacen los cambios.
git pull: Lo que hace es traerse los ultimos cambios desde el repositorio github.
git rebase --continue:Se utiliza durante un proceso de rebase cuando ya se resolvieron los conflictos en los archivos afectados.
git rebase main:Se utiliza este comando para reaplicar tus commits actuales encima de otra rama (en este caso, la rama main).
Cuando se hace git rebase y luego se usa git push origin (nombre de la rama) -f, se pone -f porque se tiene que hacer forzado.
>>>>>>> 7bd9a5f (Conceptos de la tarea)
