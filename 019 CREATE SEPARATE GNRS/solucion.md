Descripción del Problema
Este error ocurre cuando el itinerario reservado no puede permanecer en un solo GNR (Guest Name Record). Se requiere dividir el itinerario en varios GNRs para procesarlo correctamente.

Causas Posibles
1. El itinerario tiene múltiples alojamientos o segmentos que no pueden ser manejados juntos en un solo GNR.
2. Se ha intentado registrar una reserva que abarca diferentes fechas, tipos de habitación o tarifas, lo cual no es compatible con un único GNR.
3. Limitaciones en la configuración de MARSHA o en la forma en que los segmentos fueron transmitidos desde OPERA.

   Solución
1. Dividir el itinerario en múltiples GNRs:

* Si el itinerario incluye múltiples segmentos o fechas que no pueden ser procesados en un solo GNR, divídelos en varias solicitudes de GNR, cada una correspondiente a un segmento distinto de la reserva.

2. Revisar la configuración de los segmentos y fechas:

* Asegúrate de que los segmentos, habitaciones y tarifas sean correctos y adecuados para ser procesados en GNRs separados, según las reglas del sistema.

3. Reenviar la solicitud después de separar los GNRs:

* Una vez que hayas dividido el itinerario en GNRs separados, vuelve a enviar las solicitudes a MARSHA para completar el procesamiento de las reservas.

4. Contactar con el soporte de MARSHA si el error persiste:

* Si después de realizar los pasos anteriores el error sigue ocurriendo, contacta con el soporte técnico de MARSHA para investigar más a fondo el problema.
