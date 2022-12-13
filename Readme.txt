ejecutar:  npm install  
ejecutar:  nodemon src/index.js

--> sale Servidor arriba y escuchando puerto 8080!!

Ejemplos: 

Get products --> localhost:8080/api/products
Get product por id 2  -->  localhost:8080/api/products/2
Get product por limit --> localhost:8080/api/products?limit=3
Delete product id 7 --> localhost:8080/api/products/7
Update product id 2 --> localhost:8080/api/products/2    
     con product en el body: 
       {
    "id": "",
    "title": "PRODUCTO 66",
    "description": "producto 66",
    "price": 1100,
    "thumbnail": "http: ....66 ",
    "code": 660,
    "stock": 6000
  }

Get cart por id 15    --> localhost:8080/api/carts/15

Insert cart --> localhost:8080/api/carts
con body: 
 {
    "id": null,
    "products": [
        {
            "id": 1,
            "quantity": 4
        },
        {
            "id": 6,
            "quantity": 4
        }
    ]
}

Agregar producto 5 al carrito 15 --> localhost:8080/api/carts/15/product/5

