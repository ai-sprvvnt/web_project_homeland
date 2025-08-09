# Tripleten web_project_homeland

# Sprint 6

Proyecto desarrollado como parte del Sprint 6 del bootcamp de desarrollo web.
En esta entrega se amplía el proyecto del Sprint 5 añadiendo nuevas secciones 
(photo-grid y places) y aplicando técnicas avanzadas de CSS Grid, degradados, 
sombras, y un diseño completamente adaptativo para tres resoluciones principales:
320px, 768px y 1280px.

El sitio presenta una galería fotográfica y descripciones de ciudades vinculadas
a los autores de la obra, con imágenes optimizadas y diseño responsivo que se adapta 
suavemente a resoluciones intermedias.

---

## 🧩 Funcionalidad

- Diseño 100% responsivo para **tres resoluciones clave**: 1280px, 768px y 320px
- Uso de **Flexbox** y **media queries** para adaptación fluida del contenido
- Implementación de fuentes personalizadas locales: **Inter** y **Noto Serif**
- Código organizado siguiendo la **metodología BEM** con estructura de archivos plana
- Estructura semántica con HTML5 (`header`, `main`, `section`, `footer`, etc.)
- Compatible con los navegadores modernos y validado con W3C

---

## 🛠️ Tecnologías utilizadas

- HTML5 – Estructura semántica del sitio.
- CSS3 – Maquetación, BEM, Grid, Flexbox, media queries, degradados, sombras y object-fit.
- Git / GitHub – Control de versiones y despliegue.
- Figma – Diseño base y especificaciones.

---

## 📂 Estructura del proyecto

web_project_homeland/
│
├── images/                # Imágenes optimizadas y renombradas según BEM
├── pages/
│   └── index.css           # Archivo CSS principal que importa todos los bloques
├── blocks/                 # Archivos CSS por bloque según metodología BEM
│   ├── page.css
│   ├── header.css
│   ├── content.css
│   ├── lead.css
│   ├── photo-grid.css
│   ├── places.css          # Contenedor de la sección places
│   ├── place.css           # Cada tarjeta de ciudad (nuevo Sprint 6)
│   ├── footer.css
│
├── index.html              # Página principal
├── README.md               # Documentación del proyecto
├── favicon.ico             # Ícono del sitio
└── vendor/
    ├── normalize.css
    └── fonts.css

---

📏 Alcance del Sprint 6
- Implementación de sección photo-grid: cuadrícula de imágenes responsiva.
- Implementación de sección places: tarjetas con título, artistas, imagen, descripción y botón.
- Aplicación de gradientes y sombras en botones e imágenes.
- Uso de CSS Grid para organización de elementos en todas las resoluciones.
- Comprobación visual en resoluciones intermedias: 470px, 665px, 999px, 1100px y 1500px.
- Optimización y compresión de imágenes.

---

🔗 Demo del proyecto
https://ai-sprvvnt.github.io/web_project_homeland/

---

## 👨‍💻 Autor

Felipe García  
Bootcamp Web Developer – TripleTen
