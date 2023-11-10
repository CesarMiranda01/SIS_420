 Bot utilizando Aprendizaje por Refuerzo en Python
===================
Integrantes de presentacion-Ingenieria en Ciencias de la Computacion
-**Miranda Gutierrez Cesar Alvaro**
===================

Un bot de Flappy Bird en Python que aprende de cada partida a través del Aprendizaje por Refuerzo con Q-Learning.

----------
### Cómo funciona

Con cada partida jugada, el percado observa los estados en los que ha estado y las acciones que tomó. Con respecto a sus resultados, castiga o recompensa los pares estado-acción. Después de jugar el juego numerosas veces, el pescado puede obtener consistentemente puntuaciones altas.

Se utiliza un algoritmo de aprendizaje por refuerzo llamado [Q-learning](https://en.wikipedia.org/wiki/Q-learning) Este proyecto está fuertemente influenciado por el [awesome work of sarvagyavaish](http://sarvagyavaish.github.io/FlappyBirdRL/), pero cambié el espacio de estados y el algoritmo hasta cierto punto. El bot está diseñado para funcionar en una versión modificada del [Flappy Bird pygame clone of sourabhv](https://github.com/sourabhv/FlapPyBird).


**Creditos**

https://github.com/sourabhv/FlapPyBird

http://sarvagyavaish.github.io/FlappyBirdRL/

https://github.com/mihaibivol/Q-learning-tic-tac-toe
