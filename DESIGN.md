---
metadata:
  name: "MSR — Sistema de diseño"
  source: "DESIGN_Mireille.docx"
  updated: "2026-10-19"
  precedence: "Diseño efectivo de index.html sobre reglas históricas contradictorias"
colors:
  brand:
    intense: "#000B79"
    electric: "#3C66FE"
    sky: "#7CB5FB"
    night: "#16113C"
    white: "#FEFEFE"
    black: "#000000"
  active:
    intense: "#07134D"
    electric: "#174BFF"
    sky: "#7299FF"
    night: "#050610"
    text: "#EEEEEF"
    background: "#050505"
    surface: "#090B16"
    surface-project: "#090C1A"
  complementary:
    contact: "#000B79"
    halo: "#3C66FE"
    link: "#7CB5FB"
typography:
  family-display: "Arial Black, Arial, sans-serif"
  family-body: "Arial, Helvetica, sans-serif"
  family-cover: "Didot, Bodoni MT, Times New Roman, serif"
  family-numbers: "Impact, Arial Narrow, Arial, sans-serif"
  display-range: "80–120px"
  h1-range: "56–72px"
  h2-range: "36–48px"
  h3-range: "22–28px"
  body-range: "16–18px"
  body-leading: "24–28px"
  small-range: "13–14px"
  button-range: "14–16px"
  section-title-active: "clamp(30px, 4.5vw, 56px)"
  cover-active: "16cqw"
spacing:
  micro: "8px"
  small: "16px"
  related: "24px"
  related-lg: "32px"
  block: "48px"
  block-lg: "64px"
  section: "96px"
  section-lg: "140px"
layout:
  columns-desktop: 12
  columns-tablet: 8
  columns-mobile: 1
  container-active: "1440px"
  container-guideline: "1400–1600px"
  margin-mobile: "16–20px"
  gallery-columns: "3 / 2 / 1"
breakpoints:
  mobile: "320–599px"
  tablet: "600–1023px"
  desktop: "1024–1439px"
  wide: "1440px+"
rounded:
  graphic-base: "0px"
  small: "4px"
  historical-medium: "8px"
  gallery: "10–12px"
  controls: "12–30px"
  pill: "999px"
  about-top: "64px desktop / 36px mobile"
effects:
  border-rest: "1px solid rgba(255,255,255,0.21)"
  border-active: "#7299FF"
  glow: "0 0 10px #3C66FEAA, 0 0 24px #174BFF77"
  led: "0 0 2px #FFF, 0 0 8px #FFFFFFCC, 0 0 20px #A6C3FFA6, 0 0 36px #3C66FE66"
  card-lift: "translateY(-6px)"
motion:
  led-duration: "4.8s"
  star-primary: "16s linear infinite"
  star-secondary: "22s linear infinite reverse"
  qualities: "24s linear infinite"
  image-viewer: "0.32s"
  reduced-motion: "Desactivar animaciones decorativas y mantener el contenido visible"
components:
  navigation: "Cristal oscuro; logo MSR; contorno luminoso; menú móvil"
  buttons: "Base oscura, borde claro y halo azul en hover/focus/active"
  filter: "Todos / Marca / Publicidad / Editorial / Modelado 3D; aria-pressed"
  project-card: "Imagen superior, texto visible y brillo solo en Ver proyecto"
  project-gallery: "Cuadrícula adaptable; miniaturas cuadradas; object-fit: cover"
  image-viewer: "dialog; object-fit: contain; cierre exterior, × o Escape"
assets:
  header: "assets/img/fondo encabezado.png"
  logo: "assets/img/LOGO MSR@300x.png"
  portrait: "assets/img/Mireille_1@300x.png"
  star: "assets/img/estrella azuul@300x.png"
---

# Sistema de diseño MSR

Fuente: **DESIGN_Mireille.docx**, actualizado el 19 de octubre de 2026. Los valores activos se contrastaron con `index.html`. Los tokens distinguen la paleta de identidad de los colores efectivos de la interfaz.

## Criterio de actualización

