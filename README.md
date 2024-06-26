# Exemplos-de-Recursao
## Somando números de um vetor
```
def soma_lista(lista):
  if len(lista) == 1:
    return lista[0]
  else:
    return lista[0] + soma_lista(lista[1:])
```
## Encontrando impares em um vetor
```
def  encontra_impares(lista):
  if len(lista) == 0:
    return []
  elif lista[0] % 2 != 0:
    return [lista[0]] + encontra_impares(lista[1:])
  else:
    return encontra_impares(lista[1:])
```
