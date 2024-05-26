Simula un juego simple de dominó en el que se colocan las fichas de manera que los puntos en losextremos coincidan, utiliza una cola para gestionar las fichas del juego y para llevar el seguimientode las fichas en juego.

Representación de Fichas: Las fichas de dominó están representadas por pares de enteros (0 a 6)que indican los puntos en cada extremo de la ficha.

Estructura  de  Datos:    Utiliza  dos  colas,  una  para  gestionar  las  fichas  disponibles  y  otra  paramantener la secuencia de fichas que están siendo jugadas.

Orden de Fichas: 
* Comienza con una ficha inicial y agrégala a la cola de fichas en juego.
* Itera sobre las fichas restantes, para cada ficha, verifica si se puede agregar a la secuenciaactual sin necesidad de 
  girarla.
* Si  los  puntos  no  coinciden,  gira  la  ficha  (intercambia  los  puntos  de  los  extremos)  y  verificanuevamente.
* Si no se puede colocar una ficha, imprime un mensaje indicando que no se pueden organizarlas fichas.

Salida  del  Programa:  Al  finalizar,  imprime  la  secuencia  de  fichas  en  el  orden  en  que  fueronjugadas.
