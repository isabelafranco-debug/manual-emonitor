# Requisitos del Sistema

Antes de iniciar la instalación y configuración de Emonitor, verifique que se disponga de los siguientes componentes de hardware, software e infraestructura de red.

## Hardware

### Controlador Industrial

* PLC Allen-Bradley compatible con la arquitectura de monitoreo implementada.
* Firmware actualizado y correctamente configurado.

### Módulo de Monitoreo de Vibraciones

* Módulo Allen-Bradley Dynamix 1444 o equivalente compatible.
* Sensores de vibración correctamente instalados y cableados.

### Estación de Trabajo o Servidor

* Computador industrial o servidor destinado a la ejecución de Emonitor.
* Procesador Intel Core i7 o superior.
* 8 GB de memoria RAM como mínimo (16 GB recomendados).
* 5 GB de espacio libre en disco como mínimo.
* Unidad SSD recomendada para mejorar el rendimiento de la base de datos.

## Software

### Emonitor

* Emonitor 4.2 o versión compatible.

### Base de Datos

* Microsoft SQL Server 2017 o Microsoft SQL Server 2019.
* Ediciones Express, Standard o superiores.

### Herramientas de Configuración

* Studio 5000 Logix Designer para la configuración y mantenimiento del PLC.
* FactoryTalk Activation Manager para la activación de licencias.

## Red y Comunicaciones

### Infraestructura de Red

* Red Ethernet industrial operativa.
* Conectividad estable entre PLC, módulos de monitoreo y servidor Emonitor.

### Configuración de Red

* Direcciones IP configuradas correctamente para todos los dispositivos.
* Verificación de conectividad mediante pruebas de comunicación.
* Puertos requeridos habilitados en firewalls y equipos de red.

### Protocolos de Comunicación

* Ethernet/IP para la comunicación entre los dispositivos Allen-Bradley.
* Comunicación habilitada entre Emonitor y la base de datos SQL Server.
