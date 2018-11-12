# 05 Operativa del TPV
## 051 Pedido de Venta
### `Ventas > Pedido`
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
### `Ventas > Terminal Punto de Venta`
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
### `Ventas > Traspaso de tickets a albaranes facturables`
* Se filtra por los parámetros correspondientes y se muestra un listado de los tickets que pueden traspasarse.
* Marco los tickets que quiero facturar y hago click en **`[Aceptar]`**.
* Se asignará un número de albarán **`Nº Albarán`** y un número de factura **`Nº Factura`**.
* Haciendo click en **`[Opciones]`** puedo ver el ticket **`[Ver ticket]`**, el albarán facturado **`[Ver albarán]`** o la factura contabilizada **`[Ver factura]`**.
* Nota: *Los tickets traspasados a albaranes de venta tendrán como entrega a cuenta el total cobrado del ticket. Si se genera la factura de venta automáticamente y el ticket tiene algún importe pendiente de cobrar, también se generarán las previsiones de la factura*.

## 0531 Generación de tickets con pantalla táctil
### `Ventas > Terminal Punto de Venta`
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

## 0532 Generación de tickets con pantalla lineal
### `Ventas > Terminal Punto de Venta`
* Por defecto se entra en el perfil **`Táctil`**.
* Cambio a perfil lineal **`[Cambio de perfil]`**.
  * Propone el documento **`Documento` TICKET** pero se pueden generar albaranes y facturas.
  * Hago click en **`Número`** para introducir un nuevo ticket.
  * Propone el operario **`Operario`**, el vendedor **`Vendedor`** y el almacén **`Almacén`**. Asimismo propone la tarifa **`Tarifa`**, la forma de pago **`F. Pago`** y el código de cliente **`Código`**.
  * Añado **`[Añadir]`** los artículos **`Articulo`** y sus unidades **`Unidades`**.
  * Selecciono el artículo haciendo click en la **`[lupa]`**.

## 0533 Cobro del documento
### `Ventas > Terminal Punto de Venta`
* Genero un ticket en la pantalla táctil.
* Para cobrar el ticket, pulso en el botón correspondiente **`[Muestra la pantalla para cobrar ticket o imprime el documento]`**.
* Aparece la pantalla **`Cobro de tickets`**.
  * Propone el operario **`Operario`**, la fecha actual **`Fecha`** y el importe que hay que cobrar (con IVA incluido) **`Importe`**.
  * Se introduce el importe que entrega el cliente **`Entrega`** y se muestra el cambio correspondiente **`Cambio`**.
  * Se puede introducir un concepto **`Concepto`**.
  * Selecciono la forma de cobro **`Forma de cobro`**.
* Genero un ticket en la pantalla lineal.

