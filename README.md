#Práctica del curso de git, gitHub y Sourcetree
##Ejercicio 1

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
  'git reset --hard HEAD~1'
  Tenemos que usar --hard ya que indica que debemos perder los cambios realizados en nuestra working copy.
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
  'git reflog' Para listar los commits hechos y 'git reset "id"' para rehacer el commit.
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
  No, ya que el contenido del git-nuestro.md es el mismo.
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
  No me ha dado conflicto. Pero tengo la duda si lo estoy haciendo correctamente. Me dice y no se muy bien que significa lo de recursive.
  '''
  Merge made by the 'recursive' strategy.
  git-nuestro.md | 21 ++++++++++-----------
  1 file changed, 10 insertions(+), 11 deletions(-)
  '''
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
  No causo conflicto.
- ¿Qué comando o comandos utilizaste en el paso 25?
  'git log --graph --decorate --pretty=oneline'
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
  Si, ya que habia una "linea" directa entre ellos.
- ¿Qué comando o comandos utilizaste en el paso 27?
  'git reflog' Buscamos el commit previo al merge y hacemos 'git reset id'
- ¿Qué comando o comandos utilizaste en el paso 28?
  'git reset HEAD~1' y luego un 'git restore git-nuestro.md'
- ¿Qué comando o comandos utilizaste en el paso 29?
  'git branch -D title'gi
- ¿Qué comando o comandos utilizaste en el paso 30?
  'git reflog' Buscamos el commit del merge y hacemos 'git reset id'
- ¿Qué comando o comandos usaste en el paso 32?
  'git reflog' Buscamos el commit inicial y hacemos 'git reset id'
- ¿Qué comando o comandos usaste en el punto 33?
  'git retore git-nuestro.md'
