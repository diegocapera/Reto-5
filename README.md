# Reto-5
## Punto 1
Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.
```python
# Solicitar al usuario un número entero
num = int(input("Ingrese un número entero: "))

# Verificar si el número corresponde al código ASCII de una vocal minúscula
if num == ord('a') or num == ord('e') or num == ord('i') or num == ord('o') or num == ord('u'):
    print(f"El número {num} corresponde al código ASCII de una vocal minúscula.")
else:
    print(f"El número {num} no corresponde al código ASCII de una vocal minúscula.")

```
En este codigo se le pide al usuario que ingrese un numero entero el cual sera traducido a ASCII, pero se determina siertos valores los cuales se comparan traduciendolos en codigo ASCII con la funcion "ord" que es lo contrario a "chr" y comparandolos con el caracter en cuestion, si este numero traducido es igual al caracter que es una vocal minuscula, lanzará un primer mensaje confirmando que si es un a vocal minuscula, de lo contrario imprimirá otro mensaje confirmando lo contrario.

## Punto 2
Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.
```Python
# Solicitar un caracter al usuario
cadena = input("ingrese un caracter")
codigo_ascii = ord(cadena[0])
# Comparar si el caracter ingresado es par o impar
if codigo_ascii % 2 == 0:
    print("El código ASCII de la primera letra es par.")
else:
    print("El código ASCII de la primera letra es impar.")
````
En este codigo se le pide inicialmente un caracter al usuario, el cual sera evaluado con la funcion ord el cual toma el caracter y lo traduce al numero correspondiente al caracter, seguido a esto se compara y se evalua en dos casos, los cuales si el numero presentado se opera con el modulo el cual da unicamente el residuo de una division y si el residuo de esta division es 0 mostrará que el numero del caracter ingresado es un numero par o un numero impar.

## Punto 3
