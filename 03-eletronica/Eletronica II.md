---
tags: [elétrica, eletrônica, amplificadores operacionais, realimentação, filtros, osciladores, engenharia]
semestre: 6
area: Elétrica
creditos: 6
dificuldade: alta
importancia: critica
código: ELE012
carga_horaria: 90h (6 créditos)
status: completo
pré_requisitos: [Eletronica I]
links: [Eletronica Aplicada, Processamento Digital Sinais, Microprocessadores]
aliases: [Eletronica_II]
keywords: [elétrica, eletrônica, amplificadores operacionais, realimentação, filtros, osciladores, engenharia]
resumo: "Estudo de amplificadores operacionais e suas aplicações: realimentação negativa, amplificadores de instrumentação, filtros ativos, conversores analógico-digitais e digital-analógicos, geradores de funções e reguladores c"
---

# Eletrônica II

## 1. Ementa Oficial

Estudo de amplificadores operacionais e suas aplicações: realimentação negativa, amplificadores de instrumentação, filtros ativos, conversores analógico-digitais e digital-analógicos, geradores de funções e reguladores chaveados. Projeto de sistemas eletrônicos analógicos integrados.

### Objetivos da Disciplina

**Objetivo Geral:**
Capacitar o estudante a analisar e projetar circuitos eletrônicos utilizando amplificadores operacionais e técnicas de realimentação, com ênfase em aplicações de processamento de sinais, instrumentação e conversão A/D e D/A.

**Objetivos Específicos:**
- Compreender o funcionamento e características dos amplificadores operacionais
- Aplicar técnicas de realimentação negativa em amplificadores
- Projetar amplificadores de instrumentação e condicionadores de sinais
- Analisar e projetar filtros ativos de diferentes respostas
- Compreender os princípios de conversão A/D e D/A
- Projetar osciladores e geradores de funções
- Analisar reguladores de tensão chaveados (SMPS)

---

## 2. Conteúdo Programático

### Unidade 1: Amplificadores Operacionais (12h)

#### 1.1 Introdução aos Op-Amps
- Simbolo e terminais
- Características ideais:
  - Ganho de tensão infinito
  - Impedância de entrada infinita
  - Impedância de saída zero
  - Largura de banda infinita
  - Rejeição de modo comum infinita (CMRR)
  - Slew rate infinito
- Características reais e limitações
- Modelo equivalente do op-amp

#### 1.2 Configurações Básicas com Op-Amp
- Amplificador inversor:
  - Ganho: Av = -Rf/Rin
  - Impedância de entrada: Rin
  - Impedância de saída aproximadamente zero
  
- Amplificador não-inversor:
  - Ganho: Av = 1 + Rf/Rin
  - Impedância de entrada muito alta
  
- Seguidor de tensão (buffer):
  - Ganho unitário
  - Alta impedância de entrada
  - Baixa impedância de saída
  
- Amplificador somador:
  - Saída = -(Rf/R1·V1 + Rf/R2·V2 + ...)
  
- Amplificador diferencial básico

#### 1.3 Análise de Circuitos com Op-Amp
- Curto virtual (virtual short)
- Terra virtual (virtual ground)
- Análise nodal em circuitos com op-amps
- Circuitos de offset e compensação

---

### Unidade 2: Realimentação Negativa (12h)

#### 2.1 Conceitos de Realimentação
- Malha de realimentação
- Ganho de malha aberta (A)
- Ganho de realimentação (β)
- Ganho de malha fechada: Af = A/(1 + Aβ)
- Fator de desensibilidade: D = 1 + Aβ

#### 2.2 Topologias de Realimentação
- Realimentação de tensão em série (Voltage-Series)
- Realimentação de tensão em paralelo (Voltage-Shunt)
- Realimentação de corrente em série (Current-Series)
- Realimentação de corrente em paralelo (Current-Shunt)

#### 2.3 Efeitos da Realimentação Negativa
- Estabilização do ganho
- Redução de distorção não-linear
- Controle das impedâncias de entrada e saída
- Aumento da largura de banda (teorema do ganho-largura de banda constante)
- Redução do ruído (em algumas configurações)

#### 2.4 Estabilidade em Amplificadores Realimentados
- Critério de estabilidade de Nyquist
- Margem de ganho e margem de fase
- Critério de Barkhausen para oscilação
- Compensação de frequência:
  - Compensação por capacitor de Miller
  - Compensação polo-zero
  - Compensação por atraso de fase (lag) e avanço de fase (lead)

