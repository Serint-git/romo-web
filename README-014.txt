ROMO-WEB-DEMO-014 — PANELES SÁNDWICH Y PUERTAS DE REFRIGERACIÓN
Fecha: 14 de octubre de 2026
Base real recibida: ROMO-WEB-DEMO-013C(1).zip (última variante 013C aportada en esta conversación).
Tipo de paquete: PARCHE INCREMENTAL. No es una copia íntegra del sitio web.

1. CAMBIOS REALIZADOS
- Se suman dos artículos informativos al mismo bloque de familias desarrollado en ROMO 012/013:
  05 / Paneles sándwich; 06 / Puertas de refrigeración y congelación.
- Misma presentación editorial aprobada (texto comercial, chips de variantes, CTA, galerías de
  documentos originales, nota de procedencia). Sin galerías, filtros ni sistemas independientes.
- Se actualizan EXCLUSIVAMENTE el resumen editorial del catálogo y las dos entradas existentes
  de Paneles y Puertas en la cuadrícula inferior, ahora con enlace a su detalle.
- CSS agregado solo para el bloque de aclaración sobre las dos clases de puertas; se conservan
  todos los estilos y scripts anteriores.
- CTA de cada familia abre WhatsApp existente de ROMO (52 33 3255 7257), con mensaje específico.
- Se enlaza una ficha técnica PDF para cada familia, conforme a las fuentes recibidas.
- Sin precios, inventario, carrito, pagos, backend ni nuevas familias ajenas a 014.

2. FAMILIAS Y VARIANTES INCORPORADAS
PANELES SÁNDWICH
- Panel metálico con núcleo de poliuretano para cerramiento aislante de cuartos fríos.
- Variantes explícitas del catálogo ROMO: espesor 60 mm, 100 mm; acero inoxidable 60 mm y 100 mm.
- La ficha también menciona otros espesores; el sitio NO los convierte en disponibilidad o inventario.

PUERTAS
- El catálogo ROMO enumera puertas de enfriamiento, de congelación y puertas transparentes.
- Se aclara la diferencia entre puertas de acceso a recintos fríos y puertas transparentes.
- La ficha PDF proporcionada documenta puertas de vidrio para refrigeración y congelación:
  bastidores 1–4 puertas y referencias CD-01 / CD-02 en la tabla de aperturas. Estas cifras NO
  se atribuyen a las puertas de acceso opacas ni se presentan como disponibilidad comercial.
- Las fotografías exhibidas en el artículo de puertas son únicamente del tipo transparente.

3. ARCHIVOS MODIFICADOS
- index.html (contenido del catálogo / 2 fichas de familia; CSS localizado).

4. RECURSOS NUEVOS / ORIGEN Y USO DE LAS IMÁGENES
- assets/romo-014-paneles-catalogo-romo.webp
  Origen: CATALOGO - ROMO lll (actualizado fecha 31.08.2026)(4).docx,
  recurso original word/media/image291.png. Imagen ilustrativa de paneles realmente
  presente en el catálogo; no se afirma que corresponda a un espesor preciso.
- assets/romo-014-paneles-ficha-fotografia.webp
  Origen: Ficha Técnica Panel Sandwich(3).pdf, página 1; recorte exclusivamente de
  la fotografía inferior derecha de los paneles apilados de su imagen original.
- assets/romo-014-puertas-transparentes-catalogo-romo.webp
  Origen: mismo catálogo ROMO, word/media/image204.png; fotografía de puertas de vidrio.
- assets/romo-014-marcos-puertas-transparentes-romo.webp
  Origen: mismo catálogo ROMO, word/media/image208.png; imagen de bastidor de vidrio.

Las imágenes son aportadas directamente en el catálogo y la ficha recibidos. Solo se
recortaron zonas vacías/ajenas a la fotografía y se optimizó a WebP sin reconstruir
productos, añadir logotipos ni inventar instalaciones. NO se usaron bancos de imágenes
ni se copiaron fotografías de páginas externas. Las fotos NO demuestran obra ejecutada
por ROMO ni confirman todos los modelos/variantes citados.

