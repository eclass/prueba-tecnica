# Desarrollador Backend

La prueba consiste en hacer una app con un mantenedor de usuarios, el modelo de datos queda al criterio del postulante.

La app debe contar con:

- Login de usuario
- Dos perfiles (admin/usuario)
- Un mantenedor de usuarios.

La autentificación a la plataforma debe ser por medio de un usuario y contraseña, el usuario puede ser el correo electrónico de la persona.

## Funcionalidad esperada

- Login de usuario
- Mantenedor de personas y sus contraseñas de acceso
- Buscador de usuarios por distintos criterios
- Dos perfiles
- Perfil visita: sólo tiene acceso al listado de usuarios y puede visualizar los datos de cada uno
- Perfil admin: incluye lo del perfil visita y además puede modificar, eliminar, desactivar, modificar y cambiar contraseña de cualquier usuario.

## Pauta a seguir

- La aplicación debe ser desarrollada usando CakePHP 2._ o 3._ y Bootstrap en el front.
- El código debe quedar en un repositorio público como github y deberá ser compartido para su revisión, con una base de datos de prueba con datos precargados y un usuario y contraseña de test para cada perfil.
- Se deberá generar una URL pública que permita probar lo desarrollado, de lo contrario no será considerado.
- Para el punto anterior se puede usar `Heroku`, los créditos gratuitos de `amazon` o `Vercel` te ayudarán si no sabes donde subir la app.
- Código limpio y reusable.
- Utilización de funcionalidades nativas del framework.
- Utilizar un algoritmo de encriptación de contraseña (no es MD5).
- Funcionalidades adicionales útiles por parte del postulante.

## Los criterios de evaluación serán

- Funcionalidad de la aplicación
- Implementación
- Validaciones
- Convención de código y namespacing
- Capa de seguridad para cada perfil
- Orden
