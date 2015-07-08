Responsive Tooltips:
====================
- Utility for easy creation of tooltips that also work on mobile devices.
- Utilidad para la fácil creación de "tooltips" que también funcionan en dispositivos móviles.

USE/USO:
=======
- You just need to indicate the tooltip in the attribute "title", and add the attribute "rel" with the value "tooltip" on the label (with inline display) to which you apply the tooltip.

- Solo necesitas indicar el tooltip en el atributo "título", y añadir el atributo "rel" con el valor "tooltip" a la etiqueta (con display inline) a la cual se le aplicara el tooltip.

Example/Ejemplo:
  <head>
    <link rel="stylesheet" href="estilos.css">...
    
  <body>
    <abbr title="User Experience" rel="tooltip">UX</abbr>
    
    <script src="index.js"></script>
	  <script type="text/javascript">
		  var Tooltips = require('tooltips');
		  Tooltips.init_tooltip();
	  </script>
________________________	  
Note: Do not forget to link the "estilos.css" (in which you can modify the appearance of the tooltip) file.

By default tooltips are displayed when you "hover" the mouse over an element. And they hide when "mouseleave" over the item.

To support mobile devices, tooltips are displayed when you "tap" / "click" on the element, and hide to make a new "tap" / "click" on the tooltip.

Also you can use the "remove_tooltip" function to indicate when you want the tooltip to be hidden.
________________________
Nota: no olvidar enlazar el archivo "estilos.css" (en el cual puedes modificar la apariencia del tooltip).

Por defecto los tooltips se muestran al hacer "hover" con el mouse sobre un elemento. Y se ocultan al hacer "mouseleave" encima del elemento.

Para dar soporte a dispositivos moviles, los tooltips se muestran al hacer "tap"/"click" sobre el elemento, y se ocultan al hacer un nuevo "tap"/"click" sobre el tooltip.

Tambien se puede usar la función "remove_tooltip", para indicar cuando queremos que se oculte el tooltip.
