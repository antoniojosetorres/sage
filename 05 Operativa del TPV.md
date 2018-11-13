# 5 OPERATIVA DEL TPV
## 5.1 Pedido de Venta
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
---
## 5.2 Traspaso de tickets a albaranes facturables
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
---
## 5.3 Operativa de Venta
### 5.3.1 Generación de tickets con pantalla táctil
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

### 5.3.2 Generación de tickets con pantalla lineal
#### `Ventas > Terminal Punto de Venta`
* Por defecto se entra en el perfil **`Táctil`**.
* Cambio a perfil lineal **`[Cambio de perfil]`**.
  * Propone el documento **`Documento` TICKET** pero se pueden generar albaranes y facturas.
  * Hago click en **`Número`** para introducir un nuevo ticket.
  * Propone el operario **`Operario`**, el vendedor **`Vendedor`** y el almacén **`Almacén`**. Asimismo propone la tarifa **`Tarifa`**, la forma de pago **`F. Pago`** y el código de cliente **`Código`**.
  * Añado **`[Añadir]`** los artículos **`Articulo`** y sus unidades **`Unidades`**.
  * Selecciono el artículo haciendo click en la **`[lupa]`**.

### 5.3.3 Cobro del documento
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
---
## 5.4 Operativas más habituales
### 5.4.1 Descuentos lineales y descuento total
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

### 5.4.2 Aparcar ticket
#### `Ventas > Terminal Punto de Venta`
* *Aparcar un ticket* es cuando se está atendiendo a varios clientes a la vez, se tiene un ticket a medio hacer y se quiere realizar el ticket de otro cliente. Es decir, estoy cobrando a un cliente unos artículos y ese cliente se olvida de coger otro artículo. Para no tener que borrar el ticket entonces lo aparco.
* Aparcar significa que lo que está en pantalla lo guarda y deja lista la pantalla para otro cliente.
* Para aparcar el ticket actual, hago click en **`[Aparcar ticket]`**.
* Para desaparcar el ticket actual, hago click en **`[Tickets aparacdos]`**.
  * Propone el operario **`Operario`** y muestra una lista con todos los tickets aparcados.
  * Al seleccionar el ticket aparcado, este se muestra con el sello `Aparcado`.
  * Procedo al cobro como con cualquier otro ticket.

### 5.4.3 Ticket a crédito
#### `Ventas > Terminal Punto de Venta`
* Tengo un ticket que no he cobrado en su totalidad. Puedo dejar el *ticket a crédito* y recuperarlo posteriormente para su cobro.
* Realizo un ticket y al hacer click en **`[Salir]`** si no lo he cobrado, se guarda como un *ticket a crédito*.
* Procedo al cobro como con cualquier otro ticket.

### 5.4.4 Entregas a cuenta de facturas o albranes
#### `Ventas > Terminal Punto de Venta`
* Genero un ticket desde la pantalla lineal.
* Lo paso a albarán **`Documento` ALBARAN**.
  * Si el cliente es *Cliente Varios*, pregunta si se desea cambiar el cliente. Si contesto que **`[No]`**, pregunta si deseo entrar en la ficha de Clientes Varios. Y si contesto que **`[No]`**, se genera el albarán correspondiente.
* Si quiero cobrar el albarán, el programa muestra la pantalla **`Impresión albarán`** y **no** deja cobrarlo.
* Para cobrarlo, entro en **`[Opciones > Entregas a cuenta]`**.
  * Inserto el importe que me entrega el cliente **`Entrega`**.
  * Si no se cobra en su totalidad, la siguiente vez que lo seleccione se mostrará el importe que queda pendiente por cobrar.
  * Si el albarán está totalmente cobrado, **no** se pueden realizar *entregas a cuenta*. 

### 5.4.5 Emisión y gestión de vales
#### `Ventas > Terminal Punto de Venta`
* Genero un ticket y lo cobro.
* Quiero hacer una devolución de este ticket.
  * Compruebo las últimas ventas de un cliente **`[Ultimas ventas del cliente]`**.
  * Selecciono el ticket correspondiente, hago click en **`[Devolución]`** y, a continuación, hago click en **`Cobrar`**.
  * Aparece la pantalla **`Devoluciones`** preguntando si deseo efectuar la devolución en efectivo **`[Efectivo]`** o realizar un vale **`[Vale]`**. Hago click en **`[Vale]`**.
    * Aparece la pantalla **`Vales`**.
    * Propone el ticket **`Ticket`**, el número de veces que se ha hecho un vale para ese ticket **`Orden`**, la caducidad del vale **`Caducidad`**, el importe **`Importe`** y la descripción **`Descripción`**.
    * El vale puede o no imprimirse.
