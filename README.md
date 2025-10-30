Funções nomeadas:
As funções soma(a, b), sub(a, b), mult(a, b) e div(a, b) realizam as quatro operações matemáticas básicas. Cada uma 
recebe dois parâmetros numéricos e retorna o resultado da operação correspondente.
Exemplo: soma(14, 7) → retorna 21.

Função anônima:
A função const par = function (numeros) é uma função sem nome atribuída a uma variável. Ela recebe um array de 
números e utiliza o método .filter() para retornar apenas os números pares.
Exemplo: par([1,2,3,4]) → retorna [2,4].

Arrow function:
A função const calcularMedia = (numeros) => { ... } utiliza a sintaxe moderna de arrow function (=>). 
Ela recebe um array e usa o método .reduce() para somar os elementos e calcular a média.
Exemplo: calcularMedia([1,2,3,4]) → retorna 2.5.

Função com callback:
A função executarOperacao(a, b, operacao) demonstra o uso de callbacks, recebendo outra função como parâmetro. 
O parâmetro operacao define o tipo de cálculo a ser realizado, permitindo flexibilidade no código.
Exemplo: fazerrOperacao(8, 2, (x, y) => x ** y) → realiza exponenciação e retorna 64.
