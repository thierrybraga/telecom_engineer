---
tags: [computação, programação, orientação a objetos, engenharia, software]
semestre: 3
area: Computação
creditos: 4
dificuldade: media
importancia: alta
código: CMP001
carga_horaria: 60h (4 créditos)
status: completo
pré_requisitos: [Algoritmos II]
links: [Microprocessadores, Redes Computadores, Sistemas Digitais]
aliases: [Programacao_Orientada_Objetos]
keywords: [computação, programação, orientação a objetos, engenharia, software]
resumo: "Estudo dos fundamentos e aplicações da programação orientada a objetos: conceitos de classes, objetos, herança, polimorfismo, encapsulamento, tratamento de exceções, coleções e interfaces gráficas."
---

# Programação Orientada a Objetos

## 1. Ementa Oficial

Estudo dos fundamentos e aplicações da programação orientada a objetos: conceitos de classes, objetos, herança, polimorfismo, encapsulamento, tratamento de exceções, coleções e interfaces gráficas. Desenvolvimento de aplicações utilizando linguagem orientada a objetos.

### Objetivos da Disciplina

**Objetivo Geral:**
Capacitar o estudante a desenvolver programas utilizando o paradigma de programação orientada a objetos, aplicando conceitos fundamentais e boas práticas de desenvolvimento de software.

**Objetivos Específicos:**
- Compreender os conceitos fundamentais da orientação a objetos
- Desenvolver classes e objetos utilizando encapsulamento
- Aplicar herança e polimorfismo em projetos de software
- Utilizar tratamento de exceções
- Trabalhar com coleções e estruturas de dados
- Desenvolver interfaces gráficas simples
- Aplicar padrões de projeto básicos
- Desenvolver projetos de software orientado a objetos

---

## 2. Conteúdo Programático

### Unidade 1: Introdução à Orientação a Objetos (10h)

