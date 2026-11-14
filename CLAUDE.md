# Fundación Hipófisis Venezuela

Página web de una fundación de información y apoyo para pacientes con enfermedades de la hipófisis. Sede fundadora: Servicio de Neurocirugía del Hospital Vargas de Caracas. Nació como proyecto de tesis y debe poder crecer a toda Venezuela. El dueño no es programador.

## Cómo está hecho

- Web estática, **sin instalar nada**: `index.html` (contenido) y `style.css` (colores y diseño). No hay build ni dependencias.
- Para verla: abrir `index.html` en el navegador.
- Colores en variables de `:root` en `style.css` (`--indigo`, `--guayaba`, `--mango`, `--hielo`). Usa esas variables, no colores sueltos.
- Fuentes de Google Fonts: Atkinson Hyperlegible (texto, muy legible) y Bricolage Grotesque (títulos).
- Los textos entre `[corchetes]` con clase `nota` son pendientes por definir con el equipo médico. No los inventes ni los borres sin que te lo pidan.

## Con el dueño

- Responde en español, corto y sin jerga. Primero lo que cambia para él, después el detalle.
- Todo lo que le pidas hacer debe poder hacerse **desde el teléfono**, en pasos numerados. Solo herramientas **gratis**.
- Si algo cuesta dinero (dominio, hosting), requiere una cuenta o publica algo, **pregunta antes**.

## Cómo trabajar

- **Lo más simple que resuelva el pedido.** Sigue siendo HTML + CSS; nada de frameworks, librerías ni JavaScript que nadie pidió.
- **Cambios quirúrgicos.** Toca solo lo necesario y copia el estilo de alrededor.
- **Para pacientes:** lenguaje sencillo y cálido, frases cortas, letra grande, buen contraste. Debe verse bien en un teléfono barato y con mala conexión. Mantén la accesibilidad (`aria-*`, `alt`, foco visible).
- **Comprueba antes de decir «listo»:** abre la página (o haz una captura) en ancho de teléfono. Si algo no se pudo verificar, dilo.
- **Cuida el uso:** una sesión por tema. Al empezar di el nivel del pedido en una línea (fácil → Sonnet, difícil → Opus).

## Límites que no se cruzan

- **Sin permiso del dueño, nunca:** commit, push ni publicar la web.
- **Contenido médico:** solo información general y revisada por el equipo médico. Nada de dosis, tratamientos personalizados ni diagnósticos. Si no hay fuente fiable, déjalo como pendiente `[…]` y avísalo.
- Mantener visibles el aviso de emergencia y el aviso de que la página no reemplaza la consulta médica.
- Nunca datos personales de pacientes. Las historias solo se publican con **permiso por escrito**.
- No decir que es una fundación registrada hasta que el dueño lo confirme.
