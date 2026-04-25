---
tags: [elétrica, eletrônica, RF, comunicações, amplificadores, osciladores, engenharia]
semestre: 7
area: Elétrica
creditos: 4
dificuldade: alta
importancia: alta
código: ELE015
carga_horaria: 60h (4 créditos)
status: completo
pré_requisitos: [Eletronica II, Circuitos Eletricos II]
links: [Principios Comunicacoes, Microondas, Antenas, Comunicacoes Digitais]
aliases: [Eletronica_Aplicada]
keywords: [elétrica, eletrônica, RF, comunicações, amplificadores, osciladores, engenharia]
resumo: "Estudo de circuitos eletrônicos aplicados a sistemas de comunicação: amplificadores de RF, osciladores, misturadores, moduladores, demoduladores e sintetizadores de frequência."
---

# Eletrônica Aplicada

## 1. Ementa Oficial

Estudo de circuitos eletrônicos aplicados a sistemas de comunicação: amplificadores de RF, osciladores, misturadores, moduladores, demoduladores e sintetizadores de frequência. Projeto de estágios de RF para transmissores e receptores de comunicação.

### Objetivos da Disciplina

**Objetivo Geral:**
Capacitar o estudante a projetar e analisar circuitos eletrônicos para aplicações em comunicações de radiofrequência (RF), incluindo amplificadores, osciladores, misturadores e estágios de processamento de sinais modulados.

**Objetivos Específicos:**
- Analisar e projetar amplificadores de RF e de banda estreita
- Compreender e projetar osciladores senoidais e de alta frequência
- Entender o funcionamento de misturadores e conversores de frequência
- Analisar circuitos de modulação e demodulação AM/FM
- Projetar sintetizadores de frequência e PLLs
- Conhecer técnicas de casamento de impedância em RF
- Compreender arquiteturas de transmissores e receptores super-heterodinos

---

## 2. Conteúdo Programático

### Unidade 1: Fundamentos de Radiofrequência (6h)

#### 1.1 Parâmetros de Dispersão (S-Parameters)
- Definição de parâmetros S
- Matriz de dispersão para redes de duas portas
- S11 (coeficiente de reflexão de entrada)
- S21 (ganho de transmissão direta)
- S12 (isolamento reverso)
- S22 (coeficiente de reflexão de saída)
- Medição de parâmetros S com analisador de rede vetorial (VNA)

#### 1.2 Modelos de Transistores em RF
- Modelo híbrido-π de alta frequência
- Frequência de transição (fT) e frequência máxima de oscilação (fmax)
- Capacitâncias parasitas
- Resistências de base, emissor e coletor
- Modelos para MOSFET em RF

#### 1.3 Componentes Passivos em RF
- Indutores em RF: qualidade (Q), auto ressonância
- Capacitores em RF: capacitância parasita
- Resistores em RF: indutância parasita
- Transformadores e baluns em RF

---

### Unidade 2: Amplificadores de RF (12h)

#### 2.1 Considerações de Projeto
- Estabilidade de amplificadores (fator de Rollett K)
- Círculos de estabilidade
- Condições de estabilidade incondicional
- Margem de estabilidade

#### 2.2 Casamento de Impedância
- Teorema da máxima transferência de potência
- Transformação de impedância com L, T e Π
- Redes de casamento de banda estreita
- Redes de casamento de banda larga
- Casamento com linhas de transmissão (stubs)

#### 2.3 Configurações de Amplificadores
- Amplificadores de baixo ruído (LNA)
- Amplificadores de potência (PA)
- Amplificadores de ganho
- Amplificadores de banda estreita vs banda larga

#### 2.4 Amplificadores de Potência
- Classes de operação: A, B, AB, C
- Eficiência e linearidade
- Distorção harmônica e intermodulação
- Amplificadores de RF em GaAs, GaN e LDMOS

---

### Unidade 3: Osciladores (10h)

#### 3.1 Critérios de Oscilação
- Critério de Barkhausen
- Condições de amplitude e fase
- Estabilidade de amplitude e frequência

#### 3.2 Osciladores LC
- Oscilador Colpitts
- Oscilador Hartley
- Oscilador Clapp
- Oscilador Seiler
- Análise de frequência de oscilação

#### 3.3 Osciladores de Cristal
- Propriedades piezoelétricas do quartzo
- Modelo elétrico do cristal
- Frequência de série e paralelo
- Osciladores Pierce
- Estabilidade de frequência

#### 3.4 Osciladores de RF e Micro-ondas
- Osciladores com diodo Gunn
- Osciladores com diodo IMPATT
- Osciladores de estado sólido
- Sintetizadores de frequência direta (DDS)

---

### Unidade 4: Misturadores e Conversores de Frequência (10h)

