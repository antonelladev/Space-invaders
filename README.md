# Retro Space Invaders 🚀👽

Una versión inspirada en el legendario arcade de los 80 **Space Invaders**, construida desde cero en Python usando la biblioteca **Pygame**. 

Este proyecto implementa la lógica de manejo de múltiples entidades, eventos del teclado en tiempo real, detección de colisiones mediante rectángulos dinámicos (`pygame.Rect`) y estados de juego estructurados bajo el paradigma de Programación Orientada a Objetos.

## ✨ Características
* **Detección de Colisiones Avanzada:** Control exacto de impactos entre proyectiles y enemigos usando la función `colliderect`.
* **Comportamiento de Horda:** Los enemigos se desplazan en bloque de manera lateral y descienden automáticamente al impactar las paredes laterales del lienzo.
* **Sistema de Vidas y Puntuación:** El jugador inicia con 3 vidas. Cada alíen destruido otorga 10 puntos.
* **Tasa de Refresco Optimizada:** Configurado de forma nativa para ejecutarse a unos 60 FPS estables sin sobrecargar la CPU.

## 🛠️ Tecnologías y Requisitos
* **Lenguaje:** Python 3.x
* **Librerías:** `pygame` (Manejo de gráficos y eventos)

### Configuración rápida del entorno:
```bash
pip install pygame
