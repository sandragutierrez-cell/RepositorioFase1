# RepositorioFase1
Unad
<html lang-"es">
<meta http-equiv=”Content-Type” content=”text/html; charset=UTF-8″ />
<head>
  <h1> FASE 1 PRESABERES </h1>
     
     <!-- Se realiza vinculación con un archivo externo de estilos CSS -->
  
  <link rel="stylesheet" type="text/css" href="style.css">
   <style>
    h1 { color: #0000FF; }
    { background: gray  }
   </style>
</head>
<body>
      <h2>Nombre: Sandra Gutiérrez
          Grupo: 301127_3
          Cedula: 52751401
          Skype: Sandra Gutierrez
          Celular: 3192964349
          Correo personal: sanjoguti71284.25@gmail.com
      </h2>
       <style>
    h2 { color:  #FFFF00; }     
   </style>
  <style type="text/css">
       table, th, td {   
    border: 1px solid black; 
    border-collapse: collapse; }    
    th, td {  
    padding: 10px; }
    th {
    text-align: left;}
   </style>
   <link rel="stylesheet" href="tabla.css">
</body>
<body>
     <table style="width: 100%">
         <tr> 
            <th>
                ETIQUETA HTML
            </th>
            <th>
                DESCRIPCION 
            </th>
         </tr>
         <tr>
           <td>
               HTML
            </td>
            <td>
               indica el comienzo del documento HTML.
            </td>
         </tr>
         <tr> 
            <td>
              HEAD
            </td>
            <td>
              indica que empieza la cabecera de la página
            </td>
         </tr>
         <tr> 
           <td>
              BODY
            </td>
            <td>
              es el cuerpo de la página, donde va lo que se ve en el navegador al cargar una web
            </td>
         </tr>
         <tr> <td>
              H1, H2...
            </td>
            <td>
              son los títulos o encabezados
            </td>
         </tr>
         <tr> 
           <td>
              a
            </td>
            <td>
              define los enlaces
            </td>
         </tr>
         <tr> 
           <td>
              TABLE
            </td>
            <td>
              es una tabla, y dentro de esta tenemos filas <tr> y celdas
            </td>
         </tr>
         <tr> 
           <td>
               p
            </td>
            <td>
               el texto dentro de esta etiqueta forma un párrafo
            </td>
         </tr>
         <tr>
           <td>
               imag
            </td>
            <td>
               imágenes
            </td>
         </tr>
         <tr> 
           <td>
               ul
            </td>
            <td> 
              los textos dentro de esta etiqueta se estructuran en listas. 
              Mediante el uso de li definimos cada guión dentro  
              de la lista, y usando ol en lugar de ul tendremos listas ordenadas
            </td>
         </tr>
         <tr>
           <td>
              b y strong
            </td>
            <td>
              se utilizan para resaltar el texto
            </td>
         </tr>
      </table>
</body>
       <body>
     <table style="width: 100%";
            margin= auto;
            font-family: Arial;>
         <tr> 
           <th> background= "purple";
             text-transform= "uppercase";
            <th>
                ESTILOS CSS 
            </th>
            <th>
                DESCRIPCION 
            </th>
         </tr>
         <tr>
           <td>
               COLORS 
            </td>
            <td>
              <color> selecciona el valor de color de primer plano del contenido de elemento de texto y decoraciones de texto
            </td>
         </tr>
         <tr> 
            <td>
              BACKGROUNDS 
            </td>
            <td>
              es un atajo para definir los valores individuales del fondo en una única regla CSS.
              background: [  <background-color>    ||  <background-image>       ||
               <background-repeat>   ||  <background-attachment>  ||
               <background-position>
            ]   |   inherit ;
            </td>
         </tr>
         <tr> 
           <td>
              BORDERS
            </td>
            <td>
              permite definir de golpe todos los bordes en una única regla de la hoja de estilos. Se puede utilizar border para              definir el o los valores siguientes: border-width, border-style, border-color.
              border: [border-width || border-style || border-color | inherit] ;
            </td>
         </tr>
         <tr> <td>
             MARGINS
            </td>
            <td>
               establece el margen para los cuatro lados. Es una abreviación para evitar tener que establecer 
              cada lado por          separado con las otras propiedades de margen:  margin-top, margin-right, 
              margin-bottom y       margin-left.
              /* Aplica a todos los cuatro lados */
               margin: 1em;
              /* Vertical | Horizontal */
              margin: 5% auto;
          /* Arriba | Horizontal | Abajo */
           margin: 1em auto 2em; 
          /* Arriba | Derecha | Abajo | Izquierda */
           margin: 2px 1em 0 auto;
              /* Valores globales */
          margin: inherit;
          margin: initial;
          margin: unset;
            </td>
         </tr>
         <tr> 
           <td>
             TEXT
            </td>
            <td>
             define cómo realizar la manipulación de elementos de texto como los saltos de línea, la justificación, 
              la      alineación, 
             la gestión de espacios en blanco y las transformaciones de texto.
              text-align text-align-last text-indent text-size-adjust text-transform
            </td>
         </tr>
         <tr> 
           <td>
              FONTS
            </td>
            <td>
              permite establecer de una sola vez los valores para todas las propiedades: font-style, font-variant, 
              font-weight, font-size, line-height y font-family en una hoja de estilo.
              font: [ <font-style> || <font-variant> || <font-weight> ]? <font-size> [ / <line-height> ]? <font-family>
            font: caption | icon | menu | message-box | small-caption | status-bar | -moz-window | -moz-document | 
              -moz- workspace | -moz-desktop | -moz-info | -moz-dialog | -moz-button | -moz-pull-down-menu 
              | -moz-list | -moz-field font: inherit
            </td>
         </tr>
         <tr> 
           <td>
               HEIGHT
            </td>
            <td>
               especifica la altura del area de contenido de un elemento. El área de contenido está dentro del padding, 
              borde, y margen del elemento.
              /* Valores clave */
        height: auto;
        /* Valores <length> */
       height: 120px;
      height: 10em;
      /* Valores <percentage> */
     height: 75%;
      /* Valores globales */
    height: inherit;
    height: initial;
    height: unset;
            </td>
         </tr>
         <tr>
           <td>
               WIDTH
            </td>
            <td>
              especifica la anchura del area de contenido de un elemento. El área de contenido está dentro del padding, borde, y margen del elemento.
              /* Valores <length> */
width: 300px;
width: 25em;

/* Valores <percentage> */
width: 75%;

/* Valores clave */
width: 25em border-box;
width: 75% content-box;
width: max-content;
width: min-content;
width: available;
width: fit-content;
width: auto;

/* Valores globales */
width: inherit;
width: initial;
width: unset;
            </td>
         </tr>
         <tr> 
           <td>
               LINKS
            </td>
            <td> 
              representa un elemento que aún no se ha visitado. Coincide con cada elemento no visitado <a>, <area>, 
              o <link> que tiene un atributo href.
              :link
            </td>
         </tr>
         <tr>
           <td>
             LISTS
            </td>
            <td>
              La propiedad de estilo de lista (list-style) permite definir de golpe todos los parámetros: 
              list-style-type, list-style-image, y list-style-position.
              list-style: [ list-style-type || list-style-position || list-style-image ] | inherit
            </td>
         </tr>
          <tr>