5. DOCUMENTOS TÉCNICOS PUBLICADOS (COPIA ORIGINAL)
- assets/documentos/romo-ficha-tecnica-panel-sandwich.pdf
  Copia de "Ficha Técnica Panel Sandwich(3).pdf"; 1 página.
- assets/documentos/romo-ficha-tecnica-puertas-transparentes.pdf
  Copia de "Información Técnica Puertas Refrigeración y Congelación(3).pdf"; 1 página.
  Es una ficha de puertas transparentes de proveedor (identificación RMDOOR / HUAJING),
  NO una especificación de puertas sólidas para cuartos fríos.

6. PRUEBAS REALIZADAS
- Comparación DOM entre index.html de 013C y 014: sin cambios en 13 elementos
  protegidos (inicio, nosotros, cuarto frío, aplicaciones, experiencia, marcas,
  proyectos, proceso, contacto, condensadoras, evaporadores, compresores y condensadores).
- Encabezado y pie de página intactos. Scripts JS idénticos; meta robots y
  script JSON-LD/schema intactos. Se conserva NOINDEX de la demo.
- Verificación de que los 4 WebP son legibles y de que los 2 PDFs contienen 1 página cada uno.
- Validación de anchors #paneles y #puertas, enlaces a los PDFs locales y mensajes
  de WhatsApp al número preexistente, sin precios ni elementos e-commerce.
- Chromium / Playwright en 1440, 1024, 760, 390 y 320 px: ambos artículos visibles,
  imágenes nuevas cargadas y secciones sin escaparse del viewport.
- Se comprobó en Chromium la interacción existente del botón "Paneles" del cuarto frío.
- Inspección visual de capturas de escritorio y móvil, sin desbordamiento propio nuevo.
- Se constató que a 390/320 px persiste un scrollWidth total de 426 px. Esta situación
  figura como PENDIENTE PREEXISTENTE en README-013C y NO se modificó por alcance 014.

NOTA SOBRE EL ENTORNO DE PRUEBA
El 013C proporcionado y este 014 son parches (no contienen toda la carpeta assets/),
por lo que no es posible reproducir localmente TODAS las imágenes/logos/documentos
históricos sin el sitio completo desplegado. La comprobación visual en navegador se
realizó con el HTML en memoria, cargando los WebP aportados localmente para la prueba.
No se hizo despliegue ni se verificaron de extremo a extremo el envío de WhatsApp,
la descarga en hosting ni enlaces externos. Deben probarse en la liga temporal.

7. INSTALACIÓN
1) Confirmar que el sitio en la liga temporal ya integra la base 013 y el parche 013C.
2) Realizar copia de respaldo del directorio del sitio antes de cualquier sobrescritura.
3) Descomprimir ROMO-WEB-DEMO-014.zip sobre ese directorio; sobrescribir SOLO index.html;
   agregar los 4 WebP nuevos bajo assets/ y los 2 PDFs bajo assets/documentos/.
4) Conservar TODOS los demás recursos históricos; no borrar documentos, fotos ni CSS previos.
5) Refrescar caché y verificar #paneles, #puertas, sus CTAs y ambos PDFs por URL.
6) Revisar la visualización en celular y escritorio desde la liga temporal.

8. PENDIENTES
- Solicitar fotografías de producto verificables para puertas de acceso SÓLIDAS de
  cuartos fríos, evitando confundirlas con puertas transparentes.
- Confirmar con ROMO la autorización de publicación comercial de imágenes y fichas
  técnicas procedentes de proveedores y catálogo; revisar si los teléfonos/datos del
  proveedor presentes en el PDF de puertas deben estar visibles en la demo pública.
- Verificar disponibilidad, referencias y dimensiones definitivas durante la cotización.
- Comprobar en hosting que ambos PDFs se sirvan con Content-Type correcto.
- Corregir posteriormente el desbordamiento móvil preexistente solo mediante una
  iteración autorizada que permita intervenir los estilos/elementos responsables.
- No se han adelantado tareas de ROMO-WEB-DEMO-015.
