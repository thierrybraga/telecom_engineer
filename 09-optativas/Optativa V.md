---
tags: [engenharia de software, desenvolvimento, metodologias, engenharia, telecomunicações, optativa]
semestre: 10
area: Optativas
creditos: 4
dificuldade: media
importancia: media
código: OPT005
carga_horaria: 60h (4 créditos)
status: completo
pré_requisitos: [Algoritmos II, Programacao Orientada Objetos]
links: [Optativa IV, Algoritmos II, Banco_de_Dados]
aliases: [Optativa_V]
keywords: [engenharia de software, desenvolvimento, metodologias, engenharia, telecomunicações, optativa]
resumo: "Estudo dos fundamentos da engenharia de software: processos de desenvolvimento, análise e especificação de requisitos, modelagem de sistemas, padrões de projeto, qualidade de software, testes, gestão de projetos e metodo"
---

# Optativa V: Engenharia de Software

## 1. Ementa Oficial

Estudo dos fundamentos da engenharia de software: processos de desenvolvimento, análise e especificação de requisitos, modelagem de sistemas, padrões de projeto, qualidade de software, testes, gestão de projetos e metodologias ágeis. Aplicações em desenvolvimento de sistemas para telecomunicações.

### Objetivos da Disciplina

**Objetivo Geral:**
Proporcionar ao estudante conhecimentos fundamentais de engenharia de software, capacitando-o a aplicar métodos, técnicas e ferramentas para o desenvolvimento sistemático de software de qualidade.

**Objetivos Específicos:**
- Compreender processos de desenvolvimento de software
- Aplicar técnicas de levantamento e análise de requisitos
- Utilizar modelagem UML para especificação de sistemas
- Conhecer e aplicar padrões de projeto (design patterns)
- Entender e implementar estratégias de testes de software
- Aplicar métricas e garantia da qualidade de software
- Conhecer metodologias ágeis e tradicionais de gestão de projetos
- Compreender DevOps e integração contínua

---

## 2. Conteúdo Programático

### Unidade 1: Fundamentos de Engenharia de Software (10h)

#### 1.1 Introdução à Engenharia de Software
- Definição e escopo da engenharia de software
- Crise do software e evolução histórica
- Princípios fundamentais
- Áreas de conhecimento (SWEBOK)
- Profissional de engenharia de software
- Ética na engenharia de software

#### 1.2 Processos de Desenvolvimento
- Modelo em cascata (waterfall)
- Modelo iterativo e incremental
- Modelo espiral
- Modelo V
- Prototipagem
- Desenvolvimento baseado em componentes
- Métodos formais
- Escolha do processo adequado

#### 1.3 Ciclo de Vida do Software
- Fases do desenvolvimento
  - Requisitos
  - Análise e projeto
  - Implementação
  - Testes
  - Implantação
  - Manutenção
- Evolução e envelhecimento de software
- Reengenharia
- Refactoring

---

### Unidade 2: Requisitos e Análise (12h)

#### 2.1 Engenharia de Requisitos
- Tipos de requisitos
  - Funcionais
  - Não-funcionais (desempenho, segurança, usabilidade)
  - Domínio
- Atividades da engenharia de requisitos
  - Elicitação
  - Análise
  - Especificação
  - Validação
  - Gerenciamento de mudanças

#### 2.2 Técnicas de Elicitação
- Entrevistas
- Questionários
- Observação
- Análise de documentos
- Prototipagem
- JAD (Joint Application Development)
- Brainstorming
- Workshops

#### 2.3 Especificação de Requisitos
- Documento de requisitos (SRS - Software Requirements Specification)
- Histórias de usuário (User Stories)
- Critérios de aceitação
- Casos de uso
- Regras de negócio
- Priorização de requisitos (MoSCoW, Kano)

#### 2.4 Modelagem de Requisitos
- Diagramas de caso de uso (UML)
- Diagramas de atividade
- User journey maps
- Story mapping
- Protótipos de baixa e alta fidelidade
- Ferramentas: Figma, Adobe XD, Balsamiq

---

### Unidade 3: Modelagem e Projeto de Software (12h)

#### 3.1 Modelagem UML
- Visões arquiteturais (4+1)
- Diagramas estruturais
  - Classes
  - Objetos
  - Componentes
  - Implantação
  - Pacotes
  - Estrutura composta
