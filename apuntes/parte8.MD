## ✦ Parte 8 - Resolviendo conflictos
Vamos a hablar como poder **prevenir posibles conflictos** entre **nuestro repositorio local y en Github**. Para **realizar la prueba**, nosotros modificaremos nuestro *README.md* en ambos lugares, para comprobar si **funciona correctamente** o nos **da un error y/o conflicto**.

![imagen1](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p8/1.png)

En mi caso, me da error (no por conflicto, pero aun así). Podemos **utilizar un comando** para obtener lo que hay en nuestro repositorio remoto, y **manejar el conflicto** desde ahí.

⋆ ```git pull``` - Permite sacar lo guardado/los commits que no existen en nuestro repositorio local desde el remoto en Github.

![imagen2](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p8/2.png)

Por alguna razón, a mi se me ha guardado correctamente, **pero en el caso de que esto no pase**; debemos elegir una de las opciones que hay rodeadas por **<<<<<< y >>>>>>**. Tras hacer eso, podemos volver a subirlo.

![imagen3](https://github.com/divinegarden/pruebas-teresa/blob/master/apuntes/imagenesProyecto/p8/3.png)
