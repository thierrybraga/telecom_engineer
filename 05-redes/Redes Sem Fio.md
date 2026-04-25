---
tags: [redes sem fio, wireless, wifi, celular, engenharia, telecomunicações]
semestre: 9
area: Telecom
creditos: 4
dificuldade: alta
importancia: critica
código: TEL010
carga_horaria: 60h (4 créditos)
status: completo
pré_requisitos: [Redes Computadores, Propagacao]
links: [Redes Comunicacao Dados, Telefonia Celular, Comunicacoes Digitais]
aliases: [Redes_Sem_Fio]
keywords: [redes sem fio, wireless, wifi, celular, engenharia, telecomunicações]
resumo: "Estudo das tecnologias e protocolos de redes sem fio: fundamentos de comunicação sem fio, propagação de sinais, arquiteturas de redes locais (WLAN), redes celulares, redes de sensores, IoT e tendências em comunicações mó"
---

# Redes sem Fio

## 1. Ementa Oficial

Estudo das tecnologias e protocolos de redes sem fio: fundamentos de comunicação sem fio, propagação de sinais, arquiteturas de redes locais (WLAN), redes celulares, redes de sensores, IoT e tendências em comunicações móveis. Projeto e análise de redes sem fio.

### Objetivos da Disciplina

**Objetivo Geral:**
Proporcionar ao estudante conhecimentos sobre redes de comunicação sem fio, capacitando-o a compreender, analisar e projetar sistemas de comunicação móvel e redes locais sem fio.

**Objetivos Específicos:**
- Compreender os fundamentos de comunicação por rádio frequência
- Analisar características de propagação e modelos de canal sem fio
- Projetar e configurar redes locais sem fio (Wi-Fi)
- Entender a evolução e arquitetura das redes celulares
- Conhecer tecnologias de redes de sensores e IoT
- Aplicar conceitos de mobilidade e handover
- Analisar aspectos de segurança em redes sem fio
- Conhecer tendências em comunicações móveis (5G, 6G)

---

## 2. Conteúdo Programático

### Unidade 1: Fundamentos de Comunicação sem Fio (10h)

#### 1.1 Princípios de RF
- Espectro eletromagnético e alocação de frequências
- Banda estreita vs banda larga
- Banda base vs passa-faixa
- Multiplexação:
  - FDMA (Frequency Division Multiple Access)
  - TDMA (Time Division Multiple Access)
  - CDMA (Code Division Multiple Access)
  - OFDMA (Orthogonal Frequency Division Multiple Access)
- Duplexação: FDD e TDD

#### 1.2 Técnicas de Modulação sem Fio
- Modulações analógicas (revisão)
- Modulações digitais:
  - FSK, GFSK, MSK, GMSK
  - PSK (BPSK, QPSK, QAM)
  - OFDM e suas variações
- Espalhamento espectral (DSSS, FHSS)
- Codificação e correção de erros

---

### Unidade 2: Propagação e Modelos de Canal (10h)

#### 2.1 Características da Propagação sem Fio
- Grande escala vs pequena escala
- Perda de percurso (path loss)
  - Modelo de espaço livre
  - Modelo de dois raios
  - Modelos empíricos (Hata, COST-231)
- Sombreamento (shadowing)
  - Distribuição log-normal
- Modelos de canal indoor

#### 2.2 Desvanecimento Multicaminho
- Fenômeno de multicaminho
- Desvanecimento em pequena escala
  - Distribuição de Rayleigh
  - Distribuição de Rice
- Doppler e espalhamento Doppler
- Atraso de propagação e dispersão temporal
- Seletividade de frequência
- Coerência temporal e de frequência

#### 2.3 Técnicas de Mitigação
- Diversidade:
  - Espacial
  - Temporal
  - de Frequência
  - de Polarização
- Equalização
- Codificação e interleaving
- OFDM como técnica anti-multicaminho

---

### Unidade 3: Redes Locais sem Fio - WLAN (12h)

#### 3.1 Arquitetura Wi-Fi (IEEE 802.11)
- Evolução do padrão 802.11
  - 802.11b/g/a/n/ac/ax/be
- Arquitetura de rede:
  - Modo infraestrutura (BSS, ESS)
  - Modo ad-hoc (IBSS)
  - Mesh networking
- Componentes: APs, STAs, controladores

#### 3.2 Camada MAC do Wi-Fi
- CSMA/CA (Carrier Sense Multiple Access with Collision Avoidance)
- DCF (Distributed Coordination Function)
- PCF (Point Coordination Function)
- EDCA (Enhanced Distributed Channel Access) - 802.11e
- RTS/CTS
- Fragmentação
- Agregação de quadros (A-MSDU, A-MPDU)

#### 3.3 Camada Física do Wi-Fi
- DSSS em 802.11b
- OFDM em 802.11a/g/n/ac
- OFDMA em 802.11ax (Wi-Fi 6)
- MU-MIMO
- Beamforming
- Canais e frequências (2.4 GHz, 5 GHz, 6 GHz)

