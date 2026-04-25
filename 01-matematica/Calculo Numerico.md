---
tags: [matemática, métodos numéricos, computação científica, algoritmos]
semestre: 4
area: Matemática
creditos: 4
dificuldade: media
importancia: alta
status: completo
links: [Calculo Diferencial Integral II, Algoritmos II, Metodos Matematicos]
aliases: [Calculo_Numerico]
keywords: [matemática, métodos numéricos, computação científica, algoritmos]
---

# Cálculo Numérico

## 1. Ementa Expandida
Estudo de métodos numéricos para resolução de problemas matemáticos: solução de equações, sistemas lineares, interpolação, ajuste de curvas, integração numérica e solução de EDOs. Implementação computacional e análise de erros.

## 2. Blocos Teóricos

### 2.1 Erros e Aritmética de Ponto Flutuante
- Representação numérica em computadores
- Erros de arredondamento e truncamento
- Propagação de erros
- Estabilidade e condicionamento
- Normas IEEE 754
- Cancelamento catastrófico
- Escala de problemas

### 2.2 Solução de Equações Algébricas
- Método da bisseção
- Método da falsa posição
- Método de Newton-Raphson
- Método da secante
- Iteração de ponto fixo
- Convergência e critérios de parada
- Raízes de polinômios

### 2.3 Sistemas de Equações Lineares
- Eliminação gaussiana
- Pivotamento parcial e completo
- Decomposição LU
- Método de Cholesky
- Métodos iterativos: Jacobi, Gauss-Seidel
- Critérios de convergência
- Condicionamento de matrizes

### 2.4 Interpolação e Ajuste de Curvas
- Interpolação polinomial: Lagrange, Newton
- Diferenças divididas
- Interpolação por splines cúbicos
- Mínimos quadrados lineares
- Ajuste polinomial
- Linearização de modelos
- Regressão múltipla

### 2.5 Derivação e Integração Numérica
- Diferenças finitas: progressivas, regressivas, centradas
- Extrapolação de Richardson
- Regras de integração: trapézio, Simpson
- Quadratura gaussiana
- Integrais múltiplas
- Métodos de Monte Carlo

### 2.6 Solução de EDOs
- Método de Euler
- Métodos de Runge-Kutta
- Métodos preditor-corretor
- Sistemas de EDOs
- Problemas de valor de contorno
- Método das diferenças finitas

## 3. Aplicações em Telecom

### 3.1 Modelagem de Sistemas
- Simulação de circuitos não-lineares
- Análise de estabilidade de sistemas
- Modelagem de canais de comunicação
- Otimização de parâmetros de modulação

### 3.2 Processamento de Sinais
- Implementação de filtros digitais
- Transformada discreta de Fourier (DFT/FFT)
- Compressão de sinais
- Interpolação de amostras

### 3.3 Propagação e Antenas
- Solução numérica de equações de Maxwell
- Modelagem de propagação
- Análise de padrões de radiação
- Otimização de geometria de antenas

## 4. Prática/Implementação
- Lista 1: Erros e representação numérica
- Lista 2: Solução de equações não-lineares
- Lista 3: Sistemas lineares
- Lista 4: Interpolação e ajuste
- Lista 5: Integração numérica
- Lista 6: EDOs
- Projeto: Implementação de métodos em Python/C

## 5. Bibliografia

### Bibliografia Básica
- CHAPRA, S. C.; CANALE, R. P. **Métodos Numéricos para Engenharia**. 7. ed. AMGH, 2016.
- BURDEN, R. L.; FAIRES, J. D. **Análise Numérica**. 10. ed. Cengage, 2016.
- RUGGIERO, M. A. G.; LOPES, V. L. R. **Cálculo Numérico: Aspectos Teóricos e Computacionais**. 2. ed. Pearson, 2011.

### Bibliografia Complementar
- PRESS, W. H. et al. **Numerical Recipes: The Art of Scientific Computing**. 3. ed. Cambridge, 2007.
- ATKINSON, K. E. **An Introduction to Numerical Analysis**. 2. ed. Wiley, 1989.

## 6. Outputs Esperados
- Implementação de métodos numéricos
- Análise de erros e convergência
- Solução de sistemas lineares e não-lineares
- Interpolação e ajuste de dados
- Integração e derivação numérica
- Solução de EDOs computacionalmente
- Base para simulações em engenharia