Descripción del Problema
Este error ocurre cuando la solicitud recibida desde el PMS intenta actualizar una GNR (Guest Name Record) que ha sido modificada simultáneamente por otro proceso,
como puede ser una actualización automática de MARSHA o una intervención manual de un agente de MARSHA, mientras la solicitud desde el PMS estaba procesándose.


Causas Posibles
1. Conflicto de sincronización entre las actualizaciones del PMS y otros procesos de MARSHA.
2. El GNR fue modificado manualmente o por un proceso en MARSHA mientras la solicitud del PMS estaba en cola.
3. Retraso en la actualización de datos entre el PMS y MARSHA, lo que genera un conflicto de edición.

   Solución
1. Verificar el estado de la GNR en MARSHA:

* Comprueba si la GNR ha sido modificada manualmente o por otro proceso mientras la solicitud del PMS estaba en curso.

2. Revisar los logs de OXI y MARSHA:

* Revisa los logs para identificar qué proceso modificó la GNR y en qué momento se produjo el conflicto.

3. Reintentar la solicitud después de un breve intervalo:

* Si el error se debió a una coincidencia temporal de las actualizaciones, espera un momento y vuelve a intentar la solicitud desde el PMS.

4. Implementar un manejo adecuado de bloqueos en el sistema:

*Si el problema persiste, podría ser útil configurar un mecanismo de control de concurrencia para manejar las actualizaciones simultáneas de la GNR de manera más eficaz.

5. Contactar con soporte si el problema persiste:

* Si después de realizar los pasos anteriores el error sigue ocurriendo, contacta con el soporte técnico de OPERA o MARSHA para investigar más a fondo y resolver el conflicto.
