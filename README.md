# La Palabra de Hoy — juego web

Juego de palabras chilenas de cinco letras. Sitio estático: no requiere servidor propio ni dependencias.

## Publicar gratis con GitHub Pages

1. Crea o inicia sesión en GitHub y crea un repositorio público, por ejemplo `la-palabra-de-hoy`.
2. Sube `index.html` a la raíz del repositorio. Puedes añadir este `README.md` si quieres.
3. En el repositorio abre **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**; selecciona la rama `main` y la carpeta `/ (root)`, y pulsa **Save**.
5. Espera la publicación. GitHub mostrará una dirección similar a `https://TU-USUARIO.github.io/la-palabra-de-hoy/` en la sección Pages.
6. Abre esa dirección en móvil y computadora y prueba el juego y el teclado.

La publicación en GitHub requiere que el usuario cree la cuenta/repositorio y confirme la configuración. Este workspace no tiene configuradas tus credenciales, por lo que no puedo subir el juego a una cuenta ni escoger una URL pública en tu nombre.

## Antes de compartir ampliamente

- Prueba la jugabilidad en Chrome y en un teléfono real; esta versión ha recibido cambios iterativos y necesita una ronda de QA completa.
- Revisa la lista de palabras, especialmente las respuestas diarias; un diccionario corto puede frustrar a los jugadores.
- El juego guarda progreso en el dispositivo cuando el navegador permite almacenamiento. En algunas vistas previas aisladas puede no conservarlo.
- La fecha diaria se calcula con `America/Santiago`, pero la selección diaria se repite a partir de una lista corta.
- Añade un aviso de privacidad si incorporas analítica, publicidad o recopilación de datos.

## Probar localmente

Abre `index.html` en un navegador moderno. No hay que instalar nada.