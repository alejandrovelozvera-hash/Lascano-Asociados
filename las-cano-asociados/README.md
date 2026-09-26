# Las Cano y Asociados — Sitio Web Corporativo

**URL:** [https://lascanoyasociados.com](https://lascanoyasociados.com)

Sitio web corporativo desarrollado en **WordPress** para firma de abogados/consultoría en Ecuador.

## Descripción

Diseño y desarrollo de presencia digital profesional para **Las Cano y Asociados**, firma especializada en [áreas de práctica: derecho corporativo, tributario, laboral, etc.]. El sitio comunica confianza, experiencia y servicios legales de alto nivel.

**Rol:** Desarrollador / Implementador WordPress  
**Año:** 2024-2025  
**Cliente:** Las Cano y Asociados (Riobamba/Quito, Ecuador)

## Características Implementadas

- **Theme personalizado** child theme basado en [Astra / GeneratePress / Hello Elementor / custom]
- **Páginas principales:** Inicio, Nosotros, Áreas de Práctica, Equipo, Publicaciones/Blog, Contacto
- **Formularios de contacto** con validación y envío a email corporativo (Contact Form 7 / Gravity Forms / WPForms)
- **SEO técnico:** Yoast/RankMath, schema markup Organization/LegalService, sitemap XML, robots.txt
- **Performance:** Caché (WP Rocket / LiteSpeed), optimización imágenes (WebP), CDN
- **Seguridad:** Wordfence/Sucuri, 2FA admin, backups automáticos (UpdraftPlus), SSL forzado
- **Multidioma:** WPML / Polylang (español/inglés si aplica)
- **Accesibilidad:** WCAG 2.1 AA, contraste, navegación teclado, alt text en imágenes
- **RGPD/LOPD Ecuador:** Aviso cookies, política privacidad, términos uso

## Stack Técnico

| Capa | Tecnología |
|------|------------|
| CMS | **WordPress 6.x** |
| Theme | **Child theme** (PHP, SCSS, JS vanilla) |
| Page Builder | **Elementor Pro / Gutenberg / Bricks** |
| Hosting | **Hostinger / SiteGround / VPS** |
| PHP | **8.2+** |
| BD | **MySQL 8 / MariaDB** |
| Control versiones | **Git** (este repo) |
| Despliegue | **Git → FTP/SFTP / WP CLI / Deployer** |

## Estructura del Theme (si aplica)

```
wp-content/themes/las-cano-child/
├── functions.php           # Hooks, enqueue, CPT, taxonomies, ACF
├── style.css               # Info theme + estilos base
├── assets/
│   ├── css/                # SCSS compilado
│   ├── js/                 # Scripts modulares
│   └── images/             # Logos, icons, hero
├── template-parts/         # Partes reutilizables
├── templates/              # Plantillas páginas (page-*.php)
├── inc/                    # Includes: CPT, shortcodes, widgets
└── languages/              # .po/.mo traducciones
```

## Capturas de Pantalla

Coloca tus imágenes en `screenshots/`:

| Archivo | Descripción |
|---------|-------------|
| `screenshots/01-home.jpg` | Hero + propuesta de valor |
| `screenshots/02-nosotros.jpg` | Equipo, historia, valores |
| `screenshots/03-areas-practica.jpg` | Grid servicios legales |
| `screenshots/04-equipo.jpg` | Fichas abogados |
| `screenshots/05-contacto.jpg` | Formulario + mapa + info |
| `screenshots/06-mobile.jpg` | Vista responsive |
| `screenshots/07-admin.jpg` | Backend: CPT, ACF, opciones theme |

> **Nota:** Añade tus capturas reales renombrando los archivos arriba.

## Cómo Replicar / Desarrollo Local

```bash
# 1. Clonar repo
git clone https://github.com/alejandrovelozvera-hash/portfolio.git
cd portfolio/las-cano-asociados

# 2. Requisitos locales
# - Docker / Laravel Valet / XAMPP / MAMP / LocalWP
# - PHP 8.2+, MySQL 8+, Node 20+ (para build assets)

# 3. Importar BD + wp-content/uploads (si tienes backup)
# 4. Configurar wp-config.php local
# 5. npm install && npm run dev  # si usas Vite/Webpack para assets
```

## Créditos

- **Desarrollo:** Alejandro Veloz Vera
- **Diseño UI/UX:** [Tu nombre / Diseñador externo / Theme base]
- **Contenido legal:** Equipo Las Cano y Asociados
- **Fotografía:** [Stock / Fotógrafo / Cliente]

---

## Licencia

Proyecto privado — portfolio demostrativo.  
Código del theme child: MIT (si decides abrirlo).  
Contenido e imágenes: propiedad de Las Cano y Asociados.