* Genero otro ticket y lo cobro mediante un vale.
* Elijo la opcíon **`Forma de pago` Vales** y aparece la pantalla **`Entrada de vales`**.
  * Pulso en el botón **`Vales Pendientes`** para consultar cuál es el ticket **`Ticket`** que quiero utilizar.
  * Una vez introducido, aparece el orden **`Orden`** y pulso en **`[Aceptar]`**.
  * Se puede hacer un vale por la diferencia. Si no se escoge se realizará un retiro de caja por la diferencia. Si se escoge se hará el vale correspondiente.
#### `Ventas > Gestión de vales`
* Selecciono un vale y hago click en el botón **`[Ver]`**.
  * Muestra el ejercicio **`Ejercicio`**, la serie **`Serie`**, el ticket al que corresponde **`Ticket`** y toda la información referente al vale: la fecha en que se emitió **`Fecha`**, la caducidad **`Caducidad`**, el importe **`Importe`**, el operario **`Operario`** y la descripción **`Descripción`**.

### 5.4.6 Gestión de reservas
#### `Ventas > Terminal Punto de Venta`
* Genero un ticket en la pantalla lineal.
* Es posible marcar un ticket o albarán como *reservado* para identificar que el cliente vendrá posteriormente a recoger la mercancía.
* Cuando se reserva un ticket aparece con un sello identificativo.
* Si el cliente no recoge la mercancía el mismo día, es conveniente convertir el ticket en albarán para poder realizar el arqueo de caja.
* El cliente antes de cobrar el ticket me pide que se lo guarde y que más tarde recogerá la mercancía. Además, el stock ya se ha restado del almacén.
  ### 5.4.6.1 Convertir a albarán reservado
  * Para convertir el ticket en albarán reservado, hago click en **`[Opciones > Convertir en albarán reservado]`**.
  * Si el cliente es *Cliente Varios*, pregunta si se desea cambiar el cliente. Si contesto que **`[No]`**, pregunta si deseo entrar en la ficha de Clientes Varios. Y si contesto que **`[Sí]`**, muestra la panatalla de **`Entrada del cliente - Ventas al contado`**.
  * En esta pantalla puedo introducir los datos del cliente: el nombre **`Nombre cliente`** y el teléfono **`Teléfono`**.
  * De esta manera, se obtiene un albarán con el sello **`Reservado`** y ya se puede realizar un cierre de caja o un arqueo.
  * Para cobrar ese albarán, hago click en **`[Opciones > Entregas a cuenta]`** y cuando lo haya cobrado en su totalidad, anulo la reserva **`[Opciones > Anular reserva]`**.
  ### 5.4.6.2 Reservar
  * Se puede reservar un ticket si el cliente va a recoger la mercancía en el mismo día, antes de cerrar la caja.
  * Para reservar un ticket, hago click en **`[Opciones > Reservar ticket]`**.
  * El ticket aparece con un sello **`Reservado`**.
  * El cliente puede pagar todo o una parte del ticket.
  * Si no cobro la totalidad del ticket, aparece una pantalla que me advierte preguntando si deseo convertir el ticket en *Entrega a cuenta*.
  * Al terminar el cobro, me pregunta si estoy seguro de dejar el *ticket a crédito*. Si contesto que **`[Sí]`**, lo reserva.
  * Cuando el cliente recoge la mercancía y paga la parte restante del ticket, el programa me pregunta si deseo quitar la reserva del ticket.
  ### 5.4.6.3 Entregas lineales y totales
  * *Entregar una línea* es cuando el cliente solo se lleva una parte del ticket o albarán reservado.
  * Para entregar una línea, hago click en **`[Opciones > Entregar línea]`**.
  * Si no hay entregas a cuenta en la reserva, no se puede entregar ningún artículo.
  
### 5.4.7 Gestión de entregas de tickets
#### `Ventas > Gestión entregas de tickets`
* Muestra la pantalla **`Gestión de entregas de tickets`** que permite la gestión de varios tickets del mismo cliente.
  * Se puede filtrar por fecha **`Fecha`**, por operario **`Operario`** y por forma de cobro **`Forma cobro`**.
  * Al introducir el importe entregado **`Entrega`** y dar a **`[Intro]`**, muestra todos los tickets pendientes del cliente por orden cronológico y se marcarán aquellos tickets cuyo importe se cubran total o parcialmente con el importe entregado.
  * Selecciono la forma de cobro **`Forma cobro`** y hago click en el botón **`[Cobrar tickets]`**.
  
