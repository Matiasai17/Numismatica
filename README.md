# Gabinete · Colección numismática

Boceto de app móvil para inventariar una colección de monedas y medallas (Argentina, Bolivia, Uruguay y el mundo).

- `index.html`: la app completa (HTML, CSS y JS en un solo archivo). Abrila en el navegador o publicala con GitHub Pages.
- `img/`: fotos recortadas de cada pieza (720 px, WebP con fondo transparente).
- `t/`: miniaturas para la grilla (360 px).

Cada foto se nombra con un id; en `index.html`, el array `P` vincula cada pieza con su anverso (`obv`) y reverso (`rev`) y guarda la ficha: catálogo (KM, Janson, Numista), metal, peso, diámetro, tirada, conservación, valor estimado y su desglose.

Los valores son estimaciones orientativas a partir de fotos, con la plata a US$ 56,99/oz (17-oct-2026). No reemplazan una tasación.
