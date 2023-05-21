# blogpost-git

## Mi first blog using git and github

```
git init:  
```
> inicializar un repositorio

```
git config
```
> ver la configuracion de git

```
git config --list
```
> ver la lista de configuacion basica

```
git config --global user.name "[user_name]"
git config --global user.email "example@gamil.com"
```
> configurar el nombre de usuario y el correo del usuario

```
git add .
```
> Agregar a stanging (RAM) el archivo o ponerlo en un estado tracked

```
git commit -am
```
> Este realiza el add de manera automatica, pero solo funciona cuando los archivos esten en staging.

```
git rm --cached
```
> Borrar un archivo del staging pero se mantienen en el disco duro.

```
git rm --force
```
> Elimina los archivos de Git y del disco duro.

```
git commit -m "mesaje de guardado"
```
> Hace un commit en nuestro repositorio local.

```
git status
```
> Para ver el estado del stanging.

```
git log
```
> Para ver el historial de commits.

```
git log --oneline
```
> Para ver el historial de commits mas limpio.

```
git log --stat
```
> Ver las estadisticas de los cambios que hemos realizado.
	
```
git diff #commit1 #commit2
```
> Para ver las diferencias entre un archivo y otro. 

```
git show
```
> Muestra los cambios del ultimo commit 

```
git reset HEAD
```
> Este es el comando para sacar archivos del área de Staging.

```
git reset #commit [--soft] [--hard]
```
> Volvemos al archivo en la version de commit indicada.

```
git checkout #commit
```
> Podemos revisar una version anterior.

	 
```
git checkout master archivo.extencion
```
> Volvemos al archivo con el ultimo commit realizado.

## Manejo de ramas:
	
```
git branch : Permite ver las ramas que tengo creadas hasta el momento.
git branch -d nombreRama : Nos permite borrar una rama  
git merge : Permite la funcion entre ramas

Git con Github:
git remote add origin *url : Con este comando indicamos el origen del repositorio remoto 
git remote : Vemos que estamos conectados al origen 
git remote -v : Nos despliega el origen que establecimos para hacer fetch y pull

git push origin master : Para mandar nuestros datos al repositorio remoto
git pull origin master : Para traer los datos a nuestro repositorio local
git pull origin master --allow-unrelated-histories : Permite fucionar el historial de commits del local al remoto 	 
```

## Notas
	
- Para salir del editor de texto de VIM es Esc + Shift + z + z 
- Push : Es para enviar datos al servidor remoto 	
- Pull: Para traer datos del servidor remoto

## Comando terminal de linux:

ls: Para desplegar la lista de carpetas y archivos 
ls -l: Para desplegar las carpetas y archivos en lista 
ls -la: Para desplegar los archivos ocultos 

cd 'directorio' : Para moverse entre los directorios (carpetas)
cd .. : Para moverse atras 
cd c : Para ir al dis C
cd /: Para ir a la raiz del linux emulado de la terminal 

mkdir 'nombreCarpeta': Crear una carpeta (directorio)
rm 'archivo.extencion' : Eliminar archivos
rmdir: Eliminar una carpeta 
rm -r: Eliminar carpetas y archivos contenidos. 