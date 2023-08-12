# desafio_mirantes

Olá candidato, neste teste iremos analisar a sua forma de pensar e como você lida com problemas abstratos. Os códigos dessa etapa devem ser feitos em Javascript, e não se esqueça de documentar todo o processo de cada resposta,é sobre todos!!

**1 - Crie uma função que receba um valor INTEIRO positivo, e verifique se os DÍGITOS estão em ordenação sequencial CRESCENTE ou DECRESCENTE. Pode considerar dígitos iguais como sequenciais (Variação de um dígito para o outro deve ser 1 ou menor)**

Exemplo:
- Input 12345678 -> Está ordenado
- Input 1223455678 -> Está ordenado
- Input 876543210 -> Está ordenado
- Input 152456457 -> Não está ordenado
- Input 12356789 -> Não está ordenado
- Input 13579 -> Não está ordenado
- Input 9765421 -> Não está ordenado
- Input 123454321 -> Não está ordenado
- Input 12222222 -> Está ordenado
- Input 2111111 -> Está ordenado
- Input 1599 -> Não está ordenado.

**2 - Crie uma função que receba um array de inteiros como parâmetro e verifique se neste array existem números duplicados, caso exista, retorne um novo array com os valores que se repetem**

Exemplo:
Input [4,5,44,98,4,5,6,7] → Output [4,5]

**3 - Crie uma função que recebe uma string com qualquer sequência dos seguintes caracteres '[', '{', '(', ')', '}', ']' e retorne se a sequência é uma sequência válida ou não. Uma sequência é válida se as chaves, parênteses e colchetes abrem e fecham corretamente**

Exemplo:
{ [ ( ) ( ) { } [ ] ] { } } é uma sequência válida
{ [ ( ( ) ] } não é uma sequência válida (Há um parêntese posicionado incorretamente)
{ } [ ] ( ) é uma sequência válida
( ( ) { } [ [ ] ) não é uma sequência válida (Há uma chave posicionado incorretamente) [ { } ( [ ) ] ] não é uma sequência válida (O número de caracteres está correto, mas o posicionamento de uma chave/parêntese está incorreto)

Dica: Os espaços nos exemplos são apenas para favorecer a leitura.
Espaços não farão parte das strings de teste
