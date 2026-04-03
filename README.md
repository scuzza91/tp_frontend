# PFO1 — Landing de portafolio personal (HTML y CSS)

Trabajo práctico individual: página única de presentación tipo portafolio, maquetada solo con HTML5 semántico y CSS3, cumpliendo la consigna de la Práctica Formativa Obligatoria 1.

**URL de GitHub Pages (completar tras publicar):** `https://<usuario>.github.io/<repo>/`

---

## Checklist — Práctica Formativa Obligatoria 1

### Estructura del proyecto

- [x] Archivo `index.html` ubicado en la raíz.
- [x] Carpeta `css` que contenga el archivo `styles.css`.
- [x] (Opcional) Carpeta `img` para recursos gráficos — *se usaron imágenes remotas con URLs fijas (picsum.photos).*
- [x] Archivo `README.md` creado, que incluya una breve descripción del TP y este checklist.

### Repositorio y publicación

- [ ] Repositorio en GitHub creado.
- [ ] Proyecto subido al repositorio.
- [ ] Proyecto publicado utilizando GitHub Pages.
- [ ] En el `README.md` se indica la URL de GitHub Pages.

### Uso de Google Fonts

- [x] Enlace a Google Fonts incluido en la sección `head` del HTML.
- [x] La tipografía importada se aplica en el sitio.
- **¿Por qué elegiste esa fuente?** Plus Jakarta Sans es muy legible en pantalla, neutra y profesional; funciona bien en títulos y cuerpo sin recargar el portafolio.

### HTML

- [x] El documento inicia con la declaración DOCTYPE y usa el atributo `lang="es"`.
- [x] Se han incluido las metaetiquetas obligatorias: charset y viewport.
- [x] Se ha definido un título descriptivo.
- [x] Se han vinculado correctamente el archivo CSS y el enlace a Google Fonts.

**Secciones obligatorias en `main`:**

- [x] Barra de navegación (`nav`) presente y contiene al menos 3 enlaces.
- [x] Se han insertado al menos 4 comentarios explicativos en el código HTML.

### CSS

- [x] Existe el archivo `styles.css` con estilos personalizados.
- [x] Se utilizan selectores basados en clases e identificadores.
- [x] La tipografía importada desde Google Fonts se aplica correctamente en los elementos (vía `body` y variables).

**Layout y organización:**

- [x] Se ha organizado el layout (especialmente en la sección `tarjetas`) utilizando **CSS Grid** (`display: grid` en `.cards-grid`). La navegación usa **Flexbox**.
- **¿Qué ventajas encontraste al utilizar Flexbox o Grid?** Grid distribuye las tarjetas en columnas automáticas con `auto-fit` y `minmax`, sin media queries complejas; Flexbox en el nav y en el footer alinea y ordena ítems en una sola fila con `wrap` en móvil.

**Estilización de componentes:**

- [x] Se han personalizado los estilos de tablas, botones, enlaces y formularios.
- [x] Se han ajustado las dimensiones de imágenes y contenedores utilizando unidades relativas (`%`, `rem`, `clamp`, `min()`).
- [x] Se ha implementado al menos una animación o transición (hover en `.card` y `.btn--primary`).
- **¿Qué animación o transición implementaste y por qué?** Transición en tarjetas (`transform` y `box-shadow` al hover) y en el botón de envío, para dar feedback visual sin distraer y reforzar que los bloques son interactivos o clicables.

### Consideraciones adicionales

- [x] El diseño es responsivo (rejillas fluidas, `clamp`, `flex-wrap`, ancho máximo en `rem`).
- [x] Buenas prácticas de accesibilidad: `alt` en imágenes, `aria-labelledby` en secciones, labels asociados a inputs.
- [x] Comentarios en CSS sobre decisiones de diseño (fuente, grid, transiciones).

---

## Cómo ver el proyecto en local

Abrir `index.html` en el navegador o usar un servidor estático, por ejemplo:

```bash
npx serve .
```

---

## Entrega en el foro

1. Link al repositorio GitHub.
2. Link al sitio publicado (según consigna del curso: GitHub Pages y/o Vercel).
