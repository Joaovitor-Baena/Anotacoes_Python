# Estruturas de repetição ♻️
 ## For
 Quando sabemos préviamente o número exato de vezes para ser executado ou percorrer objetos

Exemplo:

```bash
texto = input("Informe um texto: ")
VOGAIS = "AEIOU"
for letra in texto:
if letra.upper() in VOGAIS:
    print(letra , end=" ")
```

## Range com for
Exemplo de list range
```bash
lista = list(range(4))
print(lista)
```
Utilizando com for
```bash
for numero in range(0 , 11):
    print(numero , end=" ")
```

## Tabuada do 5
```bash
for numero in range(0 , 51 , 5):
    print(numero , end=" ")
```

## While
Pode se utilizar else ou não
```bash
opcao = -1

while opcao != 0:
    opcao = int(input("Digite uma opção \n [1]Sacar \n [2]Extrato \n [0]Sair \n:"))

    if opcao == 1:
        print("Sacando...")
    elif opcao == 2:
        print("Exibindo extrato...")
    elif opcao == 100:
        print("Até logo!!")
        break
else:
    print("Obrigado por confiar em nosso sistema!!")
```

## Observações 👀
Utiliza se o `break` como condição de parada de execução

Pode se utilizar o `continue` para que ele pule uma condição

### break
```bash
for numero in range(100):
    if numero == 20:
        break
    print(numero, end=" ")
```
Nesse caso a execução termina no 19 
### continue
```bash
for numero in range(100):
    if numero == 20:
        continue
    print(numero, end=" ")
```
Nesse caso a execução continua, apenas pula a condição solicitada 
