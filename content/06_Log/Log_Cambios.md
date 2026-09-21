# Log de cambios

## 2026-09-15

### Acciones realizadas

- Se reviso la carpeta de trabajo `/home/forecast/Marcelo/candelaria/rev_documental_of`.
- Se identificaron dos archivos iniciales:
  - `OF.CU.26.07.063 CCMC v4.pdf`.
  - `1.1 Ant Reg.zip`.
- Se extrajo texto del PDF usando `pdftotext`.
- Se reviso el indice del documento y las secciones:
  - `4.1.- Revision documental y regulatoria`.
  - `5.- Entregables`.
  - `6.- Plan de trabajo`.
- Se intento listar el contenido de `1.1 Ant Reg.zip` con `unzip -l`, pero el comando indico que no pudo encontrar el directorio central del ZIP. El archivo existe y pesa aproximadamente 1.4 GB, por lo que queda pendiente reintentar cuando termine la carga o verificar integridad.
- Se creo el vault de Obsidian `Vault_Obsidian_Revision_Documental_Candelaria`.
- Se crearon notas base:
  - `README.md`.
  - `00_Admin/MEMORIA_CONTINUIDAD.md`.
  - `02_Resumenes/Resumen_OF_CU_26_07_063_CCMC_v4.md`.
  - `03_Planes/Plan_Trabajo_Revision_Documental.md`.
  - `04_Matrices/Matriz_Informacion_Requerida.md`.
  - `04_Matrices/Matriz_Obligaciones_RCA_Estructura.md`.
  - `05_Prompts/Prompt_Revision_Documental.md`.
  - `06_Log/Log_Cambios.md`.

### Decisiones de trabajo

- Usar el PDF de oferta como documento rector del alcance.
- Priorizar la revision documental y regulatoria durante las semanas 1 a 4.
- Preparar matrices trazables antes de iniciar el analisis masivo de documentos del ZIP.
- Registrar todos los avances dentro del vault.

### Pendientes

- Reintentar apertura/listado de `1.1 Ant Reg.zip`.
- Crear inventario documental maestro cuando el ZIP este disponible.
- Crear resumenes por documento regulatorio prioritario.
- Poblar matriz de obligaciones RCA con referencias documentales exactas.
- Identificar brechas documentales y solicitudes de informacion.

## 2026-09-16

### Actualizacion por carga completa de antecedentes

- Se confirmo la existencia de la carpeta `antecedentes` en la raiz del proyecto.
- Se levanto un conteo preliminar: 1.445 archivos y aproximadamente 7.4 GB.
- Se identificaron extensiones dominantes: 849 PDF, 238 XLSX, 113 KMZ, 61 DOCX, 51 ZIP, 10 PPTX y otros soportes.
- Se identificaron bloques documentales principales: RCA, EIA 2040, inventario/modelacion, antecedentes NC SGS, anteproyecto PDA, fiscalizaciones, reportes de cumplimiento, medidas provisionales, obligaciones RCA, planes de seguimiento, presentaciones y otros.
- Se creo `01_Fuentes/Inventario_Documental_Preliminar.md`.
- Se actualizo `00_Admin/MEMORIA_CONTINUIDAD.md` con el estado actual de antecedentes y el uso del plugin `superpowers`.
- Se actualizo `05_Prompts/Prompt_Revision_Documental.md` para incluir revision de skills al iniciar sesiones futuras.
- Se actualizo `04_Matrices/Matriz_Informacion_Requerida.md` con los bloques documentales reales detectados.

### Proxima accion recomendada

- Generar un inventario documental completo en CSV/Markdown con ruta, nombre, extension, carpeta, tamano, prioridad y tipo documental.
- Priorizar revision de RCA final EIA 2040, plan de cumplimiento, plan de seguimiento, plan de medidas, fichas resumen, medidas provisionales y NC SGS/SMA.

### Inventario documental completo

- Se genero `01_Fuentes/Inventario_Documental_Completo.csv` con 1.445 registros, uno por archivo de `antecedentes`.
- Se genero `01_Fuentes/Inventario_Documental_Completo_Resumen.md` con distribucion por carpeta, extension y archivos mas pesados.
- Se asigno categoria y prioridad preliminar segun carpeta principal para orientar la revision documental.
- Pendiente: revisar documentos prioritarios y poblar matriz de obligaciones con IDs documentales.

