### ✦ Parte 7 - Usando un par de claves SSH
Vamos a crear una clave SSH para poder subir nuestros nuevos commits sin necesitar dar la contraseña. Esto necesitará unos ajustes en nuestra cuenta, y la ejecución de algunos comandos.
	- ```ssh-keygen``` - Crea una serie de claves, pidiendo donde se guardarán y una contraseña para ellas.

(imagen)

Con estas claves creadas, podemos añadirlas a nuestra cuenta de Github. Deberemos entrar en Ajustes > SSH and GPG keys y añadirla ahí.

(imagen)

Tras esto, debemos cambiar el origen de nuestro repositorio local y añadir el enlace por SSH. 
	- ```git remote -v``` - Nos permite ver los repositorios remotos añadidos.
	- ```git remote remove ASOCIACION``` - Nos permitirá eliminar la asociación anterior. 
	- ```git remote add ASOCIACION ENLACE``` - Podremos añadir el nuevo enlace SSH a nuestro repositorio local, también lo haremos con el nombre origen. 

Con esto añadido, vamos a hacer una prueba de que funcione. Modificaremos nuestro archivo README.md, y le añadiremos unas citas. Le haremos commit, y lo subiremos. Debemos comprobarlo, justo después.

(imagenes)
