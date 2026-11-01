# Librería de botones

Este proyecto reúne **100 botones hechos con HTML y CSS**, organizados en diez categorías. También incluye cinco ejemplos adicionales que combinan varias clases.

La idea es aprender cómo pequeños cambios en CSS modifican el color, la forma, el texto o el movimiento de un botón. Puedes abrir `index.html` en un navegador para explorar el catálogo.

## Archivos del proyecto

- `index.html`: contiene las categorías y los botones.
- `css/styles.css`: contiene las reglas que dan forma, color y efectos a los botones y a las tarjetas de categorías.
- `img/`: contiene ilustraciones SVG usadas en algunos botones.

El proyecto se construye con HTML y CSS. No necesita JavaScript ni Bootstrap para mostrar el catálogo.

## Cómo se lee la clase de un botón

Un botón puede tener varias clases en el atributo `class`. Cada clase aporta una parte del diseño:

```html
<button type="button" class="btn btn-primary btn-pill btn-grow">
    Primario
</button>
```

- `btn` aplica las reglas que comparten los botones: espacio interior, borde, color base, fuente y cursor.
- `btn-primary` elige la variante azul.
- `btn-pill` hace que el botón tenga forma de píldora.
- `btn-grow` lo hace crecer al pasar el cursor o enfocarlo con el teclado.

Las reglas de cada clase están en `css/styles.css`. En general, el orden de las clases dentro del atributo `class` no decide qué estilo gana: CSS considera la especificidad de los selectores y el orden de las reglas en el archivo.

## Categoría 1. Fundamentos y colores

Practica cómo una variante de color cambia el fondo, el borde y el color del texto.

- **Primario** — `btn btn-primary`: azul principal `#1565C0` con texto blanco.
- **Secundario** — `btn btn-secondary`: gris claro con texto oscuro.
- **Éxito** — `btn btn-success`: verde con texto blanco.
- **Peligro** — `btn btn-danger`: rojo con texto blanco.
- **Advertencia** — `btn btn-warning`: amarillo con texto oscuro.
- **Información** — `btn btn-info`: celeste con texto oscuro.
- **Oscuro** — `btn btn-dark`: fondo oscuro y texto blanco.
- **Claro** — `btn btn-light`: fondo muy claro y texto oscuro.
- **Texto** — `btn btn-text`: parece un enlace; no tiene fondo ni sombra.
- **Personalizado** — `btn btn-custom`: variante morada.

## Categoría 2. Bordes, tamaños y formas

Practica cambios en el borde, las esquinas y las dimensiones, manteniendo el contenido del botón.

- **Contorno** — `btn btn-outline`: fondo transparente, borde y texto azules.
- **Borde grueso** — `btn btn-border-thick`: aumenta el grosor del borde.
- **Borde discontinuo** — `btn btn-border-dashed`: dibuja el borde con guiones.
- **Borde punteado** — `btn btn-border-dotted`: dibuja el borde con puntos.
- **Esquinas redondeadas** — `btn btn-rounded`: redondea las esquinas.
- **Píldora** — `btn btn-pill`: usa un radio grande para formar extremos redondos.
- **Favorito** — `btn btn-circle`: crea un botón circular para una estrella; `aria-label="Favorito"` da nombre al botón para lectores de pantalla.
- **Pequeño** — `btn btn-small`: reduce el relleno y el tamaño de letra.
- **Grande** — `btn btn-large`: aumenta el relleno y el tamaño de letra.
- **Ancho completo** — `btn btn-full`: ocupa todo el ancho disponible.

## Categoría 3. Tipografía y sombras

Practica cómo se presenta el texto y cómo las sombras dan sensación de profundidad.

