---
tags: [web, arquitetura, frontend, backend, engenharia, telecomunicações, optativa]
semestre: 10
area: Optativas
creditos: 4
dificuldade: media
importancia: media
código: OPT004
carga_horaria: 60h (4 créditos)
status: completo
pré_requisitos: [Programacao Orientada Objetos, Redes Computadores, Banco_de_Dados]
links: [Optativa III, Redes Comunicacao Dados, Programacao Orientada Objetos]
aliases: [Optativa_IV]
keywords: [web, arquitetura, frontend, backend, engenharia, telecomunicações, optativa]
resumo: "Estudo das arquiteturas e tecnologias para desenvolvimento de aplicações web: fundamentos da web, frontend e backend, APIs RESTful, bancos de dados, segurança web, arquiteturas modernas (microserviços, serverless), DevOp"
---

# Optativa IV: Arquitetura WEB

## 1. Ementa Oficial

Estudo das arquiteturas e tecnologias para desenvolvimento de aplicações web: fundamentos da web, frontend e backend, APIs RESTful, bancos de dados, segurança web, arquiteturas modernas (microserviços, serverless), DevOps e deploy de aplicações web.

### Objetivos da Disciplina

**Objetivo Geral:**
Proporcionar ao estudante conhecimentos especializados sobre arquitetura e desenvolvimento de aplicações web modernas, capacitando-o a projetar, implementar e implantar sistemas web escaláveis e seguros.

**Objetivos Específicos:**
- Compreender os fundamentos da web e protocolos HTTP/HTTPS
- Desenvolver interfaces frontend responsivas e interativas
- Projetar e implementar APIs RESTful e GraphQL
- Conhecer frameworks backend e padrões de arquitetura
- Entender bancos de dados relacionais e NoSQL para web
- Aplicar conceitos de segurança em aplicações web
- Conhecer arquiteturas modernas: microserviços, serverless, containers
- Entender práticas de DevOps e CI/CD para deploy de aplicações

---

## 2. Conteúdo Programático

### Unidade 1: Fundamentos da Web (10h)

