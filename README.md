# 🛒 Spring Market

Proyecto backend de una tienda desarrollado con **Spring Boot**. Este sistema gestiona productos, categorías, clientes y compras, ofreciendo una API REST para operaciones CRUD.

## Estructura del Proyecto
spring-market/
├── src/
│ ├── main/
│ │ ├── groovy/com/spring_market/
│ │ │ ├── domain/ **_Clases del modelo de dominio_**
│ │ │ ├── persistence/ **_Repositorios y entidades JPA_**
│ │ │ ├── web/controller/ **_Controladores REST_**
│ │ └── resources/ **_Archivos de configuración_**
│ └── test/ 
├── build.gradle / pom.xml **_Dependencias y configuración del proyecto_**


## Requisitos

- Java 17+
- Gradle o Maven
- Base de datos MySQL o compatible con JPA
- Spring Boot

## Instalación y Ejecución

1. Clona el repositorio:
   ```bash
   git clone https://github.com/Amerikg/API-Market.git
   cd spring-market

2. Configura la conexión a la base de datos en src/main/resources/application.properties:

    ```bash
    spring.datasource.url=jdbc:mysql://localhost:3306/spring_market
    spring.datasource.username=usuario
    spring.datasource.password=contraseña

## Endpoints de ejemplo
- GET /products/all - Obtener todos los productos

- POST /products/save - Crear un nuevo producto

- GET /products/{id} - Obtener un producto por ID

- DELETE /products/delete/{id} - Eliminar producto

