# TP1 - Parte Individual: Actividad B

Implementación de los ejercicios solicitados para el **Trabajo Práctico 1, Unidad 4**, cuyo objetivo es realizar operaciones **ABM (Alta, Baja y Modificación)** sobre datos mediante interfaces desarrolladas con React.

## Contenido

| Ejercicio | Entidad | Operaciones | Tecnologías | Persistencia |
|---|---|---|---|---|
| [Ejercicio 1](./Ejercicio1/) | Empleados | Crear, listar, editar y eliminar | React, React Router y React Bootstrap | Memoria de la aplicación |
| [Ejercicio 2](./Ejercicio2/) | Clientes | Crear, listar, editar y eliminar | React, Vite y Chakra UI | `localStorage` del navegador |

## Requisitos

- Node.js y npm instalados.
- Un navegador web actualizado.

Cada ejercicio es una aplicación independiente y posee su propio `package.json`. Los comandos deben ejecutarse desde la carpeta de la aplicación correspondiente.

## Ejecución rápida

### Ejercicio 1

```bash
cd Ejercicio1/simple-react-crud-app
npm install
npm start
```

La aplicación se abrirá en [http://localhost:3000](http://localhost:3000).

> El código utiliza el paquete `uuid` para generar identificadores al crear empleados. Si npm informa que falta ese módulo, instalarlo con `npm install uuid`.

### Ejercicio 2

```bash
cd Ejercicio2/CRUD-REACT-1
npm install
npm run dev
```

Vite mostrará en la terminal la URL local, normalmente [http://localhost:5173](http://localhost:5173).

## Alcance del ABM

### Ejercicio 1 - Empleados

- **Alta:** el botón `Create` abre un formulario para ingresar nombre y edad.
- **Baja:** el botón `DELETE` elimina el empleado seleccionado.
- **Modificación:** el botón `Edit` carga los datos existentes y permite actualizarlos.
- **Consulta/listado:** la pantalla inicial muestra la tabla de empleados.
- Los datos iniciales se encuentran en `src/components/Employees.js`.
- Los cambios se mantienen únicamente mientras la aplicación está abierta, porque se almacenan en memoria.

### Ejercicio 2 - Clientes

- **Alta:** `NUEVO REGISTRO` abre un formulario modal para ingresar nombre y e-mail.
- **Baja:** el ícono de eliminación borra el cliente seleccionado.
- **Modificación:** el ícono de edición abre el modal con los datos actuales.
- **Consulta/listado:** la pantalla principal muestra nombre y e-mail.
- No permite guardar campos vacíos ni e-mails duplicados.
- Los datos se guardan en `localStorage` con la clave `cad_cliente`, por lo que permanecen al recargar la página en el mismo navegador.

## Estructura

```text
.
├── Ejercicio1/
│   ├── README.md
│   └── simple-react-crud-app/
└── Ejercicio2/
    ├── README.md
    └── CRUD-REACT-1/
```

La solución es de carácter académico: no utiliza una API ni una base de datos externa.
