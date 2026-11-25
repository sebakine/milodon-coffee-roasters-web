# Milodón Coffee Roasters

Sitio web de una tostaduría de café de especialidad en Viña del Mar, Chile: catálogo de productos, carrito de compras persistente y páginas de marca (nosotros, blog y contacto).

Proyecto final del curso de Desarrollo Web de Coderhouse.

## Stack

| Capa | Tecnología |
| --- | --- |
| Estructura | HTML5 semántico con atributos de accesibilidad (ARIA) |
| Estilos | Sass (parciales: variables, mixins, base, layout, componentes) compilado a CSS |
| Componentes UI | Bootstrap 5 |
| Interacción | JavaScript vanilla: carrito con `localStorage`, tooltips |
| SEO | `sitemap.xml`, `robots.txt`, `humans.txt` y metadatos por página |

## Funcionalidades

- Portada con banner, productos destacados, galería, promociones y beneficios.
- Carrito de compras persistente en `localStorage`, con contador, listado y total.
- Páginas de **Nosotros**, **Blog** y **Contacto**.
- Diseño responsivo con imágenes optimizadas en WebP.

## Estructura

```
index.html          Portada
pages/              Nosotros, Blog, Contacto
scss/               Fuentes Sass (_variables, _mixins, _base, _layout, _components)
css/                CSS compilado
js/                 main.js (interacciones) y cart.js (carrito)
img/                Imágenes del sitio
```

## Ejecutar en local

```bash
npm install
npm run scss:build                 # compila Sass a css/main.css
python -m http.server 8000         # sirve el sitio en http://localhost:8000
```

Durante el desarrollo, `npm run scss:watch` recompila los estilos al guardar.

## Autor

Sebastián Muñoz Rivera · [github.com/sebakine](https://github.com/sebakine)
