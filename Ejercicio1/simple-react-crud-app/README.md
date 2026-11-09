# Simple React CRUD App

Implementación del Ejercicio 1 del TP1 Parte Individual: Actividad B. Permite administrar empleados mediante operaciones ABM.

## Inicio

```bash
npm install
npm start
```

Abrir [http://localhost:3000](http://localhost:3000).

Si aparece un error porque no se encuentra `uuid`, instalar la dependencia con:

```bash
npm install uuid
```

## Rutas

- `/`: listado de empleados.
- `/create`: formulario de alta.
- `/edit`: formulario de modificación.

Los datos se definen en `src/components/Employees.js` y se modifican en memoria; no existe persistencia en una base de datos.

## Scripts

```bash
npm start
npm test
npm run build
```
