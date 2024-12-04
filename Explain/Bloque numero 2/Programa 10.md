# Programa 10: Revisar si puedes ver una pelicula en netflix. (if anidados)
## Fecha: 25/10/2024
### Realizado por: Edson Raymundo Ruvalcaba Marin. 
``` python
edad = int(input("Digite su edad: "))
```
- En este programa se utilizó la `Iteración` y los `if anidados`.
- La `iteración` sirve para implementar algoritmos que requieren la repetición de ciertas acciones.
- Y los `if anidados` no es mas que un `if` dentro de otro `if`.
- Este `if` se ejecturara si la variable edad es mayor o igual a 18. Antes de mostrar el mensaje hara una pregunta donde si la respuesta es 1 iniciará otro `if` donde mostrara un mensaje diciendo "Puede ver la pelicula"
```
if edad >= 18:
    compra = int(input("¿Compró la pelicula?\n 1(si)\n 0(no)\n"))
    if compra == 1:
        print("Puede ver la película")
```
- Este `else` se ejecutara si la variable edad es menor a 18 mostrando un mensaje diciendo "A casa pajin"
- Adicionalmente mostrará otro mensaje agradeciendo el haber usado Netflix.
```
    else:
        print("A casa pajin")
    print("¡Gracias por usar Netflix!")
```

```

if edad <= 17:  
    print("No") 
