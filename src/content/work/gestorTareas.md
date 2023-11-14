---
title: Gestor de Tareas
publishDate: 2020-03-02 00:00:00
img: /assets/stock-1.png
img_alt: Gestor de tareas
description: Aplicación para gestionar tareas. 
url: https://github.com/CynthiaMichelle/gestor_tareas
---
<style>
  p {
    text-align: justify;
  }
</style>
La aplicación trata de un sistema de gestión de tareas que permite a los usuarios añadir, modificar y eliminar tareas. Está construida con React y proporciona una interfaz de usuario interactiva y fácil de usar.

Componentes Principales:

- Todo: Representa una tarea individual. Permite a los usuarios editar o eliminar la tarea. Contiene dos subcomponentes: FormEdit para editar la tarea y TodoElement para mostrar los detalles de la tarea. 
- TodoApp: Es el componente principal que maneja la lista de tareas (todos). Permite a los usuarios crear nuevas tareas y pasa funciones de actualización y eliminación a los componentes Todo.
- App: Sirve como el componente raíz de la aplicación y encapsula TodoApp.

Hooks:
- useState: Se usa para gestionar el estado de las tareas y los detalles de cada tarea. Controla la entrada de datos en los formularios y el estado de cada tarea en la lista.
- preventDefault en handleSubmit: Previene la recarga de la página en la presentación del formulario, asegurando una experiencia de usuario fluida.

Funciones Principales:
- handleSubmit: Agrega una nueva tarea a la lista.
- handleUpdate: Actualiza el título de una tarea existente.
- handleDelete: Elimina una tarea de la lista.

Gestión de Datos:
- Estado Local (useState): Gestiona la lista de tareas y los detalles de cada tarea. Asegura que la interfaz de usuario se actualice en respuesta a los cambios en el estado.

Navegación y Estructura:
- La aplicación gestiona la navegación interna entre la creación, edición y eliminación de tareas mediante el uso de estados y la actualización de componentes.

La interfaz proporciona una interacción inmediata con las tareas y retroalimentación visual de las acciones del usuario.


<br>
<br>
<a href="https://github.com/CynthiaMichelle/gestor_tareas" target="_blank">Enlace a GitHub</a>
<br>
<br>