### Inicio revision sustantiva EIA 2040 / RCA aire

- Se extrajo texto de siete documentos prioritarios: RCA final, Plan de Cumplimiento Adenda 3, Plan de Medidas Adenda 3, Plan de Seguimiento Adenda 3, Fichas Resumen Adenda 3, Linea Base de Calidad del Aire y Modelacion Calidad Aire base.
- Se identificaron obligaciones iniciales para humectacion, asfaltado/bischofita, seguimiento de calidad del aire, monitoreo en linea, DS 61/2008, DS 144/61, mallas Netport y barrido/aspirado.
- Se creo `02_Resumenes/Revision_Inicial_EIA2040_RCA_Aire.md`.
- Se creo `04_Matrices/Matriz_Obligaciones_Aire_EIA2040_Inicial.md`.
- Se marco como brecha la fecha `31 de septiembre` indicada en la RCA para un reporte semestral del Plan de Humectacion.

### Revision Antecedentes NC SGS aire

- Se revisaron NC SGS de enero, abril y mayo 2026 asociadas a calidad del aire, reportabilidad, QMonitor, conexion SMA, eficiencia de caminos compensatorios, DustMate y MPS.
- Se inspeccionaron planes de accion/cierre en Excel para NC 01 y NC 02.
- Se cuantifico la planilla `MPS Reportable.xlsx` para identificar maximos 2025-2026 por estacion.
- Se creo `02_Resumenes/Revision_NC_SGS_Aire_2026.md`.
- Se creo `04_Matrices/Matriz_Hallazgos_NC_SGS_Aire.md`.
- Se identifico como brecha QA/QC critica que los datos MPS 2025-2026 no deben usarse como conclusion ambiental sin validar representatividad, pesajes, calibracion, bitacoras y pronunciamiento tecnico.


### Continuación plan completo de análisis - fiscalización SMA y medidas provisionales

- Se revisaron antecedentes de fiscalización SMA ORA 70/2026, respuesta de CCMC y anexos de humectación, caminos compensatorios, barrido/aspirado y reportes técnicos Candelaria 2040.
- Se revisó Resolución Exenta MMA N° 4612/2025 sobre medidas provisionales para zona saturada Copiapó-Tierra Amarilla, junto con programas/respuestas de CCMC y SCM Ojos del Salado y oficios SEREMI Ord. 1859/2026 y 1857/2026.
- Se creó `02_Resumenes/Revision_Fiscalizacion_SMA_ORA70_Aire_2026.md`.
- Se creó `02_Resumenes/Revision_Medidas_Provisionales_Aire_2025_2026.md`.
- Se creó `04_Matrices/Matriz_Evidencias_Cumplimiento_Aire_2026.md`.
- Se creó `04_Matrices/Matriz_Brechas_Documentales_Aire.md`.
- Hallazgos destacados: humectación mina muestra evidencia favorable marzo-junio 2026; caminos compensatorios requieren trazabilidad tramo a tramo; barrido/aspirado presenta brecha crítica por no alcanzar 95% en mayo-junio y no medir enero-abril; medidas provisionales requieren localizar resolución aprobatoria final y evidencia mensual/semestral de implementación.


### Revisión monitoreo calidad del aire y meteorología 1S 2026

- Se extrajo texto de los informes trimestrales `Informe_CCMC_1T 2026.pdf` e `Informe_CCMC_2T 2026_vA 1.pdf`.
- Se revisó estructura de anexos Excel 2026 para Caldera, Mina, Puerto y Nantoco, confirmando hojas de datos válidos e inválidos.
- Se intentó extraer texto de DOC-1346, DOC-1347 y DOC-1348; los PDFs no tienen capa de texto, por lo que quedan como pendientes de OCR/revisión visual.
- Se creó `02_Resumenes/Revision_Monitoreo_Calidad_Aire_1S_2026.md`.
- Se creó `04_Matrices/Matriz_Estaciones_Parametros_Disponibilidad_Aire_2026.md`.
- Se creó `04_Matrices/Matriz_Resultados_Calidad_Aire_1S_2026.md`.
- Se actualizó `04_Matrices/Matriz_Evidencias_Cumplimiento_Aire_2026.md` y `04_Matrices/Matriz_Brechas_Documentales_Aire.md` con hallazgos de monitoreo.


### Extracción automática preliminar de anexos Excel monitoreo 2026

