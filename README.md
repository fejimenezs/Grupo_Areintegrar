# Grupo Empresarial A Reintegrar S.A.S. — Sitio Web / Website

> **Eslogan:** *Transformamos residuos en nuevas oportunidades.*
> **Slogan:** *We transform waste into new opportunities.*

---

## Español

### ¿Qué es este proyecto?

Sitio web corporativo de una sola página (landing page) para **Grupo Empresarial A Reintegrar S.A.S.**, empresa de economía circular con sede en Malambo, Atlántico, Colombia.

### Estructura de archivos

```
GRUPO EMPRESARIAL A REINTEGRAR S.A.S./
├── index.html                        ← Sitio web principal (un solo archivo)
├── logo_final.png                    ← Logo oficial de la empresa
├── imagen de referencia para la pagian.png  ← Mockup de referencia visual
├── README.md                         ← Este archivo / This file
├── Intrucciones.md                   ← Instrucciones y contenido del cliente
├── Identidad de Marca.docx           ← Documento de identidad de marca
├── Propuesta de identidad visual.docx
├── Visual Glogal.docx
├── Descripion de la empresa.docx
└── CAMARA DE COMERCIO GRUPO.pdf
```

### Secciones del sitio

| # | Sección | ID | Descripción |
|---|---|---|---|
| 1 | Navegación | `#navbar` | Barra fija con scroll effect y menú responsive |
| 2 | Hero | `#inicio` | 3 paneles: residuos · soluciones · madera plástica |
| 3 | Cifras de impacto | `#cifras` | Contadores animados de impacto |
| 4 | Economía circular | `#economia-circular` | Proceso de 5 pasos con flechas |
| 5 | Servicios | `#servicios` | Grid de 6 tarjetas de servicios |
| 6 | Productos | `#productos` | Catálogo de 6 productos |
| 7 | Madera plástica | `#madera-plastica` | Showcase del producto estrella |
| 8 | Nosotros | `#nosotros` | Misión, visión y 6 valores |
| 9 | Contacto | `#contacto` | Formulario + info + WhatsApp |
| 10 | Footer | — | Logo, enlaces, redes sociales |

### Tecnologías usadas

- **HTML5** — estructura semántica
- **Tailwind CSS v3** (CDN) — utilidades de estilo
- **CSS personalizado** — animaciones, gradientes, componentes
- **Font Awesome 6** (CDN) — íconos
- **Google Fonts** — Montserrat (títulos) + Inter (cuerpo)
- **JavaScript vanilla** — interacciones, contadores, scroll reveal

### Cómo usar

1. **Abrir directamente:** Doble clic en `index.html` → se abre en el navegador.  
   *(No requiere servidor, Node.js, ni instalación alguna.)*

2. **Ver en servidor local** (opcional, mejor rendimiento de fuentes):
   ```bash
   # Con Python
   python -m http.server 8080
   # Luego abre: http://localhost:8080
   ```

### Personalizar antes de publicar

Busca los comentarios `REEMPLAZAR / REPLACE` en el código HTML para actualizar:

| Dato | Ubicación | Qué cambiar |
|---|---|---|
| Número de WhatsApp | `#contacto` y `<footer>` | Reemplazar `573000000000` por el número real |
| Email | `#contacto` | Reemplazar `contacto@areintegrar.com` |
| Redes sociales | `<footer>` | Agregar URLs reales en los `href="#"` |
| Formulario | `handleSubmit()` en `<script>` | Conectar con Formspree, EmailJS o backend propio |
| Mapa | `#contacto` | Reemplazar el placeholder con un `<iframe>` de Google Maps |
| Cifras de impacto | `.counter` | Actualizar `data-target` con números reales |

### Paleta de colores (Identidad de Marca)

| Rol | Color | Hex |
|---|---|---|
| Verde sostenibilidad | Primario | `#2E7D32` |
| Verde brillante | Acento | `#4CAF50` |
| Azul confianza | Secundario | `#1565C0` |
| Gris grafito | Industria | `#37474F` |
| Blanco | Limpieza | `#FFFFFF` |

