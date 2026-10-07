# Práctica de TypeScript: Trivia & Actividades

Aplicación web desarrollada con **Vite** y **TypeScript** que consume datos de la **Open Trivia DB** y la **Pixabay API** para generar tarjetas interactivas de preguntas con imágenes temáticas y control de dificultad.

 **Enlace en producción:** [practica1typescriptangel.netlify.app](https://practica1typescriptangel.netlify.app)

---



## Características Principales
* **Selector de Categoría y Dificultad:** Permite filtrar preguntas de ordenadores, videojuegos o deportes en niveles fácil, medio o difícil.
* **Control de Peticiones (Anti-Spam):** Incluye un sistema de bloqueo por temporizador (`setTimeout`) para evitar errores `429 Too Many Requests` en las APIs ante clics excesivos.