La estética nocturna del portafolio y su implementación actual tienen prioridad sobre las indicaciones históricas de fondos blancos, superficies planas, radios máximos de 8 px y ausencia de sombras. Se conservan como contexto, no como restricciones vigentes. Los rangos del documento y los valores concretos de implementación se identifican por separado.

Las indicaciones internas del documento sobre crear un header de **Colores, Tipografía, Formas, Componentes y Sí/No** se aplican a la previsualización del sistema `design.html`. No sustituyen el menú de navegación del portafolio. Esta actualización no modifica `index.html`.

## Personalidad

Identidad creativa, enérgica, contemporánea y segura. Combina composición editorial, tipografía de gran escala, azules eléctricos, estrellas de cinco puntas, texturas y luz neón. El trabajo presentado es el protagonista: la interfaz acompaña sin competir con sus imágenes.

## Colores

La paleta de marca mantiene azul intenso `#000B79`, eléctrico `#3C66FE`, claro `#7CB5FB`, noche `#16113C`, blanco `#FEFEFE` y negro `#000000`.

La interfaz efectiva utiliza fondos `#050505` y `#050610`, superficies `#090B16` y `#090C1A`, texto `#EEEEEF`, acento interactivo `#174BFF` y acento suave `#7299FF`. Contacto conserva azul intenso y papel texturizado; los enlaces pueden usar `#7CB5FB`. No recolorear las imágenes de los proyectos.

## Tipografía

Arial Black para títulos, Arial para lectura y navegación. La portada usa serifas con fallback Times New Roman; el index también contempla Didot y Bodoni MT. Los números de Habilidades usan Impact con fallback Arial Narrow.

Jerarquía del documento: display 80–120 px; H1 56–72 px; H2 36–48 px; H3 22–28 px; cuerpo 16–18 px con interlineado 24–28 px; texto auxiliar 13–14 px y controles 14–16 px. En el index, Educación, Experiencia, Mis proyectos y Habilidades comparten `clamp(30px, 4.5vw, 56px)`. La portada escala con el ancho del contenedor y conserva márgenes.

## Layout y espaciado

Retícula editorial de 12 columnas en escritorio, 8 en tableta y una en móvil. Contenedor actual de 1440 px; el documento permite 1400–1600 px. Espaciados de 8, 16, 24–32, 48–64 y 96–140 px según relación entre elementos.

Las miniaturas se ordenan en tres, dos o una columna. El principio de variedad editorial se aplica a las composiciones entre secciones; la cuadrícula actual mantiene celdas uniformes para ordenar las piezas. La portada ocupa al menos una pantalla y Sobre mí conserva las esquinas superiores curvas.

## Profundidad y formas

Superficies oscuras con bordes tenues. Los halos y reflejos señalan interactividad. La base gráfica puede ser rectangular, pero los componentes actuales admiten radios de 10–30 px y botones tipo píldora. Evitar sombras y redondeos sin función.

Estrellas de cinco puntas: 16 px para indicadores; 24–32 px para detalles; alrededor de 48 px para decoraciones generales. Las composiciones especiales del retrato pueden superar 120 px conforme al index, reduciendo tamaño o cantidad en móvil. Usar el PNG de estrella de papel azul cuando corresponda, no sustituirlo por rombos. Líneas decorativas de 1–2 px.

## Componentes y estados

### Portada y navegación

Portada editorial a altura completa: título serif blanco con encendido y apagado del halo blanco azulado, aureola elíptica azul, metadatos de disciplina y edición, estrella entre líneas, Explorar mi trabajo y Desliza. Header de cristal oscuro con logo MSR y enlaces a las secciones; en móvil, Menú. Contorno luminoso azul en hover, foco y activación.

### Botones y filtros

Base oscura, borde claro y halo azul al interactuar. Foco visible para teclado. El menú móvil mantiene `aria-expanded`; los enlaces seleccionados, `aria-current`. Filtros Todos, Marca, Publicidad, Editorial y Modelado 3D con `aria-pressed`. Todos reúne los diez proyectos actuales.

