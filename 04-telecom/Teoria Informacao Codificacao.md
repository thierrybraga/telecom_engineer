---
tags: [teoria da informação, codificação, shannon, engenharia, telecomunicações]
semestre: 7
area: Telecom
creditos: 4
dificuldade: alta
importancia: alta
código: TEL014
carga_horaria: 60h (4 créditos)
status: completo
pré_requisitos: [Processos Estocasticos, Comunicacoes Digitais]
links: [Comunicacoes Digitais, Redes Computadores, Processamento Digital Sinais]
aliases: [Teoria_Informacao_Codificacao]
keywords: [teoria da informação, codificação, shannon, engenharia, telecomunicações]
resumo: "Estudo da teoria da informação de Shannon: medidas de informação, entropia, codificação de fonte, codificação de canal, capacidade de canal, códigos de bloco e códigos convolucionais."
---

# Teoria da Informação e Codificação

## 1. Ementa Oficial

Estudo da teoria da informação de Shannon: medidas de informação, entropia, codificação de fonte, codificação de canal, capacidade de canal, códigos de bloco e códigos convolucionais. Aplicações em sistemas de comunicação e compressão de dados.

### Objetivos da Disciplina

**Objetivo Geral:**
Proporcionar ao estudante conhecimentos fundamentais de teoria da informação e técnicas de codificação, capacitando-o a compreender os limites fundamentais da transmissão de informação e projetar sistemas de codificação eficientes.

**Objetivos Específicos:**
- Compreender as medidas de informação e entropia
- Aplicar codificação de fonte para compressão de dados
- Entender a capacidade de canal e o limite de Shannon
- Conhecer códigos de bloco para detecção e correção de erros
- Compreender códigos convolucionais e decodificação de Viterbi
- Analisar o desempenho de sistemas codificados
- Conhecer códigos modernos (turbo, LDPC)
- Aplicar técnicas de codificação em sistemas de comunicação

---

## 2. Conteúdo Programático

### Unidade 1: Medidas de Informação (10h)

#### 1.1 Conceitos Fundamentais
- Definição de informação (Shannon)
- Medida de informação auto-informação
- Unidades: bits, nats, hartleys
- Informação mútua
- Propriedades da informação mútua
- Entropia condicional

#### 1.2 Entropia
- Definição de entropia
- Propriedades da entropia
  - Não-negatividade
  - Entropia máxima
  - Condicionamento reduz entropia
- Entropia conjunta
- Entropia relativa (divergência de Kullback-Leibler)
- Taxa de entropia para processos estocásticos

---

### Unidade 2: Codificação de Fonte (10h)

#### 2.1 Codificação sem Perdas
- Teorema da codificação de fonte (primeiro teorema de Shannon)
- Comprimento médio de código
- Códigos de comprimento variável
- Códigos prefixo (códigos instantâneos)
- Desigualdade de Kraft
- Código de Huffman
  - Construção do código
  - Otimalidade
  - Extensão de fonte

#### 2.2 Codificação Aritmética
- Princípio da codificação aritmética
- Intervalos de codificação
- Precisão finita e aritmética inteira
- Codificação aritmética adaptativa
- Comparação com Huffman

#### 2.3 Dicionários e Compressão
- Algoritmo de Lempel-Ziv (LZ77, LZ78)
- LZW (Lempel-Ziv-Welch)
- Codificação de comprimento de corrida (RLE)
- Aplicações: ZIP, GIF, PNG, PDF

---

### Unidade 3: Capacidade de Canal (12h)

#### 3.1 Modelos de Canal
- Canal discreto sem memória (DMC)
- Canal binário simétrico (BSC)
- Canal binário com apagamento (BEC)
- Canal gaussiano
- Canal de banda limitada com ruído AWGN

#### 3.2 Capacidade de Canal
- Informação mútua canal
- Capacidade de canal discreto
- Capacidade de canal contínuo
- Fórmula de Shannon-Hartley
- Limite de Shannon
- Interpretação da capacidade

#### 3.3 Teorema da Codificação de Canal
- Segundo teorema de Shannon
- Codificação de canal vs codificação de linha
- Limite de Shannon para AWGN
- Energia por bit (Eb/N0)
- Limite de Shannon em Eb/N0
- Trade-off largura de banda vs potência

---

### Unidade 4: Códigos de Bloco (12h)

#### 4.1 Fundamentos de Códigos de Bloco
- Definição de código de bloco
- Distância de Hamming
- Peso de Hamming
- Capacidade de detecção de erros
- Capacidade de correção de erros
- Esferas de Hamming
- Limites de códigos
  - Limite de Hamming (esfera empacotada)
  - Limite de Gilbert-Varshamov
  - Limite de Singleton
  - Limite de Plotkin

