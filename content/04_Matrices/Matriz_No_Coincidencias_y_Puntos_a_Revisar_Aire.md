# Matriz de no coincidencias y puntos a revisar - componente aire

Fecha de creación: 2026-09-21  
Estado: matriz viva para revisión manual, conciliación documental y solicitudes de información.

Esta matriz concentra los puntos donde la obligación, el antecedente revisado, la evidencia operacional o la fuente documental no coinciden completamente. Su función es evitar que el entregable cierre como “cumplido” puntos que aún requieren reconciliación, respaldo adicional o confirmación formal.

## Criterio de uso

- **No coincidencia**: diferencia entre dos fuentes, entre obligación y evidencia, o entre estado reportado y respaldo disponible.
- **Pendiente de revisión**: falta de antecedente suficiente para confirmar cumplimiento o vigencia.
- **No implica incumplimiento por sí sola**: cada punto debe cerrarse con evidencia trazable, criterio técnico o confirmación documental.

## Matriz principal

| ID | Tema | No coincidencia / punto a revisar | Fuente u obligación base | Evidencia o antecedente que no calza completamente | Riesgo para el entregable | Acción requerida | Prioridad | Estado |
|---|---|---|---|---|---|---|---|---|
| NC-AIRE-001 | Caminos compensatorios | La obligación se describe como **12 caminos y aproximadamente 14,46 km**, pero el plan anexo visible lista **13 ítems y suma aproximadamente 11,75 km**. | RCA 69/2023 / RCA N°202303101169/2023, considerando 7.1.6; respuesta ORA 70; Adenda Excepcional Apéndice 6.3. | `Matriz_Caminos_Compensatorios_ORA70_2026.md` identifica 13 ítems visibles y diferencia de longitud. | Alto: impide cerrar cumplimiento tramo a tramo y podría alterar superficie/longitud compensada. | Reconciliar RCA, KMZ, planos, reemplazos autorizados, informes mensuales y mediciones DustMate por tramo. | Alta | Abierta |
| NC-AIRE-002 | Caminos compensatorios | Algunos caminos figuran como “asfalto en mal estado” con riego de agua industrial, mientras la obligación transitoria exige control de emisiones con eficiencia ≥90% mediante bischofita o similar hasta la implementación definitiva. | RCA 69/2023 / considerando 7.1.6; ORA 70; plan de riego/pavimentos. | En la matriz de caminos, Tres Puntas y Amolana aparecen con riego de agua industrial dos veces por semana. | Medio-Alto: puede requerir justificar equivalencia técnica o régimen aplicable. | Confirmar si esos tramos ya cuentan como pavimentados, si requieren reparación, o si el riego acredita eficiencia ≥90%. | Alta | Abierta |
| NC-AIRE-003 | Caminos compensatorios | Falta vínculo directo entre cada tramo, cada mes y su medición DustMate o equivalente. | RCA 69/2023 exige verificación mensual y reporte semestral. | Hay informes mensuales ORA 70, pero la matriz consolidada aún no tiene eficiencia por tramo/mes. | Alto: no permite confirmar indicador de control transitorio. | Extraer informes enero-junio 2026 y poblar tabla tramo/mes/eficiencia/certificado. | Alta | Abierta |
| NC-AIRE-004 | Barrido y aspirado | La obligación exige eficiencia de control MP2,5 de 95%, pero se identificó que enero-abril no tendrían medición de eficiencia y mayo/junio no alcanzarían 95%. | RCA 69/2023 / RCA N°202303101169/2023, medida de barrido y aspirado; informes ORA 70 enero-junio. | `Matriz_Evidencia_RCA_EIA_Reforzada_2026.md` y matriz de brechas marcan brecha crítica. | Alto: indicador RCA queda abierto. | Revisar metodología, línea base, resultados mayo-junio, causa de desviación y eventual validación de autoridad/tercero. | Alta | Abierta |
| NC-AIRE-005 | Barrido y aspirado | La evidencia operacional acredita ejecución semanal, pero no acredita por sí sola el cumplimiento del indicador de eficiencia. | RCA 69/2023; informes técnicos de barrido mecanizado enero-junio 2026. | Informes operacionales muestran rutas, maquinaria y frecuencia, pero el indicador depende de mediciones específicas. | Alto: se podría confundir ejecución con cumplimiento de indicador. | Separar evidencia de ejecución de evidencia de eficiencia en cualquier anexo o informe final. | Alta | Abierta |
| NC-AIRE-006 | Malla Netport | Se ubicó base técnica para Bosque Mina Santos, pero no se acredita todavía todo el alcance de la obligación RCA asociada a ampliación depósito Nantoco, acopios y frentes. | RCA 69/2023, obligación AIRE-RCA-007 / medida malla Netport. | `BT_Malla_Netport_Bosque_Rev.1_DPRO_04.06.2026.docx.pdf` respalda un sector, no necesariamente toda la medida. | Alto: cobertura espacial insuficiente. | Solicitar ubicación de mallas, fotos, inspecciones, mantención, mediciones dentro/fuera y reportes SMA por sector RCA. | Alta | Abierta |
| NC-AIRE-007 | Malla Netport | Falta acreditar reducción de velocidad de viento de 85% y monitoreo mensual dentro/fuera durante el primer año. | RCA 69/2023 / compromiso de reducción y monitoreo. | Antecedente ubicado es principalmente base técnica/contrato, no medición de desempeño. | Alto: indicador de eficacia no cerrado. | Solicitar informes de instalación, monitoreo mensual, datos de viento y cálculo de reducción. | Alta | Abierta |
| NC-AIRE-008 | Plantación árboles nativos | La evidencia encontrada acredita planificación/avance, pero no ejecución final, georreferenciación, inventario de individuos, prendimiento 95% ni captación MP2,5. | RCA 69/2023 / medida de plantación; informes Bosque Santos. | Informes junio-julio 2026 indican preparación y plantación programada, no cierre de medida. | Alto: medida compensatoria queda abierta. | Verificar ejecución posterior a septiembre 2026, KMZ/shapefile, registros de plantación, riego, mantención, censo y cálculo i-Tree Eco o similar. | Alta | Abierta |
| NC-AIRE-009 | Plataforma web / monitoreo en línea | La evidencia OCR respalda gestiones SINCA/SMA y QMonitor, pero no acredita plataforma pública/comunitaria, URL, disponibilidad ni MP10 en tiempo real según RCA. | RCA 69/2023 / obligación AIRE-RCA-004; DOC-1346 OCR. | DOC-1346 acredita conexión/gestiones y criterios LIN[v]/LIN[M]/VAL, pero no reemplaza prueba de plataforma web. | Alto: obligación web no cerrada. | Solicitar URL, fecha de marcha blanca/operación, bitácoras, pantallazos, logs y estaciones/parámetros publicados. | Alta | Abierta |
| NC-AIRE-010 | SINCA / TAMA | DOC-1346 indica gestiones de conexión y criterios técnicos, pero también evidencia interrupción o ausencia de registros recientes en SINCA, con último dato recibido informado al 01-01-2025. | Res. 4612/2025; obligación de conexión/transmisión; DOC-1346 OCR. | Revisión OCR SINCA/Datos Históricos. | Alto: puede afectar continuidad de reportabilidad en línea. | Revisar fecha real de restablecimiento, logs de transmisión y respaldo de datos enviados/publicados. | Alta | Abierta |
| NC-AIRE-011 | Datos históricos discretos | DOC-1347 y DOC-1348 respaldan entrega de datos históricos 2020-2025, pero falta validar contenido de planillas si se requiere auditoría de datos. | Res. 4612/2025; DOC-1347 y DOC-1348 OCR. | OCR acredita envío/entrega, no revisión cuantitativa del contenido de cada base. | Medio: suficiente documentalmente, insuficiente para auditoría de datos. | Validar anexos Excel: estación, parámetro, periodo, completitud, códigos de validación e integridad. | Media | Parcialmente respaldada |
| NC-AIRE-012 | Resolución final programas MP | No se localizó resolución exenta final que apruebe los Programas de Control de Emisiones de MP de CCMC y CCMO. | Res. 4612/2025; Ord. 1859/2026; Ord. 1857/2026. | Hay antecedentes “sin observaciones”, pero no resolución final localizada. | Alto: hito regulatorio posterior queda sin cierre documental. | Buscar correspondencia posterior al 23-03-2026 o solicitar resolución final a contraparte. | Alta | Abierta |
| NC-AIRE-013 | Humectación | Enero-febrero 2026 queda bajo régimen transicional, por lo que no debe mezclarse automáticamente exigencia 80% con 85%. | RCA 133/2015, RCA 69/2023, respuesta ORA 70, informes humectación. | Matriz de brechas BD-AIRE-006. | Medio: riesgo de evaluar meses con criterio incorrecto. | Construir línea de tiempo de exigibilidad por mes y asociar mediciones DustMate con criterio aplicable. | Media | Abierta |
| NC-AIRE-014 | Humectación / reportabilidad | Se detectó fecha “31 de septiembre” para reporte semestral; septiembre tiene 30 días. | RCA / obligación de reporte semestral del plan de humectación. | Log de revisión documental registra la inconsistencia. | Bajo-Medio: error formal que puede generar ambigüedad de plazo. | Confirmar interpretación práctica del plazo o corregir en matriz como observación formal. | Media | Abierta |
| NC-AIRE-015 | Monitoreo estaciones | No está calculada la disponibilidad efectiva por estación/parámetro desde anexos Excel 1T/2T 2026. | Res. 1449/2023; RCA seguimiento; anexos Excel 1T/2T 2026; NC SGS. | Matriz de brechas BD-AIRE-010. | Alto: no se puede cerrar continuidad/confiabilidad de monitoreo. | Automatizar extracción por estación, parámetro, datos válidos, inválidos y causa de invalidación. | Alta | Abierta |
| NC-AIRE-016 | MPS PS4 Mina | MPS PS4 Mina supera referencia durante todo 1S 2026, pero falta análisis de causalidad/representatividad. | Informes 1T/2T 2026; NC MPS; estaciones MPS. | Matriz de brechas BD-AIRE-011. | Alto: riesgo ambiental y regulatorio persistente. | Revisar viento, operación, fuente dominante, QA/QC, pesajes, calibración y medidas de control. | Alta | Abierta |
| NC-AIRE-017 | Nantoco MP10 | Nantoco MP10 continuo presenta 11 días ≥130 µg/m³N en 2T 2026, sin cruce completo de episodios. | Informe 2T 2026; anexos Nantoco. | Matriz de brechas BD-AIRE-012. | Medio-Alto: requiere análisis de episodios y causalidad. | Extraer fechas, validar datos, cruzar meteorología, operación y medidas aplicadas. | Alta | Abierta |
| NC-AIRE-018 | ICE / expediente | No se localizó documento ICE autónomo en antecedentes, aunque la RCA lo cita como referencia. | Expediente evaluación / RCA. | Matriz de brechas BD-AIRE-017 y solicitud SOL-AIRE-001. | Medio: limita trazabilidad completa del expediente de evaluación. | Solicitar ICE o localizarlo en expediente SEIA/archivo interno. | Media | Abierta |
| NC-AIRE-019 | Inicio de ejecución/operación | Falta comunicación formal de hito de inicio de ejecución y operación para activar plazos específicos. | RCA 69/2023 / plazos de medidas: web 9 meses, caminos mes 1, barrido/plantación. | Solicitud SOL-AIRE-002. | Alto: sin fecha gatillo no se puede evaluar oportunidad de implementación. | Solicitar carta/hito formal y usarla como línea base cronológica. | Alta | Abierta |
| NC-AIRE-020 | Eventos de viento intenso | Eventos de viento intenso no han sido cruzados con activación operacional preventiva. | Res. 4612/2025; programas de control; meteorología operacional. | Matriz de brechas BD-AIRE-008. | Medio: no se puede acreditar respuesta operacional ante condiciones críticas. | Cruzar alertas/datos viento con bitácoras, rutas, supresores, detenciones o medidas reforzadas. | Media | Abierta |

