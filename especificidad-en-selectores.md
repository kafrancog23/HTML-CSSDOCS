# ☮ Especificidad en selectores

La cascada se usa cuando hay dos o mas declaraciones que afectan a un elemento, es decir, cuando hay mas de dos reclas que afectan a una etiqueta html, cuando esto ocurre la cascada determinara cual de estas es tiene mayor importancia, y la de mayor importancia sera la que se aplicara. L forma de calcular el peso de una regla no se hace de forma arbitraria, se calculan en base a 3 criterios:

![Captura de pantalla de 2019-02-07 11-08-50.png](https://static.platzi.com/media/user\_upload/Captura%20de%20pantalla%20de%202019-02-07%2011-08-50-0f52fe75-3b9d-4a45-ae6d-a11dabb74610.jpg)

**1.- Importancia** -----> Las declaraciones importantes son las declaraciones que van seguidas de una directiva llamada: !important. Cualquier otra declaracion sin !important son consideradas declaraciones normales.

**2.- Especificidad** -----> La regla dice que el selector mas especifico sera el que se tome en cuenta. La forma para calcular la especificidad de un selector se hace con la siguiente formula.

![Captura de pantalla de 2019-02-07 11-18-46.png](https://static.platzi.com/media/user\_upload/Captura%20de%20pantalla%20de%202019-02-07%2011-18-46-e81fe483-c4b8-448e-b4f7-8292dbaed2ae.jpg)

se juntan todos los bloques obtenidos, a mayor numero mayor especificidad, y sera tomado en cuente la regla con mayor especificidad.

**3.-Orden** ------> Podemos definir los estilos en hojas externas, en la cabecera de la pagina y en la misma etiqueta (estilos en linea), el navegador lee el contenido de una pagina de arriba hacia bajo y los ultimos estilos definidos seran los que se tomaran en cuenta.
