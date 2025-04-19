# 🎮 Proyecto DAM: Aventura Conversacional con Colecciones - **Versión 2**

Este proyecto ha sido desarrollado como parte del curso **Desarrollo de Aplicaciones Multiplataforma (DAM)**, específicamente en el módulo de **Programación**. En esta **Versión 2**, el objetivo es crear una **aventura conversacional** interactiva utilizando colecciones en Java, como **ArrayList**, **HashMap**, **HashSet** y **Queue**.

En este proyecto, he implementado una serie de escenarios de aventura en los que el jugador interactúa con el entorno y toma decisiones. Se utiliza colecciones para almacenar datos como elecciones previas, resultados de acciones y estadísticas del juego. Entre los escenarios se encuentran una exploración en una **jungla peligrosa**, un **minijuego de cajas** y **minijuego de frutas**, además de un **clásico tres en raya**.

---

## 📦 Contenido del Proyecto

### 1. 🌴 `Jungla.java`
Una aventura en una jungla peligrosa donde el jugador explora áreas y enfrenta desafíos.

- **ArrayList<Item>**: Almacena objetos encontrados durante la exploración.
- **HashSet<String>**: Guarda las áreas que el jugador ya ha visitado.

---

### 2. 📦 `MinijuegoCajas.java`
El jugador elige entre tres cajas con la posibilidad de ganar o perder salud.

- **ArrayList<Integer>**: Guarda las elecciones previas del jugador.
- **HashMap<Integer, Boolean>**: Registra si la caja fue correcta o no.
- **Queue<String>**: Historial de resultados en orden cronológico.

---

### 3. 🍌 `MinijuegoFrutas.java`
El jugador debe adivinar cuántas frutas hay en total, ganando puntos de salud según la precisión de su respuesta.

- **ArrayList<Integer>**: Guarda los intentos realizados.
- **HashMap<Integer, Boolean>**: Indica si cada intento fue correcto.
- **Queue<String>**: Historial con los resultados del juego.

---

### 4. ❌⭕ `TresEnRaya.java`
Clásico juego de tres en raya donde dos jugadores compiten por la victoria.

- **ArrayList<String>**: Historial de movimientos del juego.
- **HashMap<Character, Integer>**: Contador de partidas ganadas por cada jugador (`X` y `O`).
- **Queue<String>**: Eventos importantes del juego (movimientos, ganador, etc.).

---

## 🧠 Objetivo Educativo

El principal objetivo de este proyecto es la **implementación de colecciones en Java** dentro de un entorno de **aventura conversacional**. Esto permite practicar conceptos clave como:

- **ArrayList** para almacenar secuencias de datos (elecciones, movimientos).
- **HashMap** para registrar pares clave-valor (resultados, victorias).
- **HashSet** para gestionar elementos únicos (áreas visitadas).
- **Queue** para mantener el orden cronológico de eventos y resultados.

---

## 🛠️ Requisitos

- Java 8 o superior
- IDE recomendado: IntelliJ IDEA, Eclipse o VS Code con extensión Java

---

## 🚀 Cómo ejecutar

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tuusuario/aventura-conversacional-colecciones.git
