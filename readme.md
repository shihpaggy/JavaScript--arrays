# formas de manipular arrays:

`concat()`
> junta dois arrays; Não altera o array no qual foi chamado, então precisamos salvar esse resultado em um novo array

`filter()`
> retorna uma lista contando elementos que passam de um teste; Não altera o array onde foi chamado, então precisamos salvar esse resultado em um novo array

`find()`
> retorna apenas o primeiro valor que satisfaz o teste

`findIndex()`
> retorna o índice do find()

`indexOf()`
> localiza e retorna o indice da primeira ocorrencia

`lastIndexOf()`
> da mesma forma que indexOf, porem retorna da ultima ocorrencia

`forEach()`
> executa uma função em cada elemento do array de forma individual; Não altera o array original e nem retorna um valor

`pop()`
> altera array original removendo o ultimo elemento

`shift()`
> altera array original removendo o primeiro elemento e renumera os indices perm

`push()`
> altera array original adicionando o elemento na lista em ultima posicao

`unshift()`
> igual ai push(), porem adiciona na primeira posicao e renumera os indices

`reduce()`
> Utiliza uma função definida pelo usuário em cada um dos elementos, guardando o resultado em uma variável que pode ser acessada dentro da função que foi definida, retornando um único valor no final

`reduceRight()`
> igual o reduce() porém começa do final do array e segue até o início

`reverse()`
> inverte a ordem dos elementos do array

`slice()`
> copia uma parte do array para outro array

`sort()`
> organiza o array; números vêm antes das letras

`splice()`
> remover, um ou mais elementos consecutivos caso o segundo parâmetro tenha um valor maior que 0, e incluir um ou mais elementos a partir de um índice escolhido
