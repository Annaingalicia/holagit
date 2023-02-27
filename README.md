# Laboratorio. Subir el primer proyecto en GitHub

## Los pasos
* Creamos una carpeta "MiPrimerProyectoGit"
* Iniciamos el trabajo con la carpeta creada utilizando el comando git init
* Añadimos ficheros de texto y dos ficheros tipo .html al repositorio. 
* hola.txt
* git.txt
* index.html
* nosotros.html

* Guardamos los cambios hechos en los archivos de la carpeta local con el comando __git add .__

* Realizamos el primer commit con el comando -__git commit -m "my first commit"__
* Realizamos cambios en dos archivos y hacemos el nuevo commit
* Para subir el proyecto en GiHub utilizamos los comandos:
* __git remote add https://github.com/Annaingalicia/holagit.git__
* __git branch -M main__
* __git push -u origin main__

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

# Laboratorio 3
## Comandos aprendidos

* _git reset --soft HEAD~__ - Deshace el último commit pero mantiene los cambios anteriores en el directorio de trabajo y la zona de intercambio temporal.
* _git reset --mixed__ - deshace todos los cambios entre HEAD y último commit, pero conservará los cambios en el directorio de trabajo (va a volver al estado unstaged)
* _git reset --hard HEAD~__ - Deshace el último commit y los cambios anteriores del directorio de trabajo volviendo a la versión anterior del repositorio.
* _git clean -f_ - Deshace los cambios realizados para volver a la versión del repositorio.
* _git restore --staged_ - Deshace cambios del estado Index(stage)
* _git restore_ - Elimina los cambios en el directorio de trabajo
- _git checkout_- si previamente modificamos un archivo, pero no queremos guardar los cambios, ese comando devolvera el archivo en el estado previo a los cambios. Hay que tener cuidado con ese comando, ya que no va a ser posible a recuperar los cambios.

# Laboratorio 4
## Gestión de ramas

1. *git branch* - crea una nueva rama
2. *git branch -av* - muestra las ramas del repositorio
3. *git checkout* - cambia a la rama que indiquemos
4. *git merge* - fusiona la rama indicada
5. *git commit -am* - Añade los cambios a la zona de intercambio temporal y hace un commit

# Repositorios remotos

1. *git remote add github url* - añade al repositorio local un repositorio ya creado en GitHub
2. *git remote -v* - muestra todos los repositorios remotos configurados.
3. *git push github master* - añade los cambios del repositorio local al repositorio remoto de GitHub.
4. *git push origin master* - el comado para subir los cambios al repositorio remoto

