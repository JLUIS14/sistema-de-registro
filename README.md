< H1 > Sistema de registro </ H1 >

- Estado del proyecto en construcción.

- para ejecutar el sistema, debes poner:
- ```npm install react```
- estoy agregando texto para actualizar este cambio en mi carpeta local.
- para restaurar a su estado anterior debo usar git restore -- source codigo obtenido de git log --oneline Nombre del archivo
- para ver el codigo de las modificaciones debo usar git log --oneline
- para ver el estado git status
- para actualizar git add .
- para comprometerse git commit -m "accion lo que debe hacer"
- para subir al github git push
- para actualizar el archivo desde el respositorio a la carpeta local git pull
- Para agregar los cambios realizados de una sola vez, es necesario usar git add . (git add y un punto) y,
-  para agregar los cambios en algún archivo específico, usamos a git add nombre-del-archivo-modificado.
- git checkout para ver las ramas y para crear una rama
- git checkout -b desarrollo  se crea la rama desarrollo
- git switch para cambiar a una rama o principal
- git push origin desarrollo para actualizar el github desde la consola que no es la principal
- git pull origin Principal "para actualizar los cambios a la carpeta local cuando existen ramas"
- hay dos formas de crear una rama
- git checkout -b git branch nombre-de-la-branch
- git branch nombre-de-la-branch  "solo que en esta opcion para pasar a la branch se debe usar git switch nombre de la branch
- git checkout main
- git fetch origin main
- git rebase -i origin/main

- git push origin main  todo este paquete hace que todas tus confirmaciones de tu rama principal envie al repositorio remoto principal
