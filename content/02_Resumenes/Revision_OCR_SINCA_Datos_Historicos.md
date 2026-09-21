# Revisión OCR documentos medidas provisionales - SINCA y datos históricos

Fecha: 2026-09-16

## Documentos OCR procesados

| ID | Archivo | Resultado OCR | Uso en análisis |
|---|---|---:|---|
| DOC-1346 | `1.1 N12 Excel Seguimiento Correos Respaldo Conexión Estación EMRP TAMA a Sinca.pdf` | 10 páginas, 36.637 caracteres | Respaldo de gestión de conexión SINCA/SMA, criterios LIN[v]/LIN[M]/VAL y estaciones involucradas. |
| DOC-1347 | `1.1 N13 Entrega datos Discretos Históricos CCMC.pdf` | 2 páginas, 3.147 caracteres | Respaldo de entrega datos discretos históricos 2020-2025 de CCMC. |
| DOC-1348 | `1.1 N13 Entrega datos Discretos Históricos CCMO.pdf` | 2 páginas, 2.385 caracteres | Respaldo de entrega datos discretos históricos 2020-2025 de CCMO. |

Textos OCR guardados en `01_Fuentes/OCR/`.

## Hallazgos de DOC-1346

El respaldo contiene una cadena de correos entre Minera Candelaria/Lundin, MMA y soporte técnico R9 sobre conexión de estaciones a SINCA/SMA.

Hallazgos relevantes:

- El MMA informa criterios nacionales para estaciones industriales: `LIN[v]` para datos crudos generados en línea, `LIN[M]` para datos operacionales depurados que se publican en plataformas públicas en tiempo real, y `VAL` para carga mensual de datos validados.
- El MMA señala que los datos operacionales `LIN[M]` son los publicados en tiempo real en plataformas públicas y deben resguardar calidad y consistencia.
- Se indica que el cálculo de promedio horario debe considerar al menos 75% de datos válidos y es responsabilidad del titular.
- Se informa que TAMA debía transmitir PM10 y PM2,5 y que, según soporte, no existían registros de envíos recientes, siendo el último dato recibido el 01-01-2025. Este punto evidencia una brecha o interrupción previa en conexión en línea.
- Minera Candelaria informa el 02-03-2026 que la estación TAMA está transmitiendo datos a la SMA según resolución y que hacia SINCA existe plazo de conexión en línea según Res. 4612 del MMA, indicado como 12 meses.
- Minera Candelaria señala que los datos históricos de estaciones discretas fueron entregados a SEREMI MMA Atacama y SMA desde 2020 en adelante, y que mensualmente se entregan datos discretos de estaciones con representatividad poblacional a SEREMI y SMA.
- El MMA aclara el 04-03-2026 que no tiene observaciones sobre datos discretos ni sus registros históricos. Respecto de datos continuos históricos, reconoce que el criterio no está establecido en la resolución de medidas provisionales, aunque solicita evaluar su carga por actualización de sistemas.
- La tabla OCR identifica estaciones: TAMA, Rajo Mina, Mina y Nantoco para Minera Candelaria; TAMA también reporta para Minera Ojos del Salado. TAMA incluye MP10 y MP2,5 discreto/continuo y meteorología.
- En agosto 2026 se confirma que la gestión de conexión aplica exclusivamente a estaciones con monitoreo continuo, de acuerdo con criterios de correos precedentes.

## Hallazgos de DOC-1347 y DOC-1348

DOC-1347 registra ingreso de datos discretos históricos 2020-2025 MP10, MP2,5 y MPS de CCMC a oficina de partes SEREMI/MMA, en atención al art. 2.2.2 de la Res. Ex. N°4612/2025, para publicación en SINCA.

DOC-1348 registra ingreso equivalente para CCMO/Ojos del Salado, también asociado a datos discretos históricos 2020-2025 MP10, MP2,5 y MPS, para publicación en SINCA.

Ambos documentos muestran acuse/recepción por oficina de partes el 06-11-2025.

## Cambio en brechas

La brecha OCR para DOC-1346, DOC-1347 y DOC-1348 queda cerrada como extracción textual. La brecha de plataforma/SINCA no queda cerrada completamente, pero cambia de estado:

- Antes: sin texto útil / pendiente OCR.
- Ahora: evidencia documental parcial de gestiones, criterios técnicos y entregas históricas discretas.
- Sigue pendiente: evidencia técnica de conexión efectiva vigente, URL o plataforma pública, disponibilidad, transmisión en tiempo real, estaciones continuas conectadas y logs/capturas.

## Implicancia para cumplimiento

Estos antecedentes son favorables para demostrar gestión y entrega histórica discreta bajo medidas provisionales. No bastan para acreditar por sí solos la obligación RCA de página web/MP10 en tiempo real ni la disponibilidad operativa actual de SINCA/QMonitor.
