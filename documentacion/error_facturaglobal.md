# ERROR | Factura Global

No timbra.

## Solución

1. **Verifica campos**

En los logs de Documento Electrónico menciona algún campo que no está lleno. Por ejemplo, el check de Comercio Exterior ha presentado errores con algunos clientes que solo empiezan a quitar campos de MX+.

2. **Verifica existencia de campo DATOS de XML**

En Personalización > Listas, registros y campos > Campos de cuerpo de la transacción busca el campo con ID *custbody_fb_tp_xml_data*
Nota: al momento de timbrar, el código pone un valor en este campo oculto para que después puedan consultar el estatus del CFDI. Si no lo tiene, va a marcar error pero sí va a timbrar.

3. **Dirígete a la pestaña de *mostrar***

Llena con la siguiente información:

![alt text](https://firebasestorage.googleapis.com/v0/b/tekiio-plus-soporte.appspot.com/o/CONSULTA%20STATUS%202.png?alt=media&token=16214bf8-eef4-458d-94de-d1ef743d0f1b)

4. **Guarda el campo**

> Una vez guardado, a partir de esa fecha en adelante las facturas o pagos timbradas podrán hacer uso del botón "Consulta Estatus SAT". 
> 
> **Si quieres comprobar que el botón sirve, se debe pedir a cliente una factura nueva para timbrar y consultar el estatus del SAT.**
