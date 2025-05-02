# 🛒 Spring Market

Proyecto backend de una tienda desarrollado con **Spring Boot**. Este sistema gestiona productos, categorías, clientes y compras, ofreciendo una API REST para operaciones CRUD.

## Estructura del Proyecto
    
```text
spring-market/
├── src/
│   ├── main/
│   │   ├── groovy/com/spring_market/
│   │   │   ├── domain/               # Clases del modelo de dominio
│   │   │   ├── persistence/          # Repositorios y entidades JPA
│   │   │   ├── web/controller/       # Controladores REST
│   │   └── resources/                # Archivos de configuración
│   └── test/                         # Pruebas (si aplica)
├── build.gradle / pom.xml            # Dependencias y configuración del proyecto
```


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

## Endpoints 
- GET /products/all - Obtener todos los productos

- POST /products/save - Crear un nuevo producto

- GET /products/{id} - Obtener un producto por ID

- DELETE /products/delete/{id} - Eliminar producto

