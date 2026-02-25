<div align="center">

# ⚔️🧟 Red Water Mystery 🕷️⚔️

**🏅 Proyecto Distinguido y Seleccionado: Concurso Wollok Game**

Proyecto académico desarrollado en el marco de la materia Programación Orientada a Objetos, seleccionado para concurso interno.

[![Ver en Wollok.org](https://img.shields.io/badge/Ver_en_Sitio_Oficial-Wollok-orange?style=for-the-badge&logo=google-chrome&logoColor=white)](https://www.wollok.org/news/concurso2025/)

*(Implementación avanzada de Programación Orientada a Objetos, Herencia y Polimorfismo)*

</div>

---

## 🧙‍♂️ Equipo de desarrollo
* **Analía Rossotti**
* Augusto Morán
* Cristian Signorini
* Daiana Díaz
* Diego Goso
* Darío Robles
* Florencia Saharrea

---

## 📸 Galería y Niveles

### 🏠 Pantalla de Inicio
![Pantalla Inicio](assets/capturas/inicio.png)
*Pantalla principal. El jugador es invitado a presionar **Enter** para comenzar la aventura.*

### 🧍 Selección de Personajes
![Selección de Personajes](assets/capturas/seleccionPersonajes.png)
*Menú de selección. Cuatro clases disponibles: **Bárbaro**, **Arquero**, **Hechicero** y **Guerrero**.*

### 🌲 Nivel 1 – Exploración Inicial
![Pantalla Nivel 1](assets/capturas/nivel1.png)
*El personaje explora el escenario inicial e interactúa con su entorno.*

### 🔥 Transición al Nivel 2
![Pantalla Transición a Nivel 2](assets/capturas/nivel2.png)
*Introducción de nuevos desafíos, enemigos y ambientación.*

### ⚔️ La Batalla Final
![Pantalla Final](assets/capturas/nivelFinal.png)
*Escena del clímax donde el jugador debe derrotar al Jefe.*

<details>
<summary><strong>Ver más capturas (Créditos, Game Over, Victoria)</strong></summary>

### 👥 Créditos
![Desarrolladores](assets/capturas/desarrolladores.png)

### 💀 Pantalla de Derrota
![Pantalla Derrota](assets/capturas/derrota.png)

### 🏆 Pantalla de Victoria
![Pantalla Fin Del Juego](assets/capturas/finDelJuego.png)

</details>

---

## ⚔️ Reglas de Juego

### 🎯 Objetivo
Conviértete en el héroe de estas tierras sobreviviendo a las hordas de criaturas. Tu objetivo final es **derrotar al temible Jefe** para restaurar la paz.

### 🗺️ Flujo del Juego
1. **Selección de Héroe:** Elige tu estilo (Guerrero, Arquero, Bárbaro o Mago).
2. **Nivel 1 - La Horda:** Sobrevive a un mapa infestado de **Arañas y Orcos**.
3. **Nivel 2 - El Jefe:** Tras limpiar el mapa, enfréntate al **Jefe** y sus ataques devastadores.

### 🎮 Controles y Mecánicas
* **Movimiento:** `W`, `A`, `S`, `D`.
* **Ataque:** Tecla `J` (Lanza hechizo/ataque en la última dirección).
* **Sistema de Vida:** Comienzas con 5 HP. Si llega a 0, es **Game Over**.
* **Condición de Victoria:** Derrotar al Jefe del Nivel 2.

---

## 💻 Arquitectura Técnica (POO)
Desarrollado en **Wollok 4.0.0**, aplicando los principios de objetos:

* **🔰 Jerarquía y Herencia:** Uso de una clase base `Unidad` para compartir lógica, extendida por `Personaje`, `Enemigo` y `Proyectil`.
* **🔄 Polimorfismo:** Todos los entes entienden mensajes como `atacar()` o `recibirDaño()`, pero un `Bárbaro`, una `Araña` o el `Jefe` responden ejecutando su propia lógica interna.
* **🔒 Encapsulamiento:** El estado interno (vida, daño) está protegido y solo se modifica mediante mensajes controlados.
* **🤝 Colaboración:** El objeto `Juego` orquesta las colisiones e interacciones entre las entidades del mapa.

---

## 🚀 Cómo Ejecutar el Proyecto

1. **Requisito:** Tener instalado [Wollok IDE](https://www.wollok.org/) o VS Code con la extensión de Wollok.
2. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/anyrossotti/Red-Water-Mystery-Wollok.git](https://github.com/anyrossotti/Red-Water-Mystery-Wollok.git)
