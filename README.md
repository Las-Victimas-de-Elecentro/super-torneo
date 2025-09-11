## Mini proyecto: Torneo de todos los universos

¡Hemos logrado reunir a héroes de varios universos ficticios para hacerlos pelear en un **torneo a muerte**!

**Solo uno puede ser el vencedor**, pero para saber quién será el que se lleve toda la gloria, es necesario un algoritmo que, utilizando registros y arreglos de registros, permita orquestar todo el evento.

He aquí las especificaciones para ello:

Luchadores (16 en total):
  - Nombre.
  - Tres atributos: velocidad, ataque y defensa (con valores entre 0 a 100).
  - Comienza cada batalla con 100 de salud.

Batalla:
  - En cada batalla se enfrentan 2 luchadores.
  - El luchador con más velocidad comienza atacando.
  - El daño se calcula restando el daño de ataque del atacante menos la defensa del oponente.
  - El oponente siempre tiene un 20% de posibilidad de esquivar el ataque.
  - Si la defensa es mayor que el ataque, recibe un 10% del daño de ataque.
  - Después de cada turno y ataque, el oponente pierde salud.
  - La batalla finaliza cuando un luchador pierde toda su salud.

Torneo:
  - El torneo debe crear parejas al azar en cada ronda.
  - Los luchadores se enfrentan en rondas eliminatorias.
  - El ganador avanza a la siguiente ronda hasta que sólo quede uno.
  - Debes mostrar por pantalla todo lo que sucede en el torneo, así como el ganador.
