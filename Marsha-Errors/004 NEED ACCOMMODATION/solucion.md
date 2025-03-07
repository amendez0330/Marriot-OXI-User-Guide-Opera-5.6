Descripción del Problema
Este error ocurre cuando la solicitud de alojamiento no fue recibida correctamente desde el PMS (Property Management System) a MARSHA. MARSHA requiere una solicitud de alojamiento para procesar la reserva correctamente.

Causas Posibles
* La reserva en OPERA no incluye una solicitud de alojamiento.
* El campo de solicitud de alojamiento está vacío o no se ha configurado correctamente.
* Problemas en la integración entre OPERA y MARSHA que impiden la transmisión de la solicitud de alojamiento.
* Error en la configuración de la interfaz OXI entre OPERA y MARSHA.

Solución
1.Verificar la reserva en OPERA:

* Asegúrate de que la solicitud de alojamiento esté correctamente configurada en la reserva.

2. Actualizar la reserva y reenviar el mensaje:

* Si la solicitud de alojamiento está vacía o no se ha configurado, agrégala y vuelve a enviar la reserva a MARSHA.

3. Revisar los logs de OXI para verificar si la solicitud fue enviada:

* Si la solicitud estaba presente pero el error persiste, revisa los logs de OXI para confirmar que la información se transmitió correctamente.

4. Verificar la configuración de la interfaz OPERA-MARSHA:

* Asegúrate de que la solicitud de alojamiento esté correctamente mapeada en la integración entre OPERA y MARSHA.

5. Contactar con soporte si el problema persiste:

* Si después de realizar los pasos anteriores el error sigue ocurriendo, consulta con el soporte técnico de OPERA o MARSHA para asistencia adicional.