- Diagramas comportamentais
  - Sequência
  - Comunicação
  - Estados
  - Atividades
  - Timing
  - Visão geral de interação

#### 3.2 Padrões de Projeto (Design Patterns)
- **Padrões criacionais**
  - Singleton
  - Factory Method
  - Abstract Factory
  - Builder
  - Prototype
- **Padrões estruturais**
  - Adapter
  - Bridge
  - Composite
  - Decorator
  - Facade
  - Flyweight
  - Proxy
- **Padrões comportamentais**
  - Observer
  - Strategy
  - Command
  - Iterator
  - Template Method
  - State
  - Visitor
  - Mediator

#### 3.3 Arquitetura de Software
- Estilos arquiteturais
  - Camadas (layers)
  - Cliente-servidor
  - Pipeline
  - Event-driven
  - Microkernel
  - Microsserviços
- Padrões arquiteturais
  - MVC, MVP, MVVM
  - Clean Architecture
  - Hexagonal Architecture
  - Onion Architecture
- Documentação arquitetural (C4 Model, ADR)

---

### Unidade 4: Implementação e Qualidade (10h)

#### 4.1 Qualidade de Software
- Conceitos de qualidade
- Fatores de qualidade (McCall, Boehm, ISO/IEC 25010)
- Qualidade interna vs externa
- Garantia da qualidade de software (SQA)
- Auditoria e revisões
- Inspeções de código
- Análise estática de código
- Refactoring

#### 4.2 Métricas de Software
- Métricas de processo
- Métricas de projeto
- Métricas de produto
  - Tamanho (LOC, FP - Function Points)
  - Complexidade (ciclomática de McCabe)
  - Acoplamento e coesão
- Métricas orientadas a objetos
- Análise de pontos de função
- Estimativa de esforço (COCOMO, Planning Poker)

#### 4.3 Documentação de Software
- Tipos de documentação
- Documentação de código
- Documentação de API
- Documentação de usuário
- Wiki e knowledge base
- Ferramentas: Swagger, Confluence, Notion, Markdown

---

### Unidade 5: Testes de Software (10h)

#### 5.1 Fundamentos de Testes
- Objetivos do teste
- Princípios de testes
- Níveis de teste
  - Unitário
  - Integração
  - Sistema
  - Aceitação
- Tipos de teste
  - Funcionais
  - Não-funcionais
  - Estruturais
  - Regressão
- Pirâmide de testes

#### 5.2 Técnicas de Teste
- Teste de caixa-preta
  - Particionamento de equivalência
  - Análise de valor limite
  - Tabelas de decisão
  - Transição de estados
- Teste de caixa-branca
  - Cobertura de instruções
  - Cobertura de decisões
  - Cobertura de condições
  - Cobertura de caminhos
- Teste baseado em experiência
  - Error guessing
  - Exploratory testing

#### 5.3 Automação de Testes
- Testes unitários (JUnit, pytest, Jest)
- Testes de integração
- Testes de interface (Selenium, Cypress, Playwright)
- Testes de API (Postman, REST Assured)
- Testes de carga e performance (JMeter, k6)
- Testes de segurança (OWASP ZAP)
- TDD (Test-Driven Development)
- BDD (Behavior-Driven Development)

---

### Unidade 6: Gestão de Projetos e Metodologias Ágeis (6h)

#### 6.1 Gestão de Projetos de Software
- PMBOK e áreas de conhecimento
- Gerenciamento de escopo
- Gerenciamento de tempo (PERT, CPM)
- Gerenciamento de custos
- Gerenciamento de riscos
- Gerenciamento de stakeholders
- Ferramentas: MS Project, Jira, Trello, Monday

#### 6.2 Metodologias Ágeis
- Manifesto Ágil
- Princípios ágeis
- Scrum
  - Papéis (Product Owner, Scrum Master, Dev Team)
  - Artefatos (Product Backlog, Sprint Backlog, Increment)
  - Eventos (Sprint, Planning, Daily, Review, Retrospective)
  - Métricas (Velocity, Burndown)
- Kanban
  - Princípios do fluxo
  - Limites de WIP
  - Métricas (Lead time, Cycle time, Throughput)
