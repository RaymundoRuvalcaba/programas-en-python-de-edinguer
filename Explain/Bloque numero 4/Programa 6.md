# Programa 6.- Akuji
## Fecha: 5/11/2024
### Realizado por: Edson Raymundo Ruvalcaba Marin.

- Declaro la lista "letras"
``` python
print("THE COUNT PATTERN")
letras = ["a", "b", "c", "d", "e"]
```
- Declaro la variable "contador"
- El `=0` es para inicializar una variable
``` python
contador = 0
```
- Con un ciclo `for` declaro la variable "letra" en "letras"
- Hago un cambio en la bariable contador, cada vez que se repita se le sumara un "+1"
- Imprimo la lista de letras y el contador
``` python
for letra in letras:
    contador = contador +1
    print("La lista \"letras\" tiene",contador, "letras")
