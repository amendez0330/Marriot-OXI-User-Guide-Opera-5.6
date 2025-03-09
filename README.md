# MARRIOTT OXI USER GUIDE  
**OPERA v5.6**

[![Marriott-Bonvoy-1.png](https://i.postimg.cc/XNfTMmRF/Marriott-Bonvoy-1.png)](https://postimg.cc/7bLB0sYY)

---

## Tabla de Contenido

1. [Introducción](#introducción)
2. [Configuración de Reintento de Entrega](#configuración-de-reintento-de-entrega)
3. [Proceso de Auto Purge](#proceso-de-auto-purge)
4. [Parámetros Globales](#parámetros-globales)
   - Propiedades OPO
   - Propiedades APO
5. [Configuraciones de MARSHA](#configuraciones-de-marsha)
   - Configuración de la Interfaz MARSHA [documentación específica](Marsha%20Configuration/Marsha%20Configuration.md).
   - Transmisión Automática de MARSHA
   - Descarga de Tarifas
   - WS Alive
   - Versiones XML de MARSHA
   - Códigos de Conversión de MARSHA
   - Métodos de Comunicación de MARSHA
   - Validación AR
   - Disponibilidad
   - Bloques
   - Sistema Externo a OPERA
   - Preferencias Garantizables
   - Control de Inventario
   - OPERA a Sistema Externo
   - Configuración de Preferencias
   - Búsqueda de Perfiles
   - Tarifas
   - Reservaciones
   - Habitaciones
   - Valores Predeterminados de la Interfaz MARSHA
   - Parámetros de la Interfaz MARSHA
   - Coincidencia de Perfiles en MARSHA
   - Eventos de Negocio de MARSHA
6. [Configuraciones de SGI](#configuraciones-de-sgi)
   - Configuración de la Interfaz SGI
   - Transmisión Automática de SGI
   - Solicitud de Perfil
   - Versión XML de SGI
   - Códigos de Conversión de SGI
   - Métodos de Comunicación de SGI
   - Valores Predeterminados de la Interfaz SGI
   - Parámetros de la Interfaz SGI
   - Eventos de Negocio de SGI
7. [Configuraciones de MIMPG](#configuraciones-de-mimpg)
   - Transmisión Automática de MIMPG
   - Configuración de la Interfaz MIMPG
   - Versión XML de MIMPG
   - Códigos de Conversión de MIMPG
   - Métodos de Comunicación de MIMPG
   - Valores Predeterminados de la Interfaz MIMPG
   - Parámetros de la Interfaz MIMPG
   - Eventos de Negocio de MIMPG
8. [Configuraciones de MISFA](#configuraciones-de-misfa)
   - Transmisión Automática de MISFA
   - Configuración de la Interfaz MISFA
   - Versión XML de MISFA
   - Códigos de Conversión de MISFA
   - Métodos de Comunicación de MISFA
   - Valores Predeterminados de la Interfaz MISFA
   - Parámetros de la Interfaz MISFA
   - Coincidencia de Perfiles en MISFA
   - Eventos de Negocio de MISFA
9. [Configuración Relacionada de OPERA PMS](#configuración-relacionada-de-opera-pms)
   - Códigos de Hotel
   - Códigos de Mercado
   - Tarjetas de Crédito
   - Características de Habitaciones
   - Especiales
   - Códigos de Moneda
   - Configuración de Usuario OXI
10. [Apéndices](#apéndices)
    - Apéndice A: Mensajes de Error de MARSHA
    - Apéndice B: Mensajes de Error de SGI
    - Apéndice C: Verificación de Conectividad con Marriott Bonvoy
    - Apéndice D: Flujo de Estado de MARSHA/OXI
    - Apéndice E: Verificación de Conectividad con MIMPG
    - Apéndice F: Parámetros Ocultos de OXI
11. [Registro de Cambios del Documento](#registro-de-cambios-del-documento)

---

## Introducción
Este documento es una guía de usuario para la configuración y uso de Marriott OXI en OPERA v5.6. Está diseñado para ayudar a los administradores y técnicos a comprender y configurar las interfaces de OXI, incluyendo MARSHA, SGI, MIMPG y MISFA. A continuación, se detallan los pasos necesarios para configurar cada componente, así como los parámetros globales y las mejores prácticas para garantizar un funcionamiento óptimo.

Cómo utilizar esta guía:

Navega por la Tabla de Contenido para encontrar la sección relevante.

Sigue las instrucciones paso a paso para configurar cada interfaz.

Consulta los Apéndices para obtener información adicional sobre mensajes de error, verificaciones de conectividad y parámetros ocultos.

## Configuración de Reintento de Entrega
Esta sección explica cómo configurar el mecanismo de reintento de entrega para garantizar que los mensajes enviados a través de las interfaces OXI se entreguen correctamente, incluso en caso de fallos temporales.

Pasos:

Accede a la configuración de reintento en el sistema.

Define el número máximo de reintentos.

Establece el intervalo de tiempo entre reintentos.

Configura las notificaciones en caso de fallo persistente. 
Para más detalles sobre cómo configurar el reintento de entrega, consulta la [documentación específica](Delivery%20Retry%20Settings/Delivery%20Retry%20Settings.md). 
## Proceso de Auto Purge
El proceso de Auto Purge elimina automáticamente los datos antiguos o innecesarios de las bases de datos para optimizar el rendimiento del sistema. Esta sección describe cómo habilitar y configurar este proceso.

Importancia:

Libera espacio en la base de datos.

Mejora el rendimiento del sistema.

Reduce el riesgo de corrupción de datos.

Configuración:

Define el período de retención de datos.

Programa la ejecución del Auto Purge en horarios de bajo uso.

Monitorea los logs para asegurarte de que el proceso se ejecute correctamente.
Para más detalles sobre como configurar el Proceso Auto Purge [documentación especifica](Auto%20Purge%20Process/Auto%20Purge%20Process.md).

## Parámetros Globales
Los parámetros globales son configuraciones que afectan a todas las interfaces de OXI. Esta sección cubre las propiedades OPO (Opera Property) y APO (Application Property).

Propiedades OPO:

Configuraciones específicas para cada propiedad.

Parámetros relacionados con la conectividad y la autenticación.

Propiedades APO:

Configuraciones generales de la aplicación.

Parámetros que afectan a múltiples propiedades.
Para más detalles sobre como configurar Parametros Globales [documentación específica](Global%20Parameters/Global%20Parameters.md).
## Configuraciones de MARSHA
MARSHA es una de las interfaces principales de OXI. Esta sección proporciona una guía completa para su configuración, incluyendo:

Configuración de la Interfaz: Detalles sobre cómo conectar MARSHA con OPERA.

Transmisión Automática: Configuración de la programación de transmisiones automáticas.

Códigos de Conversión: Lista de códigos utilizados para la conversión de datos.

Métodos de Comunicación: Descripción de los métodos de comunicación disponibles.
## Configuraciones de SGI
La interfaz SGI (Starwood Guest Information) se utiliza para gestionar la información de los huéspedes. Esta sección incluye:

Configuración de la Interfaz: Pasos para configurar la conexión entre SGI y OPERA.

Transmisión Automática: Programación de transmisiones automáticas.

Códigos de Conversión: Lista de códigos utilizados en SGI.

## Configuraciones de MIMPG
MIMPG es una interfaz utilizada para la gestión de perfiles. Esta sección cubre:

Configuración de la Interfaz: Instrucciones para configurar MIMPG.

Transmisión Automática: Configuración de transmisiones automáticas.

Códigos de Conversión: Lista de códigos utilizados en MIMPG.



## Configuraciones de MISFA
MISFA es una interfaz utilizada para la gestión de reservas y tarifas. Esta sección incluye:

Configuración de la Interfaz: Pasos para configurar MISFA.

Transmisión Automática: Programación de transmisiones automáticas.

Códigos de Conversión: Lista de códigos utilizados en MISFA.

## Configuración Relacionada de OPERA PMS
Esta sección cubre configuraciones adicionales en OPERA PMS que son relevantes para OXI, como:

Códigos de Hotel: Configuración de códigos únicos para cada propiedad.

Códigos de Mercado: Definición de mercados y segmentos.

Tarjetas de Crédito: Configuración de métodos de pago aceptados.

Características de Habitaciones: Definición de tipos de habitaciones y sus características.

Códigos de Moneda: Configuración de monedas aceptadas.



## Apéndices
Los apéndices proporcionan información adicional para la resolución de problemas y la verificación de configuraciones:

Apéndice A: Mensajes de error comunes en MARSHA y cómo solucionarlos.

Apéndice B: Mensajes de error comunes en SGI y cómo solucionarlos.

Apéndice C: Verificación de conectividad con Marriott Bonvoy.

Apéndice D: Flujo de estado de MARSHA/OXI.

Apéndice E: Verificación de conectividad con MIMPG.

Apéndice F: Parámetros ocultos de OXI.
## Registro de Cambios del Documento
Historial de cambios realizados en el documento.
