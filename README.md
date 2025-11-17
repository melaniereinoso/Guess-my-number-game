🕹️ Guess My Number Game

Un juego interactivo creado con HTML, CSS y JavaScript, donde el usuario intenta adivinar un número secreto generado automáticamente. El objetivo es adivinar el número correcto utilizando la menor cantidad de intentos posibles antes de que la puntuación llegue a cero.

🚀 Demo en vivo

👉 Juega aquí:
https://melaniereinoso.github.io/Guess-my-number-game/

🎮 ¿Cómo funciona?

El juego genera un número aleatorio entre 1 y 20.

El jugador ingresa un número y presiona Check!

El sistema mostrará mensajes dependiendo de la suposición:

📉 Too low!

📈 Too high!

🎉 Correct Number!

El puntaje (score) disminuye con cada intento incorrecto.

El jugador puede reiniciar el juego con el botón Again!

Si el jugador gana, el fondo cambia y se muestra el número secreto.

🧠 Tecnologías utilizadas

HTML5 – estructura del juego

CSS3 – diseño visual

JavaScript Vanilla – lógica del juego, eventos y manipulación del DOM

📂 Estructura del proyecto
📁 Guess-my-number-game
 ├── index.html
 ├── style.css
 └── script.js

✨ Funcionalidades principales

Generación automática de números secretos.

Validación de entrada del usuario.

Mensajes dinámicos según la suposición.

Sistema de puntaje decreciente.

Highscore que se guarda mientras la página está abierta.

Reinicio del juego sin refrescar la página.

Efectos visuales al adivinar el número.

▶️ Cómo ejecutar el proyecto localmente

Clona el repositorio:

git clone https://github.com/melaniereinoso/Guess-my-number-game.git

Entra al directorio del proyecto:

cd Guess-my-number-game

Abre el archivo index.html en tu navegador.

🛠️ Mejoras futuras

🔥 Agregar niveles de dificultad (1–50, 1–100).

🌙 Modo oscuro/claro.

🎵 Sonidos al ganar, perder o fallar.

💾 Guardar highscore en localStorage.

📱 Optimización para móviles.

🤝 Cómo contribuir

Si deseas contribuir:

Haz un fork del proyecto.

Crea una rama nueva:

git checkout -b feature/nueva-funcion


Realiza tus cambios y haz commit.

Envía un pull request.
