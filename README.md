# Spring_Back

## Participantes

- Alejandro Jameson
- Santiago Luna

## Descripción del Proyecto

Proyecto creado con Java Spring Boot, son 2 microservicios CRUD para Products y para Orders. Además, contiene un pequeño login para poder ingresar a la app y generar un token. Los servicios POST se deben hacer únicamente si el usuario tiene el token.

Para esto, debemos ingresar a las siguientes URLs para generar un token de usuario y asi poder crear una orden o un producto:

- Microservicio de Products: [http://localhost:8083/authenticate](http://localhost:8083/authenticate)
- Microservicio de Orders: [http://localhost:8082/authenticate](http://localhost:8082/authenticate)

Las URLs para usar los servicios son las siguientes:

- Productos: [http://localhost:8083/api/products](http://localhost:8083/api/products)
- Pedidos: [http://localhost:8082/api/orders](http://localhost:8082/api/orders)
