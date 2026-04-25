---
tags: [elétrica, eletrônica, semicondutores, diodos, transistores, amplificadores, engenharia]
semestre: 5
area: Elétrica
creditos: 6
dificuldade: alta
importancia: critica
código: ELE011
carga_horaria: 90h (6 créditos)
status: completo
pré_requisitos: [Circuitos Eletricos I]
links: [Eletronica II, Eletronica Aplicada, Circuitos Eletricos II]
aliases: [Eletronica_I]
keywords: [elétrica, eletrônica, semicondutores, diodos, transistores, amplificadores, engenharia]
resumo: "Estudo dos dispositivos semicondutores: diodos, transistores bipolares (BJT) e transistores de efeito de campo (FET)."
---

# Eletrônica I

## 1. Ementa Oficial

Estudo dos dispositivos semicondutores: diodos, transistores bipolares (BJT) e transistores de efeito de campo (FET). Análise e projeto de circuitos eletrônicos básicos: retificadores, reguladores, amplificadores e estágios de acoplamento.

### Objetivos da Disciplina

**Objetivo Geral:**
Proporcionar ao estudante o conhecimento teórico e prático dos dispositivos semicondutores mais utilizados em eletrônica, capacitando-o a analisar e projetar circuitos eletrônicos lineares e não-lineares.

**Objetivos Específicos:**
- Compreender a física dos semicondutores e junções PN
- Analisar e projetar circuitos com diodos (retificadores, limitadores, reguladores)
- Compreender o funcionamento e modelos de transistores bipolares (BJT)
- Analisar e projetar amplificadores com BJT em diferentes configurações
- Compreender o funcionamento de transistores de efeito de campo (FET)
- Analisar circuitos de acoplamento e resposta em frequência de amplificadores

---

## 2. Conteúdo Programático

### Unidade 1: Fundamentos de Semicondutores (10h)

#### 1.1 Introdução à Física de Semicondutores
- Estrutura cristalina e ligações covalentes
- Semicondutores intrínsecos e extrínsecos
- Dopagem tipo N e tipo P
- Concentração de portadores (n, p)
- Lei da junção de massas action: n·p = ni²

#### 1.2 Condução em Semicondutores
- Densidade de corrente de deriva
- Mobilidade dos portadores
- Condutividade e resistividade
- Difusão de portadores
- Densidade de corrente de difusão
- Comprimento de difusão e tempo de vida

#### 1.3 Junção PN
- Formação da junção PN
- Barreira de potencial
- Região de depleção (depletion region)
- Campo elétrico interno
- Tensão de contato (built-in potential)
- Equação de Poisson na junção

---

### Unidade 2: Diodos e Aplicações (15h)

#### 2.1 Diodo de Junção PN
- Característica I-V do diodo
- Equação do diodo (equação de Shockley)
- Corrente de saturação reversa (Is)
- Tensão térmica (VT = kT/q)
- Resistência dinâmica e estática
- Diodo ideal vs diodo real

#### 2.2 Modelos do Diodo
- Modelo exponencial
- Modelo de queda de tensão constante
- Modelo de resistência incremental
- Modelo de idealidade para análise de circuitos
- Reta de carga e ponto de operação (Q-point)

#### 2.3 Circuitos Retificadores
- Retificador de meia onda
- Retificador de onda completa com derivação central
- Retificador em ponte (Graetz)
- Cálculo de tensão média e eficaz
- Fator de ripple
- Diodos de roda livre (free-wheeling)

#### 2.4 Filtros para Retificadores
- Filtro capacitivo
- Filtro LC (indutor-capacitor)
- Filtro RC
- Filtro CLC (pi filter)
- Cálculo do capacitor para determinado ripple
- Regulação de carga e de linha

#### 2.5 Outras Aplicações do Diodo
- Limitadores (clippers) e restauradores de nível (clampers)
- Multiplicadores de tensão (voltage multipliers)
- Diodos Zener e circuitos reguladores
- Diodos LEDs e fotodiodos
- Diodos Schottky (características e aplicações)
- Diodos varicap (varactor) para sintonia

---

### Unidade 3: Transistores Bipolares de Junção (BJT) (18h)

