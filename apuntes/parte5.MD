### ✦ Parte 5 - Deshacer cambios en repositorio local
Vamos a ver que podemos hacer cuando cometemos un error. Como ejemplo, modificaré mi README.md con nano *README.md*, eliminando dos de las líneas que hay en el archivo.
	- ```git reset --hard``` - Nos devuelve a donde estábamos antes de hacer el cambio.

(imagen)

Esto funciona de todas formas aunque hubiéramos añadido el archivo al área de preparación.

(imagen)

Si hubiéramos hecho un commit, simplemente tenemos que hacer que el commit retroceda (en este caso, solo un commit).
	- ```git reset --hard HEAD~1``` - Nos devuelve un commit hacia atrás. Podemos ir incrementando el número de los commits que retrocedemos.

(imagenes)
