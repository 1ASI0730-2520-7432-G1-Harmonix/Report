# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping

- Segmento 1: Miembros del Hogar

<p styles="align: left">
  <img src="images/ScenarioMapping2S22.png" widht="1100">
</p>

- Segmento 2: Representante del Hogar

<p align="left">
  <img src="images/ScenarioMapping2S21.png" widht="1100">
</p>

## 3.2. User Stories
## Epic

| EPIC ID | Nombre del Epic                  | Descripción |
|---------|----------------------------------|-------------|
| EP00    | Arquitectura Técnica y Documentación     | Como desarrollador, quiero diseñar y documentar la arquitectura del sistema para garantizar escalabilidad, mantenimiento y comunicación clara entre miembros del equipo |
| EP01    | Registro y Gestión de Perfil     | Como usuario, quiero registrarme y gestionar mi perfil de forma segura y personalizada, para acceder a SplitEasy desde cualquier dispositivo. |
| EP02    | Panel del Representante del Hogar| Como representante del hogar, quiero gestionar y supervisar las finanzas del hogar de forma centralizada y transparente. |
| EP03    | Panel del Miembro del Hogar      | Como miembro del hogar, quiero registrar mis ingresos, ver mis responsabilidades y mantenerme al día con mis pagos. |
| EP04    | Gestión de Gastos Compartidos    | Como usuario, quiero registrar, clasificar y gestionar gastos para mantener el control financiero del hogar. |
| EP05    | Seguimiento y Recordatorios      | Como usuario, quiero recibir recordatorios y alertas automáticas para no olvidar mis responsabilidades financieras. |
| EP06    | Soporte y Comunidad              | Como usuario, quiero acceder a soporte técnico y a recursos para mejorar mi uso de la plataforma y resolver dudas. |
| EP07    | Exploración como Visitante       | Como visitante, quiero conocer la funcionalidad, beneficios y casos de uso de SplitEasy desde la landing page para evaluar si la plataforma es útil para mi hogar antes de registrarme. |

### EP01 - Registro y Gestión de Perfil

| User Story ID | Título                          |
|---------------|----------------------------------|
| US01          | Registro de usuario              |
| US02          | Inicio de sesión seguro          |
| US03          | Edición de información personal  |
| US04          | Cierre de sesión desde todos los dispositivos |
| US05          | Configuración de notificaciones personales |
| TS01          | Implementar autenticación JWT |
| TS02          | Cifrar contraseñas en base de datos |
| TS03          | Validar roles de administrador y miembro en backend |
| TS04          | Implementar actualización de perfil a partir de API |  
| TS05          | Conectar formularios de registro y login del front-end con endpoints   |
| TS06          | Validar respuestas del backend en la gestión de perfil del usuario      |

### EP02 - Panel del Representante del Hogar

| User Story ID | Título                          |
|---------------|----------------------------------|
| US06          | Crear hogar                      |
| US07          | Aprobar gastos                   |
| US08          | Ajustar porcentajes de aportes   |
| US09          | Visualizar reportes mensuales    |
| US10          | Configurar métodos de pago aceptados |
| US36          | Manejar errores del servidor en vistas del representante               |

### EP03 - Panel del Miembro del Hogar

| User Story ID | Título                          |
|---------------|----------------------------------|
| US11          | Ingresar ingresos personales     |
| US12          | Ver monto a pagar                |
| US13          | Registrar pagos realizados       |
| US14          | Ver historial de pagos           |
| US15          | Ver distribución de gastos del hogar |
| US37          | Implementar manejo de estados de carga y éxito en el panel del miembro |

### EP04 - Gestión de Gastos Compartidos

| User Story ID | Título                          |
|---------------|----------------------------------|
| US16          | Registrar nuevo gasto            |
| US17          | Adjuntar comprobantes de gasto   |
| US18          | Clasificar gastos por categoría  |
| US19          | Comentar o justificar un gasto   |
| US20          | Visualizar gráficos de gastos    |
| TS07          | Validar que el gasto tiene adjunto al menos 1 comprobante |
| TS08          | Agregar API para filtrar gastos por rango de fecha |
| TS09          | Implementar actualización y eliminación de gastos |  
| TS10          | Verificar integración entre back-end de gastos y sus componentes en front-end |

### EP05 - Seguimiento y Recordatorios

