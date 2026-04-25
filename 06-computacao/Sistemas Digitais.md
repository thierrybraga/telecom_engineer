---
tags: [sistemas digitais, eletrônica digital, lógica, circuitos, engenharia]
semestre: 4
area: Computação
creditos: 4
dificuldade: alta
importancia: alta
código: ELE005
carga_horaria: 60h (4 créditos)
status: completo
pré_requisitos: [Eletronica I, Algoritmos I]
links: [Microprocessadores, Eletronica II, Circuitos Eletricos II]
aliases: [Sistemas_Digitais]
keywords: [sistemas digitais, eletrônica digital, lógica, circuitos, engenharia]
resumo: "Estudo dos sistemas digitais: álgebra de Boole, circuitos combinacionais e sequenciais, minimização de funções lógicas, máquinas de estado, memórias, conversores A/D e D/A, introdução a linguagens de descrição de hardwar"
---

# Sistemas Digitais

## 1. Ementa Oficial

Estudo dos sistemas digitais: álgebra de Boole, circuitos combinacionais e sequenciais, minimização de funções lógicas, máquinas de estado, memórias, conversores A/D e D/A, introdução a linguagens de descrição de hardware (VHDL/Verilog) e projeto de sistemas digitais.

### Objetivos da Disciplina

**Objetivo Geral:**
Proporcionar ao estudante conhecimentos sobre análise e projeto de sistemas digitais, capacitando-o a compreender, projetar e implementar circuitos digitais combinacionais e sequenciais.

**Objetivos Específicos:**
- Compreender sistemas de numeração e códigos digitais
- Aplicar álgebra de Boole no projeto de circuitos lógicos
- Analisar e projetar circuitos combinacionais
- Analisar e projetar circuitos sequenciais síncronos e assíncronos
- Entender máquinas de estado finito (FSM)
- Conhecer dispositivos de memória
- Compreender conversores A/D e D/A
- Introduzir linguagens de descrição de hardware
- Desenvolver projetos de sistemas digitais

---

## 2. Conteúdo Programático

### Unidade 1: Fundamentos de Sistemas Digitais (10h)

#### 1.1 Sistemas de Numeração
- Sistemas binário, octal e hexadecimal
- Conversão entre bases
- Aritmética binária
  - Adição e subtração
  - Multiplicação e divisão
- Representação de números com sinal
  - Sinal-magnitude
  - Complemento de 1
  - Complemento de 2
- Operações em complemento de 2

#### 1.2 Códigos Digitais
- Código BCD (Binary-Coded Decimal)
- Código Gray
- Código ASCII
- Códigos de detecção e correção de erros
  - Bit de paridade
  - Código de Hamming
- Aplicações de códigos

---

### Unidade 2: Álgebra de Boole e Circuitos Combinacionais (12h)

#### 2.1 Álgebra de Boole
- Postulados e teoremas da álgebra de Boole
- Operações lógicas: AND, OR, NOT
- Portas lógicas básicas
- Propriedades e identidades
- Teoremas de De Morgan
- Formas canônicas
  - Soma de produtos (SOP)
  - Produto de somas (POS)

#### 2.2 Minimização de Funções Lógicas
- Mapas de Karnaugh
  - Mapas de 2, 3, 4 e 5 variáveis
  - Agrupamento de termos
  - Implicantes primos essenciais
- Método de Quine-McCluskey
- Síntese de circuitos minimizados
- Considerações sobre hazards

#### 2.3 Circuitos Combinacionais
- Codificadores e decodificadores
- Multiplexadores (MUX) e demultiplexadores (DEMUX)
- Comparadores
- Circuitos aritméticos
  - Meio-somador (half-adder)
  - Somador completo (full-adder)
  - Meio-subtrator e subtrator completo
  - Somadores paralelos (ripple-carry, carry-lookahead)
- Unidade Lógica e Aritmética (ULA)

---

### Unidade 3: Circuitos Sequenciais (12h)

#### 3.1 Elementos de Memória
- Latches: SR, D, JK, T
- Flip-flops: SR, D, JK, T
  - Disparo por nível
  - Disparo por borda
- Tabelas de excitação
- Conversão entre flip-flops
- Análise temporal
  - Setup time
  - Hold time
  - Propagation delay

#### 3.2 Circuitos Sequenciais Básicos
- Registradores
  - Registradores de deslocamento (shift registers)
  - Registradores paralelos
- Contadores
  - Contadores assíncronos (ripple)
  - Contadores síncronos
  - Contadores em anel
  - Contadores Johnson
  - Contadores de década

#### 3.3 Análise e Projeto de Circuitos Sequenciais
- Modelo de circuito sequencial
- Tabelas de estado
- Diagramas de estado
- Equações de estado e de saída
- Projeto de contadores arbitrários
- Projeto de sequenciadores

