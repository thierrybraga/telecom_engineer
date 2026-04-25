---
tags: [telefonia celular, redes móveis, 5G, engenharia, telecomunicações]
semestre: 9
area: Telecom
creditos: 6
dificuldade: alta
importancia: critica
código: TEL013
carga_horaria: 60h (4 créditos)
status: completo
pré_requisitos: [Telefonia, Redes Sem Fio, Propagacao]
links: [Comunicacoes Digitais, Redes Comunicacao Dados, Antenas]
aliases: [Telefonia_Celular]
keywords: [telefonia celular, redes móveis, 5G, engenharia, telecomunicações]
resumo: "Estudo dos sistemas de telefonia celular: evolução das gerações móveis (1G a 5G), arquitetura de redes celulares, técnicas de acesso múltiplo, mobilidade e handover, planejamento de células, redes 4G LTE e 5G NR, serviço"
---

# Telefonia Celular

## 1. Ementa Oficial

Estudo dos sistemas de telefonia celular: evolução das gerações móveis (1G a 5G), arquitetura de redes celulares, técnicas de acesso múltiplo, mobilidade e handover, planejamento de células, redes 4G LTE e 5G NR, serviços e aplicações móveis, IoT e tendências futuras em comunicações móveis.

### Objetivos da Disciplina

**Objetivo Geral:**
Proporcionar ao estudante conhecimentos avançados sobre sistemas de telefonia celular, desde as tecnologias legadas até as redes 5G, capacitando-o a compreender, analisar e projetar sistemas de comunicação móvel.

**Objetivos Específicos:**
- Compreender a evolução histórica das redes celulares (1G a 5G)
- Entender arquiteturas de redes móveis e seus componentes
- Conhecer técnicas de acesso múltiplo (FDMA, TDMA, CDMA, OFDMA)
- Analisar mobilidade, handover e roaming
- Projetar e dimensionar células de cobertura
- Compreender tecnologias 4G LTE e LTE-Advanced
- Entender arquitetura e recursos do 5G NR
- Conhecer aplicações de IoT e tendências futuras (6G)

---

## 2. Conteúdo Programático

### Unidade 1: Evolução das Redes Celulares (10h)

#### 1.1 Histórico e Gerações
- 1G: AMPS, TACS (analógico)
- 2G: GSM, CDMA (digitalização)
- 2.5G: GPRS, EDGE (packet data)
- 3G: UMTS, CDMA2000 (banda larga móvel)
- 4G: LTE, LTE-Advanced (all-IP)
- 5G: NR (New Radio) - eMBB, URLLC, mMTC
- Visão de 6G

#### 1.2 Conceitos Fundamentais
- Conceito de célula e cluster
- Estrutura celular e reuso de frequências
- Padrões de reuso (K=3, 4, 7, 12)
- Fator de reuso e eficiência espectral
- Conceito de capacidade celular
- Grade celular hexagonal
- Cálculo de tráfego (Erlang B e C)

---

### Unidade 2: Arquitetura de Redes Móveis (10h)

#### 2.1 Arquitetura 2G (GSM)
- BSS (Base Station Subsystem): BTS, BSC
- NSS (Network and Switching Subsystem): MSC, HLR, VLR, AUC, EIR
- Interfaces: Um, Abis, A
- Canais lógicos e físicos
- Sinalização SS7 em GSM
- GPRS e EDGE: adição de elementos de pacote (PCU, SGSN, GGSN)

#### 2.2 Arquitetura 3G (UMTS)
- UTRAN: NodeB, RNC
- Core Network: CS e PS domains
- Interfaces: Uu, Iub, Iur, Iu
- WCDMA e sua evolução (HSPA, HSPA+)
- Soft handover

#### 2.3 Arquitetura 4G (LTE/EPC)
- E-UTRAN: eNodeB (base stations)
- EPC (Evolved Packet Core)
  - MME (Mobility Management Entity)
  - S-GW (Serving Gateway)
  - P-GW (PDN Gateway)
  - HSS (Home Subscriber Server)
  - PCRF (Policy and Charging Rules Function)
- Interfaces: S1, X2, SGi
- All-IP network (AIPN)

---

### Unidade 3: Técnicas de Acesso Múltiplo (12h)

#### 3.1 FDMA e TDMA
- FDMA (Frequency Division Multiple Access)
  - Princípios e implementação
  - Aplicações em 1G (AMPS)
- TDMA (Time Division Multiple Access)
  - Estrutura de frame
  - Guard times
  - Aplicações em 2G (GSM)
  - Eficiência espectral

#### 3.2 CDMA
- CDMA (Code Division Multiple Access)
  - Espectro espalhado (spread spectrum)
  - Códigos de Walsh, sequências PN
  - Process gain
  - Soft capacity
  - Power control
  - Rake receiver
- WCDMA e CDMA2000

#### 3.3 OFDMA e SC-FDMA
- OFDMA (Orthogonal Frequency Division Multiple Access)
  - Subportadoras ortogonais
  - Cyclic prefix
  - Resource blocks
  - Aplicações em 4G (downlink)
- SC-FDMA (Single Carrier FDMA)
  - Aplicações em 4G (uplink)
  - Menor PAPR que OFDMA
