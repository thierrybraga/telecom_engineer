---
tags: [telecom, óptica, fibra óptica, comunicações, fotônica, redes ópticas]
semestre: 9
area: Telecom
creditos: 4
dificuldade: alta
importancia: critica
código: TEL012
carga_horaria: 60h (4 créditos)
status: completo
pré_requisitos: [Principios Comunicacoes, Eletromagnetismo]
links: [Comunicacoes Digitais, Redes Sem Fio, Telecom_Celular]
aliases: [Comunicacoes_Opticas]
keywords: [telecom, óptica, fibra óptica, comunicações, fotônica, redes ópticas]
resumo: "Estudo dos sistemas de comunicação por fibra óptica: princípios da óptica aplicada, características e tipos de fibras ópticas, componentes passivos e ativos, transmissores e receptores ópticos, sistemas de multiplexação "
---

# Comunicações Ópticas

## 1. Ementa Oficial

Estudo dos sistemas de comunicação por fibra óptica: princípios da óptica aplicada, características e tipos de fibras ópticas, componentes passivos e ativos, transmissores e receptores ópticos, sistemas de multiplexação (WDM), arquiteturas de redes ópticas e projetos de enlaces.

### Objetivos da Disciplina

**Objetivo Geral:**
Proporcionar ao estudante o conhecimento teórico e prático dos sistemas de comunicação por fibra óptica, desde os fundamentos físicos até o projeto de enlaces ópticos, preparando-o para atuar na área de telecomunicações ópticas.

**Objetivos Específicos:**
- Compreender os princípios físicos da propagação da luz em fibras ópticas
- Analisar as características de transmissão de fibras monomodo e multimodo
- Conhecer componentes passivos e ativos de sistemas ópticos
- Entender o funcionamento de transmissores (lasers, LEDs) e receptores (fotodetectores)
- Projetar enlaces de fibra óptica considerando atenuação e dispersão
- Compreender sistemas WDM (Wavelength Division Multiplexing)
- Analisar arquiteturas de redes ópticas (SDH, DWDM, FTTH, PON)

---

## 2. Conteúdo Programático

### Unidade 1: Fundamentos de Óptica e Física da Luz (8h)

#### 1.1 Natureza da Luz
- Teoria ondulatória da luz
- Dualidade onda-partícula
- Espectro eletromagnético: região óptica (UV, visível, IR)
- Velocidade da luz no vácuo e em meios materiais
- Índice de refração: n = c/v

#### 1.2 Óptica Geométrica
- Leis da reflexão e refração (Snell)
- Reflexão interna total (TIR)
- Ângulo crítico
- Fibra óptica como guia de onda dieletrico
- Propagação por reflexão interna total

#### 1.3 Óptica Ondulatória
- Interferência de ondas luminosas
- Difração
- Polarização da luz
- Coerência temporal e espacial
- Largura espectral e comprimento de coerência

---

### Unidade 2: Fibras Ópticas (12h)

#### 2.1 Estrutura e Fabricação
- Estrutura básica: núcleo, casca e revestimento protetor
- Materiais: sílica (SiO₂), fibras plásticas (POF)
- Processos de fabricação: MCVD, VAD, OVD
- Perfis de índice de refração: degrau e graduado

#### 2.2 Fibras Multimodo (MMF)
- Diâmetros típicos: 50/125 μm, 62.5/125 μm
- Modos de propagação
- Aberração cromática modal
- Largura de banda limitada por dispersão modal
- Fibras com índice graduado (GRIN)
- Aplicações: redes LAN, acesso curta distância

#### 2.3 Fibras Monomodo (SMF)
- Diâmetros típicos: 9/125 μm
- Condição de corte (cutoff)
- Vantagens: alta largura de banda, baixa dispersão
- Fibras padrão ITU-T G.652, G.653, G.655, G.656, G.657
- Aplicações: backbone, longa distância, alta velocidade

#### 2.4 Atenuação em Fibras Ópticas
- Atenuação intrínseca:
  - Absorção por ressonância UV
  - Absorção infravermelha
  - Espalhamento Rayleigh
- Atenuação extrínseca:
  - Absorção por impurezas (OH⁻)
  - Perdas por curvatura (macro e micro)
- Janelas de transmissão: 850 nm, 1310 nm, 1550 nm
- Fórmula de Beer-Lambert: P(z) = P₀·e^(-αz)

#### 2.5 Dispersão em Fibras Ópticas
- Dispersão modal (modais)
- Dispersão cromática (material e de guia)
- Fator de dispersão D (ps/nm/km)
- Largura de banda óptica
- Compensação de dispersão
- Fibras de dispersão deslocada (DSF, NZ-DSF)

