# Ejercicio 2 - ABM de clientes

Aplicación React desarrollada con Vite y Chakra UI para administrar clientes mediante un formulario modal.

## Ejecutar

Desde esta carpeta:

```bash
cd CRUD-REACT-1
npm install
npm run dev
```

La URL local se informa en la terminal de Vite, normalmente [http://localhost:5173](http://localhost:5173).

## Funcionalidades

- Listado de clientes con nombre y e-mail.
- Alta mediante `NUEVO REGISTRO`.
- Modificación mediante el ícono de edición.
- Baja mediante el ícono de eliminación.
- Validación de campos obligatorios.
- Validación de e-mails duplicados.
- Persistencia en `localStorage` con la clave `cad_cliente`.

## Scripts disponibles

- `npm run dev`: inicia el servidor de desarrollo.
- `npm run build`: genera la versión de producción.
- `npm run lint`: ejecuta ESLint.
- `npm run preview`: previsualiza la compilación.
