# Producto final de Cifrado Cesar

### Flujoframa Cifrado Cesar.
 Ingrese a link .

>https://imgur.com/a/b2qDC

### Pseudocódigo Cifrado Cesar.

1.Inicio;  
2.Solicitando la introduccion de el mensaje a cifrar;  
3.Inicializar función cipher parametros: a=mensaje a cifrar, b=Numero de desplazamiento (nfijo);  
4.Inicializar variable result ="";  
5.Leer mensaje;  
6.Para var i=0;i<mensaje.length;i++;  
7.Inicializar variable ascii =mensaje.charCodeAt(i)(convirtiendo mensaje a valor ascci);  
8.Si 65<=ascii && ascii<=90;  
9.Escribir_letras mayusculas;  
10.Aplicar formula result+=String.fromCharCode((ascii-65+nfijo)%26+65);  
11.Si 97<=ascii && ascii<=122;  
12.Escribir letras minusculas;  
13.Aplicar formula result+=String.fromCharCode((ascii-65+nfijo)%26+65);  
14.Si usuario ingresa numeros;  
15.Escribir alerta "Ingresar solo letras";  
16.Llamar a la función cipher(mensaje a cifrar,33);  
17.Escribir mensaje cifrado;  
18.Fin.


### README.
Se puede apreciar el proceso de mi programa en el cual el usuario ingresa un mensaje que desea codificar y/o encriptar para ello se utiliza el algoritmo de Cifrado Cesar el cual mueve cada letra del mensaje un determinado numero de espacios en el alfabeto luego de aplicarlo el programa le muestra al usuario un mensaje codificado.
En el caso de que el cliente desee descifrar su mensaje el programa lo realiza utilizando la formula (x-n)%26 el cual resta los espacios avanzados y asi finalmene se muestra al usuario un mensaje descifrado.
