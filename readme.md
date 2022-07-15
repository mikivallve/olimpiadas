# Olimpíadas

## Instroducción

El comité olímpico quiere refritar una web que se realizó hace algunos años para presentar novedades sobre Paris 2024.

Para eso, hay que realizar una serie de actualizaciones.

#

## Levantar el sitio viejo - 5pts

A partir de Olimpiadas.zip en esta repo, levantar el sitio en dónde vamos a trabajar.

#

## Bootstrap CDN por Bootstrap SASS - 10pts

En la línea 7 de `style.css` podemos ver como bootstrap está incluído utilizando el CDN. A su vez, vemos como todo el css está en ese archivo.

Crear una carpeta `scss` y generar archivos parciales que al correr el comando "npm run sass" actualice automaticamente el contenido de `style.css` con los archivos parciales de bootstrap y al menos 2 archivos parciales propios del proyecto: `_comentario_inicial.scss` y `_ajustes_generales.scss`

#

## Categoría de noticias para Paris 2024 - 10pts

Crear una categoría para Paris 2024. Replicar la misma lógica que se utilizó para Tokio 2020 y Beijing 2022.

La página deberá ser `http://olimpiadas.local/category/paris-2024/` y deberá tener un cabezal similar al de las otras categorías utilizando smartslider. Se recomienda duplicar el slider de Beijing para no partir de cero.

Agregar París al Menu, al footer y en el header principal de la home (ver `Smart-Slider- referencia.png`);

Se pueden tomar imágenes del [sitio oficial](https://olympics.com/en/olympic-games/paris-2024)

#

## Novedades de París - 5pts

Crear al menos 5 posts con contenido del [sitio oficial](https://olympics.com/en/olympic-games/paris-2024)

#

## Home - 10pts

Agregar bloques de Gutenberg con contenido dinámico sobre París, Tokio y Beijing.

Agregar un lazy block para que el usuario pueda agregar un componente "alert" de Bootstrap. El usuario podrá elegir

-   Color del alert: primary, secondary, success, danger
-   Texto del alert

#

## Cambiar las columnas - 5pts

En las páginas de categorías, cambiar de 3 a 4 columnas y ajustar el tamaño de los títulos para que no sean tan grandes.

Ver `Ejemplo 4 columnas para Tokyo-2020-–-Olimpiadas.png`

#

## Ajustes de variables - 5pts

El color oficial (primario) de Paris 2024 es `rgb(215, 195, 120);` y el color secundario es `#c91e1e`. Además queremos hacer algunos cambio en la tipografía.

```scss
$primary: rgb(215, 195, 120);
$secondary: #c91e1e;
$font-family-size-base: 16rem;
$font-family-base: 'Arial';
$headings-font-family: 'Times New Roman';
```

#

## Historia - 5pts

Agregar Tokyo y Beijing a la línea de tiempo en la página de la historia de los juegos olímpicos

#

## Footer - 5pts

-   Eliminar la sección de "Lo más reciente" del footer.
-   Agregar los links correctos a las redes sociales
-   Separar el logo de las redes sociales
-   Reemplazar> Parcial 2022 - Nombre Alumno - #estudiante por sus datos

#

## Contacto - 5pts

-   Cambiar la img de Tokio por una de Paris
-   Agregar `no binario` y `prefiero no decir` como opción del formulario
