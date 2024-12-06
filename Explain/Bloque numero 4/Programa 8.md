# Programa 8.- THE ACCUMULATION PATTERN
## Fecha: 5/11/2024
### Realizado por: Edson Raymundo Ruvalcaba Marin.

- Declaro lalista "palabras"
``` python
palabras = ["Hoy"," ","es"," ","lunes"]
```
- Declarola variable "mensaje" y la dejo vacía agregando un `= ""`
``` python
mensaje = ""
```
- Con un ciclo `for` declaro la variable "palabra" en "palabras"
- Hago un cambio en la variable "mensaje" sumandole la variable "palabra"
- Imprimo "mensaje"
``` python
for palabra in palabras:
    mensaje = mensaje + palabra
    print(mensaje)