---

### Unidade 3: Aplicações Lineares dos Op-Amps (15h)

#### 3.1 Amplificadores de Instrumentação
- Amplificador diferencial de três op-amps
- Amplificador de instrumentação integrado (INA128, AD620)
- Rejeição de modo comum (CMRR)
- Aplicações: medidas de sinais biológicos, sensores de pressão, strain gauges

#### 3.2 Conversores de Impedância
- Conversor de impedância negativa (NIC)
- Simulador de indutor com gyrator
- Transformador de impedância com op-amps

#### 3.3 Circuitos de Condicionamento de Sinais
- Amplificadores de carga (para sensores piezoelétricos)
- Amplificadores de transresistância (para fotodiodos)
- Amplificadores logarítmicos e anti-logarítmicos
- Multiplicadores analógicos (multiplicador de Gilbert)
- Divisores analógicos

#### 3.4 Amplificadores Isolados
- Isolamento galvânico
- Amplificadores isolados com optoacopladores
- Amplificadores isolados com transformadores
- Aplicações em ambientes industriais e médicos

---

### Unidade 4: Filtros Ativos (15h)

#### 4.1 Fundamentos de Filtros
- Resposta em frequência de filtros
- Tipos de resposta:
  - Butterworth (maximally flat)
  - Chebyshev (equiripple na banda de passagem)
  - Bessel (linearidade de fase)
  - Elíptica (equiripple em ambas as bandas)
- Especificações: frequência de corte, atenuação, ripple, ordem do filtro

#### 4.2 Filtros de Primeira Ordem
- Filtro passa-baixa (LPF) ativo
- Filtro passa-alta (HPF) ativo
- Filtro passa-tudo (all-pass)
- Cálculo de componentes

#### 4.3 Filtros de Segunda Ordem
- Topologias: Sallen-Key, Multiple Feedback (MFB), State-Variable
- Filtro passa-baixa de 2ª ordem
- Filtro passa-alta de 2ª ordem
- Filtro passa-faixa (BPF)
- Filtro rejeita-faixa (BRF, notch)
- Fator de qualidade Q e frequência de ressonância

#### 4.4 Filtros de Ordem Superior
- Cascata de estágios de 1ª e 2ª ordem
- Seções biquadráticas (biquads)
- Filtros com múltiplos realimentação (FLF)
- Switched-capacitor filters (introdução)

#### 4.5 Filtros Especiais
- Filtros de fase linear (Bessel)
- Filtros de banda estreita (high-Q)
- Filtros de estado variável (state-variable)
- Filtros universais (simultâneos: LPF, HPF, BPF, notch)

---

### Unidade 5: Conversores A/D e D/A (12h)

#### 5.1 Introdução à Conversão
- Sistemas de aquisição de dados
- Taxa de amostragem e teorema de Nyquist
- Aliasing e filtro anti-aliasing
- Quantização e erro de quantização
- Resolução e número de bits
- SNR de quantização: 6.02n + 1.76 dB

#### 5.2 Conversores Digital-Analógico (DAC)
- DAC de resistores ponderados
- DAC R-2R (ladder)
- DAC com chaves de corrente
- DAC com modulação de largura de pulso (PWM)
- Especificações: monotonicidade, INL, DNL, settling time

#### 5.3 Conversores Analógico-Digital (ADC)
- ADC de rampa (single slope e dual slope)
- ADC de aproximações sucessivas (SAR)
- ADC flash (parallel)
- ADC pipeline
- ADC sigma-delta (Σ-Δ)
- Especificações: resolução, taxa de amostragem, SNR, SFDR

#### 5.4 Circuitos de Amostragem e Retenção (S/H)
- Chave analógica (analog switch)
- Capacitor de retenção
- Efeito de injeção de carga
- Aquisição e aperatura (aperture) jitter

---

### Unidade 6: Osciladores e Geradores de Funções (12h)

#### 6.1 Osciladores Senoidais com Op-Amp
- Critério de Barkhausen
- Oscilador de ponte de Wien
- Oscilador com deslocamento de fase (phase-shift)
- Oscilador de quadratura
- Oscilador Colpitts e Hartley com op-amp
- Controle de amplitude

