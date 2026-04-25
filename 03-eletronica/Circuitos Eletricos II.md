---
tags: [elétrica, circuitos, transformada de Laplace, Fourier, análise de circuitos, engenharia]
semestre: 5
area: Elétrica
creditos: 6
dificuldade: alta
importancia: critica
código: ELE002
carga_horaria: 90h (6 créditos)
status: completo
pré_requisitos: [Circuitos Eletricos I, Equacoes Diferenciais A]
links: [Eletronica I, Principios Comunicacoes, Processamento Digital Sinais]
aliases: [Circuitos_Eletricos_II]
keywords: [elétrica, circuitos, transformada de Laplace, Fourier, análise de circuitos, engenharia]
resumo: "Estudo avançado de circuitos elétricos com ênfase em análise no domínio da frequência, transformada de Laplace, série de Fourier e suas aplicações em circuitos."
---

# Circuitos Elétricos II

## 1. Ementa Oficial

Estudo avançado de circuitos elétricos com ênfase em análise no domínio da frequência, transformada de Laplace, série de Fourier e suas aplicações em circuitos. Análise de circuitos trifásicos desequilibrados, circuitos acoplados magneticamente e transformadores.

### Objetivos da Disciplina

**Objetivo Geral:**
Proporcionar ao estudante ferramentas avançadas de análise de circuitos elétricos no domínio do tempo e da frequência, utilizando transformadas e séries, preparando-o para análise de sistemas de comunicação e processamento de sinais.

**Objetivos Específicos:**
- Aplicar a transformada de Laplace na análise de circuitos elétricos
- Utilizar a série e transformada de Fourier na análise de sinais e circuitos
- Analisar circuitos trifásicos desequilibrados
- Compreender o acoplamento magnético e transformadores
- Analisar circuitos de duas portas (quadripolos)
- Aplicar técnicas de análise em frequência em filtros e sistemas de comunicação

---

## 2. Conteúdo Programático

### Unidade 1: Transformada de Laplace (18h)

#### 1.1 Definição e Propriedades
- Definição: ℒ{f(t)} = F(s) = ∫₀^∞ f(t)e^(-st)dt
- Condições de existência
- Propriedades:
  - Linearidade
  - Deslocamento no tempo (time shift)
  - Deslocamento na frequência (frequency shift)
  - Mudança de escala
  - Derivada no tempo
  - Integral no tempo
  - Valor inicial e valor final

#### 1.2 Transformadas de Laplace de Funções Elementares
- Função degrau unitário (Heaviside)
- Função rampa
- Função exponencial
- Funções senoidais
- Funções hiperbólicas
- Função impulso unitário (Delta de Dirac)
- Funções periódicas

#### 1.3 Transformada Inversa de Laplace
- Método das frações parciais
- Casos: raízes reais distintas, raízes reais repetidas, raízes complexas conjugadas
- Teorema da convolução
- Uso de tabelas de transformadas

#### 1.4 Aplicação em Circuitos Elétricos
- Transformada de Laplace de elementos de circuito:
  - Resistor: R
  - Indutor: sL (com condições iniciais)
  - Capacitor: 1/(sC) (com condições iniciais)
- Análise de circuitos no domínio s
- Função de transferência H(s) = Y(s)/X(s)
- Resposta completa: natural + forçada
- Diagrama de polos e zeros

---

### Unidade 2: Séries de Fourier (12h)

#### 2.1 Fundamentos de Séries de Fourier
- Sinais periódicos e ortogonalidade
- Forma trigonométrica da série de Fourier
- Cálculo dos coeficientes a₀, aₙ, bₙ
- Forma compacta (amplitude e fase)
- Simetrias: par, ímpar, de meia onda

#### 2.2 Forma Exponencial da Série de Fourier
- Base exponencial complexa
- Coeficientes complexos cₙ
- Relação com coeficientes trigonométricos
- Espectro de frequências discretas

#### 2.3 Convergência e Propriedades
- Condições de Dirichlet
- Teorema de Parseval (potência média)
- Fenômeno de Gibbs
- Resposta de circuitos a sinais periódicos

