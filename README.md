<!-- # Desafío: CSS -->

<!-- ## Nombre de Desafío: css_introducción

## Instrucciones -->

<!-- Completa los siguientes desafíos, para que pueda funcionar de manera correcta los códigos css. -->

<!-- I. Establezca el color de todos los elementos `<p>` en rojo.

``` -->

<style>
p {
  color: red;
}
</style>


<!-- II. Establezca el color del elemento con id="para1", en rojo.

``` -->
<style>
#para1 {
  color: red;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p id="para1">This is a paragraph</p>
</body>
```

<!-- III. Establezca el color de todos los elementos con la clase colortexten rojo.

``` -->
<style>
.colortext {
  color: red;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p class="colortext">This is a paragraph</p>
  <p class="colortext">This is a paragraph</p>
</body>
```

<!-- IV. Cambia el color de todos los elementos `<p>` y `<h1>` a "rojo". Agrupe los selectores para minimizar el código. -->

<style>
h1,p {
  color: red;
}
</style>

<body>
  <h1>This is a heading</h1>
  <h2>This is a smaller heading</h2>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

<!-- V. Agregue una hoja de estilo externa con la URL: "mystyle.css". -->

<head>
<link rel="stylesheet" href="./mystyle.css"
</head>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>


<!-- VI. Inserte las partes que faltan para que el código CSS sea correcto. -->

<style>
p{
  color: red;
}
</style>


<!-- VII. Utilice la propiedad abreviada border para establecer un borde "4px", "punteado", "rojo" para los elementos `<p>`. -->

<style>
p{
  border-style: dotted; color: red;border-width: 4px;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>


<!-- VIII. Utilice la propiedad de borde correcta para establecer el color del borde en "rojo". -->

<style>
p {
  border-style: dotted;
  border-width: 4px;
  color: red;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

<!-- IX. Agregue un margen izquierdo de 20 píxeles al elemento `<h1>`. -->

<style>
h1{
    margin-left: 20px;  
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>


<!-- X. Utilice la propiedad margin abreviada para agregar márgenes superior e inferior de 20 píxeles y márgenes izquierdo y derecho de 40 píxeles en el elemento `<h1>`. -->
 

<style>
h1{
  margin: 20px 40px;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>


<!-- XI. Utilice la marginpropiedad para alinear al centro el elemento `<h1>`. -->

<style>
h1 {
  margin: 20px 20px 20px 20px;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>


<!-- XII. Establezca el relleno superior del elemento `<h1>` en 30 píxeles. -->

<style>
h1 {
  padding-top:30px;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>


<!-- XIII. Use la propiedad de relleno abreviado para agregar 10 píxeles de relleno izquierdo y derecho, y 40 píxeles de relleno superior e inferior, en el elemento `<h1>`. -->

<style>
h1 {
  padding: 40px 10px;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

<!-- XIV. Establezca la altura del elemento `<h1>` en "100px". -->

<style>
h1 {
  height: 100px;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

<!-- XV. Establezca el ancho del elemento `<h1>` en "50 %". -->

<style>
h1 {
  width: 50%;
}
</style>

<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph</p>
  <p>This is a paragraph</p>
</body>

<!-- XVI. Establezca el ancho del elemento `<div>` en "200px". -->

<style>
div{
  width: 200px;
}
</style>
<body>
  <div>
  Lorem ipsum dolor sit amet,
  consectetur adipiscing elit,
  sed do eiusmod tempor incididunt
  ut labore et dolore magna aliqua.
  </div>

</body>

<!-- XVII. Agrega un espacio de 25 píxeles afuera, a la izquierda del elemento `<div>`. -->

<style>
div {
  width: 200px;
  border: 2px solid red;
  padding: 25px;
  margin-left: 25px;
}
</style>

<body>

<div>
Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua.
</div>

</body>


<!-- XVIII. Fuerce una barra de desplazamiento al elemento `<div>` con class="intro". -->


<style>
.intro {
  width: 200px;
  height: 70px;
  overflow: scroll;
}
</style>

<body>

<div class="intro">
Lorem ipsum dolor sit amet,
consectetur adipiscing elit.
Phasellus imperdiet, nulla et dictum interdum,
nisi lorem egestas odio,
vitae scelerisque enim ligula venenatis dolor.
</div>

</body>


<!-- XIX. Especifique que el texto desbordado en el elemento `<div>` no debe ser visible, ni siquiera con una barra de desplazamiento. -->


<style>
.intro {
  width: 200px;
  height: 70px;
  overflow: hidden;
}
</style>

<body>

<div class="intro">
Lorem ipsum dolor sit amet,
consectetur adipiscing elit.
Phasellus imperdiet, nulla et dictum interdum,
nisi lorem egestas odio,
vitae scelerisque enim ligula venenatis dolor.
</div>

</body>


<!-- XX. Agregue una barra de desplazamiento horizontal al elemento `<div>`. -->


<style>
.intro {
  width: 200px;
  height: 70px;
  overflow-x: scroll;
}
</style>

<body>

<div class="intro">
Lorem ipsum dolor sit amet,
consectetur adipiscing elit.
Phasellus imperdiet, nulla et dictum interdum,
nisi lorem egestas odio,
vitae scelerisque enim ligula venenatis dolor.
</div>

</body>

