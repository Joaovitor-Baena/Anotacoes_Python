# 🐍 Anotações Python:
## Exemplos Terminal
Executar terminal Vscode e escrever python para abrir o modo interativo e executar comandos em tempo real
+ dir(100)
função dir retorna uma lista de atributos válidos para o objeto

+ help()
Aciona as ajudas disponíveis tipo uma documentação

## Variáveis & Constantes 🗃️
+ Variáveis: podem ser alteradas durante o código enquanto a constante sempre se manterá

+ Constantes: Python não possuí constantes.
Por convenção se utiliza o nome da variável todo em letras maíusculas

## Boas práticas 📝
+ Padrão snake case. Ex: taxa_juros , n_vendas
+ Escolher nomes sugestivos.
+ Nome de constantes todo em maiúsculo.

# Operadores ➕➖➗🟰
São utilizados para fazer verificações e cálculos

## Operadores Aritméticos
Pode retornar True ou False

+ Soma: +
+ Subtrai: -
+ Multiplica: *
+ Divide: /
+ Divisão Inteira: //
+ Resto Divisão: %

## Operadores Comparadores
Pode retornar True ou False

+ Igualdade: == 
+ Diferença: !=
+ Maior que: >
+ Maior igual: >=
+ Menor que: <
+ Menor igual: <=


## Operadores de Atribuição
Apenas para atribuir valores

+ Atribuição simples : = (Atribui valor)
+ Atribuição com adição: += (Adicionar valor)
+ Atribuição com subtração: -= (subtrai valor)
+ Atribuição com multiplicação: *= (multiplica valor)
+ Atribuição com divisão: /= (divide valor)
+ Atribuição com divisão inteira: //= (divide valor inteiro)
+ Atribuição com módulo: %= (Resto da divisão valor)
+ Atribuição com exponenciação: **= (potência valor)


## Operadores Lógicos
Retornam True ou False

+ Operador E = and (True se todas partes verdadeiras)
+ Operador OU = or (True se apenas uma for verdadeira)
+ Operador Negação = not (Inverso de True)

## Operadores de Indêntidade
Retornam True ou False

+ is = é (Verificar se é)
+ is not = não é (Verificar se não é)

## Operadores de Associação
Geralmente utilizado em listas, vetores, matrizes. Retornam True ou False

+ in = (Verificar se está dentro)
+ not in = (Verificar se não está dentro)

n_float_to_int = 10.23
print(int(n_float_to_int))

# Convertendo Tipos ♻️

## Convertendo direto na saída

+ print(float(20))
+ O retorno disso seria = 20.0

## Type apenas para demonstrar que funciona
Convertendo uma string para float e utilizando type para demonstrar qual o tipo na saída

n_str_to_float = "14.78" </p>
print(float(n_str_to_float))</p>
print(type(float(n_str_to_float)))

+ O retorno de type seria: </p>
 <class 'float'>
 Demonstrando que funcionou a conversão
