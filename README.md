# Requerimientos solicitados para la Validación de SAP

## A continuación se detallan los requerimientos indicados por la consultora de validación ITQA en el documento de Análisis de Riesgo enviado oportunamente y por los Asesores Externos** de INVIMA.

> ITQA es una consultora especializada en Validación de Sistemas Computarizados, de Control y Sistemas de Calidad para la industria Farmacéutica.

> Los Asesores Externos de INVIMA pre-auditaron la Empresa en de cara a la auditoría oficial del Instituto Nacional de Vigilancia de Medicamentos y Alimentos de Colombia (INVIMA)


- **Copias de seguridad y período de retención**
	- El sistema debe estar cubierto por un procedimiento de Backup que asegure la gestión de las copias de respaldo. Este proceso debe ser gestionado por el proveedor de servicios SAP.
	- Las copias de seguridad diarias, semanales o mensual deben ser almacenadas dentro de sitios ignífugos mientras no estén en sus lugares definitivos de archivo.
	- Se debe asegurar que las copias de seguridad definitivas sean almacenadas en un ambiente o edificio distinto del cual se encuentran los servidores de aplicación durante todo el período de retención.
	- Debe asegurarse el acceso a los datos durante todo período de retención.
		> Verificar alcance y vigencia del procedimiento de verificación de acceso a medios de almacenamiento archivados y que el personal alcanzado se encuentra capacitado.

- **Disaster Recovery**
	- El sistema debe estar cubierto por un procedimiento de Restauración que asegure la puesta en marcha de este ante una avería irreparable. Este proceso debe ser gestionado por el proveedor de servicios SAP.
	- El sistema debe estar cubierto por un procedimiento de Disaster Recovery que asegure la puesta en funcionamiento del sistema en caso de desastre. Este proceso debe ser gestionado por el proveedor de servicios SAP.
	- Debe estar disponible un SOP que especifique las acciones que deben realizarse cuando ocurra un fallo en el sistema.


- **Ambientes de Operación**
	- El sistema debe poseer un ambiente de Producción (ambiente real de trabajo) y un ambiente de Testing, que permita realizar las pruebas de aceptación de los cambios a solicitados y entrenamientos. Cada ambiente debe tener sets de datos independientes.
		> Falta la verificación documental

- **Servicio**
	- Deben existir contratos de nivel de servicio firmado entre el laboratorio y el proveedor del servicio SAP.
	- Debe existir un contrato de confidencialidad de la información de ambas partes.
	- Debe realizarse una auditoría al proveedor del sistema.

- **Performance**
	- El sistema debe ser capaz de almacenar la información que genera, por lo que debe verificarse el espacio disponible en disco.
	- El sistema debe ser multiusuario con conexión simultánea, permitiendo sólo una sesión por usuario a la vez. Debe verificarse que no se produzcan cierres inesperados debido a que el sistema no soporte numerosos usuarios conectados simultáneamente.

- **Interfase con software de Central de Pesadas**
	- La información transferida al software de central de pesadas debe ser consistente para evitar pérdida o corrupción de datos GMP relaventes.
	- La información suministrada por el software de central de pesadas debe ser procesada consistentemente y sin errores para evitar pérdida, corrupción, omisión y/o reprocesamiento de datos GMP relevantes.

- **Generación de lotes**
    - Validar el módulo de SAP que asigna número de lote logístico

- **Seguridad lógica**
	- Todos los servidores del sistema deben estar cubiertos por antivirus y la gestión realizada por el proveedor de servicios SAP. Debe verificarse la existencia y que se encuentren actualizados.
	- El sistema debe soportar Firma Electrónica o cualquier otro método alterno que permita certificar que las personas que acceden a él son las mismas que ejecutan las acciones sobre los datos.
	- El sistema debe permitir que la complejidad, caducidad y repetición de la contraseña sea parametrizable.
	- El sistema debe deshabilitar los usuarios que hayan estado inactivos por mas de 30 días.
	- El sistema debe bloquear la cuenta de los usuarios que intentan infructuosamente loguearse a él.
	- El sistema debe permitir que la duración de la sesión sea parametrizable.
	- El sistema debe permitir la visualización del historial del perfil de un usuario.
	- La gestión de usuarios (altas, bajas y modificaciones), debe ser realizada por el proveedor de servicios SAP.

- **Audit Trail**
	- El sistema debe almacenar el historial de modificaciones de:
		- Usuarios y perfiles
		- Recetas
		- Ordenes de producción
		- Materiales
		- Movimientos de material
		- Lote de material
		- Lote de inspección
		- Decisión de empleo
	- La auditoría debe almacenar 
		- Nombre de usuario
		- Fecha y hora de la modificación (no debe ser tomada del cliente)
		- Tipo de modificación
		- Dato nuevo y dato anterior
	- El Audit Trail debe ser inalterable y debe ser retenido el mismo periodo tiempo que los datos.

- **Seguridad física**
	- Los servidores deben instalarse en racks protegidos con llave del centro de cómputos.
	- La temperatura y humedad del ambiente de operación de los servidores debe estar controlada.
	- Debe existir un sistema de control/registro de acceso de personas al recinto donde se encuentran los servidores del sistema.
	- Debe existir un procedimiento de monitoreo de seguridad para el recinto donde se encuentran los servidores del sistema.
	- El recinto que aloja los servidores debe estar protegido contra incendios.
	- Los servidores deben seguir operando frente a cortes en el suministro eléctrico.

- **Disponibilidad y confiabilidad**
	- El sistema debe estar disponible las 24 horas de los 7 días de la semana todos los meses del año.
	- El sistema debe poseer una tasa de falla catastrófica de menos de una ocurrencia por mes (caída del sistema, cuelgue, corte de servicio).
	- El sistema no debe permanecer fuera de línea por más de 1 día.

- **Escalabilidad**
	- El sistema debe poseer capacidad de expansión ante la necesidad de incorporar nuevas funcionalidades.

- **Soporte**
	- El sistema debe contar con un nivel de soporte externo.
	- Se debe garantizar que el proveedor de soporte durante un período previamente acordado cubriendo aspectos técnicos y de operación.
		> Verificar que existen contratos de soporte que cubran el soporte técnico, de operación y on site.

- **Manuales y especificaciones**
	- Deben estar vigentes los Manuales de usuario del sistema o POEs de uso.
	- Debe estar vigente documentación de la descripción funcional del sistema.
	- Debe estar vigente un listado de las aplicaciones y versión instaladas.
  
