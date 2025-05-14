## ✦ Parte 4 - Crear repositorio remoto y subir commits locales
Vamos a **crear un repositorio vacío en Github** donde podremos **subir el repositorio en el que hemos estado trabajando por ahora**. Al crearlo, nos va a dar una línea de código que vamos a deber seguir para poder subirlo (en este caso, usando HTTPS).

![imagen1](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p4/1.png)
![imagen2](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p4/2.png)

⋆ ```git remote add ASOCIACION ENLACE``` - Asocia el repositorio en Github con nuestro repositorio en GIT Bash, ENLACE siendo el enlace que nos proporciona Github al crearlo y ASOCIACION el nombre dado al enlace, en este caso siendo origin. 

⋆ ```git remote remove ASOCIACION``` - Podemos eliminar la asociación con este comando, si hay algún error. 

⋆ ```git remote -v``` - Nos permite ver los repositorios remotos añadidos.

⋆ ```git push -u origin master``` - Nos permitirá subir los commits que hemos hecho hasta ahora, que se guardaran en el repositorio de Github. 

⋆ ```git push --tags``` - Tras subir el resto, ejecutar este comando permitirá subir las etiquetas que hemos hecho y aplicado sobre los commits realizados. 

![imagen3](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p4/3.png)

Tras **subir todo lo que llevamos por ahora**, podemos comprobar en Github que todo esta guardado correctamente.

![imagen4](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p4/4.png)
