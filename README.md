# Desarrollo-de-un-juego-2D-utilizando-JavaScript
Paso 1: La estructura del documento HTML es muy simple, porque todo el juego se visualizará dentro del elemento <canvas>.

Paso 2: Definir un blucle de dibujo. Técnicamente, estaremos pintando la pelota en la pantalla, borrándola y luego pintándola de nuevo en una posición ligeramente diferente cada fotograma para dar la impresión de movimiento, igual que se hace en las películas.

Paso 3: Detección de colisión simple, Para detectar la colisión verificamos si la bola está tocando (chocando con) la pared y si es así, cambiaremos la dirección de su movimiento en consecuencia.

Paso 4: Se define una paleta para golpear la bola y se le da el control al usuario para controlarla.

Paso 5:Implementar el final del juego, En lugar de dejar que la pelota rebote en las cuatro paredes, vamos a permitir que lo haga sólo en tres: izquierda, arriba y derecha. cuando la pelota colisione con el borde inferior del terreno de juego se activara el estado "final del juego" y detectaremos la colicion de la bola y la paleta, haciendola rebotar para que vuelva a la zona de juego.

Paso 6: Construir el muro de ladrillos y dibujar los bloques.

Paso 7: Se hace una función para detectar colisiones y hacemos que los  ladrillos desaparezcan cuando la pelota les golpea.

Paso 8:
