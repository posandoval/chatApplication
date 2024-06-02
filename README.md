#Spring Boot WebSocket Chat Application

Descripción:

Este proyecto implementa una aplicación de chat utilizando el framework Spring Boot. Permite a los usuarios identificarse a traves de un UserName, ingresar a un chatroom, enviar y recibir mensajes entre los usuarios conectados.

Version:
Java: 21
SpringBoot v3.3.0

Tecnologías:
SpringWeb
Spring Boot devTools
WebSocket
lombok

Ejecución:
Clonear el repositorio del proyecto: Git clone urlRepository
Instalar las dependencias necesarias (Maven).
Ejecutar la aplicación desde la línea de comandos: mvn spring-boot:run.
Acceder a la aplicación en la URL: http://localhost:8080.

Funcionalidades:
Ingreso de nombre de usuario: Los usuarios pueden ingresar UserName de identificación.
Inicio de sesión: Los usuarios registrados pueden iniciar sesión utilizando su nombre de usuario y contraseña.
Envío de mensajes: Los usuarios conectados pueden enviar mensajes a otros usuarios en tiempo real.
Recepción de mensajes: Los usuarios reciben notificaciones cuando otros usuarios les envían mensajes.
Lista de usuarios conectados: Los usuarios pueden ver una lista de usuarios que se encuentran actualmente conectados a la aplicación.

Próximos pasos:
Implementar un sistema de autenticación robusto (OAuth2).
Agregar funcionalidades para chats One to One.
Mejorar la interfaz de usuario de la aplicación.
