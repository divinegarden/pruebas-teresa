## ✦ Parte 10 - Fusión y eliminación de ramas
#### 1. Fusionar ★
Anteriormente, hemos creado varias ramas de dos formas diferentes, de forma que después podamos añadirlas a nuestra rama master. Posicionados en esta rama, podemos empezar a fusionar las ramas que queremos dentro de ella. Añadiremos rama1, licencia y autor.

⋆ ```git merge NOMBRE_RAMA``` - Une la rama que mencionamos con el commit en el que estamos posicionados actualmente.

![imagen1](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p10/1.png)
![imagen2](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p10/2.png)
![imagen3](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p10/3.png)

#### 2. Eliminar ★
Tenemos una rama que no hemos añadido, siendo la rama2. Esta vamos a coger la oportunidad para eliminarla de nuestro repositorio.

⋆ ```git branch -D NOMBRE_RAMA``` - Elimina la rama que mencionamos, después de asegurarse y preguntarnos si queremos eliminarla.

![imagen5](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p10/5.png)

#### 3. Subir al repositorio ★
Con esto hecho, podemos subirlo todo a nuestro repositorio, pero necesitaremos eliminar los apuntadores de las ramas que hemos fusionado, en local y remoto.

Para eliminarlos, debemos hacerlo para local y remoto.

⋆ ```git branch -d NOMBRE_RAMA``` - Elimina el apuntador de la rama que mencionemos en local. En este caso, solo eliminaremos rama1.

⋆ ```git push origin --delete NOMBRE_RAMA``` - Elimina el apuntador de la rama que mencionemos en Github.

![imagen4](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p10/4.png)
