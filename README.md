# Desafio Maeztra
Testes de avaliação inicial em lógica de programação <br>
Os códigos devem ser feitos em Javascript/JQuery<br>
Se possível, documente o código com comentários

Dê um fork neste repositório, e após concluir as atividades faça um pull request

## Questão 1
### Dado um valor inteiro, verifique se os dígitos estão em ordenação sequencial

#### Exemplo
- 1234567 e 87654321 estão ordenados.
- 1573154 e 4567891011 não estão ordenados.

## Questão 2
### Crie uma função que receba um array de inteiros como parâmetro e verifique se neste array existem números duplicados, caso exista, retorne um novo array com os valores que se repetem 

#### Exemplo
- Input [4,5,44,98,4,5,6,7]
- Output [4,5]

## Questão 3
### ### Crie uma função que recebe uma string com qualquer sequência dos seguintes caracteres: <br>
'[', '{', '(', ')', '}', ']' e retorne se a sequência é uma sequêcia válida ou não

## Questão 4
### Considere um conjuto de pessoas aposentadas, onde cada pessoa começou a trabalhar em ano X e aposentou em ano Y. Crie uma função que receba uma matriz na seguinte estrutura: <br> [[x1,y1],[x2,y2],...[xn,yn]] <br>e calcule em qual ano houve mais gente trabalhando

Considere:
- Os valores de X como o ano que os indívíduos começaram a trabalhar (x>0, x<y )
- Os valores de Y como o ano que os indívíduos se aposentaram (y>0)
- O ano de início deve ser considerado como ano trabalhado
- O ano de aposentadoria deve ser considerado como ano trabalhado

#### Exemplo:
- Input [[1960,2005],[1945,2008],[1938,1999],...]
