# ProyectoFinalG13

## Estructura de la Base de Datos:
![image](https://user-images.githubusercontent.com/100931984/194046956-7dd78517-43f7-4007-b8a8-5d61871e0d74.png)

## Reglas:
El objetivo del juego es deshacerse de todas las cartas que tengamos hasta quedarnos con ninguna. Y al tener una carta en la mano debemos tocar el botón "Uno", puesto que si no lo hacemos y nuestros rivales lo advierten, nos penalizaran haciéndonos robar otras 4 cartas del mazo.
Al empezar el juego, se le da a cada jugador 7 cartas y se pondrá una carta dada vuelta como descarte, que será el color o número que deberá seguirse. Y se empiezan a descartar las cartas entre los jugadores, en sentido de las agujas del reloj. Cuando llega el turno de cada jugador, este está obligado a tirar una carta del color que se está jugando o una carta con el mismo número que han tirado antes de ese turno. Si no se tiene una carta del color o del número que nos han tirado y tampoco se tiene una carta especial, el jugador debe llevarse una carta del mazo y si la puede tirar lo hace o sino, debe pasar su turno actual.

En el juego existen cartas especiales o comodines que tienen bonuses distintos:
- Carta Reversa: tiene el efecto de cambiar el orden en que se está jugando, o sea, al ponerse sobre la mesa ella invierte el sentido de sucesión de los turnos.
- Carta Saltar: provoca que el jugador siguiente pierda su turno.
- Carta Cambio de Color: obliga la siguiente carta a ser del color que el jugador quiera. Esta carta se puede tirar en cualquier momento sin importar el color o el valor de la carta anterior.
- Carta +2: obliga al jugador siguiente a robar 2 cartas del mazo.
- Carta +4: obliga al jugador siguiente a robar 4 cartas del mazo y puede elegir el color de la siguiente carta. Esta carta se puede tirar en cualquier momento sin importar el color o el valor de la carta anterior.

Cartas espciales en nuestra versión:
- Carta Ronda: salta toda una ronda, haciendo que el juegador que la tiro la vuelva a tirar.
- Carta Cambio de Color Random: cambia el color de la siguiente carta a uno random.
- Carta -3: cuando te toca esta carta, te suma +3 cartas a TU mazo.
- Carta Destinatario: elegí a que persona le sigue el turno (no podes elegirte a vos mismo). La ronda continuará desde esa persona.

Aclaraciones:
- No se pueden lanzar más de 2 cartas en un mismo turno (a no ser que sea un Carta Ronda o una Carta Saltar si juegan 2 personas).
- Un jugador puede responder a una Carta +2 ó +4 con las mismas para sumar el valor de las cartas a agregar.
- No se puede terminar una partida con una Carta Cambio de Color, Carta +4 o Carta Cambio de Color Random.
