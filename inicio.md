# 05 Operativa del TPV

## 051 Pedido de Venta
### `Ventas > Pedido`
* Por defecto pone un número del contador configurado en las opciones de contadores.
* Se propone la fecha del día `[Fecha]` y la fecha de entrega `[F. Entrega]`.
* Selecciono el almacén `[Almacen]`, el vendedor `[Vendedor]` y la forma de pago `[F.Pago]`.
* Selecciono el cliente `[Cliente > Codigo]`.
* Añado `[Añadir]` los artículos `[Articulo]` y sus unidades `[Unidades]`.
* Se pueden introducir observaciones `[Observ]` en el pedido.
* Se pueden añadir notas `[Notas]` previamente configuradas en las definiciones de notas.
* Haciendo click en el artículo y pulsando en `[Foto]`, se puede ver la imagen asociada a ese artículo.
* Puedo ver las últimas ventas del cliente `[Ventas]`.
* Puedo ver los últimos pedidos por cliente `[Pedidos]`, con los documentos `[Documentos]` de ese cliente con sus correspondientes detalles [Detalle].
* Puedo ver los `[Pedidos pendientes de servir del cliente]`.
* En la parte inferior puedo ver el importe del pedido `[Total (€)]`, la importe base `[Base IVA]`, el porcentaje de IVA `[% IVA]`, el importe de IVA `[Importe IVA]` y el importe de recargo `[Imp. Recargo]`.

## 052 Traspaso de pedidos de venta a albaranes de venta de la caja
(Realmente es Traspaso de tickets a albaranes facturables)
### `Ventas > Terminal Punto de Venta`
* Selecciono el perfil lineal `[Completo]`.
* Añado `[Añadir]` los artículos `[Articulo]` y sus unidades `[Unidades]`.
* Una vez introducido el ticket, supongamos el cliente me pide que le haga una factura.
* Para no tener que borrar el ticket e introducir la factura:
  * Selecciono FACTURA `[Documento]`.
  * Automáticamente se traspasa a albarán.
  * Pregunta si deseo cambiar el cliente. Si no cambio de cliente, pregunta si deseo entrar en la ficha de `Cliente Varios`.
  * Si no entro en la ficha, se convierte automáticamente en factura.
  * Para cobrar esa factura, hago click en `[Cobrar]`, selecciono `Contabilizar cobro` y hago click en `Facturar`.
  * Una vez cobrado, automáticamente pone el sello `Facturado`.
  * Haciendo doble click en Facturado, aparece la factura y muestra el sello `Contabilizada`.
  * Se ha pasado de un ticket a albarán facturado.

### `Ventas > Traspaso de tickets a albaranes facturables`
* Se filtra por los parámetros correspondientes y se muestra un listado de los tickets que pueden traspasarse.
	* Los tickets traspasados a albaranes de venta tendrán como entrega a cuenta el total cobrado del ticket.
	* Si se genera la factura de venta automáticamente y el ticket tiene algún importe pendiente de cobrar, también se generarán las previsiones de la factura.
