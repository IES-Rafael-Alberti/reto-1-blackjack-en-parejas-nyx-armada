[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YjNdb-8o)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12725438&assignment_repo_type=AssignmentRepo)

'''Este programa implementa el juego de blackjack en dos modos: solitario y multijugador.
El juego se juega entre un jugador y un distribuidor (o varios jugadores y un distribuidor en el modo multijugador). 
El objetivo del juego es acercarse a un total de 21 puntos sin pasarse. El jugador que se acerque más a 21 puntos sin pasarse gana.'''

'''Modo de juego:'''
#- Modo solitario: El jugador juega solo contra el distribuidor.
#- Modo multijugador: El juego admite varios jugadores, cada uno compitiendo contra el distribuidor.

'''El programa incluye las siguientes funciones:'''

    #1. iniciar_modo(modo): esta funcion permite al usuario elegir el modo de juego y devuelve un mensaje de inicio correspondiente al modo seleccionado.

    #2. crear_cubierta(numeros, letras): genera una cubierta de cartas mezclada utilizando numeros y letras.

    #3. repartir_cartasjugador(jugador, cubierta): reparte una carta al jugador y actualiza la cubierta de cartas.

    #4. repartir_cartasdistribuidor(distribuidor, cubierta): reparte una carta al distribuidor y actualiza la cubierta de cartas.

    #5. revelar_mano

    #6. revelar_manodistribuidor(manodistribuidor): revela la mano del distribuidor.

    #7. revelar_manojugador(manojugador): revela la mano del jugador.

    #8. crear_total(turno): Calcula el valor total de una mano de cartas.

    #9. crear_resultadosolitario(manojugador, manodistribuidor): determina el resultado del juego en el modo solitario y devuelve un mensaje apropiado.

    #10. crear_resultadomultijugador(manojugador, manodistribuidor: determina el resultado del juego en el modo multijugador y devuelve un mensaje apropiado.

'''El programa le permite al usuario seleccionar el modo de juego, reparte las cartas y simula el juego. Luego, muestra el resultado del juego'''

'''Este codigo es una implementacion basica de blackjack y puede servir como punto de partida para desarrollar una version mas completa del juego que incluya botones, imagenes, assets, etc...'''

