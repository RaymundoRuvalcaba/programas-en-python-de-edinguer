# Programa6.- Negative Subscript Indices
## Fecha: 24/10/2024
### Realizado por: Edson Raymundo Ruvalcaba Marin. 
word = "akuji"
- Al usar la `Indexación` y los corchetes podemos elegir caracteres en una cadena de texto o solo en una palabra. La indexación en "[-1]" imprime la letra "r"ya que el [-1] inicia donde termina el texto. 
``` python
print(word[-1])
```
- Los dos puntos ":" sirven para un rango de carateres en este caso [1:-1] ira desde 1 hasta -1 por lo que imprimirá de la a hasta la e, la r no la imprime ya que imprime  un caracter antes del limite
```
print(word[1:-1])
```
- En este ejemplo al iniciar en "-3" inicia 3 carateres antes del ultimo y como despues de los ":" esta vacio entonces imprimira los caracteres hasta que se termine el texto
```
print(word[-3: ])
```
- Aqui como no hay nada antes de los ":" imprimira desde el inicio del texto hasta que se encuentre un limite que en este caso es "3"
```
print(word[:3])
