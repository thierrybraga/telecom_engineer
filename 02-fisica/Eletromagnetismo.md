---
tags: [física, eletromagnetismo, ondas, maxwell, engenharia, telecom]
semestre: 5
area: Física
creditos: 4
dificuldade: alta
importancia: critica
código: FIS005
carga_horaria: 60h (4 créditos)
status: completo
pré_requisitos: [Fenomenos Eletromagneticos, Calculo III, Equacoes Diferenciais B]
links: [Propagacao, Antenas, Microondas, Comunicacoes Opticas]
aliases: []
keywords: [física, eletromagnetismo, ondas, maxwell, engenharia, telecom]
resumo: "Estudo dos fundamentos do eletromagnetismo clássico: equações de Maxwell, ondas eletromagnéticas, propagação em meios materiais, reflexão e refração, guias de onda e cavidades ressonantes."
---

# Eletromagnetismo

## 1. Ementa Oficial

Estudo dos fundamentos do eletromagnetismo clássico: equações de Maxwell, ondas eletromagnéticas, propagação em meios materiais, reflexão e refração, guias de onda e cavidades ressonantes. Aplicações em engenharia de telecomunicações.

### Objetivos da Disciplina

**Objetivo Geral:**
Proporcionar ao estudante o domínio dos fundamentos teóricos do eletromagnetismo clássico, com ênfase nas equações de Maxwell e suas aplicações em problemas de propagação de ondas, preparando a base para estudos de antenas, micro-ondas e sistemas de comunicação.

**Objetivos Específicos:**
- Compreender as equações de Maxwell na forma diferencial e integral
- Analisar a propagação de ondas eletromagnéticas em diferentes meios
- Entender os fenômenos de reflexão, refração e transmissão de ondas
- Estudar a radiação de antenas elementares
- Compreender o funcionamento de guias de onda e cavidades
- Aplicar os conceitos de eletromagnetismo em problemas de engenharia

---

## 2. Conteúdo Programático

### Unidade 1: Revisão de Eletrostática e Magnetostática (8h)

#### 1.1 Eletrostática
- Lei de Coulomb
- Campo elétrico e potencial elétrico
- Lei de Gauss elétrica
- Divergência do campo elétrico
- Rotacional do campo elétrico (regime estático)
- Condutores e dielétricos
- Deslocamento elétrico D
- Condensadores e energia eletrostática

#### 1.2 Magnetostática
- Lei de Biot-Savart
- Lei de Ampère
- Campo magnético B
- Potencial vetor magnético A
- Divergência do campo magnético
- Rotacional do campo magnético
- Materiais magnéticos: diamagnéticos, paramagnéticos, ferromagnéticos
- Intensidade de campo magnético H

#### 1.3 Campos dependentes do tempo (introdução)
- Corrente de condução e de deslocamento
- Densidade de corrente total
- Primeiras indicações de acoplamento elétrico-magnético

---

### Unidade 2: Equações de Maxwell (12h)

#### 2.1 Equações de Maxwell na Forma Integral
- Lei de Gauss elétrica: ∮D·dS = Q_enc
- Lei de Gauss magnética: ∮B·dS = 0
- Lei de Faraday: ∮E·dl = -dΦB/dt
- Lei de Ampère-Maxwell: ∮H·dl = I_cond + dΦD/dt

#### 2.2 Equações de Maxwell na Forma Diferencial
- ∇·D = ρ
- ∇·B = 0
- ∇×E = -∂B/∂t
- ∇×H = J + ∂D/∂t

#### 2.3 Significado Físico das Equações
- Divergência e densidade de carga
- Inexistência de monopolos magnéticos
- Indução eletromagnética
- Corrente de deslocamento de Maxwell

#### 2.4 Potenciais Eletromagnéticos
- Potencial escalar φ
- Potencial vetor A
- Gauge de Coulomb
- Gauge de Lorentz
- Equações de onda para os potenciais

