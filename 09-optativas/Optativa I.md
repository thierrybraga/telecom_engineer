---
tags: [satélites, design, operação, telecomunicações, engenharia, optativa]
semestre: 10
area: Optativas
creditos: 4
dificuldade: media
importancia: media
código: OPT001
carga_horaria: 60h (4 créditos)
status: completo
pré_requisitos: [Eletromagnetismo, Propagacao, Telecomunicacoes]
links: [Radiodifusao Radioenlace, Comunicacoes Opticas, Antenas]
aliases: [Optativa_I]
keywords: [satélites, design, operação, telecomunicações, engenharia, optativa]
resumo: "Estudo dos fundamentos de design e operação de sistemas de satélites: órbitas e constelações, segmento espacial e terreno, engenharia de satélites, sistemas de comunicação por satélite, técnicas de acesso múltiplo, plane"
---

# Optativa I: Design e Operação de Satélites

## 1. Ementa Oficial

Estudo dos fundamentos de design e operação de sistemas de satélites: órbitas e constelações, segmento espacial e terreno, engenharia de satélites, sistemas de comunicação por satélite, técnicas de acesso múltiplo, planejamento de enlaces e aplicações em telecomunicações.

### Objetivos da Disciplina

**Objetivo Geral:**
Proporcionar ao estudante conhecimentos especializados sobre design e operação de sistemas de satélites, capacitando-o a compreender, analisar e projetar sistemas de comunicação por satélite e aplicações espaciais.

**Objetivos Específicos:**
- Compreender a mecânica orbital e tipos de órbitas de satélites
- Conhecer o segmento espacial e seus subsistemas
- Entender o segmento terreno e estações de controle
- Analisar sistemas de comunicação por satélite
- Conhecer técnicas de acesso múltiplo (FDMA, TDMA, CDMA)
- Projetar enlaces de satélite (link budget)
- Conhecer aplicações de satélites em telecomunicações
- Entender aspectos de operação e controle de satélites

---

## 2. Conteúdo Programático

### Unidade 1: Mecânica Orbital e Órbitas (10h)

#### 1.1 Fundamentos de Mecânica Orbital
- Leis de Kepler
- Lei da gravitação universal de Newton
- Elementos orbitais
  - Semi-eixo maior
  - Excentricidade
  - Inclinação
  - Ascensão reta do nodo ascendente
  - Argumento do perigeu
  - Anomalia média
- Período orbital
- Velocidade orbital

#### 1.2 Tipos de Órbitas
- Órbitas geoestacionárias (GEO)
  - Altitude: ~35.786 km
  - Período: 24 horas sidéreas
  - Cobertura global (exceto polos)
- Órbitas de média altitude (MEO)
  - Exemplo: GPS (~20.200 km)
  - Período: ~12 horas
- Órbitas baixas (LEO)
  - Altitude: 200-2.000 km
  - Período: 90-120 minutos
  - Constelações LEO (Starlink, OneWeb, Iridium)
- Órbitas elípticas (HEO)
  - Órbitas de Molniya
  - Órbitas Tundra

#### 1.3 Constelações de Satélites
- Conceito de constelações
- Constelações Walker
- Constelações híbridas
- Cobertura global
- Handover entre satélites

---

### Unidade 2: Segmento Espacial (12h)

#### 2.1 Subsistemas de Satélites
- **Estrutura mecânica**
  - Materiais estruturais
  - Design para lançamento
- **Sistema de potência**
  - Painéis solares
  - Baterias (íons de lítio, NiH2)
  - Controle de carga
- **Sistema de controle de atitude**
  - Sensores (solares, de Terra, giroscópios)
  - Atuadores (propulsores, rodas de reação, magnetorquers)
  - Estabilização por spin ou de três eixos
- **Sistema de controle térmico**
  - Fontes de calor no espaço
  - Técnicas de controle térmico
- **Sistema de propulsão**
  - Motores químicos
  - Propulsão elétrica (íons, plasma)
  - Estações de manutenção orbital

#### 2.2 Payload de Telecomunicações
- Transponders
  - Bent pipe (repetidor transparente)
  - Processamento a bordo (regenerativo)
