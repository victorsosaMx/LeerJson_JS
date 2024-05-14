# Generador de Tablas HTML y Sentencias SQL desde JSON

Este script JS permite generar una tabla HTML y sentencias SQL a partir de datos JSON. La aplicación convierte los datos JSON en una tabla HTML y genera las instrucciones SQL necesarias para crear la tabla y insertar los registros en una base de datos SQL Server.
La estructuura de los campos se encuentra anidada desde un JSON: DATA-->> DATA


## Características

- Genera una tabla HTML a partir de datos JSON.
- Crea la instrucción SQL para crear una tabla en SQL Server basada en los datos JSON.
- Genera instrucciones SQL `INSERT` para cada registro presente en los datos JSON.
- Maneja diferentes tipos de datos, como cadenas de texto, números y valores booleanos.
- Permite ingresar el nombre de la tabla destino.
- Muestra las sentencias SQL generadas en áreas de texto para copiar y pegar.

## Tecnologías utilizadas

- HTML
- CSS
- JavaScript

## Instrucciones de uso

1. Abre el archivo `index.html` en un navegador web.
2. Pega los datos JSON en el área de texto "Pega el JSON aquí".
3. Opcionalmente, ingresa el nombre de la tabla destino en el campo de texto "Nombre de la tabla destino".
4. Haz clic en el botón "Crear Tabla".
5. Se generará una tabla HTML con los datos del JSON.
6. Las instrucciones SQL para crear la tabla y insertar los registros se mostrarán en las áreas de texto correspondientes.
7. Puedes copiar y pegar las sentencias SQL según sea necesario.

## Contribuciones

Las contribuciones son bienvenidas. Si encuentras algún problema o tienes sugerencias de mejora, por favor, abre un issue o envía una solicitud de extracción.

## Licencia

Este proyecto está licenciado bajo la [Licencia MIT](LICENSE).
