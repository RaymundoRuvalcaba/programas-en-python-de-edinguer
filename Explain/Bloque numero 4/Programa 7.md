# P7.- The sum Pattern
## Fecha: 5/11/2024
### Realizado por: Edson Raymundo Ruvalcaba Marin.

- Declaro la lista "numeros"
``` python
print("THE SUM PATTERN")
numeros = [100,200,300,400]
```
- Declaro la variable sumatoria y la inicializo "=0"
``` python
sumatoria = 0
```
- Con un ciclo `for` declaro la variable "numero" en "numeros
- Le agrego la variable "numero" a "sumatoria"
- Imprimo el valor de la sumatoria 
``` python
for numero in numeros:
    sumatoria = sumatoria + numero
print("La sumatoria es:", sumatoria)
