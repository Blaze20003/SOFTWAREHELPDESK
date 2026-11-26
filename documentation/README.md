# Arquitectura

## Arquitectura de NexusDesk

NexusDesk (`SOFTWAREHELPDESK`) es una aplicación web de mesa de ayuda estructurada en una arquitectura cliente-servidor con separación entre interfaz web y servicios de backend.



### Componentes principales

* Frontend (Interfaz web): Desarrollado con Vue 3 y Vite, encargado de las vistas de usuario, navegación y consumo de los servicios de la aplicación.
* Backend (Servidor / API): Desarrollado con Node.js, encargado de la lógica de negocio, validaciones, autenticación/autorización y comunicación con la base de datos.
* Base de datos: PostgreSQL, utilizada para el almacenamiento persistente de la información del sistema (por ejemplo, usuarios, tickets y registros relacionados.



### Flujo general

El usuario interactúa con la interfaz en el navegador; el frontend envía peticiones al servidor backend en Node.js, el cual procesa la solicitud, consulta o actualiza los datos en PostgreSQL y devuelve la respuesta a la interfaz.
