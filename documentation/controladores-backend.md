# Controladores Backend

Los controladores (o capas de control/servicios dentro de `backend/src`) gestionan la lógica asociada a cada operación solicitada por las rutas del servidor.

### Responsabilidades habituales

* Recibir y validar los datos provenientes de las peticiones del frontend.
* Coordinar las consultas o transacciones con la base de datos PostgreSQL.
* Manejar respuestas exitosas, códigos de estado HTTP y control de errores.
