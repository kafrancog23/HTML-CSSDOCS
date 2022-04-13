# ☮ Herencia



La herencia es el mecanismo mediante el cual, determinadas propiedades de un elemento padre son transferidas a un elemento hijo, no todas la propiedades son trasferidas de padre a hijo, ya que hay muchas que no tienen sentido que lo fueran ( por ejemplo los bordes)

Es importante tener bien en claro a lo que nos referimos cuando hablamos de etiquetas padres e hijo, cuando una etiqueta contiene a otra, se dice que esta es su etiqueta padre.

Tenemos que entender que hay muchos valores que se heredaran, por ejemplo, si cambio el color de fuente de en una etiqueta, todos sus hijos heredaran esta propiedad, pero si le asigno un borde negro a una etiqueta padre seria ilógico que todos sus hijos heredaran esta propiedad.

• Controlar la herencia: CSS nos brinda 4 valores que nos permite tener control de la herencia de una propiedad, todas las propiedades de CSS aceptan estos valores.

• Inherit: Establece que el valor de la propiedad sea heredado de la etiqueta padre.

• Initial: Establece que el valor de esa propiedad será establecida por la hoja de estilos del navegador.

• Unset: El valor Unset es como usar Inherit e Initial al mismo tiempo, tiene dos casos.

1. En caso de que el valor se herede de forma natural, el valor de esta propiedad será heredado.
2. En caso de que el valor no se herede de forma natural funcionara como Initial.
