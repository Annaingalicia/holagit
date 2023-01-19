# Laboratorio. Subir el primer proyecto en GitHub

## Los pasos
* Creamos una carpeta "MiPrimerProyectoGit"
* Iniciamos el trabajo con la carpeta creada utilizando el comando git init
* Añade ficheros de texto y tipo .html al repositorio. 
** hola.txt
** git.txt
** index.html
** nosotros.html
*Guardamos los cambios hechos en los archivos de la carpeta local con el comando __git add .__
* Realizamos el primer commit con el comando -__it commit -m "my first commit"__
* Realizamos cambios en dos archivos y hacemos el nuevo commit
* Para subir el proyecto en GiHub utilizamos los comandos:
** __git remote add https://github.com/Annaingalicia/holagit.git__
** __git branch -M main__
** __git push -u origin main__

# Comandos aprendidos realizando los ejercisios en clase:

* __git log --oneline --graph --decorate --all__

* __git diff__ -muestra los cambios con respecto a la última versión guardada en el repositorio.

* __git show__ - muestra los cambios de la última versión del repositorio con respecto a la anterior.

* __git commit --amend -m__ "Añadido capítulo 3 sobre gestión de ramas al índice." - es una forma de modificar el íltimo commit

* __git clone https://github.com/asalber/libro-git.git__ - hace un un clon de un repositorio remoto

* __git reset --hard 8c808 (versión)__ - Modifca el HEAD, el índice de archivos y el contenido local. El estado del proyecto es el equivalente al que se encontraba en el commit al que fue reseteado.

* __git remote remove origin__ - elimina los archivos de origen clonados del repositorio remoto

* __git diff HEAD~2..HEAD__ - muestra las diferencias entre la última versión y dos versiones anteriores.

* __git diff bd7f788(número de la primera versión puede ser diferente)..HEAD__ - muestra las diferencias entre la primera y la última versión del repositorio.

* __git annotate(ruta del archivo)__ - muestra quién ha hecho cambios sobre un archivo
