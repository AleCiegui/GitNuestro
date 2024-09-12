# GitNuestro
Practica de GitHub

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1
Deshace los cambios un commit atras y con --hard elimina tambien los cambios del working copy

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
vuelvo a editar el archivo y uso "git add" y "git commit" para subirlos.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
hago "git merge main" pero no me da ningun error. piendo que es porque ya estoy en la rama styled y no hay cambios que añadir de main a styled

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Si, porque en el commit de styled se hicieron cambios en el archivo git-nuestro.md y ahora hay otros cambios distintos en esta otra rama. Git quiere saber cuales líneas hay que guardar

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No, todos los archivos son iguales.

- ¿Qué comando o comandos utilizaste en el paso 25?
git log --oneline --graph --all , aunque también lo voy viendo mejor en sourcetree.

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
No, porque tiene que absorber los cambios que tuviesen los cambios de la rama title.

- ¿Qué comando o comandos utilizaste en el paso 27?
 git reflog para ver el commit anterior directamente
 git reset --soft e440529, para desacer el merge sin perder los cambios a los archivos.

- ¿Qué comando o comandos utilizaste en el paso 28?
git restore --staged git-nuestro.md para volver a estado anterior al git add
git restore git-nuestro.md para eliminar los cambios
- ¿Qué comando o comandos utilizaste en el paso 28?
- ¿Qué comando o comandos utilizaste en el paso 29?
- ¿Qué comando o comandos utilizaste en el paso 30?
- ¿Qué comando o comandos usaste en el paso 32?
- ¿Qué comando o comandos usaste en el punto 33?