---

### Unidade 4: Máquinas de Estado Finito (10h)

#### 4.1 Fundamentos de FSM
- Modelos de Moore e Mealy
- Representação de estados
- Tabelas de transição de estado
- Diagramas de transição de estado
- Equivalência de estados
- Minimização de estados

#### 4.2 Projeto de MFS
- Procedimento de projeto de FSM
- Atribuição de estados
- Implementação com flip-flops
- Máquinas de estado de alto nível (ASM)
- Análise de desempenho
- Considerações de temporização

#### 4.3 Aplicações de FSM
- Controladores de sequência
- Detectores de padrão
- Geradores de sequência
- Interface de dispositivos
- Protocolos de comunicação

---

### Unidade 5: Dispositivos de Memória e PLDs (10h)

#### 5.1 Memórias
- Classificação de memórias
  - RAM (Random Access Memory)
    - SRAM (Static RAM)
    - DRAM (Dynamic RAM)
  - ROM (Read-Only Memory)
    - ROM, PROM, EPROM, EEPROM
    - Flash memory
- Organização de memória
- Decodificação de endereços
- Expansão de memória
- Hierarquia de memória

#### 5.2 Dispositivos Lógicos Programáveis
- SPLD (Simple PLD)
  - PAL (Programmable Array Logic)
  - GAL (Generic Array Logic)
- CPLD (Complex PLD)
- FPGA (Field-Programmable Gate Array)
- Arquitetura de FPGAs
  - LUTs (Look-Up Tables)
  - Blocos de I/O
  - Roteamento programável
- Fluxo de projeto em FPGA

---

### Unidade 6: Conversores e HDL (6h)

#### 6.1 Conversores A/D e D/A
- Conversores D/A (Digital para Analógico)
  - Rede R-2R
  - Conversor de corrente ponderada
- Conversores A/D (Analógico para Digital)
  - Flash (paralelo)
  - Aproximações sucessivas
  - Contador
  - Integração dupla (dual-slope)
- Amostragem e quantização
- Teorema de Nyquist

#### 6.2 Linguagens de Descrição de Hardware
- Introdução a VHDL e Verilog
- Entidade e arquitetura (VHDL)
- Módulos (Verilog)
- Descrição de circuitos combinacionais
- Descrição de circuitos sequenciais
- Simulação e síntese
- Ferramentas CAD para projeto digital

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Processamento Digital de Sinais
- **Filtros digitais**: Implementação em FPGA
- **Moduladores/demoduladores**: Sistemas de comunicação
- **Codificadores**: Comunicações digitais
- **Correlacionadores**: CDMA, GPS
- **Processadores de sinais**: DSPs em hardware

### 3.2 Sistemas de Comunicação
- **Interfaces seriais**: UART, SPI, I2C
- **Controladores de protocolo**: Implementação digital
- **Sincronizadores**: Recuperação de clock
- **Equalizadores**: Compensação de canal
- **FFT/IFFT**: Implementação para OFDM

### 3.3 Telecomunicações
- **Switching digital**: Comutação de pacotes
- **Roteadores**: Processamento de pacotes
- **Multiplexadores**: TDM, FDM digital
- **Codificação de canal**: Reed-Solomon, convolutional
- **Sistemas de teste**: BERT, analisadores de protocolo

### 3.4 Sistemas Embarcados
- **Controladores**: Sistemas de controle digital
- **Microcontroladores**: Sistemas embarcados
- **SoCs (System on Chip)**: Integração completa
- **Interfaces de usuário**: Displays, teclados
- **Gerenciamento de energia**: Controle de consumo

### 3.5 Instrumentação
- **Analisadores lógicos**: Debug de sistemas digitais
- **Geradores de padrão**: Teste de circuitos
- **Osciloscópios digitais**: Aquisição de dados
- **Sistemas de medição**: Precisão e velocidade

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Conceitos de álgebra de Boole e circuitos
- **Aulas de exercícios**: Resolução de problemas de projeto
- **Laboratórios práticos**: Montagem de circuitos digitais
- **Simulações**: Software de simulação (Logisim, Proteus, Quartus)
- **Projetos**: Desenvolvimento de sistemas digitais
- **Seminários**: Tecnologias emergentes (FPGA, SoC)

### 4.2 Recursos Didáticos
- Quadro e projetor multimídia
- Laboratório de eletrônica digital com kits didáticos
- Software de simulação (Logisim, Multisim, Quartus, Vivado)
- Placas de desenvolvimento FPGA (Cyclone, Basys)
- Osciloscópios digitais
- Analisadores lógicos
- Material didático digital

### 4.3 Avaliação

**Instrumentos:**
- Provas teórico-práticas (2 avaliações) - 50%
- Projetos de circuitos digitais - 30%
- Laboratórios práticos - 15%
- Participação - 5%

