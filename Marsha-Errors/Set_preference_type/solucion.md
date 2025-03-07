Set_preference_type: Can’t identify the preference type of [OTHR, OTHR]. Ignoring those preferences.
Esto es causado por un problema en MARSHA relacionado con los campos SOTHR que no se convierten correctamente en I-Fields. Cuando el comando SOTHR se ingresa antes del sell segment en el GNR (Guest Reservation),
el campo SOTHR no se convierte en un I-Field y permanece como un SOTHR en el GNR dentro de MARSHA. Los campos SOTHR no son manejados adecuadamente en la interfaz con OPERA.

Este mensaje suele aparecer especialmente en reservas de agentes de viajes, ya que estos tienden a solicitar preferencias como el fumar antes de realizar la solicitud de alojamiento.

Solución
1. Asegurarse de que el campo SOTHR se ingrese después del sell segment:

Verifica que el campo SOTHR se ingrese en el GNR únicamente después de que el sell segment haya sido procesado. Esto garantizará que el campo SOTHR se convierta correctamente en un I-Field.

2. Revisar la configuración de MARSHA y OPERA:

Asegúrate de que la configuración en MARSHA y OPERA sea la adecuada para manejar las preferencias correctamente, especialmente las preferencias de SOTHR. De ser necesario,
contacta con el soporte de MARSHA para una posible actualización o ajuste en la forma en que se manejan estos campos.

3. Realizar pruebas:

Después de hacer los ajustes, realiza pruebas con reservas de agentes de viajes que involucren preferencias para verificar que el campo SOTHR se esté convirtiendo correctamente en I-Field.

4. Documentar el flujo de trabajo de preferencias:

Es útil documentar el flujo de trabajo para la gestión de preferencias en tu equipo, especialmente cuando se trata de reservas realizadas por agentes de viajes, para evitar este tipo de problemas en el futuro.
