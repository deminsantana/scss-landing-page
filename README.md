# Estructura del Proyecto Web: Impacta! Front-end

## Descripción General

Este proyecto consiste en una página web creada para [describir el propósito de la web]. Se ha desarrollado utilizando HTML, SCSS y JavaScript, sin hacer uso de frameworks como Bootstrap o Tailwind.

## Estructura de Archivos

Impacta! Front-end/
├── index.html            # Main HTML file
├── assets/               # All static assets
│   ├── css/              # SCSS files compiled into CSS
│   │   ├── main.scss     # Main SCSS file
│   │   └── _variables.scss # SCSS variables
│   ├── js/               # JavaScript files
│   │   ├── main.js       # Main JavaScript file
│   │   └── swiper-bundle.min.js # Swiper library
│   ├── img/              # Images
│   │   ├── logo.png
│   │   ├── hero-image.jpg
│   │   └── ...          # Other images
│   └── icons/            # SVG or icon files
│        └── ...
├── documentation/       # Documentation files
│   └── project_structure.md # Project documentation
└── swiper-bundle.min.css # Swiper CSS. Download from swiperjs.com

El proyecto está organizado en las siguientes carpetas y archivos:

*   `index.html`: Archivo principal de la página web.
*   `assets/`: Carpeta que contiene todos los recursos estáticos.
    *   `css/`: Archivos SCSS, compilados a CSS.
        *   `main.scss`: Archivo principal de estilos.
        *   `_variables.scss`: Definición de variables SCSS (colores, tipografía, etc.).
    *   `js/`: Archivos JavaScript.
        *   `main.js`: Script principal con la lógica de la página.
        *   `swiper-bundle.min.js`: Librería Swiper para el carrusel de imágenes.
    *   `img/`: Imágenes del sitio web.
        *   `logo.png`: Logo de la empresa.
        *   `hero-image.jpg`: Imagen principal de la sección hero.
        *   `carousel-1.jpg`: Imagen del carrusel.
        *   ...
    * `icons`: Carpeta para los íconos.
        * `logos`: Logos de marcas.
*   `documentation/`: Carpeta para la documentación del proyecto.
    *   `project_structure.md`: Este archivo, con la descripción del proyecto y su estructura.
* `swiper-bundle.min.css`: Archivo CSS de Swiper, para los estilos del carousel.

## Decisiones de Diseño

*   **Esquema de Colores:**
    * Azul (#001c3a): Color principal utilizado en el fondo de la sección hero y en detalles.
    * Rojo (#e2001a): Color secundario usado en botones y detalles.
    * Negro (#000): Para el texto principal.
    * Blanco (#fff): Para el texto dentro de elementos de color azul o rojo.
*   **Tipografía:**
    *   Outfit: Tipografía principal utilizada en todo el sitio web. Se han utilizado los pesos 400 y 700.
*   **Distribución (Layout):**
    *   Se ha utilizado una estructura de grilla (grid) para la sección hero.
    *   El menú de navegación está alineado de forma flexible (flexbox).
    *   El carrusel de imágenes se ha implementado con Swiper.
*   **Diseño Responsivo:**
    *   Se han implementado media queries para adaptar el diseño a diferentes tamaños de pantalla, especialmente en la sección hero, en el menú de navegación, y en el texto en general.
* **Animaciones:**
    * Se han añadido transiciones en los botones.
    * Se ha incluido AOS (comentado) para su posible uso.

## Tecnologías

*   HTML5
*   SCSS
*   JavaScript
*   Swiper (librería para el carrusel)
*   AOS (librería para las animaciones)

## Librerías

* Swiper: Está descargada desde https://swiperjs.com/get-started. Su uso se implementa mediante la inclusión del CSS y el JS, además de la función en el JS principal.
* AOS: Está descargada desde https://michalsnik.github.io/aos/. Su uso se implementa mediante la inclusión del CSS y el JS, además de la función en el JS principal y la inclusión de las propiedades data-aos en los elementos del HTML.

## Contacto

*   github.com/deminsantana
*   linkedin.com/in/deminsantana