#### 2.4 Aplicações em Circuitos
- Análise de sinais periódicos em circuitos lineares
- Resposta em frequência de circuitos
- Filtros e sua resposta a sinais periódicos
- Distorção harmônica

---

### Unidade 3: Transformada de Fourier (12h)

#### 3.1 Definição e Propriedades
- De série para transformada: período → ∞
- Definição: F(ω) = ∫_-∞^∞ f(t)e^(-jωt)dt
- Condições de existência
- Propriedades:
  - Linearidade
  - Deslocamento no tempo e frequência
  - Mudança de escala
  - Dualidade
  - Convolução
  - Derivada e integral
  - Teorema de Parseval (energia)

#### 3.2 Transformadas de Fourier de Funções Importantes
- Pulso retangular (sinc no domínio da frequência)
- Pulso triangular
- Exponencial unilateral
- Função degrau
- Impulso de Dirac
- Funções senoidais (delta de Dirac no domínio da frequência)
- Gaussiana

#### 3.3 Espectro de Frequências
- Densidade espectral de amplitude
- Densidade espectral de energia
- Largura de banda
- Relação entre duração no tempo e largura de banda

#### 3.4 Aplicações em Sistemas de Comunicação
- Resposta em frequência de circuitos
- Função de transferência H(jω)
- Diagramas de Bode (introdução)
- Filtros passivos e ativos

---

### Unidade 4: Circuitos Trifásicos Avançados (12h)

#### 4.1 Sistemas Trifásicos Desequilibrados
- Análise de sistemas desequilibrados
- Componentes simétricas (introdução)
- Método das tensões de nó
- Cálculo de correntes de linha e de fase

#### 4.2 Potência em Sistemas Trifásicos
- Potência instantânea trifásica
- Medição de potência trifásica:
  - Método de um wattímetro
  - Método de dois wattímetros
  - Método de três wattímetros
- Medição de energia reativa
- Fator de potência em sistemas trifásicos

#### 4.3 Ligações Especiais
- Transformadores em ligação estrela e triângulo
- Autotransformadores trifásicos
- Bancos de transformadores
- Ligação zig-zag

#### 4.4 Curto-Circuito em Sistemas Trifásicos
- Tipos de faltas: trifásica, bifásica, monofásica
- Correntes de curto-circuito
- Cálculo de correntes de falta
- Proteção de sistemas trifásicos

---

### Unidade 5: Acoplamento Magnético e Transformadores (15h)

#### 5.1 Indutância Mútua
- Conceito de acoplamento magnético
- Coeficiente de acoplamento (k)
- Indutância mútua M
- Convenção do ponto (dot convention)
- Polaridade relativa

#### 5.2 Análise de Circuitos Acoplados
- Circuitos com indutores acoplados
- Análise de malhas com acoplamento
- Redução de indutores acoplados
- Equivalentes T e Π (ou Y e Δ) para indutores acoplados

#### 5.3 Transformadores Ideais
- Princípio de funcionamento
- Relação de transformação: V₂/V₁ = N₂/N₁ = I₁/I₂
- Impedância refletida
- Autotransformadores
- Aplicações em telecomunicações

#### 5.4 Transformadores Reais
- Resistências dos enrolamentos
- Indutâncias de dispersão
- Perdas no núcleo (histerese e correntes de Foucault)
- Circuito equivalente do transformador
- Ensaios de curto-circuito e circuito aberto
- Eficiência e regulação

#### 5.5 Transformadores em RF
- Transformadores de RF e de banda larga
- Núcleos de ferrite
- Baluns (transformadores balanceado-desbalanceado)
- Aplicações em circuitos de comunicação

---

### Unidade 6: Circuitos de Duas Portas (Quadripolos) (12h)

#### 6.1 Parâmetros de Quadripolos
- Parâmetros impedância (z)
- Parâmetros admitância (y)
- Parâmetros híbridos (h)
- Parâmetros de transmissão (ABCD ou a)
- Conversão entre parâmetros

