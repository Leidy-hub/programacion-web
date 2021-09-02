## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Leidy-hub/programacion-web/edit/gh-pages/docs/index.md) to maintain and preview the content for your website in Markdown files.

<! DOCTYPE html >
< html  lang = " en " >
< cabeza >
    < meta  charset = " UTF-8 " >
    < meta  http-equiv = " X-UA-Compatible " content = " IE = edge " >
    < meta  name = " viewport " content = " width = device-width, initial-scale = 1.0 " >
    < título > Documento </ título >
    < link  rel = " stylesheet " href = " estilos.css " > 
</ cabeza >
< cuerpo >
    < h1  style = " color: blue; " >   </ o > Presaberes unad 2021 </ h1 >  </ titulo >
< cabeza >
< H2 >  < br > Nombre: Leidy Milena   </ br > 
    < Br > Apellido: Rincón Ayala </ br >
    < Br > Grupo: </ br >
    < Br > Cédula: 1023919068 </ br >
    < Br > Skype: leidyrinconayala1 </ br >
    < Br > Teléfono Celular: 3209845289 </ br >
    < Br > Correo personal: milenarinconayala@gmail.com </ br >
</ h2 >

< tabla  > 
   < caption  > < h2  style = " color: blue; " > Principales etiquetas html </ h2 >  </ caption >

< tr  border = " 1 " bgcolor = LightBlue  >
    < centro >
< td > < centro > iDoctype </ centro >  </ td >
< td > < centro > HTML   </ centro >  </ td >
< td >  < centro > Cabeza   </ centro >  </ td >
< td >  < centro > Título </ centro >  </ td >
< td >  < centro > Estilo </ centro >  </ td >
< td >  < centro > Enlace </ centro >  </ td >
< td >  < centro > Cuerpo </ centro >  </ td >
< td >  < centro > Scipt </ centro >  </ td >
< td >  < centro > Meta </ centro >  </ td >
< td >  < centro > "( <! - ... -> ! - ... - > )" </ centro >  </ td >

</ tr >  

< tr  border = " 1 " bgcolor = Azul aciano >
< td > Inicia la versión de htmml </ td >
< td > Es la raiz del archivo </ td >
< td > Engloba los metadatos </ td >
< td > Titulo </ td >
< td > Escribe CSS dentro del documento html </ td >
< td > Enlaza archivos CSS </ td >    
< td > Elementos visibles en la página </ td >
< td > Enlaza o escribe javascript en el doc html </ td >
< td > Caracteristicas sobre la pagina </ td >
< td > Comentario (sólo visible en el código fuente) </ td >

</ tr >

</ tabla >