#### 3.4 Segurança em Wi-Fi
- WEP (fraco)
- WPA/WPA2 (TKIP, AES-CCMP)
- WPA3 (SAE, GCMP)
- Autenticação 802.1X e RADIUS
- WPS e suas vulnerabilidades
- Rogue APs e proteção

---

### Unidade 4: Redes Celulares (12h)

#### 4.1 Evolução das Redes Celulares
- 1G a 5G: visão geral
- Arquitetura de redes celulares:
  - Estrutura celular
  - Reuso de frequências
  - Handover
  - Roaming

#### 4.2 Tecnologias 2G e 3G
- GSM (2G):
  - Arquitetura
  - TDMA
  - Handover
- GPRS e EDGE (2.5G, 2.75G)
- UMTS (3G):
  - WCDMA
  - Arquitetura
  - HSPA, HSPA+

#### 4.3 Tecnologias 4G LTE
- Arquitetura LTE:
  - EPC (Evolved Packet Core)
  - eNodeB
  - Interfaces (S1, X2)
- OFDMA no downlink
- SC-FDMA no uplink
- MIMO em LTE
- Handover em LTE
- VoLTE (Voice over LTE)

#### 4.4 Tecnologias 5G NR
- Requisitos do 5G (eMBB, URLLC, mMTC)
- Arquitetura 5G:
  - NG-RAN (gNodeB)
  - 5G Core (Service-Based Architecture)
- Novas frequências: sub-6 GHz e mmWave
- Massive MIMO
- Beamforming avançado
- Network slicing
- MEC (Multi-access Edge Computing)

---

### Unidade 5: Redes de Sensores e IoT (10h)

#### 5.1 Internet das Coisas (IoT)
- Conceitos e arquitetura de IoT
- Aplicações de IoT
- Protocolos de IoT:
  - MQTT
  - CoAP
  - HTTP/REST
  - WebSockets

#### 5.2 Tecnologias de Rede para IoT
- Bluetooth e BLE (Bluetooth Low Energy)
- ZigBee (IEEE 802.15.4)
- Z-Wave
- Thread
- LoRa e LoRaWAN
- Sigfox
- NB-IoT e LTE-M
- Wi-Fi HaLow (802.11ah)

#### 5.3 Redes de Sensores sem Fio (WSN)
- Arquitetura de WSN
- Protocolos de roteamento
- Conservação de energia
- RFID e NFC
- Localização indoor

---

### Unidade 6: Aspectos Avançados e Tendências (6h)

#### 6.1 Mobilidade e Handover
- Conceitos de mobilidade
- Mobile IP
- Handover em diferentes tecnologias
- Latência no handover
- Make-before-break vs break-before-make

#### 6.2 Gestão de Espectro
- Espectro licenciado vs não-licenciado
- Cognitive radio
- Dynamic Spectrum Access (DSA)
- White spaces
- Spectrum sharing

#### 6.3 Tendências Futuras
- 5G-Advanced
- 6G: visões e expectativas
- Comunicações terahertz
- Redes de satélites LEO (Starlink, OneWeb)
- Comunicações ópticas sem fio (Li-Fi, FSO)
- Redes de drones e HAPS

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Infraestrutura Wi-Fi
- **Redes corporativas**: WLANs empresariais
- **Hotspots**: Redes de acesso público
- **Wi-Fi em transportes**: Ônibus, trens, aviões
- **Wi-Fi em eventos**: Cobertura temporária
- **Wi-Fi em residências**: Redes domésticas

### 3.2 Redes Celulares
- **Operadoras móveis**: Infraestrutura 4G/5G
- **Small cells**: Femtocells, picocells
- **Indoor coverage**: DAS, repeaters
- **Redes privadas**: LTE/5G privados para indústria
- **VoLTE/VoNR**: Voz sobre redes modernas

### 3.3 Internet das Coisas
- **Smart Cities**: Sensores urbanos
- **Indústria 4.0**: IoT industrial
- **Agricultura de precisão**: Sensores agrícolas
- **Wearables**: Dispositivos vestíveis
- **Smart Home**: Casa conectada

### 3.4 Redes de Comunicação Especializadas
- **Redes de emergência**: TETRA, P25
- **Redes militares**: Comunicações táticas
- **Redes aeroespaciais**: SATCOM
- **Redes marítimas**: Comunicações naval
- **Redes de sensores ambientais**: Monitoramento

### 3.5 Projetos de Cobertura
- **Planejamento de RF**: Link budget
- **Site survey**: Levantamento de campo
- **Modelagem de propagação**: Predição de cobertura
- **Otimização**: Ajuste de parâmetros
- **Drive tests**: Testes de campo

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Conceitos de comunicação sem fio
- **Aulas práticas**: Configuração de equipamentos Wi-Fi
- **Laboratórios**: Análise de sinais e propagação
- **Simulações**: Ferramentas de planejamento de RF
- **Projetos**: Design de cobertura Wi-Fi/celular
- **Seminários**: Tecnologias 5G e IoT

