# Cierre. nuestro proyecto completo
En el README, explica cómo desarrollarías una pequeña aplicación o juego.

- 01. Problema, plataforma y lenguaje.

Un juego de plataformas en 2D con estilo pixel-art/8-bits, donde hay que ir superando fases para poder pasar a la siguiente e ir consiguiendo habilidades nuevas. Con un botón se puede cambiar el plano y/o perspectiva que tiene el personaje principal para poder ver el escenario desde distintos ángulos. El juego incluye un menú principal ambientado en el estilo predefinido que incluye un apartado para iniciar el juego y un apartado de ajustes para ajustar el volumen. Hay un mapa con varios niveles, mediante se vayan superando se irán desbloqueando los demás.
Tengo pensado que el juego sea para navegador web, en lenguaje html.

- 02. Algoritmo o ejemplo de paradigma que usarías.

Para cambiar la perspectiva del juego se usaría una variable para almacenar en que perspectiva se encuentra actualmente el personaje:

int perspectiva = 1;

Cuándo se use una habilidad, por ejemplo invertir la gravedad se almacena en un while, mientras se cumpla x condición la gravedad se mantiene invertida o no.

while (gravedad = 0) {
    Se mantiene la gravedad normal

}

while (gravedad = 1) {
    Se mantiene la gravedad invertida
    
}


- 03. Cómo llega el código a ejecutarse.

Para ejecutar el juego únicamente se necesita ejecutar el archivo principal del html desde el navegador web. Para mayor optimización se usa un archivo para cada apartado, personaje, escenarios, efectos, habilidades, controles, etc... Cada vez que sea necesario desde el archivo principal se van llamando a los demás mediante enlaces.

- 04. Commit, push y comprobación.

Desde github desktop hacemos un commit del readme.md para guardar el archivo y un push para subirlo a nuestro repositorio, posteriormente comprobamos que se vea en la web.