# Diplomadov2

La tarea 4, Este proyecto fue generado utilizando Angular CLI versión 19.2.10 y permite gestionar tareas de forma intuitiva y organizada. Ofrece funcionalidades para crear, editar y eliminar tareas, además de asignar categoría, prioridad y fechas clave para mejorar la planificación.

## Development server

Ejecuta el siguiente comando en la terminal:

ng serve


Una vez iniciado, abrir el navegador http://localhost:4200/

## Estructura
Para la realizacion de la tarea, se trabajo en: services, task-form, task-list-component, task-item, app.component.ts

PROYECTOMOD2
├── .angular                # Configuraciones internas de Angular
├── .vscode                 # Configuraciones del editor de código
├── node_modules            # Dependencias de npm
├── public                  # Archivos públicos
├── src                     # Código fuente del proyecto
│   ├── app                 # Módulo principal de la aplicación
│   │   ├── componente-boton-completada # Componente para marcar tareas completadas
│   │   ├── componente-boton-pendiente   # Componente para marcar tareas pendientes
│   │   ├── panel-botones    # Contenedor de botones de acción
│   │   ├── services         # Servicios para la lógica de negocio
│   │   │   ├── task.service.ts          # Gestión de tareas
│   │   ├── task-form        # Formulario para agregar tareas
│   │   │   ├── task-form.component.ts   # Lógica del formulario
│   │   │   ├── task-form.component.html # Vista del formulario
│   │   │   ├── task-form.component.css  # Estilos del formulario
│   │   ├── task-list-component # Lista de tareas
│   │   │   ├── task-item               # Componente para cada tarea
│   │   │   │   ├── task-item.component.ts   # Lógica de cada tarea
│   │   │   │   ├── task-item.component.html # Vista de cada tarea
│   │   │   │   ├── task-item.component.css  # Estilos de cada tarea
│   │   │   ├── task-list-component.component.ts  # Lógica de la lista
│   │   │   ├── task-list-component.component.html # Vista de la lista
│   │   │   ├── task-list-component.component.css  # Estilos de la lista
│   │   ├── app.component.ts    # Componente principal
│   │   ├── app.module.ts       # Módulo principal
│   │   ├── app.routes.ts       # Definición de rutas
│   │   ├── app.config.ts       # Configuraciones generales
│   ├── index.html              # Página de entrada
│   ├── main.ts                 # Punto de inicio de la aplicación
│   ├── styles.css              # Estilos globales
├── .editorconfig               # Configuraciones del editor
├── .gitignore                  # Archivos ignorados en Git
├── angular.json                # Configuración de Angular
└── package-lock.json            # Dependencias del proyecto