- Extreme Programming (XP)
  - Pair programming
  - Continuous integration
  - Refactoring
  - Simple design

#### 6.3 DevOps e Integração Contínua
- Cultura DevOps
- CI/CD (Continuous Integration/Continuous Delivery)
- Pipeline de deploy
- Infraestrutura como código (IaC)
- Monitoramento e feedback
- Feature flags
- Git Flow e GitHub Flow
- Ferramentas: Jenkins, GitLab CI, GitHub Actions, Azure DevOps

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Sistemas de Suporte a Operações (OSS)
- **Sistemas de billing**: Especificação e desenvolvimento
- **Provisioning**: Automação de provisionamento de serviços
- **Falhas e tickets**: Sistemas de gestão de incidentes
- **Inventário**: Gestão de ativos de rede
- **Performance**: Sistemas de monitoramento e análise

### 3.2 Sistemas de Negócios (BSS)
- **CRM**: Gestão de relacionamento com clientes
- **ERP**: Integração de processos empresariais
- **Self-service**: Portais para clientes
- **Charging**: Sistemas de tarifação em tempo real

### 3.3 Aplicações de Rede
- **SDN/NFV**: Software para redes definidas por software
- **Orchestration**: Sistemas de orquestração de serviços
- **Analytics**: Plataformas de análise de dados de rede
- **Optimização**: Sistemas de otimização de recursos

### 3.4 Sistemas Embarcados
- **Firmware**: Desenvolvimento para equipamentos de telecom
- **Embedded software**: Sistemas embarcados em roteadores, switches
- **IoT**: Aplicações para Internet das Coisas
- **Protocol stacks**: Implementação de pilhas de protocolo

### 3.5 Qualidade em Sistemas de Telecom
- **Testes de conformidade**: Verificação de padrões (3GPP, IEEE, ITU-T)
- **Testes de interoperabilidade**: Compatibilidade entre equipamentos
- **Testes de performance**: Vazão, latência, jitter
- **Testes de segurança**: Proteção de infraestrutura crítica

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Conceitos de engenharia de software
- **Estudos de caso**: Análise de sistemas reais de telecom
- **Laboratórios práticos**: Ferramentas de modelagem e desenvolvimento
- **Projetos**: Desenvolvimento de sistema com ciclo completo
- **Workshops**: Metodologias ágeis e práticas de DevOps
- **Code reviews**: Revisões de código em grupo
- **Seminários**: Tendências e casos de sucesso/fracasso

### 4.2 Recursos Didáticos
- Quadro e projetor multimídia
- Laboratório com computadores configurados
- Ferramentas CASE (StarUML, Visual Paradigm, Enterprise Architect)
- IDEs de desenvolvimento (VS Code, IntelliJ, Eclipse)
- Ferramentas de gestão de projetos (Jira, Trello, Azure DevOps)
- Ferramentas de versionamento (Git, GitHub, GitLab)
- Ferramentas de CI/CD (Jenkins, GitHub Actions)
- Material didático digital
- Repositórios de código open source para análise

### 4.3 Avaliação

**Instrumentos:**
- Provas teórico-práticas (2 avaliações) - 40%
- Projeto de sistema com documentação completa - 40%
- Exercícios práticos e labs - 15%
- Participação em code reviews e discussões - 5%

**Critérios:**
- Compreensão de processos e metodologias de desenvolvimento
- Capacidade de elicitar e especificar requisitos
- Habilidade em modelar sistemas usando UML
- Conhecimento e aplicação de padrões de projeto
- Entendimento de estratégias de testes
- Capacidade de aplicar métricas de qualidade
- Qualidade da documentação produzida
- Aplicabilidade de metodologias ágeis

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Introdução à Engenharia de Software. Processos de desenvolvimento |
| 2 | Ciclo de vida do software. Modelos: cascata, iterativo, espiral |
| 3 | Engenharia de requisitos. Tipos e atividades |
| 4 | Técnicas de elicitação. Especificação de requisitos |
| 5 | **1ª Avaliação** |
| 6 | Modelagem UML. Diagramas estruturais e comportamentais |
| 7 | Padrões de projeto (Design Patterns). Criacionais e estruturais |
| 8 | Padrões de projeto comportamentais. Arquitetura de software |
| 9 | Qualidade de software. Métricas e fatores de qualidade |
| 10 | **2ª Avaliação** |
| 11 | Testes de software. Níveis, técnicas e estratégias |
| 12 | Automação de testes. TDD e BDD |
| 13 | Gestão de projetos de software. PMBOK |
| 14 | Metodologias ágeis: Scrum, Kanban, XP |
| 15 | DevOps e integração contínua. Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. PRESSMAN, R. S.; MAXIM, B. R. **Engenharia de Software: Uma Abordagem Profissional**. 8. ed. McGraw-Hill, 2016.
2. SOMMERVILLE, I. **Engenharia de Software**. 10. ed. Pearson, 2018.
3. GAMMA, E. et al. **Padrões de Projeto: Soluções Reutilizáveis de Software Orientado a Objetos**. Bookman, 2000.

