# Syntopica — kit de marca

Diseño seleccionado: símbolo de líneas convergentes, dos mitades separadas, nombre serif en minúsculas, negro y terracota.

## Empieza aquí

- Abre `preview.html` para ver y abrir los recursos. Funciona localmente y muestra los archivos reales del kit.
- Para integrar en una app web, empieza por `web-ready/README.md`.
- Para editar en un programa de diseño o escalar sin perder resolución, usa los archivos de `logos/svg/`.

## Qué hay en cada carpeta

| Carpeta | Contenido |
| --- | --- |
| `logos/svg/` | Logo horizontal, apilado, solo nombre y solo símbolo. Cinco variantes: color, inverse, black, white y terracotta. |
| `logos/png/transparent/` | Las mismas versiones en PNG con transparencia real. Logos de 1200 y 2400 px de ancho; símbolos de 512 y 1024 px de ancho. |
| `logos/backgrounds/` | Logos horizontales y apilados sobre siete fondos, en SVG y PNG de 1600 px de ancho. |
| `icons/square/` | Iconos cuadrados opacos, con siete fondos. Tamaños: 32, 48, 64, 96, 128, 180, 192, 256, 512 y 1024 px. |
| `icons/rounded/` | Iconos de esquinas redondeadas, con transparencia en las esquinas. SVG y PNG de 128, 256, 512 y 1024 px. |
| `icons/transparent/` | Símbolo centrado en lienzo cuadrado transparente. SVG y PNG de 128, 256, 512 y 1024 px. |
| `favicons/` | SVG, PNG a tamaño real e ICO multirresolución. Variantes clara, oscura, marfil y terracota. |
| `desktop/macos/` | ICNS en marfil, carbón y terracota, y un iconset PNG en marfil. |
| `desktop/windows/` | ICO multirresolución en marfil, carbón y terracota. |
| `web-ready/` | Carpeta pública con favicon, Apple Touch Icon, iconos normales y maskable, logos y un manifest de ejemplo. Incluye instrucciones. |

`palette.css` y `palette.json` contienen los colores. `assets.json` enumera los recursos gráficos con sus dimensiones y su huella SHA-256.

## Qué versión elegir

**Sobre fondo claro:** archivos `-color`. El símbolo es negro + terracota y el nombre es negro.

**Sobre fondo oscuro:** archivos `-inverse`. La mitad izquierda y el nombre son blancos, y la mitad derecha sigue siendo terracota. Son transparentes, no llevan un rectángulo oscuro incorporado.

**A una sola tinta:** archivos `-black`, `-white` o `-terracotta`.

**Con fondo incorporado:** archivos `-on-white`, `-on-ivory`, etc. de `logos/backgrounds/`.

**Icono para una plataforma que aplica su propia máscara:** empieza por `icons/square/`. Los redondeados son una variante visual con esquinas ya recortadas.

**Favicon:** el SVG de la raíz adapta el color principal al tema claro/oscuro del navegador. El ICO de la raíz usa fondo marfil para mantener un fondo definido. En las subcarpetas hay alternativas transparentes y de otros colores.

## Tamaños pequeños

El símbolo completo tiene líneas muy finas en su zona central. Para evitar que se emborronen al reducirlo, los favicons de 16 y 24 px utilizan una versión micro de tres trazos por lado; los de 32 y 48 px usan una versión compacta de cinco. Los PNG de app de 32 y 48 px también usan la compacta. A partir de 64 px se mantiene el símbolo completo. Estas variantes ópticas no sustituyen al logo maestro.

El SVG de favicon usa la variante micro por estar destinado a pestañas pequeñas. Los SVG de iconos y logos mantienen la versión completa, excepto los archivos que indican explícitamente `micro` o `compact`.

## Naturaleza de los archivos

Los originales disponibles eran imágenes de presentación. El símbolo y el nombre se han **vectorizado a partir de la imagen que elegiste**, conservando su silueta y sus letras. Los SVG contienen trazados Bézier reales: no son un PNG metido dentro de un SVG. No necesitan instalar ninguna fuente. La palabra está convertida a contornos, por lo que no se edita como texto.

La paleta se ha normalizado a colores planos, tomando el terracota de la imagen elegida: `#AB6647`. El resto de fondos son variantes de uso. Se han eliminado la textura de la imagen de presentación, las sombras de las maquetas y sus rótulos. La vectorización es una reconstrucción del diseño aprobado, no un archivo maestro vectorial original de aquella imagen.

El PNG usa transparencia alfa donde corresponde. Los fondos cuadrados opacos y los logos con fondo no son transparentes. Las imágenes están en RGB para pantalla; no se incluyen separaciones CMYK ni archivos de imprenta.

No estires el logo de forma no proporcional. Usa el alto automático cuando fijes el ancho en la app y conserva aire alrededor del símbolo y del nombre.

## Paleta

- Negro del logo: `#252525`.
- Terracota: `#AB6647`.
- Blanco: `#FFFFFF`.
- Marfil: `#FAF8F4`.
- Gris piedra: `#E8E5E0`.
- Arena: `#DDD4C8`.
- Carbón: `#292929`.
- Negro de fondo: `#0C0C0C`.

Todos los logos, iconos y favicons se entregan como archivos separados. `preview.png` es solo una vista de conjunto y no hace falta recortarla.
