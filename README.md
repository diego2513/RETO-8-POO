# RETO-8-POO
en esta ocasion agregue dos nuevas clases al restaurante, una que se llama "Orderitem" y "Orderiterator"
La clase order item cinvierte un item simple en algo mas especifico, con toda la informacion que se tiene de ese item.
self.name = menu_item.name → "Fanta"
self.price = menu_item.price → 4000
self.quantity = quantity → 3
self.category = menu_item.__class__.__name__ → Beverage
self.total_price = menu_item.price * quantity → 4000 ×3 =12000
en esta clase declare un metodo especial que permite mostrar el item de forma mas legible
La clase "orderiterator" es la cual me pertmitira hacer la iteracion de la orden para ejecutar la conversion de la clase "orderitem", deja usar el "for item in order_iterator" sin problema con las tuplas convertidas en objetos de "orderitem", tambien declare unso metodos bastante utiles como totalitems para la totalidad de los productos o total price para el precio o detalle_orden para poder tener una orden mas organizada.
al final para finalizar la orden simplemente hago un "for" que me permite recorrer la orden y impprimir la orden con los detalles de cada producto de manera mas organizada
