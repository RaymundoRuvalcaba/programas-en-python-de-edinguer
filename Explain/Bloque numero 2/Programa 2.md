# Programa 2.- Chorchis and Choto fieta
## Fecha: 22/10/24
### Realizado por: Edson Raymundo Ruvalcaba Marin. 
# | A | B || not( A or B) |
# | 0 | 0 || 1
#-----------------------------
# |A | B || not ( A or B) |
# | 0 | 0 || 1
- Al agregar un  `not` el resultado de la compuerta se invierte.
- En el primer ejemplo el resultado seria False ya que 0 o 0 sigue siendo un 0 en este caso es FALSE pero al agregar `not` imprimimos el opuesto del resultado final dando como resultado "True"
``` python
print(not(False or False)) # SI hay fiesta.
```
- En estos 3 ejemplos el resultado seria True ya que 1 o 0 da 1 ya que estamos usando la compuerta `or` pero al agregar `not` imprimimos el opuesto del resultado final dando como resultado "False"
``` python
print(not(False or True))  # NO hay fiesta.
print(not(True or False))  # NO hay fiesta.
print(not(True or True))  # NO hay fiesta.