#### 4.1 Princípios de Mistura
- Conversão de frequência: up-conversion e down-conversion
- Produtos de intermodulação
- Figura de ruído de misturadores
- Isolamento entre portas (LO-RF, LO-IF, RF-IF)

#### 4.2 Tipos de Misturadores
- Misturadores passivos (diodos)
- Misturadores ativos (FET, BJT)
- Misturadores balanceados
- Misturadores de duplo balanceado (ring diode)
- Misturadores de imagem rejeitada

#### 4.3 Osciladores Controlados por Tensão (VCO)
- Princípio de funcionamento
- Sensibilidade (K_VCO)
- Linearidade de sintonia
- Ruído de fase (phase noise)
- VCOs LC e de cristal

---

### Unidade 5: Sintetizadores de Frequência e PLL (10h)

#### 5.1 Arquiteturas de Sintetizadores
- Sintetizadores diretos (DDS)
- Sintetizadores indiretos (PLL)
- Sintetizadores híbridos
- Sintetizadores fracionários

#### 5.2 Phase-Locked Loop (PLL)
- Componentes do PLL: detector de fase, filtro de loop, VCO
- Detector de fase digital (phase-frequency detector)
- Filtro de loop passivo e ativo
- Função de transferência do PLL
- Largura de banda do loop e estabilidade

#### 5.3 PLLs em Comunicações
- Multiplicação de frequência
- Divisão de frequência
- Modulação e demodulação FM com PLL
- Recuperação de clock (CDR)
- Sintetizadores de frequência com PLL

#### 5.4 Sintetizadores com Divisor Fracionário (Fractional-N)
- Princípio de funcionamento
- Spurious e técnicas de redução
- Sigma-delta modulation em PLLs

---

### Unidade 6: Moduladores e Demoduladores (8h)

#### 6.1 Moduladores AM
- Modulação de amplitude (AM)
- Moduladores de alto nível
- Moduladores de baixo nível
- Modulação em quadratura (QAM)

#### 6.2 Moduladores FM
- Modulação de frequência (FM)
- Desvio de frequência e índice de modulação
- Moduladores com varactor
- Moduladores com PLL

#### 6.3 Demoduladores AM
- Detetores de envelope
- Detetores síncronos
- Detetores de produto

#### 6.4 Demoduladores FM
- Discriminadores de frequência
- Detetores de quadratura
- Detetores com PLL
- Limitadores de amplitude

---

### Unidade 7: Arquiteturas de RF (4h)

#### 7.1 Transmissores
- Arquitetura de super-heterodino
- Transmissores de conversão direta (zero-IF)
- Transmissores de baixa IF
- Transmissores de conversão direta (direct conversion)

#### 7.2 Receptores
- Receptor super-heterodino
- Problema da frequência imagem
- Receptor de conversão direta (zero-IF, homodino)
- Receptor de baixa IF
- Receptores de digitalização direta (software-defined radio)

#### 7.3 Considerações de Sistema
- Figura de ruído de sistema
- Ponto de compressão de 1 dB (P1dB)
- Ponto de interceptação de terceira ordem (IP3)
- Dinâmica de receptores
- Seletividade e sensibilidade

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Estações Base Celulares
- **Amplificadores de potência**: Transmissores de RF para 2G/3G/4G/5G
- **LNAs**: Receptores de baixo ruído em torres celulares
- **Duplexadores**: Separação de TX/RX com Filtros
- **Sintetizadores**: Geração de portadoras precisas

### 3.2 Sistemas de Micro-ondas
- **Links de micro-ondas**: Amplificadores de banda larga
- **Satélites**: Transceptores de RF para comunicação espacial
- **Radares**: Osciladores estáveis e misturadores de alta performance
- **Rádios definidos por software (SDR)**: Arquiteturas flexíveis

### 3.3 Sistemas Ópticos
- **Moduladores ópticos**: Eletro-ópticos e eletro-absortivos
- **Receptores ópticos**: TIAs (Transimpedance Amplifiers)
- **PLLs em sistemas ópticos**: Recuperação de clock

### 3.4 Comunicações Sem Fio
- **Wi-Fi**: Amplificadores de potência para 2.4 GHz e 5 GHz
- **Bluetooth**: Transceptores de baixa potência
- **IoT**: Circuitos de RF para baixo consumo
- **RFID**: Leitores e tags de RF

### 3.5 Instrumentação de RF
- **Analisadores de espectro**: Misturadores e sintetizadores internos
- **Geradores de sinais**: VCOs e sintetizadores de alta pureza
- **Analisadores de rede**: Medição de parâmetros S

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Análise de circuitos e derivações matemáticas
- **Aulas práticas**: Simulação de circuitos com software (ADS, Microwave Office, LTspice)
- **Laboratórios**: Montagem e medição de circuitos de RF
- **Projetos**: Projeto de blocos de RF (amplificador, oscilador, misturador)
- **Seminários**: Apresentação de artigos e tendências tecnológicas