#### 2.6 Fibras Especiais
- Fibras de manutenção de polarização (PMF)
- Fibras fotônicas (PCF)
- Fibras dopadas (para amplificadores)
- Fibras de cristal fotônico
- Fibras plásticas ópticas (POF)

---

### Unidade 3: Componentes Passivos Ópticos (8h)

#### 3.1 Conectores e Emendas
- Tipos de conectores: SC, FC, ST, LC, MU, MTP/MPO
- Perdas por inserção e retorno
- Técnicas de emenda: fusão e mecânica
- Medição de perdas: OTDR

#### 3.2 Acopladores e Divisores
- Acopladores direcionais (directional couplers)
- Divisores de potência (splitters): Y, X, estrela
- Divisores por comprimento de onda (WDM couplers)
- Acopladores de fibra fundida (FBT)
- Divisores PLC (Planar Lightwave Circuit)

#### 3.3 Multiplexadores e Demultiplexadores
- Filtros de comprimento de onda
- Array de Guia de Onda (AWG - Arrayed Waveguide Grating)
- Grade de Bragg em fibra (FBG)
- Interleaves
- Circuladores ópticos

#### 3.4 Isoladores e Atenuadores
- Isoladores ópticos (baseados em efeito Faraday)
- Atenuadores fixos e variáveis
- Switches ópticos mecânicos e MEMS

---

### Unidade 4: Componentes Ativos Ópticos (10h)

#### 4.1 Fontes Ópticas - LEDs
- Princípio de emissão espontânea
- Estrutura do LED: homojunção e heterojunção
- LEDs de superfície (SLED) e de borda (ELED)
- Espectro de emissão e largura espectral
- Eficiência e características elétrico-ópticas
- Aplicações em fibras multimodo

#### 4.2 Fontes Ópticas - Lasers
- Princípio de emissão estimulada
- Condição de inversão de população
- Estrutura do laser de semicondutor
- Laser Fabry-Perot (FP)
- Laser DFB (Distributed Feedback)
- Laser DBR (Distributed Bragg Reflector)
- Laser de múltiplos modos longitudinais vs monomodo
- Largura de linha espectral e chirp

#### 4.3 Moduladores Ópticos
- Modulação direta vs externa
- Moduladores eletro-absortivos (EA)
- Moduladores eletro-ópticos:
  - Efeito eletro-óptico (Pockels)
  - Moduladores Mach-Zehnder (MZM)
  - Moduladores de fase
- Moduladores em silício (silicon photonics)

#### 4.4 Fotodetectores
- Princípio de fotoabsorção
- Fotodiodo PIN:
  - Estrutura e funcionamento
  - Responsividade e eficiência quântica
  - Largura de banda
- Fotodiodo de avalanche (APD):
  - Ganho interno
  - Fator de excesso de ruído
- Comparativo PIN vs APD

#### 4.5 Amplificadores Ópticos
- Amplificadores de fibra dopada com Érbio (EDFA):
  - Princípio de funcionamento
  - Bandas C e L
  - Figura de ruído (NF)
  - Ganho e saturação
- Amplificadores de semicondutor (SOA)
- Amplificadores Raman
- Amplificadores híbridos

---

### Unidade 5: Sistemas de Transmissão Óptica (10h)

#### 5.1 Modulação em Sistemas Ópticos
- Modulação de intensidade (IM)
- Modulação de amplitude (ASK)
- Modulação de fase (PSK): BPSK, QPSK, m-PSK
- Modulação de quadratura (QAM)
- Detecção direta vs coerente
- Sistemas de detecção coerente avançados

#### 5.2 Formatos de Modulação Avançados
- NRZ (Non-Return-to-Zero)
- RZ (Return-to-Zero)
- CSRZ (Carrier-Suppressed RZ)
- Duobinário
- Modulação por deslocamento de fase (DPSK, DQPSK)
- CO-OFDM óptico

#### 5.3 Multiplexação por Divisão de Comprimento de Onda (WDM)
- Conceito de WDM
- CWDM (Coarse WDM): 20 nm de espaçamento
- DWDM (Dense WDM): 0.8 nm (100 GHz) ou menor
- UWDM (Ultra-Dense WDM)
- Problemas em WDM:
  - Crosstalk
  - Efeitos não-lineares
  - Uniformidade de ganho do EDFA

#### 5.4 Sistemas de Multiplexação Avançada
- OTDM (Optical Time Division Multiplexing)
- SDM (Space Division Multiplexing):
  - Fibras multi-núcleo (MCF)
  - Modos espaciais (FMF)
