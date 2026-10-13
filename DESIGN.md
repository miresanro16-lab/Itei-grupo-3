---
colors:
  intense: "#000B79"
  electric: "#3C66FE"
  sky: "#7CB5FB"
  night: "#16113C"
  white: "#FEFEFE"
  black: "#000000"
  primary: "{colors.intense}"
  interactive: "{colors.electric}"
  accent-soft: "{colors.sky}"
  deep: "{colors.night}"
  surface-light: "{colors.white}"
  ink: "{colors.black}"
  background-brand: "{colors.primary}"
  background-deep: "{colors.deep}"
  background-light: "{colors.surface-light}"
  text-on-dark: "{colors.surface-light}"
  text-on-light: "{colors.black}"
typography:
  family-display: "Arial Black, Arial, sans-serif"
  family-body: "Arial, Helvetica, sans-serif"
  display:
    family: "{typography.family-display}"
    weight: 900
    size: "96px"
    line-height: "100px"
    transform: "uppercase"
    color: "{colors.text-on-dark}"
  h1:
    family: "{typography.family-display}"
    weight: 900
    size: "64px"
    line-height: "68px"
    transform: "uppercase"
  h2:
    family: "{typography.family-display}"
    weight: 900
    size: "40px"
    line-height: "44px"
    transform: "uppercase"
  h3:
    family: "{typography.family-display}"
    weight: 900
    size: "24px"
    line-height: "30px"
    transform: "uppercase"
  body:
    family: "{typography.family-body}"
    weight: 400
    size: "17px"
    line-height: "26px"
  small:
    family: "{typography.family-body}"
    weight: 400
    size: "13px"
    line-height: "18px"
  button:
    family: "{typography.family-display}"
    weight: 900
    size: "15px"
    line-height: "20px"
    transform: "uppercase"
spacing:
  micro: "8px"
  small: "16px"
  related: "24px"
  related-lg: "32px"
  block: "48px"
  block-lg: "64px"
  section: "96px"
  section-lg: "140px"
  container-max: "1600px"
  container-min: "1400px"
  gutter-desktop: "24px"
  gutter-mobile: "16px"
  margin-mobile: "16px"
rounded:
  none: "0px"
  sm: "4px"
  md: "8px"
  pill: "999px"
elevation:
  rest: "none"
  hover: "0 8px 24px rgba(22, 17, 60, 0.16)"
  deep: "0 16px 48px rgba(22, 17, 60, 0.22)"
components:
  button-primary:
    background: "{colors.interactive}"
    text: "{colors.text-on-dark}"
    border: "2px solid {colors.interactive}"
    radius: "{rounded.md}"
    font: "{typography.button}"
  button-secondary:
    background: "transparent"
    text: "{colors.interactive}"
    border: "2px solid {colors.interactive}"
    radius: "{rounded.md}"
    font: "{typography.button}"
  button-hover:
    background: "{colors.surface-light}"
    text: "{colors.interactive}"
  link:
    color: "{colors.interactive}"
    hover: "{colors.primary}"
    decoration-hover: "underline"
  card-project:
    background: "transparent"
    radius: "{rounded.none}"
    shadow: "{elevation.rest}"
    shadow-hover: "{elevation.hover}"
  nav-desktop:
    background: "{colors.background-brand}"
    text: "{colors.text-on-dark}"
  separator-category:
    background: "{colors.background-deep}"
    title-color: "{colors.text-on-dark}"
    outline-word-color: "{colors.accent-soft}"
  star:
    color-primary: "{colors.interactive}"
    color-secondary: "{colors.accent-soft}"
  focus-ring:
    outline: "3px solid {colors.interactive}"
    offset: "2px"
---

# DESIGN — Portafolio M.ROSALES

## Overview

Identidad creativa, enérgica, contemporánea y segura, enfocada en diseño gráfico, identidad de marca y comunicación visual.

Combinación editorial + elementos expresivos: tipografía de gran escala, contrastes marcados azul/blanco, estrellas de 5 puntas y líneas decorativas como recursos constantes.

Juvenil y experimental, pero profesional. Cada proyecto es el protagonista; la identidad es el hilo conductor entre Marca, Publicidad, Editorial y Modelado 3D.

Combinación principal: `{colors.primary}` + `{colors.surface-light}`.
Interacción principal: `{colors.interactive}`.

> ⚠️ REVISAR: `spacing.gutter-desktop: 24px`, `spacing.gutter-mobile: 16px`, `elevation.hover`, `elevation.deep`, `components.link`, `components.focus-ring`, `components.button-hover`, `rounded.pill` y duraciones de animación fueron completados con valores razonables porque no estaban en el documento original.

## Colors

Paleta basada en azules de diferentes intensidades + neutros blanco y negro. Alto contraste, estética enérgica y contemporánea.

