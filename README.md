# TaskFlow

TaskFlow es una aplicación para iPhone que permite registrar, organizar y consultar tareas académicas. El proyecto se desarrolla como producto final del curso mediante trabajo colaborativo, control de versiones con Git y gestión del repositorio en GitHub.

> Este archivo es un ejemplo. Cada equipo deberá sustituir el nombre, la descripción, los integrantes, las funcionalidades y los acuerdos por la información correspondiente a su proyecto.

## Integrantes del equipo

| Integrante | Matrícula | Funcionalidad asignada |
| --- | --- | --- |
| Ana López | A01234567 | Registro e inicio de sesión |
| Carlos Pérez | A01234568 | Creación y edición de tareas |
| Fernanda Ruiz | A01234569 | Lista y detalle de tareas |
| Luis García | A01234570 | Pruebas e integración |

## Entorno de desarrollo

- Plataforma: iOS
- Lenguaje: Swift
- Interfaz: SwiftUI
- Versión de Xcode: 26.0
- Modelo utilizado en el simulador: iPhone 16 Pro
- Versión mínima de iOS: 18.0

## Funcionalidades

- Registrar e iniciar sesión en la aplicación.
- Crear una tarea con título, descripción y fecha límite.
- Consultar la lista de tareas registradas.
- Editar y eliminar tareas.
- Marcar una tarea como terminada.
- Mostrar el detalle de cada tarea.

## Estructura inicial del repositorio

```text
TaskFlow/
├── .gitignore
├── README.md
├── TaskFlow.xcodeproj
├── TaskFlow/
├── TaskFlowTests/
└── TaskFlowUITests/
```

Los archivos `.gitignore` y `README.md` se encuentran en la raíz del repositorio. El archivo `.gitignore` se incorporó antes del primer commit para evitar que Git registre archivos generados por Xcode, configuraciones locales y otros elementos que no deben compartirse.

## Convención para nombrar ramas

Cada funcionalidad se desarrollará en una rama independiente. Los nombres se escribirán en minúsculas, sin espacios y con palabras separadas mediante guiones.

Formato:

```text
tipo/descripcion-breve
```

Ejemplos:

```text
feature/inicio-sesion
feature/crear-tarea
fix/corregir-fecha-limite
docs/actualizar-readme
test/pruebas-lista-tareas
```

Tipos de rama utilizados:

- `feature`: desarrollo de una funcionalidad.
- `fix`: corrección de un error.
- `docs`: cambios en la documentación.
- `test`: incorporación o modificación de pruebas.

## Flujo de colaboración

1. Actualizar la copia local de `main` antes de comenzar una tarea.
2. Crear una rama independiente a partir de la versión actualizada de `main`.
3. Desarrollar y probar la funcionalidad asignada.
4. Realizar commits con mensajes claros y descriptivos.
5. Publicar la rama en GitHub.
6. Crear un pull request hacia `main`.
7. Solicitar la revisión de al menos otra persona del equipo.
8. Atender la retroalimentación y resolver los conflictos antes de integrar los cambios.

## Convención para mensajes de commit

Se utilizarán mensajes breves que indiquen claramente la modificación realizada.

Formato:

```text
tipo: descripción del cambio
```

Ejemplos:

```text
feat: agrega formulario para crear tareas
fix: corrige validación de la fecha límite
docs: actualiza la lista de funcionalidades
test: agrega pruebas para eliminar tareas
```

## Acuerdos básicos de colaboración

- No realizar cambios directamente en `main` después de publicar la versión inicial.
- Desarrollar cada funcionalidad en una rama independiente.
- No integrar una rama que no compile o que presente errores conocidos.
- Verificar que la aplicación se ejecute en el simulador antes de crear un pull request.
- Utilizar mensajes de commit claros y descriptivos.
- Solicitar la revisión del código antes de integrarlo en `main`.
- Atender con respeto la retroalimentación recibida.
- Comunicar oportunamente los bloqueos o conflictos encontrados.
- No publicar contraseñas, tokens, llaves, certificados ni otros datos sensibles.
- Mantener actualizados el archivo `README.md` y la lista de funcionalidades.

## Ejecución del proyecto

1. Clonar el repositorio.
2. Abrir `TaskFlow.xcodeproj` en Xcode.
3. Seleccionar el simulador indicado en la sección de entorno de desarrollo.
4. Compilar y ejecutar la aplicación.

## Estado inicial

La versión inicial del proyecto compila y se ejecuta correctamente en el simulador. Las funcionalidades se incorporarán de forma incremental mediante ramas y pull requests.

