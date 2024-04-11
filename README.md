# Grafos 1 - LeetCode

**Número da Lista**: 1<br>
**Conteúdo da Disciplina**: Grafos1<br>

## Alunos
|Matrícula | Aluno |
| -- | -- |
| 18/0097181  |  Ana Beatriz Santos |
| 20/0023748  |  Marcos Santos Bittar |

## Sobre 
Repositório com resoluções de problemas de grafos do [LeetCode](https://leetcode.com/) e do [CSES](https://cses.fi/problemset/task/1192).

## Apresentação 

## Screenshots

## Exercicio 1 - Clone Graph

Dificuldade: Médio <br>
Link: [Clone Graph](https://leetcode.com/problems/clone-graph/description/)<br>
Solução: [Código](assets/codes/clone_graph.c)<br>
Para resolver esse exercício foi realizada a busca em profundidade (DFS) para percorrer o grafo original, criando uma cópia à medida que avançava. 

![](assets/img/ex1.png)

## Exercicio 2 - Counting Rooms

Dificuldade: difícil <br>
Link: [Counting Rooms](https://cses.fi/problemset/task/1192)<br>
Solução: [Código](assets/codes/countingRooms2.cpp)<br>
Para resolver esse exercício foi realizada a busca em Largura (bfs) para percorrer a entrada, que foi salva em uma matriz de caracteres. Além disso, para controlar quais dos vértices haviam sido visitados foi utilizada uma matriz de inteiros, contendo 1 para vértices visitados e 0 para vértices não visitados. Finalmente, para saber se a entrada era ou não um vértice analisáva-se o código ascii do caracter na matriz de caracteres, dado que os pontos "." eram vértices e os jogos da velha "#", na prática, não existiam

![](assets/img/ex2.png)

## Instalação 
**Linguagem**: C<br>

Você precisará de um compilador C/C++ instalado em seu sistema para utilizar o código localmente ou apenas criar uma conta no [LeetCode](https://leetcode.com/).

## Uso 
Para executar o trabalho basta abrir o link do exercício e copiar e colar o código. Se for utilizar localmente siga os seguintes comandos:

`gcc -o nomeArquivo nomeArquivo.c`

`./nomeArquivo`



