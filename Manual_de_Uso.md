# TrabalhoFinalQuickSort
Repositório criada para publicação do programa criado para entrada e testes do caso de QuickSort

O programa aqui apresentado é uma tradução e edição do código apresentado em: https://hackr.io/blog/quick-sort-in-c
Os créditos por criação e interpretação do programa são do criador original;

### O Algoritmo apresentado funciona seguindo os seguintes passos. 

1.  Começamos a função `main` antes de `quicksort` ser chamado, o usuário insere quantos elementos serão dados como entrada para serem organizados.
2.  É guardado um _array_ de até 25 elementos no máximo, nós guardamos o primeiro e último elemento nas variáveis `first` e `last` e então chamamos a função `quicksort`.
3.  Se o primeiro elemento for menor que o último, `first` é definido como o _pivot_.
4.  É então chamado um laço `while` que que aumenta `i` e decrementa `j` de acordo com sua relação com o _pivot_. Isso verifica quais os elementos maiores e menores que o _pivot_ e divide o _array_ em dois _sub-arrays_, que é passo de **partição**.
5.  A função `quicksort`é então chamada recursivamente para organizar os dois _sub-arrays_ até o vetor inteiro estar organizado.
6.  O vetor agora organizado é mostrado na tela como saída.