### 4.2 Recursos Didáticos
- Projetor multimídia e quadro
- Software de simulação de RF: Keysight ADS, AWR Microwave Office, LTspice
- Equipamentos de laboratório: VNA, analisador de espectro, gerador de sinais
- Kits de montagem de circuitos de RF
- Bibliografia especializada e datasheets de componentes

### 4.3 Avaliação

**Instrumentos:**
- Provas teóricas (2 avaliações) - 50%
- Projetos de simulação - 25%
- Laboratórios práticos - 15%
- Seminário - 10%

**Critérios:**
- Compreensão dos princípios de operação dos circuitos de RF
- Capacidade de análise com parâmetros S
- Habilidade em projetar circuitos de casamento de impedância
- Conhecimento de arquiteturas de transmissores e receptores
- Proficiência em uso de software de simulação de RF

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Parâmetros S. Modelos de transistores em RF |
| 2 | Componentes passivos em RF |
| 3 | Amplificadores de RF: estabilidade |
| 4 | **1ª Avaliação** |
| 5 | Casamento de impedância em RF |
| 6 | Amplificadores de baixo ruído e de potência |
| 7 | Osciladores LC e de cristal |
| 8 | Osciladores de RF e VCOs |
| 9 | **2ª Avaliação** |
| 10 | Misturadores e conversores de frequência |
| 11 | Phase-Locked Loops (PLL) |
| 12 | Sintetizadores de frequência |
| 13 | Moduladores AM e FM |
| 14 | Demoduladores e arquiteturas de RF |
| 15 | Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. POZAR, D. M. **Microwave Engineering**. 4. ed. Wiley, 2011.
2. GONZALEZ, G. **Microwave Transistor Amplifiers: Analysis and Design**. 2. ed. Prentice Hall, 1996.
3. RAZAVI, B. **RF Microelectronics**. 2. ed. Prentice Hall, 2011.

### Bibliografia Complementar
4. LUDWIG, R.; BOGDANOV, G. **RF Circuit Design: Theory and Applications**. 2. ed. Pearson, 2008.
5. BOWICK, C. **RF Circuit Design**. 2. ed. Newnes, 2007.
6. LEE, T. H. **The Design of CMOS Radio-Frequency Integrated Circuits**. 2. ed. Cambridge University Press, 2004.
7. MAAAS, S. A. **Nonlinear Microwave and RF Circuits**. 2. ed. Artech House, 2003.
8. EGAN, W. F. **Practical RF System Design**. Wiley, 2003.

### Recursos Online
- [IEEE Microwave Magazine](https://ieee-mtt.org/publications/magazine/)
- [Microwave 101](https://www.microwavejournal.com/resources/microwave-101) - Tutoriais de RF e micro-ondas
- [Keysight EEsof](https://www.keysight.com/us/en/products/software/eesof-eda.html) - Recursos de RF e simulação
- [Microwave Office](https://www.awrcorp.com/) - Software de projeto de RF

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Analisar circuitos de RF usando parâmetros de dispersão (S-parameters)

**RA2** - Projetar amplificadores de RF estáveis com casamento de impedância adequado

**RA3** - Projetar osciladores senoidais de RF e micro-ondas

**RA4** - Compreender e analisar misturadores e conversores de frequência

**RA5** - Projetar e analisar sintetizadores de frequência baseados em PLL

**RA6** - Analisar circuitos de modulação e demodulação AM/FM

**RA7** - Compreender arquiteturas de transmissores e receptores super-heterodinos e de conversão direta

**RA8** - Utilizar software de simulação de RF para projeto e análise de circuitos

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: A eletrônica aplicada a RF é um campo especializado. Domine os conceitos de parâmetros S desde o início, pois são a linguagem padrão da engenharia de RF.

> 📡 **Importância da Disciplina**: Esta disciplina conecta a eletrônica básica com as aplicações reais de telecomunicações. Todos os conceitos aqui são usados em celulares, Wi-Fi, rádios, satélites.

> 💻 **Simulação é Fundamental**: O uso de software como ADS, Microwave Office ou até LTspice é essencial. Na RF, a teoria e a prática frequentemente divergem devido a parasitas.

> 🔧 **Prática**: Se possível, faça medições reais com equipamentos de RF. A experiência prática é inestimável nesta área.

> 🔗 **Conexões**: Esta disciplina integra conhecimentos de:
> - Eletrônica I e II (transistores, análise de circuitos)
> - Circuitos Elétricos II (transformada de Laplace, resposta em frequência)
> - Propagação e Antenas (ondas eletromagnéticas)
> - Micro-ondas (guias de onda, componentes de RF)

> 🚀 **Carreira**: Engenheiros de RF são muito demandados em indústrias de telecomunicações, semicondutores, defesa e pesquisa.

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/2  
**Última atualização:** Abril/2025