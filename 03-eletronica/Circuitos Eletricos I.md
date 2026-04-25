---
tags: [elétrica, circuitos, análise, corrente contínua, corrente alternada, engenharia]
semestre: 4
area: Elétrica
creditos: 6
dificuldade: alta
importancia: critica
código: ELE001
carga_horaria: 90h (6 créditos)
status: completo
pré_requisitos: [Fenomenos Eletromagneticos]
links: [Circuitos Eletricos II, Eletronica I, Principios Comunicacoes]
aliases: [Circuitos_Eletricos_I]
keywords: [elétrica, circuitos, análise, corrente contínua, corrente alternada, engenharia]
resumo: "Estudo dos circuitos elétricos em corrente contínua (CC) e corrente alternada (CA)."
---

# Circuitos Elétricos I

## 1. Ementa Oficial

Estudo dos circuitos elétricos em corrente contínua (CC) e corrente alternada (CA). Análise de circuitos resistivos, capacitivos e indutivos. Leis de Kirchhoff, teoremas de circuitos, análise de regime permanente senoidal. Introdução aos circuitos trifásicos.

### Objetivos da Disciplina

**Objetivo Geral:**
Proporcionar ao estudante os fundamentos teóricos e práticos da análise de circuitos elétricos em corrente contínua e alternada, desenvolvendo habilidades para modelar, analisar e resolver circuitos elétricos lineares.

**Objetivos Específicos:**
- Aplicar as leis de Kirchhoff na análise de circuitos elétricos
- Dominar técnicas de análise de circuitos resistivos, capacitivos e indutivos
- Analisar circuitos de primeira e segunda ordem
- Compreender o regime permanente senoidal e representação fasorial
- Aplicar teoremas de circuitos (Thévenin, Norton, superposição)
- Analisar circuitos trifásicos equilibrados
- Utilizar software de simulação de circuitos (SPICE, Multisim, LTspice)

---

## 2. Conteúdo Programático

### Unidade 1: Conceitos Fundamentais e Leis de Kirchhoff (12h)

#### 1.1 Grandezas Elétricas Básicas
- Carga elétrica (Q)
- Corrente elétrica (I): definicao, unidades, convenção
- Tensão elétrica (V): potencial, diferença de potencial
- Potência elétrica (P) e energia (W)
- Passive sign convention (convenção de sinais passiva)

#### 1.2 Elementos de Circuitos
- Resistores: Lei de Ohm, resistividade, condutância
- Capacitores: capacitância, relação carga-tensão, energia armazenada
- Indutores: indutância, relação corrente-tensão, energia armazenada
- Fontes independentes: de tensão e de corrente
- Fontes dependentes (controladas): VCVS, VCCS, CCVS, CCCS

#### 1.3 Lei de Kirchhoff das Correntes (LKC)
- Lei dos nós (1ª Lei de Kirchhoff)
- Conservação de carga
- Análise nodal básica

#### 1.4 Lei de Kirchhoff das Tensões (LKT)
- Lei das malhas (2ª Lei de Kirchhoff)
- Conservação de energia
- Análise de malhas básica

---

### Unidade 2: Circuitos Resistivos em Corrente Contínua (15h)

#### 2.1 Resistores em Série e em Paralelo
- Associação série: Req = R1 + R2 + ... + Rn
- Associação paralelo: 1/Req = 1/R1 + 1/R2 + ... + 1/Rn
- Divisor de tensão
- Divisor de corrente
- Transformações Y-Δ (estrela-triângulo)

#### 2.2 Análise Nodal Sistemática
- Nó de referência (terra)
- Equações de KCL nos nós essenciais
- Caso com fontes de tensão independentes
- Caso com fontes de tensão dependentes
- Matriz de condutâncias

#### 2.3 Análise de Malhas Sistemática
- Definição de correntes de malha
- Equações de KVL nas malhas
- Caso com fontes de corrente independentes
- Caso com fontes de corrente dependentes
- Matriz de resistências

#### 2.4 Técnicas de Análise Avançadas
- Análise por inspeção
- Circuitos com múltiplos níveis de tensão
- Supermalhas
- Supernós

