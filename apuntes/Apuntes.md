# Curso Desarrollo web (Apuntes)    
![Logo HTML](imgsApunte/logoHTML.png)
![Logo css](imgsApunte/logoCSS.png)

## _Clase 1_

* **Textos**
    
```html
Texto predeterminado
<br> <!--Enter-->
<hr><!--linea separadora-->
<b>Texto en negrita</b>
<br>
<i>Texto en cursiva</i>
<u>texto Subrayado</u> <!-- no usar se confunde con los links -->
<p><!--Parrafos-->
    <b>Clase 1:</b> vimos como poner el texto en negrita, cursiva como crear parrafo, y salto de linea <br> <i>recreo a la mitad de la Clase</i>

</p>
```
---
* **Listas**

```html
<ul><!-- lista con items -->
    <li>HTML</li>
    <li>CSS</li>
    <LI>JAVASCRIPT</LI>
</ul>

<OL><!-- lista ordenada -->
    <LI>html</LI>
    <LI>CSS</LI>
    <LI>JAVASCRIPT</LI>
</OL>

<ol type="I"><!--anidamiento-->
    <li><b>frontend</b>
        <ul>    
            <LI>html</LI>
            <LI>CSS</LI>
            <LI>JAVASCRIPT</LI>
        </ul>
    </li>
    <li><b>Backend</b>
        <ul>
            <li>SQL</li>
            <li>PHP</li>
        </ul>
    </li>
</ol>
```
---
## Clase 2

* **Enlaces**
```html
<!-- para insertar enlances en html  usamos el elemento "a" -->


<a href="https://www.instagram.com/sweetwaterrrc?utm_source=ig_web_button_share_sheet&igsh=OGQ5ZDc2ODk2ZA==" target="_blank">SweetWater</a>   
<a href="https://aeropostale.com.ar/" target="_blank">aeropostale</a>

<!-- href "va en el enlace"
>< va el nombre que le ponemos al enlace
target="_blank es para que abra el sitio en otra pestaña" -->
<!-- <a href="url">text</a> -->

```
---
* **Enunciados**

```html
<!DOCTYPE html> <!-- declaracion del html -->
<html lang="es">
<head> <!-- elementos no visuales -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Titulo de la pagina</title>
    <link rel="shortcut icon" href="imgs/317755_badge_html_html5_achievement_award_icon (1).png" type="image/x-icon">
    <!--  <link rel="shortcut icon" href="imagen" type="image/x-icon"> -->
    <link rel="stylesheet" href="css/Estilos.css">
</head>
<body> <!-- contenido de la paguina imagenes, videos, parrafos todo-->
</body>

```
---
* **imagenes**
```Html
<p>
    para insertar imagenes el elemento "img"
</p>

<!-- 
    sitios para descargar imagenes
    *iconografia
        flaticon: https://www.flaticon.com/
        iconfinder: https://www.iconfinder.com/
    *fotografias 
        unsplash: https://unsplash.com/es
        pexels: https://www.pexels.com/es-es/
        pngwing: https://pngwing.com/es


 -->
 <img style="text-align: center;" src="imgs/water.png" alt="Agua en Botella">

 <!-- ->src: es para poner la ruta de la imagen
    alt:el texto alternativo x si no carga la imagen
    <img src="ruta de imagen" alt="descripcion de imagen">
-->

<!-- se puede cambiar formas de imagenes en el codigo, pero no es recomendable x el peso de la imagen -->

```
---
* **Tipografias y colores**

Dentro del head se menciona el archivo css con estilos para editar la paguina, se usa el link rel y dentro del href va la ruta del archivo css
```
<link rel="stylesheet" href="css/Estilos.css">

```
---
### Archivo Css
```css
body{
background-color: rgb(22, 144, 226);
color: darkblue;
font-family: sans-serif;
font-size: 24px;
}
/*tipografias seguras: https://blog.hubspot.com/website/web-safe-html-css-fonts*/
h1{
    color: blueviolet;
}
```

## Clase 3
### Elementos semanticos
```html 
<strong>sirve para resaltar tmb en negrita, pero tiene relevancia</strong><!--tiene importancia semantica-->
<em>es para el enfasis (en cursiva)</em>

```

### GoogleFonts
```Css
@import url('https://fonts.googleapis.com/css2? family= IBM+Plex+Sans:ital,wght@0,600;1,200;1,400 & display=swap');
body{
    font-family: 'IBM Plex Sans', sans-serif;;/*tipografia*/
    background-color: darkblue; /*color de fondo*/
    color: cadetblue;/*color de la letra*/
    font-family: 400;/* espesor de la tipografia*/
    
}

h1{
    font-weight: 600;
}
```

### Maquetado

 * MAQUETADO SEMANTICO
    * HEADER -> ARRIBA CON LA MARCA LOGO 
            * NAV -> BARRA DE NAVEGACION
    <main></main> MENU PRINCIPAL
            <section></section> CORTES DE INFO
                <article></article>
    <footer></footer> estructuras

hosting o alojamiento (de archivos)
        - gratis
            https://www.000webhost.com/
            https://www.infinityfree.com/
            https://vercel.com/


        - pagos
            https://nuthost.com/
            https://latincloud.com/
            https://www.hostinger.com/