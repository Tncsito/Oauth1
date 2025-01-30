Descripción:

Este proyecto es una aplicación en Node.js que permite a los usuarios autenticarse con Google mediante OAuth2 y obtener una lista de sus archivos almacenados en Google Drive. Utiliza Express para manejar las rutas y JSON Web Tokens (JWT) para asegurar el acceso a ciertas funciones.

Características:

Autenticación con Google OAuth2: Los usuarios pueden iniciar sesión con su cuenta de Google.

Generación de JWT: Una vez autenticado, se genera un token JWT con los datos del usuario.

Protección con Middleware: Se verifica el JWT antes de permitir el acceso a la lista de archivos.

Listado de Archivos de Google Drive: Se muestra una lista de los primeros 10 archivos del usuario en Google Drive.
