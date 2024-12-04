# Programa 6.- Calcular el area de un triangulo
## Fecha: 15/10/2024
### Elaborado por: Edson Raymundo Ruvalcaba Marin. 
- Con la función `input` pedimos tanto la base como la altura de un triangulo para asi  sacar su area.
``` python
base = float(input("Cuanto mide la base: "))
altura= float(input("Cuanto mide la altura: "))
area = base * altura / 2
```
- Dicha area la mostraremos con un print y con `+ str`concatenamos a variable string para tener un resultado compatible.
```python
print("El area de este triangulo es: "+ str(area))
``` 
