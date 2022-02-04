# Curso Aprenda o que são estrutura de dados:

### Conteúdo do curso separado no mapa abaixo:

1- O que são estrutura de dados , Algoritmo

2- Operações básicas e Principais estruturas

3- Vetores e Matriz

4- Registro e Listas

5- Lista Ligada e duplamente ligada

6- Pilhas

7- Filas, Arvores, Hash

8- Hash

9- Grafos

-------------------------------------------------------------------------------------------------------------------------------------------

### O que são estrutura de dados:

Estrutura de dados é uma estrutura organizada de dados na memória de um computador ou em qualquer dispositivo de armazenamento, de forma que os dados possam ser utilizados de forma correta.

Essas estruturas encontram muitas aplicações no desenvolvimento de sistemas, sendo que algumas são altamente especializadas e utilizadas em tarefas específicas. Usando as estruturas adequadas através de algoritmos, podemos trabalhar com uma grande quantidade de dados, como aplicações em bancos de dados ou serviços de busca.

### Algoritmo:

Um algoritmo é um conjunto de instruções estruturadas e ordenadas, seu objetivo é realizar uma tarefa ou operação específica.

Os algoritmos são utilizados para manipular dados nas estruturas de várias formas, como por exemplo: inserir, excluir, procurar e ordenar dados.

### Estrutura de dados operações básicas

- Inserir dados
- Excluir dados
- Localizar um elemento
- Percorrer todos os itens constituintes da estrutura para visualização.
- Classificar, que se resume em colocar os itens de dados em uma determinada ordem (numéricas, alfabéticas, etc...)

### Principais Estruturas de dados:

- Vetores e Matrizes
- Registros
- Lista
- Pilha
- Fila
- Árvore
- Tabela hash
- Grafos

### Vetores e Matrizes (ou Arrays)

#### Vetor:

São estruturas de dados simples que podem auxiliar quando há muitas variáveis do mesmo tipo em algoritmo.

Vetor ou array uni-dimensional é uma variável que armazena várias variáveis do mesmo tipo.

O vetor é uma estrutura de dados indexada, que pode armazenar uma determinada quantidade de valores do mesmo tipo.

#### Matriz ou array multi-dimensional:

É um vetor de vetores. <u>ma matriz é um vetor que possui duas ou mais dimensões.

### Registro:

Enquanto arrays nos permite armazenar vários dados de um único tipo de dados, o registro nos permite armazenar mais de um tipo de dado.

Um registro é composto por campos que especificam cada uma das informações que o compõem.

Toda estrutura de registro tem um nome (ex:livro), e seus campos podem ser acessados por meio do uso do operador ponto(.). Por exemplo: para acessar o preço de um livro, poderíamos utilizar a seguinte declaração: livro.preco

### lista:

A diferença entre lista e arrays é a de que as listas possuem tamanhos ajustáveis, enquanto arrays possuem tamanho físico.

#### Existem 2 tipos de lista:

- Ligadas 
- Duplamente ligadas

#### Ligadas:

Nas estruturas do tipo lista existem os nós onde cada um dos nós conhece o valor que está sendo armazenado em seu interior além de conhecer o elemento posterior a ele: por isso ela é chamada de "lista ligada", pois os nós são amarrados com essa indicação de qual é o proximo nó.

#### Duplamente ligadas:

A diferença das listas duplamente ligadas para as ligadas é que elas são bidirecionais. Vimos que naturalmente não conseguimos andar para trás em listas ligadas, pois os nós de uma lista ligada sabem somente quem é o próximo elemento. Nas listas duplamente ligadas, os nós sabem quem é o próximo elemento e também quem é o elemento anterior, o que permite a navegação reversa. 

### Pilhas:

Pilha = stack

Uma Pilha é uma estrutura de dados que serve como uma coleção de elementos, e permite o acesso a somente um item de dados armazenados.

O acesso aos itens de uma Pilha é restrito somente um item pode ser lido ou removido por vez.

#### Tipos de Pilhas:

- LIFO ou UEPS
- FIFO ou PEPS

#### LIFO ou UEPS

Apresenta o seguinte critério: o primeiro elemento a ser retirado é o último que tiver sido inserido.

 #### FIFO ou PEPS

Apresenta o seguinte critério: o primeiro elemento a ser retirado é o primeiro que tiver sido inserido.

### Filas:

Admite remoção de elementos e inserção de novos sujeito à seguinte regra de operação:

O elemento removido é o que está na estrutura há mais tempo ou seja, o primeiro que tiver sido inserido na fila é também o primeiro a ser removido. Seguindo o conceito FIFO.

### Árvore:

É uma estrutura de dados que organiza seus elementos de forma hierárquica, onde existe um elemento que fica no topo da árvore, chamado de raiz e existem os elementos subordinados a ele, que são chamados de nós ou folhas.

Facilita a busca.

### Hash

Uma tabela hash, de dispersões ou espalhamento é uma estrutura de dados especial, que associa chaves de pesquisa a valores.

Uma tabela Hash é uma generalização da ideia de array, porém utiliza uma função denominada Hashing para espalhar os elementos fazendo com que os mesmos fiquem de forma não ordenada dentro do "array" que define a tabela.

##### Não Ordenado!

A tabela Hash permite associação de "valores a chaves".

- Valores: é a posição ou índice onde o elemento se encontra.
- Chave: parte da informação que compõe o elemento a ser manipulado.

Espalhar facilita a busca na estrutura de dados, pois a partir de uma chave podemos acessar de forma rápida uma posição do "array".

### Grafos:

Grafos são estruturas que permitem programar a relação entre objetos.

Os objetos são vértices ou "nós" do grafo.

Os relacionamentos são arestas

##### Todos os lados

