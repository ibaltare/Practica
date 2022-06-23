### ¿Qué comando utilizaste en el paso 11? ¿Por qué?
comando:git reset --hard HEAD~1
reestablecemos HEAD una posición hacia atrás y el modo hard descarta todos los cambios realizados.

### ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
Comando: git reset --hard 7097079
reestablecemos HEAD al hash del ultimo commit (lo encontramos con git reflog) 
y el modo hard descarta todos los cambios realizados.

### El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No causo conflicto, no había cambios en main que pudieran entrar en conflicto con styled

### El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
El merge causo conflicto por que el archivo git-nuestro.md ha sido editado en las mismas líneas en cada rama.

### El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No causo conflicto porque el archivo git-nuestro.md solo ha sido modificado en una de las ramas

### ¿Qué comando o comandos utilizaste en el paso 25?
git log –graph

### El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Si podría ser fast-forward por que los commits están en lista, si después de hacer el merge tanto fast-forward 
como no fast-forward, deseamos regresar al commit anterior nos darían el mismo resultado, no perderíamos trabajo.

### ¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1

### ¿Qué comando o comandos utilizaste en el paso 28?
git restore git-nuestro.md

### ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title

### ¿Qué comando o comandos utilizaste en el paso 30?
git reflog
git reset –hard 4e815bc

### ¿Qué comando o comandos usaste en el paso 32?
git reflog
git checkout 005df72

### ¿Qué comando o comandos usaste en el punto 33?
git checkout main

