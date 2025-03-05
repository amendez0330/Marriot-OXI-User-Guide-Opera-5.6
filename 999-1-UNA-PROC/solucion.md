Descripción del Problema
Este error ocurre cuando MARSHA no puede encontrar la reserva o la información de la reserva en OPERA no coincide con la información almacenada en MARSHA, lo que impide realizar cambios en la reserva.

Un ejemplo de este problema es cuando un intento previo de cambio de tarifa en MARSHA falló, dejando la tarifa en un estado desactualizado. 
Si se envía otro cambio basado en la tarifa incorrecta, MARSHA no puede procesarlo y responde con el error UNA PROC – Unable to Process Request.

Causas Posibles
1. La reserva no existe en MARSHA o fue eliminada.
2. Diferencias en los datos de la reserva entre OPERA y MARSHA.
3. Un cambio previo en la reserva falló y dejó información desactualizada en MARSHA.
4. No hay un número de confirmación activo en MARSHA asociado con la reserva.
5. Problemas de sincronización entre OPERA y MARSHA.


Solución
1.Verificar el número de confirmación en MARSHA:

* Asegúrate de que la reserva tiene un número de confirmación activo en MARSHA.

2. Revisar la información de la reserva en OPERA y MARSHA:

* Compara los detalles de la reserva en ambos sistemas para detectar discrepancias en tarifas, fechas o nombres.

3. Corregir cualquier cambio fallido en MARSHA:

* Si un intento previo de cambio de tarifa falló, intenta corregir manualmente la tarifa en MARSHA antes de enviar nuevos cambios.

4. Intentar reenviar la reserva con la información correcta:

* Si la reserva aún existe en MARSHA pero tiene datos desactualizados, intenta reenviar la información con los valores correctos.

5. Verificar la sincronización entre OPERA y MARSHA:

* Si el problema persiste, revisa si hay retrasos en la actualización de reservas entre ambos sistemas.

6. Contactar con soporte técnico si el problema continúa:

* Si después de realizar los pasos anteriores el error sigue ocurriendo, contacta con el equipo de soporte de OPERA o MARSHA para asistencia.
