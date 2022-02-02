# Backend Ecommerce Node

## Variables de entorno

.env.EXAMPLE

## Endpoints:

## Auth:

POST /api/auth/login  
GET  /api/auth/logout  
POST /api/auth/signup   
GET  /api/auth/islogged

## Products:

GET /api/products/list/                                                         
GET/api/products/list/id 

Rutas protegdas: USER login para acceder a estas rutas

POST /api/products/add/ 
PUT  /api/products/update/id 
DELETE  /api/products/delete/id |          

## Cart:

Rutas protegdas: USER login para acceder a estas rutas

GET /api/cart/list                                                                                              
GET /api/cart/list/id 
POST /api/cart/add/id   
DELETE /api/cart/delete/id 

## Orders:

Rutas protegdas: USER login para acceder a estas rutas

GET /api/orders/getpurchases 
POST /api/orders/purchase  
