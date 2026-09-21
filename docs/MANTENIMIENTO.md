# Mantenimiento y publicación

[Volver al índice](../README.md)

## Una fuente de verdad

Las fichas de `recursos/` son el catálogo. El README aporta navegación y rutas; no mantener copias en hojas de cálculo ni contadores manuales. Las anclas explícitas permiten cambiar un título sin romper las rutas.

Cada categoría incluye un índice de sus fichas. Mantenerlo al añadir o retirar recursos. La cabecera y las insignias de `assets/` son SVG locales, sin scripts, fuentes externas ni servicios de imágenes. La insignia de idioma describe el repositorio; las fichas especifican el idioma de cada recurso.

## Revisión periódica

Revisión editorial sugerida cada trimestre y cuando llegue una issue. El workflow de CI comprueba Markdown y enlaces de forma automática; un fallo de bot (403, 406, 429) exige comprobación manual, no retirada automática.

1. Abrir enlaces y distinguir redirección, registro obligatorio, bloqueo temporal y baja real.
2. Confirmar autoría, muestra del contenido, idioma, coste y condiciones de laboratorio o examen.
3. Comprobar versiones y adecuación educativa. Actualizar solo la fecha de las fichas efectivamente revisadas.
4. Corregir la URL si existe un destino canónico equivalente. Un 403, 429 o error del lector automatizado exige comprobación manual, no retirada automática.
5. Si deja de cumplir los criterios, proponer su retirada con motivo y fuente en una PR. El historial Git conserva la decisión; no acumular enlaces muertos en el catálogo.

## Alcance de la revisión inicial — 2026-09-18

Se consultaron páginas públicas y resultados del buscador de las fuentes originales para verificar identidad, orientación y acceso anunciado. La revisión no acredita haber cursado la formación ni validado todos sus ejercicios. Las etiquetas de nivel y ciclo son editoriales.

Ampliación editorial **2026-09-21**: navegación entre categorías, etiquetas compactas, política de idioma explicitada y nuevas fichas en sistemas, redes, cloud y desarrollo.

Ampliación de aula **2026-09-21**: páginas [apuntes](../recursos/apuntes.md) y [proyectos](../recursos/proyectos.md) por titulación (SMR–DVRV), portales de la familia en gobierno, y filtro frente a volcados de foro. Omitidos por inaccesibles: `dotoscat/ajedrez-online`, `gabrilov/proyecto`. TodoFP puede bloquear o agotar tiempo en comprobaciones automatizadas; verificar en navegador.

| Observación | Tratamiento |
| --- | --- |
| GitHub Skills muestra una redirección hacia GitHub Learn. | Se conserva el punto de entrada y se añade el ejercicio oficial Introduction to GitHub. |
| Google Cloud Skills Boost redirige a Google Skills. | Ficha con nombre nuevo, nombre anterior y enlace a planes. |
| El lector falló al abrir `documentation.ubuntu.com/server/`. | Se verificó y utilizó la entrada oficial `ubuntu.com/server/docs/`. |
| Apertura directa de INCIBE-CERT fallida en el lector. | Índice de estudios localizado mediante búsqueda oficial; limitación visible en la ficha. Comprobar en navegador antes de una actividad de aula. |
| AWS Skill Builder necesita JavaScript. | Condiciones contrastadas en las FAQ oficiales de AWS, enlazadas en la ficha. |
| ÁNGELES contiene cursos sobre versiones antiguas de Windows. | Se señala la necesidad de comprobar versiones; su formación de riesgos y ENS conserva un valor distinto. |

Las URL de cada ficha son las fuentes primarias de su descripción. No se fijan precios, cuotas ni números de cursos que requieran mantenimiento frecuente.

## Publicar en GitHub

La carpeta `Awesome-ASIR` es autónoma y no necesita instalación ni compilación. Está preparada para un repositorio con ese nombre.

1. Crear un repositorio vacío llamado `Awesome-ASIR` en la cuenta u organización elegida.
2. Subir el contenido de esta carpeta a la raíz, incluidas `.github`, `.editorconfig` y `.gitattributes`; evitar una carpeta `Awesome-ASIR` anidada en el repositorio remoto.
3. Revisar el README renderizado y la disponibilidad de las plantillas de issues y PR.
4. Configurar descripción: «Biblioteca educativa curada para ASIR, DAW, DAM y Ciberseguridad: documentación, teoría y laboratorios».
5. Topics sugeridos: `awesome-list`, `asir`, `daw`, `dam`, `cybersecurity`, `education`, `spanish`, `sysadmin`.

La licencia propuesta y aplicada a los textos originales es CC BY-SA 4.0. No se han creado un repositorio remoto, credenciales, automatizaciones ni vínculos a un propietario ficticio.
