# ☮ Medidas EM



* Depende de quien hereda ese tamaño, es decir, el valor de “em(elemento)” va a estar condicionado por el valor asignado en su elemento padre.

```css
.text-container{
		font-size: 1em;
}
```

* Por ejemplo si tenemos que un contenedor de texto tiene 20 pixeles como tamaño original, el texto que se encuentre dentro de ese contenedor va a estar referenciado por ese tamaño.
* Por consecuencia si nosotros le decimos al texto que esta dentro de ese contenedor que es tenga 1em, eso quiere decir que tendrá el valor de su padre, y como su padre tiene 20 pixeles, **1 em = 20px**

```css
.text-container{
	font-size: 20px;
}
p{
	font-size: 1em; /*  1 x 20 = 40px */		
}
```
