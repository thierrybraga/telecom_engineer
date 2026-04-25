---
tags: [computação, algoritmos, programação, estruturas de dados]
semestre: 1
area: Computação
creditos: 4
dificuldade: media
importancia: alta
status: completo
links: [Algoritmos II, Sistemas Digitais, Microprocessadores]
aliases: [Algoritmos_I]
keywords: [computação, algoritmos, programação, estruturas de dados]
---

# Algoritmos e Estrutura de Dados I

## 1. Ementa Expandida
Introdução ao pensamento computacional e à organização de dados na memória. Fundamentos de lógica de programação, tipos abstratos de dados e estruturas lineares clássicas. Base para automação, scripting e desenvolvimento de ferramentas em telecomunicações.

## 2. Blocos Teóricos

### 2.1 Lógica de Programação e Pseudocódigo
- Sequência, seleção (`if/else`, `switch`) e repetição (`for`, `while`, `do-while`)
- Funções e procedimentos: escopo, parâmetros, retorno
- Recursão: pilha de chamadas, caso base, caso recursivo
- Pseudocódigo e fluxogramas

### 2.2 Tipos de Dados Primitivos e Abstratos
- Inteiros, ponto flutuante, caracteres, booleanos
- Strings e manipulação
- TAD (Tipo Abstrato de Dados): separação entre interface e implementação
- Enumerações e registros

### 2.3 Arrays e Matrizes
- Alocação estática vs. dinâmica
- Acesso por índice: O(1)
- Busca linear: O(n)
- Matrizes bidimensionais e multidimensionais
- Operações com arrays

### 2.4 Listas Ligadas
- Lista simplesmente ligada: nó, ponteiro `next`, cabeça
- Lista duplamente ligada: ponteiros `prev` e `next`
- Lista circular
- Operações: inserção, remoção, busca — complexidade O(n)
- Comparação com arrays

### 2.5 Pilhas (Stack)
- Princípio LIFO (Last In, First Out)
- Operações: `push`, `pop`, `peek`, `isEmpty`
- Implementação com array ou lista ligada
- Aplicações: pilha de chamadas, análise de expressões, undo/redo

### 2.6 Filas (Queue)
- Princípio FIFO (First In, First Out)
- Operações: `enqueue`, `dequeue`, `front`, `isEmpty`
- Fila circular
- Fila de prioridade (introdução)

### 2.7 Introdução a Árvores
- Conceitos: raiz, folha, nó interno, altura, profundidade
- Árvore binária: propriedades e percursos (in-order, pre-order, post-order)
- Árvore Binária de Busca (BST): inserção, remoção, busca — O(log n) médio

### 2.8 Algoritmos de Busca e Ordenação
- Busca: linear O(n), binária O(log n)
- Ordenação elementar: Bubble Sort, Selection Sort, Insertion Sort — O(n²)
- Ordenação eficiente: Merge Sort, Quick Sort — O(n log n)
- Estabilidade de algoritmos de ordenação

### 2.9 Complexidade de Algoritmos (Big O)
- Notações: O, Ω, Θ
- Análise de pior caso, melhor caso e caso médio
- Tabela de complexidades comuns: O(1), O(log n), O(n), O(n log n), O(n²)
- Análise assintótica

## 3. Aplicações em Telecom

### 3.1 Processamento de Dados em Telecom
- Parsing de logs e arquivos de configuração
- Manipulação de pacotes de rede
- Estruturas para tabelas de roteamento
- Filas de processamento em sistemas de telecom

### 3.2 Automação e Scripting
- Scripts para configuração de equipamentos
- Processamento de dados de monitoramento
- Estruturas para análise de tráfego

## 4. Prática/Laboratório
- Implementação de estruturas de dados em C/C++
- Resolução de problemas de programação
- Análise de complexidade de algoritmos
- Projetos de automação de tarefas

## 5. Bibliografia

### Bibliografia Básica
- CORMEN, T. H. et al. **Algoritmos: Teoria e Prática**. 3. ed. Elsevier, 2012.
- SEDGEWICK, R.; WAYNE, K. **Algorithms**. 4. ed. Addison-Wesley, 2011.
- ZIVIANI, N. **Projeto de Algoritmos com Implementações em Pascal e C**. Thomson, 2004.

### Bibliografia Complementar
- DROZDEK, A. **Estrutura de Dados e Algoritmos em C**. 2. ed. Cengage Learning, 2016.
- TENENBAUM, A. M. **Estruturas de Dados Usando C**. Pearson, 1995.

## 6. Outputs Esperados
- Domínio de lógica de programação
- Implementação de estruturas de dados lineares
- Análise de complexidade de algoritmos
- Resolução de problemas computacionais
- Fundamentos para estruturas avançadas e algoritmos de grafos