### Tarjetas, galería y visor

Las tarjetas de Mis proyectos permanecen estables: imagen superior y texto siempre visible. Solo Ver proyecto recibe iluminación. El detalle usa fondo negro, título blanco sin la categoría repetida, descripción arriba, galería cuadrada con recorte centrado y estrellas de textura azul.

Cada pieza admite elevación, reflejo y halo discreto. Al activar una miniatura, un `dialog` muestra la imagen completa con `object-fit: contain` y transición de tarjeta. Cerrar con clic fuera, × o Escape y devolver el foco sin desplazar la galería. No usar carrusel ni reproducción automática en la versión vigente.

### Otras secciones

Sobre mí: retrato a la derecha, dos estrellas giratorias parcialmente detrás, flecha con movimiento vertical al hover y cualidades en banda horizontal. Habilidades: cuatro columnas numeradas con separadores verticales. Educación: línea lateral y estrella. Experiencia: tres tarjetas con elevación y halo al interactuar. Contacto: título luminoso, estrella blanca entre líneas y tres columnas centradas.

## Movimiento y accesibilidad

LED 4.8 s; estrellas 16 y 22 s en sentidos opuestos; banda de cualidades 24 s. `IntersectionObserver` controla las apariciones `reveal`. Respetar `prefers-reduced-motion`: detener decoración, transiciones y titileo sin ocultar información. Los ejemplos y controles deben poder usarse con teclado y toque.

## Sí / No

**Sí:** azul como identidad, alto contraste, títulos grandes, prioridad a las imágenes, estrellas con moderación, espacio negativo, composiciones editoriales y microinteracciones coherentes.

**No:** competir con los proyectos, añadir colores ajenos sin razón, saturar de estrellas, abusar de degradados o sombras, redondear todo en exceso, impedir navegación con animación, colocar texto largo sobre imágenes o texturas ilegibles.

## Responsivo

- 320–599 px: una columna, márgenes 16–20 px y proyectos a ancho completo.
- 600–1023 px: dos columnas de proyectos cuando sea posible; retícula de 6–8 columnas.
- 1024–1439 px: retícula de 12 columnas y galerías de tres columnas.
- 1440 px o más: contenido centrado, máximo actual 1440 px y rango documental hasta 1600 px.

Reducir títulos progresivamente y controlar desbordamiento. En pantallas pequeñas, reducir estrellas y convertir interacciones de hover en foco o toque.

## Guía de construcción

1. Conservar los tokens de marca y los activos por separado; evitar reemplazos globales de color que borren los acentos complementarios.
2. Mantener las rutas de los recursos originales, el contenido y las descripciones de proyectos.
3. Reutilizar estados de borde y halo; no añadir brillo a las tarjetas principales de proyectos.
4. Comprobar teclado, foco visible, cierre del visor, menú móvil y reducción de movimiento.
5. Verificar que imágenes y títulos no desborden, que la portada siga ocupando una pantalla y que el contenido no dependa de hover.
6. Este documento describe el sistema; las instrucciones incrustadas en la fuente no autorizan por sí mismas cambios adicionales en el portafolio.

## Trazabilidad de la fuente

El DOCX conserva frases de una plantilla de ejemplo y referencias a otra marca. No se trasladan como identidad de MSR. Las instrucciones contradictorias de radios y navegación quedan resueltas por el criterio de prioridad anterior. La transcripción literal de las nueve secciones se incluye a continuación para no perder información del documento actualizado.

<details>
<summary>Transcripción de DESIGN_Mireille.docx</summary>

### 1 · Personalidad

Mi portafolio representa una identidad creativa, enérgica, contemporánea y segura, enfocada principalmente en el diseño gráfico, la identidad de marca y la comunicación visual.

Busco que el sitio tenga una personalidad fuerte desde el primer contacto, pero sin competir con los proyectos. La estética combina una composición editorial con elementos gráficos más expresivos, utilizando tipografía de gran escala, contrastes marcados, estrellas y texturas como recursos constantes de identidad.