#### 2.5 Conservação de Energia e Momento
- Teorema de Poynting: S = E×H
- Vetor de Poynting e densidade de potência
- Conservação da energia (equação da continuidade)
- Pressão de radiação
- Momento das ondas eletromagnéticas

---

### Unidade 3: Ondas Eletromagnéticas em Meios Livres (10h)

#### 3.1 Equação da Onda
- Derivação da equação de onda a partir de Maxwell
- Soluções gerais: ondas planas
- Velocidade de propagação: c = 1/√(με)
- Número de onda k, frequência angular ω
- Comprimento de onda λ = 2π/k

#### 3.2 Ondas Planas em Meios Sem Perdas
- Relação entre E e H
- Impedância intrínseca: η = √(μ/ε)
- Polarização linear, circular e elíptica
- Ondas TM, TE e TEM

#### 3.3 Ondas em Meios com Perdas
- Condutividade finita σ
- Constante de propagação complexa: γ = α + jβ
- Atenuação α (Np/m ou dB/m)
- Constante de fase β
- Comprimento de penetração (skin depth) δ
- Impedância intrínseca em meios condutores

#### 3.4 Dispersão
- Velocidade de fase vp = ω/β
- Velocidade de grupo vg = dω/dβ
- Dispersão normal e anômala
- Relação entre vp e vg

---

### Unidade 4: Reflexão e Refração de Ondas (10h)

#### 4.1 Leis de Snell
- Reflexão: θi = θr
- Refração: n1·sin(θi) = n2·sin(θt)
- Índice de refração n = √(εrμr)
- Reflexão interna total (θi > θc)

#### 4.2 Coeficientes de Reflexão e Transmissão
- Incidência normal
- Impedância de onda em meios diferentes
- Γ = (η2 - η1)/(η2 + η1)
- T = 2η2/(η2 + η1)
- Coeficientes de Fresnel

#### 4.3 Incidência Oblíqua
- Polarização paralela (p) e perpendicular (s)
- Ângulo de Brewster (polarização paralela)
- Reflexão total interna
- Onda evanescente

#### 4.4 Propagação em Meios Estratificados
- Múltiplas interfaces
- Revestimentos antirreflexo
- Filtros de interferência
- Guias de onda dielétricos planos

---

### Unidade 5: Radiação e Antenas Elementares (8h)

#### 5.1 Potenciais de Retardamento
- Potencial escalar retardado
- Potencial vetor retardado
- Aproximação de campo distante (far field)
- Aproximação de campo próximo (near field)

#### 5.2 Elementos de Radiação
- Dipolo elétrico de Hertz
- Distribuição de corrente no dipolo
- Campos radiados por um dipolo curto
- Resistência de radiação
- Padrão de radiação

#### 5.3 Dipolo Linear
- Distribuição senoidal de corrente
- Dipolo de meia onda (λ/2)
- Impedância de entrada
- Largura de feixe e diretividade
- Ganho de antena

#### 5.4 Arrays de Antenas
- Array de dois elementos
- Fator de array
- Arrays lineares uniformes
- Escalonamento em amplitude e fase
- Arrays broadside e end-fire

---

### Unidade 6: Guias de Onda (12h)

#### 6.1 Guias de Onda Retangulares
- Equações de Maxwell para guias
- Modos TE e TM
- Equação característica
- Frequência de corte fc
- Comprimento de onda de corte λc
- Comprimento de onda de guia λg
- Velocidade de fase e grupo em guias

#### 6.2 Modos em Guias Retangulares
- Modo TE10 (modo dominante)
- Campos do modo TE10
- Distribuição de corrente nas paredes
- Impedância de onda em guias
- Perdas em guias de onda

#### 6.3 Guias de Onda Circulares
- Modos TE e TM circulares
- Funções de Bessel
- Modos dominantes em guias circulares
- Aplicações práticas