### 4.2 Recursos Didáticos
- Quadro e projetor multimídia
- Laboratório com equipamentos Wi-Fi (APs, analisadores)
- Analisadores de espectro
- Software de simulação de propagação
- Ferramentas de site survey
- Material didático digital

### 4.3 Avaliação

**Instrumentos:**
- Provas teórico-práticas (2 avaliações) - 50%
- Projeto de design de rede sem fio - 30%
- Laboratórios e simulações - 15%
- Participação - 5%

**Critérios:**
- Compreensão de fundamentos de comunicação sem fio
- Conhecimento de propagação e modelos de canal
- Capacidade de projetar redes Wi-Fi
- Entendimento de arquiteturas celulares 4G/5G
- Conhecimento de tecnologias IoT
- Habilidade em usar ferramentas de planejamento

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Fundamentos de RF. Multiplexação e duplexação |
| 2 | Técnicas de modulação sem fio |
| 3 | Propagação: path loss, modelos empíricos |
| 4 | Desvanecimento multicaminho. Diversidade |
| 5 | **1ª Avaliação** |
| 6 | Arquitetura Wi-Fi (IEEE 802.11) |
| 7 | Camada MAC: CSMA/CA, QoS |
| 8 | Camada PHY: OFDM, MIMO, canais |
| 9 | Segurança em Wi-Fi |
| 10 | **2ª Avaliação** |
| 11 | Redes celulares: 2G, 3G, 4G LTE |
| 12 | 5G NR: arquitetura e tecnologias |
| 13 | Redes de sensores e IoT |
| 14 | LoRa, NB-IoT, tecnologias LPWAN |
| 15 | Tendências: 6G, satélites. Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. RAPPAPORT, T. S. **Wireless Communications: Principles and Practice**. 2. ed. Prentice Hall, 2002.
2. GOLDSMITH, A. **Wireless Communications**. Cambridge University Press, 2005.
3. MURTY, R.; Bahl, P. **Understanding Wi-Fi 6 (802.11ax)**. Artech House, 2021.

### Bibliografia Complementar
4. DAHLMAN, E. et al. **4G: LTE/LTE-Advanced for Mobile Broadband**. 2. ed. Academic Press, 2014.
5. DAHLMAN, E. et al. **5G NR: The Next Generation Wireless Access Technology**. Academic Press, 2018.
6. GAST, M. S. **802.11 Wireless Networks: The Definitive Guide**. 2. ed. O'Reilly, 2005.
7. SCHILLER, J. **Mobile Communications**. 2. ed. Addison-Wesley, 2003.
8. STALLINGS, W. **Wireless Communications & Networks**. 2. ed. Pearson, 2004.

### Recursos Online
- [Wi-Fi Alliance](https://www.wi-fi.org/) - Padrões Wi-Fi
- [3GPP Specifications](https://www.3gpp.org/specifications) - Especificações 4G/5G
- [IEEE 802.11 Working Group](https://www.ieee802.org/11/) - Padrões Wi-Fi
- [LoRa Alliance](https://lora-alliance.org/) - Tecnologia LoRa
- [GSMA](https://www.gsma.com/) - Associação de operadoras móveis

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Compreender os fundamentos de comunicação por rádio frequência e técnicas de modulação

**RA2** - Analisar características de propagação e aplicar modelos de canal sem fio

**RA3** - Projetar e configurar redes locais sem fio (Wi-Fi) considerando aspectos técnicos e de segurança

**RA4** - Entender a evolução, arquitetura e funcionamento das redes celulares (2G a 5G)

**RA5** - Conhecer tecnologias de redes de sensores e protocolos de IoT

**RA6** - Analisar aspectos de mobilidade, handover e gestão de espectro

**RA7** - Implementar medidas de segurança em ambientes de redes sem fio

**RA8** - Acompanhar tendências em comunicações móveis e próximas gerações (5G-Advanced, 6G)

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: Redes sem fio é uma disciplina que une teoria de comunicações com aspectos práticos de implementação. Estude os fundamentos, mas não deixe de praticar com equipamentos reais!

> 📡 **Propagação**: O canal sem fio é hostil. Entenda bem os modelos de propagação e desvanecimento - eles afetam todo o projeto de rede.

> 📶 **Wi-Fi**: CSMA/CA é diferente do CSMA/CD das redes cabeadas. Entenda por que e como funciona a contenção no Wi-Fi.

> 📱 **Celulares**: A evolução 1G→5G é fascinante. Cada geração trouxe novas arquiteturas e tecnologias. 5G é uma revolução, não apenas evolução.

> 🌐 **IoT**: Billions de dispositivos conectados! Cada aplicação tem requisitos diferentes - latência, throughput, consumo de energia.

> 🛰️ **Futuro**: 6G, satélites LEO, terahertz... A comunicação sem fio continuará revolucionando nossa sociedade.

> 🔗 **Conexões**: Esta disciplina integra conhecimentos de:
> - Propagação (canal sem fio)
> - Comunicações Digitais (modulações)
> - Redes de Computadores (protocolos)
> - Antenas (radiação e recepção)

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025