- Amplificadores de potência
  - TWT (Traveling Wave Tube)
  - SSPA (Solid State Power Amplifier)
- Antenas de satélite
  - Antenas de cobertura global
  - Antenas de spot beams
  - Formação de feixes (beam forming)
- Frequências de operação
  - Banda L (1-2 GHz)
  - Banda S (2-4 GHz)
  - Banda C (4-8 GHz)
  - Banda Ku (12-18 GHz)
  - Banda Ka (26.5-40 GHz)
  - Banda Q/V (40-75 GHz)

---

### Unidade 3: Segmento Terreno (10h)

#### 3.1 Estações Terrenas
- Estações de controle (TT&C - Telemetry, Tracking and Command)
- Estações de usuário (gateways)
- Estações de recepção apenas (VSAT, DTH)
- Componentes de uma estação terrena
  - Antenas
  - Amplificadores de alta potência (HPA)
  - Low Noise Amplifiers (LNA/LNB)
  - Conversores de frequência
  - Modems

#### 3.2 VSAT (Very Small Aperture Terminal)
- Conceito de VSAT
- Arquiteturas de rede VSAT
  - Star topology
  - Mesh topology
- Aplicações VSAT
  - Internet rural
  - Redes corporativas
  - Telemedicina
  - Educação a distância

#### 3.3 TT&C - Telemetria, Rastreamento e Comando
- Funções de TT&C
- Sistemas de telemetria
- Rastreamento orbital
- Comandos ao satélite
- Anomalias e recuperação

---

### Unidade 4: Sistemas de Comunicação por Satélite (12h)

#### 4.1 Técnicas de Acesso Múltiplo
- **FDMA** (Frequency Division Multiple Access)
  - Canais de frequência fixa
  - Aplicações em VSAT
- **TDMA** (Time Division Multiple Access)
  - Slots de tempo
  - Sincronização
  - TDMA em satélites procesadores
- **CDMA** (Code Division Multiple Access)
  - Códigos de espalhamento
  - CDMA em satélites móveis
- **SCPC** (Single Channel Per Carrier)
  - Canais dedicados
  - Aplicações em broadcast

#### 4.2 Modulações e Codificação
- Modulações para satélite
  - BPSK, QPSK, 8PSK, 16QAM
  - APSK (Amplitude and Phase-Shift Keying)
- Codificação de canal
  - Reed-Solomon
  - Códigos convolucionais
  - Turbo códigos
  - LDPC
- DVB-S, DVB-S2, DVB-S2X
- Standards de modulação adaptativa (ACM)

#### 4.3 Interferência e Compartilhamento
- Coordenação orbital (ITU)
- Separação orbital
- Reuso de frequências
- Interferência co-canal e adjacente
- Mitigação de interferência

---

### Unidade 5: Planejamento de Enlaces de Satélite (10h)

#### 5.1 Link Budget
- Equação de Friis para satélites
- G/T (Figura de mérito)
- EIRP (Effective Isotropic Radiated Power)
- C/N0 (Carrier-to-Noise Density Ratio)
- Eb/N0 (Energy per Bit to Noise Density Ratio)
- Margens de enlace
  - Margem de chuva
  - Margem de envelhecimento
  - Margem de implementação

#### 5.2 Efeitos da Atmosfera
- Atenuação por gases atmosféricos
- Atenuação por chuva
  - Modelos de predição (Crane, ITU-R)
  - Disponibilidade do enlace
- Despolarização
- Turbulência atmosférica
- Scintilação

#### 5.3 Propagação em Satélites
- Perda de espaço livre
- Atenuação adicional
- Ruído de sistema
- Ruído terrestre
- Ruído solar

---

### Unidade 6: Aplicações e Tendências (6h)

#### 6.1 Aplicações de Satélites
- **Broadcasting**
  - TV por satélite (DTH - Direct to Home)
  - Rádio por satélite
- **Comunicações fixas**
  - Telefonia rural
  - Internet banda larga
- **Comunicações móveis**
  - Inmarsat
  - Thuraya
  - Iridium
  - Starlink
