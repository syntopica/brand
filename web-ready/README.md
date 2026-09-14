# Integración web

1. Copia **el contenido** de `public/` a la carpeta pública de tu proyecto. Revisa antes los archivos existentes para no sobrescribir tu manifest o tus iconos sin querer.
2. Añade las etiquetas de `head.html` al `<head>`, o su equivalente mediante el sistema de metadatos de tu framework. Evita declarar los mismos iconos dos veces.
3. Usa `/brand/syntopica-horizontal-color.svg` en superficies claras y `/brand/syntopica-horizontal-inverse.svg` en superficies oscuras. Los archivos son transparentes.

```html
<img src="/brand/syntopica-horizontal-color.svg" alt="Syntopica" width="220" />
```

Las rutas del ejemplo y del manifest asumen despliegue en `/`. Si tu app vive bajo un subdirectorio, adapta las rutas, `start_url` y `scope` antes de publicarla.

`favicon.svg` contiene una variante de pocas líneas y adapta la mitad principal a la preferencia clara/oscura del navegador. El ICO de respaldo usa fondo marfil. Los PNG del favicon están dibujados al tamaño indicado y el ICO contiene varias resoluciones.

Los iconos `maskable` llevan un margen más amplio, distinto del de los iconos normales. `apple-touch-icon.png` es cuadrado, opaco y mide 180 × 180 px.

Este directorio aporta la identidad visual y un manifest de ejemplo; no configura por sí mismo el comportamiento sin conexión, el service worker ni la instalación de tu aplicación.

Si el navegador conserva un favicon anterior, prueba a recargar sin caché o a cambiar temporalmente la URL del icono.
