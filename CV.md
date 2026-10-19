---
title: "Landing CV — Mireille Abigail Sánchez Rosales"
source: "Arquitectura-CV.docx"
design_system: "DESIGN.md"
type: "one-page"
---

# CV — Mireille Abigail Sánchez Rosales

> ⚠️ REVISAR: el documento original no trae teléfono, correo ni URL de Behance. Se dejan placeholders. Tampoco trae porcentajes de habilidades: se usan números 01–04 + 4 categorías inferidas de tu perfil.

## 1. Navegación

- Tipo: menú fijo (`sticky`) visible durante el scroll. Fondo `{colors.background-brand}` (`#000B79`), texto `{colors.text-on-dark}` (`#FEFEFE`).
- Links: Inicio (`#inicio`), Sobre mí (`#sobre-mi`), Educación (`#educacion`), Experiencia (`#experiencia`), Habilidades (`#habilidades`), Proyectos (`#proyectos`), Contacto (`#contacto`).
- Hover: texto a `{colors.accent-soft}` (`#7CB5FB`) + estrella pequeña como indicador.
- Móvil: hamburguesa sin perder identidad. Scroll fluido + animaciones 200–400ms.

## 2. Inicio (hero) — `#inicio`

- Fondo azul intenso `#000B79` + textura `assets/img/fondo encabezado.png` + margen `assets/img/margen_encabezado.png`.
- Protagonista: palabra “PORTAFOLIO” en Arial Black mayúsculas, 100–120px desktop, + misma palabra en contorno detrás (profundidad editorial).
- Debajo: **Mireille Abigail Sánchez Rosales** + “Diseñadora Gráfica y Digital”, centrado, blanco + azul claro.
- Decoración: estrellas 5 puntas `#3C66FE` y `#FEFEFE`, 24–64px, movimiento sutil. Sin competir con el título.
- CTA: botón primario “Explorar mi trabajo” → `#proyectos` + indicador de scroll.

## 3. Sobre mí — `#sobre-mi`

- Fondo blanco `#FEFEFE`. Dos columnas: título + texto | foto.
- Título “SOBRE MÍ”: Arial Black ~64px, `#000B79`.
- Foto: `assets/img/Mireille_bn.png` (blanco y negro) + estrellas azules parcialmente detrás.
- Texto: Soy Mireille Abigail Sánchez Rosales, estudiante de Diseño Gráfico y Digital en la Universidad La Salle. Me apasiona el desarrollo de identidades visuales, las campañas publicitarias y la creación de propuestas gráficas que comuniquen de manera creativa y estratégica. Disfruto explorar diferentes áreas del diseño, desde la composición editorial y la edición fotográfica hasta el modelado 3D, buscando desarrollar soluciones visuales que combinen funcionalidad, estética y personalidad.
- Tags (rectangulares azules, texto blanco, radio 4px): Adaptable, Proactiva, Responsable, Aprendizaje rápido, Trabajo en equipo.

## 4. Educación — `#educacion`

- Fondo azul noche `#16113C`. Título “EDUCACIÓN”: Arial Black ~64px, blanco.
- Contenido: **Licenciatura en Diseño Gráfico y Digital — Universidad La Salle.** Actualmente curso el séptimo semestre, con conocimientos en identidad visual, comunicación gráfica, publicidad, diseño editorial y herramientas digitales.
- Bloque rectangular limpio (sin tarjeta convencional) + líneas decorativas azules + estrella ~32px.

## 5. Experiencia — `#experiencia`

- Fondo blanco `#FEFEFE`. Título “EXPERIENCIA”: Arial Black ~64px, `#000B79`, mayúsculas.
- Timeline vertical: línea `#3C66FE` 2px + estrellas 24px como indicadores. Bloques con padding 24px, separación 48px. Empresa en azul profundo, periodo en azul eléctrico. Títulos 28px Black, cuerpo 16–18px Regular. Hover sutil.
- **Motion Media — Actualidad (2 meses):** trabajo en agencia de publicidad, experiencias de marca y producción de eventos; propuestas gráficas, contenido digital, materiales publicitarios y adaptación visual para marcas y campañas.
- **Alumni, Universidad La Salle — Servicio social:** comunicación visual y materiales gráficos para egresados; organización y colaboración institucional.
- **Legends Academy — 3 meses:** entorno profesional; comunicación, responsabilidad, organización y trabajo en equipo.

## 6. Habilidades — `#habilidades`

- Fondo `#000B79` + textura papel ligera + estrellas en esquinas.
- 4 categorías (inferidas · REVISAR): Identidad visual, Publicidad, Editorial, Digital / 3D. Números 01–04 en Arial Black ~72px blanco; categoría debajo en 24px; línea 2px `#7CB5FB` de 100–140px. Estrellas pueden superponerse sin tapar lectura.
- Subsección “HERRAMIENTAS”: Adobe Illustrator, Photoshop, InDesign, After Effects (badges de texto; sin iconos en assets). Distribución ordenada, aire amplio, hover sutil.

## 7. Proyectos destacados — `#proyectos`

- Título “MIS PROYECTOS”: Arial Black ~72px + misma palabra en contorno.
- 4 categorías: Marca, Publicidad, Editorial, Modelado 3D. Fondos azules, títulos blancos, estrellas.
- Galería 2–3 columnas, imágenes protagonistas, radio 0px, gap 24px. Hover: zoom `scale 1.04` + overlay azul oscuro + nombre + “VER PROYECTO →”. Click: modal con imágenes, descripción, objetivo y resultados.
- Assets por subcarpeta:
  - Marca: `assets/img/MARCA/BIT & SERIF/` (6 piezas), `assets/img/MARCA/FERIA DEL LIBRO/` (cartel, merch, posts, pulsera), `assets/img/MARCA/Laboratorios Lapi-Rediseño/` (lapi_1–5).
  - Publicidad: `assets/img/PUBLICIDAD/ANUNCIO CLOUD ARIANA GRANDE@300x.png`, `assets/img/PUBLICIDAD/publi_skydancers.png`.
  - Editorial: `assets/img/EDITORIAL/ARTICULO GENERACIONAL MUSICA/` (4 pliegos), `assets/img/EDITORIAL/FANZINE SIGNOS ZODIACALES/` (4 piezas), `assets/img/EDITORIAL/HELVETICA/` (2 piezas).
  - Modelado 3D: `assets/img/MODELADO 3D/LEGO CITY SPACE STAND/` (6 renders), `assets/img/MODELADO 3D/LEGO CITY SPACE/` (5 renders).

## 8. Contacto — `#contacto`

- Fondo `#000B79` + textura papel. Título “CONTACTO” centrado ~100px blanco + contorno detrás.
- Estrella central ~40px + dos líneas 160px / 2px.
- 3 columnas: Teléfono / Correo / Behance. Títulos 24px Black, datos 18px Regular. Links blanco → `#7CB5FB` hover + estrellita.
- Datos (REVISAR): Teléfono `[+52 ...]`, Correo `[tu@correo.com]`, Behance `[url]`.

## 9. Footer

- Fondo `#16113C`, ~100px. “Mireille Abigail Sánchez Rosales · 2026 · Diseño Gráfico y Digital” + estrella 16px. Arial 14px blanco. Horizontal en desktop, vertical en móvil.

## 10. Responsive e interacciones

- Desktop 12 col / max 1440px · tableta 6–8 col · móvil 1 col. Displays con `clamp()`, galerías 3→2→1, menos estrellas en móvil.
- 200–400ms, suaves: reveals, parallax ligero de estrellas, hover en botones e imágenes. Respetar `prefers-reduced-motion` y no afectar carga ni legibilidad.
