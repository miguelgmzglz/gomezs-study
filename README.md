# gomez's study — PWA

Esta carpeta es una aplicación web instalable (PWA). Incluye almacenamiento local, rutinas, asignaturas, temas, resúmenes básicos, notas, calificaciones, medias, objetivos y gráfico semanal.

## Instalar en Android
1. Publica esta carpeta en cualquier alojamiento HTTPS (por ejemplo GitHub Pages, Cloudflare Pages o Netlify).
2. Abre la dirección HTTPS desde Chrome en Android.
3. Usa el menú de Chrome → **Instalar aplicación** (o **Añadir a pantalla de inicio**, según versión).
4. Se abrirá como una app independiente con el icono de gomez's study.

El Service Worker permite funcionamiento offline después de la primera carga. Los datos se guardan en el almacenamiento local del dispositivo.

## Importante
La PWA no puede instalarse correctamente desde un archivo `file://` en muchos navegadores: necesita servirse por HTTPS para que el Service Worker y la instalación PWA funcionen.
