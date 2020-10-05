
# Desafio Maeztra
Olá candidato,
Este teste se divide em duas etapas, a primeira é um teste lógico onde iremos analisar a sua forma de pensar e como você lida com problemas abstratos. Os códigos dessa etapa devem ser feitos em Javascript, e não se esqueça de documentar todo o processo de cada resposta.

Para iniciar o teste você pode clonar o repositório, e no prazo de dois dias enviar os arquivos em formato .rar/.zip para o email selecao@maeztra.com com o assunto **Processo Seletivo Maeztra**, assim como o link para o github pages (mais informações no tópico layout).

## Teste lógico
Dentro do repositório existem cinco arquivos já nomeados para você realizar os seus algoritmos.

***1 - Crie uma função que receba um valor INTEIRO positivo, e verifique se os DÍGITOS estão em ordenação sequencial CRESCENTE ou DECRESCENTE. Pode considerar dígitos iguais como sequenciais (Variação de um dígito para o outro deve ser 1 ou menor)***

> Exemplo:<br/>
> Input 12345678 -> Está ordenado <br/>
> Input 1223455678 -> Está ordenado <br/>
> Input 876543210 -> Está ordenado <br/>
> Input 152456457 -> Não está ordenado <br/>
> Input 12356789 -> Não está ordenado <br/>
> Input 13579 -> Não está ordenado <br/>
> Input 9765421 -> Não está ordenado <br/>
> Input 123454321 -> Não está ordenado <br/>
> Input 12222222 -> Está ordenado <br/>
> Input 2111111 -> Está ordenado <br/>
> Input 1599 -> Não está ordenado



***2 - Crie uma função que receba um array de inteiros como parâmetro e verifique se neste array existem números duplicados, caso exista, retorne um novo array com os valores que se repetem.***

> Exemplo:<br/>
> Input `[4,5,44,98,4,5,6,7]` &rarr; Output `[4,5]`

***3 - Crie uma função que recebe uma string com qualquer sequência dos seguintes caracteres*** `'[', '{', '(', ')', '}', ']'` ***e retorne se a sequência é uma sequência válida ou não. Uma sequência é válida se as chaves, parênteses e colchetes abrem e fecham corretamente***
> Exemplo:<br/>
> `{ [ ( ) ( ) { } [ ] ] { } }` é uma sequência válida<br/>
> `{ [ ( ( ) ] }` não é uma sequência válida (Há um parêntese posicionado incorretamente)<br/>
> `{ } [ ] ( )` é uma sequência válida<br/>
> `( ( ) { } [ [ ] )` não é uma sequência válida (Há uma chave posicionado incorretamente)

Dica: Os espaços nos exemplos são apenas para favorecer a leitura.<br/>
Espaços não farão parte das strings de teste

***4 - Considere um conjunto de pessoas aposentadas, onde cada pessoa começou a trabalhar em ano X e aposentou em ano Y. Crie uma função que receba uma matriz na seguinte estrutura*** `[[x1,y1],[x2,y2],...[xn,yn]]` ***e calcule em qual/quais ano/anos houve mais pessoas trabalhando.***

*Considere:*
- Os valores de X como o ano que os indívíduos começaram a trabalhar (x>0, x<y );
- Os valores de Y como o ano que os indívíduos se aposentaram (y>0);
- O ano de início deve ser considerado como ano trabalhado;
- O ano de aposentadoria deve ser considerado como ano trabalhado.

> Exemplo:<br/>
> Input `[[1960,2005],[1945,2008],[1938,1999],...]`

***5 - Um grupo de amigos será colocado lado a lado para tirar uma foto. De quantos modos distintos os amigos podem se organizar para tirar a foto? Desenvolva uma função que receba um número de pessoas (valor inteiro) e retorne quantas possibilidades de organização existem para que o fotografo saiba o número de modos distintos que esse grupo e outros grupos possam se organizar.***

## Layout
Essa é a segunda etapa do teste onde iremos analisar o ~~seu perfeccionismo~~ perfect pixel e de como você constrói os seus layouts.

Requisitos:
- O layout que você vai utilizar é este: [Layout Figma](https://www.figma.com/file/3RqPfS5PW9whbQNCTTaoqA/%5B2020-09%5D-MZ---Layout-Teste-de-vagas-para-time-de-Devs);
- Você pode utilizar qualquer framework ou library que você preferir;
- A sua página deve ser hospedada no [Github Pages](https://pages.github.com/) e o link deve ser enviado no e-mail;
- Estruture os seus arquivos em uma pasta chamada **layout** e se possível crie um *README*.

## Dúvidas
Caso você tenha alguma dúvida sobre os exercícios ou o layout, você pode abrir uma issue e nós responderemos por lá.

Boa sorte!
