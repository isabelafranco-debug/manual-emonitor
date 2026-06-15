# Instalación de Emonitor

## Paso 1: Preparación

- Verificar que el equipo cumpla con los requisitos de hardware y software.
- Instalar Microsoft SQL Server 2017 o 2019.
- Restaurar o crear la base de datos de Emonitor.
- Obtener el número de serie y la licencia del producto.
- Cerrar todas las aplicaciones en ejecución antes de iniciar la instalación.

### Instalación de FactoryTalk Activation Manager

1. Navegar a la carpeta `FTActivation` del medio de instalación.
2. Ejecutar `Setup.exe`.
3. Seleccionar **Install** y completar la instalación.

> FactoryTalk Activation Manager es necesario para activar las licencias de Emonitor.

### Instalación de RSLinx Classic

1. Navegar a la carpeta `RSLinx` del medio de instalación.
2. Ejecutar `Setup.exe`.
3. Seguir las instrucciones del asistente de instalación.

> RSLinx Classic es necesario para importar mediciones desde dispositivos como Dynamix 1444, XM y fuentes de datos OPC.

## Paso 2: Instalación de Emonitor

1. Ejecutar `Setup.exe` como administrador.
2. Verificar la instalación de Microsoft .NET Framework.
3. Aceptar el acuerdo de licencia.
4. Revisar los requisitos del sistema y seleccionar **Next**.
5. Seleccionar la carpeta de instalación.
6. Seleccionar la carpeta del menú Inicio.
7. Confirmar la configuración e iniciar la copia de archivos.

## Paso 3: Configuración de Base de Datos

### Base de Datos de Vibraciones

1. Introducir el usuario y contraseña de la base de datos de Emonitor.
2. Especificar el nombre o cadena de conexión del servidor SQL Server.
3. Seleccionar **Next**.

### Base de Datos de Configuración

1. Introducir el usuario y contraseña de la base de datos EConfig.
2. Seleccionar **Next**.

> Si los datos de conexión son incorrectos, Emonitor mostrará errores de conexión al iniciarse.

## Paso 4: Finalización

1. Completar el asistente de instalación.
2. Reiniciar el equipo.
3. Iniciar Emonitor desde el menú Inicio.

## Validación

- Abrir Emonitor correctamente.
- Verificar la conexión con SQL Server.
- Comprobar que las bases de datos se conectan sin errores.
- Confirmar la detección de dispositivos configurados.
- Verificar que la licencia se encuentre activa.
- Revisar que RSLinx pueda comunicarse con los dispositivos de campo.
