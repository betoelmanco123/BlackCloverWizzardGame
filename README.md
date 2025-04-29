# 🧙‍♂️ Wizard Turn-Based Game

Este es un juego de magos por turnos hecho en Python. Los jugadores controlan diferentes tipos de magos con habilidades únicas, luchando entre dos equipos: rojo y azul. El objetivo es derrotar al equipo contrario usando ataques, hechizos especiales y efectos mágicos.

## 🎮 ¿Cómo funciona?

- Cada mago pertenece a un equipo (rojo o azul).
- Cada uno tiene una cantidad de vida, maná y una lista de movimientos.
- Los movimientos pueden ser ataques, curaciones, mejoras de estado o habilidades especiales.
- Cada turno, los magos regeneran maná y actualizan sus efectos activos (como escudos o quemaduras).
- El jugador humano controla uno de los magos del equipo azul, el resto se controla automáticamente (IA básica aleatoria).

## 🧙 Clases de Magos

Actualmente, el juego incluye:
- **FireWizzard**: usa fuego para atacar e infligir quemaduras.
- **WaterWizzard**: controla el agua para atacar y ralentizar enemigos.
- **WindWizzard**: tiene movimientos rápidos y evasivos.
- **SpatialWizzard**: manipula el espacio para curar o causar confusión.
- **AntimagicWizzard**: bloquea o revierte efectos mágicos.
- **HealerWizzard**: especializado en curación y soporte.

Cada clase tiene habilidades personalizadas que consumen maná y tienen diferentes efectos en el campo de batalla.

## 🧠 IA Básica

Los enemigos y aliados que no controla el jugador eligen movimientos de manera aleatoria, atacando o ayudando dependiendo del tipo de movimiento.

## ▶️ Cómo jugar

1. Asegúrate de tener Python 3 instalado.
2. Corre el archivo principal del juego (`main.py`).
3. Elige tus movimientos cuando sea tu turno escribiendo su nombre.
4. El juego terminará cuando un equipo quede sin magos en pie.

¡Disfruta la batalla mágica por turnos!
