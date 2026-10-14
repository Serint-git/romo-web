ROMO-WEB-DEMO-013B — AJUSTE DE PRESENTACIÓN DEL CATÁLOGO
Fecha: 14 de octubre de 2026
Base obligatoria: ROMO-WEB-DEMO-013 (montada sobre ROMO-WEB-DEMO-012D).
Tipo de entrega: PARCHE INCREMENTAL. No es el sitio completo.

OBJETIVO
Mejorar la jerarquía visual de las cuatro fichas de familia existentes para que el
visitante reconozca primero el equipo real, lea después su descripción y modelos y
pueda solicitar información sin buscar las fotografías en un acordeón.

ARCHIVOS INCLUIDOS
- index.html — ÚNICO archivo del sitio modificado.
- README.txt — instrucciones y resultados de comprobación.
No se incorporaron fotografías nuevas, PDFs nuevos, fuentes, ni librerías.

CAMBIOS REALIZADOS
1. Unidades condensadoras: foto semihermética visible como protagonista;
   segunda referencia compacta visible; información y CTA a un costado.
2. Evaporadores: dos fotografías ROMO visibles; descripción, códigos y contacto
   permanecen exactamente iguales a ROMO-WEB-DEMO-013.
3. Compresores: fotografía ROMO visible. AVISO EXPRESO: la fotografía es de la
   familia del catálogo ROMO y NO identifica los modelos XECOM XR.
4. Condensadores: fotos ROMO y COMENERGY visibles y con atribución y aclaración
   de que no identifican necesariamente cada código.
5. Las imágenes se pueden abrir ampliadas en una pestaña nueva; se conserva
   la documentación técnica y los enlaces de WhatsApp originales.
6. Estilo responsive: fotografía primero, textos y acciones después; las cuatro
   fichas usan un patrón consistente de lectura y mantienen la paleta de ROMO.
7. No se alteraron secciones independientes ni las imágenes de apoyo visual que
   aparecen en las tarjetas superiores del catálogo.

MODELOS PRESENTADOS (INALTERADOS)
- Unidades condensadoras: CEM 10 HP (4VES-10Y), CEM 15 HP (4PES-15Y),
  CEM 20 HP (4NES-20Y).
- Evaporadores: ZLM-2.8/15, ZLM-7.5/40, DJ-34.6/210, DH-D40.
- Compresores XECOM: XR38B-C1-101, XR52B-D1-101, XR91B-D1-101,
  XR135B-D1-101.
- Condensadores: FNF-2.2/8.2, FNF-7.3/25, FNV-5003-219, FNV-5503-256.

ORIGEN DE LAS IMÁGENES (TODAS REUTILIZADAS DE 012D/013)
- assets/romo-condensadora-semihermetica.webp y
  assets/romo-condensadora-compacta.webp: catálogo general ROMO.
- assets/romo-evaporador-convencional.webp y
  assets/romo-evaporador-inoxidable.webp: catálogo general ROMO.
- assets/romo-compresores-foto-catalogo.webp: catálogo general ROMO, sin
  atribución visual a XECOM ni a los modelos XR.
- assets/romo-condensador-foto-catalogo.webp: catálogo general ROMO.
- assets/comenergy-condensadores-fnv-fnw.webp: documento COMENERGY.
Las fotografías representan familias de producto; las descripciones no prometen
una correspondencia exacta entre fotografía y número de modelo.

PRUEBAS REALIZADAS
- Comparación de los cuatro bloques: textos comerciales, modelos, enlaces a
  documentación y enlaces WhatsApp se mantienen SIN CAMBIOS.
- Integridad de hero, cabecera, secciones externas, cuarto frío interactivo,
  marcas, catálogo de categorías, formulario/contacto, scripts, SEO y schema.
- Metadato NOINDEX intacto. Sin precios.
- Chromium headless: 1440, 1024, 760, 390 y 320 px.
- 7 imágenes cargan correctamente; archivos enlazados existen.
- Comprobación de anclas a fichas, menú móvil, botón del cuarto frío y enlaces.
- Sin errores JavaScript de página.
- 390/320 px: el documento conserva el ancho horizontal 426 px de la base 013;
  el desbordamiento preexistente no se ha corregido porque queda fuera del
  alcance. El nuevo acomodo no aumenta ese ancho.
- Apertura real de enlaces externos (WhatsApp) deberá comprobarse al publicar.

INSTALACIÓN
1. Conservar un respaldo completo de la web aprobada.
2. Confirmar que ROMO-WEB-DEMO-013 esté ya aplicado sobre 012D: sus siete
   imágenes/documentos nuevos y los recursos históricos deben estar presentes.
3. Sustituir SOLO index.html por el de este paquete. README es documental.
4. Limpiar caché del navegador y revisar escritorio/móvil en la liga temporal.
5. NO eliminar los directorios de assets existentes.

PENDIENTES (FUERA DE 013B)
- Revisar en una iteración autorizada el desbordamiento horizontal previo a 013.
- Hacer una última revisión visual con el cliente en la liga de pruebas.
- No se agregan productos adicionales ni tareas de ROMO-WEB-DEMO-014.
