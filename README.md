# Diplomadov2

La tarea 4, Este proyecto fue generado utilizando Angular CLI versión 19.2.10 y permite gestionar tareas de forma intuitiva y organizada. Ofrece funcionalidades para crear, editar y eliminar tareas, además de asignar categoría, prioridad y fechas clave para mejorar la planificación.

## Development server

Ejecuta el siguiente comando en la terminal:

ng serve


Una vez iniciado, abrir el navegador http://localhost:4200/

## Estructura
Para la realizacion de la tarea, se trabajo en: 
- services:
  task.service.ts    # Gestión de tareas
  
- task-form:
  task-form.component.ts   # Lógica del formulario
  task-form.component.html # Vista del formulario
  task-form.component.css  # Estilos del formulario
  
- task-list-component:
  task-list-component.component.ts   # Lógica de la lista
  task-list-component.component.html # Vista de la lista
  task-list-component.component.css  # Estilos de la lista

- task-item
  task-item.component.ts   # Lógica de cada tarea
  task-item.component.html # Vista de cada tarea
  task-item.component.css  # Estilos de cada tarea
  
- app
  app.component.html       # Plantilla principal
  app.component.ts         # Componente principal
