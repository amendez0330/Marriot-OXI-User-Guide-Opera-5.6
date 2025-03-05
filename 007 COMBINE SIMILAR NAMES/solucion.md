Descripción del Problema
Este error ocurre cuando hay dos o más nombres exactamente iguales en el GNR (Guest Name Record). 
MARSHA no permite duplicados de nombres exactos en el GNR. Este error normalmente no debería ocurrir si el PMS maneja correctamente los registros de huéspedes.

Causas Posibles
1. Duplicación de nombres al ingresar los datos del huésped en OPERA.
2. Error al crear o modificar registros de huéspedes, lo que provoca la duplicación de nombres.
3. Problemas en la interfaz entre OPERA y MARSHA que pueden generar duplicados no esperados.
4. Falta de validación adecuada en el PMS para prevenir duplicados de nombres.

Solución
1.Verificar el GNR en OPERA:

*Asegúrate de que no haya duplicados de nombres exactos dentro del registro de huésped. Si es necesario, elimina o corrige los duplicados.

2. Actualizar la reserva y reenviar la solicitud:

* Si se identifican duplicados, actualiza la reserva eliminando los registros de huéspedes duplicados y vuelve a enviar la solicitud a MARSHA.

3. Revisar los logs de OXI para verificar si los duplicados fueron causados por la integración:

* Si el error persiste, revisa los logs de OXI para investigar si el problema se debe a un error en la interfaz entre OPERA y MARSHA.

4. Verificar la validación de nombres en OPERA:

* Asegúrate de que OPERA esté configurado para validar los registros de huéspedes y evitar duplicaciones de nombres exactos.

5. Contactar con soporte si el problema persiste:

* Si después de realizar los pasos anteriores el error sigue ocurriendo, contacta con el soporte técnico de OPERA o MARSHA para investigar y resolver el problema.
