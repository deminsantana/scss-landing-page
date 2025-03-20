# 🚀 Estructura del Proyecto Web: Impacta! Front-end

## 📝 Descripción General

Este proyecto consiste en una página web creada para [describir el propósito de la web]. Se ha desarrollado utilizando HTML, SCSS y JavaScript, sin hacer uso de frameworks como Bootstrap o Tailwind.

## 📂 Estructura de Archivos

```plaintext
Impacta! Front-end/
├── index.html            # Archivo HTML principal
├── assets/               # Recursos estáticos
│   ├── css/              # Archivos SCSS compilados a CSS
│   │   ├── main.scss     # Archivo principal de estilos
│   │   └── _variables.scss # Variables SCSS
│   ├── js/               # Archivos JavaScript
│   │   ├── main.js       # Script principal
│   │   └── swiper-bundle.min.js # Librería Swiper
│   ├── img/              # Imágenes
│   │   ├── logo.png
│   │   ├── hero-image.jpg
│   │   └── ...          # Otras imágenes
│   └── icons/            # Archivos SVG o íconos
│        └── ...
├── documentation/        # Archivos de documentación
│   └── project_structure.md # Documentación del proyecto
└── swiper-bundle.min.css # CSS de Swiper
```

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

## 🎨 Decisiones de Diseño

*   **🎭 Esquema de Colores:**
    * **Azul** (`#001c3a`): Color principal utilizado en el fondo de la sección hero y en detalles.
    * **Rojo** (`#e2001a`): Color secundario usado en botones y detalles.
    * **Negro** (`#000`): Para el texto principal.
    * **Blanco** (`#fff`): Para el texto dentro de elementos de color azul o rojo.
*   **🔤 Tipografía:**
    *   **Outfit**: Tipografía principal utilizada en todo el sitio web. Se han utilizado los pesos 400 y 700.
*   **📐 Distribución (Layout):**
    *   Se ha utilizado una estructura de grilla (grid) para la sección hero.
    *   El menú de navegación está alineado de forma flexible (flexbox).
    *   El carrusel de imágenes se ha implementado con Swiper.
*   **📱 Diseño Responsivo:**
    *   Se han implementado media queries para adaptar el diseño a diferentes tamaños de pantalla, especialmente en la sección hero, en el menú de navegación, y en el texto en general.
* **✨ Animaciones:**
    * Se han añadido transiciones en los botones.
    * Se ha incluido AOS (comentado) para su posible uso.

## 💻 Tecnologías

| Tecnología | Descripción |
|------------|-------------|
| HTML5      | Estructura del sitio |
| SCSS       | Estilos pre-procesados |
| JavaScript | Funcionalidad e interacciones |
| Swiper     | Librería para carruseles |
| AOS        | Librería para animaciones |

## 📚 Librerías

* **Swiper**: Descargada desde [swiperjs.com](https://swiperjs.com/get-started). Su uso se implementa mediante la inclusión del CSS y el JS, además de la función en el JS principal.
* **AOS**: Descargada desde [michalsnik.github.io/aos](https://michalsnik.github.io/aos/). Su uso se implementa mediante la inclusión del CSS y el JS, además de la función en el JS principal y la inclusión de las propiedades data-aos en los elementos del HTML.

## 🚀 Cómo Empezar

1. Clona este repositorio
2. Abre `index.html` en tu navegador para ver el proyecto
3. Para editar los estilos, trabaja con los archivos SCSS en la carpeta `assets/css/`

## 📞 Contacto

* GitHub: [github.com/deminsantana](https://github.com/deminsantana)
* LinkedIn: [linkedin.com/in/deminsantana](https://linkedin.com/in/deminsantana)
