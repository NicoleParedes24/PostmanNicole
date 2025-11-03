# PostmanNicole
Práctica Postman – Métodos HTTP

API utilizada:
https://restful-api.dev/



## Método GET
```
GET https://restful-api.dev/objects
```
Descripción:
Obtiene todos los objetos disponibles en la API.

## Método POST
```
POST https://restful-api.dev/objects
```
JSON enviado:
```
{
  "name": "Apple Ipad Pro 16 , 8 gen",
  "data": {
    "year": 2019,
    "price": 849.99,
    "CPU model": "Intel Core i9",
    "Hard disk size": "1 TB"
  }
}
```
Descripción:
Crea un nuevo objeto en la base de datos.


## Método PUT
```
PUT https://restful-api.dev/objects/ff80818119782e69e019a2cc3232d72f5
```
JSON enviado:
```
{
  "id": "ff80818119782e69e019a2cc3232d72f5",
  "name": "Apple Ipad Pro 16 , 8 gen",
  "data": {
    "year": 2019,
    "price": 849.99,
    "CPU model": "Intel Core i9",
    "Hard disk size": "1 TB"
  }
}
```
Descripción:
Actualiza el objeto con el ID especificado.


## Método DELETE
```
DELETE https://restful-api.dev/objects/ff80818119782e69e019a2cc3232d72f5
```
Descripción:
Elimina el objeto con el ID indicado.



## Evidencia
Las capturas de pantalla de cada método ejecutado se encuentran en el archivo PDF adjunto:
NicoleParedes_TallerPostman.pdf

## Repositorio GitHub
https://github.com/NicoleParedes24/PostmanNicole

