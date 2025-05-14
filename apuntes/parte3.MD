### ✦ Parte 3 - Etiquetar commits y ver diferencias
En GIT, podemos añadirle etiquetas a nuestros commits y ver las diferencias entre ellos, es decir, que podemos ver los cambios que hemos hecho respecto al anterior.

#### 1. Etiquetar commits ★
Etiquetar un commit nos puede ayudar a varias cosas; identificar las versiones, acceder a ellas de una forma más rápida, ponerles mensajes... etc.
	- ```git tag -a ETIQUETA -m MENSAJE HASH``` - Con este comando, podemos etiquetar nuestros commits; ETIQUETA siendo el nombre que le damos, MENSAJE alguna nota que queramos darle, y HASH el hash del commit que queramos etiquetar. 

(imagen)
― Es más cómodo usar la etiqueta que el hash cuando usamos `git checkout`.

#### 2. Comparar commits ★
Hay varios comandos para comparar dos commits, para ver las diferencias que hay sobre el commit realizado anteriormente.
	- ```git show ETIQUETA/HASH``` - Nos muestra la diferencia que hay entre el commit indicado y el realizado anteriormente, ETIQUETA/HASH siendo el identificador que vamos a usar para mencionar el commit.
	- ```git show ETIQUETA/HASH..ETIQUETA/HASH``` - Nos muestra la diferencia entre los commits mencionados.

(imagenes)

También podemos hacer lo mismo utilizando el comando `git diff`.
	- ```git diff ETIQUETA/HASH``` - Como show, nos muestra la diferencia que hay en comparación con el commit realizado anterior a este, ETIQUETA/HASH siendo el commit que queremos ver.
	- ```git diff ETIQUETA/HASH..ETIQUETA/HASH``` - Nos muestra la diferencia entre los commits mencionados.

(imagenes)
