## ✦ Parte 1 - Inicializar repositorio local

**Para crear un repositorio**, primero vamos a necesitar **una carpeta** donde guardar los archivos. En ella, es donde lo iniciaremos y realizaremos todos nuestros commits.

```mkdir pruebas-NOMBRE``` - Creamos la carpeta, donde NOMBRE será el nombre del desarrollador. 

```cd pruebas-NOMBRE``` - La accedemos, entrando en su interior.

```ls -la``` - Para comprobar que la carpeta está vacía.

```git init``` - Nos permitirá inicializar nuestro repositorio. Si volvemos a ejecutar el comando `ls -la`, podremos comprobar que hay unas nuevas carpetas en su interior.

![imagen1](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p1/1.png)
![imagen2](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p1/2.png)

Primero, vamos a crear un **README.md**, donde escribiré mi nombre y realizaremos **el primer commit**; añadiéndolo al **área de preparación** y añadiéndolo al **repositorio**. Con esto hecho, podemos repetir el proceso varias veces.

```nano README.md``` - Nos ayudará a crear y/o editar el archivo, donde dentro escribiremos lo pedido. En este caso, es simplemente el nombre completo, y después añadiré la fecha (en la que se hizo la actividad), y mi centro educativo.

```git add README.md``` - Añadirá el archivo al área de preparación.

```git commit -m "NOMBRE"``` - Se guardará el commit, NOMBRE siendo el nombre que se le quiere dar al commit. En este caso, será *"Primer cambio guardado"*. 

![imagen3](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p1/3.png)

Cuando hayamos creado todos los commits que queremos, podemos comprobarlos utilizando `git log --oneline --all`, que los mostrará de una forma más resumida.

![imagen4](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p1/4.png)
