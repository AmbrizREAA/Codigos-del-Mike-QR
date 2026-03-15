## obtener_datos_ubicacion
**Descripción:** Conecta con la API de Django REST Framework para obtener información geoespacial.
**Datos que recibe:** - `lat` (float): Latitud de la ubicación.
- `lon` (float): Longitud de la ubicación.
**Límites de seguridad:** Solo lectura. No realizar operaciones de escritura (POST/PUT/DELETE) en este endpoint.

## eliminar_registro_usuario
**Descripción:** Elimina un registro temporal en la base de datos de Django.
**Datos que recibe:**
- `id` (int): El identificador único del registro.
**Límites de seguridad:** CRÍTICO: "No eliminar sin confirmar". Siempre solicitar validación del usuario [S/N] antes de ejecutar la acción.