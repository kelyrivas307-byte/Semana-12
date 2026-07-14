Modelo básico de datos:

Entidad: Causa

- id: Identificador único de la causa.
- titulo: Nombre o tema principal de la petición.
- descripcion: Explicación del problema o solicitud.
- fecha: Fecha en la que fue creada la causa.

La entidad Causa almacena la información de las solicitudes creadas por los ciudadanos.


Entidad: Apoyo

- id: Identificador único del apoyo.
- causa_id: Relación con la causa que recibe el apoyo.
- nombre: Nombre del ciudadano que apoya.
- fecha: Fecha en la que se registró el apoyo.

La entidad Apoyo permite registrar las personas que respaldan una causa y llevar el conteo de participantes.