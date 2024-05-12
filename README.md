# Integración de Azure Cognitive Services AI con Spring Boot y Base de Datos

Este proyecto demuestra cómo integrar los servicios cognitivos de inteligencia artificial (AI) de Azure con una aplicación Spring Boot que utiliza una base de datos PostgreSQL para almacenar las traducciones realizadas.

## Concepto

El objetivo principal de este proyecto es utilizar los servicios cognitivos de AI de Azure, específicamente el servicio Translator Text, para traducir texto de un idioma a otro en una aplicación Spring Boot. Utilizando la API del servicio Translator, la aplicación recibe texto en un idioma de origen, lo traduce al idioma de destino especificado y guarda tanto el texto original como el traducido en una base de datos PostgreSQL.

## Herramientas y Tecnologías Utilizadas

- **Azure Cognitive Services**: Se utiliza el servicio Translator Text de Azure Cognitive Services para realizar la traducción de texto.
- **Spring Boot**: Se utiliza para construir la aplicación web que maneja las solicitudes HTTP y la lógica de negocio.
- **PostgreSQL**: Se utiliza como base de datos para almacenar las traducciones realizadas.
- **Java**: El lenguaje de programación principal utilizado en el backend de la aplicación.
- **JSON**: Formato de intercambio de datos utilizado para comunicarse con la API de Azure Translator y para la respuesta de la aplicación.

## Dependencias de Spring Boot

Las dependencias de Spring Boot utilizadas en este proyecto incluyen:

- `spring-boot-starter-webflux`: Para desarrollar aplicaciones web reactivas con Spring WebFlux.
- `lombok`: Para reducir el código boilerplate.
- `r2dbc-postgresql`: Para interactuar con la base de datos PostgreSQL de forma reactiva.
- `reactor-test`: Para pruebas reactivas.

## Fin del Desarrollo del Proyecto

El desarrollo de este proyecto tiene como objetivo crear una aplicación que permita a los usuarios traducir texto de un idioma a otro de manera eficiente y almacenar las traducciones realizadas en una base de datos para su posterior referencia. Además, proporciona una muestra de cómo integrar los servicios cognitivos de Azure AI en una aplicación Java utilizando Spring Boot.
<div style="display:flex; justify-content: center;">
    <img src="[imagen1.png](https://wiki.hornbill.com/images/4/46/Azure_ai_logo.png)" alt="Imagen 1" style="margin-right: 10px;">
    <img src="[imagen2.png](https://i.pinimg.com/564x/bd/e9/75/bde975558b82fd6c2cb9c8e2a15339fc.jpg)" alt="Imagen 2" style="margin-right: 10px;">
    <img src="[imagen3.png](https://digitalis.io/wp-content/uploads/2020/12/PostgreSQL600x340.jpg)" alt="Imagen 3" style="margin-right: 10px;">
</div>