| User Story ID | Título                          |
|---------------|----------------------------------|
| US21          | Recordatorios de pago            |
| US22          | Alertas de pagos pendientes      |
| US23          | Recordatorio de actualización de ingresos |
| US24          | Confirmación de aportes          |
| US25          | Notificación de cambios en el hogar |
| TS11          | API para programar recordatorios de pago |
| TS12          | Integrar cron job para envío de recordatorios |  
| TS13          | Conectar notificaciones del sistema con el backend                     |

### EP06 - Soporte y Comunidad

| User Story ID | Título                          |
|---------------|----------------------------------|
| US26          | Acceso a ayuda en línea          |
| US27          | Chat con soporte técnico         |
| US28          | Reportar un problema             |
| US29          | Sugerencias de mejora            |
| US30          | Foro comunitario                 |
| TS14          | API para dar seguimiento a reportes de problemas |
| TS15          | Implementar comentarios o respuestas en el foro |
| TS16          | Validar seguridad de comunicación entre frontend y backend (CORS, HTTPS) |
| TS17          | Probar funcionamiento completo en entorno de producción                |

### EP07 - Exploración como Visitante

| User Story ID | Título                          |
|---------------|----------------------------------|
| US31          | Visualizar información general sobre SplitEasy desde la landing page              |
| US32          | Conocer las funciones principales para representantes y miembros del hogar         |
| US33          | Explorar beneficios del sistema de aportes proporcionales  |
| US34          | Ver ejemplos o simulaciones de cómo funciona la plataforma |
| US35          | 	Acceder fácilmente al registro o login desde botones destacados |
| TS18          | Documentar los pasos para desplegar nuevas versiones                   |
| TS19          | Habilitar monitoreo básico del sistema desplegado (logs, uptime)       |


