# Presente

PWA personal para estar presente. Un solo archivo de app, sin dependencias ni compilación.

## Publicar en GitHub Pages (repositorio `vida-pwa`)

1. Sube **el contenido** de esta carpeta a la raíz del repositorio (`index.html`, `manifest.webmanifest`, `sw.js`, `icons/`).
2. Settings > Pages > Deploy from a branch > `main` y `/ (root)`.
3. Abre `https://TU-USUARIO.github.io/vida-pwa/`.

Todas las rutas son relativas (`./`, `icons/...`), así que funciona dentro de `/vida-pwa/`.
Si cambias el nombre del repositorio no hay que tocar nada.

## Actualizar

1. Reemplaza `index.html` en el repositorio (y `sw.js` si te lo indico). Sube todo junto si prefieres.
2. Abre la app en el iPhone. Verás una tarjeta "Presente se actualizó" y **tus datos no se borran**: viven en el dispositivo, aparte de los archivos.
3. Antes de cada cambio de versión la app guarda una copia automática (Ajustes > Versión > Volver a la copia previa).
4. Ajustes > Buscar actualización recarga la app si hay una versión nueva, sin cerrar nada.

No borres el icono de la pantalla de inicio ni cambies de dominio: los datos se guardan por dominio y por instalación. Si vas a hacerlo, haz un respaldo antes (Ajustes > Respaldo).

## Datos

Todo se guarda en el dispositivo. Usa Ajustes > Respaldo para llevarlos a otro lugar.
