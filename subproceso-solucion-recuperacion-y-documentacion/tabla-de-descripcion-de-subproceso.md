# Tabla de Descripción de Subproceso

---



| ID Actividad | Actividad | Entrada | Descripción de la Actividad | Salida | **Rol – Participante** |
| --- | --- | --- | --- | --- | --- |
| 1 | Solucionar y Recuperar | Incidente diagnosticadoSolución propuesta | Resolver el incidente ejecutando las soluciones temporales ó definitivas recuperando el servicio y minimizando el impacto en el negocio. | Servicio recuperado | E: Soporte de incidentes 1o / No Nivel |
| 2 | Actualizar el estado del incidente | Servicio recuperado | Actualizar el estado del incidente en el registro de Incidentes. | Incidente solucionado | E: Soporte de incidentes 1o / No Nivel |
| 3 | Registrar la solución del incidente | Incidente solucionado | Se debe registrar en la herramienta como se llevo a cabo la solución de dicho incidente. | Incidente solucionado (solución registrada) | E: Soporte de incidentes 1o / No Nivel |
| 4 | ¿Solución en base a documentos de la BDC? | Incidente solucionado | Si: Continúa con actividad 6No: Continúa con actividad 5 |   | E: Soporte de incidentes 1o / No Nivel |
| 5 | ¿La solución requiere documentación? | Incidente solucionado | Si: Continúa con actividad 7No: Fin del proceso |   | E: Soporte de incidentes 1o / No Nivel |
| 6 | Adjuntar documento al incidente y calificarlo | Incidente solucionadoDocumento en la BDC | Se adjunta el documento al incidente y se le califica. | Incidente solucionado (documentación en BDC adjunta) | E: Soporte de incidentes 1o / No Nivel |
| 7 | Documentar la solución en la BDC | Incidente solucionado | Se documentan las soluciones de los incidentes en la BDC no solo como un sustento de la solución, si no como un repositorio de conocimiento. Para ello se sigue el Procedimiento de Gestión de Conocimiento descrito en los documentos &quot;Manual del Agente de Centro de Servicios&quot; y &quot;Manual del Especialista de Soporte&quot;. | Documento de solución creado en la BDC | E: Soporte de incidentes 1o / No Nivel |