# Acordeón Git

### $ git init
 - Inicializa un nuevo repositorio

### $ git status
- Nos muestra el estado actual de nuestros archivos

### $ git add <archivo> | -A
 - Este comando empieza a seguir a uno o más archivos y los agrega al área de preparació, generando un nuevo estado de nuestro proyecto.
 - La bandera -A  suma todos los que estén en nuestro repositorio
 
### $ git commit
- registra nuestro nuevo estado y lo registra en la historia de nuestro repositorio. Se usa generalmente con -m y un pequeño texto que describa lo que hicimos.

### $ git log [ --oneline <archivo>]
- Muestra el historial de commits que hemos hecho en nuestro proyecto.
- --oneline muestra cada entrada en una sola línea
- Escribiendo el nombre del archivo muestra los commits de ese archivo.

### .gitignore
- Archivo que nos permite ignorar archivos o directorios los cuales no queremos que entren en el seguimiento de nuestro repositorio.
- Contenido: nombres de archivos (se puede utilizar el wildcard *)

### $ git checkout
- Permite movernos entre commits o incluso ramas de nuestro repositorio. Como argumento se introduce el id del commit o parte de él.

### $ git revert <id>
- Revierte un estado, generando un nuevo commit.

### $ git reset
- Regresa al último estado guardado, borrando permanentemente cualquier cambio en el área de pruebas. Lleva la bandera --hard . Antes del commit (los add)

### $ git clean
- Borra permanentemente los archivo no seguidos. Lleva la bandera -f

### Branching
git branch [<rama>]
- Lista las ramas existentes en el repo
- Crea una nueva rama si le pasa un argumento (nombre de la rama)

### Merging
git Merge <rama_objetivo>
- Une dos ramas

Conflictos de merging
- A veces si se está trabajando con 2 ramas al mismo tiempo, modificando un mismo archivo, se pueden generar conflictos, por lo que hay que corregirlos.

