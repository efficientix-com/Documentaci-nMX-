# Guía de Inicio

Aquí podrás consultar los primeros pasos y configuraciones necesarias para la generación de tu DIOT

## ¿Qué es la DIOT?

Es la Declaración informativa de operaciones con terceros. Informa las operaciones con proveedores relacionados con el Impuesto al Valor Agregado (IVA).

## Requerimientos

Para tener la DIOT instalada en su instancia es necesario que sea ***SuiteTax***

### 1. Configuraciones de Proveedor

- Campo **obligatorio**: tipo de tercero
    Este se configura en ***Tekiio+ > DIOT > Tipo de Tercero*** como se muestra a continuación
    ![alt text](https://firebasestorage.googleapis.com/v0/b/tekiio-plus-soporte.appspot.com/o/DIOT%201.png?alt=media&token=6c781d16-e774-4b26-9647-987a72521ed7)
- En caso de ser **proveedor Nacional** es necesario llenar el campo *RFC*
- En caso de ser **proveedor Extranjero** es necesario llenar los campos de *Nacionalidad*, *Nombre del Extranjero*, *País de Residencia*, *Tipo de Operación* y *NUMREGIDTRIB*

### 2. Configuraciones de Factura
- Campo obligatorio: Tipo de operación
- Consideración: tener configurados los códigos de impuestos correctamente (Configuración > Impuesto > Códigos de Impuesto). 

### 3. Configuraciones de Códigos de Impuesto

- Campo **obligatorio**: DIOT - Tipo de Impuesto
    Si no hay detalle de impuesto, este no se contabiliza y no estará disponible para su DIOT
![alt text](https://firebasestorage.googleapis.com/v0/b/tekiio-plus-soporte.appspot.com/o/DIOT%202.png?alt=media&token=bb143883-176b-42fe-b883-6b02ec325c69)
