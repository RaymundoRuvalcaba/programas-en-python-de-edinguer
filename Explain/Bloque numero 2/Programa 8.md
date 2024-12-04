# Programa8.- Programa que calcula el promedio de 5 unidades e indique si aprobó la materia
## Fecha: 24/10/2024
### Realizado: Edson Raymundo Ruvalcaba Marin. 
``` python
calf1 = float(input("Digite su calf en una escala del 1 al 100 de la U1: "))
calf2 = float(input("Digite su calf en una escala del 1 al 100 de la U2: "))
calf3 = float(input("Digite su calf en una escala del 1 al 100 de la U3: "))
calf4 = float(input("Digite su calf en una escala del 1 al 100 de la U4: "))
calf5 = float(input("Digite su calf en una escala del 1 al 100 de la U5: "))
calf = (calf1 + calf2 + calf3 + calf4 + calf5) / 5
```
- En este caso el `if` tiene una especificación y es si la variable "calf" es mayor o igual a 70 ejecutara un print mostrando que su calificación es aprobatoria y el resultado de dicha calificación con un `+str(calf)`.
- Y adicionalmente un mensaje agradeciendo el haber usado este programa.
```python
if calf >= 70:
    print("Su calificación es aprobatoria, su calificación final es: "+str(calf))
    print("¡GRACIAS POR USAR NUESTRO SISTEMA!")
```
- Este `else` se ejecuta si "calf" no es mayor o igual a 70 mostrando un mensaje diciendo que su calificacion no es aprobatoria y el resultado de la calificación.
- Adicionalmente se muestra un mensaje agradeciendo el haber usado este programa.
``` python
else:
    print("Lo sentimos su calificación no es aprobatoria, su calificación final es: "+str(calf))
    print("¡GRACIAS POR USAR NUESTRO SISTEMA!")
