# Las Cano y Asociados — Web Corporativa WordPress

**URL:** [https://lascanoyasociados.com](https://lascanoyasociados.com)

Sitio web corporativo para firma de abogados/consultoría legal en Ecuador.

## Descripción

Desarrollo de presencia digital profesional para **Las Cano y Asociados**, firma especializada en derecho corporativo, tributario, laboral y asesoría legal integral.

## Características Implementadas

- **Theme personalizado** child theme (PHP, SCSS, JS vanilla)
- **Páginas:** Inicio, Nosotros, Áreas de Práctica, Equipo, Blog/Publicaciones, Contacto
- **Formularios de contacto** con validación y envío a email corporativo
- **SEO técnico:** Schema markup Organization/LegalService, sitemap XML, robots.txt, meta tags
- **Performance:** Caché, optimización imágenes WebP, CDN, lazy loading
- **Seguridad:** 2FA admin, backups automáticos, WAF, SSL forzado, headers de seguridad
- **Accesibilidad:** WCAG 2.1 AA, contraste, navegación teclado, alt text
- **Cumplimiento legal Ecuador:** Aviso cookies, política privacidad, términos uso

## Stack Técnico

| Capa | Tecnología |
|------|------------|
| CMS | WordPress 6.x |
| Theme | Child theme custom |
| Page Builder | Elementor Pro / Gutenberg |
| Hosting | Hostinger |
| PHP | 8.2+ |
| Base de datos | MySQL 8 / MariaDB |
| Control de versiones | Git |

## Capturas de Pantalla

| Archivo | Descripción |
|---------|-------------|
| `las-cano-asociados/screenshots/01-home.png` | Hero + propuesta de valor |
| `las-cano-asociados/screenshots/02-nosotros.png` | Equipo, historia, valores |

---

## Estructura del Theme (referencia)

```
wp-content/themes/las-cano-child/
├── functions.php           # Hooks, CPT, taxonomías, ACF, enqueue
├── style.css               # Info theme + estilos base
├── assets/
│   ├── css/                # SCSS compilado
│   ├── js/                 # Scripts modulares
│   └── images/             # Logos, icons, hero
├── template-parts/         # Partes reutilizables
├── templates/              # Plantillas páginas
├── inc/                    # Includes: CPT, shortcodes, widgets
└── languages/              # .po/.mo traducciones
```

---

**Desarrollado por:** Alejandro Veloz Vera  
**Año:** 2024-2025  
**Cliente:** Las Cano y Asociados (Riobamba/Quito, Ecuador)