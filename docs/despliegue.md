# Procedimiento de despliegue

## Pasos

1. Descarga el código fuente del proyecto y abre un terminal en la carpeta donde está `package.json`.
2. Instala las dependencias de la aplicación:

   ```bash
   npm install
   ```

3. Inicia la API:

   ```bash
   npm start
   ```

   El servidor queda escuchando en el puerto `3000`. Mantén este terminal abierto mientras utilizas la API.

4. En otro terminal, comprueba que responde y devuelve la lista de productos:

   ```bash
   curl http://localhost:3000/api/productos
   ```

## Checklist básico

- [ ] No se han incluido contraseñas ni secretos en el repositorio
- [ ] Los posibles ficheros con secretos están incluidos en .gitignore
- [ ] En producción debería utilizarse HTTPS
- [ ] Solo deberían exponerse los puertos necesarios
