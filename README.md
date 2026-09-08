# Arquitectura por el mundo

## Datos del estudiante

**Nombre y apellido:** Homero Gonzalez

## Tema elegido

Fotografías de arquitectura y lugares icónicos del mundo.

## Descripción de la propuesta

La propuesta consiste en crear una galería visual con fotografías que saqué durante mis viajes. Se mostrarán edificios, monumentos y lugares conocidos de diferentes partes del mundo.

## Objetivo de la galería

El objetivo es compartir los lugares que conocí y mostrar diferentes estilos de arquitectura por medio de mis propias fotografías.

## Contenidos

La galería incluye fotografías acompañadas por títulos y descripciones breves. Las imágenes están organizadas en las siguientes categorías:

- Edificios
- Monumentos
- Lugares icónicos
- Ciudades visitadas

## Organización de la galería

Las fotografías están organizadas por países para proponer un recorrido de viaje. La página principal permite elegir entre Argentina, España, Estados Unidos, Francia, Italia, Reino Unido y Vaticano. Cada destino tiene su propia página con fotografías, títulos y descripciones.

## Decisiones de diseño

### Colores

Se eligió un **gris pastel** (`#e4e5e1`) como fondo común porque es neutro, suave y permite que los colores de las fotografías sean los protagonistas. Las tarjetas utilizan tonos claros, mientras que los textos se presentan en un gris casi negro para mantener una buena lectura.

La página principal utiliza un **azul claro** (`#45a6d5`) en alusion al cielo en textos y detalles destacados. Cada país incorpora además un color de propio, inspirado en su identidad, para diferenciar las secciones sin perder el estilo general del sitio.

### Tipografías

Se utiliza **Georgia** en títulos por su aspecto editorial y su relación con las publicaciones de viajes, arquitectura y fotografía. Para los textos y la navegación se utiliza **Arial**, que aporta claridad y facilita la lectura en distintos tamaños de pantalla.

### Recursos visuales

El diseño se mantiene simple. Las fotografías son el elemento visual principal y se muestran dentro de galerías organizadas con CSS Grid.

El encabezado incluye un enlace de **Inicio** acompañado por un icono de casa de [Bootstrap Icons](https://icons.getbootstrap.com/). El pie de página conserva el nombre de la galería y un enlace para volver arriba.

En las tarjetas de la página principal elegí usar emojis de banderas dentro de círculos para identificar rápidamente cada país. Son parte de la propuesta visual y acompañan el nombre escrito de cada destino. Las banderas son caracteres Unicode, su apariencia puede variar según el dispositivo o el sistema operativo.

### Diseño responsive

El sitio utiliza Flexbox, CSS Grid, unidades relativas y media queries para adaptar los contenidos a distintos tamaños de pantalla. Realicé una revisión visual de la página y comprobé que el diseño se adapta correctamente.

## Tecnologías utilizadas

- HTML5 para la estructura y el contenido.
- CSS3 para colores, tipografías, grillas y adaptación a distintos tamaños de pantalla.
- Bootstrap Icons para el icono de inicio.

## Recorrido de la galería

Elegí una navegación que propone recorrer los destinos de forma secuencial, como las etapas de un viaje. Desde la página principal se puede elegir cualquier país y, al finalizar sus fotografías, los enlaces inferiores permiten pasar al destino anterior o al siguiente. El recorrido conecta Argentina, España, Estados Unidos, Francia, Italia, Reino Unido y Vaticano, y vuelve a comenzar en Argentina.

El encabezado mantiene los accesos a Inicio, La propuesta y Destinos. El enlace a Todos los destinos permite volver al listado y elegir otro país en cualquier momento. La decisión de concentrar la selección de países en la página principal busca mantener un encabezado simple y dar protagonismo a las fotografías, mientras que la navegación inferior invita a continuar el recorrido.

## Estructura del proyecto

```text
index.html
argentina.html
espana.html
estados-unidos.html
francia.html
italia.html
reino-unido.html
vaticano.html
css/
└── style.css
imagenes/
└── fotografías de la galería
```
