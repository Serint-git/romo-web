ROMO-WEB-DEMO-016 — CIERRE DE RACKS Y REFACCIONES
Fecha: 14 de octubre de 2026

BASE OBLIGATORIA Y ALCANCE
- Fuente de implementación exclusiva: index.html de ROMO-WEB-DEMO-015(1).zip.
- Fuente comercial e imágenes exclusiva: CATALOGO - ROMO lll (actualizado fecha 31.08.2026)(6).docx.
- Entrega INCREMENTAL: no contiene los recursos históricos completos de la web. Es un parche para una instalación que YA tenga aplicadas las versiones anteriores hasta 015.
- No se incorporan precios, existencias, carrito, pagos, catálogo administrable, filtros ni inventario.

1. ARCHIVOS MODIFICADOS
- index.html: únicamente contenido de la sección #productos.
  * Nuevo detalle de 3 familias, respetando los componentes editoriales preexistentes.
  * Tres enlaces de navegación de catálogo y reemplazo de la tarjeta demostrativa previa de «Racks industriales» por la tarjeta documentada «Racks de almacenamiento» (sin duplicar la familia).
  * Conteos /08 -> /11 y ajustes a textos introductorios y notas de familias enlazadas.
- Ningún archivo CSS, JavaScript, cabecera, marca, pie de página, SEO, schema o componente de otra sección fue alterado.

2. FAMILIAS INCORPORADAS (FICHAS 09 A 11)

