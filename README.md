
>Documentación del Proyecto - Clon de Stardew Valley en Unity

>Autor: Andres Torres Ceja

>Fecha: 2025-03-18

>Versión: alpha 0.1

# Descripción del Proyecto

## 1. Resumen del Proyecto
Este proyecto consiste en el desarrollo de un videojuego 2D inspirado en Stardew Valley, utilizando el motor Unity y el lenguaje de programación C#. El juego se centrará en la simulación de una granja, permitiendo al jugador gestionar cultivos, criar animales, explorar, interactuar con NPCs y realizar diversas actividades en un mundo abierto con ciclos de día y noche.

## 2. Algoritmos 2D Utilizados
Para el desarrollo del videojuego, se emplearán los siguientes algoritmos gráficos y de optimización:
- **Z-buffering**: Para gestionar la superposición de objetos y asegurar un correcto orden de dibujado.
- **Algoritmo de Bresenham**: Para la renderización eficiente de líneas y contornos.
- **Dijkstra**: Para la implementación del pathfinding de NPCs y enemigos.
- **Viewports**: Para el manejo de cámaras y desplazamiento dentro del mundo del juego.
- **Dithering**: Para mejorar la calidad visual con limitaciones de paleta de colores.
- **Antialiasing**: Para mejorar la suavidad de los gráficos y evitar pixelaciones.
- **Mipmapping**: Para optimizar la carga y escalado de texturas según la resolución y distancia.

## 3. Mecánicas del Juego
El juego incluirá diversas mecánicas esenciales:
- **Ciclo de día y noche** con eventos dependientes de la hora.
- **Sistema de siembra y cosecha** con tiempos de crecimiento variables.
- **Cría de animales** con necesidades específicas de alimentación y cuidado.
- **Sistema de economía y comercio** con NPCs y una tienda virtual.
- **Exploración de cuevas y mazmorras** con mecánicas de combate básicas.
- **Sistema de interacción social** con NPCs, eventos y relaciones progresivas.
- **Construcción y mejora de la granja** mediante recolección de recursos.
- **Interfaz de usuario intuitiva** para inventario, misiones y progresión del personaje.

## 4. Procedimientos Principales
Algunas de las funciones clave del juego incluyen:
- **Gestor de tiempo**: Controla el avance del reloj y los eventos dependientes de la hora.
- **Gestor de entrada del jugador**: Procesa movimientos, acciones y menús.
- **Sistema de tilemaps**: Manejo de terreno, colisiones y estructura del mundo.
- **Motor de eventos**: Gestiona las interacciones con NPCs y misiones.
- **Sistema de inteligencia artificial**: Manejo de NPCs y enemigos mediante pathfinding.
- **Sistema de renderizado**: Dibujado eficiente de sprites y elementos en pantalla.

## 5. Arquitectura del Programa
El juego seguirá un diseño modular basado en los siguientes componentes:
- **Motor del juego**: Controlador principal que gestiona el estado global.
- **Manejo de escenas**: Permite la transición entre distintos mapas y ubicaciones.
- **Sistema de entidades**: Implementado con clases y herencia para objetos del juego.
- **Sistema de eventos y diálogos**: Gestiona la interacción del jugador con NPCs y el entorno.
- **Gestor de datos**: Manejo de guardado y carga de partidas.

## 6. Especificaciones Técnicas
- **Motor de desarrollo**: Unity 2022 o superior.
- **Lenguaje de programación**: C#.
- **Plataformas objetivo**: PC y potencialmente dispositivos móviles.
- **Resolución gráfica**: Pixel art con escala ajustable.
- **Sistema de animación**: Basado en spritesheets y Unity Animator.

## 7. Desarrollo de la Interfaz de Usuario (UI)
El diseño de la UI incluirá:
- **Menú principal** con opciones de juego, configuración y carga de partidas.
- **HUD minimalista** para mostrar información clave como reloj, inventario y energía.
- **Menú de interacción** para objetos, NPCs y opciones de juego.

## 8. Implementación del Movimiento
El personaje del jugador se moverá en un entorno 2D con:
- **Sistema de control basado en tiles** para alineación y colisiones precisas.
- **Interpolación de movimientos** para fluidez en desplazamientos.
- **Uso de RigidBody2D y Collider2D** en Unity para física básica.

## 9. Implementación de Tilemaps
- **Estructura basada en cuadrícula** con tiles de 16x16 px.
- **Manejo de colisiones** según los tipos de terreno y objetos.
- **Capas de tilemaps** para profundidad y decoración.

## 10. Uso de Mecanismos y Técnicas Avanzadas en C#
Para una estructura sólida y mantenible se emplearán:
- **Programación orientada a objetos** (POO) con clases bien definidas.
- **Eventos y delegados** para mejorar la comunicación entre componentes.
- **Patrones de diseño** como Singleton y MVC para modularidad.
- **Uso de Coroutines y Threads** para optimizar procesos en segundo plano.