#### 3.1 Estrutura e Princípio de Funcionamento
- Estrutura NPN e PNP
- Modos de operação: corte, saturação, ativa
- Correntes no transistor: IE, IC, IB
- Efeito transistor: controle de IC por IB
- Ganho de corrente β (hFE) e α
- Relação: IC = β·IB, IE = (β+1)·IB

#### 3.2 Características do BJT
- Características de entrada (IB vs VBE)
- Características de saída (IC vs VCE)
- Efeito Early (modulação da base)
- Tensões de breakdown: BVCEO, BVCBO
- Curvas características típicas

#### 3.3 Modelos de Pequenos Sinais
- Modelo híbrido-π (hybrid-pi)
- Modelo de parâmetros h (modelo híbrido)
- Modelo T
- Transcondutância gm = IC/VT
- Resistência de entrada rπ = β/gm
- Resistência de saída ro = VA/IC

#### 3.4 Polarização do BJT
- Ponto de operação (Q-point)
- Reta de carga DC
- Estabilidade do ponto de operação
- Circuito de polarização por divisor de tensão (auto-polarização)
- Circuito de polarização com realimentação de emissor
- Circuito de polarização com realimentação de coletor
- Análise de sensibilidade a variações de β e temperatura

#### 3.5 Configurações de Amplificadores com BJT
- Configuração emissor-comum (EC/CE):
  - Ganho de tensão
  - Ganho de corrente
  - Impedância de entrada e saída
  - Inversão de fase
  
- Configuração base-comum (BC/CB):
  - Ganho de tensão
  - Impedância de entrada baixa
  - Impedância de saída alta
  - Largura de banda
  
- Configuração coletor-comum (CC/CE) - Seguidor de emissor:
  - Ganho unitário de tensão
  - Alta impedância de entrada
  - Baixa impedância de saída
  - Casamento de impedância

---

### Unidade 4: Amplificadores com BJT (15h)

#### 4.1 Análise de Pequenos Sinais
- Separação das análises DC e AC
- Equivalente AC do circuito
- Cálculo de ganhos (Av, Ai, Ap)
- Impedâncias de entrada e saída
- Máxima excursão simétrica do sinal (swing)

#### 4.2 Amplificadores Multietapa
- Acoplamento capacitivo (RC)
- Acoplamento por transformador
- Acoplamento direto (DC)
- Ganho total em cascata
- Análise de estágios em cascata

#### 4.3 Amplificadores Diferenciais
- Par diferencial com BJT
- Modos de operação: diferencial e modo comum
- Ganho diferencial (Ad)
- Ganho de modo comum (Acm)
- Rejeição de modo comum (CMRR)
- Espelho de corrente como carga ativa

#### 4.4 Resposta em Frequência de Amplificadores
- Diagrama de Bode
- Frequências de corte (cutoff)
- Resposta de amplificadores EC
- Efeito dos capacitores de acoplamento e bypass
- Efeito das capacitâncias parasitas (Cπ, Cμ)
- Produto ganho-largura de banda (GBW)
- Frequência de transição (fT)

---

### Unidade 5: Transistores de Efeito de Campo (FET) (15h)

#### 5.1 JFET (Junction Field-Effect Transistor)
- Estrutura e princípio de funcionamento
- Modos de operação: depleção
- Características de dreno (ID vs VDS)
- Características de transferência (ID vs VGS)
- Tensão de pinch-off (Vp)
- Corrente de saturação (IDSS)
- Equação de Shockley para JFET

#### 5.2 MOSFET (Metal-Oxide-Semiconductor FET)
- Estrutura do MOSFET de canal N e P
- MOSFET de modo depleção vs modo intensificação
- Características de saída e transferência
- Tensão de threshold (Vt)
- Parâmetros: k, W/L, Cox
- Equação do MOSFET na região de triodo e saturação
- MOSFETs de potência

#### 5.3 Polarização do FET
- Polarização por divisor de tensão
- Polarização com realimentação de fonte
- Polarização com dupla fonte
- Ponto de operação Q
- Estabilidade térmica do FET

