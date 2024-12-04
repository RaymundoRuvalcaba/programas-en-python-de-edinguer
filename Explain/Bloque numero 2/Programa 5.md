# Programa 5.- Práctica de comparación, Membership, slicing e indexado.
## Fecha: 23/10/2024
### Realizado por: Edson Raymundo Ruvalcaba Marin. 
- La comparación por `==` funciona si ambas partes son iguales dando un resultado "True" de lo contrario será "False 
``` python
print("COMPARACIÓN:")
print("Perro"=="Perro") #True
```
- La comparación por `!=` funciona si una de las partes es diferente dando como resultado "True", si ambas son iguales será "False"
``` python
print("Perro"!="Gato") #True
```
- La comparación por `>` funciona si la primera parte  es mayor dando como resultado "True", si es menor  será "False"
- La comparación por `<` funciona si la primera parte  es menor dando como resultado "True", si es mayor  será "False"
``` python
print("Aguascalientes"<"Zacatecas")#True
print("Aire">"Agua") #True
```
- La comparación por `in` funciona si la primera parte esta dentro de la segunda dando como resultado "True", si no está será "False"
- La comparación por `not in` funciona si la primera parte no esta dentro de la segunda dando como resultado "True", sí si está será "False"
``` python
print("\nMEMBERSHIP:")
print("house" in "Boathouse") #True
print("bien" in "bienvenidos")#True
print("Y" not in "ejes")#True
print("je" not in "ejes")#False
```
- El `Slicing` sirve para obtener un fragmento de una cadena dada. Utilizando los corchetes "[]" podemos indicar que caracter mandar a imprimir a pantalla
- La `Indexación` sirve para obtener varios fragmentos de una cadena dada. Utilizando los corchetes "[]" y ":" podemos indicar que caracter  y de donde a donde mandar a imprimir a pantalla
``` python
print("\nSLICING:")
print("INDEXING:")
mi_nombre = "Choto Chorchis"
print(mi_nombre[3])
print(mi_nombre[12])
print(mi_nombre[2:6])
