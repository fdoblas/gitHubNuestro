-¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1. Para hacer un reset un paso para atrás y con la opcion
--hard para que no conservemos los cambios del Working Copy.
-¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
He utilizado git reflog para ver todos los commits realizados, y después he 
realizado un git reset --hard a34ed45, siendo a34ed45 el id del commmit al que 
quiero ir.
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No, no ha causado conflicto. Me ha dicho que la rama estaba Already up to date
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Sí, si ha causado conflicto. Al hacer el merge hemos creado un hijo que apunta a dos
padres.
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No, no ha causado conflicto. Desde master al hacer el merge con styled, solo hemos tenido
que mover el puntero de la rama que abosrbe al puntero de la rama styled.
- ¿Qué comando o comandos utilizaste en el paso 25?
git log --graph --pretty=oneline --decorate
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Sí ya que al hacer el merge podriamos haber mmovido el HEAD a la rama de title y
 daría el mismo resultado.
-¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1
-¿Qué comando o comandos utilizaste en el paso 28?
git reset --hard
-¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title
-¿Qué comando o comandos utilizaste en el paso 30?
git reflog
git reset --hard b40ca15
-¿Qué comando o comandos utilizaste en el paso 32?
git checkout 2c588c4
-¿Qué comando o comandos utilizaste en el paso 33?
git checkout 698a706
