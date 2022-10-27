- **git add:** Añade los ficheros al control de git.
- **git commit -m "Mensaje informativo":**  Grabar los cambios realizados con un mensaje.
- **git branch "Nombre de la rama":** Crea una rama en el repositorio en el que estamos trabajando.
- **git branch -d "Nombre de la rama":** Borra la rama que hemos indicado.
- **git log:** Muestra un historial de los commits realizados.
- **git status:** Nos permite consultar y comprobar los nuevos cambios locales.
- **git checkout:** Nos permite cambiar entre ramas.
- **git annotate:** Nos permite ver las diferencias entre unos commits / archivos.
- **git merge:** Fusiona dos ramas en las que estemos trabajando

### ¿Si has clonado el repostorio que parte del comando anterior puedo omitir? Justifica tu respuesta.

Se puede omitir "origin master" dado que la rama por defecto es main.

### ¿Se deben de subir el fichero y el directorio privado al repositorio si se encuentra añadido al fichero .gitignore. [Si/No]?  Justifica tu respuesta.

No, dado que con el .gitignore se indica que estos cambios no se deben subir en la nube y por ello tienen que quedarse en local.

### ¿Si ejecutamos las acciones add y commit, que realiza cada una sobre los ficheros? Justifica tu respuesta.

Al realizar un git add, añadiremos dichos elementos al control de git para más tarde gracias al commit grabar los cambios realizados.

### ¿Qué es un tag sobre un repositorio git, en nuestro caso Github? Justifica tu respuesta.


Un tag sirve como una rama firmada que se mantiene inalterable. Es una cadena arbitraria que apunta a un commit específico. Puede decirse que un tag es un nombre que puedes usar para marcar un punto específico en la historia de un repositorio.

### ¿Cuando estamos trabajando con ramas, cual es su fin, y sentido en organizaciones pequeñas/medianas/grandes? Justifica tu respuesta.

### ¿Se tendrían que producir conflictos en esta acción? [Si/No] Justifica tu respuesta.
