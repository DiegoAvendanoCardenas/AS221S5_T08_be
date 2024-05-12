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
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a8/Microsoft_Azure_Logo.svg/1200px-Microsoft_Azure_Logo.svg.png" alt="Azure Logo" style="width: 100px; margin-right: 20px;">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/44/Spring_Framework_Logo_2018.svg/1200px-Spring_Framework_Logo_2018.svg.png" alt="Spring Boot Logo" style="width: 100px; margin-right: 20px;">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/29/Postgresql_elephant.svg/1200px-Postgresql_elephant.svg.png" alt="PostgreSQL Logo" style="width: 100px;">
</div>