- Combinação de técnicas: DWDM + SDM

---

### Unidade 6: Arquiteturas de Redes Ópticas (8h)

#### 6.1 Hierarquia Digital Síncrona (SDH/SONET)
- Estrutura de frames STM-N/OC-N
- Multiplexação e mapeamento
- Proteção de caminho e de linha
- Anéis ópticos (MS-SPRING, SNCP)

#### 6.2 Redes Ópticas Metropolitanas
- Topologias: anel, estrela, malha
- Equipamentos: ADM, DXC, OADM
- Amplificadores inline e booster/preamp

#### 6.3 Redes de Acesso Óptico
- FTTx (Fiber to the x):
  - FTTN (Node)
  - FTTC (Curb)
  - FTTB (Building)
  - FTTH (Home)
- Arquiteturas PON (Passive Optical Network):
  - APON/BPON
  - EPON (IEEE 802.3ah)
  - GPON (ITU-T G.984)
  - XGS-PON, NG-PON2
- WDM-PON

#### 6.4 Redes Ópticas de Longa Distância
- Sistemas submarinos
- Amplificação de tração (pumped)
- Regeneração 3R (reamplificação, reshaping, retiming)
- Sistemas de próxima geração: flex-grid, supercanais

---

### Unidade 7: Projeto de Enlaces de Fibra Óptica (4h)

#### 7.1 Orçamento de Potência (Power Budget)
- Cálculo de perdas totais da fibra
- Margem de segurança
- Distância máxima limitada por atenuação
- Fórmula: P_TX - P_RX ≥ α_fibra·L + α_conectores + margem

#### 7.2 Orçamento de Dispersão (Rise Time Budget)
- Largura de banda do sistema
- Limitação por dispersão cromática
- Largura espectral da fonte
- Produto largura de banda × distância (BW×L)

#### 7.3 Efeitos Não-Lineares
- Autofaseamento (SPM - Self-Phase Modulation)
- Modulação de fase cruzada (XPM)
- Mistura de quatro ondas (FWM)
- Espalhamento estimulado de Brillouin (SBS)
- Espalhamento estimulado de Raman (SRS)
- Mitigação de efeitos não-lineares

#### 7.4 Ferramentas de Projeto
- Software de simulação: OptiSystem, VPIphotonics
- OTDR (Optical Time Domain Reflectometer)
- Medidores de potência óptica
- Analisadores de espectro óptico (OSA)

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Backbones de Telecomunicações
- **Redes de longa distância**: Interligação de cidades e países
- **Backbone nacional**: Infraestrutura da ANATEL, operadoras
- **Cables submarinos**: Conexões internacionais (ex: BRUSA, SAC)
- **Data center interconnect (DCI)**: Conexão entre data centers

### 3.2 Redes Metropolitanas
- **Anéis ópticos**: Topologia de alta disponibilidade
- **Redes de transporte**: Agregação de tráfego de acesso
- **Dark fiber**: Aluguel de fibras não utilizadas
- **Lit fiber**: Serviços ativos sobre fibra

### 3.3 Redes de Acesso (FTTH)
- **Fibra até a casa**: Provisionamento de banda larga
- **Triple play**: Voz, vídeo e dados sobre fibra
- **Competição de mercado**: Operadoras de telecom vs provedores
- **Programas governamentais**: Banda larga para todos

### 3.4 Data Centers e Cloud Computing
- **Redes ópticas intra-data center**: Conexão entre racks
- **Interconexão de data centers**: Distâncias metropolitanas
- **100G/400G/800G Ethernet**: Evolução das taxas
- **InfiniBand**: Redes de alta performance

### 3.5 Aplicações Industriais e Especiais
- **Óptica industrial**: Sensores em ambientes hostis
- **Fibra óptica para sensores**: Temperatura, pressão, vibração
- **Comunicações seguras**: Criptografia quântica (QKD)
- **Veículos**: Comunicações em aviões, navios, satélites

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Fundamentos físicos e matemáticos
- **Aulas práticas**: Demonstrações com equipamentos reais
- **Laboratórios**: Medidas com OTDR, power meters, fontes ópticas
- **Simulações**: Software OptiSystem, VPIphotonics, ou MATLAB
- **Projeto**: Dimensionamento de enlace óptico real

### 4.2 Recursos Didáticos
- Projetor multimídia e quadro
- Kits de fibra óptica para demonstração
- OTDR, power meters, light sources
- Analisador de espectro óptico (OSA)
- Software de simulação óptica
- Amostras de fibras e conectores

### 4.3 Avaliação

