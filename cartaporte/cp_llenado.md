# Campos en Ejecución de Pedido

Aquí encontrarás información para el llenado de datos en ***Ejecución de Pedido***

## 1. Información básica 
- Los campos ubicados en  **MX+ > Carta Porte** deben estar llenos.
![alt text](https://firebasestorage.googleapis.com/v0/b/mx-plus-docs.appspot.com/o/llenado_2_cp4.png?alt=media&token=21b4b46f-8c12-45ad-b528-6f30ac16485b)
-***Campos Obligatorios:***
    * **CP - Distancia Recorrida**: Indica una aproximación de la distancia en KM del punto de partida al punto destino.
    * **CP - Seguros**: Campo de selección para el seguro. Los seguros se dan de alta en el Menú **MX+ > Carta Porte > Seguros**
    * **CP - Unidad Peso**: Campo de selección de la unidad de peso del contenedor de alto nivel. *Ejemplo*:
![alt text](https://firebasestorage.googleapis.com/v0/b/mx-plus-docs.appspot.com/o/Unidad%20de%20Peso%20Alto%20Nivel.png?alt=media&token=f8220235-5ce5-4bd5-9eb7-f9660f52a087)
    * **CP - Vehículo**:Campo de selección de vehículo. Los Vehículos se dan de alta en el Menú **MX+ > Carta Porte > Vehículos**
    * **CP - Chofer**: Campo de selección de chofer. Los choferes se dan de alta en el Menú  **MX+ > Carta Porte > Choferes**.
    * **CP - Hora de Llegada**: Campo para especificar la hora aproximada de llegada, tiene formato 24Hrs.
    * **CP - Hora de Salida**: Campo para especificar la hora aproximada de salida, tiene formato 24Hrs.

- ***Campos Opcionales:***
    * **CP - Remolque Principal**: Campo de selección de remolque principal. Los remolques se dan de alta en el menú **MX+ > Carta Porte > Remolques**

    * **CP - Remolque Secundario**: Campo de selección de remolque secundario. Los remolques se dan de alta en el menú **MX+ > Carta Porte > Remolques**
    * **CP - Transporte Internacional**: Campo para especificar si es transporte internacional.
    * **CP - Régimen Aduanero**: Campo para especificar el régimen aduanero. **Este se debe de llenar en caso de que el transporte sea internacional**.


## 2. Verifica información del cliente/almacen/ubicación

Antes de dar click en el botón "Carta Porte" corrobora que la información de dirección sea la correcta. Ve al apartado de **Campos de Cliente/Almacen** en esta guía para más información. 

Si es necesario editar algún dato de la dirección de cliente/ubicación, es necesario que una vez que se haya realizado el cambio en el cliente/ubicación, hay que editar y guardar la ejecución de pedido.

## 3. Genera Carta Porte

Una vez validada la información, puedes proceder a generar la Carta Porte con el botón "Carta Porte".
![alt text](https://firebasestorage.googleapis.com/v0/b/mx-plus-docs.appspot.com/o/LlenadoCp7.png?alt=media&token=cb0dea43-f5d0-4333-b4c6-63100e7889eb)

## 4. Información de Timbrado

Una vez que la carta porte ha sido generada con éxito, se puede consultar la información de timbrado en los siguientes apartados:
- **UUID y Fecha de timbrado**: Este se encuentra en subpestaña ***Información de CFDI***:
![alt text](https://firebasestorage.googleapis.com/v0/b/mx-plus-docs.appspot.com/o/llenadocp9.png?alt=media&token=32720061-5a1d-4932-80a9-4a4b3b00b3f1)
- **PDF de Carta Porte**: se encuentra en ***Documento Electrónico***. Para la generación del PDF es necesario tener llenos los campos marcados en color rosa y dar click en el botón **"Ver Carta Porte"**, este botón generará el PDF a partir de la información del XML Certificado.
![alt text](https://firebasestorage.googleapis.com/v0/b/mx-plus-docs.appspot.com/o/llenadocp10.png?alt=media&token=db0abfed-f2b6-4464-ad4b-799eefc272e1)
- **XML Certificado**: se encuentra en **MX+ > Datos de Timbrado**.
![alt text](https://firebasestorage.googleapis.com/v0/b/mx-plus-docs.appspot.com/o/llenadocp11.png?alt=media&token=0e021f72-3e3c-44d0-afd6-79bb0419f88c)

## BONUS: ¿Cómo sé que información se mandó al SAT para timbrado?

Se puede consultar la información que se manda a timbrar en el campo ***MX+ JSON Generado***. Al abrir el documento adjunto en el campo podrás corroborar todos los datos necesarios para generar una carta porte. 

Cuando ocurra un error de timbrado por falta de información, este campo se llenará y **podrás consultar la información faltante** además de los errores que despliega en el mensaje de error. Es necesario refrescar la página después de que el error fue desplegado

