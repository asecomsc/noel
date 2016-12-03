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
