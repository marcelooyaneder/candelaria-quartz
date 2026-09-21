# Control preliminar anexos Excel monitoreo 2026

Estado: extracción automática preliminar desde anexos Excel 1T/2T 2026. Debe revisarse contra el informe PDF y criterios QA/QC antes de usar como conclusión final.

Archivo fuente CSV: `04_Matrices/Control_Anexos_Excel_Monitoreo_2026.csv`.

## Calidad del aire

| Archivo | Hoja | Filas con fecha | Datos numéricos | Nulos/no numéricos | Máximo col. B | Promedio col. B | Conteo ≥130 | Lectura preliminar |
|---|---|---:|---:|---:|---:|---:|---:|---|
| A 5.1 E MP-10 CALDERA Enero 2026.xlsx | MP-10 Valida | 744 | 10 | 734 | 47.0 | 20.9 | 0 | Caldera MP10 discreto sin valores ≥130 en estos anexos. |
| A 5.1 E MP-10 CALDERA Enero 2026.xlsx | MP-10 Inválida | 744 | 0 | 744 |  |  | 0 | Caldera MP10 discreto sin valores ≥130 en estos anexos. |
| A 5.2 E MP-10 CALDERA Febrero 2026.xlsx | MP-10 Valida | 744 | 8 | 736 | 34.0 | 22.375 | 0 | Caldera MP10 discreto sin valores ≥130 en estos anexos. |
| A 5.2 E MP-10 CALDERA Febrero 2026.xlsx | MP-10 Inválida | 744 | 0 | 744 |  |  | 0 | Caldera MP10 discreto sin valores ≥130 en estos anexos. |
| A 5.3 E MP-10 CALDERA Marzo 2026.xlsx | MP-10 Valida | 744 | 10 | 734 | 36.0 | 24.5 | 0 | Caldera MP10 discreto sin valores ≥130 en estos anexos. |
| A 5.3 E MP-10 CALDERA Marzo 2026.xlsx | MP-10 Inválida | 744 | 0 | 744 |  |  | 0 | Caldera MP10 discreto sin valores ≥130 en estos anexos. |
| A 5.4 E MP-10 CALDERA Abril 2026.xlsx | MP-10 Valida | 744 | 8 | 736 | 77.0 | 27.875 | 0 | Caldera MP10 discreto sin valores ≥130 en estos anexos. |
| A 5.4 E MP-10 CALDERA Abril 2026.xlsx | MP-10 Inválida | 744 | 0 | 744 |  |  | 0 | Caldera MP10 discreto sin valores ≥130 en estos anexos. |
| A 5.5 E MP-10 CALDERA Mayo 2026.xlsx | MP-10 Valida | 744 | 10 | 734 | 39.0 | 22.2 | 0 | Caldera MP10 discreto sin valores ≥130 en estos anexos. |
| A 5.5 E MP-10 CALDERA Mayo 2026.xlsx | MP-10 Inválida | 744 | 0 | 744 |  |  | 0 | Caldera MP10 discreto sin valores ≥130 en estos anexos. |
| A 5.5 Formato_SEREMI SALUD_ Nantoco Mayo 2026.xlsx | MP-10 Data Valida | 744 | 744 | 0 | 705.12 | 103.316 | 163 | Nantoco mayo muestra episodios horarios altos; requiere cálculo diario y validación. |
| A 5.5 Formato_SEREMI SALUD_ Nantoco Mayo 2026.xlsx | MP-10 Inválida | 744 | 0 | 744 |  |  | 0 | Nantoco mayo muestra episodios horarios altos; requiere cálculo diario y validación. |
| A 5.5 Formato_SEREMI SALUD_ Nantoco Mayo 2026.xlsx | MP-2.5 Data Valida | 744 | 744 | 0 | 68.2 | 19.142 | 0 | MP2,5 Nantoco sin valores ≥130; revisar contra umbral normativo de MP2,5, no MP10. |
| A 5.5 Formato_SEREMI SALUD_ Nantoco Mayo 2026.xlsx | MP-2.5 Inválida | 744 | 0 | 744 |  |  | 0 | MP2,5 Nantoco sin valores ≥130; revisar contra umbral normativo de MP2,5, no MP10. |
| A 5.6 E MP-10 CALDERA Junio 2026.xlsx | MP-10 Valida | 720 | 10 | 710 | 37.0 | 24.5 | 0 | Caldera MP10 discreto sin valores ≥130 en estos anexos. |
| A 5.6 E MP-10 CALDERA Junio 2026.xlsx | MP-10 Inválida | 720 | 0 | 720 |  |  | 0 | Caldera MP10 discreto sin valores ≥130 en estos anexos. |