- **Navegação**
  - GPS (EUA)
  - GLONASS (Rússia)
  - Galileo (UE)
  - BeiDou (China)
- **Sensoriamento remoto**
  - Imagens de satélite
  - Observação da Terra
- **Meteorologia**
  - Previsão do tempo
  - Monitoramento climático

#### 6.2 Tendências e Novas Tecnologias
- Constelações LEO de grande escala
  - Starlink (SpaceX)
  - OneWeb
  - Kuiper (Amazon)
  - Telesat Lightspeed
- Satélites de pequeno porte (CubeSats, nanosats)
- Satélites reconfiguráveis em órbita
- Laser communication (optical inter-satellite links)
- 5G via satélite (NTN - Non-Terrestrial Networks)
- Internet das Coisas via satélite
- Mineração espacial

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Backhaul e Acesso
- **Backhaul celular**: Interligação de estações base remotas
- **Internet rural**: Acesso em áreas sem infraestrutura terrestre
- **Aplicações marítimas**: Comunicações em navios
- **Aplicações aeronáuticas**: Comunicações em aviões
- **Aplicações militares**: Comunicações seguras

### 3.2 Broadcasting
- **TV por satélite**: DTH para residências
- **Distribuição de conteúdo**: Cabo headends, estações terrestres
- **Rádio por satélite**: SiriusXM, WorldSpace
- **Multicasting**: Distribuição eficiente de conteúdo

### 3.3 Comunicações Corporativas
- **VSAT corporativo**: Redes privadas de empresas
- **Backup de fibra**: Enlaces de contingência
- **Eventos temporários**: Cobertura de desastres
- **Exploração de petróleo**: Plataformas offshore

### 3.4 Navegação e Posicionamento
- **GNSS**: Sistemas globais de navegação
- **Aplicações de precisão**: Agricultura de precisão, construção
- **Timing**: Sincronização de redes (TD-SCDMA, CDMA)
- **Localização**: Serviços baseados em localização

### 3.5 Internet das Coisas (IoT)
- **IoT via satélite**: Conectividade global para sensores
- **Monitoramento ambiental**: Floresta, oceanos, clima
- **Rastreamento de ativos**: Logística global
- **Smart grids**: Monitoramento de redes elétricas

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Conceitos de mecânica orbital e engenharia de satélites
- **Aulas práticas**: Cálculos de link budget e planejamento de órbitas
- **Simulações**: Software de planejamento de satélites (STK, GMAT)
- **Projetos**: Design de sistema de comunicação por satélite
- **Seminários**: Tecnologias emergentes (LEO constellations, optical links)
- **Estudos de caso**: Missões espaciais reais

### 4.2 Recursos Didáticos
- Quadro e projetor multimídia
- Software de simulação orbital (STK, GMAT, Orekit)
- Calculadoras de link budget
- Material didático digital
- Vídeos de lançamentos e operações de satélites
- Acesso a dados de satélites reais

### 4.3 Avaliação

**Instrumentos:**
- Provas teórico-práticas (2 avaliações) - 50%
- Projeto de design de sistema de satélite - 35%
- Seminários/Relatórios - 10%
- Participação - 5%

**Critérios:**
- Compreensão de mecânica orbital e tipos de órbitas
- Conhecimento dos subsistemas de satélites
- Capacidade de calcular link budget
- Entendimento de técnicas de acesso múltiplo
- Conhecimento de aplicações de satélites
- Qualidade do projeto desenvolvido

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Fundamentos de mecânica orbital. Leis de Kepler |
| 2 | Elementos orbitais. Tipos de órbitas (GEO, MEO, LEO) |
| 3 | Constelações de satélites. Cobertura global |
| 4 | Subsistemas de satélites: estrutura, potência, atitude |
| 5 | **1ª Avaliação** |
| 6 | Subsistemas: controle térmico, propulsão, payload |
| 7 | Segmento terreno. Estações de controle e usuário |
| 8 | VSAT. Arquiteturas e aplicações |
| 9 | Técnicas de acesso múltiplo: FDMA, TDMA, CDMA |
| 10 | **2ª Avaliação** |
| 11 | Modulações e codificação para satélite. DVB-S2 |
| 12 | Planejamento de enlaces. Link budget |
| 13 | Efeitos atmosféricos. Atenuação por chuva |
| 14 | Aplicações de satélites. Broadcasting, navegação, IoT |
| 15 | Tendências: LEO constellations, 5G NTN. Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. RODDY, D. **Satellite Communications**. 4. ed. McGraw-Hill, 2006.
2. PRATT, T.; BOSTIAN, J.; ALLNUTT, J. **Satellite Communications**. 2. ed. Wiley, 2003.
3. MARAL, G.; BOUSQUET, M. **Satellite Communications Systems: Systems, Techniques and Technology**. 5. ed. Wiley, 2009.

