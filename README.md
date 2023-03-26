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
