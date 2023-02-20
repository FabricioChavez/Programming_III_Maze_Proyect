![portada_mazer](extra/background_md.jpg)

<a name="readme-top"></a>

<div align="center">
  <a href="https://github.com/CS1103/proyecto-final-2023_0-proyecto-final-2023_0-grupo-5">
    <img src="extra/square_maze.jpg" alt="hex board" width="150" height="150">
  </a>
  <h1>👾 MAZERS Ver. 1.0 👾</h1>
  
  <p>
  Este proyecto ha sido desarrollado por estudiantes del curso de Programación 3
de la Universidad de Ingeniería y Tecnología 💙🤍. Esperemos les guste. 🎮
    
  </p>
</div>

<details open>
  <summary>Índice:</summary>
  <ol>
    <li><a href="#acerca-del-proyecto">
      Acerca del proyecto
      <ul>
        <li><a href="#descripción">Descripción</a></li>
        <li><a href="#características">Características</a></li>
        <li><a href="#tecnologías">Tecnologías</a></li>
        <li><a href="#temas-de-interés">Temas de interés</a></li>
        <li><a href="#algoritmos-y-contenedores-utilizados">Algoritmos y contenedores utilizados</a></li>
      </ul>
    </a></li>
    <li><a href="#instalación">
      Instalación
      <ul>
        <li><a href="#requisitos">Requisitos</a></li>
        <li><a href="#pasos-de-instalación">Pasos de instalación</a></li>
      </ul>
    </a></li>
    <li><a href="#instrucciones-de-uso">
      Instrucciones de uso
    </a></li>
    <li><a href="#licencia">
      Licencia
    </a></li>
    <li><a href="#diagramas">
      Diagramas
      <ul>
        <li><a href="#grafo-del-tablero">Grafo del tablero-11x11</a></li>
        <li><a href="#diagrama-de-clases">Diagrama de clases</a></li>
      </ul>
    </a></li>
    <li><a href="#link-del-video">
      Link del video
    </a></li>
    <li><a href="#autores">
      Autores
    </a></li>
    <li><a href="#referencias-y-links">
      Referencias y links
    </a></li>
  </ol>
</details>

---

## Acerca del proyecto

### Descripción

Este proyecto consiste en el desarrollo del mítico juego del laberinto, con varios
añadidos extra e implementaciones que se adaptan a ofrecer la mejor
experiencia de juego posible. Este juego tiene como objetivo ofrecer posibilidades
infinitas a la hora de jugar, ya que ningun juego será igual que el anterior, además
de poder configurar algunos aspectos del juego antes de empezar para mejorar la
experiencia. No obstante, el juego también permite decidir la forma de jugar, ya sea
entre un jugador de manera local, u contra la misma computadora.

### Características

#### Características Principales

- **Orden de juego:**

  El juego comienza con la elección de un turno al azar, dependiendo de ello un jugador u otro tiene la posibilidad de realizar cualquier movimiento dentro del laberinto, mientras que el otro solo espera y el juego no ejecuta ninguna acción extra mientras esto ocurre.

- **Asignación del ganador:**

  El primer jugador que llegue a la meta se declara ganador, y el juego muestra en pantalla el nombre del jugador ganador.

- **Partidas sin limites:**

  Cada juego es único y diferente, por lo que no habrán 2 laberintos iguales que puedas jugar. Siempre son distintos.

#### Caracteristicas Adicionales

- Implementación de la jugabilidad multijugador desde un mismo dispositivo (local).
- Selector de diferentes dificultades al jugar contra un bot (computadora).
- Gráficos, musica, y diferente contenido multimedia para mejorar la experiencia de juego.
- Posicionamiento adaptable de los elementos del juego de acuerdo al tamaño de la pantalla.