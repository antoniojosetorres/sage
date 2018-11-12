# 05 OPERATIVA DEL TPV
## 051 Pedido de Venta
#### `Ventas > Pedido`
* Por defecto propone un número del contador configurado en las opciones de contadores.
* Se propone la fecha del día **`Fecha`** y la fecha de entrega **`F. Entrega`**.
* Selecciono el almacén **`Almacen`**, el vendedor **`Vendedor`** y la forma de pago **`F.Pago`**.
* Selecciono el cliente **`Código`**.
* Añado **`[Añadir]`** los artículos **`Articulo`** y sus unidades **`Unidades`**.
* Se pueden introducir observaciones **`[Observ]`** en el pedido.
* Se pueden añadir notas **`[Notas]`** previamente configuradas en las definiciones de notas.
* Haciendo click en el artículo y pulsando en **`[Foto]`**, se puede ver la imagen asociada a ese artículo.
* Puedo ver las últimas ventas del cliente **`[Ventas]`**.
* Puedo ver los últimos pedidos por cliente **`[Pedidos]`**, con los documentos **`Documentos`** de ese cliente con sus correspondientes detalles **`Detalle`**.
* Puedo ver los **`[Pedidos pendientes de servir del cliente]`**.
* En la parte inferior puedo ver el importe del pedido **`Total (€)`**, la importe base **`Base IVA`**, el porcentaje de IVA **`% IVA`**, el importe de IVA **`Importe IVA`** y el importe de recargo **`Imp. Recargo`**.

## 052 Traspaso de tickets a albaranes facturables
#### `Ventas > Terminal Punto de Venta`
* Selecciono el perfil lineal **`Completo`**.
* Añado **`[Añadir]`** los artículos **`Articulo`** y sus unidades **`Unidades`**.
* Una vez introducido el ticket, supongamos el cliente me pide que le haga una factura.
* Para no tener que borrar el ticket e introducir la factura:
  * Selecciono el documento **`Documento` FACTURA**.
  * Automáticamente se traspasa a **albarán**.
  * Pregunta si deseo cambiar el cliente. Si no cambio de cliente, pregunta si deseo entrar en la ficha de `Cliente Varios`.
  * Si no entro en la ficha, se convierte automáticamente en **factura**.
  * Para cobrar esa factura, hago click en **`[Cobrar]`**, selecciono **`Contabilizar cobro`** y hago click en **`[Facturar]`**.
  * Una vez cobrado, automáticamente pone el sello **`Facturado`**.
  * Haciendo doble click en **`Facturado`**, aparece la factura y muestra el sello **`Contabilizada`**.
  * Se ha pasado de un **ticket** a **albarán facturado**.
#### `Ventas > Traspaso de tickets a albaranes facturables`
* Se filtra por los parámetros correspondientes y se muestra un listado de los tickets que pueden traspasarse.
* Marco los tickets que quiero facturar y hago click en **`[Aceptar]`**.
* Se asignará un número de albarán **`Nº Albarán`** y un número de factura **`Nº Factura`**.
* Haciendo click en **`[Opciones]`** puedo ver el ticket **`[Ver ticket]`**, el albarán facturado **`[Ver albarán]`** o la factura contabilizada **`[Ver factura]`**.
* Nota: *Los tickets traspasados a albaranes de venta tendrán como entrega a cuenta el total cobrado del ticket. Si se genera la factura de venta automáticamente y el ticket tiene algún importe pendiente de cobrar, también se generarán las previsiones de la factura*.

## 053 Operativa de Venta
### 0531 Generación de tickets con pantalla táctil
#### `Ventas > Terminal Punto de Venta`
* Aparece la pantalla **`Reposiciones`**.
  * Propone la caja **`Caja`**, el operario **`Operario`** y la fecha actual **`Fecha`**.
  * Inserto el importe en efectivo **`Importe`** que quiero dejar en la caja.
  * Puedo ver el número de reposiciones **`Nº Reposiciones`** y el total de reposiciones del día **`Total Reposiciones`**.
* Una vez hecha la reposición se puede acceder a la pantalla del TPV llamada **`Perfil`**.
  * En el perfil **`Táctil`** aparece el documento y debajo la tabla de los artículos que se van añadiendo a la venta.
  * El perfil **`Táctil`** dispone de una matriz con celdas para cada artículo en los cuales puede aparecer el nombre o una imagen del artículo.
  * Los artículos se pueden clasificar por **`Familias`**, **`Subfamilias`**, **`Marcas`**, **`Artículos definibles`** y **`Clasificaciones`**.
  * Se pueden generar tickets **`[TICKET]`**, albaranes **`[ALBARAN]`** o facturas **`[FACTURA]`** dependiendo de los permisos del operario.
  * Propone el operario **`Operario`**, el vendedor **`Vendedor`**, el almacén **`Almacén`** y el cliente por defecto asociados a esa caja.
  * Añado una unidad de cada artículo haciendo click en su celda. Cada vez que hago click se inserta una unidad más.
  * También puedo añadir unidades desde el teclado.

