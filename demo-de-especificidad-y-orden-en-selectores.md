# ☮ Demo de especificidad y orden en selectores

1. Los **!important** estarán por encima de los demás estilos. Sin embargo, son mala práctica y no se deberían usar.
2. Los estilos embebidos en el HTML, es decir **inline styles** están por encima de las **clases y IDs**. Sin embargo, también se deberían evitar.
3. Los **IDs** están por encima de las **clases**. Los **IDs** son específicos, si se usa uno en un archivo HTML ya no se podrá repetir más en ese mismo archivo. Mientras que las **clases** si se pueden repetir en cualquier elemento.
4. Un **estilo de etiqueta** es el último valor que el navegador tiene en cuenta antes de tomar los estilos por defecto de esa etiqueta. Los **estilos de etiqueta** son los que menos peso tienen.