---

### Unidade 3: Teoremas de Circuitos (12h)

#### 3.1 Linearidade e Superposição
- Definição de circuito linear
- Princípio da superposição
- Aplicação em circuitos com múltiplas fontes
- Limitações da superposição (potência)

#### 3.2 Transformação de Fontes
- Equivalência fonte de tensão ↔ fonte de corrente
- Resistência/impedância interna
- Transformação de fontes dependentes

#### 3.3 Teorema de Thévenin
- Circuito equivalente de Thévenin
- Cálculo de Vth (tensão de circuito aberto)
- Cálculo de Rth (resistência equivalente)
- Teorema da máxima transferência de potência

#### 3.4 Teorema de Norton
- Circuito equivalente de Norton
- Cálculo de In (corrente de curto-circuito)
- Equivalência Thévenin-Norton

#### 3.5 Outros Teoremas
- Teorema de Millman
- Teorema da reciprocidade
- Transformação de potencial (deslocamento de fonte)

---

### Unidade 4: Circuitos de Primeira Ordem (12h)

#### 4.1 Circuitos RL em CC
- Equação diferencial do circuito RL
- Resposta natural (solução homogênea)
- Resposta forçada (solução particular)
- Resposta completa: i(t) = If + (I0 - If)e^(-t/τ)
- Constante de tempo: τ = L/R
- Crescimento e decaimento exponencial

#### 4.2 Circuitos RC em CC
- Equação diferencial do circuito RC
- Resposta natural e forçada
- Constante de tempo: τ = RC
- Carga e descarga do capacitor
- Aplicações: temporizadores, filtros

#### 4.3 Análise Completa de Circuitos de 1ª Ordem
- Resposta a degrau (step response)
- Resposta a pulso
- Resposta a rampa
- Método dos três elementos (método prático)

#### 4.4 Aplicações Práticas
- Circuitos de comutação
- Circuitos de temporização
- Filtros passa-baixa de 1ª ordem
- Filtros passa-alta de 1ª ordem

---

### Unidade 5: Circuitos de Segunda Ordem (9h)

#### 5.1 Circuito RLC Série em CC
- Equação diferencial de 2ª ordem
- Tipos de resposta:
  - Superamortecida (sobredamped)
  - Criticamente amortecida
  - Subamortecida (underdamped)
  - Oscilatória (sem amortecimento)
- Frequência natural e fator de amortecimento
- Constantes de tempo complexas

#### 5.2 Circuito RLC Paralelo em CC
- Equações de análise
- Comportamento dual do série
- Resposta natural e forçada

#### 5.3 Análise Completa
- Resposta a degrau em circuitos RLC
- Comportamento transitório e permanente
- Aplicações em filtros ressonantes

---

### Unidade 6: Regime Permanente Senoidal (15h)

#### 6.1 Conceitos de Corrente Alternada
- Sinais senoidais: v(t) = Vm·cos(ωt + φ)
- Amplitude, frequência, período, fase
- Valores médio e eficaz (RMS)
- Potência em CA: ativa, reativa, aparente
- Fator de potência

#### 6.2 Representação Fasorial
- Números complexos: forma retangular e polar
- Transformada de Steinmetz (representação fasorial)
- Impedância complexa: Z = R + jX
- Reatância indutiva: XL = ωL
- Reatância capacitiva: XC = 1/(ωC)
- Admitância complexa: Y = G + jB

#### 6.3 Análise de Circuitos em CA
- Leis de Kirchhoff no domínio fasorial
- Análise nodal fasorial
- Análise de malhas fasorial
- Impedâncias em série e paralelo
- Divisores de tensão e corrente fasoriais

#### 6.4 Diagramas Fasoriais
- Representação gráfica de tensões e correntes
- Triângulos de impedância, tensão e potência
- Correção do fator de potência

#### 6.5 Resonância
- Circuito RLC série em ressonância
- Frequência de ressonância: ω0 = 1/√(LC)
- Fator de qualidade (Q)
- Largura de faixa e seletividade
- Circuito RLC paralelo em ressonância

---

### Unidade 7: Potência em Corrente Alternada (9h)

