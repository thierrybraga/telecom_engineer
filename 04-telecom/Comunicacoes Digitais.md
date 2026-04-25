---
tags: [telecomunicações, comunicações digitais, modulação digital, codificação, engenharia]
semestre: 7
area: Telecom
creditos: 4
dificuldade: alta
importancia: critica
código: TEL006
carga_horaria: 60h (4 créditos)
status: completo
pré_requisitos: [Principios Comunicacoes, Processamento Digital Sinais]
links: [Comunicacoes Opticas, Redes Comunicacao Dados, Telefonia Celular]
aliases: [Comunicacoes_Digitais]
keywords: [telecomunicações, comunicações digitais, modulação digital, codificação, engenharia]
resumo: "Estudo das técnicas de transmissão digital: codificação de fonte e de canal, modulação digital avançada, equalização, sincronização, sistemas de espalhamento espectral e técnicas de acesso múltiplo."
---

# Processamento e Transmissão Digital de Informação

## 1. Ementa Oficial

Estudo das técnicas de transmissão digital: codificação de fonte e de canal, modulação digital avançada, equalização, sincronização, sistemas de espalhamento espectral e técnicas de acesso múltiplo. Análise de desempenho de sistemas de comunicação digital em canais ruidosos.

### Objetivos da Disciplina

**Objetivo Geral:**
Proporcionar ao estudante conhecimentos avançados sobre técnicas de processamento e transmissão digital de informação, capacitando-o a analisar, projetar e otimizar sistemas de comunicação digital.

**Objetivos Específicos:**
- Compreender técnicas de codificação de fonte e de canal
- Analisar modulações digitais avançadas e seu desempenho
- Entender técnicas de equalização de canais
- Conhecer métodos de sincronização em receptores digitais
- Aplicar técnicas de espalhamento espectral
- Conhecer técnicas de acesso múltiplo em sistemas digitais
- Analisar o desempenho de sistemas de comunicação digital

---

## 2. Conteúdo Programático

### Unidade 1: Codificação de Fonte (10h)

#### 1.1 Teoria da Informação
- Entropia e informação mútua
- Codificação de fonte discreta sem memória
- Codificação de Huffman
- Codificação aritmética
- Comprimento médio e eficiência
- Teorema da codificação de fonte de Shannon

#### 1.2 Codificação de Canal
- Capacidade do canal de Shannon
- Codificação para controle de erro
- Detecção vs correção de erros
- Distância de Hamming
- Capacidade de detecção e correção
- Codificação de canal vs codificação de linha

#### 1.3 Códigos de Bloco
- Códigos de bloco lineares
- Matriz geradora e matriz de paridade
- Síndrome e detecção de erros
- Códigos de Hamming
- Códigos cíclicos
- Códigos BCH
- Códigos Reed-Solomon

---

### Unidade 2: Códigos Convolucionais e Turbo Códigos (10h)

#### 2.1 Códigos Convolucionais
- Estrutura de codificadores convolucionais
- Representação: diagrama de estados, diagrama de treliça, árvore de código
- Decodificação por algoritmo de Viterbi
- Distância livre e desempenho
- Códigos sistemáticos recursivos (RSC)
- Puncturing e taxas de código variáveis

#### 2.2 Turbo Códigos
- Princípio dos turbo códigos
- Codificação paralela concatenada
- Decodificação iterativa (BCJR, MAP)
- Troca de informação extrínseca
- Desempenho próximo ao limite de Shannon
- Aplicações em 3G, 4G, satélites

#### 2.3 LDPC e Códigos Modernos
- Códigos LDPC (Low-Density Parity Check)
- Representação em grafos de Tanner
- Decodificação por propagação de crença (belief propagation)
- Códigos polares
- Códigos para 5G NR
- Comparativo de desempenho

---

### Unidade 3: Modulação Digital Avançada (10h)

#### 3.1 Modulações M-árias
- Modulações M-ASK, M-FSK, M-PSK
- Constelações e distância Euclidiana
- Probabilidade de erro símbolo vs erro bit
- Modulação M-QAM
- Mapeamento Gray
- Taxa de transmissão vs largura de banda

#### 3.2 Modulação Ortogonal
- OFDM (Orthogonal Frequency Division Multiplexing)
- Subportadoras ortogonais
- IFFT/FFT em OFDM
- Prefixo cíclico e equalização simples
- PAPR (Peak-to-Average Power Ratio)
- OFDMA e aplicações em 4G/5G

#### 3.3 Modulações de Espectro Contínuo
- CPM (Continuous Phase Modulation)
- MSK e GMSK
- Modulações com memória
- TCM (Trellis Coded Modulation)
- Modulação codificada
- Trade-off banda-eficiência energética

---

### Unidade 4: Equalização e Sincronização (10h)