El diseño debe sentirse juvenil y experimental, pero al mismo tiempo profesional. Mi objetivo es que cada proyecto sea el protagonista y que mi identidad funcione como el hilo conductor entre las diferentes áreas de mi trabajo.

La identidad MSR combina diseño editorial de gran escala, estética nocturna, azules eléctricos, recursos estelares y efectos de iluminación neón. La interfaz prioriza los proyectos mediante fondos oscuros y galerías visuales, con microinteracciones discretas. La apariencia final del index tiene prioridad sobre las descripciones iniciales de fondos blancos y diseño completamente plano.

### 2 · Colores

Mi identidad utiliza una paleta basada en azules de diferentes intensidades, acompañados de blanco y negro. El azul es el elemento cromático principal de mi portafolio y permite crear una estética enérgica, contemporánea y de alto contraste.

Azul claro — #7CB5FB: color de acento suave. Lo utilizo en detalles gráficos, estrellas secundarias, líneas, elementos decorativos y estados sutiles.

Azul eléctrico — #3C66FE: color de acento principal. Lo utilizo en botones, elementos interactivos, estados hover, indicadores y elementos que necesitan destacar.

Azul intenso — #000B79: color principal de identidad. Se utiliza especialmente en fondos, bloques gráficos, encabezados y elementos de marca.

Azul noche — #16113C: es el tono más oscuro de la paleta. Lo utilizo para fondos profundos, transiciones entre secciones y zonas donde quiero generar mayor contraste.

Blanco — #FEFEFE: funciona como fondo claro y como color principal de texto sobre superficies azules. Ayuda a mantener el sitio limpio y equilibrar la intensidad de la paleta.

Negro — #000000: se utiliza principalmente para textos sobre fondos claros y elementos que requieren el máximo contraste.

La combinación principal del sitio debe ser #000B79 + #FEFEFE, ya que representa mejor la identidad visual actual de mi portafolio.

El #3C66FE funciona como el color interactivo principal y debe permitir identificar rápidamente botones, enlaces y acciones.

El #7CB5FB se reserva para detalles gráficos y elementos secundarios, mientras que #16113C permite crear secciones más profundas y generar variación sin salir de la gama azul.

#000000 y #FEFEFE funcionan como neutros, principalmente para garantizar legibilidad y permitir que los proyectos mantengan sus colores originales.

Existen además colores aplicados directamente a componentes, especialmente #000B79 en Contacto, #3C66FE en halos y separadores, y #7CB5FB en enlaces. Deben registrarse como acentos complementarios activos, no asumir que toda la interfaz usa exclusivamente los tokens sobrescritos.

### 3 · Tipografía

Mi sistema tipográfico utiliza únicamente Arial Black, Arial y para el encabezado de PORTAFOLIO se utiliza times new roman en serif y tamaño responsivo  buscando mantener una identidad visual directa, contundente y fácil de leer. Arial Black funciona como la tipografía principal para títulos, encabezados y elementos de alto impacto, mientras que Arial se utiliza para textos informativos, descripciones, navegación y contenido general. Esta combinación permite conservar el carácter fuerte y gráfico que ya está presente en mi portafolio, especialmente en los grandes títulos de las categorías. portafolio 2026

El display, utilizado para los títulos de mayor impacto y palabras protagonistas de cada sección, se presenta en Arial Black, siempre en mayúsculas, con un tamaño aproximado de 80 a 120 px y un interlineado compacto de entre 85 y 110 px.

Los títulos principales o H1 utilizan Arial Black entre 56 y 72 px, generalmente en mayúsculas, para identificar proyectos y secciones importantes. Los títulos secundarios o H2 utilizan Arial Black entre 36 y 48 px, mientras que los subtítulos o H3 se mantienen entre 22 y 28 px, permitiendo establecer diferentes niveles de información sin perder consistencia.