- **Mayúsculas** — `btn btn-uppercase`: transforma el texto a mayúsculas con CSS.
- **Espaciado** — `btn btn-spaced`: aumenta el espacio entre letras.
- **Negrita** — `btn btn-bold`: hace el texto más grueso.
- **Elegante** — `btn btn-elegant`: usa una fuente con serifas.
- **Subrayado** — `btn btn-underline`: agrega una línea bajo el texto.
- **Sombra suave** — `btn btn-shadow-soft`: añade una sombra discreta.
- **Sombra pronunciada** — `btn btn-shadow-strong`: añade una sombra más grande y oscura.
- **Sombra de color** — `btn btn-shadow-color`: combina el azul con una sombra azul.
- **Relieve** — `btn btn-relief`: mezcla una luz interior con una sombra inferior para sugerir profundidad.
- **Texto brillante** — `btn btn-text-glow`: añade un resplandor celeste alrededor de las letras.

## Categoría 4. Degradados

Un degradado mezcla dos o más colores. Estas variantes practican distintas direcciones y formas de transición.

- **Horizontal** — `btn btn-gradient-horizontal`: mezcla colores de izquierda a derecha.
- **Vertical** — `btn btn-gradient-vertical`: mezcla colores de arriba abajo.
- **Diagonal** — `btn btn-gradient-diagonal`: mezcla colores en diagonal.
- **Tres colores** — `btn btn-gradient-three`: recorre tres colores en línea.
- **Radial** — `btn btn-gradient-radial`: distribuye los colores desde un centro hacia afuera.
- **Atardecer** — `btn btn-gradient-sunset`: mezcla tonos rojos, naranjas y dorados.
- **Océano** — `btn btn-gradient-ocean`: mezcla azul y verde.
- **Pastel** — `btn btn-gradient-pastel`: mezcla tonos rosados y violetas claros.
- **Borde degradado** — `btn btn-gradient-border`: deja el centro claro y aplica el degradado al borde.
- **Degradado interactivo** — `btn btn-gradient-hover`: desplaza el degradado cuando se pasa el cursor o se usa el teclado.

## Categoría 5. Estados e interacción

Algunos estilos reaccionan al cursor, al teclado o al momento en que se presiona el botón.

- **Cambio de fondo** — `btn btn-hover-background`: oscurece el fondo al interactuar.
- **Cambio de texto** — `btn btn-hover-text`: cambia el color de las letras.
- **Cambio de borde** — `btn btn-hover-border`: cambia el color del borde.
- **Sombra al interactuar** — `btn btn-hover-shadow`: muestra una sombra al interactuar.
- **Subrayado interactivo** — `btn btn-hover-underline`: subraya el texto al interactuar.
- **Presionado** — `btn btn-active`: oscurece el fondo mientras se mantiene presionado el botón.
- **Foco destacado** — `btn btn-focus`: muestra un contorno amarillo y un anillo oscuro al llegar con el teclado.
- **Deshabilitado** — `btn btn-disabled`: muestra un botón inactivo; el atributo HTML `disabled` también impide usarlo.
- **Transición lenta** — `btn btn-transition-slow`: cambia de fondo y se eleva lentamente.
- **Transición escalonada** — `btn btn-transition-stagger`: cambia de fondo y posición con un pequeño retraso en el movimiento.

El foco del teclado se puede probar con la tecla **Tab**. El selector `:focus-visible` permite mostrar el indicador cuando se navega con el teclado.

## Categoría 6. Transformaciones

Las transformaciones cambian la escala, la posición o la inclinación del botón al interactuar.

- **Crecer** — `btn btn-grow`: aumenta ligeramente de tamaño.
- **Reducir** — `btn btn-shrink`: disminuye ligeramente de tamaño.
- **Elevar** — `btn btn-lift`: se desplaza hacia arriba.
- **Desplazar** — `btn btn-move-right`: se mueve hacia la derecha.
- **Rotar** — `btn btn-rotate`: gira unos grados.
- **Inclinar** — `btn btn-skew`: inclina el botón y compensa la inclinación del texto para que se lea mejor.
- **Presionar** — `btn btn-press`: se desplaza hacia abajo mientras se mantiene presionado.
- **Perspectiva** — `btn btn-perspective`: combina perspectiva y giro en tres dimensiones.
- **Icono en movimiento** — `btn btn-icon-move`: mueve la flecha hacia la derecha.
- **Combinado** — `btn btn-transform-combined`: combina elevación, crecimiento y sombra.