#### 4.1 Caracterização de Canais
- Modelos de canais discretos
- Canal AWGN
- Canal com desvanecimento
- Canal com interferência intersimbólica (ISI)
- Diagrama de olho
- Resposta ao impulso do canal

#### 4.2 Técnicas de Equalização
- Equalizadores lineares:
  - ZF (Zero-Forcing)
  - MMSE (Minimum Mean Square Error)
- Algoritmos adaptativos:
  - LMS (Least Mean Squares)
  - RLS (Recursive Least Squares)
- Equalizadores de decisão por realimentação (DFE)
- Equalizadores de máxima verossimilhança (MLSE)

#### 4.3 Sincronização
- Sincronização de símbolo (timing recovery)
- Sincronização de portadora
- Loop de Costas
- Loop de early-late
- Recuperação de clock
- Efeitos de jitter

---

### Unidade 5: Espalhamento Espectral (10h)

#### 5.1 Fundamentos de Spread Spectrum
- Princípio do espalhamento espectral
- Processamento de ganho
- Jamming margin
- Vantagens do spread spectrum
- Aplicações: militares, CDMA, WLAN

#### 5.2 DSSS (Direct Sequence Spread Spectrum)
- Sequências pseudo-aleatórias (PN)
- Propriedades de sequências PN (m-sequences, Gold, Kasami)
- Correlacionadores
- Rake receiver
- Desempenho em multipath
- CDMA e capacidade

#### 5.3 FHSS (Frequency Hopping Spread Spectrum)
- Saltos em frequência
- Fast hopping vs slow hopping
- Sincronização em FHSS
- Combinação de FHSS e DSSS
- Aplicações: Bluetooth, military
- Comparativo DSSS vs FHSS

---

### Unidade 6: Acesso Múltiplo e Sistemas Modernos (10h)

#### 6.1 Técnicas de Acesso Múltiplo
- FDMA (Frequency Division Multiple Access)
- TDMA (Time Division Multiple Access)
- CDMA (Code Division Multiple Access)
- OFDMA (Orthogonal Frequency Division Multiple Access)
- SDMA (Space Division Multiple Access)
- NOMA (Non-Orthogonal Multiple Access)

#### 6.2 Sistemas Celulares
- Evolução: 1G a 5G
- Arquitetura de rede celular
- Handoff e roaming
- Planejamento de frequências
- Reuso de frequências
- Capacidade de sistemas celulares

#### 6.3 Tecnologias Emergentes
- Massive MIMO
- Beamforming digital
- Full-duplex
- mmWave communications
- Visible light communications (VLC)
- Tendências para 6G

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Sistemas Celulares
- **2G (GSM)**: TDMA, equalização, codificação convolucional
- **3G (UMTS)**: CDMA, WCDMA, turbo códigos
- **4G (LTE)**: OFDMA, SC-FDMA, MIMO
- **5G (NR)**: Massive MIMO, mmWave, LDPC, polar codes
- **6G (futuro)**: IA, terahertz, holographic communications

### 3.2 Redes sem Fio
- **Wi-Fi (802.11)**: DSSS, OFDM, MIMO, LDPC
- **Bluetooth**: FHSS, GFSK
- **ZigBee**: DSSS, O-QPSK
- **LoRa**: Chirp Spread Spectrum
- **NB-IoT**: OFDMA, repetitions, coverage enhancement

### 3.3 Comunicações por Satélite
- **DVB-S/S2/S2X**: LDPC, BCH, modulation adaptive
- **VSAT**: TDMA, SCPC
- **GPS/GNSS**: DSSS, BPSK, CDMA
- **Satélites de comunicação**: FDMA, TDMA, CDMA
- **LEO constellations**: Starlink, OneWeb, Kuiper

### 3.4 Redes Ópticas
- **Coherent optical**: QPSK, 16-QAM, 64-QAM
- **DSP para óptica**: Equalização, compensação de dispersão
- **FEC**: Reed-Solomon, LDPC para óptica
- **Flex-grid**: Elastic optical networking

### 3.5 Sistemas Militares e Espaciais
- **Comunicações seguras**: Espalhamento espectral
- **Anti-jamming**: DSSS, FHSS
- **LPI/LPD**: Low probability of intercept/detection
- **Deep space communications**: Concatenated codes, turbo codes

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Conceitos de codificação e modulação
- **Aulas de exercícios**: Cálculo de probabilidade de erro, projetos
- **Simulações**: MATLAB/Python para verificação de desempenho
- **Laboratórios**: Implementação de codificadores e decodificadores
- **Seminários**: Tecnologias de 5G e sistemas avançados
- **Projetos**: Análise de sistema de comunicação completo

