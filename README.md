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
Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.
```python
caracter = input("Ingrese un numero de un digito")

if ord(caracter) >= 48 and ord(caracter) <= 57:
    print("El carácter es un dígito.")
else:
    print("El carácter no es un dígito.")
```
En el siguiente codigo se le pide un caracter al usuario, el cual se traducirá en un numero y seguido a ello se comparará en el intervalo propuesto, lo cual si el numero del caracter ingresado esta dentro del intervalo, este confirmara que el caracter es un digito, de lo contrario confirmará lo contrario, es decir que no es un digito.

## Punto 4
Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:

Positivo: "El número x es positivo"
Negativo: "El número x es negativo"
Cero (0): "El número x es el neutro para la suma"
```python
num = float(input("ingrese un numero real."))
if num > 0:
    print("el numero es positivo.")
elif num < 0:
    print("el numero es negativo")
elif num == 0:
    print("el numero es 0")
```
En el siguiente punto se le pide al usuario que ingrese un numero y este numero se comparará con tres condicionales los cuales en alguno de los 3 tendra que cumplir ya que se evaluan todos los numeros reales y solo se determina si es positivo, negativo o 0.

## Punto 5
Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.
```python
import math

# Pedimos al usuario que ingrese las coordenadas del punto
x = float(input("Ingrese la coordenada x del punto: "))
y = float(input("Ingrese la coordenada y del punto: "))

# Calculamos la distancia del punto al centro del círculo
distancia = math.sqrt(x**2 + y**2)

# Comparamos la distancia con el radio del círculo
if distancia < 10:
    print("El punto está dentro del círculo.")
elif distancia == 10:
    print("El punto está en la circunferencia del círculo.")
else:
    print("El punto está fuera del círculo.")
```
En este punto se tiene que tener en cuenta que el centro del círculo es (0,0) y que el radio de dicho circulo es de 10 unidades, por lo que lo unico que se le pide al usuario es que ingrese las coordenadas del punto que quiere ingresar, y con esto se usa el teorema de pitagoras el cual usamos la ecuacion de pitagoras que es h = (x*2+y*2)**2 y con su respectivo resultado se determina si el punto propuesto por el usuario esta dentro o fuera del circulo.

## Punto 6
Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.
```python
# Pedir al usuario tres longitudes
lado1 = float(input("Introduce la longitud del primer lado: "))
lado2 = float(input("Introduce la longitud del segundo lado: "))
lado3 = float(input("Introduce la longitud del tercer lado: "))

# Verificar si se puede construir un triángulo
if lado1 + lado2 >= lado3 and lado1 + lado3 >= lado2 and lado2 + lado3 >= lado1:
    print("Sí se puede construir un triángulo con esas longitudes.")
else:
    print("No se puede construir un triángulo con esas longitudes.")
```
En el ultimo punto no se establece un triangulo en especifico, por lo que hay que tener en cuenta todos los que hay, los cuales se tiene que procurar ciertos requerimientos, los cuales son que la suma de los lados sea mayor o igual, ya que esto permite que este los triangulos equilateros e isosceles, por lo que se procede a pedirle tres valores positivos al usuario, y despues se suman y se comparan con cada uno de los tres lados, y dado a que la suma de dos lados tiene que ser mayor al tercer lado, entonces se dan dos posiilidades, las cuales si se cumplen en esa suma, se imprimira un mensaje confirmando que si se puede hacer ese triangulo, de lo contrario imprime el mensaje confirmando lo contrario.
Este es el archivo .zip del reto ya que no se puede subir sin que este en un formato especifico como lo pide git hub.
[RETO 5.zip](https://github.com/diegocapera/Reto-5/files/11072521/RETO.5.zip)