### Bibliografia Complementar
4. BECK, K. **Extreme Programming Explained: Embrace Change**. 2. ed. Addison-Wesley, 2004.
5. SCHWABER, K.; SUTHERLAND, J. **Guia do Scrum**. Scrum.org, 2020.
6. MARTIN, R. C. **Código Limpo: Habilidades Práticas do Agile Software**. Alta Books, 2009.
7. FOWLER, M. **Refactoring: Improving the Design of Existing Code**. 2. ed. Addison-Wesley, 2018.
8. HUMBLE, J.; FARLEY, D. **Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation**. Addison-Wesley, 2010.

### Recursos Online
- [SWEBOK](https://www.computer.org/education/bodies-of-knowledge/software-engineering) - Software Engineering Body of Knowledge
- [Scrum.org](https://www.scrum.org/) - Recursos sobre Scrum
- [Agile Alliance](https://www.agilealliance.org/) - Agile e metodologias ágeis
- [Refactoring Guru](https://refactoring.guru/) - Padrões de projeto e refactoring
- [OWASP](https://owasp.org/) - Segurança em software
- [GitHub](https://github.com/) - Repositórios e exemplos de código

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Compreender e aplicar processos de desenvolvimento de software adequados ao contexto

**RA2** - Elicitar, analisar e especificar requisitos de software utilizando técnicas adequadas

**RA3** - Modelar sistemas de software utilizando UML e outras notações

**RA4** - Aplicar padrões de projeto e arquiteturas de software em soluções reais

**RA5** - Definir e executar estratégias de testes de software em diferentes níveis

**RA6** - Aplicar métricas e técnicas de garantia da qualidade de software

**RA7** - Utilizar metodologias ágeis para gestão e desenvolvimento de projetos

**RA8** - Aplicar práticas de DevOps e integração contínua no ciclo de desenvolvimento

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: Engenharia de Software é sobre criar software que funciona, é confiável, manutenível e atende às necessidades dos usuários. Técnica importa, mas entender as pessoas importa mais!

> 📋 **Requisitos**: A maioria dos projetos falha por problemas de requisitos, não de código. Dedique tempo para entender o problema antes de propor a solução.

> 🎨 **Modelagem**: UML é uma ferramenta de comunicação. Não modele tudo - modele o que é importante para comunicar ideias.

> 🧩 **Padrões**: Design patterns são soluções testadas para problemas recorrentes. Conheça-os, mas não force seu uso onde não se aplica.

> 🧪 **Testes**: Testar não é encontrar bugs, é garantir que o software funciona como especificado. Testes automatizados são investimento, não custo.

> 📊 **Métricas**: "O que não se mede, não se gerencia". Métricas ajudam a tomar decisões baseadas em dados, não em intuição.

> 🏃 **Ágil**: Agile não é ausência de processo, é adaptação constante. Scrum e Kanban são frameworks - adapte à sua realidade.

> 🔄 **DevOps**: Quebre o silo entre desenvolvimento e operações. Quem constrói, opera. Feedback rápido é essencial.

> 🔗 **Conexões**: Esta disciplina integra conhecimentos de:
> - Programação (implementação de padrões e arquiteturas)
> - Gestão de Projetos (planejamento e acompanhamento)
> - Qualidade (testes e métricas)
> - Todas as áreas que envolvam desenvolvimento de software

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025