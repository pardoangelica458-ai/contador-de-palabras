# contador-de-palabras

## Descripción
Este programa cuenta la cantidad de palabras que hay en una frase ingresada por el usuario.

## Código corregido

```python
def contar(frase):
    palabras = frase.split()
    return len(palabras)

texto = input("Frase: ")
print(contar(texto))
