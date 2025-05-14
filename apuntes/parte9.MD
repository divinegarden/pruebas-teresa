### ✦ Parte 9 - Creación de ramas
Podemos crear ramas de nuestro repositorio utilizando dos comandos; git checkout -b y git branch. En esta parte, lo vamos a hacer de ambas formas.
#### 1. git checkout -b ★
Con este comando; vamos a crear, por ejemplo, una rama desde el primer commit que hicimos, etiquetado V1. Dentro, vamos a crear un archivo, y vamos a hacer un commit. Si nos movemos, nos depegaremos, por lo que podemos hacer otra rama y repetir el proceso.
	- ```git checkout -b NOMBRE_RAMA COMMIT``` - Permite crear una rama a partir de un commit, donde NOMBRE_RAMA será el nombre de la rama y COMMIT será de donde queremos sacar la rama, donde nos posicionará inmediatamente.

(imagenes)

De esta forma, podemos estar seguros de que no se van a perder nuestros cambios al comprobarlo.

#### 2. git branch ★
Este comando se usa de una forma prácticamente idéntica al anterior, excepto que vamos a necesitar cambiar a nuestras ramas manualmente. Vamos a crear dos ramas similares a las anteriores.
	- ```git branch NOMBRE_RAMA COMMIT``` - Permite crear una rama, como el comando usado anteriormente; excepto que este requiere que nos movamos a la nueva rama.
	- ```git checkout NOMBRE_RAMA``` - Nos mueve a la rama que queremos visitar.

(imagenes)

#### 3. Subir al repositorio ★
Con esto hecho, podemos subir nuestras nuevas ramas a nuestro repositorio.

(imagenes)