- NOMA (Non-Orthogonal Multiple Access)
  - Aplicações em 5G

---

### Unidade 4: Mobilidade e Handover (10h)

#### 4.1 Conceitos de Mobilidade
- Localização e paging
- Tracking area e routing area
- Atualização de localização
- Attach e detach procedures
- Idle mode vs connected mode

#### 4.2 Handover
- Tipos de handover:
  - Hard handover
  - Soft handover (CDMA)
  - Softer handover
- Handover em GSM
- Handover em UMTS
- Handover em LTE (X2-based, S1-based)
- Handover preparation e execution
- Handover failure e recovery

#### 4.3 Roaming
- Conceitos de roaming
- Roaming nacional e internacional
- Interfaces de roaming
- Billing e tarifação em roaming
- LTE roaming (S8 interface)
- VoLTE roaming

---

### Unidade 5: Planejamento de Células (10h)

#### 5.1 Fundamentos de Planejamento
- Cobertura vs capacidade
- Link budget
- Path loss models
  - Okumura-Hata
  - COST-231
  - Walfisch-Ikegami
- Shadowing margin
- Cell edge probability
- Indoor coverage

#### 5.2 Dimensionamento
- Cálculo de tráfego (Erlang)
- Grade de oferta e grade de demanda
- Número de células necessárias
- Balanceamento de carga
- Sectorização
- Cell splitting
- Microcells, picocells, femtocells

#### 5.3 Interferência e Frequências
- Interferência co-canal
- Interferência adjacente
- Carrier-to-Interference ratio (C/I)
- Frequency hopping
- Fractional frequency reuse
- ICIC (Inter-Cell Interference Coordination)
- eICIC (enhanced ICIC) e FeICIC

---

### Unidade 6: Tecnologias 4G e 5G (8h)

#### 6.1 LTE e LTE-Advanced
- Evolução do LTE
- LTE-Advanced features:
  - Carrier Aggregation (CA)
  - MIMO avançado (8x8, 4x4)
  - CoMP (Coordinated Multi-Point)
  - eICIC
  - HetNets (Heterogeneous Networks)
- LTE-Advanced Pro (4.5G)

#### 6.2 5G NR (New Radio)
- Requisitos e casos de uso:
  - eMBB (enhanced Mobile Broadband)
  - URLLC (Ultra-Reliable Low Latency Communications)
  - mMTC (massive Machine Type Communications)
- Arquitetura 5G (SA e NSA)
- NG-RAN: gNodeB
- 5G Core (SBA - Service-Based Architecture)
- Novas frequências: sub-6 GHz e mmWave
- Massive MIMO e beamforming
- Network slicing
- MEC (Multi-access Edge Computing)
- D2D (Device-to-Device)
- V2X (Vehicle-to-Everything)

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Operadoras Móveis
- **Planejamento de rede**: Dimensionamento de cobertura e capacidade
- **Otimização**: Ajuste de parâmetros para melhor performance
- **Rollout**: Expansão de cobertura
- **Refarming**: Reorganização de espectro
- **Modernização**: Upgrade 2G/3G para 4G/5G

### 3.2 Infraestrutura de Rede
- **Macrocells**: Torres e antenas de grande porte
- **Small cells**: Densificação de rede
  - Microcells
  - Picocells
  - Femtocells
  - DAS (Distributed Antenna Systems)
- **Sites indoor**: Shopping centers, aeroportos, estádios
- **Backhaul**: Conectividade das estações base

### 3.3 Serviços e Aplicações
- **VoLTE/VoNR**: Voz de alta qualidade sobre 4G/5G
- **Video calling**: Chamadas de vídeo HD
- **Mobile broadband**: Internet móvel de alta velocidade
- **IoT celular**: NB-IoT, LTE-M para dispositivos conectados
- **Mobile payments**: Pagamentos móveis
- **Streaming**: Vídeo e música em movimento

### 3.4 Indústria e Setor Público
- **Indústria 4.0**: Conectividade para automação
- **Smart grids**: Redes elétricas inteligentes
- **Telemedicina**: Saúde móvel
- **Educação**: Ensino à distância
- **Segurança pública**: Comunicações de emergência
- **Transportes**: Logística e frota

### 3.5 Tecnologias Emergentes
- **5G privado**: Redes dedicadas para empresas
- **5G mmWave**: Alta capacidade em áreas densas
- **Network slicing**: Redes virtuais dedicadas
- **Edge computing**: Processamento na borda
- **V2X**: Comunicação veicular
- **Drones**: Controle de UAVs

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Conceitos de redes celulares e arquiteturas
- **Aulas práticas**: Uso de ferramentas de planejamento de RF
- **Laboratórios**: Análise de sinais de redes móveis
- **Projetos**: Planejamento de rede celular
- **Seminários**: Tecnologias 5G e casos de uso
- **Estudos de caso**: Redes de operadoras brasileiras

### 4.2 Recursos Didáticos
- Quadro e projetor multimídia
- Software de planejamento (Atoll, Planet, Pathloss)
- Analisadores de drive test
- Simuladores de rede celular
- Material didático digital
- Acesso a dados de cobertura de operadoras

