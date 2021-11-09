# DesafiosPythonicos
Repositório para arquivos do curso de desafios pythonicos.

## Desafios:

### 1: Donuts

Dado um contador inteiro do numero de donuts, retorne uma string com o formato 'Number of donuts: <count>' onde <count> é o numero recebido. Entretanto, se o contador for 10 ou mais, use a palavra 'many' ao invés do contador. 
  
  Exemplo: _donuts(5)_ retorna 'Number of donuts: 5'
e _donuts(23)_ retorna 'Number of donuts: many'

#### Arquivo: 01_donuts.py


### 2: Both Ends

Dada uma string s, retorne uma string feita com os dois primeiros e os dois ultimos caracteres da string original. Entretanto, se o tamanho da string
for menor que 2, retorne uma string vazia.

Exemplo: 'spring' retorna 'spng'. 

#### Arquivo: 02_both_ends.py

### 3. Fix Start

Dada uma string _s_, retorne uma string onde todas as ocorrências do primeiro caracter de _s_ foram substituidas por '*', exceto a primeira.

Exemplo: 'babble' retorna 'ba**le'

Assuma que a string tem tamanho 1 ou maior.

Dica: s.replace(stra, strb) retorna uma versão da string s
onde todas as instancias de stra foram substituidas por strb.

#### Arquivo: 03_fix_start.py

### 4. Mix Up

Dadas as strings a e b, retorne uma string com a e b separados por um espaço 'a b', além disso, troque os 2 primeiros caracteres
das duas strings.


Exemplo:
    'mix', 'pod' -> 'pox mid'
    'dog, 'dinner' -> 'dig donner'

Assuma que a e b tem tamanho 2 ou maior.


#### Arquivo: 04_mix_up.py

### 5. Verbing

Dada uma string, se seu tamanho for pelo menos 3, adicione 'ing' no seu fim, a menos que a string já termine com 'ing', nesse caso adicione 'ly'.

Se o tamanho da string for menor que 3, não altere nada.

Retorne o resultado da string.

#### Arquivo: 05_verbing.py


### 6. Not Bad

Dada uma string, encontre a primeira aparição das substrings 'not' e 'bad'. Se 'bad' aparecer depois de 'not', troque todo o trecho entre 'not' e 'bad' por 'good' e retorne a string resultante.

Exemplo: 'The dinner is not that bad!' retorna 'The dinner is good!'

#### Arquivo: 06_not_bad.py

### 7. Front Back

Considere dividir uma string em duas metades. Caso o comprimento seja par, a metade da frente e de trás tem o mesmo tamanho. Caso o comprimento seja impar, o caracter extra fica na metade da frente.

Exemplo: 'abcde', a metade da frente é 'abc' e a de trás é 'de'.

Finalmente, dadas duas strings a e b, retorne uma string na forma:
a-frente + b-frente + a-trás + b-trás

#### Arquivo: 07_front_back.py

### 8. Match Ends

Dada uma lista de strings, retorne a contagem do número de strings onde o comprimento da cadeia é 2 ou mais e o primeiro e o último caracteres da cadeia são os mesmos.

PS: Python não possui o operador ++, porém += funciona.

#### Arquivo: 08_match_ends.py


### 9. Front X

Dada uma lista de strings, retorne a lista com as strings ordenadas, porém agrupe todas as strings que começam com 'x' primeiro.

Exemplo: ['mix', 'banana' ,'xyz', 'apple', 'xanadu', 'aardvark']
Irá retornar: ['xanadu', 'xyz', 'aardvark', 'apple', 'banana' ,'mix']

Dica: Isso pode ser resolvido criando 2 listas e ordenando cada uma antes de combina-las.

#### Arquivo: 09_front_x.py

### 10. Sort Last

Dada uma lista de tuplas não vazias, retorne uma lista ordenada em ordem
crescente com base no último elemento de cada tupla.

Exemplo: [(1, 7), (1, 3), (3, 4, 5), (2, 2)]
Irá retornar: [(2, 2), (1, 3), (3, 4, 5), (1, 7)]

Dica: Use uma custom key= function para extrair o ultimo elemento de cada tupla.

#### Arquivo: 10_sort_last.py