#### 5.4 Modelos de Pequenos Sinais do FET
- Transcondutância gm do FET
- Resistência de saída rd (ro)
- Modelo equivalente de pequenos sinais
- Capacitâncias parasitas (Cgs, Cgd, Cds)
- Frequência de transição (fT)

#### 5.5 Configurações de Amplificadores com FET
- Configuração fonte-comum (FC):
  - Ganho de tensão
  - Impedância de entrada muito alta
  - Impedância de saída
  
- Configuração porta-comum (GC):
  - Características similares à base-comum
  
- Configuração dreno-comum (DC) - Seguidor de fonte:
  - Ganho unitário
  - Alta impedância de entrada
  - Baixa impedância de saída

---

### Unidade 6: Fontes de Alimentação (7h)

#### 6.1 Reguladores Lineares
- Reguladores com diodo Zener
- Reguladores com transistor série (série-pass)
- Reguladores com transistor shunt
- Análise de regulação de linha e de carga
- Limitação de corrente (current limiting)
- Proteção contra curto-circuito

#### 6.2 Circuitos Integrados Reguladores
- Reguladores de tensão fixos: 78xx, 79xx
- Reguladores de tensão ajustáveis: LM317, LM337
- Cálculo de componentes externos
- Dissipação de potência e heatsinks
- Reguladores de baixa queda (LDO - Low Dropout)

#### 6.3 Fontes Chaveadas (Conceitos)
- Introdução às fontes chaveadas (SMPS)
- Vantagens sobre fontes lineares
- Topologias básicas: buck, boost, buck-boost
- Introdução aos conversores DC-DC

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Fontes de Alimentação
- **Retificadores e reguladores**: Alimentação de equipamentos de telecom
- **Fontes redundantes**: Sistemas de alta confiabilidade
- **Conversores DC-DC**: Adaptação de tensões em circuitos
- **Proteção contra surtos**: Circuitos de proteção em estações

### 3.2 Amplificadores de Sinal
- **Pré-amplificadores**: Amplificação de sinais fracos de sensores/antenas
- **Amplificadores de potência**: Excursão de potência em transmissores
- **Amplificadores de instrumentação**: Medição de sinais
- **Buffers**: Isolamento de estágios

### 3.3 Circuitos de RF (Base)
- **Diodos de detecção**: Demoduladores de AM simples
- **Diodos varicap**: Sintonia em receptores de rádio
- **Amplificadores de baixo ruído**: Primeiros estágios de receptores
- **Osciladores (introdução)**: Base para geração de portadoras

### 3.4 Processamento Analógico
- **Amplificadores diferenciais**: Rejeição de ruído de modo comum
- **Conversores A/D (preparação)**: Condicionamento de sinais
- **Filtros ativos**: Processamento de sinais analógicos
- **Choppers e moduladores**: Processamento de sinais precisos

### 3.5 Sistemas de Controle
- **Drivers**: Acionamento de atuadores
- **Circuitos de proteção**: Limitação de corrente e tensão
- **Sensores e condicionamento**: Interface com o mundo físico
- **Realimentação**: Controle de ganho e estabilidade

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Exposição de conceitos físicos e matemáticos
- **Aulas de exercícios**: Resolução de problemas de análise e projeto
- **Laboratórios práticos**: Montagem e medição de circuitos
- **Simulações computacionais**: LTspice, Multisim, Proteus
- **Projetos**: Projeto de amplificador ou fonte de alimentação

### 4.2 Recursos Didáticos
- Quadro e projetor multimídia
- Kits de eletrônica analógica (protoboards, componentes)
- Osciloscópios, multímetros, geradores de função
- Fontes de alimentação DC
- Software de simulação: LTspice, Multisim, Proteus
- Componentes semicondutores diversos (datasheets)

### 4.3 Avaliação

**Instrumentos:**
- Provas teóricas (2 avaliações) - 50%
- Laboratórios práticos - 25%
- Projeto de circuito - 15%
- Listas de exercícios e participação - 10%