#### 7.1 Potência Instantânea e Média
- p(t) = v(t)·i(t)
- Potência ativa (P): média no período
- Potência reativa (Q)
- Potência aparente (S)
- Triângulo de potências: S² = P² + Q²

#### 7.2 Fator de Potência
- Definição: FP = cos(θ) = P/S
- Importância econômica e técnica
- Correção do fator de potência com capacitores
- Cálculo do capacitor para correção

#### 7.3 Potência Complexa
- Conceito de potência complexa: S = P + jQ = V·I*
- Conservação da potência complexa
- Cálculo de potência em circuitos trifásicos

#### 7.4 Máxima Transferência de Potência em CA
- Impedância conjugada
- Teorema da máxima transferência em CA
- Eficiência na transferência de potência

---

### Unidade 8: Circuitos Trifásicos (6h)

#### 8.1 Sistemas Polifásicos
- Geração de tensões polifásicas
- Sistemas equilibrados e desequilibrados
- Sequência de fases (direta e inversa)

#### 8.2 Ligações em Estrela (Y)
- Tensões de fase e de linha
- Correntes de fase e de linha
- Relação VL = √3·VF (sistema equilibrado)
- Neutro e corrente de neutro

#### 8.3 Ligações em Triângulo (Δ)
- Tensões de fase e de linha
- Correntes de fase e de linha
- Relação IL = √3·IF (sistema equilibrado)

#### 8.4 Potência em Sistemas Trifásicos
- Potência ativa, reativa e aparente trifásica
- Medição de potência: método dos dois wattímetros
- Aplicações: motores, sistemas de distribuição

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Fontes de Alimentação
- **Retificadores**: Conversão CA-CC para equipamentos de telecom
- **Filtros de entrada**: Eliminação de ruído da rede elétrica
- **Reguladores de tensão**: Estabilização para circuitos sensíveis
- **UPS**: No-breaks para proteção de equipamentos críticos

### 3.2 Circuitos de Sinal
- **Acoplamento AC/DC**: Circuitos RC para separação de componentes
- **Filtros passivos**: RC, RL, RLC para seleção de frequência
- **Circuitos de偏置 (bias)**: Polarização de amplificadores
- **Redes de equalização**: Compensação de resposta em frequência

### 3.3 Sistemas de Transmissão
- **Linhas de transmissão**: Modelagem com parâmetros RLCG
- **Impedância característica**: Z0 = √(L/C)
- **Casamento de impedâncias**: Máxima transferência de potência RF
- **Estações de rádio**: Sistemas de alimentação de RF

### 3.4 Instrumentação e Medição
- **Pontes de impedância**: Medição de componentes
- **Analisadores de espectro**: Princípios de circuitos ressonantes
- **Osciloscópios**: Circuitos de deflexão vertical/horizontal
- **Medidores de potência**: Watts, dBm em sistemas de RF

### 3.5 Proteção e Segurança
- **Dispositivos de proteção**: Fusíveis, disjuntores, varistores
- **Aterramento**: Sistemas de proteção contra surtos
- **Descargas atmosféricas**: Proteção de equipamentos de telecom
- **Isolamento galvânico**: Transformadores e optoacopladores

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Exposição de conceitos com demonstrações matemáticas
- **Aulas práticas**: Resolução de exercícios em sala
- **Laboratórios**: Montagem e análise de circuitos reais
- **Simulações computacionais**: Uso de software SPICE (LTspice, Multisim, Proteus)
- **Projetos**: Desenvolvimento de circuitos aplicados

### 4.2 Recursos Didáticos
- Quadro e projetor multimídia
- Kits de circuitos elétricos (protoboards, componentes)
- Osciloscópios, multímetros, geradores de função
- Software de simulação (LTspice, Multisim, Proteus, QUCS)
- Material didático digital (apostilas, vídeos, simulações interativas)

### 4.3 Avaliação

**Instrumentos:**
- Provas teóricas (2 avaliações) - 50%
- Laboratórios práticos - 25%
- Projeto de circuito - 15%
- Participação e listas de exercícios - 10%

