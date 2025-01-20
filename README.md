# ForoHub - API

## Descripción
ForoHub es una API para gestionar un foro en línea donde los usuarios pueden crear, listar y eliminar tópicos.

## Requisitos
- Java 17 o superior
- MySQL 8 o superior

## Instalación
1. Clonar el repositorio.
2. Configurar la base de datos `forohub` en MySQL.
3. Configurar las credenciales en `application.properties`.
4. Ejecutar la aplicación.

## Endpoints
- `POST /topics`: Crear un nuevo tópico.
- `GET /topics/{id}`: Obtener detalles de un tópico.
- `GET /topics`: Listar todos los tópicos.
- `DELETE /topics/{id}`: Eliminar un tópico.

## Autenticación
La API utiliza JWT para la autenticación. Se debe enviar un token en los encabezados de las solicitudes.