**Critérios:**
- Compreensão da física dos semicondutores
- Capacidade de análise de circuitos com diodos e transistores
- Habilidade em projetar amplificadores com BJT e FET
- Conhecimento de técnicas de polarização
- Proficiência em simulação de circuitos eletrônicos

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Fundamentos de semicondutores. Junção PN |
| 2 | Diodos: características e modelos |
| 3 | Retificadores e filtros |
| 4 | Aplicações do diodo. Zener, LEDs |
| 5 | **1ª Avaliação** |
| 6 | BJT: estrutura e funcionamento |
| 7 | Polarização do BJT |
| 8 | Modelos de pequenos sinais do BJT |
| 9 | Amplificadores EC, BC, CC |
| 10 | **2ª Avaliação** |
| 11 | Amplificadores multietapa e diferenciais |
| 12 | Resposta em frequência |
| 13 | JFET e MOSFET |
| 14 | Amplificadores com FET. Fontes de alimentação |
| 15 | Reguladores de tensão. Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. SEDRA, A. S.; SMITH, K. C. **Microeletrônica**. 7. ed. Pearson, 2016.
2. BOYLESTAD, R. L.; NASHELSKY, L. **Dispositivos Eletrônicos e Teoria de Circuitos**. 11. ed. Pearson, 2013.
3. MALVINO, A. P. **Eletrônica**. 7. ed. McGraw-Hill, 2011.

### Bibliografia Complementar
4. RAZAVI, B. **Fundamentals of Microelectronics**. 2. ed. Wiley, 2013.
5. HORENSTEIN, M. N. **Microelectronic Circuits and Devices**. 2. ed. Prentice Hall, 1996.
6. NEAMEN, D. A. **Semiconductor Physics and Devices: Basic Principles**. 4. ed. McGraw-Hill, 2011.
7. GRAY, P. R.; HURST, P. J.; LEWIS, S. H.; MEYER, R. G. **Analysis and Design of Analog Integrated Circuits**. 5. ed. Wiley, 2009.
8. ALLEN, P. E.; HOLBERG, D. R. **CMOS Analog Circuit Design**. 3. ed. Oxford University Press, 2011.

### Recursos Online
- [LTspice](https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html) - Simulador gratuito
- [Falstad Circuit Simulator](http://www.falstad.com/circuit/) - Simulação online
- [All About Circuits](https://www.allaboutcircuits.com/) - Tutoriais de eletrônica
- [IEEE Xplore](https://ieeexplore.ieee.org/) - Artigos técnicos

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Explicar o funcionamento físico de semicondutores e a formação da junção PN

**RA2** - Analisar e projetar circuitos retificadores, limitadores e reguladores com diodos

**RA3** - Compreender o princípio de funcionamento e modelos do transistor bipolar (BJT)

**RA4** - Projetar circuitos de polarização estáveis para transistores BJT e FET

**RA5** - Analisar e projetar amplificadores com BJT em configurações EC, BC e CC

**RA6** - Compreender o funcionamento de transistores de efeito de campo (JFET e MOSFET)

**RA7** - Analisar a resposta em frequência de amplificadores e calcular banda passante

**RA8** - Projetar fontes de alimentação reguladas lineares com componentes discretos e CI

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: A eletrônica analógica requer prática. Não basta entender a teoria; você precisa resolver muitos exercícios e fazer simulações para desenvolver intuição sobre o comportamento dos circuitos.

> 🔧 **Laboratório**: A montagem prática é essencial. Comece sempre com simulação, mas valide com medições reais. Os componentes reais têm tolerâncias e comportamentos que diferem do ideal.

> 💻 **Simulação**: Use o LTspice (gratuito da Analog Devices) para verificar seus projetos antes de montar. É uma ferramenta profissional usada na indústria.

> 📊 **Datasheets**: Aprenda a ler datasheets de componentes. Eles contêm todas as informações necessárias para projeto: limites máximos, características típicas, curvas gráficas.

> 🔗 **Conexões**: Esta disciplina é pré-requisito para:
> - Eletrônica II (amplificadores operacionais, realimentação)
> - Eletrônica Aplicada (circuitos de RF)
> - Circuitos Elétricos II (resposta em frequência detalhada)
> - Projetos de hardware em geral

> 🎯 **Mercado**: O conhecimento de eletrônica analógica é fundamental para:
> - Projeto de hardware
> - Manutenção de equipamentos
> - Integração de sistemas
> - Internet das Coisas (IoT)
> - Sistemas embarcados

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025