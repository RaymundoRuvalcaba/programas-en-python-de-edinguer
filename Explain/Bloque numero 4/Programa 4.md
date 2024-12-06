# Programa 4.- Función Range
## Fecha: 4/11/2024
### Realizado por: Edson Raymundo Ruvalcaba Marin.

- Utilizamos la función `range`
- La funcioón `range` sirve paara generar secuencias de números enteros
- Si declaras `range` el numero que imprimira sera uno menor al declarado
- En este caso declaro que "x" sea igual al rango del 0 al al 9
``` python
print("Imprime los valores del 0 al 9")
x = range(10)
```
- Con un ciclo `for` declaro que "num" o los numeros en "x" se imprimiran
- imprimo los "num" en la variable "x"
```python
for num in x:
    print(num)
```
- Declaro que la variable "x1" sea igual al rango del 5 al 16
- Imprimirá solo los numeros del 5 al 15
- Con un ciclo `for` declaro que la variable "num" o numeros en "x1" se imprima
- Imprimo los "num" en la variable "x1"
``` python
print("Imprime los valores del 5 al 15")
x1 = range(5,16)
for num in x1:
    print(num)
```
- Declaro que la variable "x2" sea igual a los pares del 10 al 21
- Imprimirá los pares del 10 al 20
- Con un ciclo `for` declaro la variable "num" o numeros en "x2"
- Imprimo los pares de "num" en la variable "x2"
``` python
print("Imprime los pares del 10 al 20")
x2 = range(10,21,2)
for num in x2:
    print(num)
```
- Declaro que la variable "x3" sea igual a los impares del 10 al 21
- Imprimirá los impares del 10 al 20
- Con un ciclo `for` declaro la variable "num" o numeros en "x3"
- Imprimo los impares de "num" en la variable "x3"
``` python
print("Imprime los impares del 10 al 20")
x3 = range(11,22,2)
for num in x3:
    print(num)