**Critérios:**
- Domínio de sistemas de numeração e códigos
- Capacidade de aplicar álgebra de Boole
- Habilidade em projetar circuitos combinacionais
- Conhecimento de circuitos sequenciais e FSM
- Entendimento de dispositivos de memória
- Familiaridade com PLDs e FPGAs
- Qualidade de projetos e implementações

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Sistemas de numeração. Aritmética binária |
| 2 | Códigos digitais. Códigos de erro |
| 3 | Álgebra de Boole. Portas lógicas |
| 4 | Minimização com Mapas de Karnaugh |
| 5 | **1ª Avaliação** |
| 6 | Circuitos combinacionais. Decodificadores e MUX |
| 7 | Circuitos aritméticos. ULA |
| 8 | Latches e Flip-flops |
| 9 | Registradores e contadores |
| 10 | **2ª Avaliação** |
| 11 | Análise de circuitos sequenciais |
| 12 | Máquinas de estado FSM (Moore e Mealy) |
| 13 | Memórias RAM e ROM |
| 14 | Dispositivos PLD e FPGA |
| 15 | Conversores A/D e D/A. HDL. Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. TOCCI, R. J.; WIDMER, N. S.; MOSS, G. L. **Sistemas Digitais: Princípios e Aplicações**. 12. ed. Pearson, 2018.
2. BROWN, S.; VRANESIC, Z. **Fundamentos de Lógica Digital com Projeto VHDL**. Bookman, 2009.
3. ERCEGOVAC, M. D.; LANG, T.; MORENO, J. H. **Introdução aos Sistemas Digitais**. Bookman, 2000.

### Bibliografia Complementar
4. MANO, M. M.; CILETTI, M. D. **Digital Design**. 5. ed. Pearson, 2012.
5. FLOYD, T. L. **Digital Fundamentals**. 11. ed. Pearson, 2014.
6. KATZ, R. H.; BORRIELLO, G. **Contemporary Logic Design**. 2. ed. Pearson, 2004.
7. WAKERLY, J. F. **Digital Design: Principles and Practices**. 4. ed. Pearson, 2005.
8. CHU, P. P. **FPGA Prototyping by VHDL Examples**. Wiley, 2008.

### Recursos Online
- [Logisim](http://www.cburch.com/logisim/) - Simulador de circuitos digitais
- [Intel FPGA](https://www.intel.com/content/www/us/en/products/programmable.html) - Documentação e ferramentas
- [Xilinx](https://www.xilinx.com/) - Documentação e ferramentas
- [VHDL Tutorial](https://www.ics.uci.edu/~jmoorkan/vhdlref/) - Referência VHDL
- [Verilog Tutorial](https://www.asic-world.com/verilog/) - Tutorial Verilog

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Compreender e converter entre sistemas de numeração e aplicar códigos digitais

**RA2** - Aplicar álgebra de Boole e teoremas na análise e síntese de circuitos lógicos

**RA3** - Projetar e analisar circuitos combinacionais utilizando portas lógicas

**RA4** - Projetar e analisar circuitos sequenciais com flip-flops e registradores

**RA5** - Modelar e implementar máquinas de estado finito (FSM)

**RA6** - Compreender dispositivos de memória e sistemas de armazenamento

**RA7** - Entender o funcionamento de conversores A/D e D/A

**RA8** - Introduzir conceitos de linguagens de descrição de hardware para projeto de sistemas digitais

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: Sistemas Digitais é a base da eletrônica moderna. Domine bem álgebra de Boole - ela é a linguagem dos circuitos digitais!

> 🔢 **Sistemas de Numeração**: Binário é a base, mas hexadecimal é seu amigo para representar números grandes. Aprenda a converter rapidamente.

> 🎯 **Karnaugh**: O mapa de Karnaugh é uma ferramenta visual poderosa para minimização. Pratique até conseguir simplificar de olho fechado!

> 🔄 **Sequenciais**: Circuitos sequenciais têm "memória" - o estado atual depende do passado. Entenda bem flip-flops antes de partir para FSMs.

> 🎰 **FSM**: Máquinas de estado são usadas em TODO lugar - desde CPUs até controles de elevadores. Moore vs Mealy é uma escolha importante!

> 💾 **Memórias**: RAM é volátil e rápida. ROM é permanente. Flash é o meio-termo. Cada uma tem seu lugar no sistema.

> 🔧 **FPGA**: Field-Programmable Gate Arrays revolucionaram o projeto digital. Aprenda VHDL ou Verilog - são linguagens do futuro!

> 🔗 **Conexões**: Esta disciplina é fundamental para:
> - Microprocessadores (CPU, registradores, memória)
> - Eletrônica II (interfaces digitais)
> - Processamento Digital de Sinais (implementação hardware)
> - Todas as áreas de telecom que envolvam hardware digital

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025