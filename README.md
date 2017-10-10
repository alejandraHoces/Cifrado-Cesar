# Producto final de Cifrado Cesar

### Flujoframa Cifrado Cesar.
 Ingrese a link .
 
>https://imgur.com/a/b2qDC

### Pseudocódigo Cifrado Cesar.

**Sub proceso funcion cipher**  
Obtener codigo ASCII de las letras del mensaje ingresado,utilizamos un _FOR_ hasta _EL TAMAÑO DE LA LONGITUD_ de el mensaje ,al indice de cada letra recorrida le aplico el metodo _charCodeAt()_ el cual devuelve el indice en codigo _ASCII_ luego convierto la posicion que nosotros entendemos en el alfabeto para eso aplico la formula (x + 65 +n )%26 +65 . Seguidamente con esa posicion ya obtenida (resultado) que esta en el alfabeto pasarlo nuevamente y retornar la letra ,para ello coloco el siguente metodo String.fromCharCode() ,asi me aparece el mensaje encriptado.  
**Sub proceso funcion decipher**  
Aplicamos el mismo procedimiento pero con la formula de disminucion de espacios (x-n)%26 asi mi mensaje se encuentra descifrado.

### README.
Se puede apreciar el proceso de mi programa en el cual el usuario ingresa un mensaje que desea codificar y/o encriptar para ello se utiliza el algoritmo de Cifrado Cesar el cual mueve cada letra del mensaje un determinado numero de espacios en el alfabeto luego de aplicarlo el programa le muestra al usuario un mensaje codificado.
En el caso de que el cliente desee descifrar su mensaje el programa lo realiza utilizando la formula (x-n)%26 el cual resta los espacios avanzados y asi finalmene se muestra al usuario un mensaje descifrado.
