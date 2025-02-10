# IS1-TP-TusLibros  

Trabajo práctico realizado para la materia **Ingeniería de Software 1**, en conjunto con [Leonardo Duchen](https://github.com/LeoDuchen).  

**Lenguaje:** Smalltalk (CuisUniversity)  
**Descripción:** Desarrollo del backend para un e-commerce de una editorial.  

**Notas:**  
- El frontend fue provisto por la cátedra. 
- La consigna se encuentra en el archivo [`consigna.md`](./consigna.md).
- Por razones de tiempo, no se completó la funcionalidad de *"interface batch"*.

## Levantar el servidor  

1. Usar una imagen limpia de **CuisUniversity**.  
2. Instalar el paquete `WebClient`.  
3. Ir a la carpeta `backend` y arrastrar el archivo correspondiente a la imagen (*file in*).  
4. Abrir un *workspace* y ejecutar:  

    ```smalltalk
    api := ExternalRestInterface new.
    ```
5. El servidor se quedará escuchando en el puerto 9000. Para detenerlo, ejecutar: `api endServerConnection`.

## Levantar el frontend

1. Ir a la carpeta frontend.
2. En una consola, ejecutar: `npm install`.
3. Luego, iniciar el servidor con: `npm start`.

## Posibles problemas con CORS

Si se presentan problemas de CORS, abrir Chrome de la siguiente manera:

1. Windows (Win + R): `"C:\Program Files\Google\Chrome\Application\chrome.exe" --disable-web-security --user-data-dir="C:/ChromeDev"`.
2. Luego, ingresar a `localhost:3000` en el navegador.