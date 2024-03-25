# Actividad 36

**2. Realiza un XML para estructurar la información de la tabla siguiente:**

### XLM

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE libros>
<libros>
    <libro ISBN="979-8391200475">
        <titulo>Git y Github desde cero</titulo>
        <autor>Brais Moure</autor>
        <anio_publicacion>2023</anio_publicacion>
        <editorial>Publicación independiente</editorial>
        <paginas>321</paginas>
    </libro>
    <libro ISBN="978-8441532106">
        <titulo>Código Limpio</titulo>
        <autor>Robert C. Martin</autor>
        <anio_publicacion>2012</anio_publicacion>
        <editorial>Anaya Multimedia</editorial>
        <paginas>463</paginas>
    </libro>
    <libro ISBN="979-8852737427">
        <titulo>Aprendiendo JavaScript</titulo>
        <autor>Carlos Azaustre</autor>
        <anio_publicacion>2023</anio_publicacion>
        <editorial>Publicación independiente</editorial>
        <paginas>286</paginas>
    </libro>
    <libro ISBN="978-8441545878">
        <titulo>El programador prágmatico</titulo>
        <autor>David Thomas y Andrew Hunt</autor>
        <anio_publicacion>2022</anio_publicacion>
        <editorial>Anaya Multimedia</editorial>
        <paginas>339</paginas>
    </libro>
</libros>
```

**[archivo en drive](https://drive.google.com/file/d/17JlVUrLdLqkuDk61Dl18Zoogk2Mlgqod/view?usp=sharing)**

**3. Escribir un documento XML que almacene la siguiente información:**

### XLM

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE ciudades>
<Ciudades>
    <Ciudad HusoHorario="UTC+1">
        <Nombre>Ceuta</Nombre>
        <Pais Continente="Africa">España</Pais>
        <Elevacion>10m</Elevacion>
    </Ciudad>
    <Ciudad HusoHorario="UTC+2">
        <Nombre>Santorini</Nombre>
        <Pais Continente="Europa">Grecia</Pais>
        <Elevacion>260m</Elevacion>
    </Ciudad>
    <Ciudad HusoHorario="UTC+8">
        <Nombre>Hong Kong</Nombre>
        <Pais Continente="Asia">China</Pais>
        <Elevacion>957m</Elevacion>
    </Ciudad>
    <Ciudad HusoHorario="UTC-6">
        <Nombre>Guadalajara</Nombre>
        <Pais Continente="América">México</Pais>
        <Elevacion>1566m</Elevacion>
    </Ciudad>
    <Ciudad HusoHorario="UTC+1">
        <Nombre>Casablanca</Nombre>
        <Pais Continente="África">Marruecos</Pais>
        <Elevacion>27m</Elevacion>
    </Ciudad>
</Ciudades>
```

