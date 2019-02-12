# Formularios

PSEUDO CLASES PARA FORMULARIOS

* `::placeholder` (estilos para el placeholder)
* `:checked` (inputs seleccionados)
* `:focus` (inputs con el cursor dentro)
* `:required` (campos obligatorios)
* `:disabled` (campos desactivados)
* `:read-only` (campos de solo lectura)

[Volver al inicio](#-Formularios)

---------------------------------------------------------------------------

**EJEMPLO CÓDIGO**: PLACEHOLDER

---------------------------------------------------------------------------

<div>
    <input type="text" name="fname">
    <input type="text" name="fname" placeholder="First name" style="color: red;">
</div>

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
    ::-webkit-input-placeholder { /* Edge */
      color: red;
    }
    :-ms-input-placeholder { /* Internet Explorer */
      color: red;
    }
    ::placeholder {
      color: red;
    }
    </style>
  </head>
  <body>
    <input type="text" name="fname">
    <input type="text" name="fname" placeholder="First name">
  </body>
</html>
```

---------------------------------------------------------------------------

**EJEMPLO CÓDIGO**: READ-ONLY

---------------------------------------------------------------------------

<div>
    <p>A normal input element:<br><input value="hello"></p>
    <p>A readonly input element:<br><input readonly value="hello" style="background-color: yellow;"></p>
</div>

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      input:-moz-read-only { /* For Firefox */
        background-color: yellow;
      }
      input:read-only {
        background-color: yellow;
      }
    </style>
  </head>
  <body>
    <p>A normal input element:<br><input value="hello"></p>
    <p>A readonly input element:<br><input readonly value="hello"></p>
  </body>
</html>
```

[Volver al inicio](#-Formularios)