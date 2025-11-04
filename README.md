Tarea Emily

Conceptos:

git branch:Se usa para gestionar las branchs (ramas) en Git, permiten trabajar en distintas versiones del proyecto al mismo tiempo. Además, facilita que varios desarrolladores trabajen en diferentes partes del código sin interferir entre sí, manteniendo el proyecto ordenado y controlado.

git checkout -b (nombre de la branch): Sirve para crear nuestra propia branch o rama, si se usa solo "git checkout", se usa para cambiar a una existente.Este comando ayuda mucho para desarrollar nuevas funciones o corregir errores sin afectar la rama principal del proyecto.

git status: Nos ayuda a saber cuales archivos se han modificado, cuales se estan trabajando o cuales estan listos para confirmar. También muestra si hay archivos pendientes de agregar, esto ayuda a mantener un control claro del estado del repositorio antes de hacer un commit.

git add . : Lo que hace es agregar todos los archivos que tengan cambios a la cola, prepara los archivos para ser confirmados en el siguiente commit, y se puede usar también con archivos específicos si no se desea agregar todos.

git commit -m "mensaje x": Sirve para guardar los cambios que se hicieron en el archivo de la branch  que se creo con un comentario. Cada commit representa parte del historial de la branch dentro de un archivo y debe llevar un mensaje claro que describa las modificaciones realizadas.

git push origin (nombre de la branch): Lo que hace este comando es enviar los commit al repositorio github y luego se pone el nombre de branch (rama) en la que se hacen los cambios.Con esto se actualiza el repositorio remoto con los cambios realizados en la máquina local. Esto es importante hacerlo para compartir el trabajo con otros colaboradores o guardar los avances de forma segura en la nube. O sea en Github.

git pull: Lo que hace es traerse los ultimos cambios desde el repositorio github. Este comando descarga las actualizaciones del repositorio remoto y las integra con la rama actual del proyecto local. Es recomendable usarlo antes de empezar a trabajar o antes de hacer un push, para asegurarse de tener la versión más reciente del código y evitar conflictos. En pocas palabras, mantiene sincronizado el entorno local con el remoto.

git rebase --continue:Se utiliza durante un proceso de rebase cuando ya se resolvieron los conflictos en los archivos afectados, este comando permite continuar el proceso de rebase después de haber solucionado los problemas detectados por Git. Básicamente, indica que ya se resolvieron los conflictos y que puede seguir aplicando los commits restantes.

git rebase main:Se utiliza este comando para reaplicar tus commits actuales encima de otra rama (en este caso, la rama main).Esto ayuda a mantener la rama actual renovada con los cambios más recientes de la rama principal, sin crear commits de fusión. Con rebase se logra tener historial más limpio y fácil de leer. 

Cuando se hace git rebase y luego se usa git push origin (nombre de la rama) -f, se pone -f porque se tiene que hacer forzado.

git diff: Este comando permite comparar el contenido de los archivos entre dos estados del repositorio, muestra qué líneas fueron agregadas, modificadas o eliminadas. Es una herramienta muy útil para revisar los cambios antes de confirmarlos con un commit. De esta manera, se puede verificar que las modificaciones sean correctas y evitar errores al registrar los cambios en el historial del proyecto.

git log: Este otro comando lo que nos muestra es un registro completo de los commits realizados dentro del repositorio. Con este comando se pueden ver datos importantes como el autor de cada commit, la fecha, el mensaje descriptivo y el código de identificación. Gracias a esta información, se puede analizar la evolución del código, identificar cuándo se introdujeron ciertos cambios o revertir versiones anteriores si es necesario.

git rebase -i HEAD: Sirve para ejecutar un rebase interactivo desde la posición actual (HEAD), esto permite editar el historial reciente de commits. Con esto se pueden combinar o eliminar commits para mantener una línea de desarrollo más clara y ordenada. Es muy utilizado para limpiar el historial antes de subir los cambios a un repositorio remoto, asegurando que el registro sea coherente y fácil de seguir por otros colaboradores de la branch.

git commit --amend: Se utiliza para realizar ajustes en el último commit creado, ya sea modificando el mensaje, agregando nuevos archivos o eliminando algunos que se incluyeron por error. Este comando evita tener que crear un nuevo commit para corregir detalles menores, manteniendo un historial más limpio. Es muy útil cuando uno se olvida de incluir un archivo o se desea mejorar la descripción del cambio sin alterar la secuencia del proyecto.

git branch -D: Elimina una rama local de manera definitiva, incluso si tiene cambios que no han sido fusionados. Se usa generalmente cuando una rama ya no tiene utilidad, se creó por error o ya se respaldó en el repositorio remoto. Al ser un borrado forzoso, debe utilizar con mucho cuidado.

git clone: Permite crear una copia exacta de un repositorio remoto en el equipo local, incluyendo todos los archivos, historial de commits, ramas y configuraciones. Este comando es el punto de partida cuando se desea trabajar con un proyecto que ya existe en plataformas como GitHub. Una vez clonado, se puede realizar modificaciones, crear nuevas ramas o contribuir al proyecto sin alterar directamente la versión remota.

git commit --amend --no-edit:Este comando se utiliza para modificar el último commit realizado sin cambiar su mensaje original. Permite agregar archivos que uno se olvidó de incluir o realizar pequeños ajustes al contenido del commit sin crear uno nuevo. Es muy útil cuando se desea mantener un historial limpio y evitar múltiples commits con mensajes similares. 