- **Azul intenso `{colors.intense}` — principal de identidad.** Fondos, bloques gráficos, encabezados, elementos de marca. Fondo base junto a `{colors.surface-light}`.
- **Azul eléctrico `{colors.electric}` — acento principal / interactivo.** Botones, enlaces, hovers, indicadores. Debe identificar rápidamente toda acción.
- **Azul claro `{colors.sky}` — acento suave / secundario.** Estrellas secundarias, líneas, decorativos, estados sutiles, palabra en contorno detrás de títulos.
- **Azul noche `{colors.night}` — tono más oscuro.** Fondos profundos, transiciones entre secciones, variación sin salir del azul.
- **Blanco `{colors.white}` — fondo claro y texto sobre azul.** Equilibra la intensidad, mantiene limpieza.
- **Negro `{colors.black}` — texto sobre fondos claros.** Máximo contraste. Los proyectos mantienen sus colores originales; la UI no añade color extra.

Reglas de uso: base `{colors.background-brand}` + `{colors.text-on-dark}`; secciones profundas alternan a `{colors.background-deep}`; `{colors.accent-soft}` solo detalles, nunca superficies grandes; neutros garantizan legibilidad.

## Typography

Solo dos familias: **Arial Black** para impacto + **Arial** para información.

- **Display `{typography.display}`:** `family-display`, 900, 80–120px (token: 96px), line-height 85–110px (token: 100px), siempre mayúsculas. Títulos protagonistas de sección.
- **H1:** `Arial Black` 56–72px (token: 64px), mayúsculas. Proyectos y secciones importantes.
- **H2:** `Arial Black` 36–48px (token: 40px).
- **H3 / subtítulo:** `Arial Black` 22–28px (token: 24px).
- **Body `{typography.body}`:** `Arial Regular` 16–18px (token: 17px), line-height 24–28px (token: 26px). Descripciones, proceso, sobre mí.
- **Small:** `Arial Regular` 13–14px (token: 13px). Categorías, fechas, etiquetas.
- **Navegación / Botones `{typography.button}`:** `Arial Bold` o `Arial Black` 14–16px (token: 15px), mayúsculas en botones.

> ⚠️ REVISAR: pesos 900/700/400 y line-heights de H1/H2/H3 (68/44/30px) inferidos de los rangos. Si usas Arial Black real, no aplicar `font-stretch`; simular condensado solo con tracking ajustado.

## Layout

Composición editorial, modular, visual, con protagonismo de imagen. No todos los proyectos en tarjetas idénticas; variar tamaños para recorrido editorial.

- **Rejilla escritorio:** 12 columnas, composiciones variables. Proyectos hero a ancho completo, otros en 2–3 columnas.
- **Ancho máximo:** `{spacing.container-min}`–`{spacing.container-max}`, centrado. >1440px: contenido centrado.
- **Espaciado:** micro `{spacing.micro}`; pequeña `{spacing.small}`; elementos relacionados `{spacing.related}`–`{spacing.related-lg}`; bloques `{spacing.block}`–`{spacing.block-lg}`; secciones `{spacing.section}`–`{spacing.section-lg}`.
- **Responsivo:**
  - Móvil 320–599px: 1 columna, márgenes `{spacing.margin-mobile}`–20px, proyectos a ancho completo.
  - Tableta 600–1023px: 2 columnas cuando el contenido lo permita.
  - Escritorio 1024–1439px: 12 columnas variables.
  - Amplio 1440px+: max `{spacing.container-max}`.
- Títulos grandes reducen tamaño progresivamente; palabra en contorno nunca provoca scroll horizontal. En móvil, hover → información visible o toque.

> ⚠️ REVISAR: `gutter-desktop 24px / gutter-mobile 16px` inventados para implementar la rejilla de 12 columnas.

## Elevation & Depth

Diseño principalmente plano. Sombras suaves y difusas solo en interacción o apilamiento.

- **Nivel 0 reposo `{elevation.rest}`:** tarjetas en reposo, campos, navegación. Sin sombra.
- **Nivel 1 hover/interactivo `{elevation.hover}`:** solo cuando ayuda a indicar interactividad.
- **Nivel 2 profundo `{elevation.deep}`:** solo para overlays / menú móvil apilado.
- Las imágenes de proyectos pueden traer sombras propias de sus mockups; no añadir sombra UI extra sobre ellas.

> ⚠️ REVISAR: valores `hover/deep` inventados (el original solo dice "muy sutil"). Ajustar opacidad si se quiere aún más plano.

## Shapes

Geométrico, rectangular, bordes definidos, estética gráfica/editorial.