Las transiciones suavizan los cambios para que no ocurran de golpe.

## Categoría 7. Iconos e imágenes

Practica la posición de iconos y el uso de imágenes decorativas dentro o detrás del botón.

- **Confirmar** — `btn btn-icon-left`: coloca una marca antes del texto. El icono tiene `aria-hidden="true"` porque el texto ya explica la acción.
- **Continuar** — `btn btn-icon-right`: coloca una flecha después del texto.
- **Buscar** — `btn btn-icon-only`: crea un botón solo con lupa; `aria-label="Buscar"` le da un nombre accesible.
- **Descargar** — `btn btn-download`: combina una flecha hacia abajo con el texto.
- **Explorar paisaje** — `btn btn-image-background`: pone una ilustración de fondo.
- **Ver imagen** — `btn btn-image-overlay`: pone una capa oscura sobre la ilustración para destacar el texto blanco.
- **Mi perfil** — `btn btn-avatar`: muestra una imagen redonda junto al texto. La imagen tiene `alt=""` porque es decorativa.
- **Configuración** — `btn btn-icon-separated`: coloca el engranaje en una zona visualmente separada.
- **Imagen al interactuar** — `btn btn-image-hover`: amplía el fondo cuando se pasa el cursor o se enfoca con el teclado.
- **Más información** — `btn btn-icon-reveal`: revela una flecha al interactuar.

Las imágenes usadas como fondos están en `img/`. Por ejemplo, `button-landscape.svg` se carga desde CSS con una ruta relativa a `css/styles.css`.

## Categoría 8. Efectos con pseudoelementos

Los pseudoelementos `::before` y `::after` permiten crear capas decorativas desde CSS, sin agregar elementos adicionales al HTML. En varios botones, `z-index` mantiene el texto por encima de esas capas.

- **Relleno lateral** — `btn btn-fill-left`: una capa de color entra desde la izquierda.
- **Relleno inferior** — `btn btn-fill-bottom`: una capa entra desde abajo.
- **Relleno central** — `btn btn-fill-center`: una capa crece desde el centro hacia los lados.
- **Brillo deslizante** — `btn btn-shine`: una franja clara cruza el botón.
- **Línea inferior** — `btn btn-underline-expand`: una línea crece bajo el texto.
- **Esquinas destacadas** — `btn btn-corners`: dibuja esquinas de color al interactuar.
- **Doble capa** — `btn btn-double-layer`: dos capas de color se acercan desde lados opuestos.
- **Círculo expansivo** — `btn btn-circle-expand`: un círculo de color se expande desde el centro.
- **Borde animado** — `btn btn-border-reveal`: revela un borde alrededor del botón.
- **Corte diagonal** — `btn btn-diagonal-sweep`: una capa diagonal cruza el botón.

## Categoría 9. Animaciones CSS

Las animaciones se definen con `@keyframes`, que describe los pasos de un movimiento. Algunas se repiten y otras empiezan al interactuar.

- **Pulso** — `btn btn-pulse`: crece y vuelve a su tamaño de forma repetida.
- **Latido** — `btn btn-heartbeat`: imita un latido con cambios de escala.
- **Flotante** — `btn btn-float`: sube y baja suavemente.
- **Sacudida** — `btn btn-shake`: se mueve hacia los lados al interactuar.
- **Rebote** — `btn btn-bounce`: rebota al interactuar.
- **Brillo pulsante** — `btn btn-glow-pulse`: aumenta y reduce el resplandor.
- **Degradado en movimiento** — `btn btn-gradient-motion`: anima la posición del degradado.
- **Icono giratorio** — `btn btn-icon-spin`: hace girar el símbolo de flecha circular.
- **Cargando** — `btn btn-loading`: muestra un indicador giratorio y está deshabilitado para representar una espera.
- **Secuencia** — `btn btn-sequence`: ejecuta una secuencia corta de movimiento al interactuar.

