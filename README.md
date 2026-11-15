# landing-fads-prototipo
Prototipo académico de landing para el Plan de Marketing de Fred Astaire Dance Studios Santiago. No es el sitio oficial.

## Fotos y videos

La página es de pestañas y lee sus archivos desde [`media`](media/). Para cambiar uno, suban otro con el mismo nombre.

| Pestaña | Archivos |
|---|---|
| Inicio (tres videos a la vez, sin sonido) | `portada-1.mp4` a `portada-3.mp4`, con su imagen `portada-N.jpg` |
| Clases | `clase-privada.mp4` y `clase-privada-2.mp4` (se reproducen uno tras otro), `clase-grupal.mp4`, `estudio-2.jpg` |
| Fiestas, foto grupal | `evento-2.jpg` |
| Fiestas (cada una aparece al subir su video; la lista `FIESTAS` de [`index.html`](index.html) define título y archivo) | `fiesta-halloween.mp4`, `fiesta-mexico.mp4`, `fiesta-espana.mp4` |
| Instructores | una foto por persona, con el nombre de archivo que figura en las listas `INSTRUCTORES` y `PRACTICANTES` de [`index.html`](index.html) (por ejemplo `profe-jose-luis-tejo.jpg`) |
| Eventos → Próximos eventos | `proximo-1.jpg`, … (hasta 20) |
| Eventos → Shows | `show-1.jpg`, `show-2.jpg`, … (hasta `show-20.jpg`) |
| Eventos → Competencias | fotos `competencia-1.jpg`, … y videos `competencia-video-1.mp4`, … (hasta 20 de cada uno) |
| Eventos → Eventos y estudio | `evento-1.jpg`, … (hasta 20), más `estudio-1.jpg` a `estudio-3.jpg` |
| Eventos → Videos (la pestaña aparece al subir el primero) | `video-1.mp4`, … (hasta 20) |

Para agregar una foto o video a Eventos basta subir el siguiente número; la página lo muestra sola. Los pies de foto se editan en la lista `PIES` de [`index.html`](index.html).

Origen de las fotos y videos: publicaciones de Instagram de @fadssantiago y de alumnos, entregadas por el equipo el 2026-11-15. Sin verificar: autorización de las personas que aparecen.

## Changelog

- 2026-11-15: primera versión de la landing "¿Me concedes esta pieza?" ([`index.html`](index.html)).
- 2026-11-15: paleta de la marca (negro, blanco y dorado) y portada con video opcional `media/portada.mp4` ([`index.html`](index.html)).
- 2026-11-15: página por pestañas, negro, blanco y dorado, portada con tres videos y fotos reales ([`index.html`](index.html), [`media`](media/)).
- 2026-11-15: galerías de Eventos que detectan solas los archivos numerados, pestaña Videos y videos de portada en mayor calidad ([`index.html`](index.html)).
- 2026-11-15: videos originales en la portada, en Tu primera clase y en Eventos → Videos ([`media`](media/)).
- 2026-11-15: agrega `competencia-4.jpg` (foto de @karin.shots) y `video-3.mp4` (reel de @openchilechampionships), ambos tomados de Instagram con crédito en el pie ([`media`](media/)).
- 2026-11-15: corrige los videos de portada que se salían de su espacio y tapaban el texto en pantallas medianas ([`index.html`](index.html)).
- 2026-11-15: pestaña Fiestas temáticas (México y España; Halloween aparece al subir `fiesta-halloween.mp4`) y fiesta de México en el video central de la portada ([`index.html`](index.html)).
- 2026-11-15: video del Mini Match en Eventos → Competencias ([`media/competencia-video-1.mp4`](media/competencia-video-1.mp4)).
- 2026-11-15: elimina la pestaña Tu primera clase; videos en Clases privadas y grupales; foto grupal en Fiestas; nuevo video 1 de portada; todos los videos reexportados a la resolución de su fuente ([`index.html`](index.html), [`media`](media/)).
- 2026-11-15: segundo video en Clases privadas ([`media/clase-privada-2.mp4`](media/clase-privada-2.mp4)).
- 2026-11-15: la foto grupal de Fiestas se muestra completa, sin cortar a las personas ([`index.html`](index.html)).
- 2026-11-15: sub-pestaña Próximos eventos con el afiche del Open Chile Championships 2026, tomado de Instagram con crédito ([`media/proximo-1.jpg`](media/proximo-1.jpg)).
- 2026-11-15: equipo actualizado a 10 instructores y 3 practicantes, según lo informado por el equipo del proyecto; sin verificar apellidos y grafías ([`index.html`](index.html)).
- 2026-11-15: fotos y nombres completos de seis instructores, tomados de los nombres de archivo entregados por el equipo ([`media`](media/)).
- 2026-11-15: fotos de cinco personas más del equipo y nombre completo de Josefa De la Fuente, según los nombres de archivo entregados ([`media`](media/)).
- 2026-11-15: foto de José Luis Tejo ([`media/profe-jose-luis-tejo.jpg`](media/profe-jose-luis-tejo.jpg)).
