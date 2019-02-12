# Tablas

De forma predeterminada, las tablas se ajustan en su ancho al contenido

* `table-layout* `especifica como se distribuirá el espacio de las columnas. 
    Valores
      * `automatic` (default)
      * `fixed:` el ancho de la tabla se define con width. Si no se especifica un ancho para las columnas, serán uniformes.

* `caption-side* `Indica si el caption se mostrará arriba (top, default) o abajo (bottom)
* `border-spacing: x y;* `Indica la separacion entre las celdas (solo aplica si la tabla tiene border-collapse: separate)
* `border-collapse`, Indica si los bordes de la tabla y las celdas se unirán (collapse) o estarán separados (separate, default)

---------------------------------------------------------------------------

**EJEMPLO CÓDIGO**: 

---------------------------------------------------------------------------

<div>
  <img src="https://lenguajecss.com/img/logo.png" width=20px><h1 style="display: inline;">This is a heading</h1>
  <h1>This is a heading</h1>
</div>
  
```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      h1::before {
        content: url(https://lenguajecss.com/img/logo.png);
      }
    </style>
  </head>
  <body>
    <h1>This is a heading</h1>
    <h1>This is a heading</h1>
  </body>
</html>
```

---------------------------------------------------------------------------

[Volver al inicio](#-Tablas)