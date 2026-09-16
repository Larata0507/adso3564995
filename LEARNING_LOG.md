# Mi bitácora de aprendizaje

Registro de temas y notas de lo que voy aprendiendo.

## Git

- Control de versiones: guardar el historial de cambios de un proyecto _(2026-09-09)_
- Repositorio en GitHub conectado a mi proyecto local _(2026-09-09)_

## Emmet

- Abreviaciones para escribir estructura HTML/CSS más rápido (workflow de marcado) _(2026-09-09)_
- Carpeta `01-emmet` en mi repo, archivo `index.html` con 17 ejercicios prácticos _(2026-09-10)_
- **01 - Child (`>`)**: crea elementos hijos, es decir anidados uno dentro de otro (`ul>li>a`) _(2026-09-10)_
- **02 - Sibling (`+`)**: crea elementos hermanos, uno al lado del otro al mismo nivel (`header+section+footer`) _(2026-09-10)_
- **03 - Multiplication (`*`)**: repite un mismo elemento varias veces (`ul>li*3` genera 3 `<li>`) _(2026-09-10)_
- **04 - Class (`.`)**: agrega un atributo `class` al elemento (`div.contenedor`) _(2026-09-10)_
- **05 - Classes (`.clase1.clase2`)**: agrega varias clases al mismo elemento de una vez _(2026-09-10)_
- **06 - Id (`#`)**: agrega un atributo `id` (`nav#menu`) _(2026-09-10)_
- **07 - Text (`{}`)**: inserta texto dentro del elemento (`div{Lorem Ipsum}`) _(2026-09-10)_
- **08 - Custom Attributes (`[]`)**: agrega atributos personalizados como `href` o `src` (`a[href=...]`) _(2026-09-10)_
- **09 - Item Numbering (`$`)**: numera automáticamente elementos repetidos en secuencia (`li.num$*3` → num1, num2, num3) _(2026-09-10)_
- **10 - Reverse Numbering (`@-`)**: invierte el orden de la numeración automática _(2026-09-10)_
- **11 - Base Numbering (`@n`)**: define desde qué número empieza la secuencia _(2026-09-10)_
- **12 - Climb Up (`^`)**: sube un nivel en la jerarquía antes de seguir agregando elementos _(2026-09-10)_
- **13 - Grouping (`()`)**: agrupa varios elementos para aplicarles una acción en conjunto, como multiplicarlos o anidarlos juntos _(2026-09-10)_
- **14 - Lorem**: genera texto de relleno tipo "lorem ipsum" automáticamente, con control de cantidad de palabras (`lorem20`) o repeticiones (`lorem*5`) _(2026-09-10)_
- **15 - HTML Documents (`!`)**: genera la estructura base de un documento HTML completo (doctype, head, body) según distintas versiones/tipos de HTML _(2026-09-10)_
- **16 - Meta Tags**: genera etiquetas `<meta>` predefinidas, como la de viewport (`meta:vp`) _(2026-09-10)_
- **17 - Challenge**: ejercicio final que combina todo lo anterior en un caso real — arma un navbar completo (header, nav, botón hamburguesa, logo, links) usando anidación, agrupación, clases, atributos y texto en una sola línea de Emmet _(2026-09-10)_

padre*hijos*hermanos*abuelo*bisabuelos

section+header+nav

ul>li*10

ul>li>a

section+header+nav

ul>li*3

div.contenedor

.contenedor2

div.clase1.clase2.clasen

nav#menu

div{Lorem Ipsum Dolor}

a{Click Aquí}

a[href=www.google.com]

ul>li.num$*3

section>article.sec$$$*3

ul>li.num$@-*3

ul>li.num$@3*4

section>article>div^p

(header>nav)+(section>article)

Lorem

lorem20

lorem*5

html:xs —— Documento xhtml 1.0 Strict

html:xt —— Documento xhtml 1.0 Transitional

html:4s —— Documento html 4.01 Strict

html:4t —— Documento html 4.01 Transitional

html:5 —— Documento html 5

html:5 —— Documento html 5

!

header>nav+div.hero^(main>article*2)+footer
--------------------------------------------------
.card>(div.card-img>img[src="thumb.jpg"])+.card-body>(h3{Título}+p{Texto})+div.card-footer>(a.btn[href="#"]{Leer más})
-----------------------------------------------------------------
nav>ul>(li>a{Inicio})+(li>a{Servicios})+(li>a{Contacto})
---------------------------------------------------------
header#header>nav.navbar.navbar-inverse>div.container>(div.navbar-header>(button[type="button"].navbar-toggle>span.sr-only{Toggle navigation}+span.icon-bar+span.icon-bar+span.icon-bar)>a.navbar-brand[href="index.php"]>img[src="imgs/logo.png" alt=""])>div.collapse>ul.nav.navbar-nav>(li>a.link[href="index.html"]{Inicio})>(li.active.link>a[href="login.html"]{Ingresar})>(li>a.link[href="registro.html"]{Registrarse})>i>a.link[href="contacto.html"]{contacto}
-----------------------------------------------------
div.cards>(article.card[img=""]+h3{tarjeta-1})+(article.card[img=""]+h3{tarjeta-2})+(article.card[img=""]+h3{tarjeta-3})
----------------------------------------------------
div.cards>article.card*3>img+h3{Tarjeta $}
----------------------------------------------------------------------
div.cards>(article.card>img+h3{Tarjeta $})*3
--------------------------------------------------------
nav.navbar>div.container-fluid>a[href="index.html"].navbar-brand{Mi sitio}+ul.nav-list>li>a[href="#"]*3.item-$
----------------------------------------------------
nav.navbar>div.container-fluid>a[href="index.html"].navbar-brand{Mi Sitio}+ul.nav-list>(li>a[href="#"].item-1{Inicio})+(li>a[href="#"].item-2{Servicios})+(li>a[href="#"].item-3{Contacto})
--------------------------------------
.post>h2{Articulo 1}+p>lorem
-----------------------------------------
table>thead>th{Id}+th{Nombre}+th{Accion}
-----------------------------------
section.blog>.container>h2{Ultimas Noticias}+.grid>(article>img[src="img-1.jpg" alt=""]+div.content>h3{Post 1}+p>lorem5)*2
--------------------------------------------------
section.blog>.container>h2{Últimas Noticias}+.grid>(article.post-card>img[src="img-$.jpg" alt=""]+div.content>h3{Post $}+p>lorem5)*2



## HTML

- Estructura de una página con HyperText Markup Language _(2026-09-09)_
- Carpeta `02-html` en mi repo con los ejercicios _(2026-09-09)_


## CSS

- Cascading Style Sheets: cómo darle look & feel a la estructura HTML _(2026-09-09)_
- Carpeta `03-css` en mi repo _(2026-09-09)_

## Javascript

- Lenguaje para darle comportamiento/interactividad a la página _(2026-09-09)_
- Carpeta `04-javascript` en mi repo _(2026-09-09)_
