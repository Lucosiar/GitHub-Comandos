En caso de que quieras descargar el archivo lo tienes en un Notebook de Jypiter, sino te lo comento:
# GitHub
GitHub es una forja para alojar proyectos de software. Está basado en Git, es un sistema de control de versiones distribuido que permite a los desarrolladores trabajar en un proyecto simultánea. Facilita la colaboración y gestión de proyectos a través de herramientas que permiten el mantenimiento de cambios, gestión de versiones e integración continua.

# Git
Git es un sistema de control de versiones que permite rastrear los cambios en tus archivos y coodinar el trabajo de múltiples personas. A diferencia de otros sistemas, Git es distribuido, lo que significa que cada desarrollador tiene una copia completa del historial del proyecto.

### Comandos principales de Git
# Inicializar un repositorio.
git init

# Clonar un repositorio.
git clone <url_del_repositorio>

# Comprobar estado de los archivos.
git status

# Agregar archivos.
git add <archivo_o_directorio>

# En caso de agregar todos los archivos modificados.
git add .

# Mensaje de confirmación de cambios.
git commit -m "Mensaje descriptivo"
# Para mi los mensajes suelen ser cortos y concisos.

# Ver el historial de cambios
git log

# Crear una nueva rama
git branch <nombre_de_la_rama>

# Cambiar de una rama a otra / Movernos entre ramas
git checkout <nombre_de_la_rama>

# Crear y cambiar a una nueva rama en un solo paso:
git checkout -b <nombre_de_la_rama>

# Combinar ramas
git merge <nombre_de_la_rama>

# Enviar cambios al repositorio remoto
git push origin <nombre_de_la_rama>
# Yo suelo usar siempre:
git push -u origin master

# actualizar tu repositorio local
git pull

# Eliminar un archivo de tu repositorio remoto
git rm <archivo>

# Revertir cambios
git revert <hash_del_commit>

# Ver los cambios realizados
git diff

# Agregar un repositorio remoto
git remote add origin <url_del_repositorio>

# Clonar un repositorio
git clone <url_del_repositorio>





