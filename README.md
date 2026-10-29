# Las Coquetas

Landing local sin dependencias: abrir `index.html` con Live Server. HTML5, CSS3 y JavaScript vanilla. No necesita instalación ni compilación. Repositorio: https://github.com/pabloldl/lascoquetascadiz. No se ha configurado alojamiento, reserva ni canal de contacto.

## Dirección y contenido

Información proporcionada: Las Coquetas, peluquería, Calle la Rosa, 35, 11670 El Bosque, Cádiz, España. Los enlaces de Google Maps buscan esta dirección; no se han inventado coordenadas. Pendiente de confirmación: teléfono, horarios, servicios concretos, precios, equipo y fotografías propias. No se publican esos datos.

Una única etiqueta `noindex, nofollow` en el HTML. Mantenerla también si en el futuro se sube el proyecto a un repositorio.

## Fotografías y licencias

Descargadas de Pexels el 29 de octubre de 2026 y servidas localmente en WebP, con ancho máximo de 1000–1400 px y calidad 82–84. No son imágenes del establecimiento ni de sus trabajos. Se advierte en la portada, en la sección del oficio y en textos alternativos. No se repiten imágenes ni se presentan marcas o personas como colaboradoras del negocio.

Licencia: https://www.pexels.com/license/ — permite uso gratuito comercial en webs y modificación, sin atribución obligatoria. No implica respaldo del fotógrafo o las personas retratadas al negocio. Deben respetarse las restricciones de la licencia.

| Archivo | Autor | Página de origen |
| --- | --- | --- |
| assets/herramientas.webp | RDNE Stock project | https://www.pexels.com/photo/hairdresser-equipment-on-table-7697654/ |
| assets/gesto.webp | RDNE Stock project | https://www.pexels.com/photo/hands-holding-hair-and-comb-7755251/ |
| assets/tijeras.webp | Kampus Production | https://www.pexels.com/photo/different-types-of-hair-scissors-on-a-towel-8834066/ |
| assets/cabello.webp | Nadezhda Moryak | https://www.pexels.com/photo/combing-the-hair-of-a-person-6503329/ |
| assets/corte.webp | Kampus Production | https://www.pexels.com/photo/person-holding-comb-and-scissor-8834034/ |
| assets/secado.webp | by Natallia | https://www.pexels.com/photo/hairdresser-styling-hair-with-a-hairdryer-13714794/ |
| assets/textura.webp | Ron Lach | https://www.pexels.com/photo/back-view-of-a-woman-s-hair-9489719/ |

Tipografías del sistema: Georgia para titulares y Arial/Helvetica para texto. Sin peticiones de fuentes a terceros. Iconos SVG monocromáticos propios con currentColor. Favicon tipográfico propio.

## Diseño y accesibilidad

Rediseño fotográfico: nombre en una franja propia sobre un tríptico de imágenes de diferentes tamaños, sin botones duplicados: la navegaci?n principal permite acceder al sal?n, al oficio y a la ubicaci?n. En móvil, una imagen vertical acompaña dos detalles apilados bajo el t?tulo, sin contenedores de acciones adicionales. Navegación siempre visible, sin menú hamburguesa.

Presentación reducida a una frase junto a una fotografía panorámica de manos y herramientas. Composición del oficio con imagen horizontal de tijeras, secado vertical y textura de cabello a gran escala. El anterior bloque central de texto se integra junto a esta última fotografía. Ubicación sobre fondo malva para continuar la identidad visual. Se conservan las cuatro fotos originales y se añaden tres; siete fotografías diferentes en total. No se ha reutilizado código de Mari Carmen.

Enlace para saltar al contenido, estructura semántica, focos visibles, enlaces descriptivos, imágenes con alt y carga diferida fuera del hero. Revelado mediante recorte con IntersectionObserver; respeta prefers-reduced-motion. Sin JavaScript, el contenido y la navegación siguen disponibles.

## Verificación realizada

29 de octubre de 2026, tras el rediseño: `node --check script.js` y comprobación con Chrome headless mediante `.qa/check.cjs`. Resultados en `.qa/results.json`, capturas a 375, 768, 1440 y 1920 px y vistas completas en `.qa/full.png` y `.qa/full-mobile.png`. Sin desbordamiento horizontal, imágenes rotas, destinos internos inexistentes ni errores de JavaScript. Navegación visible en los cuatro tamaños. Siete imágenes distintas, una única etiqueta robots correcta, sin enlaces de teléfono, WhatsApp ni correo. Verificados los parámetros de dirección y apertura segura de ambos enlaces de Google Maps. Comprobado scroll sin animación con preferencia de movimiento reducido.

Inspección visual de las capturas completas de escritorio y móvil y de la portada a 768 px. No se ha probado Safari real ni un iPhone físico, ni se ha comprobado una ficha comercial o ruta dentro de Google Maps. Solo se han modificado o creado archivos dentro de `las-coquetas/`. La carpeta `.qa/` contiene comprobaciones locales y queda excluida del repositorio. La subida a GitHub no configura un despliegue.
