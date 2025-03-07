Descripción del Problema
Este error ocurre cuando la reserva enviada desde el PMS (Property Management System) a MARSHA no incluye un nombre de huésped. MARSHA requiere que cada reserva tenga al menos un nombre asociado para poder procesarla correctamente.

Causas Posibles
* La reserva en OPERA no tiene un nombre asignado.
* El campo de nombre del huésped está vacío o no se envió en el mensaje de integración.
* Problemas en la interfaz entre OPERA y MARSHA que impiden la transmisión del nombre del huésped.
* Error en la configuración de la integración OXI entre OPERA y MARSHA.

  Solución
1. Verificar la reserva en OPERA:

* Asegúrate de que el campo del nombre del huésped está correctamente completado en la reserva.

2. Actualizar la reserva y reenviar el mensaje:

* Si el nombre del huésped estaba vacío, agrégalo y vuelve a enviar la reserva a MARSHA.

3. Revisar los logs de OXI para verificar si el nombre fue enviado:

* Si la reserva tenía un nombre pero aún así el error aparece, revisa los logs de OXI para confirmar que la información se transmitió correctamente.

4. Verificar la configuración de la interfaz OPERA-MARSHA:

* Asegúrate de que el campo del nombre del huésped esté correctamente mapeado en la integración entre OPERA y MARSHA.

5. Contactar con soporte si el problema persiste:

* Si después de realizar los pasos anteriores el error sigue ocurriendo, consulta con el soporte técnico de OPERA o MARSHA para asistencia adicional.
