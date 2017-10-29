# read-and-show-values-from-form
*Escribe un programa PHP que permita al usuario rellenar un formulario de registro con los datos de nombre, contraseña, fecha de nacimiento, tienda, edad y suscripción. El programa recibe los datos del formulario y los muestra en pantalla tal y como los escribió el usuario.*

Rama: "read-and-show-values-from-form-basic"

Orientaciones:

1. Procedimiento de paso de parámetros entre formulario y script PHP

2. Creación de una página web con PHP incrustado

*Implementa el mismo programa con las siguientes mejoras:*

Rama: "read-and-show-values-from-form-valid" 

* Mejora el script para que se compruebe la validez de los datos introducidos por el usuario en el formulario

    * Todos los campos son obligatorios
    * El nombre contiene letras mayúsculas y minúsculas y espacios y tiene una longitud entre 3 y 25 caracteres
    * La contraseña contiene caracteres alfanuméricos y tiene una longitud entre 6 y 8 caracteres
    * El correo electrónico debe tener el formato correcto
    * Debe ser mayor de edad

* Si se intenta activar el script "procesaformulario" sin pasar por el formulario el script reenvía el formulario para que se rellene.

Orientaciones:

1. Uso de la función PHP header

2. Uso de funciones de saneamiento y validación filter_input y filter_var

*Implementa el programa anterior con un único fichero que integre la creación del formulario con la creación de la página dinámica con los datos introducidos*

Rama: "read-and-show-values-from-form-one-file" 


