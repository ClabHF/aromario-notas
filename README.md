# aromario-notas

Paquete de pictogramas realistas y sin fondo (WebP 256px con transparencia) de las notas de perfume de Aromario — Fase 1: 156 imágenes que cubren las notas más frecuentes del catálogo (85.3% de los huecos de pirámide).

- `notas.json` — manifiesto: `imagenes` (nota canónica → ruta) y `alias` (variante cruda del catálogo → nota canónica).
- `notas/nota_<id>.webp` — imágenes servidas por GitHub Pages.

La app descarga el paquete completo en el primer arranque con conexión y lo cachea en el dispositivo.