- **Radio por defecto `{rounded.none}`:** imágenes, bloques, galerías, secciones principales.
- **Redondeo sutil `{rounded.sm}`:** elementos interactivos pequeños.
- **Máximo botones/etiquetas `{rounded.md}`:** evitar radios mayores; nada excesivamente redondeado. `{rounded.pill}` reservado solo para tags/etiquetas si se necesita — no para tarjetas.
- **Estrella 5 puntas (recurso característico):**
  - Principal decorativa escritorio: 48×48px, color `{colors.interactive}`.
  - Secundarias: 24×24–32×32px, color `{colors.accent-soft}`.
  - Indicadores/pequeños: 16×16px.
  - Fondos/composiciones: 80–120px, sin interferir lectura ni competir con proyecto.
- **Líneas decorativas:** grosor 1–2px, longitud 80–200px, acompañando títulos o estrellas, color `{colors.accent-soft}` o `{colors.text-on-dark}`.

## Components

### Navegación

Sencilla y limpia. Items: Inicio, Sobre mí, Proyectos, Contacto + categorías directas: Marca, Publicidad, Editorial, Modelado 3D.

- Escritorio: visible arriba, fondo `{colors.background-brand}`, texto `{typography.button}` en `{colors.text-on-dark}`.
- Móvil: menú compacto (hamburguesa → overlay en `{colors.background-deep}` con `{elevation.deep}`).
- Estado activo: subrayado o estrella 16px en `{colors.accent-soft}`.
- > ⚠️ REVISAR: estado activo y overlay móvil inferidos; definir si nav es fija (sticky) o estática.

### Botones

- **Primario `{components.button-primary}`:** fondo `{colors.interactive}`, texto blanco, bold/mayúsculas, radio `{rounded.md}`, borde `2px solid {colors.interactive}`.
- **Secundario `{components.button-secondary}`:** fondo transparente, borde azul, texto azul.
- **Hover:** invertir colores (fondo blanco/texto azul) o pequeño desplazamiento (ej. `translateY(-2px)` + `{elevation.hover}`, transición 200ms). > ⚠️ REVISAR: `2px`, `translateY(-2px)`, `200ms` son valores razonables no especificados.
- **Enlaces:** color `{colors.interactive}`, hover `{colors.primary}` + subrayado. > ⚠️ REVISAR: estilo de enlace inferido.
- **Foco accesible:** `outline: 3px solid {colors.interactive}`, offset 2px. > ⚠️ REVISAR: añadido por accesibilidad, no estaba en original.

### Tarjetas de proyecto

Prioridad absoluta a la imagen, sin marco uniforme.

- Reposo: imagen limpia, radio `{rounded.none}`, sombra `{elevation.rest}`.
- Hover (desktop): ligero zoom imagen (`scale 1.04`, 300ms) + overlay en `{colors.background-deep}` con: Nombre, Categoría, Año, CTA "Ver proyecto". > ⚠️ REVISAR: `scale 1.04 / 300ms / overlay` son valores razonables.
- Móvil/táctil: sin depender de hover; mostrar título/categoría siempre debajo o activar por toque.

### Separadores de categoría

Sección fondo `{colors.background-deep}` con título blanco gran escala (`{typography.display}`) + misma palabra detrás en contorno `{colors.accent-soft}` o blanco (efecto actual del portafolio). Contorno con `-webkit-text-stroke: 2px` + `color: transparent`. Nunca causa overflow.

### Estrellas / decorativos

Usar como hilo conductor, con moderación. No llenar todas las secciones. Respetar tamaños de Shapes. En fondos grandes, opacidad reducida para no competir.

## Do's and Don'ts

### Do's — Sí

- Mantener el azul (`{colors.primary}`) como identidad principal.
- Utilizar títulos grandes, condensados y en mayúsculas (`{typography.display}`).
- Dar prioridad a las imágenes de los proyectos.
- Utilizar estrellas como recurso gráfico recurrente, con medida.
- Mantener alto contraste azul/blanco (`{colors.background-brand}` / `{colors.text-on-dark}`).
- Crear composiciones editoriales y dinámicas.
- Utilizar mucho espacio negativo (`{spacing.section}`–`{spacing.section-lg}`).
- Incorporar animaciones sencillas que den vida (150–300ms). > ⚠️ REVISAR: duración inferida.
- Mantener consistencia entre categorías Marca / Publicidad / Editorial / 3D.

### Don'ts — No

- No dejar que la identidad compita con los proyectos.
- No utilizar demasiados colores adicionales en la interfaz fuera de la paleta.
- No llenar todas las secciones de estrellas.
- No utilizar degradados sin una función específica.
- No abusar de sombras (por defecto `{elevation.rest}`).
- No utilizar tarjetas excesivamente redondeadas (respetar `{rounded.none}`–`{rounded.md}`).
- No hacer que todos los proyectos tengan exactamente el mismo tamaño.
- No utilizar animaciones que dificulten la navegación.
- No colocar demasiado texto sobre las imágenes.
- No utilizar texturas detrás de textos largos si afectan la legibilidad.