**Critérios:**
- Domínio das leis e teoremas de circuitos
- Capacidade de análise de circuitos CC e CA
- Habilidade em simulação computacional
- Competência em montagem experimental
- Clareza na apresentação de soluções

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Grandezas elétricas. Elementos de circuitos |
| 2 | Leis de Kirchhoff (LKC e LKT) |
| 3 | Circuitos resistivos: associações e divisores |
| 4 | Análise nodal e de malhas |
| 5 | **1ª Avaliação** |
| 6 | Teoremas: superposição, Thévenin, Norton |
| 7 | Circuitos de 1ª ordem: RL e RC |
| 8 | Aplicações de circuitos de 1ª ordem |
| 9 | Circuitos de 2ª ordem: RLC |
| 10 | **2ª Avaliação** |
| 11 | Regime permanente senoidal. Fasores |
| 12 | Análise de circuitos em CA. Impedância |
| 13 | Ressonância. Potência em CA |
| 14 | Circuitos trifásicos |
| 15 | Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. ALEXANDER, C. K.; SADIKU, M. N. O. **Fundamentos de Circuitos Elétricos**. 5. ed. McGraw-Hill, 2013.
2. BOYLESTAD, R. L. **Introdução à Análise de Circuitos**. 12. ed. Pearson, 2012.
3. NILSSON, J. W.; RIEDEL, S. A. **Circuitos Elétricos**. 8. ed. Pearson, 2009.

### Bibliografia Complementar
4. HAYT, W. H.; KEMMERLY, J. E.; DURBIN, S. M. **Análise de Circuitos em Engenharia**. 7. ed. McGraw-Hill, 2008.
5. DORF, R. C.; SVOBODA, J. A. **Introdução aos Circuitos Elétricos**. 8. ed. LTC, 2012.
6. IRWIN, J. D. **Análise de Circuitos em Engenharia**. 4. ed. LTC, 2000.
7. JOHNSON, D. E.; HILBURN, J. L.; JOHNSON, J. R. **Fundamentos de Análise de Circuitos Elétricos**. 4. ed. LTC, 1994.

### Recursos Online
- [LTspice](https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html) - Simulador gratuito da Analog Devices
- [Falstad Circuit Simulator](http://www.falstad.com/circuit/) - Simulador online interativo
- [All About Circuits](https://www.allaboutcircuits.com/) - Tutoriais e recursos educacionais
- [IEEE Xplore](https://ieeexplore.ieee.org/) - Artigos técnicos em engenharia elétrica

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Aplicar as leis de Kirchhoff e técnicas de análise nodal e de malhas em circuitos elétricos

**RA2** - Utilizar teoremas de circuitos (Thévenin, Norton, superposição) para simplificação e análise

**RA3** - Analisar circuitos de primeira e segunda ordem em regime transitório

**RA4** - Representar e analisar circuitos em regime permanente senoidal usando fasores

**RA5** - Calcular potências ativa, reativa e aparente em circuitos de corrente alternada

**RA6** - Analisar circuitos trifásicos equilibrados em ligações estrela e triângulo

**RA7** - Simular circuitos elétricos usando software adequado (SPICE)

**RA8** - Montar e analisar experimentalmente circuitos elétricos básicos em laboratório

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: A análise de circuitos é uma habilidade que se desenvolve com prática. Resolva o máximo de exercícios possível, variando as configurações de circuitos.

> 🔧 **Prática em Laboratório**: A teoria ganha vida no laboratório. Preste atenção às medidas e compare com os valores teóricos calculados.

> 💻 **Simulação**: Use o LTspice (gratuito) para verificar suas soluções antes de montar circuitos. É uma ferramenta essencial para engenheiros.

> ⚡ **Segurança**: Sempre verifique limites de tensão e corrente dos componentes. O resistor certo no lugar errado pode queimar!

> 🔗 **Conexões**: Esta disciplina é a base para Eletrônica, Circuitos II, Princípios de Comunicações e muitas outras. Uma base sólida aqui é fundamental.

> 📡 **Telecom**: Os conceitos de impedância, ressonância e casamento são essenciais para projetos de RF e antenas que você verá adiante.

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025