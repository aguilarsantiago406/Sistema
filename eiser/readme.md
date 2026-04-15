# Eiser - Sitio Web de Comercio Electrónico

## Descripción del Proyecto

Este proyecto es un template front-end para un sitio web de comercio electrónico llamado "Eiser". Está diseñado para mostrar productos, blogs, carrito de compras, proceso de checkout y otras funcionalidades típicas de una tienda en línea. El sitio es estático y utiliza tecnologías web modernas para una experiencia de usuario atractiva y responsiva.

## Características Principales

- **Página de Inicio (index.html)**: Muestra productos destacados, banners y navegación principal.
- **Blog (blog.html, single-blog.html)**: Sección para artículos y publicaciones relacionadas con la tienda.
- **Productos (category.html, single-product.html)**: Páginas para categorías de productos y detalles individuales.
- **Carrito y Checkout (cart.html, checkout.html)**: Funcionalidades para agregar productos al carrito y procesar compras.
- **Contacto (contact.html)**: Formulario de contacto con procesamiento PHP (contact_process.php).
- **Elementos (elements.html)**: Página de demostración de componentes UI.
- **Seguimiento (tracking.html)**: Página para seguimiento de pedidos.

## Tecnologías Utilizadas

- **HTML5**: Estructura del sitio web.
- **CSS3/SCSS**: Estilos y diseño responsivo.
- **JavaScript/jQuery**: Interactividad y funcionalidades dinámicas.
- **Bootstrap**: Framework CSS para diseño responsivo.
- **Vendors**: Librerías adicionales como Owl Carousel para carruseles, Lightbox para imágenes, etc.

## Estructura del Proyecto

```
eiser/
├── index.html                 # Página principal
├── blog.html                  # Página de blog
├── cart.html                  # Carrito de compras
├── category.html              # Categorías de productos
├── checkout.html              # Proceso de pago
├── contact.html               # Página de contacto
├── contact_process.php        # Procesamiento del formulario de contacto
├── elements.html              # Elementos de UI
├── single-blog.html           # Artículo individual del blog
├── single-product.html        # Detalle de producto individual
├── tracking.html              # Seguimiento de pedidos
├── css/                       # Archivos CSS compilados
│   ├── bootstrap.css
│   ├── style.css
│   └── ...
├── scss/                      # Archivos SCSS fuente
│   ├── style.scss
│   └── ...
├── js/                        # Archivos JavaScript
│   ├── jquery-3.2.1.min.js
│   ├── custom.js
│   └── ...
├── img/                       # Imágenes del sitio
│   ├── banner/
│   ├── blog/
│   ├── product/
│   └── ...
├── fonts/                     # Fuentes personalizadas
└── vendors/                   # Librerías de terceros
    ├── owl-carousel/
    ├── bootstrap-datepicker/
    └── ...
```

## Instalación y Uso

1. **Clona o descarga el repositorio** en tu máquina local.
2. **Abre el archivo `index.html`** en tu navegador web preferido.
3. El sitio es completamente estático, por lo que no requiere servidor para la navegación básica. Sin embargo, el formulario de contacto utiliza `contact_process.php`, que necesitaría un servidor PHP para funcionar completamente.

## Configuración

- **SCSS**: Los estilos están escritos en SCSS. Para modificarlos, edita los archivos en la carpeta `scss/` y compila a CSS usando un preprocesador como Prepros (configurado en `prepros-6.config`).
- **Imágenes**: Las imágenes están organizadas en carpetas temáticas dentro de `img/`.
- **JavaScript**: Los scripts personalizados están en `js/custom.js`. Las librerías externas están en `vendors/`.

## Contribución

Si deseas contribuir al proyecto, por favor sigue estos pasos:
1. Haz un fork del repositorio.
2. Crea una rama para tu feature (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -am 'Agrega nueva funcionalidad'`).
4. Push a la rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## Contacto

Para preguntas o soporte, contacta a través de la página de contacto del sitio o envía un email a [aguilarfloressantiago406@gmail.com].
