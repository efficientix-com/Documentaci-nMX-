# Pago de cliente

## Error: sumas no coinciden en BaseDR y BaseP

Detalles del error:

> Debe ser igual a la suma de los importes de los atributos BaseDR registrados en los documentos relacionados donde el impuesto del documento relacionado sea igual al atributo ImpuestoP de este elemento y la TasaOCuotaDR del documento relacionado sea igual al atributo TasaOCuotaP de este elemento.: El campo BaseP que corresponde a Traslado, no es igual a la suma de los importes de las bases registrados en los documentos relacionados donde el impuesto del documento relacionado sea igual al campo ImpuestoP de este elemento y la TasaOCuotaDR del documento relacionado sea igual al campo TasaOCuotaP de este elemento. /n [] /n

### Solución

1. **Realiza operaciones**

Abre el documento XML y empieza a sumar lo de *BaseDR*. Si tu suma no coincide con el monto en *BaseP* 