### 5.4.8 Operaciones de caja
#### `Ventas > Terminal Punto de Venta`
* Cambio a perfil lineal **`[Cambio de perfil]`**.
* Cobros varios **`[Q-Cobros]`**: permite entrar un importe en la caja, en cualquier forma de cobro, que no está relacionado con una venta.
  * Propone el operario **`Operario`** y la fecha **`Fecha`**.
  * Puedo introducir la entrega **`Entrega`** y el concepto **`Concepto`**.
  * Internamente se contabiliza a través de una cuenta puente **`Cuenta puente`** definida en el mantenimiento de cajas.
* Pagos varios **`[H-Pagos]`**: permite sacar un importe de la caja, en cualquier forma de pago, que que no está relacionado con una compra.
  * Procedo como con *Cobros varios*.  
* Reposición de caja **`[S-Reposición]`**: permite ingresar el importe con el que se abre la caja cada día.
  * Pueden hacerse tantas reposiciones de caja como sean necesarias.
  * Propone la caja **`Caja`**, el operario **`Operario`** y la fecha actual **`Fecha`**.
  * Puedo introducir el importe de reposición **`Importe`** y muestra el número de reposiciones **`Nº Reposiciones`** y el importe total en reposiciones **`Total Reposiciones`**.
  * Para comprobar las reposiciones del día, hago click en el botón **`[Reposiciones del día]`**.
* Retiros de caja **`[M-Retiros]`**: permite retirar un importe en efectivo de la caja.
  * Propone la caja **`Caja`**, el operario **`Operario`** y la fecha actual **`Fecha`**.
  * Puedo introducir el concepto de retirada **`Concepto`**.
  * Procedo como con *Reposición de caja*.
  * Internamente se contabiliza a través de una cuenta puente definida en el mantenimiento de cajas.
* Cobros de facturas **`[T-Cobros Fra]`**: permite cobrar una factura o documento a crédito.
  * Abre la pantalla **`Previsiones de cobro`**.
  * Permite filtrar por cliente **`Cliente inicial`**, **`Cliente final`**; por banco **`Banco inicial`**, **`Banco final`** y por fecha **`Desde`**, **`Hasta`**. Luego hago click en el botón **`[Refrescar]`**.
  * Permite buscar por factura **`Buscar factura`** y por importe **`Buscar importe`**.
  * Una vez seleccionada la factura, se abre la pantalla **`Cobro de previsiones`** y se cobra la factura con el botón **`[Cobrar]`**.
* Pagos de facturas **`[Y-Pagos Fra]`**: permite pagar una factura o documento a crédito.
  * Abre la pantalla **`Previsiones de pago`**.
  * Permite filtrar por proveedor **`Proveedor inicial`**, **`Proveedor final`**; por banco **`Banco inicial`**, **`Banco final`** y por fecha **`Desde`**, **`Hasta`**. Luego hago click en el botón **`[Refrescar]`**.
  * Una vez seleccionada la factura, se abre la pantalla **`Petición de datos`** y me solicita la cuenta contable de pago **`Banco`**, el operario **`Operario`** y la forma de pago **`F de pago`**.
---
## 5.5 Arqueo de caja
### 5.5.1 Cierre de turno o de caja
#### `Ventas > Cierre de turno o caja`
* Permite realizar el arqueo de caja definitivo, sin mostrar los datos existentes en el TPV.


### 5.5.2 Arqueo de caja (Interpretación y datos de arqueo)
### 5.5.3 Consulta de arqueos
### 5.5.4 Consolidación de arqueos
---
## 5.6 Contabilización de los movimientos de TPV
### 5.6.1 Facturación de tickets
### 5.6.2 Traspaso de tickets a albaranes facturables
### 5.6.3 Funcionamiento de las cuentas contables de TPV
  ### 5.6.3.1 ¿Dónde aparecen cuentas contables predefinidas?
  ### 5.6.3.2 ¿En qué momento se contabilizan los movimientos de TPV?
  ### 5.6.3.3 ¿Cómo se utilizan las cuentas de Sage 50c TPV?
---
## 5.7 Gestión de solicitud de material

