# PersonaN — Aplicación Node.js (Express + Handlebars + MySQL)

Este repositorio contiene una aplicación web construida con **Node.js** usando **Express**, motor de plantillas **Handlebars** y conexión a **MySQL**.

## Tecnologías
- Express
- express-handlebars
- MySQL (mysql2)
- Morgan (logs)
- Nodemon (desarrollo)

## Estructura
- `src/index.js`: entrada principal de la aplicación.
- `src/database.js`: configuración/conexión a base de datos.
- `src/routes/`: rutas del servidor.
- `src/views/`: vistas (plantillas) renderizadas.

## Ejecución (modo desarrollo)
1. Instala dependencias:

```bash
npm install
```

2. Ejecuta en dev:

```bash
npm run dev
```

> El script `dev` usa nodemon sobre `src/index.js`.

## Configuración de base de datos
Revisa `src/database.js` y/o los archivos dentro de `src/database/` para configurar host, usuario, contraseña y nombre de la BD.

## Objetivo
Proyecto orientado a practicar un flujo típico MVC sencillo:
- rutas (controllers)
- vistas (handlebars)
- persistencia en MySQL