- Se creó `04_Matrices/Control_Anexos_Excel_Monitoreo_2026.csv` con conteos por archivo/hoja, datos numéricos, nulos/no numéricos, máximos/promedios y conteo auxiliar ≥130 para columna B.
- Se creó `04_Matrices/Control_Anexos_Excel_Monitoreo_2026.md` con lectura interpretativa y limitaciones.
- Hallazgo automático: Nantoco mayo 2026 contiene 744 datos horarios MP10, máximo 705,12 y 163 registros horarios ≥130; se requiere agregación diaria para evaluación normativa.
- Caldera enero-junio 2026 no muestra valores MP10 discretos ≥130 en columna B de anexos revisados.


### Matriz caminos compensatorios ORA 70

- Se creó `04_Matrices/Matriz_Caminos_Compensatorios_ORA70_2026.md`.
- Se identificó inconsistencia documental a cerrar: respuesta ORA 70 indica 12 caminos y ~14,46 km; plan anexo visible contiene 13 ítems y ~11,75 km sumados.
- Se agregó brecha BD-AIRE-013 en la matriz de brechas documentales.


### Resumen ejecutivo preliminar

- Se creó `02_Resumenes/Resumen_Ejecutivo_Preliminar_Aire.md` con hallazgos críticos, hallazgos favorables, brechas prioritarias y próximo bloque recomendado.
- Se actualizó `README.md` con los últimos productos de análisis.

## 2026-09-16 - Consolidación RCA/EIA componente aire

- Se creó `01_Fuentes/Control_Documentos_RCA_EIA_Aire.md` con control de documentos EIA, adendas y RCA revisados.
- Se creó `02_Resumenes/Revision_RCA_EIA_Consolidada_Aire.md` con análisis consolidado de obligaciones, impactos MP10/MP2,5 y brechas.
- Se creó `04_Matrices/Matriz_Trazabilidad_RCA_EIA_Aire.md` para seguir cada obligación desde EIA/adendas hasta RCA final.
- Se reemplazó `04_Matrices/Matriz_Obligaciones_Aire_EIA2040_Inicial.md` por versión consolidada RCA/EIA, incorporando malla Netport, plantación de árboles nativos y criterio MP2,5.
- Se agregaron brechas BD-AIRE-014 a BD-AIRE-017 en `04_Matrices/Matriz_Brechas_Documentales_Aire.md`.

## 2026-09-16 - evidencia RCA/EIA reforzada 2026

- Se creó `04_Matrices/Matriz_Evidencia_RCA_EIA_Reforzada_2026.md`.
- Se creó `02_Resumenes/Revision_Evidencia_RCA_EIA_Reforzada_2026.md`.
- Se actualizó `04_Matrices/Matriz_Brechas_Documentales_Aire.md` con estado parcial de Netport, plantación y plataforma/QMonitor/SINCA.
- La evidencia encontrada permite documentar planificación/avance de plantación y Netport Bosque Santos, ejecución mensual de barrido, y avance QMonitor, pero no cierra los indicadores RCA de 95% MP2,5, 95% prendimiento/captación MP2,5, 85% reducción de viento ni web/MP10 tiempo real.



## 2026-09-16 - Cierre del análisis documental aire

- Se creó `02_Resumenes/Informe_Final_Analisis_Documental_Aire.md` como producto de cierre.
- Se creó `01_Fuentes/Mapa_Cobertura_Documental_Aire.md`.
- Se creó `02_Resumenes/Revision_Modelacion_Inventario_Emisiones_Aire.md`.
- Se creó `02_Resumenes/Revision_Anteproyecto_PDA_Aire.md`.
- Se creó `02_Resumenes/Revision_Reportabilidad_Historica_Aire.md`.
- Se creó `03_Planes/Plan_Cierre_Documental_Aire.md`.
- Se creó `04_Matrices/Matriz_Solicitudes_Informacion_Cierre.md`.
- El plan queda completado a nivel documental con salvedades explícitas: ICE no localizado, OCR pendiente en PDFs sin texto y cierre de indicadores operacionales sujeto a antecedentes solicitados.


## 2026-09-16 - OCR DOC-1346 a DOC-1348

