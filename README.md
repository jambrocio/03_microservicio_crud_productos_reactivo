# Tipos de Consultas

## Mostrar todos los productos
### Method GET
http://localhost:8090/productos

![Postman]([Link URL](https://github.com/jambrocio/03_microservicio_crud_productos_reactivo/blob/main/Configurar%20Postman%20para%20peticiones%20reactivas.png))  

## Buscar por categoria
### Method GET
http://localhost:8090/productos/Limpieza

## Buscar por codigo de producto
### Method GET
http://localhost:8090/producto?cod=101

## Alta de producto
### Method POST
http://localhost:8088/alta

```
{
    "codProducto": 230,
    "nombre": "zanahoria",
    "categoria": "Alimentación",
    "precioUnitario": 2.5,
    "stock": 50
}
```

## Eliminar producto
### Method DEL
http://localhost:8090/eliminar?cod=120

## Actualizar producto
### Method PUT
http://localhost:8088/actualizar?cod=101&precio=5.5
