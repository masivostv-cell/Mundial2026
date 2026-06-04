# Fixture Mundial 2026 PWA

Aplicación web instalable para celular con fixture interactivo, resultados, avance automático de ganadores por fases, marcado de partidos con localStorage y calendario general `.ics`.

## Cómo subir a GitHub Pages

1. Descomprime este ZIP.
2. Sube todos los archivos al repositorio `Mundial2026`.
3. Verifica que `index.html`, `manifest.webmanifest`, `service-worker.js`, `.nojekyll` y la carpeta `icons/` queden en la raíz del repositorio.
4. En GitHub entra a **Settings > Pages**.
5. En **Build and deployment**, selecciona la rama principal y carpeta `/root`.
6. Abre la URL pública con HTTPS, por ejemplo: `https://masivostv-cell.github.io/Mundial2026/`.

## Instalación en Android

1. Abre la URL en Google Chrome.
2. Toca el botón **Instalar app en mi celular**.
3. Si no aparece la ventana automática, toca los tres puntos de Chrome y elige **Instalar app** o **Agregar a pantalla principal**.

## Nota importante

La instalación PWA solo funciona correctamente publicada por HTTPS. GitHub Pages cumple este requisito. Si abres el archivo localmente como `file://`, Chrome normalmente no lo instala como aplicación.
