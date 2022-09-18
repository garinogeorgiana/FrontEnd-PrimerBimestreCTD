# Grid

## sintaxis grid

- display:grid;

### columnas

- grid-template-colums: 50% 50%;  // crea dos columnas
-         "             1fr 1fr 1fr; // tres columnas de igual tamaño
-         "             repeat(3, 1fr) // tres columnas de una fraccion.
-         "             auto 1fr 1fr; // tres columnas, una con ancho igual a  su contenido y otras dos que se dividen el tamaño restante.

### filas

- grid-template-rows: 40px 30px 50px 60px; // creara 4 filas con esas alturas.


## determinar tamaño
<!-- columnas -->
- grid-column-start: 1;    <!-- representa las lineas de separacion -->
- grid-column-end: 4;
- grid-column: 1/4; <!-- lineas -->
- grid-column: span 3; <!-- columnas, no representa las lineas -->

- grid-column-start 1;
- grid-column-end: -1; <!-- abarca todas las columnas aunque se agreguen mas -->

<!-- filas -->
-grid-row: span 3;

## Breakpoints

