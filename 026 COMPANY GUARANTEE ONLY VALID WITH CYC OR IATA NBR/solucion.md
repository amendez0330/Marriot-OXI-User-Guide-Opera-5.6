Descripción del Problema
Este error indica que se ha intentado procesar una garantía de empresa, pero no se ha proporcionado un CYC (Corporate Code) o un IATA Number. 
La aplicación MARSHA no permite garantías de empresa sin uno de estos identificadores.

Causas Posibles
1. La reserva está garantizada por empresa, pero no tiene un CYC o IATA asociado.
2. Problema en la configuración del perfil de empresa en OPERA, lo que impide que se envíe el código correcto a MARSHA.
3. Error en la comunicación entre OPERA y MARSHA, donde los datos de la empresa no se están transmitiendo correctamente.

Solución
1. Verificar que la reserva tenga un CYC o IATA válido:

* Accede a OPERA y revisa el perfil de la empresa en la reserva. Asegúrate de que tenga un código corporativo (CYC) o un número IATA válido asociado.

2. Actualizar la información en la reserva:

* Si el código corporativo o IATA no está presente, agrégalo manualmente en el perfil de la empresa y asócialo a la reserva.

3. Reenviar la solicitud a MARSHA:

* Después de actualizar la información, vuelve a enviar la solicitud a MARSHA para que el procesamiento de la garantía se realice correctamente.

4. Contactar con el soporte de MARSHA si el error persiste:

* Si el problema continúa a pesar de corregir los datos en OPERA, contacta con el helpdesk de MARSHA para obtener asistencia adicional.
