# Programa 9.- Programa que permite crear una lista de todos los numeros menores a 50
## Fecha: 6/11/2024
### Realizado por: Edson Raymundo Ruvalcaba Marin.

- Declaro lalista "numeros"
``` python
print("THE FILTER PATTERN")
numeros =[10,50,25,13,10,28,100,500,29,29]
``` 
menores_50 = [] #Crea un vector o lista vacía
for numero in numeros:
    if numero < 50:
        menores_50.append(numero)


print("La lista original es: ",numeros)
print("La nueva lista es: ",menores_50)
