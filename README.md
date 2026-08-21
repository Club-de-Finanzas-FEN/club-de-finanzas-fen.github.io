# Informes de Research — Club de Finanzas FEN UChile

Sitio del archivo de informes del Área de Research del Club de Finanzas de la
Facultad de Economía y Negocios de la Universidad de Chile.

**https://joaquin-vmo.github.io/club-finanzas/**

## Estructura

```
index.html          página completa (estilos y scripts en línea, sin dependencias)
assets/buho.png     isotipo del club, usado como máscara CSS
assets/favicon.png  isotipo en el azul del club
informes/           los PDF publicados, nombrados AAAA-MM-DD_tema.pdf
```

## Identidad

Tomada de los propios informes:

| | |
|---|---|
| Azul | `#2033D8` |
| Tipografía | Montserrat (400 / 500 / 600 / 700 + itálica) |
| Datos y metadatos | DM Mono |

El isotipo se aplica como `mask-image` con `background-color: currentColor`, de
modo que adopta el color del tema claro u oscuro sin necesidad de dos archivos.

## Agregar un informe

1. Dejar el PDF en `informes/` con el formato `AAAA-MM-DD_tema.pdf`.
2. Copiar un bloque `<details class="informe">` en `index.html`, encabezando la
   lista, y actualizar fecha, título, número de páginas y puntos clave.
3. Ajustar `data-temas` con los temas que correspondan (`macro-cl`, `macro-gl`,
   `commodities`, `mercados`, `equity`, `fiscal`, `corp`).
4. Actualizar los totales de la portada (número de informes, período, páginas).

## Aviso

Los informes responden a un propósito estrictamente académico y formativo,
enmarcado en el quehacer universitario, y en ningún caso deben interpretarse
como una recomendación o asesoría de inversión.
