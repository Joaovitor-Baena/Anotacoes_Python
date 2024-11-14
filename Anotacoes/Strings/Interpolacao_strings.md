# Interpolação de Strings 
## Old style %
```bash
nome = "João"
idade = 23
profissao = "Analista"

print("Olá, me chamo %s. Eu tenho %d anos de idade e trabalho como %s" %(nome , idade , profissao))
```
%s = Utilizado para strings
%d = Utilizado para int
%f = Utilizado para float

## Método format
```bash
nome = "João"
idade = 23
profissao = "Analista"

print("Olá, me chamo {}. Eu tenho {} anos de idade e trabalho como {}".format(nome, idade, profissao))
```
Pode se manipular a sequencia dentro dos {} colocando número que represente na lista
#### Exemplo:
```bash
nome = "João"
idade = 23
profissao = "Analista"

print("Olá, me chamo {2}. Eu tenho {1} anos de idade e trabalho como {0}".format(profissao, idade, nome))
```
## Método f-string
```bash
nome = "João"
idade = 23
profissao = "Analista"

print(f"Olá, me chamo {nome}. Eu tenho {idade} anos de idade e trabalho como {profissao}")
```

## Resultados
Para todos os casos o resultados serão o mesmo:
```
Olá, me chamo João. Eu tenho 23 anos de idade e trabalho como Analista
```

## Formatando Strings com f-string
```bash
PI = 3.14159
print(f"Valor de PI:{PI:.2f}")
```

```bash
print(f"Valor de PI:{PI:10.2f}")
```
#### Resultados:
```
Valor de PI:3.14
Valor de PI:      3.14
```
No segundo print executado ele coloca 10 espaços conforme definido em:
```bash 
{PI:10.2f}
```
Além disso utiliza o 2 para pegar apenas os 2 números após a virgula ( f de float)