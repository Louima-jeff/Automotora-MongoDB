# Automotora Web con MongoDB

## Descripción del proyecto

Este proyecto consiste en una aplicación web para gestionar la información de una automotora.

Permite registrar, consultar, actualizar y eliminar clientes, vehículos, ventas y pagos mediante una base de datos NoSQL MongoDB.

Proyecto desarrollado para la Evaluación Parcial 3 de Taller de Base de Datos (BDY1103), Duoc UC.

## Problema del negocio

La automotora necesita organizar la información de sus clientes, vehículos, ventas y pagos para facilitar su administración y consulta.

## Solución implementada

Desarrollamos una aplicación web conectada a MongoDB que permite centralizar la información y realizar operaciones CRUD.

## Tecnologías utilizadas

- HTML: estructura de la interfaz web.
- CSS: diseño y presentación.
- JavaScript: funcionamiento de la interfaz.
- Node.js: ejecución del servidor.
- Express: creación de la API REST.
- MongoDB: almacenamiento de datos NoSQL.
- MongoDB Compass: visualización de las colecciones y documentos.

## Base de datos

Nombre: `automotora_nosql`

Colecciones:

- `clientes`
- `vehiculos`
- `ventas`
- `pagos`

## Operaciones CRUD

| Operación | Función |
|---|---|
| CREATE | Registrar información |
| READ | Consultar información |
| UPDATE | Modificar información |
| DELETE | Eliminar información |

## Estructura principal

```text
AutomotoraWeb/
├── server.js
├── Automotora_Interfaz.html
├── Automotora_respaldo.html
├── package.json
└── package-lock.json
```

## Instalación y ejecución

Requisitos:

- Node.js
- MongoDB

1. Descargar el proyecto.
2. Abrir una terminal dentro de la carpeta.
3. Instalar las dependencias:

```bash
npm install
```

4. Iniciar MongoDB localmente.
5. Ejecutar el servidor:

```bash
node server.js
```

6. Abrir la aplicación en el navegador:

http://localhost:3000/Automotora_Interfaz.html

## API REST

La aplicación utiliza las siguientes rutas:

- `/api/clientes`
- `/api/vehiculos`
- `/api/ventas`
- `/api/pagos`

Cada módulo permite realizar operaciones CRUD.

## Pruebas realizadas

Se comprobaron las siguientes operaciones:

- Registro de clientes, vehículos, ventas y pagos.
- Consulta de información almacenada.
- Modificación de registros.
- Eliminación de registros.
- Verificación de cambios en MongoDB Compass.

## Conclusión

El proyecto Automotora demuestra la integración de una interfaz web con una API desarrollada en Node.js y Express y una base de datos NoSQL MongoDB.

La aplicación permite administrar la información del negocio mediante operaciones CRUD y mantener los registros almacenados en la base de datos.

## Autor

Gefmy Louima

Ingeniería Informática

Duoc UC

Asignatura: Taller de Base de Datos, BDY1103.
