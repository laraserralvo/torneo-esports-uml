# Sistema de Gestión de Torneos de eSports

## Autor
Lara Serralvo De Jesús

https://github.com/laraserralvo

## Descripción del Proyecto

https://github.com/laraserralvo/torneo-esports-uml

Este proyecto implementa un sistema de gestión de torneos de eSports utilizando 
UML para el modelado y Java para la implementación.

## Análisis del problema y requisitos del sistema

1. ¿Quiénes son los actores que interactúan con el sistema?

    En este caso, los actores que van a interactuar con el sistema son el admistrador
    y los jugadores.

2. ¿Cuáles son las acciones que cada actor puede realizar?

    El administrador va a tener la oportunidad de registrar los equipos, añadir jugadores
    a los equipos y consultar la lista de equipos y jugadores.

    Mientras que los jugadores solamente podrán consultar la lista de equipos y jugadores.


3. ¿Cómo se relacionan entre sí las entidades del sistema?

    Respecto a equipos, un equipo puede estar compuesto tanto por un jugador como por varios
    jugadores, por lo que es una relación de uno a muchos.

    Sin embargo, un jugador tan solo puede pertenecer a un equipo.

## Diagramas UML
### Diagrama de Casos de Uso

![Diagrama de casos de uso](diagrams-casos-uso.png)

### Diagrama de Clases

![Diagrama de clases](diagrams-clases.png)

## Justificación del diseño