#### 1.1 Protocolos e Infraestrutura
- História da web (Web 1.0, 2.0, 3.0)
- Protocolo HTTP/1.1 e HTTP/2
- Protocolo HTTPS e TLS/SSL
- Certificados digitais (Let's Encrypt)
- DNS e resolução de nomes
- WebSockets para comunicação bidirecional
- WebRTC para comunicação em tempo real
- HTTP/3 e QUIC

#### 1.2 Arquitetura Cliente-Servidor
- Modelo cliente-servidor na web
- Arquitetura em camadas (3-tier, n-tier)
- Stateless vs stateful
- Cookies, sessões e armazenamento local
- CDN (Content Delivery Network)
- Proxy reverso
- Load balancing
- Escalabilidade horizontal e vertical

---

### Unidade 2: Frontend Web (12h)

#### 2.1 HTML, CSS e JavaScript Moderno
- HTML5 semântico
- CSS3: Flexbox, Grid, animações
- JavaScript ES6+: arrow functions, promises, async/await, modules
- TypeScript: tipagem estática
- Pré-processadores CSS (Sass, Less)
- Bundlers: Webpack, Vite, Parcel

#### 2.2 Frameworks Frontend
- **React**
  - Componentes e JSX
  - Hooks (useState, useEffect, useContext)
  - Redux/Context API para gerenciamento de estado
  - React Router
  - Next.js (SSR, SSG)
- **Vue.js**
  - Diretivas e componentes
  - Vuex para estado
  - Vue Router
  - Nuxt.js
- **Angular**
  - Componentes e módulos
  - Services e injeção de dependência
  - RxJS e programação reativa
- Single Page Applications (SPA) vs Server-Side Rendering (SSR)

#### 2.3 Design Responsivo e UX
- Mobile-first design
- Media queries
- Frameworks CSS (Bootstrap, Tailwind CSS, Material-UI)
- Acessibilidade web (WCAG)
- Performance frontend
  - Lazy loading
  - Code splitting
  - Otimização de imagens
  - Core Web Vitals

---

### Unidade 3: Backend Web (12h)

#### 3.1 Frameworks Backend
- **Node.js**
  - Express.js
  - NestJS
  - Fastify
- **Python**
  - Django
  - Flask
  - FastAPI
- **Java**
  - Spring Boot
- **Outras linguagens**
  - Ruby on Rails
  - PHP (Laravel)
  - Go (Gin, Echo)

#### 3.2 APIs e Comunicação
- RESTful APIs
  - Métodos HTTP (GET, POST, PUT, DELETE, PATCH)
  - Códigos de status HTTP
  - Versionamento de APIs
  - HATEOAS
- GraphQL
  - Queries e mutations
  - Resolvers
  - Schema
- gRPC
- Webhooks
- Autenticação e autorização
  - JWT (JSON Web Tokens)
  - OAuth 2.0 e OpenID Connect
  - Sessions e cookies
  - API Keys

#### 3.3 Padrões de Arquitetura Backend
- MVC (Model-View-Controller)
- Repository Pattern
- Dependency Injection
- Middleware
- Interceptors e filters
- CQRS (Command Query Responsibility Segregation)
- Event-driven architecture

---

### Unidade 4: Banco de Dados e Persistência (10h)

#### 4.1 Bancos de Dados Relacionais
- PostgreSQL, MySQL, MariaDB
- Modelagem de dados
- Normalização
- Índices e otimização de queries
- Transações ACID
- ORMs (Sequelize, TypeORM, Prisma, Hibernate)
- Migrations

#### 4.2 Bancos de Dados NoSQL
- MongoDB (documentos)
- Redis (cache e estruturas de dados)
- Cassandra (colunar)
- Neo4j (grafo)
- Elasticsearch (busca)
- Casos de uso e escolha do banco adequado

#### 4.3 Cache e Performance
- Estratégias de cache
- Redis/Memcached
- Cache HTTP
- CDN para assets estáticos
- Database connection pooling
- Read replicas

---

### Unidade 5: Arquiteturas Modernas e DevOps (10h)

#### 5.1 Microserviços
- Conceito de microserviços
- Monolito vs microserviços
- Comunicação entre serviços
  - REST
  - Message queues (RabbitMQ, Kafka)
  - gRPC
- Service discovery
- API Gateway
- Circuit breaker
- Distributed tracing

#### 5.2 Containers e Orquestração
- Docker: containers e imagens
- Dockerfile e docker-compose
- Kubernetes
  - Pods, services, deployments
  - ConfigMaps e secrets
  - Ingress
  - Escalabilidade
- Container registries (Docker Hub, AWS ECR)

#### 5.3 Serverless e Cloud
- Conceito de serverless
- AWS Lambda
- Azure Functions
- Google Cloud Functions
- FaaS (Function as a Service)
- Event-driven serverless
- Vantagens e limitações

#### 5.4 DevOps e CI/CD
- Versionamento com Git (GitHub, GitLab, Bitbucket)
- CI/CD pipelines
  - GitHub Actions
  - GitLab CI
  - Jenkins
- Testes automatizados
  - Unit tests
  - Integration tests
  - E2E tests (Cypress, Selenium)
- Deploy
  - Blue-green deployment
  - Canary releases
  - Feature flags
- Monitoramento e logging
  - Prometheus e Grafana
  - ELK Stack
  - Datadog, New Relic

---

### Unidade 6: Segurança Web e Tendências (6h)

#### 6.1 Segurança em Aplicações Web
- OWASP Top 10
  - Injection (SQL, NoSQL, OS command)
  - Broken authentication
  - Sensitive data exposure
  - XSS (Cross-Site Scripting)
  - CSRF (Cross-Site Request Forgery)
  - Security misconfiguration
- HTTPS e HSTS
- Content Security Policy (CSP)
- CORS (Cross-Origin Resource Sharing)
- Sanitização de input
- Hashing de senhas (bcrypt, Argon2)
- Proteção contra DDoS

#### 6.2 Testes de Segurança
- Pentest básico
- Ferramentas: OWASP ZAP, Burp Suite
- SAST e DAST
- Dependency scanning
- Secret scanning

#### 6.3 Tendências e Futuro da Web
- Progressive Web Apps (PWA)
- JAMstack (JavaScript, APIs, Markup)
- WebAssembly (WASM)
- Edge computing e Edge Functions
- Web3 e blockchain
- IA generativa em desenvolvimento web
- Low-code/No-code platforms

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Dashboards e Monitoramento
- **NMS/OSS**: Interfaces web para gerenciamento de redes
- **Dashboards de performance**: Visualização de métricas de rede
- **Mapas de cobertura**: Interfaces geoespaciais
- **Monitoramento de infraestrutura**: Sistemas web para data centers

### 3.2 APIs de Telecomunicações
- **REST APIs**: Exposição de serviços de telecom
- **Webhooks**: Notificações de eventos de rede
- **GraphQL**: APIs flexíveis para clientes diversos
- **Streaming APIs**: Dados em tempo real de sensores

### 3.3 Sistemas de Suporte (BSS/OSS)
- **Sistemas de billing**: Web apps para faturamento
- **CRM para telecom**: Gestão de relacionamento com clientes
- **Provisioning**: Automação de provisionamento de serviços
- **Ticketing systems**: Sistemas de suporte ao cliente

### 3.4 Aplicações de Voz e Vídeo
- **WebRTC**: Comunicação em tempo real no navegador
- **Softphones web**: Telefonia via browser
- **Videoconferência**: Plataformas web (Zoom, Teams)
- **Streaming**: Plataformas de transmissão de vídeo

### 3.5 Internet das Coisas (IoT)
- **Dashboards IoT**: Visualização de dados de sensores
- **Controle remoto**: Interfaces web para dispositivos
- **OTA updates**: Sistemas web para atualização de firmware
- **Digital twins**: Representação web de ativos físicos

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Conceitos de arquitetura web
- **Laboratórios práticos**: Desenvolvimento hands-on
- **Projetos**: Aplicação web full-stack completa
- **Code reviews**: Análise de código em grupo
- **Seminários**: Arquiteturas de sistemas reais
- **Workshops**: Ferramentas e frameworks específicos

### 4.2 Recursos Didáticos
- Quadro e projetor multimídia
- Laboratório com computadores configurados
- Ambientes de desenvolvimento na nuvem (GitHub Codespaces, Gitpod)
- Acesso a serviços cloud (AWS, Azure, GCP - free tier)
- IDEs: VS Code, WebStorm, IntelliJ
- Ferramentas de design: Figma
- Material didático digital
- Documentação oficial de frameworks

### 4.3 Avaliação

**Instrumentos:**
- Provas teórico-práticas (2 avaliações) - 40%
- Projeto de aplicação web full-stack - 40%
- Laboratórios práticos - 15%
- Participação - 5%

**Critérios:**
- Compreensão de arquiteturas web modernas
- Capacidade de desenvolver frontend responsivo
- Habilidade em projetar e implementar APIs
- Conhecimento de bancos de dados
- Entendimento de segurança web
- Qualidade do código e documentação
- Funcionalidade do projeto desenvolvido

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Fundamentos da web. HTTP/HTTPS, DNS |
| 2 | Arquitetura cliente-servidor. Escalabilidade |
| 3 | HTML5, CSS3, JavaScript ES6+ |
| 4 | Frameworks frontend: React/Vue/Angular |
| 5 | **1ª Avaliação** |
| 6 | Backend: Node.js, Python, Java |
| 7 | APIs RESTful. GraphQL |
| 8 | Autenticação: JWT, OAuth |
| 9 | Bancos de dados: SQL e NoSQL |
| 10 | **2ª Avaliação** |
| 11 | Microserviços. Message queues |
| 12 | Docker e Kubernetes |
| 13 | Serverless. CI/CD |
| 14 | Segurança web. OWASP Top 10 |
| 15 | Tendências: PWA, WebAssembly, Web3. Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. FLANAGAN, D. **JavaScript: The Definitive Guide**. 7. ed. O'Reilly, 2020.
2. FOWLER, M. **Patterns of Enterprise Application Architecture**. Addison-Wesley, 2002.
3. RICHARDSON, C. **Microservices Patterns**. Manning, 2018.

### Bibliografia Complementar
4. STEFANOV, S. **React: Up & Running**. 2. ed. O'Reilly, 2021.
5. MARMEL, E. **Mastering Django**. 3. ed. Packt Publishing, 2020.
6. NEWMAN, S. **Building Microservices**. 2. ed. O'Reilly, 2021.
7. KIM, G. **The DevOps Handbook**. 2. ed. IT Revolution, 2021.
8. HIGHSMITH, J. **Agile Software Development Ecosystems**. Addison-Wesley, 2002.

### Recursos Online
- [MDN Web Docs](https://developer.mozilla.org/) - Documentação web
- [React Documentation](https://react.dev/) - Documentação oficial React
- [Node.js Documentation](https://nodejs.org/docs/) - Documentação Node.js
- [Docker Documentation](https://docs.docker.com/) - Documentação Docker
- [Kubernetes Documentation](https://kubernetes.io/docs/) - Documentação K8s
- [OWASP](https://owasp.org/) - Segurança web
- [Can I Use](https://caniuse.com/) - Compatibilidade de browsers

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Compreender os fundamentos da web, protocolos HTTP/HTTPS e arquitetura cliente-servidor

**RA2** - Desenvolver interfaces frontend responsivas utilizando HTML, CSS, JavaScript e frameworks modernos

**RA3** - Projetar e implementar APIs RESTful e GraphQL com boas práticas

**RA4** - Desenvolver aplicações backend utilizando frameworks modernos e padrões de arquitetura

**RA5** - Modelar e integrar bancos de dados relacionais e NoSQL em aplicações web

**RA6** - Implementar mecanismos de autenticação, autorização e segurança em aplicações web

**RA7** - Conhecer e aplicar arquiteturas modernas: microserviços, containers, serverless

**RA8** - Aplicar práticas de DevOps, CI/CD e deploy de aplicações web em produção

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: Arquitetura web é um campo em constante evolução. Acompanhe blogs, newsletters e repositórios no GitHub para se manter atualizado!

> 🌐 **HTTP**: Entenda bem o protocolo HTTP. É a base de toda a web. Saiba os métodos, status codes e headers.

> ⚛️ **Frontend**: React domina o mercado, mas Vue e Angular também são relevantes. Domine um bem antes de aprender outros.

> 🖥️ **Backend**: Node.js é ótimo para full-stack JavaScript. Python (Django/FastAPI) é excelente para ML integração. Java (Spring) é padrão em grandes empresas.

> 🗄️ **Banco de Dados**: SQL primeiro! Entenda bem modelagem relacional antes de ir para NoSQL. Escolha a ferramenta certa para o problema.

> 🐳 **Docker**: Containerização é essencial hoje. Aprenda Docker antes de Kubernetes.

> 🔒 **Segurança**: OWASP Top 10 é obrigatório. Nunca confie em input do usuário. Sempre sanitize e valide dados.

> 🚀 **Deploy**: Seu código só tem valor quando está em produção. Aprenda CI/CD desde cedo. Automatize testes e deploy.

> 🔗 **Conexões**: Esta disciplina integra conhecimentos de:
> - Programação Orientada a Objetos (padrões de projeto)
> - Redes de Computadores (protocolos HTTP, TCP/IP)
> - Banco de Dados (modelagem, queries, ORMs)
> - DevOps e infraestrutura de TI

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025