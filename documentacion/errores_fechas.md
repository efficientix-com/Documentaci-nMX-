# ERROR | Fecha Pago XML

Descripción del error:

> La fecha de pago en el XML timbrado no coincide con la fecha de pago/depósito en Netsuite

Ejemplo:

![alt text](https://firebasestorage.googleapis.com/v0/b/tekiio-plus-soporte.appspot.com/o/ERROR%20FECHA%20EJEMPLO.png?alt=media&token=59b1b2f1-cdf3-4886-b842-1cff6172b8f6)

## Solución

1. **Verifica Fecha en Preferencias generales**

Checa en **Configuración > Empresa > Preferencias Generales** que el campo de *Formato de Fecha* esté en formato *D/M/YYYY*

![alt text](https://firebasestorage.googleapis.com/v0/b/tekiio-plus-soporte.appspot.com/o/ERROR%20FECHA%201.png?alt=media&token=871237f4-6c59-4483-9641-b737339381f8)

2. **Verifica Preferencias de Usuario**

Checa en **Establecer preferencias**:

![alt text](https://firebasestorage.googleapis.com/v0/b/tekiio-plus-soporte.appspot.com/o/ERROR%20FECHA%202.png?alt=media&token=898a7b8e-2c83-4cad-a55a-6ac621a71b58)

En la sección de *Formatos* configura el campo de *Formato de Fecha* a **DD/MM/YYYY** como se muestra en la siguiente imagen:

![alt text](https://firebasestorage.googleapis.com/v0/b/tekiio-plus-soporte.appspot.com/o/ERROR%20FECHA%203.jpeg?alt=media&token=657442b5-9875-4328-92eb-4ac7c402051d)

3. **Vuelve a timbrar**

Regresa a tu transacción timbrada, se tendrá que cancelar y volver a timbrar ya que va a cambiar el formato de las fechas del pago/depósito. Una vez timbrada, puedes verificar en el XML generado de que las fechas coinciden con la transacción de Netsuite. 

Ejemplo de resultado de PDF generado:
![alt text](https://firebasestorage.googleapis.com/v0/b/tekiio-plus-soporte.appspot.com/o/ERROR%20FECHA%204.jpeg?alt=media&token=63a33e8e-288a-497b-8b01-ceaaff4910dd)

resultado de XML de documento electrónico:

![alt text](https://firebasestorage.googleapis.com/v0/b/tekiio-plus-soporte.appspot.com/o/ERROR%20FECHA%205.jpeg?alt=media&token=189cbec0-0562-40c0-b426-d8c9cb8cb848)

## Consideraciones

Esta solución aplica a lo siguiente:

1. Cliente se dio cuenta de que su transacción en fecha no coincide con la timbrada en Netsuite

2. Timbrado marca error de fecha de no poder timbrar pasando las 72 hrs, no siempre aplica esta solución porque hay ocasiones en que el cliente tiene configurado su producto de configuración en que no permita timbrar pasando las 72 hrs y por ende sale ese error en timbrado.