< table  id = " uno " >
    
    < caption  > < h2  style = " color: blue; " > Estilos para CSS </ h2 >  </ caption >
        < tr >
            < td > CSS </ td >
            < td > Ejemplo </ td >
            < td > Sintaxis </ td >
        </ tr >
        < tr >
            < td > Fondos </ td >
            < td > Sintaxis
                < Br > / * ^ Usando background-color ^ * / </ br >
                    < Br > fondo: verde; </ br >
                    
                    < Br > / * ^ Usando bg-imagen ^ y ^ repetición de estilo ^ * / </ br >
                        < Br > background: url ( "test.jpg") repetir-y; </ br >
                    
                        < Br > / * Usando < cuadro > y ^ background-color ^ * / </ br >
                            < Br > fondo: Frontera-rectángulo rojo; </ br >
                    
                            < Br > / * Una sola imagen, CENTRADA y escalada * / </ br >
                            < Br > fondo: no-repeat centro / 80% url ( "../ img / image.png"); </ br >   </ td >
            < td  bgcolor = " Cyan " >  </ td >
        </ tr >
        < tr >
            < td > Color </ td >
            < Td > < br > Los Colores en HTML se especifican Mediante el Estándar RGB (Rojo Verde y Azul). </ br > 
                < Br > Este Estándar indica Que Una Combinación de los Tres Colores Básicos: rojo, </ br >
                < Br > Verde y Azul PUEDE dar Lugar a Otro any color. </ br >
                < Br > Los Valores Que se les da al hijo RGB Valores hexadecimales van Que Desde el 00 Hasta el FF. </ br >
                < Br > Al valor del color de se le antepone Una almohadilla. </ br >
            
            </ td >
            < Td  > < br >  < p  estilo = color: # FF0000 > De forma this ONU de color rojo seria Aquel Que Tiene solitario Activado el rojo, </ br >
                < Br > < p  estilo = color: # 00FF00 > El Verde solo la parte del verde y < p  estilo = color: # 0000FF > El Azul La Parte del azul. </ br >
                < Br > < p  estilo = color: # F76138 > Así Los Colores Básicos en HTML Séran: </ br >
                < Br > < p  estilo = color: # FF0000 > Rojo # FF0000 </ br >
                < Br > < p  estilo = color: # 00FF00 > Verde # 00FF00 </ br >
                < Br >  < p  estilo = color: # 0000FF > Azul # 0000FF </ br >  </ td >
        </ tr >
        < tr >
            < td > Fronteras </ td >
            < Td > < br > La propiedad permite frontera Definir de golpe todos los bordes </ br >
                < Br > En Una Única regla de la hoja de Estilos. </ br > </ td >
                
                < td > 
                < h2  style = " color: # 50B748; margin: 20px; text-align: right; border-style: dashed; " > Hola mundo mundo </ h2 > </ td >
        </ tr > 
        < tr >
            < td > Márgenes </ td >
            < td > / * Aplica a todos los cuatro lados * /
                < Br > margen: 1 em; </ br >
                
                < Br >   / * Vertical | Horizontal * / </ br >
                < Br > margen: 5% auto; </ br >
                
                < Br > / * Arriba | Horizontal | Abajo * / </ br >
                < Br >   margen: 1 em 2em automático; </ br >
                
                < Br >   / * Arriba | Derecha | Abajo | Izquierda * / </ br >
                < Br >   margen: 2px 1 em 0 auto; </ br >
                
                < Br > / * Valores Globales * / </ br >
                < Br > margen: heredar; </ br >
                < Br > margen: inicial; </ br >
                < Br >   margen: unset; </ br > </ td >
        
            < div  class = " et2 " >
            < td > < h3  style = " color: darkgoldenrod; margin: 25px; border: 1px solid black; " > Fila 2 Este espacio es un ejemplo para dar una margen distinta </ h3 > </ td > </ class >
        </ tr > 
        < tr >
            < td > Texto </ td >
            < Td > < br > / * Valores clave * / </ br >
                < Br > text-decoration: none; / * Sin decoración * / </ br >
                < Br > text-decoration: underline rojo; / * Subrayado rojo * / </ br >
                < Br > text-decoration: underline ondulado de color rojo; / * Subrayado rojo ondulado * / </ br >
                
                < Br > / * Valores Globales * / </ br >
                < Br > text-decoration: heredar; </ br >
                < Br > text-decoration: inicial; </ br >
                < Br > text-decoration: desarmar; </ br > </ td >

            < td >
                < h2  style = " text-shadow: 2px 5px 2px # F76138; " > Subrayado Salmon efecto shadow </ h2 > </ td >
        </ tr > 
        < tr >
            < td > Fuentes </ td >
            < td > Nos permite definir el aspecto de una familia tipográfica
                 </ td >
            < td >  < h2  style = " font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; letter-spacing: 3px; " > De esta manera podemos cambiar las fuentes </ td >
            < td >  < h2  style = " font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; letter-spacing: -3px; " > y darle una visión distinta a nuestro texto </ td >

            </ tr > 
        < tr >
            < td > Altura </ td >
            < Td > < br > La propiedad CSS altura ESPECIFICA La altura del área de contenido de la ONU Elemento. </ br >
                < Br > El área de contenido ESTA DENTRO DEL relleno, Borde, y margen del Elemento </ br > </ td >
            < td >
               < h5  style = " height: 100px; border: 1px solid # 4CAF50 " > Este elemento tiene una altura de 100 píxeles </ h5 > </ td >
        </ tr >
        < tr >
            < td > Ancho </ td >
            < td > Especifica la anchura del area de contenido de un elemento </ td >
            < td >
                < h5  style = " width: 100%; border: 1px solid # 4CAF50 " > Este elemento tiene un ancho de 100% píxeles </ h5 > </ td >
            </ tr >
        < tr >
            < td > Enlaces </ td >
            < Td >  < br > ESPECIFICA La Relación Entre el documento real externo recurso y de la ONU. </ br >
                < Br > Los usos Posibles of this Elemento INCLUYEN La Definición de la ONU Marco
                 relacional para navegación. </ br > </ td >
            < td >
                Ver enlace de < un  href = " http://google.com.co " target =" _blank " > page </ una > </ td >
                
        </ tr >
        < tr >
            < td > Listas </ td >
            < td > Se utilizan para establecer de forma abreviada el valor de
                una o más propiedades individuales. </ td >
            < td >
               < Br > < h3  estilo = " estilo de tipo lista: círculo; " >  < li > Purpura </ li > < li > Purpura </ li >  < li > Purpura </ li > </ h3 > </ br >
               < Br > < h3  estilo = " estilo de tipo lista: superior-roman; " >  < li > Purpura </ li > < li > Purpura </ li >  < li > Purpura </ li > </ h3 > </ br >
            </ tr >
        < tr >
            < td > Tablas </ td >
            < td > Presenta datos en dos o más dimensiones </ td >

            < td > < table  id = " clientes " >
                < tr >
                  < th > Paquete 1 </ th >
                  < th > Paquete 2 </ th >
                  < th > Paquete 3 </ th >
                </ tr >
                < tr >
                  < td > Matemáticas </ td >
                  < td > Ciencias </ td >
                  < td > Fisica </ td >
                </ tr >
                < tr >
                  < td > Economía </ td >
                  < td > Arte </ td >
                  < td > Química </ td >
                </ tr >
                < tr >
                  < td > Redacción </ td >
                  < td > Historia </ td >
                  < td > Inglés </ td > </ td >
        </ tr >
    </ tabla >
        < tr >
            < td > Posición </ td >
            < Td > < br > La posición de propiedad de CSS ESPECIFICA Como Un Elemento ES ha posicionado </ br >
                < Br > en el documento. </ br >
                < Br > Las propiedades arriba, derecha, abajo, izquierda y determinante La ubicación </ br >
                < Br > última de Los Elementos posicionados. </ br > </ td >
                < td >   < h2 > Posición: absoluta; </ h2 >
                    
                    < Div  clase = " relativo " > Este Elemento TIENE UNA s posición: Relativa;
                      < div  class = " absolute " > Este elemento tiene una posición: absoluta; </ div >  </ td >
        </ tr >
        < tr >
            < td > Desbordamiento </ td >
            < Td > < br > La propiedad CSS desbordamiento ESPECIFICA: si recortar contenido, </ br >
                < Br > dibujar Barras de Desplazamiento o Mostrar el contenido excedente En un Elemento Nivel de un bloque. </ br >
                < Br > Usando la propiedad de desbordamiento Con Un valor Distinto de manera visible, el valor por Defecto, </ br >
                < Br > Creara Un Nuevo contexto de Formatos de bloques. </ br > </ td >
            < td > < h2 > Desbordamiento de CSS </ h2 >
                < p > De forma predeterminada, el desbordamiento es visible, lo que significa que no está recortado y se renderiza fuera de la caja del elemento </ p >
                < div > Puede utilizar la propiedad de desbordamiento cuando desee tener un mejor control del diseño. Este ejemplo fue tomado de https://www.w3schools.com/css/tryit.asp?filename=trycss_overflow_visible </ div > </ td >
        </ tr >

        < tr >
            < td > Flotar </ td >
            < Td > < br > La propiedad CSS float UBICA ONU Elemento al Lado Izquierdo o derecho de su contenedor, </ br >
                < Br > permitiendo una Los Elementos de texto y en Línea Aparecer un costado do. </ br >
                < Br > El elemento m es removido del Flujo normal de la página elegida, </ br >
                < Br > AUNQUE AÚN Sigue Siendo parte del Flujo (una Diferencia del posicionamiento absoluto). </ br > </ td >
            < td >
            < p > < img  src = " UNAD_18_.jpg " alt = " UNAD " style = " width: 170px; height: 170px; float: right; " >

                < h1 > Flotar a la derecha </ h1 >
                < h3 > En este ejemplo podremos crear un parrafo ya su costado colocar una imagen.
         
        Fragmento de un escrito con unidad temática, que queda diferenciado del resto de fragmentos 
        por un punto y aparte y generalmente también por llevar letra mayúscula inicial y un espacio 
        en blanco en el margen izquierdo de alineación del texto principal de la primera línea. </ h3 > </ p > </ td >
</ tr >
    </ tabla >


</ td >
</ tabla >
</ cuerpo >
</ html >

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
