# Edificio Carrera (Negrete) · Informes ejecutivos ITO

Informe ejecutivo mensual de inspección técnica de obra del Edificio Carrera (código GIP_228), cliente Inmobiliaria Ruta Desarrollo Cuatro SpA, constructora Ingevec. Publicado por GIP Inspección Técnica de Obras.

Publicado en https://informes.gip.cl/carrera/ (portada de todas las obras: https://informes.gip.cl).

La página `index.html` muestra cada informe en una pestaña, con el más reciente marcado como vigente. Cada informe se puede abrir directo con `#n` y su número, por ejemplo `index.html#n18`.

## Informes cargados

| N° | Período | Cierre | PDF |
|----|---------|--------|-----|
| 19 | Septiembre 2026 | 30-09-2026 | `pdf/GIP_228_Informe_N19_2026-09.pdf` |
| 18 | Agosto 2026 | 31-08-2026 | `pdf/GIP_228_Informe_N18_2026-08.pdf` |

## Estructura

- `index.html`: la aplicación completa. Los datos de cada informe están en el arreglo `INFORMES`, al comienzo del script.
- `media/AAAA-MM/`: fotos del período (`foto-NN.jpg` y su miniatura `foto-NN-mini.jpg`), curva S (`curvaS.jpg`) y foto de portada (`hero.jpg`).
- `media/marca/`: logos de GIP.
- `pdf/`: informe del período en PDF A4, impreso desde la misma página con pie de página numerado (mismo formato que Torre 1).

## Agregar un mes nuevo

1. Copiar las fotos, la curva S y la portada en `media/AAAA-MM/`.
2. Copiar el PDF en `pdf/`.
3. Agregar un objeto nuevo al comienzo de `INFORMES` en `index.html`, junto con su constante `MEDIA_AAAA_MM`.
