# Tipos de Consultas

## Mostrar todos los productos

http://localhost:8090/productos

## Buscar por categoria

http://localhost:8090/productos/Limpieza

## Buscar por codigo de producto

http://localhost:8090/producto?cod=101

## Alta de producto

http://localhost:8088/alta

{
    "codProducto": 230,
    "nombre": "zanahoria",
    "categoria": "Alimentación",
    "precioUnitario": 2.5,
    "stock": 50
}
