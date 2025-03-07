Descripción del Problema
Este error ocurre cuando la reserva enviada desde el PMS (Property Management System) a MARSHA no incluye la dirección del huésped, o si la dirección ya existente en MARSHA ha sido eliminada. 
MARSHA requiere que cada reserva tenga una dirección asociada para poder procesarla correctamente.


Causas Posibles
* La reserva en OPERA no tiene una dirección de huésped asignada.
* El campo de la dirección está vacío o se eliminó accidentalmente en la reserva.
* Problemas en la integración entre OPERA y MARSHA que impiden la transmisión de la dirección.
* Error en la configuración de la interfaz OXI entre OPERA y MARSHA.

  Solución
1.Verificar la reserva en OPERA:

* Asegúrate de que la dirección del huésped esté correctamente ingresada en la reserva.

2. Actualizar la reserva y reenviar el mensaje:

* Si la dirección está vacía o ha sido eliminada, agrégala nuevamente y vuelve a enviar la reserva a MARSHA.

3. Revisar los logs de OXI para verificar si la dirección fue enviada:

* Si la dirección estaba presente pero el error persiste, revisa los logs de OXI para confirmar que la información se transmitió correctamente.

4. Verificar la configuración de la interfaz OPERA-MARSHA:

* Asegúrate de que el campo de dirección esté correctamente mapeado en la integración entre OPERA y MARSHA.

5. Contactar con soporte si el problema persiste:

 * Si después de realizar los pasos anteriores el error sigue ocurriendo, consulta con el soporte técnico de OPERA o MARSHA para asistencia adicional.