### Bibliografia Complementar
4. LARSON, W. J.; WERTZ, J. R. **Space Mission Analysis and Design**. 3. ed. Microcosm Press, 1999.
5. FORTESCUE, P.; STARK, J.; SWINERD, G. **Spacecraft Systems Engineering**. 4. ed. Wiley, 2011.
6. GRIFFIN, M. D.; FRENCH, J. R. **Space Vehicle Design**. 2. ed. AIAA, 2004.
7. PATTERSON, D. **Satellite Communications: The Invisible Infrastructure**. AIAA, 2020.
8. FLEETWOOD, S. **Satellite Communications for the Nonspecialist**. SPIE Press, 2020.

### Recursos Online
- [NASA - JPL](https://www.jpl.nasa.gov/) - Laboratório de Propulsão a Jato
- [ESA](https://www.esa.int/) - Agência Espacial Europeia
- [INPE](https://www.gov.br/inpe/pt-br) - Instituto Nacional de Pesquisas Espaciais (Brasil)
- [ITU Satellite](https://www.itu.int/en/ITU-R/space/Pages/default.aspx) - Regulamentação de satélites
- [CelesTrak](https://celestrak.org/) - Dados orbitais de satélites
- [Satellite Today](https://www.satellitetoday.com/) - Notícias do setor

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Compreender os fundamentos de mecânica orbital e características de diferentes tipos de órbitas

**RA2** - Conhecer os subsistemas que compõem um satélite de telecomunicações

**RA3** - Entender o segmento terreno e arquiteturas de comunicação por satélite

**RA4** - Analisar e aplicar técnicas de acesso múltiplo em sistemas de satélite

**RA5** - Calcular link budget e projetar enlaces de comunicação por satélite

**RA6** - Considerar efeitos atmosféricos e margens de enlace em planejamentos

**RA7** - Conhecer aplicações de satélites em telecomunicações e navegação

**RA8** - Acompanhar tendências tecnológicas como constelações LEO e 5G via satélite

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: Design de satélites é multidisciplinar. Além de telecom, envolve mecânica, controle, termodinâmica e engenharia de materiais!

> 🌍 **Órbitas**: GEO é ótima para broadcast (cobertura fixa). LEO é melhor para latência baixa. Escolha depende da aplicação.

> 📡 **Transponders**: Entenda bem a diferença entre "bent pipe" (transparente) e processamento regenerativo. O segundo é mais complexo mas melhora SNR.

> 📊 **Link Budget**: Calcule com atenção! Um erro de 3 dB pode significar duplicar ou reduzir pela metade a potência necessária.

> 🌧️ **Chuva**: É o maior inimigo de enlaces em Ku e Ka band. O modelo de Crane ou ITU-R é essencial para planejar disponibilidade.

> 🚀 **LEO Constellations**: Starlink e similares estão revolucionando o acesso à Internet. Entenda os desafios de handover e gestão de constelações.

> 🛰️ **TT&C**: Não esqueça! Um satélite sem controle é apenas lixo espacial. A operação é tão importante quanto o design.

> 🔗 **Conexões**: Esta disciplina integra conhecimentos de:
> - Propagação (efeitos atmosféricos)
> - Comunicações Digitais (modulação, codificação)
> - Antenas (ganho, padrões de radiação)
> - Sistemas de Controle (atitude, órbita)

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025