---
tags: [processamento, sinais, DSP, filtros digitais, transformadas, engenharia]
semestre: 6
area: Telecom
creditos: 4
dificuldade: alta
importancia: critica
código: TEL005
carga_horaria: 60h (4 créditos)
status: completo
pré_requisitos: [Analise Sinais Sistemas, Metodos Matematicos]
links: [Comunicacoes Digitais, Processamento Audio Video, Principios Comunicacoes]
aliases: [Processamento_Digital_Sinais]
keywords: [processamento, sinais, DSP, filtros digitais, transformadas, engenharia]
resumo: "Estudo das técnicas de processamento digital de sinais: amostragem e quantização, transformada Z, transformada discreta de Fourier, projeto de filtros digitais FIR e IIR, estruturas de filtros, processamento multirrate e"
---

# Processamento Digital de Sinais

## 1. Ementa Oficial

Estudo das técnicas de processamento digital de sinais: amostragem e quantização, transformada Z, transformada discreta de Fourier, projeto de filtros digitais FIR e IIR, estruturas de filtros, processamento multirrate e aplicações em telecomunicações.

### Objetivos da Disciplina

**Objetivo Geral:**
Proporcionar ao estudante conhecimentos sobre processamento digital de sinais, capacitando-o a analisar, projetar e implementar sistemas digitais para processamento de sinais em aplicações de telecomunicações.

**Objetivos Específicos:**
- Compreender os fundamentos de amostragem e quantização de sinais
- Aplicar a transformada Z na análise de sistemas discretos
- Utilizar a DFT e FFT na análise espectral de sinais
- Projetar filtros digitais FIR e IIR
- Implementar estruturas de filtros digitais
- Aplicar técnicas de processamento multirrate
- Desenvolver aplicações de DSP em telecomunicações

---

## 2. Conteúdo Programático

### Unidade 1: Amostragem e Quantização de Sinais (10h)

#### 1.1 Revisão de Sinais e Sistemas Discretos
- Sequências e operações básicas
- Sistemas lineares invariantes no tempo (SLIT)
- Convolução discreta
- Estabilidade e causalidade
- Equações de diferenças
- Resposta em frequência de sistemas discretos

#### 1.2 Amostragem de Sinais Contínuos
- Teorema da amostragem de Nyquist-Shannon
- Reconstrução ideal de sinais
- Aliasing e prevenção
- Amostragem de sinais passa-banda
- Reamostragem e decimação
- Interpolação e upsampling

#### 1.3 Quantização
- Quantização uniforme
- Erro de quantização
- Relação sinal-ruído de quantização (SQNR)
- Quantização não-uniforme (lei μ e A)
- Dithering e noise shaping
- Codificação de pulsos (PCM, DPCM, DM)

---

### Unidade 2: Transformada Z (10h)

#### 2.1 Definição e Propriedades
- Definição da transformada Z
- Região de convergência (ROC)
- Transformada Z inversa
- Propriedades:
  - Linearidade
  - Deslocamento no tempo
  - Escalonamento no domínio Z
  - Convolução
  - Teorema do valor inicial e final
  - Diferenciação no domínio Z

#### 2.2 Análise de Sistemas LTI
- Função de transferência H(z)
- Pólos e zeros
- Estabilidade no domínio Z (critério de Jury)
- Resposta em frequência a partir de H(z)
- Sistemas de fase mínima, máxima e mista
- Sistemas de fase linear

#### 2.3 Solução de Equações de Diferenças
- Transformada Z unilateral
- Condições iniciais
- Resposta natural e forçada
- Resposta transitória e permanente
- Sistemas de primeira e segunda ordem

---

### Unidade 3: Transformada Discreta de Fourier (10h)

#### 3.1 Transformada de Fourier em Tempo Discreto (DTFT)
- Definição da DTFT
- Propriedades da DTFT
- Relação com a transformada Z
- Teorema de Parseval
- Convolução periódica
- Densidade espectral de energia e potência

#### 3.2 Transformada Discreta de Fourier (DFT)
- Definição da DFT
- Propriedades da DFT
- Convolução circular vs linear
- Zero-padding
- Resolução de frequência
- Efeito de vazamento (leakage)

#### 3.3 Transformada Rápida de Fourier (FFT)
- Algoritmo radix-2 de Cooley-Tukey
- Complexidade computacional: O(N log N)
- FFT de tempo decrescente vs freqüência decrescente
- FFT inversa (IFFT)
- Implementação prática da FFT
- Janelamento e análise espectral

---

### Unidade 4: Projeto de Filtros Digitais FIR (12h)

#### 4.1 Características de Filtros FIR
- Resposta ao impulso finita
- Filtros de fase linear
- Simetria da resposta ao impulso
- Tipos de filtros FIR (Tipo I, II, III, IV)
- Projeto por janelas
- Janelas: retangular, Hanning, Hamming, Blackman, Kaiser

