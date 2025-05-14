### ✦ BONUS (2) - Optimización
La optimización de código es el proceso de poder mejorar la eficiencia, el rendimiento y la rentabilidad del código de una aplicación. No es solamente que haga lo que se pide, si no que lo haga de una forma eficiente.

#### 1. La hediondez del código ★
Existen los "code smell"s (o conocido como una hediondez del código), que es algo parecido a una deficiencia, indicando un problema más profundo. Puede ser código duplicado, clases que no hagan mucho, identificadores muy largos, etc...

Podemos hacer dos tipos de análisis, dinámico y estático.
- El análisis estático (lints) se puede realizar mediante analizadores estáticos (como lint para C, sonar para Java...) o mediante sitios web (como Scrutinizer y SonarQube).

#### 2. La refactorización ★
La refactorización es modificar un código de forma que no cambie como este se comporta. Puede ser para hacerlo más legible, eficiente, o mantenible. Existen varias técnicas para hacerlo.
- 1. Renombrar variables; para que sean más descriptivas sobre su función.
- 2. Eliminar código redundante; código que nos podemos ahorrar de una forma u otra.
- 3. Simplificación de condicionales; que se pueden hacer con código más corto y más legible.
- 4. Añadir constantes en vez de números mágicos; para evitar modificarlos y poder acceder a ellos de una forma más fácil.