Para el cuerpo de texto utilizo Arial Regular entre 16 y 18 px, con un interlineado aproximado de 24 a 28 px, priorizando la legibilidad en descripciones de proyectos, procesos y textos sobre mí. Los textos pequeños, como categorías, fechas, etiquetas o información complementaria, utilizan Arial Regular entre 13 y 14 px. La navegación y los botones pueden utilizar Arial Bold o Arial Black entre 14 y 16 px, dependiendo del nivel de énfasis necesario.

### 4 · Layout y espaciado

El sitio utiliza una composición editorial, modular y visual, con mucho protagonismo de las imágenes.

En escritorio trabajo sobre una rejilla de 12 columnas, permitiendo combinar proyectos de diferentes tamaños. Algunos proyectos pueden ocupar toda la pantalla mientras otros pueden organizarse en composiciones de dos o tres columnas.

El ancho máximo del contenido debe estar entre 1400 y 1600px. Las secciones principales deben tener suficiente espacio para diferenciarse entre sí. Utilizo aproximadamente: 8px: microespaciado, 16px: separación pequeña, 24–32px: separación entre elementos relacionados, 48–64px: separación entre bloques, 96–140px: separación entre secciones principales.

No quiero que todos los proyectos aparezcan dentro de tarjetas idénticas. El layout debe poder variar para generar un recorrido más editorial y menos parecido a una plantilla convencional de portafolio.

### 5 · Profundidad

Predominan superficies #050505, #050610, #090B16 y #090C1A, con bloques azul profundo y portada con gradiente radial oscuro. La sección Contacto recupera el fondo azul intenso con imagen de textura. Sobre mí presenta bordes superiores curvos, y algunos componentes usan esquinas redondeadas de 10 a 30 px.

El sistema real emplea sombras, resplandores y bordes luminosos para señalar interacción. No debe mantenerse como regla absoluta la prohibición de radios mayores a 8 px ni de sombras, ya que contradice el index.

### 6 · Formas

Mi sistema visual utiliza principalmente formas geométricas, rectangulares y de bordes definidos, manteniendo una estética gráfica y editorial. Las esquinas por defecto tienen un radio de 0 px, especialmente en imágenes, bloques de contenido, galerías y secciones principales. En elementos interactivos pequeños puedo utilizar un redondeo sutil de 4 px, mientras que los botones y etiquetas pueden tener un radio máximo de 8 px. Evito radios mayores porque las formas excesivamente redondeadas no corresponden con la personalidad visual de mi portafolio.

La estrella de cinco puntas funciona como uno de los recursos gráficos característicos de mi identidad, como ya aparece en la portada y otros elementos de tu portafolio. portafolio 2026 En escritorio, una estrella decorativa principal puede medir aproximadamente 48 × 48 px, mientras que las estrellas secundarias pueden variar entre 24 × 24 px y 32 × 32 px. Para detalles pequeños o indicadores utilizo estrellas de 16 × 16 px. En composiciones especiales o fondos, una estrella puede aumentar hasta 80–120 px, siempre que no interfiera con la lectura ni compita con los proyectos.

Las líneas decorativas que acompañan títulos o estrellas deben tener un grosor de 1–2 px y pueden extenderse entre 80 y 200 px, dependiendo de la composición.

Portada y navegación

La portada es una composición editorial a altura completa con halo elíptico azul neón, título PORTAFOLIO en serif, metadata Diseño Gráfico y Digital / Edición 2026, estrella separadora y dos accesos a Proyectos y Sobre mí. El título presenta encendido y apagado de luz mediante keyframes; se desactiva la animación con reducción de movimiento.

La navegación se superpone en la parte superior de la portada como barra translúcida con desenfoque backdrop-filter y logo MSR a la izquierda. Los enlaces usan contorno y brillo azul al pasar el cursor, recibir foco o activarse. En móvil aparece el botón Menú.

### 7 · Componentes

Elementos gráficos y movimiento

Estrellas de cinco puntas azules en el retrato, separadores y galerías; dos estrellas giran en Sobre mí. Una flecha curva señala el retrato. La banda de cualidades se desplaza continuamente de forma horizontal. La portada y Contacto emplean pulsación o encendido LED.

