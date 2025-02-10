# IS1-TP-TusLibros

TP realizado para la materia: Ingeniería de Software 1. El trabajo fue realizado junto con [Leonardo Duchen](https://github.com/LeoDuchen).

Lenguaje: Smalltalk (CuisUniversity).

Descripción: Desarrollar el backend de una aplicación FullStack que es el e-commerce de una editorial.

Nota: El frontend ya vino desarrollado por la cátedra.

## Levantar el servidor

- Levantar con una imagen de CuisUniversity limpia.

- Instalar el paquete "WebClient".

- Ir a la carpeta backend y arrastrar a la imagen el archivo.

- Abrir un workspace y ejecutar lo siguiente: `api := ExternalRestInterface new`.

Ahora el servidor va a estar escuchando en el puerto 9000. Para apagarlo, ejecutar en el workspace: `api endServerConnection`.

## Levantar el frontend

- Ir a la carpeta frontend.

- En una consola, ejecutar `npm install`.

- En una consola, ejecutar `npm start`.