### 4.2 Recursos Didáticos
- Quadro e projetor multimídia
- Software de simulação: MATLAB, Python (CommPy, scikit-dsp-comm)
- Ferramentas de codificação: MATLAB Communication Toolbox
- Simuladores de sistemas de comunicação
- Material didático digital
- Acesso a papers IEEE

### 4.3 Avaliação

**Instrumentos:**
- Provas teórico-práticas (2 avaliações) - 50%
- Projetos de simulação - 30%
- Seminários/Relatórios - 15%
- Participação - 5%

**Critérios:**
- Compreensão de codificação de fonte e canal
- Capacidade de analisar modulações digitais
- Conhecimento de técnicas de equalização
- Entendimento de sincronização
- Aplicação de espalhamento espectral
- Análise de sistemas de acesso múltiplo
- Proficiência em ferramentas de simulação

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Teoria da informação. Codificação de fonte |
| 2 | Codificação de canal. Códigos de bloco |
| 3 | Códigos de Hamming, BCH, Reed-Solomon |
| 4 | Códigos convolucionais. Decodificação de Viterbi |
| 5 | **1ª Avaliação** |
| 6 | Turbo códigos e decodificação iterativa |
| 7 | LDPC e códigos polares |
| 8 | Modulações M-árias e constelações |
| 9 | OFDM e modulações ortogonais |
| 10 | **2ª Avaliação** |
| 11 | Caracterização de canais. Equalização |
| 12 | Sincronização: timing e carrier recovery |
| 13 | Espalhamento espectral: DSSS e CDMA |
| 14 | FHSS e técnicas de acesso múltiplo |
| 15 | Sistemas modernos e 5G. Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. PROAKIS, J. G.; SALEHI, M. **Fundamentals of Communication Systems**. 2. ed. Pearson, 2014.
2. SKLAR, B. **Digital Communications: Fundamentals and Applications**. 2. ed. Prentice Hall, 2001.
3. RAPPAPORT, T. S. **Wireless Communications: Principles and Practice**. 2. ed. Prentice Hall, 2002.

### Bibliografia Complementar
4. LIN, S.; COSTELLO, D. J. **Error Control Coding**. 2. ed. Pearson, 2004.
5. RYAN, W. E.; LIN, S. **Channel Codes: Classical and Modern**. Cambridge University Press, 2009.
6. GOLDSMITH, A. **Wireless Communications**. Cambridge University Press, 2005.
7. BIGLIERI, E. **Coding for Wireless Channels**. Springer, 2005.
8. MENGALI, U.; D'ANDREA, A. N. **Synchronization Techniques for Digital Receivers**. Springer, 1997.

### Recursos Online
- [IEEE Communications Society](https://www.comsoc.org/) - Sociedade técnica
- [MATLAB Communications Toolbox](https://www.mathworks.com/products/communications.html) - Simulação
- [GNU Radio](https://www.gnuradio.org/) - Toolkit SDR open-source
- [3GPP Specifications](https://www.3gpp.org/specifications) - Especificações de celulares
- [Satellite Communications](https://www.satmagazine.com/) - Revista de satélites

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Aplicar técnicas de codificação de fonte e de canal para controle de erros

**RA2** - Analisar e projetar modulações digitais avançadas (M-árias, OFDM)

**RA3** - Projetar equalizadores para compensação de distorção de canal

**RA4** - Compreender e implementar técnicas de sincronização em receptores

**RA5** - Aplicar técnicas de espalhamento espectral em sistemas de comunicação

**RA6** - Analisar sistemas de acesso múltiplo e sua capacidade

**RA7** - Calcular probabilidade de erro e desempenho de sistemas digitais

**RA8** - Conhecer tecnologias emergentes em comunicações digitais (5G, massive MIMO)

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: Comunicações digitais é a disciplina que une teoria da informação, processamento de sinais e telecomunicações. É desafiadora mas extremamente recompensadora!

> 🎯 **Limite de Shannon**: Entenda bem a capacidade do canal. Ela define o limite fundamental de qualquer sistema de comunicação.

> 🔧 **Codificação**: Códigos modernos (turbo, LDPC, polar) operam a décimos de dB do limite de Shannon. A evolução dos códigos revolucionou as telecomunicações.

> 📡 **OFDM**: É a base do 4G, Wi-Fi, DVB. Domine bem o conceito de ortogonalidade e o papel do prefixo cíclico.

> 🔄 **Equalização**: Canais reais distorcem sinais. Equalizadores são essenciais para recuperar a informação.

> 🛰️ **Spread Spectrum**: Além de militares, é usado em GPS, Wi-Fi, Bluetooth. Entenda o processamento de ganho.

> 🔗 **Conexões**: Esta disciplina integra conhecimentos de:
> - Processamento Digital de Sinais (equalização, filtragem)
> - Principios de Comunicações (modulações básicas)
> - Microondas (implementação RF)
> - Redes (protocolos e arquiteturas)

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025