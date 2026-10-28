# PRACTICAS — material de refuerzo autocontenido

Sitio estático publicado con GitHub Pages. Cada práctica es una carpeta independiente de
páginas HTML que se abren en el navegador sin instalar nada, sin registrarse y sin conexión.
No hay servidor, ni cuentas, ni registro de resultados: la corrección ocurre en el navegador
del alumno.

## Estructura

    index.html                 Portada del sitio: lista de prácticas y descargas.
    refuerzo_dia2/             Topografía agraria — refuerzo · Día 2 (12 páginas + LEEME.txt)
    descargas/refuerzo_dia2.zip  El mismo bloque empaquetado, para descargar desde la web.
    .nojekyll                  Evita que GitHub Pages procese el sitio con Jekyll.

## Añadir una práctica nueva

1. Copiar la carpeta completa (con su `index.html` dentro) a la raíz del repositorio.
2. Copiar su `.zip` a `descargas/`.
3. Añadir un bloque `<div class="pr">` en `index.html` con el enlace de apertura
   (`carpeta/index.html`) y el de descarga (`descargas/archivo.zip`, con atributo `download`).
4. Commit y push a `main`. GitHub Pages publica solo, en un minuto.

## Sobre el .zip

`descargas/refuerzo_dia2.zip` es el paquete original tal y como se entrega al alumnado
(md5 `05d5b1fb62000eab827d65e49961febf`). La única diferencia con la carpeta `refuerzo_dia2/`
del repositorio es el botón «Descargar el bloque (.zip)», que solo tiene sentido en la web:
dentro del zip no habría nada que descargar porque el material ya está en el equipo.

## Publicación

- Pages: rama `main`, carpeta `/ (root)`.
- URL: https://hamletlg.github.io/PRACTICAS/
- Práctica: https://hamletlg.github.io/PRACTICAS/refuerzo_dia2/
