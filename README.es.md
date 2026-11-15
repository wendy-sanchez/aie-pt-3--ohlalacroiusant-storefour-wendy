# Ohlala Croisant Storefour

Prototipo de tienda online responsive desarrollado con HTML, CSS y JavaScript. El proyecto explora la estructura y las interacciones de una tienda digital, incluyendo navegación por productos, filtrado por categorías, gestión del carrito y una interfaz de checkout en varios pasos.

## Descripción general

Ohlala Croisant Storefour es un proyecto académico colaborativo de desarrollo web basado en el concepto de una tienda online personalizable.

El repositorio contiene varias páginas de tienda y componentes interactivos de frontend. El catálogo actual incluye categorías de muestra orientadas a la moda, mientras que otras partes de la interfaz conservan la identidad original de Croisant Storefour. Por este motivo, el proyecto se documenta como un prototipo general de tienda online y no como una tienda de producción completamente integrada.

## Funcionalidades

- **Página de inicio:** estructura principal de la tienda y navegación.
- **Catálogo de productos:** tarjetas de productos organizadas por categorías.
- **Filtrado por categorías:** permite filtrar los productos, incluyendo calzado, camisas, pantalones y accesorios.
- **Carrito de compra:** permite añadir productos, incrementar cantidades, modificar unidades y eliminar artículos.
- **Persistencia del carrito:** guarda los datos del carrito en `localStorage` del navegador.
- **Resumen del carrito:** muestra cantidades, totales por artículo y subtotal.
- **Página de detalle de producto:** presentación individual del producto con selector de cantidad e interfaz para añadirlo al carrito.
- **Interfaz de checkout en varios pasos:** flujo de tres etapas para datos personales, dirección de entrega y datos de tarjeta.
- **Validación de formularios:** validación en el navegador de campos obligatorios y comprobaciones básicas del formato de tarjeta.
- **Página de contacto:** formulario visual para consultas y solicitudes especiales.
- **Componentes reutilizables:** elementos compartidos de navegación y pie de página.

## Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura y contenido de las páginas |
| CSS3 | Estilos personalizados y diseño responsive |
| JavaScript | Carrito, filtros del catálogo, interacciones del checkout y navegación |
| Tailwind CSS 4 | Estilos mediante CDN del navegador |
| Alpine.js | Interacciones declarativas ligeras en el frontend |
| Python | Servidor local de desarrollo |
| Flask | Servir la web estática durante el desarrollo |

## Estructura del proyecto

```text
aie-pt-3--ohlalacroiusant-storefour-wendy/
├── components/
│   └── layout-components.js
├── index.html
├── catalogo.html
├── carrito.html
├── carrito.js
├── product.html
├── product.css
├── contact.html
├── app.js
├── script.js
├── styles.css
├── server.py
├── README.md
└── README.es.md
```

## Instalación y ejecución

### Requisitos previos

- Python 3.
- pip.
- Un navegador web moderno.

### Instalación

1. Clonar o descargar el repositorio.
2. Abrir una terminal en el directorio del proyecto.
3. Instalar Flask:

   ```bash
   pip install flask
   ```

### Ejecutar la aplicación

Iniciar el servidor local de desarrollo:

```bash
python server.py
```

Abrir la siguiente dirección en el navegador:

```text
http://localhost:3000
```

## Cómo utilizar la aplicación

1. Abrir la página de inicio para explorar la tienda.
2. Acceder al catálogo para consultar los productos.
3. Utilizar los botones de categorías para filtrar los artículos disponibles.
4. Añadir productos al carrito.
5. Abrir el carrito para modificar cantidades o eliminar productos.
6. Consultar la interfaz de checkout y avanzar por sus diferentes pasos.
7. Utilizar la página de contacto para explorar el formulario de consultas.

## Alcance y limitaciones del proyecto

Este repositorio representa un prototipo académico centrado en el frontend. Algunos elementos son demostraciones de interfaz y no servicios de comercio electrónico completos.

- El carrito utiliza `localStorage` del navegador y no depende de una base de datos backend.
- El checkout valida los campos en el navegador y muestra un mensaje de confirmación. No está conectado a una pasarela de pago ni procesa transacciones reales.
- El paso de datos personales está intencionadamente dejado como marcador de posición.
- El formulario de contacto se presenta como interfaz frontend; no hay un backend configurado para enviar mensajes.
- El contenido de productos y la identidad de marca no son completamente consistentes en todas las páginas y deben considerarse contenido de muestra del proyecto.

## Proyecto colaborativo

Este proyecto fue desarrollado en equipo como parte de una actividad académica de desarrollo web.

Permitió adquirir experiencia práctica con estructuras web multipágina, interacciones frontend, manipulación del DOM, almacenamiento en el navegador, componentes reutilizables y desarrollo colaborativo.

---

**Tipo de proyecto:** Proyecto colaborativo  
**Estado:** Prototipo frontend de tienda online