#### 6.2 Osciladores de Relaxação
- Multivibrador astável
- Multivibrador monoestável
- Circuito integrador-comparador (oscilador de onda triangular)
- Gerador de onda quadrada
- Gerador de onda dente de serra

#### 6.3 Geradores de Funções
- Gerador de onda triangular e quadrada
- Gerador de onda senoidal, triangular e quadrada
- Modulação de largura de pulso (PWM)
- Sintetizadores de funções integrados (ICL8038, XR2206)

#### 6.4 PLLs (Introdução)
- Phase-Locked Loop básico com op-amps e comparador
- VCO com op-amp
- Aplicações em demodulação FM
- Sincronismo de clock

---

### Unidade 7: Reguladores Chaveados (SMPS) (12h)

#### 7.1 Introdução às Fontes Chaveadas
- Vantagens sobre reguladores lineares
- Eficiência energética
- Componentes magnéticos: indutores e transformadores
- Diodos de recuperação rápida e Schottky

#### 7.2 Topologias Básicas
- Conversor Buck (step-down):
  - Princípio de funcionamento
  - Modos de condução: contínuo (CCM) e descontínuo (DCM)
  - Cálculo do indutor e capacitor de saída
  - Ripple de tensão e corrente
  
- Conversor Boost (step-up):
  - Ganho de tensão: Vo/Vi = 1/(1-D)
  - Aplicações em PFC (Power Factor Correction)
  
- Conversor Buck-Boost (inversor):
  - Tensão de saída invertida
  - Conversor Cuk (variação do buck-boost)
  - Conversor SEPIC

#### 7.3 Controladores de SMPS
- Modulação por largura de pulso (PWM)
- Controladores de modo tensão
- Controladores de modo corrente
- Circuitos integrados controladores (UC3842, TL494, LM2575)
- Compensação do loop de realimentação

#### 7.4 Isolamento e Segurança
- Transformadores em SMPS
- Topologias isoladas: flyback, forward, push-pull, half-bridge, full-bridge
- Retroalimentação isolada com optoacoplador
- Normas de segurança e isolamento

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Processamento de Sinais Analógicos
- **Pré-amplificadores de áudio**: Microfones, instrumentos musicais
- **Equalizadores**: Filtros ativos para correção de resposta
- **Crossovers ativos**: Divisão de frequência em sistemas de som
- **Compressores e limitadores**: Controle de dinâmica

### 3.2 Instrumentação e Medição
- **Amplificadores de instrumentação**: ECG, EEG, sensores de pressão
- **Condicionadores de sinais de sensores**: Temperatura, strain, pressão
- **Conversores A/D**: Aquisição de dados em sistemas de telecom
- **Isoladores**: Proteção em ambientes industriais

### 3.3 Sistemas de Comunicação (Base)
- **Filtros de IF**: Seleção de canais em receptores
- **Detector de envelope**: Demodulação AM
- **Discriminador FM**: Conversão frequência-tensão
- **AGC (Automatic Gain Control)**: Controle automático de ganho

### 3.4 Fontes de Alimentação
- **SMPS para equipamentos de telecom**: Alta eficiência
- **Conversores DC-DC**: Alimentação de circuitos digitais
- **Reguladores LDO**: Alimentação de circuitos sensíveis
- **PFC**: Correção do fator de potência

### 3.5 Sistemas de Controle
- **Drivers**: Interface entre microcontroladores e atuadores
- **PWM**: Controle de velocidade de motores, iluminação LED
- **Realimentação**: Controle de processos analógicos

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Desenvolvimento de conceitos e derivações
- **Aulas de exercícios**: Resolução de problemas de projeto
- **Laboratórios práticos**: Montagem e teste de circuitos com op-amps
- **Simulações computacionais**: LTspice, Multisim, Proteus
- **Projetos**: Sistema eletrônico completo (filtro, conversor, etc.)

### 4.2 Recursos Didáticos
- Quadro e projetor multimídia
- Kits de eletrônica analógica com op-amps (741, TL081, LM358)
- Osciloscópios, multímetros, geradores de função
- Fontes de alimentação simétricas (+/- 15V)
- Software de simulação: LTspice, Multisim, Proteus
- Módulos didáticos de filtros e conversores

### 4.3 Avaliação

**Instrumentos:**
- Provas teóricas (2 avaliações) - 50%
- Laboratórios práticos - 25%
- Projeto de sistema eletrônico - 15%
- Listas de exercícios e participação - 10%

