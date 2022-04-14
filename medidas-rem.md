# ☮ Medidas REM

Unidad de medida absoluta significa REM = root element, la medida **siempre** va a tomar como referencia a la etiqueta **ROOT.**

**A diferencia de EM que toma como referencia su padre directo.**

**Por ejemplo, si \<p> tiene por defecto 16px, si ponemos como medida 1rem, te dará 16px, siempre.**

> **Nota:** Un Trick en Css es configurar tu archivo inicial de la siguiente forma:

```css
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

html {
  font-size: 62.5%;
}
```

Asi podemos utilizar medidas relativas basadas en REM con una escala\
similar a pixeles, `(1.6rem => 16px, 3.5rem => 35px)`
