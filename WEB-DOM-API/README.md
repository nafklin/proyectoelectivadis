# Explorador de Publicaciones - JSONPlaceholder

Proyecto HTML, CSS y JavaScript que consume la API de JSONPlaceholder.

## Funcionalidad añadida
- Al pulsar una tarjeta, se abre una ventana modal con la información del autor.
- Los datos mostrados son `id`, `name`, `username`, `email`, `phone` y `website`.
- Los usuarios se consultan desde `https://jsonplaceholder.typicode.com/users` y se relacionan con las publicaciones por `userId`.
- La ventana se cierra con la X, haciendo clic fuera de ella o pulsando Escape.

## Cómo ejecutar
1. Descomprime la carpeta.
2. Abre `PAGES/Index.html` con Live Server (recomendado) o desde un navegador con conexión a internet.
3. Haz clic en cualquier tarjeta para ver los datos del usuario.

## Archivos
- `PAGES/Index.html`: estructura de la aplicación.
- `STYLES/style.css`: estilos.
- `SCRIPTS/app.js`: consumo de API y comportamiento.

API usada: https://jsonplaceholder.typicode.com/users