**[archivo en drive](https://drive.google.com/file/d/1oLLeP4cwOjs08S0J8paoVRiWFWsN3hRX/view?usp=sharing)**

**4. Escribir un documento XML que almacene la siguiente información:**

### XLM

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE Hechoshistoricos>
<Hechos_historicos>
    <hecho descripcion="IBM da a conocer el PC">
        <fecha>
            <dia>12</dia>
            <mes>8</mes>
            <anio>1981</anio>
        </fecha>
    </hecho>
    <hecho descripcion="Tim Berners-Lee escribe la primera web">
        <fecha>
            <dia>20</dia>
            <mes>12</mes>
            <anio>1990</anio>
        </fecha>
    </hecho>
    <hecho descripcion="Se funda Google">
        <fecha>
            <dia>4</dia>
            <mes>9</mes>
            <anio>1998</anio>
        </fecha>
    </hecho>
    <hecho descripcion="Se funda Facebook">
        <fecha>
            <dia>4</dia>
            <mes>2</mes>
            <anio>2004</anio>
        </fecha>
    </hecho>
    <hecho descripcion="Steve Jobs presenta el iPhone">
        <fecha>
            <dia>29</dia>
            <mes>6</mes>
            <anio>2007</anio>
        </fecha>
    </hecho>
</Hechos_historicos>
```

**[archivo en drive](https://drive.google.com/file/d/11vYSvfyxGSJX5wnRyqR4W7k1oX5hJmBQ/view?usp=sharing)**

**5. Sin utilizar atributos, crear un documento XML bien formado que describa una lista de marcadores de páginas web, sabiendo que se desea que la información de cada página sea el nombre, una descripción breve y su URL. Los datos de los marcadores son los descritos en la siguiente tabla:**

### XLM

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE marcadores>
<marcadores>
    <marcador>
        <nombre>MDN Web Docs</nombre>
        <descripcion>Resources for Developers, by Developers</descripcion>
        <url>https://developer.mozilla.org/es/</url>
    </marcador>
    <marcador>
        <nombre>Lenguaje JavaScript</nombre>
        <descripcion>JavaScript en Español</descripcion>
        <url>https://lenguajejs.com/</url>
    </marcador>
    <marcador>
        <nombre>W3Schools</nombre>
        <descripcion>Learn to code</descripcion>
        <url>https://www.w3schools.com</url>
    </marcador>
    <marcador>
        <nombre>Wikipedia</nombre>
        <descripcion>La enciclopedia libre</descripcion>
        <url>https://es.wikipedia.org/</url>
    </marcador>
</marcadores>
```

**[archivo en drive](https://drive.google.com/file/d/1sKkAikH3CuShRE3Sa34sMSLcjywoGRgh/view?usp=sharing)**

**6. Escribir un documento XML bien formado que guarde información de dos equipos de fútbol (nombre, estadio, ciudad y entrenador) con tres jugadores (nombre, apellidos, numero, posición y nacionalidad) cada uno. La posición (portero, defensa, medio o delantero) deberá representarse mediante un atributo del jugador.Utilizar datos reales para los equipos y jugadores. No obstante, no deberá indicarse el nombre del entrenador.**

### XLM

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE equipos>
<equipos>
    <equipo>
        <nombre>f.c.barcelona</nombre>
        <estadio>spotify Cam Nou</estadio>
        <ciudad>barcelona</ciudad>
        <entrenador nombre="xavi"></entrenador>
        <jugadores>
            <jugador posicion="dfc">
                <nombre>Ronald</nombre>
                <apellidos>Federico Araújo da Silva</apellidos>
                <numero>4</numero>
                <nacionalidad>uruguayo</nacionalidad>
            </jugador>
            <jugador posicion="mc">
                <nombre>Pedro</nombre>
                <apellidos>González López</apellidos>
                <numero>8</numero>
                <nacionalidad>español</nacionalidad>
            </jugador>
            <jugador posicion="mc">
                <nombre>Frenkie</nombre>
                <apellidos>de Jong</apellidos>
                <numero>22</numero>
                <nacionalidad>holandes</nacionalidad>
            </jugador>
        </jugadores>
    </equipo>
    <equipo>
        <nombre>real madrid</nombre>
        <estadio>santiago bernabeu</estadio>
        <ciudad>madrid</ciudad>
        <entrenador nombre="anchelotti"></entrenador>
        <jugadores>
            <jugador posicion="dfc">
                <nombre>Éder</nombre>
                <apellidos>Gabriel Militão Pinheiro</apellidos>
                <numero>3</numero>
                <nacionalidad>brasileño</nacionalidad>
            </jugador>
            <jugador posicion="mc">
                <nombre>Federico</nombre>
                <apellidos>Santiago Valverde Dipetta</apellidos>
                <numero>15</numero>
                <nacionalidad>uruguayo</nacionalidad>
            </jugador>
            <jugador posicion="ei">
                <nombre>Vinícius</nombre>
                <apellidos>José Paixão de Oliveira Júnior</apellidos>
                <numero>7</numero>
                <nacionalidad>brasileño</nacionalidad>
            </jugador>
        </jugadores>
    </equipo>
</equipos>
```

**[archivo en drive](https://drive.google.com/file/d/1mvWCq_W6jk9-JB0Y4zjTMOWl9E5IeG2Q/view?usp=sharing)**

**7. Corregir los errores que hay en el siguiente documento XML ("frutas.xml") para que esté bien formado. Para ello, puede ser necesario crear nuevas etiquetas o atributos.**

### XLM

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE lista_de_frutras>
<frutas>
    <fruta>cereza</fruta>
    <fruta>naranja</fruta>
</frutas>
```

**[archivo en drive](https://drive.google.com/file/d/1U4ZxTvdgSL2XCQTlS2732QbAJCV91gBI/view?usp=sharing)**

**8. Corregir los errores que hay en el siguiente documento XML ("vehiculos.xml") para que esté bien formado. Para ello, puede ser necesario crear nuevas etiquetas o atributos.**

### XLM

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE vehiculos>
<vehiculos>
    <terrestres>
        <vehiculo>bicicleta</vehiculo>
        <vehiculo>coche</vehiculo>
        <vehiculo>tractor</vehiculo>
    </terrestres>
    <acuaticos>
        <vehiculo>canoa</vehiculo>
    </acuaticos>
    <aereos>
        <vehiculo>avioneta</vehiculo>
        <vehiculo>helicóptero</vehiculo>
    </aereos>
</vehiculos>
```

**[archivo en drive](https://drive.google.com/file/d/1zb_edCrmIhWuJPpFFxlJAlPywpctBLqF/view?usp=sharing)**

**9. Corregir los errores que hay en el siguiente documento XML ("figuras.xml") para que esté bien formado. Para ello, puede ser necesario crear nuevas etiquetas o atributos.**

### XLM

```xml
<!DOCTYPE figuras >

<figuras>
    <figura tipo="plana">
        <nombre>cuadrado</nombre>
        <lados>4</lados>
    </figura>
    <figura tipo="plana">
        <nombre>triángulo</nombre>
        <lados>3</lados>
    </figura>
    <figura tipo="tridimensional">
        <nombre>cubo</nombre>
        <aristas>12</aristas>
        <caras>6</caras>
    </figura>
</figuras>
```

**[archivo en drive](https://drive.google.com/file/d/1ZqOQa1IR2hb61wepj0PmBTj68vzcSHKv/view?usp=sharing)**

**10. Realiza un documento XML en la que añadáis una sección CDATA con el código HTML de una página web.**

### XLM

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE html>
    <(#PCDATA)a
        <html>
            <head>
                <meta charset="UTF-8">
                <title>tim brack, senior art director</title>
                <meta name="description" content="senior art director &amp; concept creative working for jung von matt.">

                <link href="css/styles.css" rel="stylesheet" type="text/css">
                <link href="css/animate.css" rel="stylesheet" type="text/css">

                <script type="text/javascript" src="http://code.jquery.com/jquery-1.10.2.js"></script>
                <script type="text/javascript" src="js/functions.js"></script>
                <script type="text/javascript" src="js/jquery.onepage-scroll.js"></script>

            </head>

            <body style="">
                <div id="home" class="animated fadeInUp" style="font-size: 24.1975px;">
                    hi. my name is <a href="#contact" class="scroll">tim</a>. im an awarded senior art director <a href="#work_wrapper" class="scroll">working</a> for jung von matt.
                </div>
                <style>.cryptedmail:after { content: attr(data-name);}</style>
                <div id="contact" style="height: 968px;">
                    <h1 style="font-size: 140px;">
                        you can contact me via 
                        <a href="#" class="cryptedmail" data-name="mail" data-domain="timbrack" data-tld="de" onclick="window.location.href = 'mailto:' + this.dataset.name + '@' + this.dataset.domain + '.' + this.dataset.tld; return false;"></a>
                        or <a href="https://www.linkedin.com/in/tim-brack-341285103" target="_blank">linkedin</a> or <a href="https://www.xing.com/profile/Tim_Brack" target="_blank">xing</a>.
                    </h1>
                </div>

                <!-- Resto del código HTML -->

                <script src="js/jquery.fittext.js"></script>
                <script type="text/javascript">
                    $("#home").fitText(0.81, { minFontSize: '20px', maxFontSize: '350px' });
                    $(".work h1").fitText(0.62, { minFontSize: '30px', maxFontSize: '500px' });
                    $(".work h2").fitText(0.45 , { minFontSize: '30px', maxFontSize: '500px' });
                    $("#contact h1").fitText(0.80, { minFontSize: '140px', maxFontSize: '350px' });
                    $("#fittext3").fitText(1.1, { minFontSize: '50px', maxFontSize: '75px' });
                </script>
            </body>
        </html>
    ]]>
```

**[archivo en drive](https://drive.google.com/file/d/1FUZBM9HYtKYALc05Wkt12lnghnfof1GN/view?usp=sharing)**

**11. Una tienda de muebles, necesita organizar sus productos (mesas y sillas) para guardar la siguiente información: nombre, ancho, alto, profundidad y material. A partir del enunciado y el ejemplo anterior, realiza un XML con dos espacios de nombres.**

### XLM

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE muebles>
<muebles xmlns:mesas="https://www.mejorqueikea.com/espaciodenombre/mesas" xmlns:sillas="https://www.mejorqueikea.com/espaciodenombre/sillas">
    <mesas:mesa>
        <mesas:nombre>Mesa de comedor</mesas:nombre>
        <mesas:ancho>120</mesas:ancho>
        <mesas:alto>80</mesas:alto>
        <mesas:profundidad>120</mesas:profundidad>
        <mesas:material>Madera</mesas:material>
    </mesas:mesa>
    <sillas:silla>
        <sillas:nombre>Silla de cocina</sillas:nombre>
        <sillas:ancho>40</sillas:ancho>
        <sillas:alto>90</sillas:alto>
        <sillas:profundidad>40</sillas:profundidad>
        <sillas:material>Acero</sillas:material>
    </sillas:silla>
</muebles>
```

**[archivo en drive](https://drive.google.com/file/d/1i5hr8I7fX5JJ_-06G3jianTafFjmBCpe/view?usp=sharing)**

**12. Realiza un documento XML con DTD para la siguiente información: Empleado: Silvia Vázquez García**

### XLM

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE empleado SYSTEM "empleado.dtd">
<empleado>Silvia Vázquez García</empleado>
```

**[archivo en drive](https://drive.google.com/file/d/1LZTPacxgv-dweh5Q-3HCqIb8naPTHnnY/view?usp=sharing)**

**13. Realiza un documento XML y luego una DTD que nos sirva para validarlo. La información a almacenar es sobre un vehículo (marca, modelo, precio, numBastidor, matriculado). Debemos tener en cuenta que para indicar si está matriculado queremos utilizar una etiqueta vacía, el resto es todo texto.**

### XLM-dtd

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE vehiculos [
    <!ELEMENT vehiculos (vehiculo)>
    <!ELEMENT vehiculo (marca, modelo, precio, numBastidor, matriculado)>
    <!ELEMENT marca (#PCDATA)>
    <!ELEMENT modelo (#PCDATA)>
    <!ELEMENT precio (#PCDATA)>
    <!ELEMENT numBastidor (#PCDATA)>
    <!ELEMENT matriculado EMPTY>
]>
<vehiculos>
    <vehiculo>
        <marca>Audi</marca>
        <modelo>A4</modelo>
        <precio>30000</precio>
        <numBastidor>123456789</numBastidor>
        <matriculado/>
    </vehiculo>
</vehiculos>
```

**[archivo en drive](https://drive.google.com/file/d/1fG8WGZjfHCkzlM6SS3QpoiZ1uhi0h-5_/view?usp=sharing)**

**14. Realiza una DTD que sirva para que se cumpla la estructura básica de una web HTML:**

**<html>**

**<head>**

**<title>Título del HTML</title>**

**</head>**

**<body>**

**<br/>**

**<p>Esto es un párrafo</p>**

**</body>**

**</html>**

### XLM-dtd

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE html [
<!ELEMENT html (head, body)>
<!ELEMENT head (title)>
<!ELEMENT title (#PCDATA)>
<!ELEMENT body (br, p)>
<!ELEMENT br EMPTY>
<!ELEMENT p (#PCDATA)>
]>
<html>
    <head>
        <title>Título del HTML</title>
    </head>
    <body>
        <br/>
        <p>Esto es un párrafo</p>
    </body>
</html>
```

**[archivo en drive](https://drive.google.com/file/d/13ytukgHEjo_fJmH2VkndEs2gL1o9ZMBG/view?usp=sharing)**

**15. Realiza un documento XML cuyo DTD sirva para que se cumpla la estructura básica de un empleado.**

- **Nombre**
- **Apellidos**
- **Fecha de nacimiento**
- **Dia**
- **Mes**
- **Año**
- **Dirección**
- **Puesto**
- **Salario**

### XLM-dtd

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE empleados [
    <!ELEMENT empleados (empleado)>
    <!ELEMENT empleado (Nombre, Apellidos, FechaNacimiento, Direccion, Puesto, Salario)>
    <!ELEMENT Nombre (#PCDATA)>
    <!ELEMENT Apellidos (#PCDATA)>
    <!ELEMENT FechaNacimiento (Dia, Mes, Año)>
    <!ELEMENT Dia (#PCDATA)>
    <!ELEMENT Mes (#PCDATA)>
    <!ELEMENT Año (#PCDATA)>
    <!ELEMENT Direccion (#PCDATA)>
    <!ELEMENT Puesto (#PCDATA)>
    <!ELEMENT Salario (#PCDATA)>
]>
<empleados>
    <empleado>
        <Nombre>John</Nombre>
        <Apellidos>Doe</Apellidos>
        <FechaNacimiento>
            <Dia>05</Dia>
            <Mes>12</Mes>
            <Año>1990</Año>
        </FechaNacimiento>
        <Direccion>123 Calle Principal, Ciudad</Direccion>
        <Puesto>Gerente</Puesto>
        <Salario>50000</Salario>
    </empleado>
</empleados>
```

**[archivo en drive](https://drive.google.com/file/d/1LjusumxNM5cYEl70cFc6ERv6ltFNXo9z/view?usp=sharing)**

**16. Realiza una DTD a partir del XML siguiente. Ten en cuenta que el elemento producto tiene que aparecer una o más veces.**

### XLM

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE cesta SYSTEM "cesta.dtd">
<cesta>
    <producto>WD BLACK SN778 1TB SSD PCIe Gená NVMe</producto>
    <producto>Sony Playstation 5</producto>
    <producto>Xiaomi Pet Fountain</producto>
</cesta>
```

### DTD

```xml
<!ELEMENT cesta (producto+)>
<!ELEMENT producto (#PCDATA)>
```

**[archivo en drive](https://drive.google.com/file/d/1hsJKgSEBFHXsFaSZaUlyXnWxs5VKd422/view?usp=sharing)**

**17. Realiza una DTD a partir del XML siguiente. Ten en cuenta que el elemento “nombre” tiene que aparecer una única vez. Ahora bien, el elemento “ingrediente” puede aparecer cero o más veces.**

### XLM

```xml
<?xm1 version="1.0" encoding="UTF-8"?>
<!DOCTYPE receta_cocina SYSTEM "receta.dtd">
<receta_cocina>
    <nombre>Dip cementerio</nombre>
    <ingrediente>Frijoles cocidos</ingrediente>
    <ingrediente>Creme Fraiche o crema fresca</ingrediente>
    <ingrediente>Sazonador para quesadillas, burritos o tacos</ingrediente>
    <ingrediente>Salsa Tabasco unas gotas</ingrediente>
    <ingrediente>Aguacate maduro</ingrediente>
    <ingrediente>Tortillas de trigo</ingrediente>
    <ingrediente>Lechuga iceberg</ingrediente>
</receta_cocina>
```

### DTD

```xml
<!ELEMENT receta_cocina (nombre, ingrediente*)>
<!ELEMENT nombre (#PCDATA)>
<!ELEMENT ingrediente (#PCDATA)>
```

**[archivo en drive](https://drive.google.com/file/d/1dwVzGxYyvbdgJKRHwq8n-q-Kq6twRVJj/view?usp=sharing)**

**18. Tomando como referencia el XML del Ejercicio 13, realiza una DTD de manera que el elemento matriculado sea opcional, es decir, que pueda no aparecer.**

### XLM-dtd

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE vehiculos [
    <!ELEMENT vehiculos (vehiculo*)>
    <!ELEMENT vehiculo (marca, modelo, precio, numBastidor, matriculado?)>
    <!ELEMENT marca (#PCDATA)>
    <!ELEMENT modelo (#PCDATA)>
    <!ELEMENT precio (#PCDATA)>
    <!ELEMENT numBastidor (#PCDATA)>
    <!ELEMENT matriculado EMPTY>
]>
<vehiculos>
    <vehiculo>
        <marca>Audi</marca>
        <modelo>A4</modelo>
        <precio>30000</precio>
        <numBastidor>123456789</numBastidor>
        <matriculado/>
    </vehiculo>
</vehiculos>
```

**[archivo en drive](https://drive.google.com/file/d/1RTdnjOfos-iYLn3HyQSRL9NxNBcnlw_x/view?usp=sharing)**

**19. Realiza una DTD a partir del XML siguiente.**

**Ten en cuenta que el elemento “articulos” puede:**

- **Estar vacío.**
- **Contener un elemento “codigo”.**
- **Contener un elemento “id”.**
- **Contener un elemento “codigo” y un elemento “id”.**
- **Contener un elemento “codigo” y varios elementos “id”.**
- **Contener un elemento “id” y varios elementos “codigo”.**
- **Contener varios elementos “codigo” y varios elementos “id”.**

### XLM-dtd

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE articulos [
    <!ELEMENT articulos (codigo*, id*)>
    <!ELEMENT codigo (#PCDATA)>
    <!ELEMENT id (#PCDATA)>
    
]>
<articulos>
    <codigo>AF-32</codigo>
    <id>3891</id>
    <codigo>AF-50</codigo>
    <codigo>AF-89</codigo>
</articulos>
```

**[archivo en drive](https://drive.google.com/file/d/1WG6u0GjKaNgvqnXaelITCWwHRV-CkfYq/view?usp=sharing)**

**20. Crea una DTD externo correspondiente a la siguiente estructura de datos de un documento XML:**

### XLM

```xml
<?xm1 version="1.0" encoding="UTF-8"?>
<!DOCTYPE alumno SYSTEM "alumno.dtd">
<alumno edad="24">
    <nombre>Nobita</nombre>
    <apellido>Nobi</apellido>
    <direccion>Calle Setagaya</direccion>
</alumno>
```

### DTD

```xml
<!ELEMENT alumno (nombre, apellido, direccion)>
<!ATTLIST alumno edad CDATA #REQUIRED>
<!ELEMENT nombre (#PCDATA)>
<!ELEMENT apellido (#PCDATA)>
<!ELEMENT direccion (#PCDATA)>
```

**[archivo en drive](https://drive.google.com/file/d/1mpvA5CJ0X8GsdFSnNaJoVuOgPA2777bU/view?usp=sharing)**

**21. Crea un DTD correspondiente a la siguiente estructura de datos de un documento XML.**

**Ten en cuenta que también podemos tener deportistas de futbol, que los valores posibles del atributo pais son "ESP", "FRA", "ITA" y "ALE" y que su valor por defecto es "ESP".**

### XLM

```xml
<?xml version="1.0" encoding="UTF-1"?>
<!DOCTYPE deportistas SYSTEM "deportista.dtd">
<deportistas>
    <f1 pais="ALE">Sebastian Vettel</f1>
    <f1>Fernando Alonso</f1>
    <f1 pais="ESP">Carlos Sainz</f1>
    <tenis>Rafael Nadal</tenis>
</deportistas>
```

### DTD

```xml
<!ELEMENT deportistas (f1|futbol|tenis)*>
<!ELEMENT f1 (#PCDATA)>
<!ATTLIST f1
          pais (ESP | FRA | ITA | ALE) "ESP">
<!ELEMENT tenis (#PCDATA)>
<!ATTLIST tenis
          pais (ESP | FRA | ITA | ALE) "ESP">
<!ELEMENT futbol (#PCDATA)>
<!ATTLIST futbol
          pais (ESP | FRA | ITA | ALE) "ESP">
```

**[archivo en drive](https://drive.google.com/file/d/1ZrTR3dPY1hj7nq66XqwUUpHpYL0rGu0k/view?usp=sharing)**

**22. Modifica el anterior ejercicio para que los pilotos de F1 tengan un atributo  “código” identificativo.**

### XLM-dtd

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE deportistas [
    <!ELEMENT deportistas (f1*, tenis*)>
    <!ELEMENT f1 (#PCDATA)>
    <!ATTLIST f1 codigo CDATA #REQUIRED>
    <!ATTLIST f1 pais CDATA #IMPLIED>
    <!ELEMENT tenis (#PCDATA)>
]>
<deportistas>
    <f1 codigo="VET" pais="ALE">Sebatastian Vettel</f1>
    <f1 codigo="ALO">Fernando Alonso</f1>
    <f1 codigo="SAI" pais="ESP">Carlos Sainz</f1>
    <tenis>Rafael Nadal</tenis>
</deportistas>
```

**[archivo en drive](https://drive.google.com/file/d/16v7OMB4k1w8SVGVdMyRUMdORqcSvtfip/view?usp=sharing)**

**23. Crea un DTD correspondiente a la siguiente estructura de datos de un documento XML:**

**Ten en cuenta que los elementos “pelicula” que se escriban, deben incluir el atributo direccion, cuyo valor estará asignado a un atributo ID de otro elemento del documento. En este caso, el valor estará asignado a un atributo coddir de un elemento “director”**

### XLM-dtd

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE cine [
    <!ELEMENT cine (directores, peliculas)>
    <!ELEMENT directores (director+)>
    <!ELEMENT director (#PCDATA)>
    <!ATTLIST director coddir ID #REQUIRED>
    <!ELEMENT peliculas (pelicula+)>
    <!ELEMENT pelicula (#PCDATA)>
    <!ATTLIST pelicula direccion IDREF #REQUIRED>
]>
<cine>
    <directores>
        <director coddir="CE">Clint Eastwood</director>
        <director coddir="JC">James Cameron</director>
    </directores>
    <peliculas>
        <pelicula direccion="JC">avatar</pelicula>
        <pelicula direccion="CE">Mystic Rivers</pelicula>
        <pelicula direccion="JC">Titanic</pelicula>
    </peliculas>
</cine>
```

**[archivo en drive](https://drive.google.com/file/d/17e_yfWTE2bSkVAHKSgWLqdBCtA77si1L/view?usp=sharing)**

**24. Crea un DTD correspondiente a la siguiente estructura de datos de un documento XML:**

### XLM-dtd

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE usuarios [
    <!ELEMENT usuarios (usuario+)>
    <!ELEMENT usuario (#PCDATA)>
    <!ATTLIST usuario clave CDATA #REQUIRED>

]>
<usuarios>
    <usuario clave="123456789">Ana</usuario>
    <usuario clave="ab-c-d-fg">Iker</usuario>
    <usuario clave="A1_B2..C3">Elsa</usuario>
</usuarios>
```

**[archivo en drive](https://drive.google.com/file/d/12-XDuICFIlpBzUd96_VpfGTLzZHhtNxG/view?usp=sharing)**

**25. Crea un DTD correspondiente a la siguiente estructura de datos de un documento XML.**

**Ten en cuenta que los elementos “animal” que se escriban, deben incluir opcionalmente el atributo tipo_de_imagen, cuyo valor será una notación (gif, jpg o png). Además, son declaraciones de los siguientes tipos MIME (Multipurpose Internet Mail Extensions): image/gif, image/jpeg e image/png.**

### XLM-dtd

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE animales [
<!ELEMENT animales (animal+)>
<!ELEMENT animal (nombre)>
<!ATTLIST animal
          imagen CDATA #REQUIRED
          tipo_de_imagen (gif|jpg|png) >
<!ELEMENT nombre (#PCDATA)>
]>
<animales>
    <animal imagen="ballena-azul.gif" imagen="gif">
        <nombre>Ballena</nombre>
    </animal>
    <animal imagen="leon-dormido.png" tipo_de_imagen="png">
        <nombre>leon</nombre>
    </animal>
</animales>
```

**[archivo en drive](https://drive.google.com/file/d/1D4ZGSiwv8sIZOFYK4ADLaVMKcyDjc-TD/view?usp=sharing)**

**26. Crea un DTD correspondiente a la siguiente estructura de datos de un documento XML. Ten en cuenta:**

- **Que los valores (ballena, delfin, elefante, leon y oso) van a ser cargados desde una URI (Uniform Resource Identifier). En este caso, se hace referencia a los archivos externos “ballena.gif”, “delfin.gif”, “elefante.gif”, “leon.gif” y “oso.gif”.**
- **Con NDATA (Notation Data) se ha asociado a las entidades ballena, delfin, elefante, leon y oso con la notación gif.**
- **La notación gif es una declaración del tipo MIME image/gif.**

### XLM-dtd

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE animales [
<!ELEMENT animales (grupos+)>
<!ELEMENT grupos (#PCDATA)>
<!ATTLIST grupos
          imagenes CDATA #REQUIRED>
<!NOTATION gif SYSTEM "image/gif">
<!ENTITY % animales "ballena | delfin | elefante | leon | oso">
<!ENTITY % gif_ents
   "<!ENTITY ballena SYSTEM 'ballena.gif' NDATA gif>
    <!ENTITY delfin SYSTEM 'delfin.gif' NDATA gif>
    <!ENTITY elefante SYSTEM 'elefante.gif' NDATA gif>
    <!ENTITY leon SYSTEM 'leon.gif' NDATA gif>
    <!ENTITY oso SYSTEM 'oso.gif' NDATA gif>">
%gif_ents;

]>
<animales>
    <grupos imagenes="ballena"/>
    <grupos imagenes="ballena delfin"/>
    <grupos imagenes="elefante leon oso"/>
    <grupos imagenes="ballena elefeante"/>
</animales>
```

**[archivo en drive](https://drive.google.com/file/d/1S89z65NUkI2Mtb0txWbuak-_QZJOnjN-/view?usp=sharing)**

**27. Realiza un documento XML y un XSD para la siguiente información:**

**Alumno: Manuel García Fernández**

### XLM

```xml
<?xml version="1.0" encoding="UTF-8"?>
<Alumno>
  <Nombre>Manuel García Fernández</Nombre>
</Alumno>

```

### XSD

```xml
<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema">
  <xs:element name="Alumno">
    <xs:complexType>
      <xs:sequence>
        <xs:element name="Nombre" type="xs:string"/>
      </xs:sequence>
    </xs:complexType>
  </xs:element>
</xs:schema>
```

**[archivo.xml](https://drive.google.com/file/d/1K11XbVivI-Il0QgoErgHCDS6D1_VHqBq/view?usp=sharing) [archivo.xsd](https://drive.google.com/file/d/1PselX_bibtwDxM8Z0VC1h3ZapJMSdPGT/view?usp=sharing) en drive ambos archivos**

**28. Para los siguientes elementos:**

**<ciudad>Milán</ciudad>**

**<fecha-de-nacimiento>1999-12-18</fecha-de-nacimiento>**

**<hora>10:15:45</hora>**

**<nota>8.75</nota>**

**<apto>true</apto>**

**Escribir sus definiciones de elementos simples correspondientes.**

### XSD

```xml
<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema">
  <xs:element name="ciudad" type="xs:string"/>
  <xs:element name="fecha-de-nacimiento" type="xs:date"/>
  <xs:element name="hora" type="xs:time"/>
  <xs:element name="nota" type="xs:decimal"/>
  <xs:element name="apto" type="xs:boolean"/>
</xs:schema>
```

**[archivo en drive](https://drive.google.com/file/d/16k8skjmE47UbAemkfWVEKoUsaygtGEk9/view?usp=sharing)**

**29. Definir un elemento llamado ventanaCerrada de tipo lógico, que por defecto tenga el valor false, y otro elemento llamado puertaAbierta también de tipo lógico, que tenga asignado el valor fijo true.**

### XSD

```xml
<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema">
  <xs:element name="ventanaCerrada" type="xs:boolean" default="false"/>
  <xs:element name="puertaAbierta" type="xs:boolean" fixed="true"/>
</xs:schema>
```

**[archivo en drive](https://drive.google.com/file/d/1qEe_24tTmto5k5ZXTKoWFA0M4gW7_drD/view?usp=sharing)**

**30. Asocia el documento XML con su XSD, ambos realizados en el ejercicio anterior.**

### XLM

```xml
<?xml version="1.0" encoding="UTF-8"?>
<libro xmlns:xsi="http://www.w3.org/2001/XMlSchema-instance" xsi:noNamespaceSchemaLocation="ejemplo.xsd">
    <titulo>XML práctico</titulo>
    <autor>Sebastien lecomte</autor>
    <autor>Andrew Watt</autor>
    <editorial>Ediciones ENI</editorial>
</libro>
```

**[archivo en drive](https://drive.google.com/file/d/1gBch0UyPeWNlPbt8irVWih3fVGmh4jNh/view?usp=sharing)**

**31. Crea el esquema correspondiente al siguiente documento XML alumnos.xml para estructurar la información personal sobre los alumnos de un centro educativo:**

### XLM

```xml
<?xml version="1.0" encoding="UTF-8"?>

<alumnos xmlns:xsi="http://ww.w3.org/2001/XMLSchema-instance"
xsi:noNamespaceSchemaLocation="actividad31.xsd">
    <alumno>
        <nombre>Jose</nombre>
        <apellidos>García González</apellidos>
        <direccion>
            <domicilio>Velarde 12</domicilio>
            <codigo_postal>51001</codigo_postal>
            <localidad>Ceuta</localidad>
            <provincia>Ceuta</provincia>
        </direccion>
        <contactar>
            <telf_casa>956523165</telf_casa>
            <telf_movil>611233544</telf_movil>
            <telf_trabajo>956847536</telf_trabajo>
            <email>pepitoecifp.net</email>
        </contactar>
    </alumno>
    <alumno>
        <nombre>Aitana</nombre>
        <apellidos>Ramirez Aguirre</apellidos>
        <direccion>
            <domicilio>Plaza Sin nombre, 25</domicilio>
            <codigo_postal>51002</codigo_postal>
            <localidad>Benzú</localidad>
            <provincia>Ceuta</provincia>
        </direccion>
        <contactar>
            <telf_casa>956132565</telf_casa>
            <telf_movil>623863544</telf_movil>
            <telf_trabajo>956557536</telf_trabajo>
            <email>aitanaGcifp.net</email>
        </contactar>
    </alumno>
</alumnos>
```

### XSD

```xml
<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema">

  <xs:element name="alumnos">
    <xs:complexType>
      <xs:sequence>
        <xs:element name="alumno" maxOccurs="unbounded">
          <xs:complexType>
            <xs:sequence>
              <xs:element name="nombre" type="xs:string"/>
              <xs:element name="apellidos" type="xs:string"/>
              <xs:element name="direccion">
                <xs:complexType>
                  <xs:sequence>
                    <xs:element name="domicilio" type="xs:string"/>
                    <xs:element name="codigo_postal" type="xs:string"/>
                    <xs:element name="localidad" type="xs:string"/>
                    <xs:element name="provincia" type="xs:string"/>
                  </xs:sequence>
                </xs:complexType>
              </xs:element>
              <xs:element name="contactar">
                <xs:complexType>
                  <xs:sequence>
                    <xs:element name="telf_casa" type="xs:string"/>
                    <xs:element name="telf_movil" type="xs:string"/>
                    <xs:element name="telf_trabajo" type="xs:string"/>
                    <xs:element name="email" type="xs:string"/>
                  </xs:sequence>
                </xs:complexType>
              </xs:element>
            </xs:sequence>
          </xs:complexType>
        </xs:element>
      </xs:sequence>
    </xs:complexType>
  </xs:element>

</xs:schema>
```

**[archivo.xml](https://drive.google.com/file/d/1N1mlNzKx8MiGo1fcRt79NyaRfktekgv-/view?usp=sharing)   [archivo.xsd](https://drive.google.com/file/d/1ojMbsFxFoTLTKEVG1KeeJQiMVch_6nfa/view?usp=sharing) de drive**

**32. Dado el documento XML Ejemplo.xml, genera el correspondiente  documento XSD para validarlo con las siguientes condiciones:**

- **el elemento "nombre" debe admitir nombres compuestos que comienzan con mayúscula.**

### XLM

```xml
<?xml version="1.0" encoding="UTF-8"?>
<usuarios xmlns:xs="http://wwmw.w3.0rg/2001/XMLSchema-instance"
xs:noNamespaceSchemaLocation="actividad32.xsd">
<usuario>
<nombre>Peter Green</nombre>
<departamento>Finanzas</departamento>
<puntuación>5</puntuación>
<estado>conectado</estado>
</usuario>
</usuarios>
```

### XSD

```xml
<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema">
  <xs:element name="usuarios">
    <xs:complexType>
      <xs:sequence>
        <xs:element name="usuario" maxOccurs="unbounded">
          <xs:complexType>
            <xs:sequence>
              <xs:element name="nombre">
                <xs:simpleType>
                  <xs:restriction base="xs:string">
                    <xs:pattern value="[A-Z][a-z]+ [A-Z][a-z]+"/>
                  </xs:restriction>
                </xs:simpleType>
              </xs:element>
              <xs:element name="departamento" type="xs:string"/>
              <xs:element name="puntuación" type="xs:integer"/>
              <xs:element name="estado" type="xs:string"/>
            </xs:sequence>
          </xs:complexType>
        </xs:element>
      </xs:sequence>
    </xs:complexType>
  </xs:element>
</xs:schema>
```

**[archivo.xml](https://drive.google.com/file/d/1e6L5gomwmCkWisveDZpgcjihrqfzhu4r/view?usp=sharing)     [archivo.xsd](https://drive.google.com/file/d/1Ta0bkqYPVCA5DAbGhkvL3W4J1Hltb_g3/view?usp=sharing) en drive**

**33. Dado el documento XML Ejemplo.xml, genera el correspondiente documento XSD para validarlo con las siguientes condiciones:**

- **el elemento "puntuación" debe ser un número entero comprendido entre 1 y 10, ambos inclusive.**

### XLM

```xml
<?xml version="1.0" encoding="UTF-8"?>
<usuarios xmlns:xs="http://wwmw.w3.0rg/2001/XMLSchema-instance"
xs:noNamespaceSchemaLocation="actividad33.xsd">
<usuario>
<nombre>Peter Green</nombre>
<departamento>Finanzas</departamento>
<puntuación>5</puntuación>
<estado>conectado</estado>
</usuario>
</usuarios>
```

### XSD

```xml
<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema">
  <xs:element name="usuarios">
    <xs:complexType>
      <xs:sequence>
        <xs:element name="usuario" maxOccurs="unbounded">
          <xs:complexType>
            <xs:sequence>
              <xs:element name="nombre" type="xs:string"/>
              <xs:element name="departamento" type="xs:string"/>
              <xs:element name="puntuación">
                <xs:simpleType>
                  <xs:restriction base="xs:integer">
                    <xs:minInclusive value="1"/>
                    <xs:maxInclusive value="10"/>
                  </xs:restriction>
                </xs:simpleType>
              </xs:element>
              <xs:element name="estado" type="xs:string"/>
            </xs:sequence>
          </xs:complexType>
        </xs:element>
      </xs:sequence>
    </xs:complexType>
  </xs:element>
</xs:schema>
```

**[archivo.xml](https://drive.google.com/file/d/1DuzNUX95hLlmn0s6bqHxeGMvbfcQjP3m/view?usp=sharing)   [archivo.xsd](https://drive.google.com/file/d/1yqzpeR7gOoiOQg3WrwWT992rMtEfrCR6/view?usp=sharing) en drive**

**34. Dado el documento XML siguiente, genera el correspondiente documento XSD para validarlo:**

### XLM

```xml
<?xml version="1.0" encoding="UTF-8"?>
<fichas xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
xsi:noNamespaceSchemaLocation="actividad34.xsd">
    <ficha numero="1">
        <nombre>Abdeselam Mohamed Lachiri</nombre>
        <edad>22</edad>
    </ficha>
    <ficha numero="2">
        <nombre>ILdefonse Rubio Molineiro</nombre>
        <edad>23</edad>
    </ficha>
</fichas>
```

### XSD

```xml
<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema">
  <xs:element name="fichas">
    <xs:complexType>
      <xs:sequence>
        <xs:element name="ficha" maxOccurs="unbounded">
          <xs:complexType>
            <xs:sequence>
              <xs:element name="nombre" type="xs:string"/>
              <xs:element name="edad" type="xs:integer"/>
            </xs:sequence>
            <xs:attribute name="numero" type="xs:integer" use="required"/>
          </xs:complexType>
        </xs:element>
      </xs:sequence>
    </xs:complexType>
  </xs:element>
</xs:schema>
```

**[archivo.xml](https://drive.google.com/file/d/1hPdnzPJ84IRqqQAosDY5Ze41yKk79CJ2/view?usp=sharing)    [archivo.xsd](https://drive.google.com/file/d/1WS-cm3T04E6Er9s4f-rJPm4yt8VT83dk/view?usp=sharing)  en drive**

**35. Dado el documento XML Ejemplo.xml, genera el correspondiente documento XSD con la documentación del esquema realizado.**

### XLM

```xml
<?xml version="1.0" encoding="UTF-8"?>
<usuarios xmlns:xs="http://wwmw.w3.0rg/2001/XMLSchema-instance"
xs:noNamespaceSchemaLocation="actividad35.xsd">
<usuario>
<nombre>Peter Green</nombre>
<departamento>Finanzas</departamento>
<puntuación>5</puntuación>
<estado>conectado</estado>
</usuario>
</usuarios>
```

### XSD

```xml
<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema"
    targetNamespace="http://example.com"
    xmlns="http://example.com">
    <xs:element name="usuarios">
        <xs:complexType>
            <xs:sequence>
                <xs:element name="usuario" maxOccurs="unbounded">
                    <xs:complexType>
                        <xs:sequence>
                            <xs:element name="nombre" type="xs:string">
                                <xs:annotation>
                                    <xs:documentation>Nombre del usuario.</xs:documentation>
                                </xs:annotation>
                            </xs:element>
                            <xs:element name="departamento" type="xs:string">
                                <xs:annotation>
                                    <xs:documentation>Departamento al que pertenece el usuario.</xs:documentation>
                                </xs:annotation>
                            </xs:element>
                            <xs:element name="puntuación">
                                <xs:simpleType>
                                    <xs:restriction base="xs:integer">
                                        <xs:minInclusive value="1"/>
                                        <xs:maxInclusive value="10"/>
                                    </xs:restriction>
                                </xs:simpleType>
                                <xs:annotation>
                                    <xs:documentation>Puntuación del usuario, debe estar entre 1 y 10.</xs:documentation>
                                </xs:annotation>
                            </xs:element>
                            <xs:element name="estado" type="xs:string">
                                <xs:annotation>
                                    <xs:documentation>Estado del usuario (por ejemplo, conectado o desconectado).</xs:documentation>
                                </xs:annotation>
                            </xs:element>
                        </xs:sequence>
                    </xs:complexType>
                </xs:element>
            </xs:sequence>
        </xs:complexType>
    </xs:element>
</xs:schema>
```

**[archivo.xml](https://drive.google.com/file/d/1UJ47t3TQCBBcdA8ZDmSEKtsXY-sNtwBQ/view?usp=sharing)     [archivo.xsd](https://drive.google.com/file/d/1pkNjJL-CXmLShVhaOkuvtMSmrYKwLZe0/view?usp=sharing)   en drive**