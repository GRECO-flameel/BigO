**1- Complexidade:**

O(1)
A função apenas verifica se a lista está vazia e retorna o primeiro elemento. Essas duas operações (len(lista) e lista[0]) acontecem em tempo constante e não dependem do tamanho da lista n. Portanto, mesmo que a lista tenha 10 ou 1 milhão de elementos, o tempo de execução permanece o mesmo.


**2- Complexidade:**

O(n)
Justificativa:
A função percorre todos os elementos da lista para conseguir somá-los. Isso acontece por causa do for, que passa por cada item da lista uma vez. Dessa forma, quanto maior for a lista, mais operações serão realizadas. Por isso, o tempo de execução cresce de acordo com o tamanho da entrada n.


**3- Complexidade:**

O(log n)
Justificativa:
A cada repetição do while, o algoritmo divide o tamanho da lista pela metade para continuar a busca. Em vez de verificar todos os elementos, ele elimina metade das possibilidades a cada passo. Por isso, mesmo que a lista seja muito grande, o número de operações cresce lentamente em relação ao tamanho da entrada n.


**4- Complexidade:**

O(n^2)
Justificativa:
A função usa dois loops for aninhados para comparar pares de elementos da lista. O primeiro loop percorre cada elemento, e o segundo verifica todos os elementos que vêm depois dele. Assim, conforme o tamanho da lista aumenta, o número de comparações cresce rapidamente, aproximadamente proporcional ao quadrado de n.


**5- Complexidade:**

O(n^2)
Justificativa:
A função primeiro percorre a lista uma vez para imprimir os elementos, o que tem custo O(n). Depois, usa dois loops aninhados para formar todos os pares possíveis da lista, o que gera O(n^2). Como essa parte cresce mais rápido, ela define a complexidade final do algoritmo.


**6- Complexidade:**

O(log n)
Justificativa:
A cada repetição do while, o valor de i é multiplicado por 2. Isso faz com que o número de repetições cresça lentamente em relação ao valor de n, já que o valor dobra a cada passo. Por causa disso, a quantidade de execuções do loop é proporcional ao logaritmo de n.


**7- Complexidade:**

O(2^n)
Justificativa:
A função calcula o Fibonacci usando recursão e, a cada chamada, cria duas novas chamadas da própria função (n-1 e n-2). Isso faz com que o número de chamadas cresça muito rápido conforme n aumenta. Por causa dessa duplicação constante de chamadas, o tempo de execução cresce de forma exponencial.


**8- Complexidade:**

O(n^2)
Justificativa:
O algoritmo usa dois loops for para percorrer a lista várias vezes e comparar elementos vizinhos. A cada passagem, ele verifica quase todos os elementos novamente para garantir que estejam na ordem correta. Por causa dessas repetições dentro de repetições, o número de operações cresce aproximadamente proporcional ao quadrado de n.


**9- Complexidade:**

O(n^3)
Justificativa:
A função utiliza três loops for aninhados para calcular o produto das matrizes. Cada loop percorre n posições, fazendo com que o número total de operações seja proporcional a n × n × n. Por isso, o tempo de execução cresce de forma cúbica em relação ao tamanho n das matrizes.


**10- Complexidade:**

O(n log n)
Justificativa:
O algoritmo divide a lista em duas partes menores usando recursão até chegar em listas de tamanho 1. Depois, ele junta essas partes novamente de forma ordenada. Como a lista é dividida em níveis logarítmicos e em cada nível todos os elementos são percorridos, o tempo total de execução resulta em O(n log n).

