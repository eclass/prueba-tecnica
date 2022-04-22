# Desarrollador Backend

La prueba consiste en hacer un microservicio con un mantenedor de usuarios, el modelo de datos queda al criterio del postulante.

La app debe contar con:

- Login de usuario
- Dos perfiles (admin/usuario)
- Un mantenedor de usuarios

La autentificación al servicio debe ser debe ser por medio de un usuario y contraseña, el usuario puede ser el correo electrónico de la persona.
Una vez autenticado retornar un TOKEN JWT para poder usar como validación en las otras peticiones.

## Funcionalidad esperada

- Login de usuario
- Mantenedor de personas y sus contraseñas de acceso
- Buscador de usuarios por distintos criterios
- Dos perfiles
- Perfil visita: sólo tiene acceso al listado de usuarios y puede visualizar los datos de cada uno
- Perfil admin: incluye lo del perfil visita y además puede modificar, eliminar, desactivar, modificar y cambiar contraseña de cualquier usuario.

## Pauta a seguir

- La aplicación debe ser desarrollada usando Node 16+
- El código debe quedar en un repositorio público como github y deberá ser compartido para su revisión, con una base de datos de prueba con datos precargados y un usuario y contraseña de test para cada perfil.
- Se deberá generar una pequeña documentación de su uso del servicio (`apiary` puede ser un ejemplo) o enviar estructura para `Insomnia` o `Postman` con los request necesarios del microservicio.
- Código limpio y reusable.
- Utilizar un algoritmo de encriptación de contraseña (no es MD5).
- Funcionalidades adicionales útiles por parte del postulante (queda a tu criterio y tiempo).

## Los criterios de evaluación serán

- Funcionalidad de la aplicación
- Implementación
- Validaciones
- Convención de código
- Capa de seguridad para cada perfil
- Orden

Si tienes alguna pregunta, no dudes en escribirnos.

- victor@eclass.com
- sebastian@eclass.com

¡Saludos!