#### 4.2 Códigos Lineares
- Definição de código linear
- Matriz geradora
- Matriz de paridade
- Síndrome
- Decodificação por síndrome
- Código dual
- Códigos sistemáticos

#### 4.3 Códigos Cíclicos
- Definição de código cíclico
- Polinômios geradores
- Codificação sistemática
- Decodificação de códigos cíclicos
- Registradores de deslocamento
- Códigos BCH (Bose-Chaudhuri-Hocquenghem)
- Códigos Reed-Solomon
- Decodificação algébrica (Berlekamp-Massey)

---

### Unidade 5: Códigos Convolucionais (10h)

#### 5.1 Estrutura de Códigos Convolucionais
- Codificadores convolucionais
- Representação em diagrama de estados
- Representação em diagrama de treliça
- Distância livre
- Códigos recursivos sistemáticos (RSC)
- Códigos de taxa 1/n e k/n
- Puncturing

#### 5.2 Decodificação
- Decodificação de sequência máxima verossimilhança (ML)
- Algoritmo de Viterbi
  - Métricas de ramo e caminho
  - Sobreviventes
  - Complexidade
- Decodificação sequencial
- Algoritmo de Stack
- Algoritmo de Fano

#### 5.3 Aplicações
- Codificação em sistemas de comunicação
- Concatenação de códigos
- Códigos convolucionais em standards (V.32, V.34, GSM, 3G)

---

### Unidade 6: Códigos Modernos (6h)

#### 6.1 Turbo Códigos
- Princípio dos turbo códigos
- Codificação paralela concatenada
- Decodificação iterativa
  - Algoritmo BCJR (MAP)
  - Troca de informação extrínseca
  - Convergência
- Desempenho próximo ao limite de Shannon
- Aplicações em 3G, 4G, satélites

#### 6.2 Códigos LDPC
- Códigos de verificação de paridade de baixa densidade
- Representação em grafos de Tanner
- Matriz de verificação de paridade
- Decodificação por propagação de crença (sum-product, belief propagation)
- Códigos LDPC irregulares
- Aplicações em Wi-Fi, 5G, DVB-S2

#### 6.3 Códigos Polares
- Construção de códigos polares
- Canal de capacidade síntese
- Decodificação por cancelamento sucessivo
- Lista de decodificação
- Aplicações em 5G NR

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Compressão de Dados
- **Áudio**: MP3, AAC, FLAC (codificação de fonte)
- **Vídeo**: H.264/AVC, H.265/HEVC, H.266/VVC
- **Imagens**: JPEG, PNG (codificação aritmética, Huffman)
- **Arquivos**: ZIP, GZIP, BZIP2 (Lempel-Ziv)
- **Transmissão**: Compactação de dados para economia de banda

### 3.2 Comunicações Digitais
- **Códigos de canal**: Proteção contra erros
- **Deep space**: Códigos convolucionais, Reed-Solomon
- **Satélites**: Turbo códigos, LDPC (DVB-S2)
- **Celulares**: Turbo códios (3G), LDPC (5G)
- **Wi-Fi**: LDPC (802.11n/ac/ax)
- **Discos rígidos**: Códigos Reed-Solomon

### 3.3 Limites de Comunicação
- **Capacidade de canal**: Quanto podemos transmitir?
- **Eb/N0 mínimo**: Limite fundamental
- **Eficiência espectral**: Bits/s/Hz
- **Projeto de sistemas**: Trade-offs otimizados

### 3.4 Sistemas de Armazenamento
- **Memórias**: Códigos de correção de erro (ECC)
- **CD/DVD/Blu-ray**: Reed-Solomon, LDPC
- **SSD**: BCH, LDPC
- **QR codes**: Reed-Solomon

### 3.5 Criptografia e Segurança
- **Entropia**: Medida de aleatoriedade
- **Geração de chaves**: Fontes de alta entropia
- **Compressão e criptografia**: Interação

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Conceitos matemáticos de teoria da informação
- **Aulas de exercícios**: Cálculos de entropia, códigos, capacidade
- **Simulações**: Implementação de codificadores/decodificadores
- **Projetos**: Análise de desempenho de códigos
- **Seminários**: Códigos modernos e aplicações

### 4.2 Recursos Didáticos
- Quadro e projetor multimídia
- Software de simulação: MATLAB, Python (NumPy, SciPy)
- Ferramentas de codificação
- Material didático digital
- Bibliotecas de códigos (MATLAB Communication Toolbox)

### 4.3 Avaliação

