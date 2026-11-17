# Guía de estilos — Lola

Valores tomados del mockup de Figma (`design/`) y de las variables definidas en `src/css/styles.css`.

## 1. Colores

| Nombre | HEX | Uso |
|---|---|---|
| Crema (fondo) | `#F7F4EB` | Fondo general de la página |
| Blanco cálido | `#FFFEFA` | Header, tarjetas y secciones claras |
| Verde oscuro | `#163D2C` | Títulos, footer, banda de promoción |
| Dorado | `#D9BD85` | Botones principales |
| Dorado hover | `#C8A96B` | Botón al pasar el cursor |
| Texto | `#24352C` | Texto principal |
| Texto secundario | `#69766C` | Descripciones y textos de apoyo |
| Borde | `#E7E0D2` | Bordes de tarjetas y separadores |
| Beige producto | `#EEE5D2` | Fondo de la imagen de producto |
| Beige sección | `#EEE9DC` | Fondo de materias primas |
| Dorado texto | `#8B7044` | Etiquetas superiores (eyebrow) |
| Lima promoción | `#B7FE00` | Banner de descuento (tomado del mockup) |

## 2. Tipografías

| Familia | Uso | Pesos |
|---|---|---|
| **DM Serif Display** | Títulos (h1, h2) | 400 |
| **Inter** | Párrafos y texto general | 400, 500, 600, 700 |
| **Manrope** | Navegación, botones, etiquetas, títulos pequeños | 400–800 |

Se cargan desde Google Fonts. Alternativas: `serif` y `sans-serif`.

## 3. Tamaños de texto

| Elemento | Tamaño | Detalle |
|---|---|---|
| h1 | 48–76 px | `clamp(48px, 6vw, 76px)`, interlineado 1.12 |
| h2 | 34–48 px | `clamp(34px, 4vw, 48px)`, interlineado 1.12 |
| h3 (tarjetas) | 16–17 px | Manrope 700 |
| Párrafo | 12–15 px | Inter, interlineado 1.65 |
| Navegación | 11 px | Manrope 600 |
| Botón | 11–12 px | Manrope 800 |
| Etiqueta (eyebrow) | 10 px | Manrope 800, espaciado de letras 2 px |

## 4. Espaciados y medidas

| Elemento | Valor |
|---|---|
| Ancho máximo del contenido | 1120 px (margen lateral 20 px) |
| Espacio vertical de sección | 90 px (65 px en móvil) |
| Altura del header | 82 px |
| Separación entre tarjetas | 16–18 px |
| Separación entre columnas | 75–85 px |
| Radio de bordes | 4 px (botones, campos), 6–8 px (tarjetas) |

## 5. Componentes

- **Header:** logo a la izquierda, navegación central y botón «Contáctanos» a la derecha. Fondo blanco cálido con borde inferior.
- **Botón principal:** fondo dorado `#D9BD85`, texto verde oscuro, alto mínimo 48 px, se eleva 2 px al pasar el cursor.
- **Enlace de texto:** Manrope 800, color verde oscuro, flecha `→`.
- **Tarjeta de producto:** imagen sobre fondo beige, categoría, nombre, descripción y enlace; borde `#E7E0D2`, radio 7 px; 4 columnas en escritorio.
- **Materia prima:** tarjeta blanca con ícono, título y descripción; 4 columnas.
- **Banner de promoción:** fondo lima del mockup con título «Hoy un 20 % de descuento» y botón de compra.
- **Banda de promociones:** fondo verde oscuro, texto crema y botón claro.
- **Formulario:** etiquetas verdes, campos con borde `#DED8CA` y radio 4 px; el foco cambia el borde a `#9B865E`.
- **Footer:** fondo verde oscuro; títulos dorados, enlaces claros y línea de derechos reservados.

## 6. Puntos de quiebre (responsive)

| Ancho | Cambio |
|---|---|
| ≤ 980 px | Navegación en una segunda fila; productos en 2 columnas |
| ≤ 650 px | Una columna en secciones principales; navegación con scroll horizontal |
| ≤ 390 px | Productos y materias primas en 1 columna |