#### 6.4 Linhas de Transmissão como Guias TEM
- Cabos coaxiais
- Linhas bifilares
- Linhas microstrip e stripline
- Velocidade de propagação
- Impedância característica
- Equações do telegrafista

#### 6.5 Excitação e Acoplamento
- Métodos de excitação de modos
- Acopladores direcionais
- Junções e descontinuidades
- Elementos discretos em guias

---

### Unidade 7: Cavidades Ressonantes (10h)

#### 7.1 Cavidades Retangulares
- Cavidade formada por curto em guia
- Frequências de ressonância
- Modos TE e TM em cavidades
- Fator de qualidade Q
- Perdas em cavidades

#### 7.2 Cavidades Circulares
- Modos em cavidades circulares
- Aplicações em filtros e osciladores

#### 7.3 Aplicações de Cavidades
- Cavidades em micro-ondas
- Osciladores de micro-ondas
- Filtros de micro-ondas
- Medição de propriedades de materiais

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Propagação de Ondas
- **Modelagem de canais**: Propagação em meios diversos
- **Efeitos de multipath**: Reflexões múltiplas em ambientes urbanos
- **Atenuação atmosférica**: Absorção por moléculas de água e oxigênio
- **Propagação ionosférica**: Reflexão em camadas da ionosfera (HF)

### 3.2 Antenas
- **Análise de antenas**: Dipolos, arrays, refletores
- **Padrões de radiação**: Modelagem e medição
- **Impedância de entrada**: Casamento de antenas
- **Arrays faseados**: Beamforming eletrônico
- **Microstrip antennas**: Antenas planares para dispositivos móveis

### 3.3 Micro-ondas
- **Guias de onda**: Transmissão em alta frequência
- **Componentes passivos**: Acopladores, circuladores, isoladores
- **Filtros de micro-ondas**: Cavidades e linhas acopladas
- **Amplificadores e osciladores**: Circuitos de RF
- **Sistemas de radar**: Princípios de detecção

### 3.4 Fibra Óptica
- **Propagação em fibras**: Modos guidos
- **Dispersão modal e cromática**: Limitações de banda
- **Atenuação**: Mecanismos de perda
- **Componentes ópticos**: Acopladores, filtros, multiplexadores

### 3.5 Compatibilidade Eletromagnética (EMC)
- **Interferência eletromagnética (EMI)**: Fontes e mecanismos
- **Blindagem**: Proteção contra campos eletromagnéticos
- **Aterramento**: Técnicas para redução de ruído
- **Normas EMC**: Regulamentações e testes

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Desenvolvimento matemático rigoroso das equações de Maxwell
- **Aulas práticas**: Resolução de problemas de aplicação
- **Demonstrações experimentais**: Guias de onda, antenas, polarização
- **Simulações computacionais**: MATLAB, COMSOL, HFSS, CST
- **Projetos**: Análise de antenas ou guias de onda

### 4.2 Recursos Didáticos
- Quadro e projetor multimídia
- Software de simulação eletromagnética
- Kit de micro-ondas com guias de onda
- Antenas e equipamentos de medição de campo
- Material didático digital (notas de aula, animações)

### 4.3 Avaliação

**Instrumentos:**
- Provas teóricas (2 avaliações) - 50%
- Listas de exercícios - 20%
- Projeto/seminário - 20%
- Participação - 10%