## Checklist de cierre por no coincidencia

Antes de considerar cerrada cualquiera de las no coincidencias anteriores, verificar que exista:

1. Fuente primaria identificada con nombre de archivo, sección/página cuando sea posible y fecha.
2. Criterio de comparación explícito: obligación, indicador, plazo, longitud, estación, parámetro o tramo.
3. Evidencia que resuelva la diferencia, no solo evidencia relacionada.
4. Estado actualizado en la matriz correspondiente: brecha, solicitud de información, evidencia RCA/EIA o Excel final.
5. Registro en `06_Log/Log_Cambios.md` si cambia el estado de abierta a parcial o cerrada.

## Relación con matrices existentes

Esta matriz complementa, no reemplaza, los siguientes archivos:

- `04_Matrices/Matriz_Brechas_Documentales_Aire.md`
- `04_Matrices/Matriz_Caminos_Compensatorios_ORA70_2026.md`
- `04_Matrices/Matriz_Solicitudes_Informacion_Cierre.md`
- `04_Matrices/Matriz_Evidencia_RCA_EIA_Reforzada_2026.md`
- `04_Matrices/Matriz_Candelaria_Aire_Revision_Documental_2026.xlsx`

## Próxima actualización sugerida

Cuando se reciba nueva evidencia, actualizar primero esta matriz con el estado de cada no coincidencia y luego reflejar el cierre en la matriz Excel y en la matriz de brechas documentales.
