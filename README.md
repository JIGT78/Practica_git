# Practica_git
Repositorio para la entrega de la práctica final del módulo git.

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?

git reset --hard HEAD~1
Porque deshace el ultimo commit y lo que había en mi working copy de manera que todo quede como estaba antes.
Nuestro staging area queda vacío.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

git reflog
Para ver los ultimos commits por los que he pasado y ver el identificador del commit al que quiero ir.

git reset --hard e6d5ae1
Para moverme al commit anterior.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No porque ambas ramas contienen los mismos commits, ambas están actualizadas la una con respecto a la otra.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Si, porque se realizaron cambios en las mismas lineas.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

No, no causo conflictos. Porque main ya tenia los cambios de la rama styled.

- ¿Qué comando o comandos utilizaste en el paso 25?

git log --graph

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

Si, porque la rama main no tiene commits que la rama title no tenga.git

- ¿Qué comando o comandos utilizaste en el paso 27?

git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28?

git restore git-nuestro.md

- ¿Qué comando o comandos utilizaste en el paso 29?

git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?

git reflog
git reset --hard 7a7149c

- ¿Qué comando o comandos usaste en el paso 32?

git reflog
git checkout 8e1e707

- ¿Qué comando o comandos usaste en el punto 33?

git reflog
git checkout 6cffc1a
