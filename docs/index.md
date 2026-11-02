# Documentación de API de Productos

## Qué es

Esta es una pequeña API REST de productos desarrollada con **Node.js** y **Express**.

## Endpoints (qué hace)

Tiene 3 productos en memoria, y dos *endpoints*:

```http
GET /api/productos
GET /api/productos/{id}
```

Con estas operaciones, podemos:

* Obtener un listado de los productos en memoria
* Obtener la información de un producto por su número de identificación (ID)