#### 1.1 Paradigmas de Programação
- Paradigma procedural vs orientado a objetos
- Histórico e evolução da POO
- Linguagens orientadas a objetos (Java, C++, Python, C#)
- Vantagens da POO
- Aplicações em engenharia

#### 1.2 Conceitos Fundamentais
- Classes e objetos
- Atributos e métodos
- Estado e comportamento
- Instanciação
- Construtores e destrutores
- Palavra-chave this/self

#### 1.3 Encapsulamento
- Modificadores de acesso (public, private, protected)
- Getters e setters
- Propriedades
- Ocultação de informação
- Coesão e acoplamento
- Benefícios do encapsulamento

---

### Unidade 2: Herança e Polimorfismo (12h)

#### 2.1 Herança
- Conceito de herança
- Superclasse e subclasse
- Palavra-chave extends/:
- Herança simples e múltipla
- Construtores em herança
- Sobrescrita de métodos (@Override)
- Classe Object (raiz da hierarquia)

#### 2.2 Polimorfismo
- Conceito de polimorfismo
- Polimorfismo de inclusão
- Polimorfismo ad-hoc (sobrecarga)
- Ligagem dinâmica (late binding)
- Type casting
- instanceof/typeof
- Benefícios do polimorfismo

#### 2.3 Classes Abstratas e Interfaces
- Classes abstratas
- Métodos abstratos
- Interfaces
- Implementação de interfaces
- Diferença entre classe abstrata e interface
- Herança múltipla via interfaces

---

### Unidade 3: Tratamento de Exceções e E/S (10h)

#### 3.1 Exceções
- Conceito de exceção
- Hierarquia de exceções
- Try-catch-finally
- Throw e throws
- Exceções checked e unchecked
- Criação de exceções customizadas
- Boas práticas no tratamento de exceções

#### 3.2 Entrada e Saída
- Streams de entrada e saída
- Leitura e escrita de arquivos
- Serialização de objetos
- Manipulação de arquivos texto e binários
- Try-with-resources
- Classe File/Path

---

### Unidade 4: Coleções e Estruturas de Dados (10h)

#### 4.1 Framework de Coleções
- Hierarquia de coleções
- Interface Collection
- Listas (ArrayList, LinkedList)
- Conjuntos (HashSet, TreeSet)
- Mapas (HashMap, TreeMap)
- Filas e pilhas (Queue, Stack)
- Iteradores

#### 4.2 Generics
- Conceito de generics
- Classes genéricas
- Métodos genéricos
- Wildcards
- Type erasure
- Benefícios dos generics

#### 4.3 Algoritmos e Utilitários
- Ordenação (Comparable, Comparator)
- Busca binária
- Collections utility class
- Arrays utility class
- Complexidade de algoritmos

---

### Unidade 5: Interfaces Gráficas e Eventos (10h)

#### 5.1 Programação GUI
- Bibliotecas gráficas (Swing, JavaFX, Tkinter, etc.)
- Componentes básicos (JFrame, JPanel, JButton, JLabel)
- Layouts (BorderLayout, FlowLayout, GridLayout)
- Containers
- Look and feel

#### 5.2 Programação Orientada a Eventos
- Modelo de eventos
- Listeners e handlers
- Eventos de mouse e teclado
- Inner classes e anonymous classes
- Lambda expressions
- MVC básico

#### 5.3 Aplicações Gráficas
- Formulários e diálogos
- Validação de entrada
- Atualização dinâmica de interface
- Threads e interface gráfica
- Aplicações desktop simples

---

### Unidade 6: Padrões de Projeto e Tópicos Avançados (8h)

#### 6.1 Padrões de Projeto (Design Patterns)
- Conceito de padrões de projeto
- Padrão Singleton
- Padrão Factory
- Padrão Observer
- Padrão Strategy
- Introdução a outros padrões (MVC, DAO)

#### 6.2 Tópicos Avançados
- Classes aninhadas e internas
- Enumerations (enum)
- Anotações (annotations)
- Reflexão (reflection)
- Programação funcional (streams, lambdas)
- Documentação com Javadoc/docstrings

#### 6.3 Boas Práticas
- Convenções de nomenclatura
- Organização de pacotes
- Princípios SOLID (introdução)
- Testes unitários básicos
- Versionamento com Git
- Documentação de código

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Desenvolvimento de Software
- **Aplicações de telecom**: Gerenciadores de configuração
- **Simuladores**: Simulação de sistemas de comunicação
- **Análise de dados**: Processamento de logs e métricas
- **Automação**: Scripts para testes e deploy
- **Ferramentas internas**: Dashboards e monitoramento

### 3.2 Sistemas Embarcados
- **Firmware**: Programação de dispositivos de telecom
- **Drivers**: Interfaces com hardware de rede
- **Protocolos**: Implementação de stacks de comunicação
- **Roteadores e switches**: Software de controle
- **IoT**: Programação de dispositivos conectados

### 3.3 Redes e Protocolos
- **Implementação de protocolos**: TCP/IP, custom protocols
- **Servidores**: Aplicações servidoras de rede
- **Clientes**: Aplicações clientes
- **Parsing**: Análise de pacotes e mensagens
- **Sockets**: Programação de rede orientada a objetos

### 3.4 Processamento de Sinais
- **Aplicações DSP**: Implementação de algoritmos
- **Visualização**: Gráficos e análise de sinais
- **Processamento em tempo real**: Aplicações multithread
- **Simulações**: Modelagem de sistemas

### 3.5 Projetos de Engenharia
- **Gestão de projetos**: Ferramentas de acompanhamento
- **Documentação**: Sistemas de documentação técnica
- **Integração**: APIs e web services
- **Banco de dados**: Persistência de dados de projetos

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Exposição de conceitos com exemplos
- **Aulas práticas**: Exercícios de programação em laboratório
- **Projetos**: Desenvolvimento de aplicações completas
- **Code reviews**: Análise coletiva de código
- **Pair programming**: Programação em duplas
- **Seminários**: Apresentação de projetos

### 4.2 Recursos Didáticos
- Laboratório de computação com IDEs instaladas
- Ambiente de desenvolvimento integrado (IDE)
- Compiladores e ferramentas de build
- Sistema de versionamento (Git)
- Plataforma de exercícios online
- Material didático digital
- Projetor e quadro

### 4.3 Avaliação

**Instrumentos:**
- Provas teórico-práticas (2 avaliações) - 40%
- Projetos de programação - 40%
- Exercícios práticos - 15%
- Participação - 5%

**Critérios:**
- Domínio dos conceitos de orientação a objetos
- Capacidade de desenvolver classes e objetos
- Aplicação correta de herança e polimorfismo
- Uso adequado de tratamento de exceções
- Conhecimento de coleções e estruturas de dados
- Qualidade do código (organização, documentação)
- Funcionalidade das aplicações desenvolvidas

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Introdução à POO. Classes e objetos |
| 2 | Atributos, métodos e encapsulamento |
| 3 | Construtores e modificadores de acesso |
| 4 | Herança: conceitos e implementação |
| 5 | **1ª Avaliação** |
| 6 | Polimorfismo e sobrescrita |
| 7 | Classes abstratas e interfaces |
| 8 | Tratamento de exceções |
| 9 | Entrada e saída de dados |
| 10 | **2ª Avaliação** |
| 11 | Coleções: Listas, conjuntos e mapas |
| 12 | Generics e algoritmos |
| 13 | Interfaces gráficas (GUI) |
| 14 | Eventos e programação orientada a eventos |
| 15 | Padrões de projeto. Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. DEITEL, P.; DEITEL, H. **Java: Como Programar**. 10. ed. Pearson, 2016.
2. SIERRA, K.; BATES, B. **Use a Cabeça! Java**. 2. ed. Alta Books, 2007.
3. HORSTMANN, C. S. **Core Java, Volume I: Fundamentals**. 11. ed. Prentice Hall, 2018.

### Bibliografia Complementar
4. BLOCH, J. **Effective Java**. 3. ed. Addison-Wesley, 2018.
5. GAMMA, E. et al. **Padrões de Projeto: Soluções Reutilizáveis de Software Orientado a Objetos**. Bookman, 2000.
6. SEDGWICK, R.; WAYNE, K. **Introduction to Programming in Java: An Interdisciplinary Approach**. Addison-Wesley, 2007.
7. ECKEL, B. **Thinking in Java**. 4. ed. Prentice Hall, 2006.
8. MARTIN, R. C. **Código Limpo: Habilidades Práticas do Agile Software**. Alta Books, 2009.

### Recursos Online
- [Oracle Java Documentation](https://docs.oracle.com/en/java/) - Documentação oficial
- [Java Tutorials](https://docs.oracle.com/javase/tutorial/) - Tutoriais oficiais
- [LeetCode](https://leetcode.com/) - Exercícios de programação
- [HackerRank](https://www.hackerrank.com/) - Desafios de código
- [Stack Overflow](https://stackoverflow.com/) - Comunidade de programadores
- [GitHub](https://github.com/) - Repositórios de código

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Compreender e aplicar os conceitos fundamentais da programação orientada a objetos

**RA2** - Desenvolver classes bem encapsuladas com atributos e métodos apropriados

**RA3** - Aplicar herança e polimorfismo para reutilização e extensibilidade de código

**RA4** - Implementar tratamento de exceções para robustez de aplicações

**RA5** - Utilizar coleções e estruturas de dados eficientemente

**RA6** - Desenvolver interfaces gráficas simples com tratamento de eventos

**RA7** - Aplicar padrões de projeto básicos em soluções de software

**RA8** - Desenvolver projetos de software orientado a objetos seguindo boas práticas

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: Programação se aprende praticando. Não basta ler o código - escreva seus próprios programas desde o primeiro dia!

> 🏗️ **POO**: Pense em objetos como "coisas" do mundo real com características (atributos) e comportamentos (métodos). Isso torna o código mais natural.

> 🧬 **Herança**: "É um" vs "Tem um". Use herança para relações "é um" (cachorro É UM animal). Use composição para "tem um" (carro TEM UM motor).

> 🎭 **Polimorfismo**: Mesma interface, comportamentos diferentes. É a chave para código flexível e extensível.

> 🛡️ **Encapsulamento**: Proteja seus dados! Acesso controlado via getters/setters permite validação e mudanças internas sem afetar quem usa a classe.

> 🗃️ **Coleções**: Escolha a estrutura certa para o problema. ArrayList para acesso rápido, LinkedList para inserções, HashMap para busca por chave.

> 🔗 **Conexões**: Esta disciplina é fundamental para:
> - Desenvolvimento de software em geral
> - Microprocessadores (programação embarcada)
> - Redes de Computadores (protocolos, sockets)
> - Sistemas Digitais (simulação, VHDL)
> - Todos os projetos de engenharia que envolvam software

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025