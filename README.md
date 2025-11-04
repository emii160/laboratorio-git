git branch: Es un comando de Git el cual permite gestionar ramas en un repositorio, permite experimentar, construir y probar cambios sin afectar el código principal. Este comando es fundamental para aislar el trabajo en nuevas funciones, adem[as de corregir los errores sin que se afecte la rama principal.
Es esencial para hacer más fácil el trabajo en equipos, debido a que cada integrante del grupo puede trabajar en su propia rama sin afectar a los demás.

git checkout: Es un comando de Git que básicamente permite cambiar de rama y restaurar archivos en el directorio de trabajo, gracias a este comando es posible moverse entre diferentes líneas de desarrollo y revisar versiones anteriores del código, sin que esto perjudique en la modificación de la rama principal.
Este comando es esencial para lograr descartar cambios que no se desean en archivos y dejaros nuevamente como estaban en la íltima versión, ayuda a que el trabajo sea más ordenado.

git checkout -b: Este comando se utiliza para crear una nueva rama y lograr cmabiarse automaticamente a ella, además, permite que se pueda trabajar en una línea nueva de desarrollo sin afectar la rama principal.

git status: Es un comando fundamental de Git el cual se encarga de mostrar el estado actual del repositorio, permite ver cuales archivos han sifo modificados, cuales archivos se encuentrar en el área de preparación, también es necesario ya que ayuda a solo confirmar los cambios que se desean, de esta manera se evitan errores accidentales con archivos que no queramos incluir.

git add: Es el comando que se utiliza para añadir cambios del directorio de trabajo al área de preparación, es un comando muy importante porque solo los archivos que se agregan explicitamente al área de preparación, son los únicos que estarán incluidos en el próximo commit, se puede utilizar para agregar archivos específicos o todos los cambios de una sola vez.

git commit -m: Este comando crea un nuevo commit en el repositorio, resgistra de forma permanente los cambios que se hayan añadido mediante el 'git add'. Guarda los cambios confirmados en el repositorio junto a un mensaje descriptivo. 

git push origin: Es el comando que envía las confirmaciones (commits) locales a un repositorio remoto, esto hace que los cambios puedan estar disponibles para otros colaboradores o para respaldarlos en la nube, este comando asegura que el proceso del proyecto se mantenga centralizado y actualizado .

git pull: Comando de Git que descarga los cambios más recientes del repositorio remoto y los fuciona automáticamente con la rama que estamos utilizando, este comando mantiene nuestro proyecto local actualizado, trae cualquier modificación que otros colaboradores subieron en el repositorio remoto, este codigo evita trabajar con versiones desactualizadas del código.

git rebase --continue: Este comando se usa para continuar un proceso de rebase de Git el cual se pausó por conflictos, una vez que se solucionaron los conflictos se marcan como listos usando el comando git add, se ejecuta git rebase --continue para continuar con el proceso.

git rebase main: Este comando integra los cambios más recientes de la rama main en la rama actual, se reescribe el historial de la rama para qeu aparezca que se trabajó en la version más reciente de main, esto se realiza para mantener el historial de git lineal y limpio al evitar commits innecesarios.

git diff: Comando que muestra las diferencias entre distintos puntos de un repositorio, permite observar cuales línes específicamente han sido modificadas, añadidas o eliminadas antes de confirmar los cambios coon un commit, se utiliza mucho para revisar el trabajo realizado y de esta manera asegurarse de que todo esté bien antes de agregarlo al área de staging o hacer un commit.

git log: Este comando es como un historial de todo lo que se ha hecho, permite visualizar el historial de commits realizados en el repositorio, muestra infromación como el identificador del commit, el autor, la fecha y el mensaje del commit, cada vez que se guarda un commit, Git se encarga de guardar la versión del proyecto y git log permite ver todas esas versiones junto con algunos detalles. 

git rebase -i HEAD: Este comando permite usar rebase interactivo sobre los commits más recientes, empezando desde el HEAD, en si, git rebase -i realiza acciones como: editar mensajes de commits, combinar commits, reordenar commits, eliminar commits, separar los commits en varios y unificar el historial antes de compartir el código, básicamente se utiliza como una herramienta para limpiar o mejorar el proyecto.

git commit --amend: Este comando se utiliza para modificar el último commit que se hizo, con este comando se puede cambiar el mensaje del último commit, agregar archivos que se olvidaron, quitar archivos del último commit y corregir detalles sin l anecesidad de crear un nuevo commit. 

git branch -D: Este comando se utiliza para eliminar una rama local de manera forzada, permite eliminarlo aunque temga cambios no fusionados, este comando se usa casi siempre cuando se está totalmente seguro de que ya no se necesita esa rama, cuando se creó una rama equivocada, Cuando ya hiciste backup / push y quieres limpiar localmente.

git clone: Este comando se utiliza para clonar o copiar un repositorio remoto y traerlo hacia la computadora que se está utilizando, se encarga de clonar archvios de proyecto, historial de commits, ramas y etiquetas.

git commit --amend --no-edit: Este comando se utiliza para cambiar el último commit sin editar ni cambiar su mensaje, se utiliza para agregar archivos que se olvidaron incluir en el último commit o para corregir cierto errores en el mensaje de confirmación sin tener que volver a escribirlo completamente.