| **ID Épica** | **Épica**                         | **ID HU** | **Título HU**                                       | **Descripción HU**                                                                                                                                                                     | **Criterios de Aceptación**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| ------------ | --------------------------------- | --------- | --------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| EP01         | Registro y Gestión de Perfil      | US01      | Registro de usuario                                 | Como usuario de ambos segmentos, quiero registrarme en la plataforma para comenzar a usar SplitEasy.                                                                                   | - **Escenario 1: Registro como miembro del hogar exitoso**<br> Dado que un usuario quiere registrarse como miembro del hogar,<br> Cuando proporciona todos los datos requeridos correctamente,<br> Entonces el sistema registra al usuario como miembro del hogar,<br> Y el usuario puede acceder a las funcionalidades correspondientes a ese rol.<br><br> - **Escenario 2: Registro como representante del hogar exitoso**<br> Dado que un usuario desea registrarse como representante del hogar,<br> Cuando proporciona todos los datos requeridos correctamente,<br> Entonces el sistema lo registra como representante del hogar,<br> Y el usuario puede acceder a las funcionalidades correspondientes a ese rol. |
| EP01         | Registro y Gestión de Perfil      | US02      | Inicio de sesión seguro                             | Como usuario registrado, quiero iniciar sesión de forma segura para acceder a mis datos personales.                                                                                    | - **Escenario 1: Inicio de sesión exitoso**<br> Dado que el usuario está registrado,<br> Cuando proporciona credenciales válidas,<br> Entonces el sistema le permite acceder a su cuenta.<br><br> - **Escenario 2: Inicio de sesión fallido por credenciales incorrectas**<br> Dado que el usuario intenta autenticarse,<br> Cuando las credenciales proporcionadas no son válidas,<br> Entonces el sistema rechaza el intento de acceso,<br> Y le indica que las credenciales no son válidas.                                                                                                                                                                                                                           |
| EP01         | Registro y Gestión de Perfil      | US03      | Edición de información personal                     | Como usuario de ambos segmentos, quiero editar mi información personal para mantenerla actualizada.                                                                                    | - **Escenario 1: Visualización de información personal**<br> Dado que el usuario ya está logueado,<br> Cuando accede a su información de perfil,<br> Entonces el sistema le muestra sus datos personales actuales en formato editable.<br><br> - **Escenario 2: Actualización de datos personales**<br> Dado que el usuario modifica su información personal,<br> Cuando envía los nuevos datos,<br> Entonces el sistema actualiza correctamente la información.                                                                                                                                                                                                                                                         |
| EP01         | Registro y Gestión de Perfil      | US04      | Cierre de sesión desde todos los dispositivos       | Como usuario de ambos segmentos, quiero cerrar sesión desde todos mis dispositivos para mayor seguridad.                                                                               | - **Escenario 1: Cierre de sesión en todos los dispositivos**<br> Dado que el usuario ha iniciado sesión en su cuenta,<br> Cuando solicita cerrar sesión en todos los dispositivos,<br> Entonces el sistema invalida todas las sesiones activas asociadas a su cuenta.                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| EP01         | Registro y Gestión de Perfil      | US05      | Configuración de notificaciones personales          | Como usuario de ambos segmentos, quiero configurar mis notificaciones para recibir alertas relevantes.                                                                                 | - **Escenario 1: Visualización de opciones de notificación**<br> Dado que el usuario accede a su configuración de perfil,<br> Cuando solicita ver las opciones de notificación,<br> Entonces el sistema muestra las opciones disponibles para activar o desactivar alertas.<br><br> - **Escenario 2: Aplicación de configuración de notificaciones**<br> Dado que el usuario selecciona sus preferencias de notificación,<br> Cuando envía la configuración,<br> Entonces el sistema guarda las preferencias y las aplica para futuras alertas.                                                                                                                                                                          |
| EP01         | Registro y Gestión de Perfil      | TS01      | Implementar autenticación JWT                       | Como desarrollador, quiero que el inicio de sesión implemente autenticación JWT para mayor seguridad en el manejo de sesiones.                                                         | - **Escenario 1: Generación del JWT**<br> Dado que el usuario proporciona credenciales correctas,<br> Cuando se autentica,<br> Entonces el backend genera y responde con un JWT válido.<br><br> - **Escenario 2: Validación del JWT**<br> Dado que el JWT se adjunta en el encabezado de la solicitud,<br> Cuando el backend verifica el token,<br> Entonces autoriza el acceso si el token es válido.                                                                                                                                                                                                                                                                                                                   |
| EP01         | Registro y Gestión de Perfil      | TS02      | Cifrar contraseñas en base de datos                 | Como desarrollador, quiero que las contraseñas de los usuarios sean encriptadas antes de guardarlas en la base de datos para garantizar la seguridad.                                  | - **Escenario 1: Almacenar contraseña cifrada**<br> Dado que la contraseña llega en texto plano,<br> Cuando el backend lo encripta,<br> Entonces se almacena en la base de datos de forma cifrada.<br><br> - **Escenario 2: Validar contraseña cifrada durante autenticación**<br> Dado que la contraseña en la base de datos está cifrada,<br> Cuando el backend verifica credenciales,<br> Entonces primero hace el hash de la contraseña ingresada y lo compara con el guardado.                                                                                                                                                                                                                                      |
| EP01         | Registro y Gestión de Perfil      | TS03      | Validar roles de administrador y miembro en backend | Como desarrollador, quiero que ciertos endpoints sean usados solo por determinados roles para asegurar que solo los usuarios autorizados puedan ejecutar determinadas acciones         | - **Escenario 1: Acceso permitido a endpoint por rol administrador**<br> Dado que el rol incluido en el JWT es administrador,<br> Cuando invoque un endpoint de administrador,<br> Entonces el backend permitirá el acceso.<br><br> - **Escenario 2: Acceso denegado a endpoint por rol no autorizado**<br> Dado que el rol incluido en el JWT es miembro,<br> Cuando invoque un endpoint de administrador,<br> Entonces el backend rechazará la solicitud con 403 (Forbidden).                                                                                                                                                                                                                                          |
| EP01         | Registro y Gestión de Perfil      | TS04      | Implementar actualización de perfil a partir de API | Como desarrollador, quiero implementar la actualización del perfil de usuario mediante una API para permitir que los usuarios modifiquen su información de manera segura y controlada. | - **Escenario 1: Actualización exitosa**<br> Dado que el token es válido,<br> Cuando el usuario envía nuevos datos,<br> Entonces el backend actualiza el perfil en la base de datos.<br><br> - **Escenario 2: Solicitud sin autenticación válida**<br> Dado que el token es vencido o inexistente,<br> Cuando el backend recibe la solicitud,<br> Entonces responde con 401 (Unauthorized).                                                                                                                                                                                                                                                                                                                              |
| EP01         | Registro y Gestión de Perfil      | TS05      | Conectar formularios con endpoints                  | Como desarrollador, quiero conectar los formularios de registro y login con los endpoints del backend para que funcionen correctamente.                                                | - **Escenario 1: Envío de datos de registro al backend**<br> Dado que el usuario completa el formulario de registro,<br> Cuando envía el formulario,<br> Entonces el formulario envía la información al endpoint correspondiente.<br><br> - **Escenario 2: Autenticación de usuario mediante el backend**<br> Dado que el usuario ingresa sus credenciales,<br> Cuando el frontend las envía al endpoint de autenticación,<br> Entonces el backend valida las credenciales.                                                                                                                                                                                                                                              |
| EP01         | Registro y Gestión de Perfil      | TS06      | Validar respuestas del backend                      | Como desarrollador, quiero validar las respuestas del backend para mostrar mensajes adecuados al usuario.                                                                              | - **Escenario 1: Error en el registro**<br> Dado que haya un error del backend al procesar el registro,<br> Cuando el usuario envíe un formulario,<br> Entonces se mostrará un mensaje de error específico.<br><br> - **Escenario 2: Fallo en el inicio de sesión**<br> Dado que el backend retorne un 401 Unauthorized,<br> Cuando se intente iniciar sesión,<br> Entonces el frontend indicará que las credenciales son inválidas.                                                                                                                                                                                                                                                                                     |
| EP02         | Panel del Representante del Hogar | US06      | Crear hogar                                         | Como representante del hogar, quiero crear un hogar en la app para empezar a gestionar sus finanzas.                                                                                   | - **Escenario 1: Acceso al proceso de creación de hogar**<br> Dado que el usuario ha iniciado sesión como representante del hogar,<br> Cuando accede a la opción de creación de hogar,<br> Entonces podrá ingresar un nombre e ID para el hogar.<br><br> - **Escenario 2: Creación exitosa del hogar**<br> Dado que el usuario completa los campos requeridos,<br> Cuando envía la solicitud de creación,<br> Entonces se crea el hogar y se muestra en su panel.                                                                                                                                                                                                                                                        |
| EP02         | Panel del Representante del Hogar | US07      | Aprobar gastos                                      | Como representante, quiero aprobar gastos para tener control sobre lo que se gasta en el hogar.                                                                                        | - **Escenario 1: Listado de gastos pendientes**<br> Dado que haya gastos sin aprobar,<br> Cuando el representante acceda al panel,<br> Entonces verá una lista de gastos para revisar.<br><br> - **Escenario 2: Aprobación de un gasto**<br> Dado que el representante selecciona un gasto,<br> Cuando confirme su aprobación,<br> Entonces el gasto pasará a estado "Aprobado".                                                                                                                                                                                                                                                                                                                                         |
| EP02         | Panel del Representante del Hogar | US08      | Ajustar porcentajes de aportes                      | Como representante, quiero modificar los porcentajes de contribución de cada miembro según sus ingresos.                                                                               | - **Escenario 1: Acceso a la configuración de aportes**<br> Dado que el representante está autenticado y accede al módulo de gestión del hogar,<br> Cuando accede a la sección de configuración de aportes,<br> Entonces verá una lista editable de miembros.<br><br> - **Escenario 2: Modificación y guardado de aportes**<br> Dado que el representante ha realizado ajustes en los porcentajes,<br> Cuando envía los nuevos valores,<br> Entonces se actualizarán los porcentajes automáticamente.                                                                                                                                                                                                                    |
| EP02         | Panel del Representante del Hogar | US09      | Visualizar reportes mensuales                       | Como representante, quiero ver reportes de ingresos y gastos mensuales para tomar decisiones informadas sobre la economía del hogar.                                                   | - **Escenario 1: Acceso a reportes mensuales**<br> Dado que el representante esté en su dashboard,<br> Cuando accede a la sección de reportes mensuales,<br> Entonces se mostrarán gráficos y resúmenes.<br><br> - **Escenario 2: Descarga de reporte**<br> Dado que el representante ha visualizado un reporte,<br> Cuando solicita su descarga,<br> Entonces el sistema genera un archivo PDF y se descargará el informe correspondiente.                                                                                                                                                                                                                                                                              |
| EP02         | Panel del Representante del Hogar | US10      | Configurar métodos de pago aceptados                | Como representante, quiero configurar qué métodos de pago están habilitados en el hogar.                                                                                               | - **Escenario 1: Ver métodos disponibles**<br> Dado que el usuario acceda a configuración,<br> Cuando seleccione "Métodos de pago",<br> Entonces verá una lista de métodos disponibles.<br><br> - **Escenario 2: Activar métodos**<br> Dado que seleccione métodos específicos,<br> Cuando presione “Guardar”,<br> Entonces esos métodos quedarán habilitados para el hogar.                                                                                                                                                                                                                                                                                                                                             |


## 3.3. Impact Mapping
## 3.4. Product Backlog
