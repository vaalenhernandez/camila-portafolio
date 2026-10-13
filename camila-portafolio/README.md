# Portafolio de Camila González

Sitio web de una sola página: perfil, servicios, proyectos, testimonios, planes y contacto.

## Cómo hacer cambios desde GitHub (sin instalar nada)

1. Abre `index.html` y toca el lápiz (**Edit this file**).
2. Busca el texto que quieres cambiar con Ctrl+F (Cmd+F en Mac) y escríbelo encima.
3. Abajo, toca **Commit changes**. En uno o dos minutos el sitio se actualiza solo.

### Dónde está cada cosa en `index.html`

| Quiero cambiar… | Busca |
|---|---|
| Frase de la portada | `class="lead"` |
| Servicios | `id="servicios"` |
| Videos (título, marca, descripción) | `var R=[` al final del archivo |
| Testimonios | `id="clientes"` |
| Planes y precios | `id="planes"` |
| Formación y habilidades | `id="perfil"` |
| Teléfono / WhatsApp | `3024633657` (aparece en tres lugares) |
| Colores | `:root{` al inicio del archivo |

### Cambiar una foto o una miniatura

Entra a la carpeta `img`, toca **Add file → Upload files** y sube la nueva imagen **con el mismo nombre** (`camila.jpg`, `v1.jpg` … `v6.jpg`). Las miniaturas de los videos se ven mejor en formato vertical 9:16.

### Poner el enlace real de cada video

En `index.html`, dentro de `var R=[`, cada video tiene una línea. Agrega `url:'https://www.instagram.com/reel/…'` y el botón "Ver en Instagram" usará ese enlace.
