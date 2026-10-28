# PRACTICAS

Material de refuerzo en HTML estático publicado con GitHub Pages.

## Estructura

    index.html                     Portada e índice de bloques
    refuerzo_dia2/                 Bloque Día 2 — Topografía agraria (13 ficheros)
    descargas/refuerzo_dia2.zip    Paquete del bloque (163 KB)
    .nojekyll                      Desactiva Jekyll en Pages

Cada bloque es autónomo: HTML, CSS y JavaScript en línea, sin dependencias, sin
compilación y sin peticiones externas.

## Publicar

    git push origin main

Pages sirve la raíz de `main`. URL: https://hamletlg.github.io/PRACTICAS/

## Añadir un bloque

1. Copiar la carpeta del bloque a la raíz del repositorio.
2. Copiar su `.zip` a `descargas/`.
3. Añadir en `index.html` la entrada del bloque y su descarga con atributo `download`.
4. Commit y push.

## Notas

- `descargas/refuerzo_dia2.zip` es el paquete original de entrega
  (md5 `05d5b1fb62000eab827d65e49961febf`). No incluye el botón de descarga que sí
  lleva la copia publicada en `refuerzo_dia2/index.html`.
- Los enlaces entre páginas son relativos: sirve la carpeta por HTTP
  (`python3 -m http.server`) para probarlos antes de publicar.
