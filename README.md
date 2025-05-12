# Prueba-de-desempeño
Este es un programa de inventarios, que permite al usuario añadir, consultar, actualizar y elimiar productos. Tambien permite calcular el valor total del inventario y muestra todos los articulos en el con la finalidad de tener un mayor control del mismo.
## Lista Vacía 
Como inicio partimos de la creacion de una lista vacía para que el usuario ingrese sus productos. ¿Por qué vacía? Supongamos que es la primera vez que el usuario ingresa al programa, no podria haber elementos en esta lista dado a que nadie tenia acceso anteriormente.

A medida que el usuario va ingresando productos, estos se van guardando en la lista llamada *stock*
____________________
Ejemplo:

stock :  list = [ ] 
____________________


## Función agregar productos 
Esta función le permite al usuario ingresar los producto con 3 características: 
* Nombre: El programa inicialmente le solicita al usuario que ingrese un nombre para el producto. 
* Precio: El producto debe tener un precio. Por lo tanto, el segundo paso que debe realizar el usuario es ingresar el precio. El ingreso de los datos debe ser un numero real, es decir, el tipo de dato es flotante (float)
* Cantidad: Finalemente el programa le solicita al usuario la cantidad del producto. La cantidad esta definido por un dato entero.

El programa valida que los datos ingresados tanto en precio como en cantidad sean números, de lo contrario lanza error.

_________________________
Ejemplo:

Enter the product name:

resaltador

Enter the price of the product resaltador:

5632.36

Enter the quantity of the product resaltador:

62

The product resaltador has been added successfully

Name: resaltador  - Price: $5632.36 - Quantity: 62

______________________________________________________
## Función consulta productos
Esta funcion le permite al usuario consultar la informacion (precio y cantidad) de un producto previamente registrado. Para esto, el programa le solicita al usuario el nombre del producto que desea consultar y devulve los datos  registrados.

En caso de que el producto solicitado no se encuentre en la lista, salta mensaje de error.
___________________________________________
Ejemplo:

Enter the name of the product you wish to inquire about.

lapiz

Name: lapiz - Price: $452.36 - Quantity: 2
____________________________________________________

## Función actualizar precio de productos
Esta función le permite al usuario actualizar el precio de un producto previamente registrado. Para lo cual, es necesario que el usuario ingrese el nombre del producto como se lo indica el programa; despues, le solicitara al usuario que ingrese el precio nuevo (Aqui entra una validacion, porque en caso de que el usuario ingrese un numero negativo le saltará error). Una vez ingresado el precio, el programa mostrará el producto con la informacion actualizada. Ó en caso de que el nombre del producto ingresado no coincida con ninguno de la lista, arroja error anunciando que el producto no se halló.
__________________________________
Ejemplo:

Enter the name of the product you want to update the price for.

lapiz

Enter the updated price:

789.36

Price updated successfully.

Name: lapiz - Price: $789.36 - Quantity: 12
______________________________________________

## Función Eliminar Producto
Esta función le permite al usuario eliminar un producto previamente registrado. Primeramente, el programa le solicita el nombre del producto que desea utilizar, si el producto coincide con alguno de la lista, el programa arrojará una confirmacion adicional para que el usuario esté seguro de que sí desea eliminar el producto mencionado. En caso de que la respuesta del usuario sea negativa, se cancelará el proceso, por el contrario, si la respuesta es afirmativa se eliminara el producto del inventario.
________________________________
Ejemplo:

Enter the name of the item you want to remove.

lapiz

Are you sure you want to delete lapiz from inventory? (yes/no)

yes

The product lapiz was successfully deleted
_________________________________________________

## Función Total Inventario
Está funcion muestra el valor total del inventario. Su uso principal es permitirle ver al usuario el valor actual de sus activos. En caso de que al momento no se haya ingresado ningun articulo, el programa anuncia que el inventario está vacío.
_______________________________
Ejemplo:

Total inventory value:395000.35


________________________________________

## Función ver lista
Permite al usuario ver todos los productos con su informacion asociada.

___________________________________________
Ejemplo:

Name: cuaderno - Price: 3500 - Quantity: 10

Name: lapiz - Price: 8000 - Quantity: 20

Name: borrador - Price: 4000 - Quantity: 50
______________________________________________________

## Función exit program.
Permite salir del programa y despide al usuario.
_________________________
Ejemplo:

Thank you for using our services!

Bye bye!
____________________________________________________


