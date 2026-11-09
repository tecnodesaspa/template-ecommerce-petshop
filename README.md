# Pet Paradise — Template ecommerce

Template de tienda de mascotas con 17 páginas HTML existentes.

## Alcance

Incluye servicios y tres pantallas del proceso de pago (pago-1, pago-2 y pago-3), además de catálogo y cuenta. El menú usa JavaScript compartido; los datos de compra y cliente son de muestra.

Los precios, contactos y datos de cliente son ejemplos para personalizar. La presencia de un formulario o botón no garantiza una integración con servicios externos.

## Tecnologías y estructura

- HTML para las páginas.
- Tailwind CSS mediante CDN; no requiere compilar estilos para la vista previa.
- Estilos y configuración visual incluidos en los propios HTML.
- JavaScript local: `main.js`.
- Fuentes, iconos o imágenes externas según cada pantalla; se necesita conexión para cargar esos recursos.

## Vista previa local

Desde esta carpeta, inicia un servidor estático. Por ejemplo, con Node.js y npm disponibles:

```sh
npx --yes http-server . -p 8000
```

Abre [la pantalla inicial](http://localhost:8000/index.html) en el navegador. No hay un package.json ni un paso de build propio del template.

La navegación existente usa el prefijo absoluto `/template-ecommerce-petshop/`. La URL anterior permite inspeccionar la pantalla inicial; para recorrer los enlaces sin modificarlos, configura tu servidor o sitio contenedor para servir esta carpeta bajo ese prefijo. Las rutas de los archivos se conservan tal como están.

## Páginas incluidas

Las rutas son relativas a esta carpeta.

| Archivo | Título de la pantalla |
| --- | --- |
| `carrito/index.html` | Pet Paradise |
| `confirmacion/index.html` | Pet Paradise |
| `contacto/index.html` | Pet Paradise |
| `detalle-producto/index.html` | Pet Paradise |
| `index.html` | Pet Paradise |
| `login/index.html` | Pet Paradise |
| `pago-1/index.html` | Pet Paradise |
| `pago-2/index.html` | Pet Paradise |
| `pago-3/index.html` | Pet Paradise |
| `pedido/index.html` | Pet Paradise |
| `perfil/index.html` | Pet Paradise |
| `politicas/index.html` | Pet Paradise |
| `productos/index.html` | Pet Paradise |
| `recuperar/index.html` | Pet Paradise |
| `registro/index.html` | Pet Paradise |
| `servicios/index.html` | Pet Paradise |
| `terminos/index.html` | Pet Paradise |

## Personalización

- Edita los textos, contactos e imágenes en los HTML.
- Ajusta la configuración de Tailwind y los bloques de estilos de cada HTML.
- Los importes del template están presentados en CLP. Mantén el formato sin decimales y los contactos de ejemplo para Chile al personalizarlo.
- Comprueba los cambios en móvil, tablet y escritorio.

## Integración

Antes de usar el template en una tienda operativa, conecta los servicios que correspondan: catálogo, inventario, autenticación, pedidos, pagos y contacto. Revisa las rutas y sustituye el contenido de muestra y los textos legales por los del negocio.