## Meteorología

Para hojas de viento, el campo `Conteo ≥130` del CSV no debe interpretarse como superación ambiental: en dirección del viento corresponde a grados. La utilidad principal aquí es disponibilidad de datos numéricos e invalidaciones.

| Archivo | Hoja | Filas con fecha | Datos numéricos | Nulos/no numéricos | Máximo col. B | Promedio col. B | Lectura preliminar |
|---|---|---:|---:|---:|---:|---:|---|
| A 5.1 EM MINA Enero 2026.xlsx | Vel Data Valida | 744 | 558 | 186 | 7.947 | 2.488 | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.1 EM MINA Enero 2026.xlsx | Vel Inválida | 744 | 0 | 744 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.1 EM MINA Enero 2026.xlsx | Dir Data Valida | 744 | 558 | 186 | 356.4 | 111.356 | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.1 EM MINA Enero 2026.xlsx | Dir Inválida | 744 | 0 | 744 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.1 EM PUERTO Enero 2026.xlsx | Vel Data Valida | 744 | 735 | 9 | 9.11 | 3.842 | Alta completitud aparente |
| A 5.1 EM PUERTO Enero 2026.xlsx | Vel Inválida | 744 | 0 | 744 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.1 EM PUERTO Enero 2026.xlsx | Dir Data Valida | 744 | 744 | 0 | 339.89 | 232.76 | Alta completitud aparente |
| A 5.1 EM PUERTO Enero 2026.xlsx | Dir Inválida | 744 | 0 | 744 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.2 EM MINA Febrero 2026.xlsx | Vel Data Valida | 744 | 567 | 177 | 9.11 | 2.429 | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.2 EM MINA Febrero 2026.xlsx | Vel Inválida | 744 | 0 | 744 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.2 EM MINA Febrero 2026.xlsx | Dir Data Valida | 744 | 567 | 177 | 313.19 | 130.503 | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.2 EM MINA Febrero 2026.xlsx | Dir Inválida | 744 | 0 | 744 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.2 EM PUERTO Febrero 2026.xlsx | Vel Data Valida | 744 | 672 | 72 | 9.23 | 3.768 | Alta completitud aparente |
| A 5.2 EM PUERTO Febrero 2026.xlsx | Vel Inválida | 744 | 0 | 744 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.2 EM PUERTO Febrero 2026.xlsx | Dir Data Valida | 744 | 672 | 72 | 357.7 | 222.54 | Alta completitud aparente |
| A 5.2 EM PUERTO Febrero 2026.xlsx | Dir Inválida | 744 | 0 | 744 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.3 EM MINA Marzo 2026.xlsx | Vel Data Valida | 744 | 734 | 10 | 7.55 | 1.982 | Alta completitud aparente |
| A 5.3 EM MINA Marzo 2026.xlsx | Vel Inválida | 744 | 0 | 744 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.3 EM MINA Marzo 2026.xlsx | Dir Data Valida | 744 | 732 | 12 | 312.5 | 108.956 | Alta completitud aparente |
| A 5.3 EM MINA Marzo 2026.xlsx | Dir Inválida | 744 | 0 | 744 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.3 EM PUERTO Marzo 2026.xlsx | Vel Data Valida | 744 | 744 | 0 | 9.59 | 3.217 | Alta completitud aparente |
| A 5.3 EM PUERTO Marzo 2026.xlsx | Vel Inválida | 744 | 0 | 744 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.3 EM PUERTO Marzo 2026.xlsx | Dir Data Valida | 744 | 744 | 0 | 346.0 | 216.952 | Alta completitud aparente |
| A 5.3 EM PUERTO Marzo 2026.xlsx | Dir Inválida | 744 | 0 | 744 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.4 EM MINA Abril 2026.xlsx | Vel Data Valida | 720 | 719 | 1 | 5.46 | 1.594 | Alta completitud aparente |
| A 5.4 EM MINA Abril 2026.xlsx | Vel Inválida | 720 | 0 | 720 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.4 EM MINA Abril 2026.xlsx | Dir Data Valida | 720 | 701 | 19 | 335.0 | 97.193 | Alta completitud aparente |
| A 5.4 EM MINA Abril 2026.xlsx | Dir Inválida | 720 | 0 | 720 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.4 EM PUERTO Abril 2026.xlsx | Vel Data Valida | 720 | 720 | 0 | 9.46 | 3.029 | Alta completitud aparente |
| A 5.4 EM PUERTO Abril 2026.xlsx | Vel Inválida | 720 | 0 | 720 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.4 EM PUERTO Abril 2026.xlsx | Dir Data Valida | 720 | 720 | 0 | 351.0 | 195.412 | Alta completitud aparente |
| A 5.4 EM PUERTO Abril 2026.xlsx | Dir Inválida | 720 | 0 | 720 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.5 EM MINA Mayo 2026.xlsx | Vel Data Valida | 744 | 744 | 0 | 5.36 | 1.142 | Alta completitud aparente |
| A 5.5 EM MINA Mayo 2026.xlsx | Vel Inválida | 744 | 0 | 744 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.5 EM MINA Mayo 2026.xlsx | Dir Data Valida | 744 | 703 | 41 | 282.0 | 101.73 | Alta completitud aparente |
| A 5.5 EM MINA Mayo 2026.xlsx | Dir Inválida | 744 | 0 | 744 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.5 EM PUERTO Mayo 2026.xlsx | Vel Data Valida | 744 | 744 | 0 | 8.79 | 3.141 | Alta completitud aparente |
| A 5.5 EM PUERTO Mayo 2026.xlsx | Vel Inválida | 744 | 0 | 744 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.5 EM PUERTO Mayo 2026.xlsx | Dir Data Valida | 744 | 744 | 0 | 348.0 | 192.008 | Alta completitud aparente |
| A 5.5 EM PUERTO Mayo 2026.xlsx | Dir Inválida | 744 | 0 | 744 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.6 EM MINA Junio 2026.xlsx | Vel Data Valida | 720 | 720 | 0 | 5.43 | 1.274 | Alta completitud aparente |
| A 5.6 EM MINA Junio 2026.xlsx | Vel Inválida | 720 | 0 | 720 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.6 EM MINA Junio 2026.xlsx | Dir Data Valida | 720 | 703 | 17 | 303.0 | 116.117 | Alta completitud aparente |
| A 5.6 EM MINA Junio 2026.xlsx | Dir Inválida | 720 | 0 | 720 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.6 EM PUERTO Junio 2026.xlsx | Vel Data Valida | 720 | 720 | 0 | 9.54 | 3.119 | Alta completitud aparente |
| A 5.6 EM PUERTO Junio 2026.xlsx | Vel Inválida | 720 | 0 | 720 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |
| A 5.6 EM PUERTO Junio 2026.xlsx | Dir Data Valida | 720 | 720 | 0 | 339.0 | 179.417 | Alta completitud aparente |
| A 5.6 EM PUERTO Junio 2026.xlsx | Dir Inválida | 720 | 0 | 720 |  |  | Disponibilidad menor; revisar invalidaciones/comentarios |

