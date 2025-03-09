Descripción del Problema
Este error ocurre cuando MARSHA detecta una combinación inválida de múltiples habitaciones y nombres en una misma reserva (GNR).
Puede deberse a un problema en la estructura de la reserva o a una restricción dentro de la aplicación de MARSHA.

Causas Posibles
1. La reserva contiene múltiples habitaciones asignadas a la misma persona de manera incorrecta.
2. Nombres duplicados en la misma reserva que entran en conflicto con la configuración de MARSHA.
3. Error en la sincronización entre OPERA y MARSHA a través de OXI.
4. Restricción en MARSHA que impide la combinación de ciertos nombres y configuraciones de habitaciones en la misma reserva.

Solución
1. Verificar la estructura de la reserva en OPERA:

* Asegúrate de que cada habitación tenga un nombre asignado correctamente.
* Si hay nombres duplicados o combinaciones incorrectas, corrige la información y vuelve a enviar la solicitud.

2. Modificar la reserva y reenviar la solicitud:

* Si hay múltiples habitaciones asignadas al mismo nombre y esto no es válido en MARSHA, separa la reserva en múltiples GNRs.
* Elimina posibles duplicaciones de nombres en la reserva y vuelve a intentar.

3. Revisar la conversión en OXI (si aplica):

* Confirma que los datos se están enviando correctamente desde OPERA a MARSHA sin errores en la conversión.

4. Contactar con el soporte de MARSHA:

* Si después de corregir los datos el problema persiste, comunícate con el helpdesk de MARSHA para obtener asistencia.
