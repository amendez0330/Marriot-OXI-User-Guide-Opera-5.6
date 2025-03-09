Descripcion del Error.
Este error ocurre cuando MARSHA detecta que el archivo del cliente no es válido para el tipo de producto que se está intentando procesar.


Causas Posibles
1. El perfil del cliente en OPERA tiene información incompleta o incorrecta.
2. El producto asociado a la reserva no es compatible con el tipo de perfil del cliente.
3. Problema en la conversión de datos entre OPERA y MARSHA a través de OXI.
4. Configuración incorrecta en MARSHA que impide la validación del perfil del cliente.

   Solución
1. Verificar la información del cliente en OPERA:

* Accede al perfil del cliente y asegúrate de que todos los campos requeridos estén correctamente llenos.
* Confirma que el cliente esté asignado al tipo de producto adecuado.

2. Revisar la configuración del producto en la reserva:

* Asegúrate de que el producto vinculado a la reserva sea compatible con el perfil del cliente.

3. Consultar la conversión de datos en OXI:

* Revisa las configuraciones en la tabla de conversión de OXI para garantizar que los datos del cliente se están transmitiendo correctamente a MARSHA.

4. Reenviar la solicitud a MARSHA:

* Una vez corregida la información, intenta enviar la reserva nuevamente para verificar si se procesa correctamente.

5. Contactar con el soporte de MARSHA si el error persiste:

* Si el problema continúa, comunícate con el helpdesk de MARSHA para confirmar si hay configuraciones adicionales que deban ajustarse.