- Se ejecutó OCR de DOC-1346, DOC-1347 y DOC-1348; textos guardados en `01_Fuentes/OCR/`.
- Se creó `02_Resumenes/Revision_OCR_SINCA_Datos_Historicos.md`.
- Se actualizó `04_Matrices/Matriz_Evidencia_RCA_EIA_Reforzada_2026.md`, `04_Matrices/Matriz_Brechas_Documentales_Aire.md`, `04_Matrices/Matriz_Solicitudes_Informacion_Cierre.md` e `Informe_Final_Analisis_Documental_Aire.md`.
- Hallazgo: existe respaldo de gestiones SINCA/SMA y entrega de datos discretos históricos 2020-2025 de CCMC/CCMO, pero sigue pendiente la prueba de disponibilidad/URL/transmisión efectiva en tiempo real para cierre completo de plataforma.

## 2026-09-16 - Matriz Excel de cambios de aire

Se generó la matriz Excel `04_Matrices/Matriz_Candelaria_Aire_Revision_Documental_2026.xlsx`, usando como referencia estructural el archivo base `/home/forecast/Marcelo/candelaria/rev_documental_0/Matriz_Candelaria_Aire.xlsx`.

Contenido incorporado:
- Matriz consolidada de obligaciones y cambios asociados a RCA/EIA y antecedentes revisados.
- Trazabilidad de cambios normativos, operacionales y documentales identificados.
- Resumen por RCA, listado documental, bitácora, diccionario de campos, brechas, evidencia 2026 y cobertura documental.
- Integración de hallazgos OCR de DOC-1346, DOC-1347 y DOC-1348 sobre plataforma SINCA, datos históricos discretos 2020-2025, medidas provisionales y brechas de disponibilidad de información.

Validación realizada: apertura del archivo con `openpyxl`, comprobación de hojas esperadas y verificación de IDs clave `AIRE-RCA-001`, `AIRE-RCA-004`, `AIRE-RCA-009` y `AIRE-MP-001`.

## 2026-09-21 - Verificación final de matriz Excel

Se ejecutó verificación fresca sobre la matriz `Matriz_Candelaria_Aire_Revision_Documental_2026.xlsx` en carpeta de trabajo y copia del vault.

Resultado: OK, sin fallas.

Evidencia verificada:
- Ambos archivos existen y abren correctamente con `openpyxl`.
- Ambas copias contienen las 9 hojas esperadas: Matriz Consolidada, Trazabilidad de Cambios, Resumen por RCA, Listado RCA, Bitácora de Cambios, Diccionario de Campos, Brechas y Solicitudes, Evidencia 2026 y Cobertura Documental.
- Ambas copias tienen las mismas dimensiones por hoja.
- IDs clave presentes en Matriz Consolidada: `AIRE-RCA-001`, `AIRE-RCA-004`, `AIRE-RCA-009`, `AIRE-MP-001`.
- No se detectaron celdas con fórmulas pendientes o referencias a recalcular.
- Log y memoria contienen los marcadores de trazabilidad asociados a DOC-1346, DOC-1347 y DOC-1348.

Hashes registrados:
- Copia carpeta de trabajo: `c2bda582248b960a598e2d89c9149be8abcd5c45ddb4ffe07805b4962b466aff`.
- Copia vault: `2d019deb7fc81f85eaf17854add9fa7c52976613dfbf8e110db4e49592e58332`.

## 2026-09-21 - Matriz de no coincidencias y puntos a revisar

Se creó `04_Matrices/Matriz_No_Coincidencias_y_Puntos_a_Revisar_Aire.md` para centralizar todos los puntos donde la obligación, evidencia o fuente documental no coinciden completamente.

La matriz incluye, entre otros, los siguientes grupos de revisión:
- Caminos compensatorios: 12 caminos / 14,46 km versus 13 ítems / ~11,75 km visibles; control de caminos con asfalto en mal estado; falta de DustMate por tramo/mes.
- Barrido y aspirado: ejecución semanal versus indicador 95% MP2,5 no cerrado.
- Malla Netport: base técnica parcial versus alcance total RCA e indicador 85% viento.
- Plantación: planificación versus ejecución, prendimiento 95% y captación MP2,5 no acreditados.
- Plataforma web/SINCA: gestiones QMonitor/SINCA versus obligación de web pública/MP10 tiempo real.
- Resolución final programas MP, disponibilidad de estaciones, episodios MPS/MP10, ICE, hitos de inicio y eventos de viento.

También se agregó referencia cruzada en `04_Matrices/Matriz_Brechas_Documentales_Aire.md`.