**Instrumentos:**
- Provas teóricas (2 avaliações) - 60%
- Projetos de implementação de códigos - 30%
- Listas de exercícios - 5%
- Participação - 5%

**Critérios:**
- Compreensão de medidas de informação e entropia
- Capacidade de projetar códigos de fonte
- Entendimento da capacidade de canal
- Conhecimento de códigos de bloco lineares
- Entendimento de códigos convolucionais
- Familiaridade com códigos modernos

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Medida de informação. Auto-informação |
| 2 | Entropia e suas propriedades |
| 3 | Informação mútua. Entropia condicional |
| 4 | Teorema de codificação de fonte. Códigos de Huffman |
| 5 | **1ª Avaliação** |
| 6 | Codificação aritmética. Lempel-Ziv |
| 7 | Canais discretos. Canal BSC e BEC |
| 8 | Capacidade de canal. Fórmula de Shannon-Hartley |
| 9 | Teorema da codificação de canal |
| 10 | **2ª Avaliação** |
| 11 | Códigos de bloco lineares. Matriz geradora e paridade |
| 12 | Códigos cíclicos. BCH e Reed-Solomon |
| 13 | Códigos convolucionais. Diagramas de estado e treliça |
| 14 | Algoritmo de Viterbi |
| 15 | Turbo códigos, LDPC, códigos polares. Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. COVER, T. M.; THOMAS, J. A. **Elements of Information Theory**. 2. ed. Wiley, 2006.
2. LIN, S.; COSTELLO, D. J. **Error Control Coding**. 2. ed. Pearson, 2004.
3. MACKAY, D. J. C. **Information Theory, Inference, and Learning Algorithms**. Cambridge University Press, 2003.

### Bibliografia Complementar
4. GALLAGER, R. G. **Information Theory and Reliable Communication**. Wiley, 1968.
5. BLATUT, R. E. **Principles and Practice of Information Theory**. Addison-Wesley, 1987.
6. RYAN, W. E.; LIN, S. **Channel Codes: Classical and Modern**. Cambridge University Press, 2009.
7. RICHARDSON, T.; URBANKE, R. **Modern Coding Theory**. Cambridge University Press, 2008.
8. ARIKAN, E. **Channel Polarization: A Method for Constructing Capacity-Achieving Codes**. IEEE, 2009.

### Recursos Online
- [Information Theory Society](https://www.itsoc.org/) - IEEE Information Theory Society
- [Elements of Information Theory - Online](http://www.inference.org.uk/itprnn/book.html) - Recursos do livro
- [David MacKay's Website](http://www.inference.org.uk/mackay/itila/) - Information Theory lectures
- [MATLAB Communication Toolbox](https://www.mathworks.com/products/communications.html) - Documentação

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Compreender e calcular medidas de informação, entropia e informação mútua

**RA2** - Aplicar técnicas de codificação de fonte para compressão de dados

**RA3** - Calcular a capacidade de canais discretos e contínuos

**RA4** - Entender o teorema da codificação de canal e o limite de Shannon

**RA5** - Projetar e analisar códigos de bloco lineares e cíclicos

**RA6** - Compreender códigos convolucionais e o algoritmo de Viterbi

**RA7** - Conhecer códigos modernos (turbo, LDPC, polares) e suas aplicações

**RA8** - Aplicar conceitos de teoria da informação em sistemas de comunicação

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: Teoria da Informação é matematicamente intensiva. Dedique tempo para entender as demonstrações e fazer muitos exercícios!

> 🎯 **Entropia**: É a medida fundamental de incerteza. Entenda bem suas propriedades - elas são a base de toda a teoria.

> 📊 **Limite de Shannon**: Define o que é possível. Todo sistema real opera abaixo deste limite. Entenda bem a interpretação física.

> 🔧 **Huffman**: É ótimo (para fontes sem memória). Mas Lempel-Ziv é universal e não precisa conhecer a distribuição da fonte.

> 🔢 **Códigos de Bloco**: Distância de Hamming determina tudo. d_min define capacidade de detecção e correção.

> 🌊 **Convolucionais**: A treliça é sua amiga. Visualize os caminhos e entenda por que Viterbi é tão eficiente.

> 🚀 **Códigos Modernos**: Turbo e LDPC operam a décimos de dB do limite de Shannon. São a prova de que podemos nos aproximar arbitrariamente do limite.

> 🔗 **Conexões**: Esta disciplina é fundamental para:
> - Comunicações Digitais (limite de desempenho)
> - Processos Estocásticos (modelagem estatística)
> - Compressão de dados (codificação de fonte)
> - Todas as áreas que envolvam transmissão confiável de informação

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025