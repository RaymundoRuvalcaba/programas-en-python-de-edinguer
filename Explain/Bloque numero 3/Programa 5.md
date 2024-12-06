# Programa 5.-Programa que calcule el desempeño deun estudiante de acuerdo con su calificacion dada por el usuario
## Fecha: 29/10/2024
### Realizado por: Edson Raymundo Ruvalcaba Marin.

- Declaro la variable "calificación"
``` python
calificacion = int(input("Digite su calificación en escala del 1 al 100: "))
```
- Con un `if` declaro la condicional, si "calificacion" es menor o igual a 60 y menor o igual a 69
- Si se cumple esta condición se imprimirá un mensaje a pantalla
``` python
if calificacion <= 60 and calificacion <= 69: 
    print("Su calificación es insuficiente")
```
- Con un `elif` declaro la condición, si "calificación" es igual a 70 y menor o igual a 79
- Si se cumple esta condición se imprimira un mensaje a pantalla
``` python
elif calificacion == 70 and calificacion <= 79: 
    print("Su calificacion es suficiente")