## Hallazgos automáticos relevantes

- En Caldera, los anexos mensuales de MP10 discreto enero-junio 2026 no muestran valores de columna B ≥130 µg/m³N; máximos mensuales extraídos: 47, 34, 36, 77, 39 y 37.

- En Nantoco mayo 2026, la hoja `MP-10 Data Valida` contiene 744 datos horarios, máximo 705,12 y 163 registros horarios ≥130. Esto no equivale directamente a días normativos; debe agregarse a promedio diario y validarse con códigos/criterios.

- En Nantoco mayo 2026, la hoja `MP-2.5 Data Valida` contiene 744 datos horarios, máximo 68,2 y promedio 19,142. Debe evaluarse con norma MP2,5 aplicable, no con el umbral MP10 de 130.

- Las planillas meteorológicas Mina/Puerto contienen hojas válidas e inválidas para velocidad y dirección; la disponibilidad numérica aparente es suficiente para cruzar episodios, pero debe revisarse por mes debido a nulos y códigos de invalidación.


## Limitaciones

- La extracción usa columna B por hoja, por lo que sirve como control rápido, no como validación oficial.

- No se localizaron planillas Excel TAMA en los anexos trimestrales 2026 listados; TAMA debe extraerse desde tablas PDF u otros respaldos.

- Para MP10 continuo corresponde convertir datos horarios a promedios diarios válidos antes de comparar contra 130 µg/m³N.

- Para muestreos discretos se debe confirmar fecha/filtro válido y aplicar los códigos de invalidación Res. 1449/2023.
