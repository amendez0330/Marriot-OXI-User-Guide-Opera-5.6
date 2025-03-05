Descripción del Problema
Este error ocurre cuando MARSHA no reconoce el tipo de tarjeta de crédito utilizada en una reserva o transacción. Generalmente, esto se debe a una configuración incorrecta en la conversión de métodos de pago entre sistemas.

Causas Posibles
Código de conversión de método de pago incorrecto o faltante:

*La tarjeta de crédito utilizada en la reserva no tiene una conversión correcta entre OPERA y MARSHA.

Configuración incorrecta en OPERA o MARSHA:

*La tarjeta de crédito puede no estar correctamente configurada en la base de datos local del PMS.

Tarjeta no admitida en la propiedad o sistema:

*Puede que la tarjeta utilizada no sea aceptada por la propiedad o no esté habilitada en MARSHA.

Errores en la interfaz de comunicación entre OPERA y MARSHA:

*Puede haber un problema en la integración que impide la conversión del método de pago.


Solución

1. Verificar la configuración de conversión de métodos de pago en OPERA y MARSHA:

*Asegúrate de que el código de conversión para la tarjeta de crédito está correctamente configurado en OXI Conversion Codes.

2.Confirmar que la tarjeta de crédito es válida y admitida:

* Revisa si la tarjeta utilizada en la reserva es compatible con los métodos de pago aceptados por la propiedad y MARSHA.

3. Revisar la configuración local de tarjetas de crédito en OPERA:

* Accede a la configuración del PMS y valida que la tarjeta de crédito esté correctamente mapeada.

4. Reintentar la reserva con una tarjeta diferente:

* Si el problema persiste, intenta procesar la reserva con otra tarjeta de crédito válida.

5. Contactar con el soporte de OPERA o MARSHA:

* Si ninguna de las soluciones anteriores resuelve el problema, contacta con el equipo de soporte para revisar la configuración y sincronización del sistema.

