## ✦ Parte 6 - Archivo .gitignore y subir de local a remoto
#### 1. Archivo .gitignore ★
Vamos a crear una aplicación java en nuestro repositorio local. Después de crearla, podemos comprobar de que se ha creado una nueva carpeta. Podemos comprobarlo con ls -a.

Esto no mostrará que ha ocurrido una diferencia tras ejecutar el comando git diff HEAD, pero si nos devolverá algo con git status.

⋆ ```gradle init --type java-application``` - Nos permitirá crear una nueva aplicación, preguntándonos sobre como debe ser.

⋆ ```gradle run``` - Lo utilizamos para probar que se ejecuta correctamente.

![imagen1](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p6/1.png)
![imagen2](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p6/2.png)

Cuando ejecutamos git status, nos devuelve una serie de archivos sin seguimiento.

⋆ ```git status``` - Nos muestran archivos sin seguimiento, es decir, que no se han añadido al repositorio y no pueden ser seguidos por git diff.

![imagen3](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p6/3.png)

Tras realizar esto, hay algunos archivos que pueden no servirnos, por lo que podemos ignorarlos. En este caso, serán .build/ y .gradle/.

⋆ ```nano .gitignore``` - Nos permite añadir los archivos que deseamos ignorar. Para mí, .gradle y .build bienen ignorados por defecto.

![imagen4](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p6/4.png)

#### 2. Subir a Github ★
Ahora, con los archivos ignorados y la aplicación terminada; podemos subirlo a Github. Debemos añadir todo al área de preparación y empujarlo todo a Github.

⋆ ```git add .``` - Añade los archivos que se han creado con la aplicación al área de preparación.

⋆ ```git commit -m NOMBRE``` - Hacemos un commit, guardándolo con un nombre, yo lo he llamado "Código fuente inicial".

⋆ ```git tag v3``` - Le damos una etiqueta, haciéndolo más fácil para subir.

⋆ ```git push origin v3``` - Lo subimos a nuestro repositorio. Debemos comprobar si se ha hecho correctamente.

![imagen5](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p6/5.png)
![imagen6](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p6/6.png)
![imagen7](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p6/7.png)