### Tipografía

- **Títulos:** Montserrat Bold / Black
- **Cuerpo:** Inter Regular / Medium

---

## English

### What is this project?

A single-page corporate website (landing page) for **Grupo Empresarial A Reintegrar S.A.S.**, a circular economy company based in Malambo, Atlántico, Colombia.

### File Structure

```
GRUPO EMPRESARIAL A REINTEGRAR S.A.S./
├── index.html                        ← Main website (single file)
├── logo_final.png                    ← Official company logo
├── imagen de referencia para la pagian.png  ← Visual reference mockup
├── README.md                         ← This file
└── ... (brand & company documents)
```

### Page Sections

| # | Section | ID | Description |
|---|---|---|---|
| 1 | Navigation | `#navbar` | Fixed navbar with scroll effect and responsive menu |
| 2 | Hero | `#inicio` | 3-panel hero: waste · solutions · plastic wood |
| 3 | Impact Numbers | `#cifras` | Animated impact counters |
| 4 | Circular Economy | `#economia-circular` | 5-step process with arrows |
| 5 | Services | `#servicios` | 6-card services grid |
| 6 | Products | `#productos` | 6-product catalog |
| 7 | Plastic Wood | `#madera-plastica` | Star product showcase |
| 8 | About Us | `#nosotros` | Mission, vision, and 6 core values |
| 9 | Contact | `#contacto` | Form + info + WhatsApp |
| 10 | Footer | — | Logo, links, social media |

### Tech Stack

- **HTML5** — semantic structure  
- **Tailwind CSS v3** (CDN) — utility-first styling  
- **Custom CSS** — animations, gradients, components  
- **Font Awesome 6** (CDN) — icons  
- **Google Fonts** — Montserrat (headings) + Inter (body)  
- **Vanilla JavaScript** — interactions, counters, scroll reveal  

### How to Use

1. **Open directly:** Double-click `index.html` → opens in browser.  
   *(No server, Node.js, or installation required.)*

2. **Run on local server** (optional, better font loading):
   ```bash
   # With Python
   python -m http.server 8080
   # Then open: http://localhost:8080
   ```

### Pre-launch Checklist

Find `REEMPLAZAR / REPLACE` comments in the HTML to update:

| Data | Location | What to change |
|---|---|---|
| WhatsApp number | `#contacto` + `<footer>` | Replace `573000000000` with real number |
| Email address | `#contacto` | Replace `contacto@areintegrar.com` |
| Social media links | `<footer>` | Add real URLs to `href="#"` anchors |
| Contact form | `handleSubmit()` in `<script>` | Connect Formspree, EmailJS, or custom backend |
| Google Maps | `#contacto` | Replace placeholder with real `<iframe>` embed |
| Impact numbers | `.counter` elements | Update `data-target` with real figures |

### Brand Color Palette

| Role | Color | Hex |
|---|---|---|
| Sustainability green | Primary | `#2E7D32` |
| Bright green | Accent | `#4CAF50` |
| Trust blue | Secondary | `#1565C0` |
| Graphite gray | Industry | `#37474F` |
| White | Cleanliness | `#FFFFFF` |

### Typography

- **Headings:** Montserrat Bold / Black
- **Body text:** Inter Regular / Medium

---

## Git — Subir al repositorio / Push to repository

```bash
# Clonar o inicializar / Clone or initialize
git init
git remote add origin https://github.com/fejimenezs/pagina_web_Grupo_empresarila_areintegrar.git

# Agregar archivos / Stage files
git add index.html README.md logo_final.png

# Confirmar / Commit
git commit -m "feat: add complete landing page for A Reintegrar S.A.S."

# Subir / Push
git push -u origin main
```

---

*© 2026 Grupo Empresarial A Reintegrar S.A.S. · Malambo, Atlántico, Colombia*