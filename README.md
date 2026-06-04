# Fixture Mundial 2026 Interactivo - PWA

Esta versión funciona como aplicación web instalable. Incluye:

- `index.html`: aplicación principal.
- `manifest.webmanifest`: configuración de instalación.
- `service-worker.js`: caché offline básico.
- `icons/`: íconos para Android, Chrome, Edge y Apple.

## Cómo subirlo a GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube todos estos archivos manteniendo la misma estructura.
3. Entra a **Settings > Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/root`.
6. Guarda y abre el enlace público que te da GitHub Pages.

## Instalación en celular

- Android/Chrome: abre el enlace de GitHub Pages y toca **Instalar app** o el menú de Chrome > **Agregar a pantalla principal**.
- iPhone/Safari: abre el enlace, toca **Compartir** y luego **Agregar a pantalla de inicio**.

Importante: la instalación como app requiere HTTPS. GitHub Pages ya lo ofrece. Si abres el archivo directamente desde el celular como `file://`, no saldrá como app instalable.
