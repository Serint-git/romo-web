ROMO-WEB-DEMO-018 — CONOCE NUESTROS EQUIPOS
Fecha: 15 de octubre de 2026

ESTADO: PARCHE INCREMENTAL PARA APLICAR SOBRE LA INSTALACIÓN COMPLETA ROMO-WEB-DEMO-017.
NO ES UN SITIO COMPLETO INDEPENDIENTE.

1. BASE DE TRABAJO
- Base única: ROMO-WEB(4).zip proporcionado en esta iteración.
- Se verificó que contiene index.html, los recursos locales y ocho documentos PDF enlazados, además de README-014.txt a README-017.txt.
- El archivo README-017.txt identifica esta base como la versión 017 y detalla la modificación anterior.
- No se reconstruyó el sitio, no se recuperaron versiones antiguas ni se eliminaron archivos.

2. CAMBIOS IMPLEMENTADOS
- Nueva sección informativa «Conoce nuestros equipos» (#conoce-equipos), situada entre el catálogo y «¿Qué integra un cuarto frío?».
- Seis fichas visuales de carácter comercial: unidades condensadoras, evaporadores, compresores, condensadores, paneles aislantes y puertas de refrigeración/congelación.
- Cada ficha responde, con vocabulario sencillo y breve, qué es, para qué sirve y cómo interviene en el proceso de refrigeración.
- Cada ficha contiene una fotografía de catálogo existente, un crédito visual discreto y un enlace a la familia comercial ya aprobada (#condensadoras, #evaporadores, #compresores, #condensadores, #paneles o #puertas).
- Se añadió exclusivamente un enlace textual «¿Qué hace cada equipo? Conócelo aquí» al párrafo introductorio de #productos para facilitar el descubrimiento de la nueva sección.
- Al final de la guía se enlaza a la sección del cuarto frío de 011, sin copiar ni alterar su módulo interactivo.
- CSS encapsulado en #conoce-equipos y un estilo exclusivo para el enlace #productos .romo018-educ-link. No se agregaron scripts ni dependencias.

3. ARCHIVOS DEL PARCHE / DESPLIEGUE
MODIFICADO
- index.html: inclusión de una sección informativa, sus reglas CSS y un enlace interno desde productos.

NUEVO
- README-018.txt: registro de alcance, fuentes, verificaciones y pasos para actualizar.

SIN CAMBIOS / NO INCLUIDOS EN EL ZIP
- assets/ y assets/documentos/ en su totalidad. Los seis recursos WebP son fotografías existentes en ROMO-WEB-DEMO-017; no deben volverse a copiar ni borrarse.
- Fichas técnicas y extractos PDF, logos y material comercial, navegación, scripts y formularios.

4. FOTOGRAFÍAS REUTILIZADAS (TODAS PREEXISTENTES)
- assets/romo-013c-unidad-semihermetica.webp (catálogo ROMO, familia de condensadoras).
- assets/romo-013c-evaporador-convencional.webp (catálogo ROMO, familia evaporadores).
- assets/romo-013c-compresores-referencia.webp (catálogo general ROMO; NO identifica productos XECOM XR específicos).
- assets/romo-013c-condensador-romo.webp (catálogo ROMO, familia de condensadores).
- assets/romo-014-paneles-catalogo-romo.webp (catálogo ROMO, paneles aislantes).
- assets/romo-014-puertas-transparentes-catalogo-romo.webp (catálogo ROMO, puertas TRANSPARENTES; NO es una fotografía de puertas sólidas para cuartos fríos).
- Los créditos y las limitaciones anteriores aparecen expresamente en los pies de foto de la sección.
- No se incorporaron imágenes de stock, material generado ni instalaciones inventadas.

5. FUENTES UTILIZADAS
A. index.html y recursos de la instalación ROMO-WEB-DEMO-017 (principal fuente para las fotos, la arquitectura y los enlaces comerciales).
B. CATALOGO - ROMO lll (actualizado fecha 31.08.2026)(9).docx: familias comercializadas, unidades condensadoras, evaporadores, compresores, condensadores, paneles y puertas; no se trasladaron fichas/valores técnicos no necesarios.
C. 2026-V07 Com-Energy Heat exchanger & Units Ok(6).docx: documento COMENERGY con evaporadores, condensadores y unidades condensadoras (incluidas las unidades con compresor Bitzer), para contextualizar funciones generales de componentes.
D. «Cuestionario_Contenidos_Sitio_Web_SERINT (Contestado).pdf»: prioridad declarada de unidades condensadoras y evaporadoras; interés del cliente en explicar visualmente los elementos del cuarto frío.
E. «Brandbook Romo Refrigeracion.pdf»: identidad visual azul/teal y tipografía Kanit, conservadas desde la base aprobada.
- Las frases educativas son explicaciones funcionales GENERALES, no especificaciones ni características garantizadas de modelos concretos. No se atribuye una imagen a códigos específicos.

6. PRUEBAS REALIZADAS
- Comparación textual/DOM de 017 frente a 018: sin alteraciones en hero, nosotros, cuarto frío de 011, aplicaciones, experiencia, marcas, proyectos, proceso, contacto, header, footer o scripts. Los 25 artículos de catálogo permanecen intactos; solo se añade un enlace a la introducción.
- Las once familias y la variante inoxidable aprobadas hasta 017 se conservan; sus fichas y descargas no se alteraron.
- 67 identificadores HTML únicos; sin anclas internas huérfanas; 35 rutas de recursos locales src/href verificadas contra los archivos presentes en la copia completa.
- Seis imágenes existentes asociadas a seis fichas; los enlaces llevan a seis anclas del catálogo y el CTA complementario enlaza a #cuarto-frio.
- Verificación en Chromium aislado, mediante HTML en memoria (política del entorno bloquea file:// y localhost): layout de la guía en 320, 390, 760, 1024 y 1440 px; imágenes decodificadas; tarjetas sin overflow. 1 columna para móviles, 2 para tabletas y 3 en escritorio grande.
- Comparación de ancho total de la página 017 vs. 018 en 320, 390, 760, 1024 y 1440 px: respectivamente 426/426, 426/426, 760/760, 1024/1024 y 1440/1440. No se introdujo nuevo desbordamiento; el overflow general anterior a 426 px en móviles estrechos ya existía en 017 y queda fuera de alcance.
- Prueba de ejecución del HTML íntegro en memoria: los scripts no produjeron errores de página; índice de documentación técnica <details> abre; se conservaron cuatro controles del cuarto frío; navegación por anclas a evaporadores y al cuarto frío comprobada.
- Confirmación de <meta name="robots" content="noindex,nofollow,noarchive"> y schema LocalBusiness sin cambios.
- Pruebas de navegador con inyección temporal de imágenes como data URI únicamente para poder visualizar y validar el montaje; los enlaces reales del archivo entregado siguen siendo rutas relativas a assets/.

7. PENDIENTES Y ALCANCE EXCLUIDO
- Después de subir el parche, probar en la LIGA TEMPORAL del cliente la visualización con los recursos reales, los vínculos externos y la apertura pública de todos los PDF, el teléfono, el formulario y WhatsApp. No se ha publicado desde este entorno.
- Revisión editorial y autorización comercial final por ROMO del texto divulgativo y del uso de fotos de catálogo.
- Si se requieren imágenes de puertas sólidas, ROMO debe entregar una fotografía propia/autorizada; la guía usa claramente identificada una imagen existente de puertas transparentes.
- La validación de ajustes de especificaciones/capacidades de modelos y la disponibilidad real de equipos no forma parte de la guía.
- Sin cursos, evaluaciones, cuentas, videos, certificados, LMS, área privada, inventario, cotizador complejo ni administración.
- NO se adelantaron tareas de ROMO-WEB-DEMO-019.

8. INSTRUCCIONES PARA APLICAR EN HOSTING TEMPORAL
1) Respaldar el index.html actual y confirmar que la instalación completa de ROMO-WEB-DEMO-017 ya está desplegada con assets/ y assets/documentos/.
2) Descomprimir ROMO-WEB-DEMO-018.zip en la raíz pública de esa instalación, sobrescribiendo ÚNICAMENTE index.html; el README puede conservarse fuera del sitio público si se prefiere.
3) NO eliminar ni reemplazar en conjunto assets/, documentos o imágenes.
4) Limpiar caché y comprobar #conoce-equipos desde el enlace nuevo de «Productos», los seis enlaces comerciales, sus fotografías y el enlace a «Cuarto frío».
5) Verificar versiones móvil/escritorio, NOINDEX, PDF, contacto y navegación general en la URL de la demo.
6) En caso de incidencia, restaurar el index.html respaldado. No es necesario revertir assets porque no se modificaron.

FIN DE ROMO-WEB-DEMO-018.
