# Algoritmo de Luhn
## O que é
O algoritmo Luhn , também conhecido como o " módulo de 10" , em homenagem a seu criador, IBM cientista Hans Peter Luhn , é uma simples soma de verificação fórmula utilizada para validar uma variedade de números de identificação, tais como crédito números de cartão.

## Código
O codigo foi divido em 3 partes para melhor entendimento e funcionamento.

### 1. Transformação dos valores em inteiro.
No início do código inserimos os números do cartão para realizar a validação, porém devido ao tipo de método inserido não será possível utilizar os valores na lista. Por isso utilizamos o método para converter os valores.

### 2. Função de Luhn.
Em seguida aplicamos o algoritmo de Luhn. Para isso iremos reverter a lista e começar a pegar os números de 2 em 2, depois iremos pegar esses valores, dobrá-los e caso tenha valores maiores que 9 pegaremos esses valores e subtraimos 9 e adicionaremos a lista e depois iremos soma-los. Para que o algoritmo valide o cartão a soma desses valores terá que ser um muliplo de 10.

### 3. Indentificação da bandeira.
Nessa parte iremos  identificar a bandeira do cartão inserido, por meio de vários IF ELSE. Identificaremos as bandeiras da AMEX com início 34 ou 37, a bandeira VISA com início 4 e a bandeira MASTERCARD com início 51, 52, 53, 54 ou 55. Se o cartão não for de nenhuma dessas bandeiras, ele mostrará como cartão inválido.
