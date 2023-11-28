---
title: Nodepop
publishDate: 2020-03-02 00:00:00
img: /Portfolio-Cynthia/assets/stock-1.png
img_alt: Venta artículos de segunda mano
description: Venta de artículos de segunda mano. 
url: https://github.com/CynthiaMichelle/nodepop
---
<style>
  p {
    text-align: justify;
  }
</style>

Nodepop es un proyecto de aplicación web para la venta de artículos de segunda mano. A través de esta plataforma, los usuarios pueden comprar y vender artículos, con la posibilidad de buscar productos utilizando varios filtros como el tag, tipo de anuncio (venta o compra), rango de precios y nombre del artículo.

La aplicación permite la internacionalización, es decir, se puede utilizar en diferentes idiomas, y se encarga de la subida de imágenes en background, lo que significa que las imágenes se procesan en un servicio separado sin afectar la interacción del usuario con la página web.

En el backend, Nodepop usa Node.js con el framework Express para manejar las solicitudes HTTP y Mongoose para interactuar con una base de datos MongoDB. Esto permite realizar operaciones CRUD (crear, leer, actualizar y borrar) en los anuncios. El proyecto también incluye autenticación JWT para proteger el API y asegurar que solo los usuarios autorizados puedan realizar ciertas acciones.

Para el frontend, se utiliza una plantilla EJS para mostrar la lista de anuncios, que puede filtrarse por medio de la URL. Esto se hace para simplificar la interacción con el API y facilitar la implementación de filtros por parte de los usuarios.

En el proyecto también hubo la creación de un microservicio usando RabbitMQ para gestionar la creación de miniaturas (thumbnails) para las imágenes subidas, mejorando así el rendimiento y la eficiencia del procesamiento de imágenes.

El objetivo era desarrollar una API bien documentada y estructurada que pueda ser fácilmente mantenida y utilizada por otros desarrolladores.

<br>
<br>
<a href="https://github.com/CynthiaMichelle/nodepop" target="_blank">Enlace a GitHub</a>
<br>
<br>
