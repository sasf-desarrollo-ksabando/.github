# Organización de GitHub

Bienvenido a la organización de GitHub. Esta es una organización dedicada a la colaboración y desarrollo en áreas como **capacitaciones**, **proyectos de desarrollo**, **investigación**, entre otros. A continuación, encontrarás los lineamientos y convenciones que seguimos para mantener la consistencia en la organización de nuestros repositorios.

## Estructura de Repositorios

### Nombres de Repositorios

Para facilitar la organización y comprensión de los proyectos, seguimos un sistema de nomenclaturas. Los nombres de los repositorios deben estar compuestos por un **prefijo** que represente el tipo de proyecto y un **nombre corto** que describa el propósito del repositorio.

#### Prefijos de Nomenclatura Común:
- **cp** - Capacitaciones: Proyectos relacionados con la formación de equipos, tutoriales, y cursos.
  - Ejemplo: `cp-programming-basics` (Capacitación en conceptos básicos de programación)
- **ms** - Microservicios: Proyectos relacionados con arquitecturas de microservicios.
  - Ejemplo: `ms-user-authentication` (Microservicio de autenticación de usuario)
- **mf** - Microfrontends: Proyectos relacionados con la arquitectura de microfrontends.
  - Ejemplo: `mf-user-profile` (Microfrontend para la visualización del perfil de usuario)
- **fe** - Frontend: Proyectos de desarrollo en el frontend (sin microfrontends).
  - Ejemplo: `pf-ecommerce-ui` (Frontend para la tienda en línea)
- **be** - Backend: Proyectos de desarrollo en el backend.
  - Ejemplo: `be-payment-service` (Backend para servicios de pago)
- **db** - Base de datos: Repositorios relacionados con la estructura y gestión de bases de datos.
  - Ejemplo: `db-sql-structure` (Estructura de base de datos SQL para gestión de clientes)
- **ia** - Inteligencia Artificial: Proyectos relacionados con IA, aprendizaje automático, procesamiento de datos, etc.
  - Ejemplo: `ia-recommendation-system` (Sistema de recomendación basado en IA)
- **doc** - Documentación: Repositorios destinados exclusivamente a la documentación de proyectos o procesos.
  - Ejemplo: `doc-telconet-process` (Análisis de datos de ventas)
- **pb** - Power Bi: Herramientas para monitoreo y control de tiempos, productividad, etc.
  - Ejemplo: `pb-time-tracking` (Aplicación para seguimiento de tiempo de trabajo)
 
### Convenciones para Commit Messages
Utilizamos una convención estándar para los mensajes de commits para asegurar claridad y consistencia. Los mensajes deben seguir el siguiente formato: <tipo>(<área>): <mensaje breve en presente>

#### Tipos comunes:

- **feat**: Nueva funcionalidad. Se usa cuando se agrega una nueva característica o funcionalidad al proyecto.
- **fix**: Corrección de errores. Se utiliza cuando se soluciona un error o problema en el código.
- **docs**: Cambios en la documentación. Se emplea cuando se hace una modificación en los archivos de documentación del proyecto.
- **style**: Cambios de estilo. Se utiliza para cambios que no afectan el código funcional, como la indentación, el formato o los espacios.
- **refactor**: Refactorización de código. Se emplea cuando se realiza una reestructuración del código sin cambiar su funcionalidad.
- **test**: Añadir o modificar pruebas. Se usa para agregar nuevas pruebas o modificar las existentes.
- **chore**: Tareas generales o de mantenimiento. Se usa para tareas que no encajan en otras categorías, como actualizaciones de dependencias o cambios en el entorno de desarrollo.

#### Ejemplos:

- `feat(auth): agregar login con Google`
- `fix(ui): corregir bug en el modal de registro` 
- `docs(readme): actualizar sección de instalación`
- `style(main): corregir indentación en archivo principal` 
- `refactor(auth): simplificar lógica de validación`
- `test(auth): agregar pruebas para el registro de usuario`
- `chore(deps): actualizar dependencias de producción` 

Este formato ayuda a mantener los mensajes claros, consistentes y fáciles de entender para todos los miembros del equipo.