#### 4.2 Métodos de Projeto FIR
- Método das janelas
- Método da amostragem em frequência
- Método de Parks-McClellan (equiripple)
- Critérios de projeto:
  - Frequência de corte
  - Ripple na banda passante
  - Atenuação na banda de rejeição
  - Largura da banda de transição

#### 4.3 Estruturas de Implementação FIR
- Forma direta
- Forma em cascata
- Forma linear de fase
- Estruturas polifásicas
- Implementação em hardware (DSPs, FPGAs)

---

### Unidade 5: Projeto de Filtros Digitais IIR (12h)

#### 5.1 Características de Filtros IIR
- Resposta ao impulso infinita
- Função de transferência racional
- Pólos e zeros
- Estabilidade
- Fase não-linear
- Ordem do filtro vs especificações

#### 5.2 Projeto de Filtros IIR por Transformação de Protótipos Analógicos
- Projeto de filtros analógicos:
  - Butterworth (máxima planicidade)
  - Chebyshev Tipo I (equiripple na banda passante)
  - Chebyshev Tipo II (equiripple na banda de rejeição)
  - Elíptico (equiripple em ambas as bandas)
  - Bessel (fase linear)

#### 5.3 Transformações de Frequência
- Transformação bilinear
- Prewarping de frequência
- Transformação de baixa passa para:
  - Alta passa
  - Passa-banda
  - Rejeita-banda
- Transformação LP-LP (frequência de corte variável)

#### 5.4 Estruturas de Implementação IIR
- Forma direta I e II
- Forma em cascata (série de seções de segunda ordem)
- Forma paralela
- Forma lattice
- Efeitos de quantização de coeficientes
- Efeitos de overflow e limit cycles

---

### Unidade 6: Processamento Multirrate e Aplicações (6h)

#### 6.1 Processamento Multirrate
- Decimação (downsampling)
- Interpolação (upsampling)
- Filtros antialiasing para decimação
- Filtros de interpolação
- Bancos de filtros
- Filtros em comb (comb filters)
- Filtros CIC (Cascaded Integrator-Comb)

#### 6.2 Aplicações em Telecomunicações
- Modulação e demodulação digital
- Equalização de canais
- Cancelamento de eco
- Sistemas OFDM
- Análise e síntese de subbandas
- Compensação de canal
- Sincronização de símbolos

#### 6.3 Implementação de DSP
- Arquiteturas de DSPs
- Pipeline e paralelismo
- Precisão finita e efeitos de quantização
- Overflow e saturação
- Benchmarks e otimização
- DSPs comerciais (Texas Instruments, Analog Devices)
- Implementação em FPGAs

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Modulação e Demodulação
- **Moduladores digitais**: Implementação de ASK, FSK, PSK, QAM
- **Demoduladores coerentes**: Recuperação de portadora
- **Formação de pulso**: Filtros de raiz quadrada de cosseno levantado
- **Matched filters**: Maximização de SNR
- **Sincronização**: Timing recovery, phase-locked loops digitais

### 3.2 Filtragem e Equalização
- **Filtros de recepção**: Seleção de canais, rejeição de interferência
- **Equalizadores**: Compensação de distorção de canal
  - Zero-forcing
  - MMSE (Minimum Mean Square Error)
  - LMS (Least Mean Squares)
  - RLS (Recursive Least Squares)
- **Filtros adaptativos**: Cancelamento de eco, beamforming

### 3.3 Análise Espectral
- **Analisadores de espectro**: Implementação digital
- **Detecção de sinais**: PSD estimation, energy detection
- **Classificação de modulação**: Feature extraction
- **Cognitive radio**: Spectrum sensing
- **Análise de vibrações**: Condition monitoring

### 3.4 Sistemas de Comunicação
- **OFDM**: Implementação via FFT/IFFT
- **CDMA**: Correlacionadores digitais, rake receivers
- **Sistemas MIMO**: Processamento espacial, beamforming digital
- **Sistemas de espalhamento espectral**: DSSS, FHSS
- **Pré-distorção digital**: Linearização de amplificadores

### 3.5 Processamento de Áudio e Voz
- **Codecs de áudio**: Filtros de sub-banda, MDCT
- **Cancelamento de ruído**: Filtros adaptativos, spectral subtraction
- **Reconhecimento de voz**: MFCC, feature extraction
- **Efeitos de áudio**: Reverb, equalização digital
- **Áudio 3D**: HRTF processing

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Desenvolvimento de conceitos matemáticos
- **Aulas de exercícios**: Projetos de filtros e análise de sistemas
- **Laboratórios**: Implementação em MATLAB/Python
- **Projetos**: Desenvolvimento de aplicações práticas
- **Simulações**: Verificação de projetos de filtros
- **Seminários**: Aplicações avançadas de DSP

### 4.2 Recursos Didáticos
- Quadro e projetor multimídia
- Laboratório de computação com MATLAB
- Python com bibliotecas SciPy, NumPy, Matplotlib
- Software de projeto de filtros: FDATool, Filter Designer
- Kits de DSP para implementação prática
- Material didático digital
- Ferramentas de simulação (GNU Radio)

