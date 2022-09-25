# ProyectoFinalBerocay

Es un simulador de una tienda on line que vende tecnología obsoleta.

Cuando accedes por primera vez te pide un nombre que se guarda en el Local Storage y después lo carga desde ahí y no te lo vuelve a pedir.

La primera vez que se ingresa hay 4 productos precargados, se pueden agregar productos mediante un formulario. Los productos agregados también se guardan en el Local Storage y se cargan desde ahí cuando se vuelve a ingresar a la tienda.

Se pueden agregar los productos al carrito, los productos agregados también se almacenan en el Local Storage lo que permite volver a cargar estos productos la próxima vez que accedemos a la tienda.
En el carrito se suman todos los precios y te da el total a pagar.
Si el carrito esta vacío sale un texto que dice que “El carrito está vacío” 
Si das comprar te pide una confirmación y un cartel de agradecimiento, si el carrito esta vacío te sale una alerta.
El botón de “Vaciar carrito” solo aparece si hay productos agregados, cuando se da clic en él se pide una confirmación antes de vaciarlo. 

Utilicé la librería Sweet Alert para la confirmación de la compra y del vaciamiento del carrito. La librería Toastify la usé para mostrar el mensaje de que un producto fue agregado al carrito.

Usé la API Open Weather para cargar la temperatura actual de Montevideo.

La parte de HTML y CSS esta media caótica y desprolija, pero todavía no hice el curso de desarrollo web así que hice lo que pude con las cosas que fui encontrando por ahí.
