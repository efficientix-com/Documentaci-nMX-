# Campos de Cliente/Almacén

Aquí encontrarás información para el llenado de **datos de dirección** a usar en la ***Ejecución de Pedido***

En una ejecución de pedido que provenga de una ***Orden de Traslado*** tomará la dirección del almacén de origen y destino.

En una ejecución de pedido que provenga de una ***Orden de Venta*** tomará la información de la dirección de cliente como destino y el almacén como origen.

Los campos de dirección son los mismos, por lo que no es relevante si una ejecución de pedido fue creada desde una orden de venta u orden de traslado.
## Consideraciones
- La dirección a tomar del cliente/almacén será la que tenga marcado como "Dirección de Envío" como se muestra a continuación:
![alt text](https://firebasestorage.googleapis.com/v0/b/mx-plus-docs.appspot.com/o/Direccion%20CP.png?alt=media&token=6df49b46-04ff-4f7d-9706-51d0f8ba8ccc)

## 1. Información básica 
- Los campos ubicados en **Dirección** deben estar llenos.

![alt text](https://firebasestorage.googleapis.com/v0/b/mx-plus-docs.appspot.com/o/llenadocp4.png?alt=media&token=7c08ce8a-4d30-497a-8ab7-1614b44fcf00)
![alt text](https://firebasestorage.googleapis.com/v0/b/mx-plus-docs.appspot.com/o/llenadocp5.png?alt=media&token=63d3d2df-a4a5-4c14-bc62-ebd9d1c01d36)

Los campos marcados deben estar llenos tanto en la **dirección de origen como de destino**, es decir la dirección de almacen (origen) debe tener estos campos llenos.

## 2. Caso: El Receptor es Extranjero (RFC: XEXX010101000)
Si el Receptor es extranjero y su **RFC es XEXX010101000**, los siguientes campos marcados deben estar llenos:

![alt text](https://firebasestorage.googleapis.com/v0/b/mx-plus-docs.appspot.com/o/llenado_2_cp5.png?alt=media&token=5906976b-94fc-4c49-a9fd-e4d2fcd5887b)

En el caso de dirección solo se requiere llenar el código postal, país y estado.

## ¿Cómo edito la dirección de una ubicación/almacén?
En modo edición de alguna Ubicación hay que dar click en "editar" a un lado del campo de dirección.
![alt text](https://firebasestorage.googleapis.com/v0/b/mx-plus-docs.appspot.com/o/Direccion%20de%20Ubicaci%C3%B3n.png?alt=media&token=a119a661-c766-4164-ad44-937cd809df53)

En la ventana que se despliega están los campos que se mencionaron previamente que requieren llenarse.