La regla `prefers-reduced-motion` detiene varias animaciones si el dispositivo está configurado para reducir el movimiento.

## Categoría 10. Botones de diseño avanzado

Esta categoría combina varias técnicas para crear apariencias más elaboradas.

- **Neón** — `btn btn-neon`: usa fondo oscuro, borde celeste y resplandor que aumenta al interactuar.
- **Cristal** — `btn btn-glass`: usa transparencia, borde claro y desenfoque si el navegador lo admite. Está dentro de `.escenario-cristal`, un fondo azul que permite ver el efecto.
- **Neumórfico** — `btn btn-neumorphic`: usa tonos grises y sombras claras y oscuras para parecer elevado; al presionarlo, las sombras se vuelven interiores. `.escenario-neumorphic` crea el fondo donde se aprecia.
- **Retro 3D** — `btn btn-retro-3d`: usa amarillo, una sombra sólida y un movimiento hacia abajo al presionar.
- **Metálico** — `btn btn-metallic`: combina varios grises en un degradado y deja pasar un brillo.
- **Borde arcoíris** — `btn btn-rainbow-border`: anima un borde con varios colores alrededor de un centro oscuro.
- **Agregar al carrito** — `btn btn-double-text`: cambia el texto visible al pasar el cursor o enfocar. `aria-label` mantiene un nombre accesible estable y el texto alternativo tiene `aria-hidden="true"`.
- **Imagen cinematográfica** — `btn btn-cinematic`: mezcla una ilustración de fondo con una capa oscura para que el texto blanco se lea mejor.
- **Acción premium** — `btn btn-premium`: combina degradado azul-violeta, sombra, icono y una franja de brillo.
- **Diseño original** — `btn btn-original`: combina degradado, forma de píldora, sombra, elevación, crecimiento, brillo deslizante e icono. Este botón reúne técnicas de categorías anteriores.

## Categoría 11. Prueba las combinaciones

Esta sección no suma otros diez botones al catálogo original. Contiene cinco ejemplos extra para practicar cómo se pueden usar varias clases en un solo botón.

- **Primario: píldora y crecimiento** — `btn btn-primary btn-pill btn-grow`: combina el azul, la forma de píldora y el crecimiento al interactuar.
- **Éxito: grande y elevación** — `btn btn-success btn-large btn-lift`: combina el verde, el tamaño grande y la elevación.
- **Peligro: redondeado y sombra** — `btn btn-danger btn-rounded btn-hover-shadow`: conserva el fondo rojo y agrega esquinas redondeadas y sombra. Una regla específica de esta categoría conserva el rojo mientras la clase de sombra cambia la sombra.
- **Contorno: pequeño y cambio de fondo** — `btn btn-outline btn-small btn-hover-background`: empieza transparente y pequeño; al interactuar, cambia al fondo azul oscuro y el texto blanco.
- **Océano: píldora y brillo pulsante** — `btn btn-gradient-ocean btn-pill btn-glow-pulse`: combina el degradado océano, la forma de píldora y un resplandor celeste. Una regla específica conserva el degradado mientras se anima el resplandor.

## Organización visual

En la página, cada categoría es una sección HTML. CSS la muestra como una tarjeta grande; los botones se ordenan en tarjetas pequeñas dentro de una cuadrícula adaptable. Al reducir el ancho de la pantalla, la cuadrícula muestra menos columnas para que los ejemplos sigan siendo fáciles de leer.

El indicador de foco también funciona con el teclado. Prueba presionar **Tab** para recorrer los botones. Los efectos de pasar el cursor se pueden activar con mouse o con el foco del teclado cuando el estilo incluye `:focus-visible`.