### 0532 Generación de tickets con pantalla lineal
#### `Ventas > Terminal Punto de Venta`
* Por defecto se entra en el perfil **`Táctil`**.
* Cambio a perfil lineal **`[Cambio de perfil]`**.
  * Propone el documento **`Documento` TICKET** pero se pueden generar albaranes y facturas.
  * Hago click en **`Número`** para introducir un nuevo ticket.
  * Propone el operario **`Operario`**, el vendedor **`Vendedor`** y el almacén **`Almacén`**. Asimismo propone la tarifa **`Tarifa`**, la forma de pago **`F. Pago`** y el código de cliente **`Código`**.
  * Añado **`[Añadir]`** los artículos **`Articulo`** y sus unidades **`Unidades`**.
  * Selecciono el artículo haciendo click en la **`[lupa]`**.

### 0533 Cobro del documento
#### `Ventas > Terminal Punto de Venta`
* Genero un ticket en la pantalla táctil.
  * Para cobrar el ticket, pulso en el botón correspondiente **`[Muestra la pantalla para cobrar ticket o imprime el documento]`**.
  * Aparece la pantalla **`Cobro de tickets`**.
    * Propone el operario **`Operario`**, la fecha actual **`Fecha`** y el importe que hay que cobrar (con IVA incluido) **`Importe`**.
    * Se introduce el importe que entrega el cliente **`Entrega`** y se muestra el cambio correspondiente **`Cambio`**.
    * Se puede introducir un concepto **`Concepto`**.
    * Selecciono la forma de cobro **`Forma de cobro`**.
* Cambio a perfil lineal **`[Cambio de perfil]`**.
* Genero un ticket en la pantalla lineal.
  * Para cobrar el ticket, pulso en el botón correspondiente **`[Muestra la pantalla para cobrar ticket o imprime el documento]`**.
  * Aparece la pantalla **`Cobro de tickets`**.
  * Procedo como con la pantalla táctil.

## 054 Operativas más habituales
### 0541 Descuentos lineales y descuento total
#### `Ventas > Terminal Punto de Venta`
* Genero un ticket en la pantalla lineal.
* Hay dos tipos de descuento: *descuento lineal* y *descuento total*.
  * Los descuentos lineales son sólo para tickets. Un descuento lineal es un descuento aplicado a la línea seleccionada.
  * Accedo a los descuentos lineales **`[Opciones > Descuentos lineales]`**.
    * Propone el importe de la línea seleccionada **`Importe`**.
    * Escribo el descuento **`Descuento`** que puede ser por cantidad **`Descuento por cantidad`** o por porcentaje **`Descuento por %`**.
    * El importe final aparece en **`Total línea`**.
    * La columna **`Dto 1`** solo muestra el descuento por porcentaje. Si selecciono **`Descuento por cantidad`** el programa calcula el porcentaje correspondiente.
  * Un descuento total es un descuento aplicado a todo el ticket.
  * Accedo a los descuentos totales **`[Opciones > Descuentos totales]`**.
    * Procedo como con el *descuento lineal*.
    * La columna **`Dto 1`** se recalcula con el porcentaje coorecto.

### 0542 Aparcar ticket
#### `Ventas > Terminal Punto de Venta`
* *Aparcar un ticket* es cuando se está atendiendo a varios clientes a la vez, se tiene un ticket a medio hacer y se quiere realizar el ticket de otro cliente. Es decir, estoy cobrando a un cliente unos artículos y ese cliente se olvida de coger otro artículo. Para no tener que borrar el ticket entonces lo aparco.
* Aparcar significa que lo que está en pantalla lo guarda y deja lista la pantalla para otro cliente.
* Para aparcar el ticket actual, hago click en **`[Aparcar ticket]`**.
* Para desaparcar el ticket actual, hago click en **`[Tickets aparacdos]`**.
  * Propone el operario **`Operario`** y muestra una lista con todos los tickets aparcados.
  * Al seleccionar el ticket aparcado, este se muestra con el sello `Aparcado`.
  * Procedo al cobro como con cualquier otro ticket.

### 0543 Ticket a crédito
#### `Ventas > Terminal Punto de Venta`
* Tengo un ticket que no he cobrado en su totalidad. Puedo dejar el *ticket a crédito* y recuperarlo posteriormente para su cobro.
* Realizo un ticket y al hacer click en **`[Salir]`** si no lo he cobrado, se guarda como un *ticket a crédito*.
* Para cobrar el ticket a crédito, procedo como con cualquier otro ticket.

### 0544 Entregas a cuenta de facturas o albranes
#### `Ventas > Terminal Punto de Venta`
* Genero un ticket desde la pantalla lineal.
* Lo paso a albarán **`Documento` ALBARAN**.
  * Si el cliente es *Cliente Varios*, pregunta si se desea cambiar el cliente. Si contesto que **`[No]`**, pregunta si deseo entrar en la ficha de Clientes Varios. Y si contesto que **`[No]`**, se genera el albarán correspondiente.
* Si quiero cobrar el albarán, el programa muestra la pantalla **`Impresión albarán`** y **no** deja cobrarlo.
* Para cobrarlo, entro en **`[Opciones > Entregas a cuenta]`**.
  * Inserto el importe que me entrega el cliente **`Entrega`**.
  * Si no se cobra en su totalidad, la siguiente vez que lo seleccione se mostrará el importe que queda pendiente por cobrar.
  * Si el albarán está totalmente cobrado, **no** se pueden realizar *entregas a cuenta*. 

### 0545 Emisión y gestión de vales
#### `Ventas > Terminal Punto de Venta`
* 
