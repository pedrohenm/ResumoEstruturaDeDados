# Pilhas 
### Conceito:
  Estrutura de dados do tipo LIFO ( last-in first-out ), em que o ultimo elemento inserido, será o ultimo a sair. Com isso, permite o acesso a um único item de dados ( o ultimo ). Para acessa o penúltimo tem que tirar o ultimo.

#### Exemplos: 

•	Funções recursivas em compiladores;

•	Mecanismos de desfazer/refazer dos editores de texto;

•	Navegação entre páginas WEB;

  A implementação pode ser feita através de um vetor ou através de listas encadeadas. Manipulação é realizada em uma das extremidades, topo e base
Operações com pilhas:
Podem ser representadas como uma pilha de pratos ou cartas de baralho
Passos:

•	Criação da pilha informando a capacidade – vetor

•	Empilhar ( push ) – elemento = parâmetro

•	Desempilhar ( pop );

•	Mostrar o topo;

•	Verificar se a pilha está vazia ( isEmpty );

•	Verificar se a pilha está cheia ( isFull  );


# Listas
#### Conceito:
Listas são conjuntos de elementos, objetos, variáveis, tarefas, ou qualquer coisa que se possa enumerar e formar um conjunto
Implementação: 
Listas em Arrays e Encadedas, Duplamente Encadeadas

Arrays: cada elemento da lista deve ser colocado em uma posição no array
        Ao inserir ou excluir um elemento, talvez seja necessário realocar todos os demais elementos

Encadeadas: Cada nó ou elemento de uma lista encadeada irá possuir o valor do nó e o endereço do próximo nó. Em uma lista encadeada                 linear o ultimo elemento aponta para NULL .

Duplamente Encadeadas: uma estrutura de dados ligada que consiste de um conjunto de registros sequencialmente ligados chamados de nós e                       é uma extensão da lista simplesmente ligada

# Memória
### Conceito:
Quando um programa inicia sua execução, ele começa a solicitar memória ao sistema operacional, Nem sempre a memória alocada na iniciação do programa é suficiente, então o programa também precisa alocar memória durante a sua execução.

• **Alocação Estática de Memória:**
O espaço de memória, é definido no processo de compilação. Não sendo possível alterar o tamanho desse espaço durante a execução do
programa. Utilizado quando se sabe a quantidade de memória que será utilizada pelo programa. 

• **Alocação Dinâmica de Memória:**
o espaço de memória, é definido enquanto o programa está em execução. Quando não se sabe ao certo quanto de memória será
necessário para o armazenamento das informações.
