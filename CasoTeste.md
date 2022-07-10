# CASOS DE TESTE

## TESTES DE ENTRADA
### Caso 1: Caso Médio
1.  Quantos elementos serão colocados (Max. - 25):  `5`;
2.  Entrada de 5 elementos: `22 5 -19 63 1`;
3.  Saída Esperada: `-19 1 5 22 63`.

### Caso 2: Melhor Caso
1.  Quantos elementos serão colocados (Max. - 25): `5`;
2.  Entrada de 5 elementos: `9 -8 5 11 17`;
3.  Saída Esperada: `-8 5 9 11 17`.

### Caso 3: Pior Caso
1.  Quantos elementos serão colocados (Max. - 25): `5`;
2.  Entrada de 5 elementos: `0 1 2 3 4`;
3.  Saída Esperada: `0 1 2 3 4`;

## EXPLICADO CADA CASO
### Caso 1
  Nesse caso, uma mistura de escolhas de _pivot_ ruins e boas escolhas de _pivot_ ocorrem.
### Caso 2
  Nesse caso, a escolha do _pivot_ é sempre feita de forma, que ele fique no centro do _array_.
### Caso 3
  Nesse último caso, a escolha do _pivot_ sempre ocorre de forma que os _sub-arrays_ fiquem um com n-1 elementos e outro com 0 elementos.
  
