Descripción del Problema
Este error ocurre cuando se recibe una solicitud de alojamiento con un grupo de habitaciones (room pool) y fecha de llegada que coinciden exactamente con otro segmento dentro de la misma reserva (GNR).
MARSHA no permite duplicaciones de estos elementos dentro de una misma solicitud.

Causas Posibles
1. Duplicación de fecha de llegada y grupo de habitaciones en diferentes segmentos dentro de la misma reserva.
2. Error al intentar agregar múltiples segmentos con las mismas configuraciones de habitación y fecha de llegada.
3. Problemas de configuración o sincronización entre OPERA y MARSHA que causan duplicaciones de datos.

   Solución
1. Revisar la reserva en OPERA:

* Verifica que no haya duplicación de segmentos con la misma fecha de llegada y grupo de habitaciones en el mismo GNR.
* Si se detecta duplicación, divide la reserva en dos o más GNRs con configuraciones de alojamiento distintas.

2. Separar la solicitud en diferentes GNRs:

* Si la reserva contiene varios segmentos con los mismos parámetros, crea una nueva solicitud de reserva con la misma configuración para el nuevo GNR.

3. Revisar la configuración de las habitaciones y fechas:

* Asegúrate de que no haya coincidencias en los grupos de habitaciones y fechas de llegada que puedan generar este error.

4. Contactar con el soporte de MARSHA si el error persiste:

* Si no puedes corregir el error separando los GNRs o configurando correctamente los parámetros, contacta al helpdesk de MARSHA para obtener asistencia.
