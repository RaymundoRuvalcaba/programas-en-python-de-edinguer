# Programa 7.- Prog. que colicite la edad e indique si puede entrar a un bar.
##  Fecha: 24/10/2024
### Realizado por: Edson Raymundo Ruvalcaba Marin. 
``` python
edad = int(input("ingresar tu edad: "))
``` 
- La condicional `if` es un control de flujo que permite ejecutar una parte del código solo si se cumple una condición específica. La condición se evalúa como verdadera (true) o falsa (false),si es verdadera, el programa ejecuta el código asociado.
- En este caso nuestro programa se ejecutará solo si la variable edad es mayor o igual a 18 dando como resultado un `print` que imprima a pantalla el mensaje "Entras"
``` python
if edad >= 18:
    print("Entras")
```
- Un `else` se utiliza para especificar que parte del código se ejecutará cuando la condición principal no se cumpla.
- En este caso el `else` ejecutara un `print` con el mensaje "No entras"
``` python
else:
    print("No entras")
