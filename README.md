# buscaminas
Buscaminas programado en c++.


Este repositorio contiene un juego de Campo Minado implementado en C, diseñado para ser jugado en la línea de comandos. El juego simula un campo de minas en un tablero de 9x9 casillas, con 3 minas ocultas. El objetivo es descubrir todas las casillas que no contienen minas sin detonar ninguna de ellas.

Características principales del juego:

Inicialización del Tablero: El tablero se inicializa con todas las casillas cubiertas, representadas por el carácter '#'. Las minas se distribuyen aleatoriamente en el tablero.

Jugabilidad: El jugador selecciona casillas para descubrir, eligiendo coordenadas en el tablero. Puede marcar casillas sospechosas de contener minas con una bandera ('B').

Conteo de Minas Adyacentes: El juego calcula y muestra el número de minas en las casillas adyacentes a cada casilla descubierta, proporcionando pistas al jugador.

Verificación y Resolución: Si una casilla con una mina es descubierta, se muestra un '@' y el juego termina. El juego también finaliza exitosamente cuando todas las casillas sin minas son descubiertas.

Funciones Auxiliares: Incluye funciones para limpiar el tablero, imprimir el tablero, contar las bombas adyacentes a cada casilla y analizar cada casilla para determinar si contiene una bomba.

El repositorio incluye el código fuente y un archivo de encabezado (header.h). El juego es interactivo y se maneja mediante la entrada estándar del usuario, lo que lo hace accesible y fácil de jugar. Es adecuado para aquellos que desean practicar sus habilidades de programación en C, así como para los entusiastas de los juegos de lógica y estrategia.