**Instrumentos:**
- Provas teóricas (2 avaliações) - 50%
- Laboratórios práticos - 25%
- Projeto de enlace óptico - 15%
- Seminário sobre tecnologia emergente - 10%

**Critérios:**
- Compreensão dos princípios físicos da propagação óptica
- Capacidade de calcular orçamentos de potência e dispersão
- Conhecimento de componentes e sistemas ópticos
- Habilidade em utilizar equipamentos de medição
- Capacidade de projetar enlaces ópticos

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Fundamentos de óptica. Natureza da luz |
| 2 | Fibras ópticas: estrutura, MMF e SMF |
| 3 | Atenuação e dispersão em fibras |
| 4 | **1ª Avaliação** |
| 5 | Componentes passivos ópticos |
| 6 | LEDs e Lasers semicondutores |
| 7 | Moduladores e fotodetectores |
| 8 | Amplificadores ópticos (EDFA) |
| 9 | **2ª Avaliação** |
| 10 | Modulação e detecção óptica |
| 11 | WDM, CWDM, DWDM |
| 12 | SDH/SONET e redes metropolitanas |
| 13 | FTTH, PON, EPON, GPON |
| 14 | Projeto de enlaces ópticos |
| 15 | Efeitos não-lineares. Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. SENIOR, J. M. **Optical Fiber Communications: Principles and Practice**. 3. ed. Prentice Hall, 2009.
2. KEISER, G. **Optical Fiber Communications**. 5. ed. McGraw-Hill, 2015.
3. AGRAWAL, G. P. **Fiber-Optic Communication Systems**. 4. ed. Wiley, 2010.

### Bibliografia Complementar
4. RAMASWAMI, R.; SIVARAJAN, K. N.; SASAKI, G. H. **Optical Networks: A Practical Perspective**. 4. ed. Morgan Kaufmann, 2021.
5. PÁSKA, S. **Optoelectronics and Photonics: Principles and Practices**. 2. ed. Prentice Hall, 2012.
6. KAZOVSKY, L.; BENEDETTO, S.; WILLNER, A. **Optical Fiber Communication Systems**. Artech House, 1996.
7. BECKER, P. C.; OLSSON, N. A.; SIMPSON, J. R. **Erbium-Doped Fiber Amplifiers: Fundamentals and Technology**. Academic Press, 1999.

### Recursos Online
- [IEEE/OSA Journal of Lightwave Technology](https://www.osapublishing.org/jlt/home.cfm)
- [Optical Society of America (OSA)](https://www.osa.org)
- [ITU-T Recommendations](https://www.itu.int/rec/T-REC-G/en) - Séries G.65x, G.98x
- [Fiber Optic Association (FOA)](https://www.thefoa.org) - Certificações e recursos

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Compreender os princípios físicos da propagação da luz em fibras ópticas e calcular parâmetros de transmissão

**RA2** - Analisar e comparar as características de fibras multimodo e monomodo para diferentes aplicações

**RA3** - Identificar e dimensionar componentes passivos e ativos de sistemas ópticos

**RA4** - Entender o funcionamento de transmissores (lasers, LEDs) e receptores (PIN, APD) ópticos

**RA5** - Projetar enlaces de fibra óptica considerando orçamentos de potência e dispersão

**RA6** - Compreender sistemas WDM e suas aplicações em redes ópticas modernas

**RA7** - Analisar arquiteturas de redes ópticas (SDH, FTTH, PON) e suas tecnologias

**RA8** - Operar equipamentos de medição óptica (OTDR, power meters, OSA) e interpretar resultados

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: A fibra óptica é a base da infraestrutura moderna de telecom. Entenda bem a física da propagação, pois isso explica todas as limitações e possibilidades dos sistemas ópticos.

> 🔧 **Laboratório**: O OTDR é o "radar" da fibra óptica. Aprenda a interpretar as traças (traces) para identificar falhas e medir perdas.

> 💻 **Simulação**: Use softwares como OptiSystem (se disponível) ou implemente simulações em Python/MATLAB para entender a propagação de pulsos ópticos.

> 🌐 **Mercado de Trabalho**: Engenheiros de telecom com conhecimento em fibra óptica são altamente demandados por operadoras, provedores de internet, data centers e integradores.

> 🔗 **Conexões**: Esta disciplina integra conhecimentos de:
> - Eletromagnetismo (propagação)
> - Eletrônica (componentes ativos)
> - Princípios de Comunicações (sistemas)
> - Redes (arquiteturas)

> 📈 **Tendências**: Acompanhe a evolução para 400G/800G, fibras multi-núcleo, e redes ópticas flexíveis (flex-grid).

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/2  
**Última atualização:** Abril/2025