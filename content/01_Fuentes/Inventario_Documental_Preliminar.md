# Inventario documental preliminar

## Estado general

Fecha de levantamiento: 2026-09-16.

La carpeta `antecedentes` se encuentra cargada en la raiz del proyecto y contiene aproximadamente 7.4 GB de informacion documental distribuida en 1.445 archivos.

## Conteo preliminar por extension

| Extension | Cantidad | Uso esperado |
|---|---:|---|
| PDF | 849 | Fuente principal para RCA, EIA, Adendas, ICE, informes, resoluciones, fiscalizaciones y respaldos. |
| XLSX | 238 | Matrices, reportes, planes de accion, programas, datos de monitoreo y respaldos tabulares. |
| KMZ | 113 | Ubicaciones, rutas, puntos de monitoreo, fuentes, areas y archivos geograficos. |
| DOCX | 61 | Cartas, minutas, respuestas, documentos de trabajo y no conformidades. |
| ZIP | 51 | Anexos comprimidos y respaldos digitales que deben abrirse selectivamente. |
| PPTX | 10 | Presentaciones de gestion, Steerco, talleres y observaciones. |
| Otros | 123 | Shapefiles, correos, imagenes, XML, RAR, 7z y otros soportes. |

## Estructura principal detectada

| Carpeta | Lectura preliminar | Prioridad |
|---|---|---|
| `1. RCA` | Pertinencias, RCA y antecedentes regulatorios de CCMC. | Alta |
| `2. EIA 2040` | EIA, Adendas, anexos, resolucion final y documentos base del proyecto 2040. | Alta |
| `3. Inventario Emisiones` | Actualizacion de modelacion de calidad del aire, catalogos, validacion de eficiencias y enlace a modelo. | Alta |
| `Antecedentes NC SGS` | No conformidades, cartas, planes de accion, respaldos y reportabilidad 2026. | Alta |
| `Anteproyecto PDA` | Antecedentes del PDA, inventarios, decretos, actas y presentaciones COA. | Media-Alta |
| `Fiscalizaciones` | Requerimientos y respuestas SMA 2026. | Alta |
| `Informes y reportes de cumplimiento ambiental asociados a calidad del aire y emisiones` | Informes mensuales, trimestrales y semestrales. | Alta |
| `Medidas Prov` | Programas de control de emisiones, medidas provisionales, observaciones, KMZ y respaldos. | Alta |
| `Obligaciones RCA` | Presentaciones de observaciones criticas asociadas al area mina y puerto. | Alta |
| `Planes de seguimiento ambiental asociados al componente aire` | Resolucion asociada a seguimiento/componente aire. | Alta |
| `Presentaciones` | Steerco MPS y taller de gestion de emisiones/calidad de aire. | Media |
| `Otros` | Resoluciones y documentos complementarios. | Media |

## Priorizacion recomendada

1. Resolver jerarquia normativa y vigencia: RCA, resolucion final EIA 2040, Adendas, ICE si esta disponible, pertinencias y resoluciones complementarias.
2. Extraer obligaciones del componente aire desde EIA 2040, Plan de Cumplimiento, Plan de Seguimiento, Plan de Medidas y Fichas Resumen.
3. Revisar inventario/modelacion para fuentes, contaminantes, factores, eficiencias, escenarios y archivos geograficos.
4. Revisar medidas provisionales y no conformidades SGS/SMA para hallazgos, respuestas, planes de accion y brechas recurrentes.
5. Incorporar reportes periodicos para evidencia de cumplimiento, continuidad operacional y medios de verificacion.

## Pendientes tecnicos

- Generar inventario documental completo en formato tabular con ruta, nombre, extension, carpeta, tamano y prioridad.
- Revisar comprimidos ZIP/7z/RAR de forma selectiva para evitar duplicar anexos ya extraidos.
- Identificar documentos corruptos, protegidos, duplicados o no legibles.
- Crear resumenes individuales de documentos prioritarios en `02_Resumenes`.
- Poblar la matriz de obligaciones RCA con referencias exactas por documento, pagina o considerando.