#### 6.2 Interconexão de Quadripolos
- Conexão em cascata
- Conexão em paralelo
- Conexão em série
- Conexão série-paralelo

#### 6.3 Quadripolos Importantes
- Transformador ideal como quadripolo
- Amplificadores operacionais
- Filtros passivos como quadripolos
- Linhas de transmissão

#### 6.4 Funções de Rede
- Função de transferência de tensão
- Função de transferência de corrente
- Impedância de entrada e saída
- Ganho e atenuação

---

### Unidade 7: Resposta em Frequência e Filtros (9h)

#### 7.1 Análise de Resposta em Frequência
- Resposta em frequência de circuitos RLC
- Diagramas de Bode (magnitude e fase)
- Frequência de corte (cutoff)
- Largura de banda (bandwidth)
- Fator de qualidade Q

#### 7.2 Filtros Passivos
- Filtros passa-baixa (LPF)
- Filtros passa-alta (HPF)
- Filtros passa-faixa (BPF)
- Filtros rejeita-faixa (BRF ou notch)
- Projeto de filtros RLC

#### 7.3 Filtros Ativos (Introdução)
- Filtros com amplificadores operacionais
- Vantagens sobre filtros passivos
- Topologias básicas
- Aplicações em processamento de sinais

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Sistemas de Comunicação
- **Modulação AM/FM**: Análise espectral usando Fourier
- **Multiplexação por divisão de frequência (FDM)**: Filtros passa-faixa
- **Equalizadores**: Correção de resposta em frequência
- **Analisadores de espectro**: Princípio baseado em Fourier

### 3.2 Processamento de Sinais
- **Filtragem digital**: Projeto de filtros analógicos como protótipos
- **Transformada discreta de Fourier (DFT)**: Base teórica em Fourier contínuo
- **Janelamento**: Efeitos no domínio do tempo e frequência
- **Convolução**: Implementação de filtros no domínio do tempo

### 3.3 Transmissão e Propagação
- **Linhas de transmissão**: Modelagem com quadripolos
- **Adaptação de impedância**: Transformadores de RF
- **Baluns**: Conversão entre circuitos balanceados e desbalanceados
- **Isoladores e circuladores**: Uso de elementos acoplados magneticamente

### 3.4 Fontes de Alimentação
- **Conversores CC-CC**: Transformadores em alta frequência
- **Retificadores trifásicos**: Análise com Fourier
- **Filtros de linha**: Eliminação de harmônicos
- **No-breaks (UPS)**: Sistemas trifásicos de backup

### 3.5 Antenas e RF
- **Transformadores de impedância**: Casamento de antenas
- **Divisores de potência**: Redes de quadripolos
- **Acopladores direcionais**: Princípios de acoplamento magnético
- **Filtros de RF**: Projeto passa-faixa para seletividade

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Desenvolvimento matemático das transformadas
- **Aulas práticas**: Resolução de problemas em sala
- **Laboratórios**: Verificação experimental de circuitos
- **Simulações computacionais**: MATLAB, Python (SciPy/NumPy), LTspice
- **Projetos**: Desenvolvimento de filtros e sistemas

### 4.2 Recursos Didáticos
- Quadro e projetor multimídia
- Kits de circuitos para montagem
- Osciloscópios, geradores de função, analisadores de espectro
- Software: MATLAB, Python (Jupyter), LTspice, Multisim
- Material didático digital e bibliografia especializada

### 4.3 Avaliação

**Instrumentos:**
- Provas teóricas (2 avaliações) - 50%
- Laboratórios práticos - 25%
- Projeto de filtros/circuitos - 15%
- Listas de exercícios e participação - 10%

