ROMO-WEB-DEMO-017 — EVAPORADORES DE ACERO INOXIDABLE Y DOCUMENTACIÓN TÉCNICA
Fecha: 15 de octubre de 2026

ESTADO: PARCHE INCREMENTAL LISTO PARA APLICAR SOBRE ROMO-WEB-DEMO-016 COMPLETA

1. BASE CONFIRMADA ANTES DE TRABAJAR
- Archivo completo recibido: ROMO-WEB(3).zip, con index.html, assets/ y assets/documentos/.
- Comparación SHA-256: los seis archivos del parche ROMO-WEB-DEMO-016(2).zip (index.html + 5 WebP) coinciden exactamente con los correspondientes archivos de ROMO-WEB(3).zip. El README-016.txt también coincide.
- En la base completa se localizaron los siete PDF previamente enlazados y todos los recursos locales referenciados desde la página.
- La imagen assets/romo-evaporador-inoxidable.webp YA existía en la base completa: se reutilizó. Su contenido visual coincide con la fotografía del apartado «Evaporadores de acero inoxidable» del catálogo ROMO actualizado 31.08.2026 (word/media/image46.png). NO se empaqueta nuevamente.
- No se reconstruyó el sitio, no se utilizaron versiones previas y no se descartaron contenidos.

2. CAMBIOS (SOLO EN #productos)
- Se incorporó, inmediatamente después de la ficha de evaporadores convencionales, la variante documentada «Evaporadores de acero inoxidable» (#evaporadores-inoxidables), con presentación editorial y responsive ya aprobada, reutilizando la fotografía original existente.
- Se muestran exclusivamente referencias reales del apartado inoxidable del catálogo ROMO: ZLM-2.8/15, ZLM-7.5/40, ZLM-14.9/80 y ZLM-37.4/200, como muestra representativa de los once modelos publicados en el origen. No se adjudica un modelo concreto a la foto.
- Se añadió WhatsApp de solicitud de cotización al mismo número aprobado, 33 3255 7257.
- La tarjeta «Unidades evaporadoras» del catálogo inferior incorpora un segundo enlace a la variante inoxidable. No se creó tarjeta duplicada ni se cambió el conteo de las once familias principales: el inoxidable se identifica como variante 02B de la familia 02.
- Se añadió un índice plegable «Documentación técnica por familia» con ocho accesos PDF, para consulta rápida sin llenar la página con tablas. Los siete enlaces históricos siguen también en sus fichas sin cambios.
- Los únicos estilos añadidos están bajo el selector #productos, destinados al índice documental y el ancla de la variante.

3. DOCUMENTO NUEVO
assets/documentos/romo-evaporadores-acero-inoxidable-catalogo-extracto.pdf
- Una página informativa DERIVADA del apartado inoxidable del catálogo ROMO (31.08.2026), con fotografía de catálogo, los once nombres de modelos ZLM allí publicados y alimentación declarada en el listado (220 V / 1 PH / 60 HZ).
- No es una ficha técnica individual ni una ficha certificada del fabricante; se rotula explícitamente como extracto informativo derivado.
- IMPORTANTE: el extracto general COMENERGY de ZLM no identifica fabricación inoxidable; no se utiliza para acreditar esa variante. No se atribuyeron capacidades, espesores, prestaciones, dimensiones ni certificaciones al producto inoxidable.
- No se añadió PDF completo del catálogo ROMO, que es un DOCX fuente de gran tamaño; se evitó publicar un archivo pesado y no optimizado.

4. DOCUMENTOS YA PUBLICADOS (REVISADOS, SIN CAMBIOS)
Documentos existentes y enlaces EXACTOS encontrados en index.html:
1. assets/documentos/romo-unidades-condensadoras-comenergy-extracto.pdf
   1 página. COMENERGY, unidades condensadoras semiherméticas; corresponde a #condensadoras.
2. assets/documentos/romo-evaporadores-comenergy-extracto.pdf
   7 páginas. COMENERGY, evaporadores Compact ZL, Classic D, Cosy DH y Peak DE; corresponde a #evaporadores convencional/general. No certifica inoxidable.
3. assets/documentos/romo-condensadores-comenergy-extracto.pdf
   2 páginas. COMENERGY, FNF y FNV/FNW; corresponde a #condensadores. Nomenclaturas FNF no idénticas entre fuentes, como la nota histórica ya advierte.
4. assets/documentos/romo-compresores-xecom-extracto.pdf
   2 páginas. XECOM; corresponde a #compresores y conserva su nota original de fuentes.
5. assets/documentos/romo-ficha-tecnica-panel-sandwich.pdf
   1 página. Paneles sándwich; corresponde a #paneles.
6. assets/documentos/romo-ficha-tecnica-puertas-transparentes.pdf
   1 página. Puertas transparentes del proveedor; corresponde al material transparente de #puertas, NO a puertas sólidas.
7. assets/documentos/romo-ficha-tecnica-vitrina-cerrada-dem.pdf
   1 página. Vitrinas cerradas serie DEM; corresponde a #vitrinas.
Los siete PDF siguen siendo EXACTAMENTE los del ZIP completo recibido; no se duplican en el parche incremental.

5. ENLACES VERIFICADOS
- En la copia completa recibida, TODOS los recursos locales enlazados en atributos href/src del HTML apuntan a archivos existentes.
- Los ocho PDF enlazados en la iteración 017 abren como documentos PDF legibles mediante inspección local: 7 existentes y el nuevo.
- El índice documental incluye ocho enlaces correctos y accionables; la ampliación de foto enlaza al WebP original existente.
- Los identificadores de página son únicos; los enlaces internos #... apuntan a elementos existentes (incluido el nuevo #evaporadores-inoxidables).
- Los enlaces HTTPS externos, WhatsApp y el funcionamiento desde el hosting público NO se comprobaron contra servidores remotos; deben validarse en la liga temporal. Un archivo presente en el ZIP no garantiza por sí solo su presencia en el hosting.

6. PRUEBAS Y REGRESIÓN
- Comparación textual con 016: TODO el HTML antes de #productos es idéntico tras excluir exclusivamente el nuevo CSS encapsulado en #productos. TODO el HTML a partir de #cuarto-frio es byte por byte idéntico a 016.
- Las once fichas originales de familia se conservan; la nueva variante se agrega sin eliminar ni renombrar las anteriores.
- HTML comprobado: 59 IDs únicos; ninguna ancla local sin destino; ninguna ruta local rota en la base completa; NOINDEX original conservado.
- Validación de documentos PDF: ocho archivos íntegros, páginas con dimensiones válidas; el nuevo tiene una sola página y enumera los modelos contra el catálogo.
- Chromium aislado por inserción del HTML en memoria: anchos 320, 390, 760, 1024 y 1440 px. Variante inoxidable visible y fotografía existente decodificada en la prueba; índice nativo <details> se abre y exhibe sus ocho enlaces; ninguna excepción de JavaScript.
- Desbordamiento horizontal: 320 px base/017 = 426/426; 390 px = 426/426; 760 px = 760/760; 1024 = 1024/1024; 1440 = 1440/1440. La sección nueva permanece dentro de cada viewport y NO añade desbordamiento.
- El desbordamiento general preexistente a 320/390 px ya estaba en 016 y se deja expresamente fuera de alcance.
- Limitación navegador: el entorno de QA restringió acceso a file:// y servidores locales. En la prueba en memoria se incluyó sólo la imagen inoxidable como data-URI para validar su decodificación. Los demás elementos gráficos conservan rutas normales en la entrega y se validaron por existencia, no por su representación integral en ese entorno.
- No se realizaron modificaciones a hero, navegación, animaciones, fuentes Kanit, marcas, contacto, SEO/schema, scripts, política NOINDEX, otras secciones, funcionalidades ni imágenes ilustrativas externas.

7. PENDIENTES / NO INCLUIDOS
- Validar en la liga temporal la apertura pública de cada PDF, enlaces salientes, WhatsApp, y las vistas móvil/escritorio con los recursos reales del hosting.
- Confirmar con ROMO los modelos, material constructivo y disponibilidad exacta antes de presentar datos más específicos de evaporadores inoxidables.
- Solicitar fichas inoxidables individuales autorizadas si se requiere detalle técnico del fabricante; el extracto creado no las reemplaza.
- Revisar derechos/autorización de publicación comercial de fotografías de catálogo antes de publicar en producción.
- Se conserva el NOINDEX mientras se trate de una demo temporal; no se modificó a INDEX.
- No se amplían máquinas de hielo, combinación enfriador/congelador ni educación; tampoco se crea panel de administración, filtros avanzados, inventario ni comercio electrónico.

8. CONTENIDO EXACTO DEL ZIP ROMO-WEB-DEMO-017.zip
- index.html (MODIFICADO, reemplazar en el hosting de demo)
- assets/documentos/romo-evaporadores-acero-inoxidable-catalogo-extracto.pdf (NUEVO)
- README-017.txt (NUEVO)

NO INCLUIDOS (PRESERVADOS EN LA INSTALACIÓN 016 COMPLETA): TODOS los otros assets, los siete PDF anteriores, assets/romo-evaporador-inoxidable.webp y los README previos.

9. APLICAR EL PARCHE SOBRE LA VERSIÓN COMPLETA 016
1) Antes de actualizar, respaldar index.html y assets/ del hosting temporal.
2) Confirmar que la raíz pública es la instalación completa ROMO-WEB-DEMO-016 (no su ZIP incremental aislado).
3) Extraer este ZIP en la raíz del sitio: sobrescribir index.html; crear el nuevo PDF en assets/documentos/; conservar todos los otros archivos.
4) NO BORRAR carpetas ni archivos existentes y NO reemplazar assets/ completos por una carpeta vacía.
5) Limpiar caché. Verificar la nueva ancla #evaporadores-inoxidables, la foto, WhatsApp, nuevo PDF y el índice en «Productos».
6) Comprobar en la liga temporal el resto del sitio, las once familias originales, hero, animaciones, Kanit, responsive, proyectos, marcas y contacto.
7) Si algo falla, restaurar index.html del respaldo y retirar únicamente el PDF nuevo; los assets previos nunca se eliminan.

FIN DE ITERACIÓN 017. NO SE ADELANTÓ 018.
