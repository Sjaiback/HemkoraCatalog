# Hemkora · Catálogo editorial

Sitio estático independiente del sistema de ventas. `dist/` es el sitio completo, sin backend, dependencias de compilación ni claves.

## Vista local

Desde esta carpeta: `python -m http.server 5180 --bind 127.0.0.1 --directory dist`.

## Contenido y experiencia

- Seis colecciones y 24 productos ilustrativos, definidos en `dist/catalog.js`.
- Libro de dos páginas en escritorio; página completa en celular. Transición 3D con anverso y reverso, flechas, teclado y gestos táctiles. Respeta movimiento reducido.
- Fichas de producto, favoritos en almacenamiento local, selección copiable y ayuda de uso. No realiza ventas ni envía mensajes.
- Favicon y logo originales de Hemkora. Imágenes de productos de muestra de Unsplash: fuentes en `asset-sources.json`.
- Portada generada con la herramienta integrada de generación de imágenes. Activo final: `dist/assets/hemkora-editorial.png`.
- No conecta inventario real ni reutiliza credenciales del CRM. Productos y precios identificados como ejemplos.

## Dirección de imagen de portada

Fotografía editorial de naturaleza muerta con cartera estructurada rosa empolvado, frasco de perfume de vidrio con tapa dorada, labial negro y dorado, rosas y peonías rosadas. Pedestal de travertino, satén crema y rosa, luz cálida natural y sombras orgánicas. Sin texto, marcas ni logotipos. Composición horizontal 3:2 de boutique elegante y femenina.

La publicación y su identidad se configuran en `.openai/hosting.json`.
