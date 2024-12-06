# Programa 1.- Programa que indica, de 2 enteros ingresados el primero es mayor,
#  igual o menos que el segundo
## Fecha: 28/10/2024
### Realizado por: Edson Raymundo Ruvalcaba Marin.

- Declaramos variables
``` python
n1 = int(input("Digite el primer numero en numeros enteros: "))
n2 = int(input("Digite el segundo numero en numeros enteros: "))
```
- Con un `if` declaramos la condicional de si la variable "n1" es mayor a "n2"
- Al cumplirse esta condición se imprimira un `print` con un mensaje
``` python
if n1 > n2:
    print("El numero " +str(n1) + " es mayor al " +str(n2))
```
- Usando un `elif` declaramos tra condicion, si "n1" es igual a "n2"
- Si esta condicional se cumple se imprimirá un mensaje a pantalla 
 ``` python
elif n1 == n2:
    print("Son numeros iguales")
```
- Si ninguna se las condiciones anteriores secumplió es porque la variable "n1" es menor a "n2"
- Con un `else` y un `print` imprimimos ese mensaje a pantalla
``` python
else:
    print("El numero " +str(n1)+ " es menor al numero"+str(n2))

    print("¡Gracias por usar nuestro programa!")
