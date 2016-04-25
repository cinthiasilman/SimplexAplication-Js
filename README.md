# SimplexAplication-Js
Repositório para a implementação do algoritmo Simplex.

O Simplex permite que se encontre valores ideais em situações em que diversos aspectos precisam ser respeitados. Diante de um problema, são estabelecidas inequações que representam restrições para as variáveis. A partir daí, testa-se possibilidades de maneira a otimizar, isto é, maximizar ou minimizar o resultado da forma mais rápida possível.

O Método Simplex procura encontrar uma solução que não possua soluções vizinhas melhores que ela. Ela procura a solução ótima. A solução ótima pode não existir em dois casos: quando não há nenhuma solução viável para o problema, devido a restrições incompatíveis; ou quando não há máximo (ou mínimo), isto é, uma ou mais variáveis podem tender a infinito e as restrições continuarem sendo satisfeitas, o que fornece um valor sem limites para a função objetivo.

O algoritmo pode ser definido em três partes:

1) Inicialização (o algoritmo prepara os dados de entrada)

2) Iteração (o algoritmo repete diversar vezes o procedimento e faz com que a otimização do modelo seja alcançada)

3) Regra de parada (o algoritmo avalia se a solução ótima foi obtida ou se é impossível obtê-la)

Passo a passo:

-Digite a quantidade máxima de iterações do algoritmo.

-Informe se maximizará ou minimizará o resultado.

-Digite a função Z, que será a função objetivo.  

-Digite todas as restrições para a função.

O algoritmo criará as variáveis de folga para transformar as desigualdades das restrições em igualdades. Criará o quadro do SIMPLEX.

Quem entrará na base?
 - O menor coeficiente que pode ser encontrado na linha da função objetivo.

Quem sairá da base?
 - O algoritmo dividirá os elementos da última coluna pelos correspondentes elementos positivos da coluna da variável que irá entrar na base. O menor quociente será a variável que sairá.

Transformação da Matriz: operações para tornar a coluna do pivô em um vetor identidade.

A condição de parada ocorrerá quando toda a linha Z for maior ou igual a 0.

Ao chegar na condição de parada, mostrará o resultado ideal para cada tipo de variável.

Apresentará a Análise de Sensibilidade que serve para investigar o efeito sobre a solução ótima fornecida pelo método Simplex.


