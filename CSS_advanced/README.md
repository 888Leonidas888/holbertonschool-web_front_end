# CSS - Hojas de estilo en cascada

CSS, que significa Hojas de Estilo en Cascada, es un lenguaje de hoja de estilo utilizado para describir la apariencia y el formato de un documento escrito en HTML. Es una tecnología fundamental utilizada por la mayoría de los sitios web para crear visualmente atractivos diseños de páginas web, colores personalizados y fuentes, y mucho más.

Aquí hay algunos puntos clave sobre CSS:

- **Separación de contenido y diseño**: CSS permite separar el contenido de la presentación. Esto significa que el HTML puede centrarse en la estructura y el contenido, mientras que el CSS se encarga del diseño y la apariencia.

- **Ahorro de tiempo**: Puedes escribir CSS una vez y luego reutilizarlo en múltiples páginas HTML. Esto puede ahorrar mucho tiempo, especialmente en sitios web grandes.

- **Páginas web con carga más rápida**: Al utilizar CSS, puedes reducir la redundancia en tu código HTML, lo que puede hacer que tus páginas web se carguen más rápido.

- **Fácil mantenimiento**: Si necesitas cambiar el estilo de tu sitio web, puedes hacerlo fácilmente cambiando tu archivo CSS.

- **Compatibilidad con dispositivos**: CSS permite un diseño adaptable que hace que tu sitio web se vea bien en todos los dispositivos, desde ordenadores de sobremesa hasta teléfonos móviles.

## Sintaxis

La imagen siguiente, muestra la sintaxis:

1. **Regla CSS**: Consiste en un selector y una declaración (que es un conjunto de propiedades y valores). Las reglas definen cómo se deben mostrar los elementos seleccionados.
2. **Selector**: Se utilizan para seleccionar el elemento(s) HTML que quieres estilizar.
3. **Propiedades**: Son los estilos que puedes aplicar a los elementos seleccionados. Algunas propiedades comunes incluyen color, tamaño de fuente, margen, relleno y fondo.
4. **Valores**: Son las configuraciones específicas que quieres aplicar a una propiedad. Por ejemplo, si la propiedad es “color”, el valor podría ser “rojo”.
5. **Declaración**: Es la propiedad con su respectivo valor.

<img src="https://i.pinimg.com/originals/9f/43/ed/9f43ed935e09d856f02aed19f9306ff5.png" width="400px" height="400px" alt="Sintaxis de CSS">

## No olvides lo siguiente:

1. **Herencia**: Es un concepto clave en CSS que permite que los estilos se “hereden” de un elemento padre a un elemento hijo.
2. **Especificidad**: Determina qué regla de CSS se aplica si varias reglas pueden aplicarse a un elemento. Una regla con mayor especificidad sobrescribirá a una regla con menor especificidad.

<img src="https://res.cloudinary.com/practicaldev/image/fetch/s--Q7AjHHJ9--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/hhf8sfgmd2w72c7yp8o3.png" width="400px" height="400px" alt="Especificidad de CSS">

3. **Hojas de estilo**: Una hoja de estilo es un archivo que contiene un conjunto de reglas. Puedes tener múltiples hojas de estilo para diferentes partes de tu sitio web.
4. **Modelo de caja**: El modelo de caja es una característica de CSS que define cómo se deben diseñar los elementos, incluyendo el relleno, el borde y el margen.

<img src="https://i.pinimg.com/originals/65/3a/c5/653ac552b34578770363c766034e2b75.png" width="400px" height="400px" alt="Los 3 pilares de CSS">

## 3 Formas de aplicar estilos

La forma recomendada es la número 3, através de archivos externos.

1. **Estilo en línea**: Puedes aplicar estilos directamente a tus elementos HTML utilizando el atributo `style`.

```html
<p style="color: blue;">Este es un párrafo azul.</p>
```

2. **Etiqueta de estilo**: Puedes incluir CSS en tu documento HTML utilizando la etiqueta `<style>` dentro del `<head>`.

```html
<head>
  <style>
    p {
      color: red;
    }
  </style>
</head>
<body>
  <p>Este es un párrafo rojo.</p>
</body>
```

3. **Archivo CSS externo**: Puedes crear un archivo CSS separado y vincularlo a tu documento HTML utilizando la etiqueta `<link>` dentro del `<head>`.

```html
<!-- En tu archivo HTML -->
<head>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <p>Este es un párrafo verde.</p>
</body>
```

```css
/* En tu archivo styles.css */
p {
  color: green;
}
```

## Sigue aprendiendo

Consult la documentación y otro sitios web para seguir aprendiendo sobre CSS.

- [MDM Web Docs (en español)](https://developer.mozilla.org/es/docs/Web/CSS)
- [W3Schools](https://www.w3schools.com/Css/)
