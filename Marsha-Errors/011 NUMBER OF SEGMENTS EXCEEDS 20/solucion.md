Descripción del Problema
Este error ocurre cuando se recibe una solicitud de alojamiento adicional para un GNR (Guest Name Record) que ya contiene el máximo número de segmentos permitidos (20). 
MARSHA no puede procesar más segmentos en un solo GNR, por lo que se requiere realizar ajustes en la reserva.

Causas Posibles
1. El GNR contiene más de 20 segmentos de alojamiento.
2. Se intentó agregar un nuevo segmento de alojamiento sin combinar o cancelar segmentos previos.
3. El GNR ha alcanzado su límite de segmentos debido a reservas múltiples o cambios de alojamiento.

Solución
1. Verificar el número de segmentos en el GNR en OPERA:

* Revisa el GNR y verifica cuántos segmentos de alojamiento contiene. Si ya hay 20 segmentos, se deben realizar ajustes.

2. Combinar o cancelar segmentos en OPERA:

* Si hay segmentos redundantes o innecesarios, combínalos o cancélalos para liberar espacio para el nuevo alojamiento.

3. Crear un nuevo GNR si es necesario:

* Si no es posible ajustar los segmentos existentes, considera crear un nuevo GNR para procesar la nueva solicitud de alojamiento.

4. Reenviar la solicitud después de los ajustes:

* Una vez que los segmentos hayan sido combinados o cancelados, o se haya creado un nuevo GNR, vuelve a enviar la solicitud de alojamiento a MARSHA.

5. Contactar con soporte si el problema persiste:

* Si después de realizar los pasos anteriores el error sigue ocurriendo, contacta con el soporte técnico de OPERA o MARSHA para asistencia adicional.
