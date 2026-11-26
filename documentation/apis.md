# APIs

El backend expone endpoints HTTP/REST para comunicar la interfaz frontend con los servicios y datos de NexusDesk `[completar según endpoints reales del proyecto]`.

### Aspectos generales

* Formato de intercambio: JSON para el envío y recepción de datos entre cliente y servidor.
* Configuración de entorno: El servidor requiere variables de entorno (como `DATABASE_URL` y claves o configuraciones definidas en `src/config/env.js`) para iniciar y conectarse a los servicios correspondientes.
