# Programa 5.- Operaciones aritmeticas basicas
## Fecha: 15/10/2024
### Realizado por: Edson Raymundo Ruvalcaba Marin.
- La variable `float` imprime números con punto decimal.
``` python
num1 = float(input("Digite el primer numero: "))
num2 = float(input("Digite el segundo numero: "))

``` 
- Aquí declaramos variables para usar operaciones con diferentes simbolos aritmeticos (+,-,*,/)

``` python
suma = num1 + num2
res = num1 - num2
multi = num1 * num2
div = num1 / num2

```
- El "+ str" sirve para convertir numeros a texto para así poder concatenarlos.
``` python

print("La suma de esos 2 numeros da como resultado: " + str(suma))
print("La resta de esos 2 numeros da como resultado: " + str(res))
print("La multiplicacion de esos  numeros da como resultado: "+ str(multi))
print("La division de esos  numeros da como resultado: "+ str(div))
