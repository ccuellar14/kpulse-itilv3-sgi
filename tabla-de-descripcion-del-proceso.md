# Tabla de Descripción del Proceso

---

| ID Actividad | Actividad | Entrada | Descripción de la Actividad | Salida | Rol-Participante |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | Reportar Ocurrencias | Ocurrencia Detectada | Se reporta ocurrencia mediante Jira | Ocurrencia Reportada | E: Usuario |
| 2 | ¿Incidente? | Ocurrencia Reportada | SI: Continua / NO: Continúa con Actividad 16 |  | E: Soporte de Incidentes 1er Nivel / C: Usuario |
| GINCI00110 | Registro y Clasificación | Incidente Reportado | Se registra, clasifica y determina grado de severidad del incidente | Incidente Registrado | E: Soporte de incidetes 1er Nivel |
| 3 | ¿El incidente esta sociado a un problema? | Incidente registrado | SI: Continúa con SubProceso GINCI00120 / NO: Continúa con Actividad 4 |  | E: Soporte de incidentes 1er Nivel |
| 4 | ¿Incidente de alto impacto o prioridad 1? | Incidente registrado | SI: Continúa con actividad 5.NO: Continúa con actividad 6. |   | E: Soporte de incidentes 1o / No Nivel |
| 5 | ¿Ya existe un problema relacionado? | Incidente registrado | SI: Continúa con actividad 7.NO: Continúa con actividad 8. |   | E: Soporte de incidentes 1o / No Nivel |
| 6 | ¿Existen múltiples incidentes similares? | Incidente registrado | SI: Continúa con actividad 5.NO: Continúa con subproceso GINCI00120. |   | E: Soporte de incidentes 1o / No Nivel |
| 7 | Asociar incidente al problema | Incidente registradoProblema relacionado | Se asocia el incidente con un problema previamente reportado. | Incidente registrado (asociado a problema) | E: Soporte de incidentes 1o / No Nivel |
| 8 | ¿Soporte Nivel &gt; 1? | Incidente registrado | SI: Continúa con subproceso GINCI00120 y con proceso GPROB00100.NO: Continúa con subproceso GINCI00120. |   | E: Soporte de incidentes 1o / No Nivel |
| GINCI00120 | Investigación y Diagnóstico | Incidente registrado | Se busca en la BDC la solución, si no se encuentra se investiga y diagnostica. Se efectúan cambios para implementar la solución, de ser necesario. | Incidente diagnosticado | E: Soporte de incidentes 1o / No Nivel |
| 9 | ¿Se puede resolver en el nivel actual? | Incidente diagnosticado | SI: Continúa con subproceso GINCI00130.NO: Continúa con actividad 10. |   | E: Soporte de incidentes 1o / No Nivel |
| 10 | Reasignar o escalar a nivel correspondiente | Incidente que requiere transferencia | Se reasigna o escala un incidente que no tiene solución en este nivel. | Incidente reasignado | E: Soporte de incidentes 1o / No Nivel |
| PROCITIL130 | Solución, Recuperación y Documentación | Incidente diagnosticadoSolución propuesta | Se da la solución encontrada se recupera el servicio, se registra y se documenta. | Incidente solucionado  | E: Soporte de incidentes 1o / No Nivel |
| 11 | ¿Se encontró la causa raíz? | Incidente solucionado | SI: Continúa con actividad 12.NO: Continúa con actividad 13. |   | E: Soporte de incidentes 1o / No Nivel |
| 12 | ¿Soporte Nivel &gt; 1? | Incidente solucionado | SI: Continúa con proceso GPROB00100 y actividad 13.NO: Continúa con actividad 14. |   | E: Soporte de incidentes 1o / No Nivel |
| 13 | ¿Probabilidad de Recurrencia? | Incidente solucionado | SI: Continúa con proceso GPROB00100 y actividad 14.NO: Continúa con actividad 14. |   | E: Soporte de incidentes 1o / No Nivel |
| 14 | Validar solución de incidente | Incidente solucionado | Llamar por teléfono o enviar mail solicitando al usuario la conformidad de la atención de la incidencia reportada.Si el usuario no responde al mensaje enviado vía mail  dentro de las 24 horas se asumirá como solucionado el incidente y se actualizará el Sistema. | Conformidad de atención | E: Soporte de incidentes 1o / No Nivel |
| 15 | ¿Usuario lo considera resuelto? | Incidente solucionado | SI: Continúa con proceso GINCI00140NO: Retorna a subproceso GINCI00120. |   | E: Soporte de incidentes 1o / No Nivel |
| PROCITIL140 | Validación y Cierre | Incidente solucionadoConformidad del usuario | Si el usuario da su conformidad a la solución del incidente,  se procede a cerrar el ticket. | Incidente cerrado | E: Soporte de incidentes 1o / No Nivel |
| PROCITIL150 | Seguimiento y Verificación del proceso | Incidentes | Se generan informes ejecutivos para la Gerencia de Operaciones TI para su análisis incluyendo sus recomendaciones. | Informes Ejecutivos | E: Gestor de Incidentes |
| 16 | Gestionar Solicitud de Servicio | Solicitud de Servicio reportada | Se atiende la solicitud según el Procedimiento de Solicitud de Servicio descrito en los documentos &quot;Manual del Agente de Centro de Servicios&quot; y &quot;Manual del Especialista de Soporte&quot;. | Solicitud de Servicio cerrada | E: Soporte de incidentes 1o / No Nivel |
| PROCITIL200 | Gestión de Problemas | Problema detectado | Se ejecuta el proceso de Gestión de Problemas. | Problema cerrado | R: Gestor de Problemas |





