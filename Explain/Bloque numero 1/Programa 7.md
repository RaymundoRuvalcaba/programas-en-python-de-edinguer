# Programa 7.-calcula el area y el perimetro de un circulo ingresando el valor del radio por el usuario.
## Fecha: 15/10/2024
### Realizado por: Edson Raymundo Ruvalcaba Marin. 
- Con la función `input` solicitamos el valor del radio
``` python
radio = float(input("Ingresa el valor del radio: "))
```
- Declaramos las variables "area" y "perimetro".
``` python
area = 3.1416 * radio ** 2
perimetro = 3.1416 * 2 * radio

```
- Con la función `print` imprimimos el resultado
``` python
print("El area del circulo es: "+str(area))

print("El perimetro del circulo es: "+str(perimetro))
