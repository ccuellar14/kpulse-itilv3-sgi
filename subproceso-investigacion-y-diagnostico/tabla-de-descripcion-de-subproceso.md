# Tabla de Descripción de Subproceso

---

| ID Actividad | Actividad | Entrada | Descripción de la Actividad | Salida | **Rol – Participante** |
| --- | --- | --- | --- | --- | --- |
| 1 | Buscar solución o workaround en la BDC | Incidente registrado | Buscar en la BDC si existe una solución temporal o definitiva para el incidente. | Resultado de la búsqueda de soluciones en la BDC | E: Soporte de incidentes 1o / No Nivel |
| 2 | ¿Existen solución o workaround en la BDC? | Resultado de la búsqueda de soluciones en la BDC | Si: Continúa con actividad 4No: Continúa con actividad 3 |   | E: Soporte de incidentes 1o / No Nivel |
| 3 | Investigar y diagnosticar | Incidente registrado | Comparar el incidente en el registro de errores conocidos, problemas, soluciones, cambios planeados o bases de información para hallar ocurrencias similares, investigar posible solución.Diagnosticar luego de revisar, investigar y analizar la información obtenida a través de la data histórica del incidente | Incidente diagnosticado | E: Soporte de incidentes 1o / No Nivel |
| 4 | ¿Se requiere de un cambio? | Incidente diagnosticado | Si: Continúa con proceso GCAMB00100No: Fin del subproceso |   | E: Soporte de incidentes 1o / No Nivel |
| GCAMB00100 | Gestión de Cambios | Incidente diagnosticadoCambio propuesto | Registrar la orden de cambio para la restauración del CI y/o servicio(s) afectado(s) y comunicar al gestor de cambios para seguimiento de su aprobación. | Cambio cerrado | R: Gestor de Cambios |