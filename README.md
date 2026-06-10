# GSL Congresos - Organización de Eventos Empresariales

¡Bienvenido/a al repositorio de **GSL Congresos**! Este sitio web fue desarrollado como proyecto para el curso de Desarrollo Web, enfocado en crear una plataforma moderna, intuitiva y completamente responsive para una empresa dedicada a la planificación y logística de eventos corporativos, jornadas y congresos.

## Demo En Vivo
Puedes ver el sitio web desplegado en producción aquí:
**[gsl-congresos.vercel.app](https://gsl-congresos.vercel.app)** *(o tu enlace de GitHub Pages)*

---

## Tecnologías Utilizadas

El proyecto fue construido utilizando las siguientes herramientas y tecnologías de desarrollo frontend:

* **HTML5:** Estructura semántica global del sitio.
* **CSS3 & Flexbox / Grid:** Maquetación a medida, grillas simétricas para la galería y alineación precisa.
* **SASS (Syntactically Awesome Style Sheets):** Arquitectura avanzada de estilos organizada por módulos (Layout, Components, Utilities, Base) y manejo de variables.
* **Bootstrap:** Implementación de componentes ágiles como la barra de navegación responsive (Navbar), carruseles y ventanas flotantes (Modales) para la visualización de imágenes.
* **Git & GitHub:** Control de versiones y despliegue del proyecto.

---

## Características Principales

* **Diseño 100% Responsive:** Optimizado con Media Queries específicas para garantizar una experiencia visual perfecta en computadoras, tablets y teléfonos celulares.
* **Galería con Efecto Lightbox:** Grilla moderna construida con CSS Grid que permite expandir las imágenes en un modal interactivo de Bootstrap al hacer clic.
* **Sección de Servicios Dinámica:** Tarjetas adaptables diseñadas estéticamente para mostrar la propuesta de valor (Inscripciones, Catering, etc.).
* **Botón Flotante de WhatsApp:** Acceso rápido y directo para facilitar el contacto del usuario en cualquier momento de la navegación.
* **Footer Organizado:** Pie de página simétrico y centrado para dispositivos móviles que unifica las vías de comunicación y redes sociales.

---

## Estructura del Proyecto

La arquitectura de carpetas mantiene un estándar profesional y limpio:


PROYECTO/
│
├── css/                  # Archivos CSS compilados por Sass (main.css)
├── img/                  # Material gráfico, logos e imágenes del sitio
├── pages/                # Páginas secundarias (contacto, galeria, nosotros, servicios)
├── sass/                 # Archivos fuente de Sass organizados por módulos
│   ├── base/             # Estilos globales y reseteos
│   ├── components/       # Estilos de botones, tarjetas, modales
│   ├── layout/           # Estilos de partes fijas (_header.scss, _footer.scss, _media.scss)
│   └── utilities/        # Variables y mixins de Sass
│
├── index.html            # Landing page principal del sitio
└── README.md             # Documentación del proyecto