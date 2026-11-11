# Sistema de acceso a biblioteca · CETYS

Proyecto universitario en equipo para registrar accesos a la biblioteca y consultar métricas con React, Node.js y PostgreSQL.

## Aportación de Luis Vargas

Desarrollo de vistas del dashboard, gráficas, registro de ingresos y reorganización de los menús de administrador y empleado. El historial conserva las contribuciones de todo el equipo.

## Configuración local

El frontend está en `dashboard_cetys/` y el servidor en `dashboard_cetys/backend/`. Cada carpeta contiene su propio `package.json` y se inicia con `npm run dev` después de instalar sus dependencias.

Copia `dashboard_cetys/backend/.env.example` a `dashboard_cetys/backend/.env` y configura una base PostgreSQL de prueba con el esquema que requieren las consultas del servidor. La aplicación depende de esa base de datos para registrar y consultar accesos.

Los archivos `.env` se excluyen de las nuevas versiones del repositorio. Las credenciales incluidas en revisiones históricas deben sustituirse en su proveedor si siguen vigentes.

## Versión web

[Probar la aplicación](https://luisvvargas-swe.github.io/proyectos/biblioteca/). El código de la adaptación para navegador está en `web/`.
La demo usa estudiantes ficticios y guarda visitas en el navegador. Permite registrar entradas y salidas, filtrar visitas y exportarlas en CSV.
