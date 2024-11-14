# Fatiamento de strings
```bash
nome = João Vitor

print(nome[0])
```
O resultado seria apenas a letra 0 nesse caso J</p>

Podemos selecionar a quantidade de caracteres que desejamos dessa forma
```bash
print(nome[:4])
```
Resultado seria : João

A localização dos dois pontos é onde vamos realizar os filtros, criar intervalos, por exemplo

```bash
print(nome[5:])
```
Pularia os 5 primeiros caracteres e retornaria o restante, resultando em : Vitor

Podemos fazer esses e vários outros filtros

## Espelhamento da string
podemos inclusive fazer um espelhamento da string:
```bash
print(nome[::-1])
```
Resultaria na string escrita ao contrário



