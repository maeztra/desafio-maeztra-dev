# Desafio Maeztra
Testes de avaliação inicial em lógica de programação <br>
Os códigos devem ser feitos em Javascript/JQuery<br>
Envie os códigos nos arquivos correspondentes<br>
Se possível, documente o código com comentários

Dê um fork neste repositório, e após concluir as atividades faça um pull request

## Questão 1
### Dado um valor inteiro positivo, verifique se os dígitos estão em ordenação sequencial

#### Exemplo
- 1234567 e 87654321 estão ordenados.
- 1573154 e 4567891011 não estão ordenados.

## Questão 2
### Crie uma função que receba um array de inteiros como parâmetro e verifique se neste array existem números duplicados, caso exista, retorne um novo array com os valores que se repetem 

#### Exemplo
- Input [4,5,44,98,4,5,6,7]
- Output [4,5]

## Questão 3
### Crie uma função que recebe uma string com qualquer sequência dos seguintes caracteres: <br> '[', '{', '(', ')', '}', ']' <br> e retorne se a sequência é uma sequêcia válida ou não 

#### Exemplo:
- { [ ( ) ( ) { } [ ] ] { } } é uma sequência válida
- { [ ( ( ) ] } não é uma sequência válida
- { } [ ] ( ) é uma sequência válida
- ( ( ) { } [ [ ] ) não é uma sequência válida

Dica: Os espaços nos exemplos são apenas para favorecer a leitura. Espaços não farão parte das strings de teste

## Questão 4
### Considere um conjuto de pessoas aposentadas, onde cada pessoa começou a trabalhar em ano X e aposentou em ano Y. Crie uma função que receba uma matriz na seguinte estrutura: <br> [[x1,y1],[x2,y2],...[xn,yn]] <br>e calcule em qual/quais ano/anos houve mais gente trabalhando

Considere:
- Os valores de X como o ano que os indívíduos começaram a trabalhar (x>0, x<y )
- Os valores de Y como o ano que os indívíduos se aposentaram (y>0)
- O ano de início deve ser considerado como ano trabalhado
- O ano de aposentadoria deve ser considerado como ano trabalhado

#### Exemplo:
- Input [[1960,2005],[1945,2008],[1938,1999],...]

## Questão 5
### Um grupo de x amigos serão colocados lado a lado para tirar uma foto. De quantos modos distintos os X amigos podem se organizar para tirar a foto? Desenvolva uma função para que o fotografo saiba o número de modos distintos que essas e outros grupos possam se organizar