**Critérios:**
- Domínio das transformadas de Laplace e Fourier
- Capacidade de análise no domínio da frequência
- Habilidade em projetar e analisar filtros
- Competência em simulação computacional
- Entendimento de circuitos acoplados e transformadores

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Transformada de Laplace: definição e propriedades |
| 2 | Transformadas de funções elementares. Inversa de Laplace |
| 3 | Aplicação de Laplace em circuitos elétricos |
| 4 | **1ª Avaliação** |
| 5 | Séries de Fourier: forma trigonométrica e exponencial |
| 6 | Aplicações da série de Fourier. Fenômeno de Gibbs |
| 7 | Transformada de Fourier: definição e propriedades |
| 8 | Espectro de frequências. Aplicações em comunicação |
| 9 | **2ª Avaliação** |
| 10 | Circuitos trifásicos avançados. Sistemas desequilibrados |
| 11 | Acoplamento magnético. Indutância mútua |
| 12 | Transformadores ideais e reais |
| 13 | Circuitos de duas portas (quadripolos) |
| 14 | Resposta em frequência e filtros |
| 15 | Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. ALEXANDER, C. K.; SADIKU, M. N. O. **Fundamentos de Circuitos Elétricos**. 5. ed. McGraw-Hill, 2013. (Capítulos de Laplace, Fourier)
2. HAYT, W. H.; KEMMERLY, J. E.; DURBIN, S. M. **Análise de Circuitos em Engenharia**. 7. ed. McGraw-Hill, 2008.
3. NILSSON, J. W.; RIEDEL, S. A. **Circuitos Elétricos**. 8. ed. Pearson, 2009.

### Bibliografia Complementar
4. OGATA, K. **Engenharia de Controle Moderno**. 5. ed. Pearson, 2011. (Capítulos sobre Laplace)
5. OPPENHEIM, A. V.; WILLSKY, A. S. **Sinais e Sistemas**. 2. ed. Pearson, 2010.
6. LATHI, B. P. **Sinais e Sistemas Lineares**. 2. ed. Bookman, 2008.
7. CLOSE, C. M.; FREDERICK, D. K.; NEWELL, J. C. **Modeling and Analysis of Dynamic Systems**. 3. ed. Wiley, 2002.

### Recursos Online
- [MIT OpenCourseWare - Signals and Systems](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-003-signals-and-systems-fall-2011/)
- [MATLAB Onramp](https://matlabacademy.mathworks.com/) - Tutorial gratuito de MATLAB
- [Python Signal Processing](https://docs.scipy.org/doc/scipy/reference/signal.html) - Processamento de sinais com SciPy
- [Falstad Circuit Simulator](http://www.falstad.com/circuit/) - Simulação interativa

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Aplicar a transformada de Laplace na análise de circuitos elétricos e resolução de equações diferenciais

**RA2** - Utilizar séries e transformadas de Fourier na análise de sinais periódicos e não-periódicos

**RA3** - Analisar circuitos trifásicos equilibrados e desequilibrados

**RA4** - Compreender e analisar circuitos acoplados magneticamente e transformadores

**RA5** - Caracterizar circuitos de duas portas (quadripolos) usando parâmetros z, y, h e ABCD

**RA6** - Analisar a resposta em frequência de circuitos e projetar filtros passivos

**RA7** - Utilizar software de computação (MATLAB/Python) para análise de circuitos e sinais

**RA8** - Aplicar técnicas de análise avançada em problemas de engenharia de telecomunicações

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: As transformadas de Laplace e Fourier são ferramentas matemáticas poderosas. Dedique tempo para entender as propriedades e pratique a transformação direta e inversa.

> 🎯 **Conexão com Telecom**: Esta disciplina é a ponte entre circuitos básicos e análise de sinais/sistemas. Os conceitos de espectro de frequência são fundamentais para compreender modulação, filtragem e processamento de sinais.

> 💻 **Ferramentas**: Aprenda a usar MATLAB ou Python para calcular transformadas e plotar respostas em frequência. Isso será essencial em disciplinas futuras.

> 🔗 **Disciplinas Futuras**: Os conceitos aqui são pré-requisitos para:
> - Processamento Digital de Sinais (PDS)
> - Análise de Sinais e Sistemas
> - Princípios de Comunicações
> - Sistemas de Comunicação

> 📡 **Aplicação Imediata**: Você será capaz de analisar qualquer circuito linear, projetar filtros simples e entender o comportamento de sistemas no domínio da frequência.

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025