**Critérios:**
- Compreensão do funcionamento de amplificadores operacionais
- Capacidade de projetar circuitos com realimentação
- Habilidade em projetar filtros ativos
- Conhecimento de técnicas de conversão A/D e D/A
- Proficiência em análise de circuitos eletrônicos

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Introdução aos op-amps. Configurações básicas |
| 2 | Análise de circuitos com op-amps |
| 3 | Realimentação negativa: conceitos e topologias |
| 4 | Efeitos da realimentação. Estabilidade |
| 5 | **1ª Avaliação** |
| 6 | Amplificadores de instrumentação |
| 7 | Conversores de impedância e condicionadores |
| 8 | Filtros ativos de 1ª e 2ª ordem |
| 9 | Filtros de ordem superior |
| 10 | **2ª Avaliação** |
| 11 | Conversores D/A e A/D |
| 12 | Circuitos de amostragem e retenção |
| 13 | Osciladores senoidais e de relaxação |
| 14 | Geradores de funções. Introdução a SMPS |
| 15 | Topologias Buck, Boost. Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. SEDRA, A. S.; SMITH, K. C. **Microeletrônica**. 7. ed. Pearson, 2016.
2. BOYLESTAD, R. L.; NASHELSKY, L. **Dispositivos Eletrônicos e Teoria de Circuitos**. 11. ed. Pearson, 2013.
3. FRANCO, S. **Design with Operational Amplifiers and Analog Integrated Circuits**. 4. ed. McGraw-Hill, 2014.

### Bibliografia Complementar
4. HOROWITZ, P.; HILL, W. **The Art of Electronics**. 3. ed. Cambridge University Press, 2015.
5. JUNG, W. **Op Amp Applications Handbook**. Newnes, 2004.
6. RAZAVI, B. **Design of Analog CMOS Integrated Circuits**. 2. ed. McGraw-Hill, 2016.
7. MANCINI, R. (ed.) **Op Amps for Everyone**. 4. ed. Texas Instruments, 2013.
8. ERICKSON, R. W.; MAKSIMOVIC, D. **Fundamentals of Power Electronics**. 2. ed. Springer, 2001.

### Recursos Online
- [TI Analog Engineer's Pocket Reference](https://www.ti.com/lit/slyw038)
- [Analog Devices Op Amp Applications](https://www.analog.com/en/education/education-library/op-amp-applications-handbook.html)
- [LTspice](https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html)
- [Filter Design Tool](https://tools.analog.com/filterwizard/) - Ferramenta de projeto de filtros da Analog Devices

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Analisar e projetar circuitos básicos com amplificadores operacionais

**RA2** - Aplicar técnicas de realimentação negativa para melhorar características de amplificadores

**RA3** - Projetar amplificadores de instrumentação e circuitos de condicionamento de sinais

**RA4** - Analisar e projetar filtros ativos de diferentes tipos e ordens

**RA5** - Compreender os princípios de funcionamento de conversores A/D e D/A

**RA6** - Projetar osciladores senoidais e geradores de funções com op-amps

**RA7** - Analisar o funcionamento de reguladores de tensão chaveados (SMPS)

**RA8** - Projetar sistemas eletrônicos analógicos integrados para aplicações específicas

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: Os amplificadores operacionais são blocos fundamentais da eletrônica analógica moderna. Dedique tempo para entender as topologias básicas (inversor, não-inversor, somador), pois elas são a base para circuitos mais complexos.

> 🔧 **Laboratório**: Experimente diferentes op-amps (741, TL081, LM358, LM324) e observe as diferenças nas características reais (slew rate, largura de banda, offset). Isso desenvolverá intuição prática.

> 🎵 **Aplicações Interessantes**: Filtros ativos são usados em equalizadores de áudio, crossovers de caixas de som e processadores de sinais. Tente projetar um crossover para um sistema de áudio!

> 💻 **Simulação**: O LTspice é excelente para simular filtros. Use a análise AC para verificar a resposta em frequência antes de montar.

> 🔋 **SMPS**: As fontes chaveadas estão em todos os equipamentos modernos (carregadores de celular, fontes de computador). Entender seus princípios é essencial para qualquer engenheiro eletrônico.

> 🔗 **Conexões**: Esta disciplina é pré-requisito para:
> - Eletrônica Aplicada (circuitos de RF)
> - Processamento Digital de Sinais (interface analógico-digital)
> - Projetos de instrumentação e controle

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025