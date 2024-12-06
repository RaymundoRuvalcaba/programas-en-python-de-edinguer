# Programa 4.- Programa que calcule los impuestos que debe pagar un empleado
## Fecha: 29/10/2024
### Realizado por: Edson Raymundo Ruvalcaba Marin.

- Declaro la variable "ingresos"
``` python
ingresos = input("¿Cuales son sus ingresos? ")
```
- Cnvierto la variable "ingresos" a tipo `float`
``` python
ingresos = float(ingresos)
```
- Con un `if` declaro la condicional, si "ingresos" es menor a 1000
- Declaro la variable "ingresos" al multiplicar "ingresos" * 0.05
- Si se cumple la condición se imprimirá un mensaje a pantalla dando tus ingresos menos los impuestos
``` python
if ingresos <=1000:
    impuestos = ingresos * 0.05
    print("Tus ingresos menos los impuestos son de "+str(impuestos))
```
- Con un `elif` declaro otra condicional, si "ingresos" es mayor a 1000 y menor o igual a 2500
- Declaro un cambio a la variable impuestos, ahora multiplico "ingresos" * 0.08
- Si la condición se cumple imprimirá un mensaje a pantalla dando tus ingresos menos los impuestos
``` python
elif ingresos > 1000 and ingresos <=2500:
    impuestos = ingresos * 0.08
    print("Tus ingresos menos los impuestos son de "+str(impuestos))
```
- Con otro `elif` declaro otra condicional, si "ingresos" es mayor a 2500 y menor o igual a 6000
- Declaro un cambio a la variable impuestos, ahora multiplico "ingresos" * 0.12
- Si la condición se cumple imprimirá un mensaje a pantalla dando tus ingresos menos los impuestos

``` python
elif ingresos > 2500 and ingresos <= 6000:
    print("Tus ingresos menos los impuestos son de "+str(impuestos))
    impuestos= ingresos * 0.12
```
- Con un `else` declaro un cambio en "impuestos" donde ahora multiplico "ingresos" *0.15
- Declaro una nueva variable llamada "salario_total" que es igual a "ingresos" - "impuestos"
- Imprimo un mensaje a pantala donde muestro los impuestos y el salario final
``` python
else:
    impuestos = ingresos * 0.15
    salario_total = ingresos - impuestos
    print("Tus impuestos son "+str(impuestos) + "y tu salario final es" +str(salario_total))
