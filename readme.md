##2017-02-03   v11
* numpad ya funciona con Unidades y cargar ( digito, backspace, enter )
* tabla "compras detalle" agregar campo exist
* numpad se posiciona cerca del control donde se hace el enfoque
* compras, focus en Unidades fix err al pulsar 1er digito
* crear tabla salidas, donde se almacenará todo lo que se cargue

##2017-01-20   v10
  * definir como agregar columna de cant a cargar ( asset\noel-cargar.gif)
  * al seleccionar lista-servicio se mueve numpad de unidades hacia a un costado de partidas a cargar
##2017-01-13   v9
* numpad
  * flecha izq y enter ( update tbChofer )
  * boton edit, activa/desactiva simultaneamente numpad/list box
  * boton edit, modifica lBox recordsource segun Frame/toggle buttons
  * boton edit, lBox update actualiza tbChofer
  * borrar y hacer de nuevo form unidades
  * agregar boton para abrir form taller 

##2017-01-06   v8
* taller
  * subform quitar columna "servicio"
  * renombrar columna "cant" x "exist"
  * resize subform ( descripcion, exist )
  * quitar subform "choferes"
  * agregar lBox "choferes"
* form rediseño "choferes" & sorted
* form unidades - quitar columna "chofer"
* tabla unidades - eliminar campo "chofer"
* form "unidades hoja" - eliminar
* replace unidad buttons x option group toggle buttons
* new form numpad & embed into taller
* numpad - macro, module1, function miNum()

##2016-12-30   v7
* form taller, eliminar cBox/lBox tipo de unidades/unidades
* BE crear tabla de choferes y FE link
* crear form datasheet choferes
* form taller agregar subform chofer & sort asc ( default )

##2016-12-23   v6
* form taller
  * servicio cBox After Update - filtra "compras Detalle Subform"
  * "compras Detalle Subform" - quitar dropdown & not in list
  * filter using lBox "Servicio"
  * lBox "tipo de unidades" 
    * ubound
	* selected value (index + 1), different than bound ( column 0)
	* propiedad "filter on load" - activar
	* filter using lBox "Unidades"
	
##2016-12-17   v5
* Servicio - cBox: newrec & dropdown
* form servicioModal - eliminar & code to open it.
* copiar "compras Detalle Subform" como "compras Detalle Subform2
*  form blanco "taller"
  * drag "compras Detalle Subform"
  * Servicio - lBox y Encabezado
  * Tipo unidades - gBox
  * unidades - form hoja & encabezados y sin logo
* Servicio tab 
  * tabStop = NO
  * descuento/lostfocus si servicioID es nulo, entonces
  servicioID.setfocus
  
##2016-12-02   v4
* Mover tabla "servicios" de fEnd a bEnd
* Compras-Subform cBox descripcion "order asc"
* **Change:**  "servicioID" de formModal a Cbox  en subform "Compras Detalle" 
  * Agregar CampoDeBusqueda “servicioID” a tabla “descripciones”
  * Agregar "servicioID" a subform "Compras Detalle"

##2016-11-18   v3
* tabla servicios
* formulario servicios
* formulario ppal, agregar servicios
* logotipo compras y servicios
* compras - servicios modal: listbox
  * emergente ( no new tab ) 
  * modal (hasta cerrar poder continuar)

##2016-11-05   v2
* crear tablas: compras, compras Detalle, Proveedores, Descripciones
* formulario master/detail: compras/compras Detalle
* cuadro combinado proveedor / descripciones
- cb.dropdown
- evento:  not in list, agregue el nuevo valor 
- filas en la lista: 6 
- detail: compraID esconder 
- agregar: subtotal / iva /total
- bloquear: importe ( precio extendido), para evitar punto de tabulacion
- detail: importe quitar #Err con NZ


##2016-10-28   v1













* tabla de usuarios.
* tabla de unidades.
* formulario de usuarios.
* formulario de unidades.
* formulario principal para acceder a los demas formularios.
* al abrir el programa, se abra el formulario principal de  forma automatica.
* acceso directo al sistema, sin abrir access.
* formularios, agregar logotipo.
* dividir base de datos: datos y captura
* formulario unidades:  tipo de unidad - Marco que mantenga el ultimo valor.


#OBJETIVOS DEL PROGRAMA:
1. A quien se le va a poner ( Unidades {tipos:[Auxiliares, Rutas, Autotanques]} )
2. Que se le hizo ( Refacciones )
3. Reportes: mensuales, anuales.
4. Cuanto se gastó.
