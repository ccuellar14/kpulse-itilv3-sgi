# Tabla de Descripción de Subproceso

---

| ID Actividad | Actividad | Entrada | Descripción de Actividad | Salida | Rol - Participante |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | Registrar el user ID de quien reporta el incidente | Incidente reportado | Registrar el user ID de la persona que comunica el incidente. | Incidente en registro | E: Soporte de incidentes 1o Nivel |
| 2 | Verificar Nombre, Fecha y hora del incidente | Incidente en registro | Verificar el registro de la fecha y hora en que se presentó el incidente. | Incidente en registro | E: Soporte de incidentes 1o Nivel |
| 3 | Obtener detalles del incidente | Incidente en registro | Registra detalles del incidente, tales como Software/hardware afectado, tiempo de inactividad, personas afectadas. | Incidente en registro | E: Soporte de incidentes 1o Nivel |
| 4 | Tipificar o Clasificar incidente  | Incidente en registro | Tipificar y Clasificar el incidente reportado en el sistema de manera correcta para poder obtener posteriormente las métricas y reportes del sistema | Incidente en registro | E: Soporte de incidentes 1o Nivel |
| 5 | Registrar el estado del incidente | Incidente en registro | Registrar el  incidente en  estado ABIERTO y generar el número de ticket en el registro de incidentes. | Incidente registrado | E: Soporte de incidentes 1o NivelI: Gestor de Incidentes |
| 6 | Comunicar el número de Ticket | Número de Ticket | Comunicar al usuario el numero de ticket de la siguiente manera:-Si el reporte del incidente es por teléfono el Agente le indica el número del ticket en ese momento porque está con el CA ServiceDesk ingresando los datos del usuario y del incidente.-Si el incidente es reportado por Correo el Agente le responde por esta vía el número de Ticket generado por el CA ServiceDesk al ingresar la información que contiene el correo.-Si el reporte es por la intranet [http://centrodeservicios](http://centrodeservicios/) la asignación del número de ticket es inmediato asignado por el CA ServiceDesk. | Número de ticket comunicado | E: Soporte de Incidentes 1° NivelI: Usuario |