### 4.3 Avaliação

**Instrumentos:**
- Provas teórico-práticas (2 avaliações) - 50%
- Projeto de planejamento de rede celular - 30%
- Seminários/Relatórios - 15%
- Participação - 5%

**Critérios:**
- Compreensão da evolução das gerações móveis
- Conhecimento de arquiteturas de redes celulares
- Entendimento de técnicas de acesso múltiplo
- Capacidade de calcular link budget e dimensionar células
- Conhecimento de mobilidade e handover
- Entendimento de tecnologias 4G/5G

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Evolução das redes celulares. 1G a 5G |
| 2 | Conceitos de célula e reuso de frequências |
| 3 | Arquitetura 2G (GSM). GPRS e EDGE |
| 4 | Arquitetura 3G (UMTS). WCDMA |
| 5 | **1ª Avaliação** |
| 6 | Arquitetura 4G (LTE/EPC) |
| 7 | Técnicas de acesso: FDMA, TDMA |
| 8 | CDMA e WCDMA |
| 9 | OFDMA e SC-FDMA |
| 10 | **2ª Avaliação** |
| 11 | Mobilidade, handover e roaming |
| 12 | Planejamento de células. Link budget |
| 13 | Dimensionamento e interferência |
| 14 | LTE-Advanced e 5G NR |
| 15 | IoT e tendências futuras. Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. RAPPAPORT, T. S. **Wireless Communications: Principles and Practice**. 2. ed. Prentice Hall, 2002.
2. DAHLMAN, E. et al. **4G: LTE/LTE-Advanced for Mobile Broadband**. 2. ed. Academic Press, 2014.
3. DAHLMAN, E. et al. **5G NR: The Next Generation Wireless Access Technology**. Academic Press, 2018.

### Bibliografia Complementar
4. GARG, V. K. **Wireless Communications & Networking**. Morgan Kaufmann, 2007.
5. SCHILLER, J. **Mobile Communications**. 2. ed. Addison-Wesley, 2003.
6. GOODMAN, D. J. **Wireless Personal Communications Systems**. Addison-Wesley, 1997.
7. HOLMA, H.; TOSKALA, A. **LTE for UMTS: Evolution to LTE-Advanced**. 2. ed. Wiley, 2011.
8. SESIA, S.; TOUFIK, I.; BAKER, M. **LTE: The UMTS Long Term Evolution: From Theory to Practice**. 2. ed. Wiley, 2011.

### Recursos Online
- [3GPP Specifications](https://www.3gpp.org/specifications) - Especificações 3G/4G/5G
- [GSMA](https://www.gsma.com/) - Associação de operadoras móveis
- [IEEE 802.16](https://www.ieee802.org/16/) - Padrões WiMAX
- [5G Americas](https://www.5gamericas.org/) - Recursos sobre 5G
- [ETSI 5G](https://www.etsi.org/technologies/5g) - Padrões europeus
- [Anatel - Serviço Móvel Pessoal](https://www.gov.br/anatel/pt-br) - Regulamentação brasileira

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Compreender a evolução histórica e tendências das redes celulares

**RA2** - Analisar arquiteturas de redes móveis 2G, 3G, 4G e 5G

**RA3** - Conhecer e comparar técnicas de acesso múltiplo (FDMA, TDMA, CDMA, OFDMA)

**RA4** - Entender mecanismos de mobilidade, handover e roaming

**RA5** - Projetar e dimensionar células de cobertura celular

**RA6** - Analisar interferência e aplicar técnicas de coordenação

**RA7** - Compreender tecnologias avançadas: LTE-Advanced e 5G NR

**RA8** - Conhecer aplicações de IoT e tendências futuras em comunicações móveis

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: Telefonia Celular é uma disciplina em constante evolução. Acompanhe as novidades sobre 5G e prepare-se para o 6G!

> 📱 **Gerações**: Cada G trouxe revoluções. 1G=analógico, 2G=digital, 3G=dados, 4G=all-IP, 5G=conectividade universal.

> 🏗️ **Arquitetura**: Entenda bem os componentes de cada geração. O 5G mudou radicalmente com a arquitetura Service-Based.

> 📊 **Acesso Múltiplo**: FDMA é simples, TDMA é eficiente, CDMA é robusto, OFDMA é versátil. Cada um tem seu lugar na história.

> 🔄 **Handover**: O desafio das redes móveis: manter a chamada enquanto se move entre células. Soft handover (CDMA) vs hard handover (GSM/LTE).

> 📐 **Planejamento**: Use ferramentas profissionais (Atoll, Planet). A teoria é importante, mas a prática com dados reais é essencial.

> 🚀 **5G**: Não é só mais velocidade! É baixa latência (URLLC) e conexão massiva (mMTC). Habilite novas aplicações como carros autônomos e cirurgia remota.

> 🔗 **Conexões**: Esta disciplina integra conhecimentos de:
> - Propagação (modelagem de canal)
> - Comunicações Digitais (modulação, codificação)
> - Antenas (MIMO, beamforming)
> - Redes sem Fio (Wi-Fi, conectividade)

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025