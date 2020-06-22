# PracticaWebCSS
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="description" content="descripción de mi sitio web">
    <meta name="author" content="Jeareth Venegas">
    <meta name="keywords" content=bloques>
    <link rel="stylesheet" href="style.css"/>
    <title>CSS - WEB I</title>
</head>

<body>
    <h1><span><em>CSS - Selectores</em></span></h1>
    <h3><span><em>Tipos de selectores</em></span></h3>
    <br>
    <p><strong>Selector Universal.</strong></p>

    <p><span>Se utiliza para seleccionar todos los elementos de la página.</span></p>
    <br>
    <p><strong>Selector de tipo o etiqueta</strong></p>
    <p>Selecciona todos los elementos de la página cuya etiqueta HTML coincide con el valor del selector.</p>
    <br>
    <p><strong>Selector descendente</strong></p>
    <p><span>Selecciona los elementos que se encuentran dentro de otros elementos. Un elemento es descendiente de otro cuando se encuentra entre las etiquetas de apertura y de cierre del otro elemento.</span></p>
    <br>
    <p><strong>Selector de clase</strong></p>
    <p><em>¿Cómo se pueden aplicar estilos CSS sólo al primer párrafo?</em></p>
    <p class= "destacado">El selector universal (*) no se puede utilizar porque selecciona todos los elementos de la página.</p>
    <p>El selector de tipo o etiqueta (p) tampoco se puede utilizar porque seleccionaría todos los párrafos.</p>
    <p class="destacado">Por último, el selector descendente (body p) tampoco se puede utilizar porque todos los párrafos se encuentran en el mismo sitio.</p>
    <br>
    <p><strong>Selector ID</strong></p>
    <P>El selector de ID permite seleccionar un elemento de la página a través del valor de su atributo id.</p> 
    <p id="destacado">Este tipo de selectores sólo seleccionan un elemento de la página porque el valor del atributo id no se puede repetir en dos elementos diferentes de una misma página.</p>
    <br>
    <p><strong>Selector de combinación</strong></p>
    <p>CSS permite la combinación de uno o más tipos de selectores para restringir el alcance de las reglas CSS.</p>
</body>

</html>