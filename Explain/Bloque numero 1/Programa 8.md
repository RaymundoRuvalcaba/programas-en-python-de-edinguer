# Programa 8.- Programa que calcula el numero de minutos, horas y meses, dado el numero de dias por el usuario
# Fecha: 16/10/2024
# Elaborado por: Edson Raymundo Ruvalcaba Marin. 
- Con la función `input` solicitamos la cantidad de dias
``` python
dias = int(input("Digite la cantidad de dias: "))
```
- Declaramos variables
``` python
horas = dias * 24
min = horas * 60
meses = dias / 30
```
- Con la función `print` mostramos los resultados
``` python
print("La cantidad de horas en esos dias es: "+str(horas))
print("La cantidad de minutos en esas horas es: "+str(min))
print("La cantidad de meses en esos dias es: "+str(meses))
