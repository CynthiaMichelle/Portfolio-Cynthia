---
title: Librería
publishDate: 2019-12-01 00:00:00
img: /assets/stock-2.png
img_alt: Librería
description: Aplicación para creación y visualización de libros.
url: https://github.com/CynthiaMichelle/biblioteca
---
<style>
  p {
    text-align: justify;
  }
</style>
Esta aplicación React es un sistema estructurado para la creación y visualización de libros. Los usuarios pueden añadir libros proporcionando detalles como el título, autor, imagen de portada, una breve introducción y una reseña. Los libros creados se visualizan en la página principal, proporcionando una interfaz interactiva y fácil de usar.

Componentes Principales:
- Book: Muestra un libro individual con su portada, título y un enlace para más detalles. Interactúa con otros componentes para presentar una vista cohesiva.
- View: Despliega detalles completos de un libro seleccionado, incluyendo autor, introducción y reseña.
- Create: Permite a los usuarios crear un nuevo libro, capturando todos los detalles necesarios a través de un formulario interactivo.
- Index: La página principal que muestra todos los libros disponibles, actualizándose dinámicamente con cada nuevo libro agregado.
- Layout: Define el diseño general, incluyendo la barra de navegación (NavBar) y el espacio para el contenido principal.
- NavBar: Una barra de navegación intuitiva con enlaces a las páginas de inicio y creación de libros, mejorando la navegabilidad.
<br>
Hooks:
- useState: Gestiona el estado local de los formularios (Create) y los detalles del libro (View), asegurando una experiencia de usuario interactiva.
- useEffect: Utilizado en View para cargar los detalles del libro cuando la página se carga, asegurando que los datos estén actualizados.
- useContext: Permite compartir el estado de los libros entre componentes (Book, Index, View) sin pasar props manualmente, simplificando el flujo de datos.
<br>
Gestión de Datos (store.js):
<br>
- AppContext: Un contexto de React que proporciona funciones para crear, obtener y actualizar libros. Facilita la administración del estado global de los libros y mejora la escalabilidad de la aplicación.
<br>
<br>
Navegación y Rutas:
<br>

- Se utiliza react-router-dom para manejar la navegación entre diferentes páginas y componentes, con rutas bien definidas que mejoran la experiencia del usuario y facilitan la mantenibilidad del código.
<br>
<br>
Flujo de Usuario:
<br>

- Creación de un Libro: El usuario navega a la página de creación, llena el formulario y envía los detalles. El libro se agrega al estado global y se muestra en la página principal, con retroalimentación adecuada al usuario.

- Visualización de Libros: La página principal muestra todos los libros creados con una interfaz actualizable que refleja inmediatamente las nuevas adiciones.

- Navegación: La barra de navegación permite una transición fluida y clara entre la creación de libros y la vista principal, destacando por su diseño intuitivo y accesibilidad.
<br>
<br>
<a href="https://github.com/CynthiaMichelle/biblioteca" target="_blank">Enlace a GitHub</a>
<br>
<br>