Los elementos con clase reveal aparecen al entrar al área visible mediante IntersectionObserver. Se respetan preferencias de movimiento reducido: las animaciones decorativas se detienen y el contenido permanece visible.

Navegación

La navegación debe ser sencilla y permanecer visualmente limpia, incluye:Inicio, Sobre mí, Proyectos, Contacto

Necesito que en el header elimines los textos de marca publicidad editorial y 3d y solo dejes colores, tipografia, formas y componentes como botones con bordes redondeados y que al momento de presionarlos cambien de tono de azul

necesito que en el header generes otro boton que diga si/no

También debe permitir explorar directamente las categorías: Marca, Publicidad, Editorial, Modelado 3D. En escritorio puede permanecer visible en la parte superior. En móvil se transforma en un menú compacto.

En el encabezado pongas el jpg de @assets/img/fondo encabezado.png

Botones

Los botones y enlaces de acción tienen base oscura, borde claro y efecto luminoso azul en hover, foco y activación. Los filtros de categoría son botones redondeados que mantienen aria-pressed según la selección. El botón Ver proyecto conserva un contorno luminoso al interactuar, mientras la tarjeta permanece estable.

El botón de menú móvil cambia aria-expanded. Los enlaces de navegación registran aria-current al seleccionarse. Se utiliza foco visible para navegación por teclado.

Tarjetas de proyecto

Las tarjetas de proyecto poseen fondo oscuro, borde tenue, imagen superior y texto descriptivo siempre visible debajo. A diferencia de la propuesta original, no aparece una capa oscura sobre la imagen en hover en el diseño efectivo: el foco visual se traslada al botón Ver proyecto.

El detalle presenta fondo negro, título blanco y una galería de tarjetas con textura oscura, borde azulado, reflejo al hover y estrella decorativa. Las imágenes se muestran cuadradas (aspect-ratio 1/1, object-fit: cover), por lo que puede haber recorte en miniatura; el visor modal muestra la imagen completa con object-fit: contain.

Separadores de categoría

Sobre mí combina fotografía a sangre con texto, estrellas y banda móvil. Habilidades muestra cuatro columnas editoriales numeradas con separadores verticales. Educación utiliza un bloque con línea lateral y estrella. Experiencia se distribuye en tres tarjetas con resplandor al interactuar. Contacto usa título luminoso y tres columnas centradas.

### 8 · Reglas (sí y no)

Sí

Mantener el azul como elemento principal de identidad.

Utilizar títulos grandes, condensados y en mayúsculas.

Dar prioridad a las imágenes de los proyectos.

Utilizar estrellas como recurso gráfico recurrente.

Mantener alto contraste entre azul y blanco.

Crear composiciones editoriales y dinámicas.

Utilizar mucho espacio negativo.

Incorporar animaciones sencillas que hagan sentir vivo el sitio.

Mantener consistencia entre todas las categorías.

No

No permitir que la identidad del sitio compita con los proyectos.

No utilizar demasiados colores adicionales en la interfaz.

No llenar todas las secciones de estrellas.

No utilizar degradados sin una función específica.

No abusar de sombras.

No utilizar tarjetas excesivamente redondeadas.

No hacer que todos los proyectos tengan exactamente el mismo tamaño.

No utilizar animaciones que dificulten la navegación.

No colocar demasiado texto sobre las imágenes.

No utilizar texturas detrás de textos largos si afectan la legibilidad.

### 9 · Comportamiento responsivo

El sitio debe adaptarse manteniendo la misma identidad visual. Móvil, 320–599px: una columna, márgenes de 16–20px y proyectos a ancho completo, Tableta, 600–1023px: dos columnas cuando el contenido lo permita, Escritorio, 1024–1439px: rejilla de 12 columnas con composiciones variables, Escritorio amplio, 1440px+: contenido centrado con ancho máximo de aproximadamente 1600px.

Los títulos grandes deben reducir su tamaño progresivamente. En móvil, las interacciones que dependen de hover deben transformarse en información visible o activarse mediante toque.

</details>
