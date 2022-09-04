# Proyecto Electivade ProfundizaciónI -Creaciónde APIs
Integrantes:
Edgardo Yesid Rojas Robles  @yesidro https://github.com/yesidro?tab=repositories
Luis Rodrigues     @LuixDev
Luis Castro    @Lukas-1996
Sprint  1:
Historia de Usuario
•Feature: Registro de Usuario
•Scenario: Registro de Usuario enla plataformacon correo nuevo (nunca antes registrado)
•Given: el usuario ha de hacer clic en el botón "Nuevo Usuario" e introduce de forma correcta nombre de usuario, nombre y apellido, correo electrónico ycontraseña.
•When: el usuario clica sobre el botón de "Registrar".
•Then: el usuario puede registrarse de forma correcta e iniciar sesión con el usuario y contraseña que ha definido.
•Subtareas (Definir  las tareas de BackEnd):
•Creación de Tabla de Usuarios con los campos nombre de usuario, nombre y apellido, correo electrónico ycontraseña. (Llave única el correo)
•Método
•URIsde EndPoint
•Bodyde las solicitud
•Respuesta
•Códigos HTTP de las respuestas
•Mensajes de Error
Historia Técnica
Creación de Base de DatosEn PostgreSQL,  crear base de datos para el almacenamiento persistente  de los datos de la aplicación.
Subtareas
•Instalación  de PostgreSQL
•Creación de la Base de Datos
•Configuración  de la conexión a la Base de Datos desde  el Framework
