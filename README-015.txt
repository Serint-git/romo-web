ROMO-WEB-DEMO-015 — INTEGRACIÓN DE VITRINAS Y VENTILADORES
Fecha: 14 de octubre de 2026
Base obligatoria utilizada: ROMO-WEB-DEMO-014(1).zip (index.html original preservado y ampliado)
Tipo de entrega: PARCHE INCREMENTAL. NO es una copia completa del sitio.

1. RESUMEN DE CAMBIOS
- Añadidas exclusivamente las familias 07 (Vitrinas de refrigeración) y 08 (Ventiladores),
  bajo #productos, mediante las clases/editorial/galerías/CTA ya existentes en 012–014.
- Vitrinas: explicación comercial, 3 referencias DEM respaldadas por catálogo, dos imágenes
  originales, botón WhatsApp y PDF de una página con las especificaciones de proveedor.
- Ventiladores: explicación comercial, diámetros respaldados de 350 / 400 / 500 / 600 mm,
  una fotografía original, botón WhatsApp y enlace a asesoría técnica por WhatsApp.
- Modificado solamente el resumen de #productos, su pie de procedencia, la tarjeta inferior
  EXISTENTE de Vitrinas, y añadida una tarjeta de Ventiladores con enlace interno.
- Ajustado el contador textual de familias anteriores 01–06 al nuevo total de 08.
- Sin cambios en CSS, JavaScript, header, footer, hero, animación de frío, Kanit, marcas,
  guía de cuarto frío, otras secciones, schema JSON-LD o directiva NOINDEX.
- No se incluyen precios, existencias, filtros, racks, refacciones, venta electrónica
  ni capacidades de administración de productos.

2. PRODUCTOS Y RESPALDO DOCUMENTAL
VITRINAS CERRADAS (CATÁLOGO ROMO, apartado VITRINA CERRADA):
- DEM-S187R-6A1W
- DEM-S250R-6A1W
- DEM-S250R-6ACW
Nota importante: la ficha '20241206 Vitrina Cerrada.docx', página 3,
  muestra DEM-S187R-6A1WI (sufijo adicional I) mientras el catálogo ROMO
  muestra DEM-S187R-6A1W. La ficha WEB conserva las claves del catálogo y
  advierte expresamente la discrepancia; solicitar confirmación antes de venta.
- La ficha del proveedor refiere prestaciones técnicas, que no se reproducen
  como tabla extensa en la web. La página de especificaciones del documento
  original se ofrece como PDF de consulta (sin página de contactos).

VENTILADORES (CATÁLOGO ROMO, apartado VENTILADORES):
- Referencias por tamaño nominal: 350 mm, 400 mm, 500 mm y 600 mm.
- Los cuatro registros se listan en el catálogo con 220 V / 1 PH / 60 Hz.
- No se asigna la fotografía a una medida específica y no se inventan códigos.
- No se aportó ficha independiente de ventiladores; las consultas técnicas
  se canalizan al WhatsApp comercial y NO a un PDF inexistente.

3. ARCHIVOS MODIFICADOS
- index.html
  Únicamente contenido localizado en #productos: dos nuevas fichas, resumen,
  enlaces de índice y aclaraciones textuales de catálogo/procedencia.

4. RECURSOS NUEVOS — IMÁGENES Y PROCEDENCIA
- assets/romo-015-vitrina-catalogo-romo.webp
  CATALOGO - ROMO lll (actualizado fecha 31.08.2026)(5).docx
  -> word/media/image168.png. Fotografía de vitrina del catálogo.
- assets/romo-015-vitrina-ficha-resour.webp
  20241206 Vitrina Cerrada(3).docx -> word/media/image230.png.
  Fotografía/render de producto aportada en la ficha del proveedor RESOUR.
- assets/romo-015-ventilador-catalogo-romo.webp
  CATALOGO - ROMO lll (actualizado fecha 31.08.2026)(5).docx
  -> word/media/image144.png. Fotografía de ventilador axial del catálogo.