### 4.3 Avaliação

**Instrumentos:**
- Provas teórico-práticas (2 avaliações) - 50%
- Projetos de filtros digitais - 30%
- Relatórios de laboratório - 15%
- Participação - 5%

**Critérios:**
- Domínio da teoria de amostragem e quantização
- Capacidade de aplicar transformada Z e DFT
- Habilidade em projetar filtros FIR e IIR
- Conhecimento de estruturas de implementação
- Proficiência em uso de ferramentas computacionais
- Qualidade de projetos e implementações

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Revisão de sinais discretos. Amostragem de sinais |
| 2 | Quantização. Reamostragem e interpolação |
| 3 | Transformada Z: definição e propriedades |
| 4 | Análise de sistemas LTI no domínio Z |
| 5 | **1ª Avaliação** |
| 6 | DTFT e suas propriedades |
| 7 | DFT e propriedades |
| 8 | FFT: algoritmo e implementação |
| 9 | Projeto de filtros FIR: características e métodos |
| 10 | **2ª Avaliação** |
| 11 | Projeto de filtros FIR: Parks-McClellan e estruturas |
| 12 | Projeto de filtros IIR: protótipos analógicos |
| 13 | Transformação bilinear e estruturas IIR |
| 14 | Processamento multirrate |
| 15 | Aplicações em telecom. Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. OPPENHEIM, A. V.; SCHAFER, R. W. **Processamento em Tempo Discreto de Sinais**. 3. ed. Pearson, 2012.
2. PROAKIS, J. G.; MANOLAKIS, D. G. **Digital Signal Processing: Principles, Algorithms and Applications**. 4. ed. Pearson, 2006.
3. DINIZ, P. S. R. **Processamento Digital de Sinais: Projeto e Análise de Sistemas**. 2. ed. Bookman, 2014.

### Bibliografia Complementar
4. MITRA, S. K. **Digital Signal Processing: A Computer-Based Approach**. 4. ed. McGraw-Hill, 2011.
5. LYONS, R. G. **Understanding Digital Signal Processing**. 3. ed. Prentice Hall, 2010.
6. IFeachor, E. C.; JERVIS, B. W. **Digital Signal Processing: A Practical Approach**. 2. ed. Prentice Hall, 2002.
7. Vaidyanathan, P. P. **Multirate Systems and Filter Banks**. Prentice Hall, 1993.
8. HAYKIN, S. **Adaptive Filter Theory**. 5. ed. Prentice Hall, 2013.

### Recursos Online
- [DSPRelated.com](https://www.dsprelated.com/) - Comunidade e recursos de DSP
- [MATLAB Signal Processing Toolbox](https://www.mathworks.com/products/signal.html) - Documentação
- [SciPy Signal Processing](https://docs.scipy.org/doc/scipy/reference/signal.html) - Biblioteca Python
- [DSP Guide](http://www.dspguide.com/) - The Scientist and Engineer's Guide to DSP
- [Coursera - DSP](https://www.coursera.org/learn/dsp) - Curso online

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Compreender os fundamentos de amostragem, quantização e reconstrução de sinais digitais

**RA2** - Aplicar a transformada Z na análise e projeto de sistemas discretos

**RA3** - Utilizar a DFT e FFT para análise espectral de sinais discretos

**RA4** - Projetar filtros digitais FIR atendendo especificações de frequência

**RA5** - Projetar filtros digitais IIR por transformação de protótipos analógicos

**RA6** - Implementar estruturas de filtros digitais considerando efeitos de quantização

**RA7** - Aplicar técnicas de processamento multirrate em sistemas de comunicação

**RA8** - Desenvolver aplicações de DSP em problemas de engenharia de telecomunicações

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: DSP é uma disciplina que une teoria matemática com implementação prática. Não deixe de fazer os exercícios computacionais!

> 🔄 **Transformadas**: Entenda bem a relação entre DTFT, DFT e FFT. A FFT é apenas um algoritmo eficiente para calcular a DFT.

> 🎚️ **Filtros FIR**: Fase linear é uma propriedade desejável em muitas aplicações. FIRs são mais fáceis de projetar para fase linear que IIRs.

> 📈 **Filtros IIR**: Mesma magnitude com ordem menor que FIR, mas com fase não-linear. Use quando a fase não for crítica.

> 🧮 **Quantização**: Em implementações reais, a precisão finita importa! Entenda os efeitos de overflow e quantização de coeficientes.

> 🚀 **FFT**: Revolucionou o processamento de sinais. O algoritmo de Cooley-Tukey reduziu a complexidade de O(N²) para O(N log N).

> 🔗 **Conexões**: Esta disciplina é fundamental para:
> - Comunicações Digitais (modulação, demodulação, equalização)
> - Processamento de Áudio e Vídeo (codecs, compressão)
> - Sistemas de Comunicação sem Fio (OFDM, MIMO)
> - Radiodifusão (processamento de sinais de RF)

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025