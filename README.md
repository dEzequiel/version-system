# Version System - ES

## Preparación

Podemos crear y posicionarnos dentro de una nueva rama con:

`git checkout -b develop`

Clonar el repositorio base

`
git@github.com:JuanLlado/Practica4.git
`

Dentro del repositorio eliminar el archivo oculto `.git` que hace referencia a estar bajo el control de versiones.

Podemos ver el historial de commits, identificadores y tags para volver atras en las versiones del proyecto.

`git log --oneline`

![git-log](images/1-git-log.png)

Podemos retroceder en las versiones del proyecto con su identificador con `git reset`.

`git reset ee9c6ae`

![git-reset](images/2-git-reset.png)

Si hacemos un `git log` podemos ver en que tag del proyecto nos encontramos.

![3-git-log](images/3-git-log.png)