**Critérios:**
- Domínio das equações de Maxwell e suas aplicações
- Capacidade de resolver problemas de propagação de ondas
- Entendimento de fenômenos de reflexão e refração
- Conhecimento de guias de onda e cavidades
- Habilidade em utilizar software de simulação

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Revisão: Eletrostática e Magnetostática |
| 2 | Equações de Maxwell na forma integral |
| 3 | Equações de Maxwell na forma diferencial |
| 4 | **1ª Avaliação** |
| 5 | Potenciais e teorema de Poynting |
| 6 | Ondas eletromagnéticas em meios livres |
| 7 | Ondas em meios com perdas e dispersão |
| 8 | Reflexão e refração: incidência normal |
| 9 | **2ª Avaliação** |
| 10 | Reflexão e refração: incidência oblíqua |
| 11 | Radiação: dipolo de Hertz |
| 12 | Dipolo linear e arrays de antenas |
| 13 | Guias de onda retangulares |
| 14 | Guias circulares e cavidades ressonantes |
| 15 | Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. HAYT, W. H.; BUCK, J. A. **Eletromagnetismo**. 8. ed. McGraw-Hill, 2014.
2. SADIKU, M. N. O. **Elementos de Eletromagnetismo**. 4. ed. Bookman, 2012.
3. BALANIS, C. A. **Advanced Engineering Electromagnetics**. 2. ed. Wiley, 2012.

### Bibliografia Complementar
4. GRIFFITHS, D. J. **Introduction to Electrodynamics**. 4. ed. Cambridge University Press, 2017.
5. RAMO, S.; WHINNERY, J. R.; VAN DUZER, T. **Fields and Waves in Communication Electronics**. 3. ed. Wiley, 1994.
6. POZAR, D. M. **Microwave Engineering**. 4. ed. Wiley, 2011.
7. COLLIN, R. E. **Foundations for Microwave Engineering**. 2. ed. IEEE Press, 2001.
8. ORFANIDIS, S. J. **Electromagnetic Waves and Antennas**. Rutgers University, 2016.

### Recursos Online
- [MIT OpenCourseWare - Electromagnetics](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-013-electromagnetics-and-applications-fall-2005/)
- [COMSOL RF Module](https://www.comsol.com/rf-module) - Simulação eletromagnética
- [CST Studio Suite](https://www.3ds.com/products-services/simulia/products/cst-studio-suite/) - Simulação de RF
- [Antenna Theory](https://www.antenna-theory.com/) - Recursos sobre antenas

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Formular e aplicar as equações de Maxwell na análise de problemas eletromagnéticos

**RA2** - Analisar a propagação de ondas eletromagnéticas em diferentes meios materiais

**RA3** - Resolver problemas de reflexão e refração de ondas em interfaces

**RA4** - Calcular campos radiados por antenas elementares e compreender seus padrões de radiação

**RA5** - Analisar modos de propagação em guias de onda retangulares e circulares

**RA6** - Dimensionar cavidades ressonantes para aplicações em micro-ondas

**RA7** - Utilizar software de simulação eletromagnética para modelar problemas práticos

**RA8** - Aplicar os conceitos de eletromagnetismo no projeto de sistemas de telecomunicação

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: O eletromagnetismo é matematicamente desafiador. Domine o cálculo vetorial (gradiente, divergência, rotacional, laplaciano) antes de aprofundar nas equações de Maxwell.

> 🎯 **Conexão com Telecom**: Esta é uma disciplina-chave! Os conceitos aqui são usados em:
> - Propagação (modelagem de canais)
> - Antenas (projeto e análise)
> - Micro-ondas (guias e componentes)
> - Fibra óptica (propagação em dielétricos)

> 💻 **Simulação**: Softwares como COMSOL, HFSS ou CST são ferramentas poderosas para visualizar campos e ondas. Aproveite para fazer simulações complementares.

> 📐 **Matemática**: Não subestime o poder das equações de Maxwell. Elas descrevem toda a eletricidade, magnetismo e óptica clássica em apenas quatro equações!

> 🔗 **Pré-requisitos**: Esta disciplina exige domínio de:
> - Cálculo III (vetores, coordenadas curvilíneas)
> - Equações Diferenciais (EDPs, ondas)
> - Fenômenos Eletromagnéticos (base introdutória)

> 🚀 **Futuro**: Após esta disciplina, você estará pronto para:
> - Propagação e Antenas
> - Micro-ondas
> - Sistemas de Comunicação sem fio

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025