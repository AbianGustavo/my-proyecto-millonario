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

Las ramas las usamos para llevar un mejor control del código. Se trata de una bifurcación del estado del código que crea un nuevo camino de cara a la evolución del código, en paralelo a otras ramas que se puedan generar. Las ramas nos pueden servir para la creación de una funcionalidad que queramos integrar en un programa y para la cual no queremos que la rama principal se vea afectada. Esta función experimental se puede realizar en una rama independiente, de modo que, aunque tardemos varios días o semanas en terminarla, no afecte a la producción del código que tenemos en la rama principal y que permanecerá estable.

A la hora de aplicarlo en un proyecto el trabajo con ramas resulta muy cómodo, porque es posible que todas las ramas creadas evolucionen al mismo tiempo, pudiendo el desarrollador pasar de una rama a otra en cualquier momento según las necesidades del proyecto. Si en un momento dado el trabajo con una rama nos ha resultado interesante, útil y se encuentra estable, entonces podemos fusionar ramas para incorporar las modificaciones del proyecto en su rama principal.

### ¿Se tendrían que producir conflictos en esta acción? [Si/No] Justifica tu respuesta.

No se tendría que producir ningún conflicto dado que se ha hecho correctamente el comando merge junto el nombre de la rama que queremos fusionar y se ha hecho estando situados en la rama que queremos usar como base.
