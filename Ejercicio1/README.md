# Ejercicio 1 - ABM de empleados

Aplicación React para realizar el alta, baja, modificación y listado de empleados.

## Ejecutar

Desde esta carpeta:

```bash
cd simple-react-crud-app
npm install
npm start
```

La aplicación estará disponible en [http://localhost:3000](http://localhost:3000).

> `src/components/Add.js` utiliza `uuid` para generar identificadores. Si el paquete no se instala desde el manifiesto, ejecutar `npm install uuid`.

## Funcionalidades

- Listado de empleados con nombre y edad.
- Alta mediante el formulario `Create`.
- Modificación mediante el formulario `Edit`.
- Baja mediante el botón `DELETE`.
- Navegación entre listado, alta y edición con React Router.

Los empleados iniciales se encuentran en `simple-react-crud-app/src/components/Employees.js`. La información se mantiene en memoria y se reinicia al recargar la aplicación.

## Scripts disponibles

- `npm start`: inicia el servidor de desarrollo.
- `npm test`: ejecuta las pruebas configuradas.
- `npm run build`: genera la versión de producción.
