# Instalación

## Software necesario

- Node.js
- NPM
- Navegador de confianza (Firefox, Chrome, Edge...) o `curl` en `bash`
- (Opcional) Postman u otra herramienta para enviar y consultar peticiones HTTP.


## Cómo obtener el proyecto

**Descarga** el repositorio de Github: [Aquí](https://github.com/mxescag/api-productos-a14).

## Instalación de dependencias

1. Una vez lo tengas descargado, sitúate en la carpeta del repositorio (el nombre será algo como "api-productos-a14").
2. Abre una sesión de terminal desde la carpeta y ejecuta:
```bash
npm install
```
Esto **instala las dependencias**.

## Inicio de la aplicación

1. En un terminal, dentro de la carpeta del repositorio, ejecuta:
```bash
npm start
```
Si todo funciona bien, debería devolver algo como:
```bash
API disponible en http://localhost:3000
```
## Comprobación de funcionamiento

1. Para realizar peticiones a la API, inicia el navegador y accede a `http://localhost:3000/api/productos`.
2. También puedes realizar peticiones desde tu terminal abriendo otra sesión y utilizando `curl`, así:
```bash
curl http://localhost:3000/api/productos
curl http://localhost:3000/api/productos/1
curl http://localhost:3000/api/productos/99
```