Todas las imágenes anteriores proceden de los archivos entregados por el cliente.
Solo se redujo resolución cuando correspondía y se convirtió a WebP con Pillow;
no se generaron ni sustituyeron objetos. No se usaron bancos externos ni IA.
Las imágenes representan las familias y NO validan un modelo exacto, una
obra ejecutada por ROMO ni disponibilidad de inventario.

5. NUEVO DOCUMENTO TÉCNICO
- assets/documentos/romo-ficha-tecnica-vitrina-cerrada-dem.pdf
  Fuente: 20241206 Vitrina Cerrada(3).docx, página 3 de 4.
  Se convirtió el documento recibido a PDF, y se extrajo exclusivamente la página
  de especificaciones de vitrina DEM sin modificar contenido ni reproducir la
  página 4 de datos telefónicos de personas del proveedor. Contiene marca RESOUR.
  Las unidades/modelos son de proveedor; deben validarse comercialmente con ROMO.

6. PRUEBAS Y RESULTADOS
- Comparación automatizada contra index.html EXACTO dentro del 014 recibido:
  sin diferencias en header, footer, CSS, todos los scripts y schema JSON-LD.
- DOM comparado sin modificaciones en #inicio, #nosotros, #cuarto-frio,
  #aplicaciones, #experiencia, #marcas, #proyectos, #proceso y #contacto.
- Las seis familias 01–06 quedaron idénticas salvo su contador de total.
- Ocho identificadores de familia únicos, sin elementos duplicados.
- Confirmado <meta name="robots" content="noindex,nofollow,noarchive">.
- Validadas las rutas de los 3 WebP y del PDF nuevos, legibilidad de imágenes y
  una sola página del PDF con referencias técnicas.
- CTA verificadas a https://wa.me/523332557257 con mensajes por familia, y
  enlaces internos #vitrinas / #ventiladores presentes.
- Chromium: pruebas de las dos nuevas fichas con los ESTILOS ORIGINALES en
  una envoltura de #productos aislada a 320, 390, 760, 1024 y 1440 px:
  las imágenes cargan y no hay desbordamiento originado por las fichas nuevas.
- Limitación QA: la prueba integral de navegación del sitio con assets completos
  no se realizó: el ZIP 014 también es un parche sin todos los recursos históricos;
  el navegador restringió la carga local/HTTP del sitio completo. No se afirma
  validación de entrega real de WhatsApp ni hospedaje. Se requiere prueba en liga.

7. INSTALACIÓN DEL PARCHE
1) Confirmar que la liga temporal ya tiene el sitio completo y todos los parches
   anteriores hasta 014; respaldar index.html y el directorio antes de tocarlo.
2) Extraer este ZIP en la RAÍZ de ese sitio, respetando la estructura de carpetas.
3) Sobrescribir ÚNICAMENTE index.html; agregar los tres WebP y el PDF nuevos.
4) NO borrar imágenes, documentos o scripts históricos: el ZIP NO LOS INCLUYE.
5) Refrescar caché del navegador/servidor; visitar #vitrinas y #ventiladores.
6) Comprobar en servidor imágenes, descarga de PDF, CTAs y navegación en
   escritorio y móvil. Verificar también preservación de todas las familias previas.

8. PENDIENTES (NO RESUELTOS POR LÍMITES DE 015)
- Confirmar con ROMO la diferencia DEM-S187R-6A1W vs DEM-S187R-6A1WI.
- Autorizar publicación comercial de fotografías y PDF del proveedor RESOUR.
- Solicitar ficha técnica individual de ventiladores y fotos para cada diámetro
  si se desea mayor detalle en una futura iteración.
- Validar modelos, diámetros, compatibilidad y disponibilidad en cada cotización.
- Verificar PDF Content-Type, ruta y redirecciones de WhatsApp en el hosting.
- El README 014 documenta un desbordamiento móvil PREEXISTENTE a 390/320 px
  (scrollWidth 426 px). Se deja pendiente por alcance de esta iteración;
  no debe confundirse con las nuevas fichas, que no desbordan aisladas.
- Administración de catálogo, racks, refacciones y otras familias NO se ejecutaron.
- No se adelantan tareas de ROMO-WEB-DEMO-016.
