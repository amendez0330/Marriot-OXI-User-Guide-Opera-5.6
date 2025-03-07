Descripción del Problema
Este error ocurre cuando las fechas en la sección de alojamiento del GNR (Guest Name Record) están fuera de secuencia, lo que significa que hay un problema en el orden de las fechas de llegada y salida. 
Este error generalmente indica un problema en el procesamiento de la aplicación MARSHA.

Causas Posibles
1. Fechas incorrectas ingresadas en el GNR en OPERA o MARSHA.
2. Problemas de sincronización entre OPERA y MARSHA que afectan el orden de las fechas.
3. Errores en la interfaz de comunicación entre OPERA y MARSHA que modifican o alteran las fechas del GNR.
4. Problemas en el sistema MARSHA al procesar la reserva, lo que provoca un error en el orden de las fechas.

   Solución
1.Verificar las fechas en OPERA:

* Asegúrate de que las fechas de llegada y salida estén correctamente ingresadas y que no haya errores en la secuencia de las fechas.

2.Revisar la reserva en MARSHA:

* Si el error persiste después de verificar las fechas en OPERA, revisa el GNR en MARSHA para confirmar si el problema está ocurriendo debido a un error en el sistema de MARSHA.

3.Reenviar la reserva a MARSHA:

*Después de corregir las fechas, vuelve a enviar la reserva a MARSHA para asegurarte de que el GNR se procese correctamente.

4.Contactar con el soporte de MARSHA:

*Si después de realizar los pasos anteriores el error sigue ocurriendo, contacta al soporte técnico de MARSHA para que investiguen más a fondo el problema, ya que puede haber un error en su aplicación que está afectando el procesamiento de las fechas.
