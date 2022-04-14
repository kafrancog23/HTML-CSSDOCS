# ☮ Display Flex

property **justify-content** alinea elementos horizontalmente, valores:

* flex-start: Alinea elementos al lado izquierdo del contenedor.
* flex-end: Alinea elementos al lado derecho del contenedor.
* center: Alinea elementos en el centro del contenedor.
* space-between: Muestra elementos con la misma distancia entre ellos.
* space-around: Muestra elementos con la misma separación alrededor de ellos.
* Space-evenly: Distribuye uniformemente el espacio entre los items y su alrededor.

property **align-items** alinea elementos verticalmente

* flex-start: Alinea elementos a la parte superior del contenedor.
* flex-end: Alinea elementos a la parte inferior del contenedor.
* center: Alinea elementos en el centro (verticalmente hablando) del contenedor.
* baseline: Muestra elementos en la línea base del contenedor
* stretch: Elementos se estiran para ajustarse al contenedor.

property **flex-direction** define la dirección de los elementos en el contenedor. / Permite elegir la alineación de los elementos hijos sea en vertical (column) u horizontal (row). Viene por defecto.\
valores:

* row: Elementos son colocados en la misma dirección del texto.
* row-reverse: Elementos son colocados en la dirección opuesta al texto.
* column: Elementos se colocan de arriba hacia abajo.
* column-reverse: Elementos se colocan de abajo hacia arriba.

property **order** para agregar un orden a elementos individuales

property \*\*flex-wrap \*\* especifica si los elementos “hijos” son obligados a permanecer en una misma línea o pueden fluir en varias líneas

* nowrap: Cada elemento se ajusta en una sola línea.
* wrap: los elementos se envuelven alrededor de líneas adicionales.
* wrap-reverse: Los elementos se envuelven alrededor de líneas adicionales en reversa.

property **flex-flow** es una combinación de flex-direction y flex-wrap. Acepta un valor de cada una separada por un espacio. Permite establecer filas y envolverlas.

property **align-content** determina el espacio entre las líneas, mientras que align-items determina como los elementos en su conjunto están alineados dentro del contenedor. Cuando solo hay una línea align-content no tiene efecto.

* flex-start: Las líneas se posicionan en la parte superior del contenedor.
* flex-end: Las líneas se posicionan en la parte inferior del contenedor.
* center: Las líneas se posicionan en el centro (verticalmente hablando) del contenedor.
* space-between: Las líneas se muestran con la misma distancia entre ellas.
* space-around: Las líneas se muestran con la misma separación alrededor de ellas.
* stretch: Las líneas se estiran para ajustarse al contenedor.

property **align-self** permite los mismos valores de align-items. Se usa para un elemento específico

Nota que cuando estableces la dirección a una fila invertida o columna, el inicio y el final también se invierten.
