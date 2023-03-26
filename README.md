1 - Alquilar:

   	- Nos a mandó una empresa gestionar un diseño de un software de alquler de videojuegos y compras de Informática
   	- Para cada videojuego, conocemos **marca**, **modelo** y **numeroSerie**. 
	- Los videojuegos alquilan **consolas**, **Juegos** y **Accesorios**.
	- Para las consolas alamcenamos (**nombreConsola** y **companinha**), 
	- juegos (**nombreJuego**, **genero**) y Para accesorios (**nombreAccesorio**).
	Cada vez que se guarde **fechaIncio**, **fechaFin**, si ha sido **entregado** y **precioAlquiler**.
	- Los videojuegos podrán alquilarse por usuarios de los guardaremos el 
	(**nombre**, **apellidos**, **direccion**, **teléfono**, **dni** y **e-mail**).
	
2 - Compra:

  	- Para cada articulo de informática, conocemos **marca**, **modelo**, **categoría**. 
	- Los articulos de Informática que se compran **ordenadores**, **componentes** y **Accesorios**. 
	- Los ordenadores almacenamos (**nombreOrdenaodor** y **características**), 
	componentes (**nombreComponente** y **características**) y Accesorios (**nombreArtículo**).
	- Los artículos de informática podrán comprarse por usuarios de los guardaremos el 
	(**nombre**, **apellidos**, **direccion**, **teléfono**, **dni** y **e-mail**)	
   
   ![carpetas iniciales](diagramas/tienda_UML.svg)
   
3 - Tienda Online

	 - Una empresa nos mandó gestionar un diseño de una tienda online.
	 Un cliente guardaremos (**nombre**, **direccion**, **e-mail**, **infoTarjetaCredito**, **infoCompra** y **saldo**), 
	 registar(), inciar() y actualizarPerfil().
	 
	 - Usario guardaremos (**idusuario**, **password**, **estadoLogin**, **dataRegistro**), verifcarLogin().
	 - Adminsitrador guardaremos (**nombreAdmin**, **e-mail**), actualizarCatálogo().
	 - Esta compuesto por cliente: **carritoCompra** y **pedido**
	 - Pedido guardaremos (**id**, **dataCreacion**, **dataCompra**, **nombreCliente**, **estado**, **idCompra**), 
	 realizarPedido().
	 
	 - CarritoCompra guardaremos (**carritoId**, **idProducto**, **cantidadProducto**, **fecha**), 
	  actualizarCarrito(), actualizarCantidad(), detallesCantidad(), verificar()
	 - Esta compuesto por pedido: **informacionEnvio** y **detallesPedido**
	 - informacionEnvio guardaremos (**idCompra**, **tipoCompra**, **costeCompra**, **compraRegionalId**), 
	 actualizarCompra().
	 - detallesPedido guardaremos (**idOrden**, **idProducto**, **nombreProducto**, 
  	 **cantidad**, **precioProducto**, **totalPedido**), calcularPrecio().
	
	
   ![carpetas iniciales](diagramas/Tienda_Online_UML.svg)
	
