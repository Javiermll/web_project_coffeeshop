# Triple Espresso — Cafeteria Triple Peaks

Sitio web estático para la cafetería de especialidad "Triple Espresso", desarrollado como proyecto de formación en el bootcamp TripleTen.

## Descripcion / Objetivo

Página web de una cafetería universitaria/coworking que informa a sus usuarios sobre el menú en video, permite reservar una mesa mediante un formulario interactivo y presenta los datos de contacto del local.

## Tecnologias y herramientas

- HTML5 (etiquetas semánticas y meta tags)
- CSS3 con Flexbox y posicionamiento
- Metodología BEM para nomenclatura de clases
- Google Fonts (Inter + Noto Serif) integradas vía `@import`
- Pseudoclases CSS para estilos interactivos (`:hover`, `:focus`)
- `<iframe>` para incrustar videos de YouTube
- Formularios HTML5 con validación nativa
- Git / GitHub para control de versiones

## Funcionalidades principales

- **Sección de recetas en video:** 2 videos de YouTube incrustados con `<iframe>` que muestran recetas de café (Aeropress y cafetera francesa), con leyenda de duración estimada.
- **Formulario de reserva de mesa:** campos para nombre, número de comensales (1-8), fecha y hora (`datetime-local`), email y checkbox de aceptación de términos, con validación nativa HTML5.
- **Navegación con anclas:** menú que enlaza a `#recipes`, `#reservation` y `#footer`.
- **Footer con redes sociales:** logo, horario de apertura y enlaces a Facebook e Instagram con efecto hover.

## Rol

Proyecto individual: diseño completo del HTML, estructura modular CSS con `@import`, aplicación de BEM y formularios desde cero.

## Resultado / Impacto

- Formulario de reserva funcional con 4 campos y validación HTML5 nativa.
- 2 videos interactivos de YouTube integrados mediante `<iframe>`.
- CSS modular con separación de bloques por archivos importados desde `pages/index.css`.
- Diseño fiel al brief de Figma, con tipografías personalizadas desde Google Fonts.

## Repositorio

- GitHub: https://github.com/Javiermll/web_project_coffeeshop
