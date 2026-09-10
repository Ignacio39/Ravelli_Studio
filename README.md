# Ravelli Studio

Página web profesional para servicios de desarrollo web y soluciones digitales.

## Descripción

Ravelli Studio es el portafolio comercial de Ignacio Ravelli, desarrollador freelance especializado en crear páginas web profesionales para negocios y emprendedores.

## Estructura del Proyecto

```
ravelli-studio/
├── index.html              # Página principal
├── pages/
│   ├── servicios.html      # Servicios ofrecidos
│   ├── portfolio.html      # Portfolio de proyectos
│   ├── sobre-mi.html       # Sobre Ignacio Ravelli
│   ├── proceso.html        # Metodología de trabajo
│   └── contacto.html       # Información de contacto
├── css/
│   └── style.css           # Estilos personalizados
├── js/
│   └── main.js             # Funcionalidades JavaScript
├── assets/
│   ├── images/             # Imágenes
│   ├── icons/              # Iconos
│   └── logos/              # Logos
├── lang/
│   └── es.json             # Textos en español
└── README.md               # Este archivo
```

## Características

- Diseño moderno y profesional
- Totalmente responsive (mobile-first)
- Optimizado para SEO
- Animaciones suaves al hacer scroll
- Integración con WhatsApp
- Fácil de mantener y actualizar

## Tecnologías Utilizadas

- HTML5
- CSS3 (con variables CSS)
- JavaScript vanilla
- Google Fonts (Inter)

## Cómo Usar

1. Abre `index.html` en tu navegador
2. Navega por las diferentes secciones
3. Haz clic en "Solicitar presupuesto" para contactar por WhatsApp

## Personalización

### Cambiar número de WhatsApp

Edita el archivo `js/main.js` y busca la línea:

```javascript
const phone = link.dataset.whatsappPhone || '5492657311791';
```

Cambia el número por el tuyo.

### Cambiar colores

Edita las variables CSS en `css/style.css`:

```css
:root {
  --accent: #3b82f6;        /* Color principal */
  --accent-hover: #2563eb;  /* Color hover */
  --bg-primary: #0a0a0a;    /* Fondo principal */
}
```

### Agregar contenido

Los textos principales están en `lang/es.json`. Puedes editar este archivo para cambiar cualquier texto del sitio.

## Hosting

Esta página está preparada para desplegarse en:

- GitHub Pages
- Cloudflare Pages
- Cualquier hosting estático

## Licencia

© 2026 Ravelli Studio. Todos los derechos reservados.
# Ravelli_Studio