09 · RACK DE REFRIGERACIÓN (#rack-refrigeracion)
- Conjunto de compresión para sistemas frigoríficos, diferente de racks estructurales.
- Referencia original publicada: 40 HP (2000-BV-56X).
- Alimentación mostrada según el catálogo ROMO: 220V–440V / 3 PH / 60 HZ.
- Una foto tomada del apartado «RACK DE REFRIGERACIÓN». No se presenta como prueba visual del modelo exacto.
- Botón WhatsApp de cotización y enlace a consulta de configuración.

10 · RACKS DE ALMACENAMIENTO (#racks)
- Estructuras para organizar y almacenar mercancía; NO son racks frigoríficos.
- Elementos del apartado «RACKS»: cabeceras 3000, 4050 y 5025 mm; larguero; estante.
- Ilustración original del catálogo ROMO, rotulada expresamente como ilustración, no como fotografía de montaje.
- Botón WhatsApp de cotización y enlace para consultar componentes.
- Sin inferir carga, material estructural, montaje, medidas adicionales ni especificaciones ausentes.

11 · REFACCIONES (#refacciones)
- Presentación agrupada de componentes en lugar de una tabla técnica masiva.
- Ejemplos documentados:
  * SA-204: acumulador de línea de succión.
  * AW-55824: separador de aceite.
  * EK-304 S: filtro secador de líquido.
  * VLR-03: receptor de líquido vertical.
  * EVR-10 S: válvula de solenoide.
  * NRFE-1 SC: válvula de expansión.
- Otras agrupaciones mencionadas sin lista extensa: válvulas check, controles de presión, mirillas y accesorios de puertas.
- Tres imágenes del apartado de refacciones, como contexto para las familias de componentes y NO como verificación de un modelo exacto.
- Botón WhatsApp de cotización y enlace a asesoría de refacciones.

3. PROCEDENCIA DE IMÁGENES NUEVAS
Todas derivan SIN CREAR OBJETOS del archivo CATALOGO - ROMO lll (actualizado fecha 31.08.2026)(6).docx; imágenes en word/media/:
- assets/romo-016-rack-refrigeracion-catalogo-romo.webp
  Origen: image160.png; apartado «RACK DE REFRIGERACIÓN»; fotografía de conjunto frigorífico.
- assets/romo-016-racks-estructura-catalogo-romo.webp
  Origen: image304.png; apartado «RACKS»; ilustración de estructura de almacenamiento.
- assets/romo-016-refaccion-control-presion-catalogo-romo.webp
  Origen: image215.png; apartado «REFACCIONES»; imagen de control de presión (el objeto original exhibe marca de fabricante).
- assets/romo-016-refaccion-componente-linea-catalogo-romo.webp
  Origen: image211.png; apartado «REFACCIONES»; componente cilíndrico de línea.
- assets/romo-016-refaccion-valvula-catalogo-romo.webp
  Origen: image213.png; apartado «REFACCIONES»; válvula de línea.

Tratamiento: reducción de resolución y codificación a WebP mediante Pillow, manteniendo aspecto y objeto original. No se añadieron insignias ROMO a los productos ni se utilizaron bancos externos, fotografías de proyectos inventados o imágenes generadas por IA. El pie de cada bloque aclara que las imágenes ilustran la familia, sin acreditar modelo exacto, obra ejecutada ni disponibilidad. Puede ser necesario revisar autorizaciones de uso comercial antes de producción.

4. PRUEBAS EFECTUADAS — RESULTADOS
- Comparación textual exacta 015 vs 016: la totalidad de index.html FUERA de #productos permanece byte por byte idéntica (incluidos hero «El frío. Bajo control.», header, navegación, cuarto frío 011, marcas COMENERGY/RESOUR/XECOM, contacto, footer, estilos CSS, scripts, SEO y JSON-LD).
- Comparación de las ocho fichas de 012–015: estructuras, enlaces, textos, galerías e imágenes idénticos salvo actualización deliberada del contador total /08 a /11.
- HTML estructural: once identificadores únicos de familia, tres enlaces internos nuevos sin duplicados y tres CTAs dirigidos al WhatsApp ya existente (33 3255 7257).
- Recursos nuevos: se comprueba que los cinco WebP existen, se decodifican y se muestran en las fichas nuevas; todas las imágenes nuevas incluyen texto alternativo.
- Navegador Chromium con HTML y estilos originales: probados anchos de 320, 390, 760, 1024 y 1440 px. Ninguna de las tres nuevas fichas excede los límites horizontales del viewport; imágenes nuevas decodificadas; enlaces internos a #refacciones probados; ningún error de ejecución de JavaScript en la prueba.
- Responsive: escritorio en dos columnas y móvil en una columna, utilizando estilos existentes SIN cambios CSS.
- NOINDEX confirmado: <meta name="robots" content="noindex,nofollow,noarchive">.
- No se agregaron precios ni bases de datos, procesos de compra o filtros avanzados.

LIMITACIONES IMPORTANTES DE LAS PRUEBAS
- ROMO-WEB-DEMO-015(1).zip es un PARCHE que no incluye todos los assets y documentos de versiones históricas. Por ello NO se pudo verificar en este entorno la carga integral del sitio completo en el hosting. Debe comprobarse tras instalar sobre la acumulación real 001–015.
- La infraestructura del navegador de pruebas bloquea conexiones a localhost. La inspección visual se hizo con el HTML y CSS 015 íntegros cargados en memoria y con las cinco imágenes nuevas incrustadas exclusivamente para la prueba; los archivos finales siguen enlazando sus rutas relativas normales.
- El documento base 015 ya tiene un desbordamiento horizontal preexistente: scrollWidth 426 px en viewports de 320 y 390 px. Las fichas 016 se mantienen dentro de 292 y 362 px respectivamente, y NO aumentaron ese valor (015 y 016 comparados en el mismo motor). Queda expresamente FUERA de 016 corregirlo.
- No se probó el envío efectivo de mensajes WhatsApp, un servidor remoto, enlaces salientes ni la instalación en la liga pública.

5. REVISIÓN DE COBERTURA FRENTE AL CATÁLOGO ORIGINAL
Apartados generales (títulos del catálogo entregado) frente a fichas web:
- Evaporadores de refrigeración: YA PUBLICADO en 012–015.
- EVAPORADORES DE ACERO INOXIDABLE: PENDIENTE (familia diferenciada por material en el catálogo).
- Unidades condensadoras: YA PUBLICADO.
- Condensadores: YA PUBLICADO.
- Ventiladores: YA PUBLICADO (015).
- Rack de refrigeración: INCORPORADO en 016.
- Vitrina cerrada: YA PUBLICADO (015).
- Compresores: YA PUBLICADO.
- Puertas de refrigeración/congelación y transparentes: YA PUBLICADO (014).
- Refacciones: INCORPORADO en 016.
- Paneles: YA PUBLICADO (014).
- Racks estructurales: INCORPORADO en 016.

PENDIENTES IDENTIFICADOS PARA REVISAR EN 017 (NO IMPLEMENTADOS):
A. Incorporar, previa validación de alcance, la familia explícita «Evaporadores de acero inoxidable», con la serie ZLM indicada por el catálogo. Evitar duplicar la ficha de evaporadores ya publicada: deberá diferenciarse por material.
B. Aclarar comercialmente si «Enfriador/Congelado combinado» mencionado en el índice original requiere una subfamilia distinta de «Vitrina cerrada»: en el cuerpo recuperado aparece el apartado VITRINA CERRADA, sin ficha específica inequívoca de combinado. No inventar modelos ni fotografías.
C. Las tarjetas demostrativas «Máquinas de hielo» y «Componentes para unidades condensadoras» existen en 015, pero NO tienen una ficha detallada inequívoca en los apartados originales revisados; no se crean familias nuevas de ellas sin documentación/autorización.
D. Solicitar especificaciones/fichas individuales y autorizaciones de imágenes si se desea precisión de compatibilidad y publicación definitiva de racks y refacciones.

No se adelantó implementación técnica ni visual de 017, capacitación, animación progresiva o proyectos.

6. DESPLIEGUE DEL PARCHE INCREMENTAL
1) Confirmar que la liga temporal contiene el sitio completo y actualizaciones hasta 015. Respaldar index.html y assets.
2) Descomprimir ROMO-WEB-DEMO-016.zip en la raíz del sitio temporal.
3) SOBRESCRIBIR exclusivamente index.html y AÑADIR los cinco WebP indicados a la carpeta assets/.
4) NO BORRAR nada previo del hosting; los recursos no incluidos en este ZIP se consideran preservados por la instalación previa.
5) Limpiar caché y visitar #rack-refrigeracion, #racks y #refacciones en escritorio y móvil.
6) Revisar enlaces de tarjeta, WhatsApp, imágenes ampliadas, navegación, las ocho fichas previas, el cuarto frío, marcas, formulario, SEO/noindex y responsive.
7) Mantener NOINDEX mientras la demo siga siendo temporal. Cualquier publicación productiva debe tener revisión/autorización separada.

ARCHIVOS TOTALES DE ESTE ZIP: index.html, cinco imágenes WebP nuevas y README-016.txt.
