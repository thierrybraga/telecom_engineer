---
tags: [redes, comunicação de dados, protocolos, telecomunicações, engenharia]
semestre: 7
area: Telecom
creditos: 4
dificuldade: alta
importancia: critica
código: TEL007
carga_horaria: 60h (4 créditos)
status: completo
pré_requisitos: [Redes Computadores, Comunicacoes Digitais]
links: [Redes Sem Fio, Comunicacoes Opticas, Telefonia]
aliases: [Redes_Comunicacao_Dados]
keywords: [redes, comunicação de dados, protocolos, telecomunicações, engenharia]
resumo: "Estudo das redes de comunicação de dados: arquiteturas de redes, protocolos de comunicação, redes locais e metropolitanas, tecnologias de transporte, comutação de pacotes e circuitos, qualidade de serviço, gerenciamento "
---

# Redes de Comunicação de Dados

## 1. Ementa Oficial

Estudo das redes de comunicação de dados: arquiteturas de redes, protocolos de comunicação, redes locais e metropolitanas, tecnologias de transporte, comutação de pacotes e circuitos, qualidade de serviço, gerenciamento de redes e segurança. Aplicações em sistemas de telecomunicações.

### Objetivos da Disciplina

**Objetivo Geral:**
Proporcionar ao estudante conhecimentos avançados sobre redes de comunicação de dados, capacitando-o a analisar, projetar e gerenciar infraestruturas de comunicação de dados em ambientes de telecomunicações.

**Objetivos Específicos:**
- Compreender arquiteturas e protocolos de redes de comunicação de dados
- Analisar tecnologias de comutação de circuitos e pacotes
- Entender redes locais, metropolitanas e de longa distância
- Conhecer tecnologias de transporte de dados
- Aplicar conceitos de qualidade de serviço (QoS) em redes
- Compreender gerenciamento e segurança de redes de dados
- Projetar soluções de comunicação de dados

---

## 2. Conteúdo Programático

### Unidade 1: Arquiteturas de Redes de Comunicação (10h)

#### 1.1 Evolução das Redes de Comunicação
- Histórico das redes de dados
- Redes de comutação de circuitos vs comutação de pacotes
- Arquiteturas de redes de telecomunicações
- Convergência voz-dados-vídeo
- Arquiteturas de próxima geração (NGN)
- Arquiteturas de redes definidas por software (SDN)

#### 1.2 Modelos de Serviço
- Modelo cliente-servidor
- Modelo peer-to-peer (P2P)
- Arquiteturas hierárquicas
- Redes overlay
- Content Delivery Networks (CDN)
- Edge computing e fog computing

---

### Unidade 2: Tecnologias de Enlace e Acesso (10h)

#### 2.1 Tecnologias de Acesso
- xDSL (ADSL, VDSL, G.fast)
- Cabo (HFC - Hybrid Fiber Coaxial)
- Fibra óptica (FTTH, FTTB, FTTC)
- Acesso sem fio (Wi-Fi, WiMAX, LTE)
- Satélite (VSAT, DTH)
- Tecnologias emergentes (5G, Li-Fi)

#### 2.2 Protocolos de Enlace
- HDLC (High-Level Data Link Control)
- PPP (Point-to-Point Protocol)
- Frame Relay (conceitos históricos)
- ATM (Asynchronous Transfer Mode)
- MPLS (Multiprotocol Label Switching)
- Ethernet Carrier

---

### Unidade 3: Redes Locais e Metropolitanas (10h)

#### 3.1 Ethernet Avançada
- Ethernet de 1 Gbps a 400 Gbps
- Virtual LANs (VLANs) avançadas
  - VLANs por porta, MAC, protocolo
  - Q-in-Q (stacked VLANs)
  - Private VLANs
- Link Aggregation (LACP)
- Spanning Tree avançado (RSTP, MSTP)
- Ethernet em operadoras (Carrier Ethernet)

#### 3.2 Redes Metropolitanas (MANs)
- Topologias de redes metropolitanas
- Tecnologias Metro Ethernet
- RPR (Resilient Packet Ring)
- PON (Passive Optical Networks)
  - GPON
  - EPON
  - NG-PON2
- Redes ópticas metropolitanas

---

### Unidade 4: Redes de Longa Distância e Transporte (12h)

#### 4.1 Redes de Transporte
- Tecnologias PDH e SDH/SONET
- Redes ópticas DWDM (Dense Wavelength Division Multiplexing)
- CWDM (Coarse WDM)
- OTN (Optical Transport Network)
- ROADMs (Reconfigurable Optical Add-Drop Multiplexers)
- Redes ópticas elásticas

#### 4.2 Tecnologias de Backbone
- IP over DWDM
- IP over MPLS
- MPLS-TP (Transport Profile)
- Segment Routing
- P4 e programabilidade de redes
- Redes ópticas disaggregadas

#### 4.3 Interconexão de Redes
- Pontos de troca de tráfego (IXPs)
- Peering e transit
- Redes de distribuição de conteúdo (CDNs)
- Interconexão de data centers (DCI)
- Redes multicloud

---

### Unidade 5: Qualidade de Serviço e Engenharia de Tráfego (10h)

#### 5.1 Qualidade de Serviço (QoS)
- Parâmetros de QoS
  - Atraso (latency)
  - Jitter (variação de atraso)
  - Perda de pacotes
  - Throughput
- Mecanismos de QoS
  - Classificação e marcação (DSCP, 802.1p)
  - Escalonamento (WFQ, CBWFQ, LLQ)
  - Policiamento e modelagem de tráfego
  - Controle de admissão

#### 5.2 Engenharia de Tráfego
- Conceitos de engenharia de tráfego
- Balanceamento de carga
- Otimização de rotas
- MPLS Traffic Engineering
- RSVP-TE
- Segment Routing com engenharia de tráfego

---

### Unidade 6: Gerenciamento e Segurança de Redes (8h)

#### 6.1 Gerenciamento de Redes
- Modelo TMN (Telecommunications Management Network)
- FCAPS (Fault, Configuration, Accounting, Performance, Security)
- Protocolos de gerenciamento (SNMP, NETCONF, RESTCONF)
- Modelos de dados (YANG)
- Automação de redes
- Redes autônomas e intent-based networking

#### 6.2 Segurança em Redes de Comunicação
- Ameaças específicas a redes de telecom
- Segurança em protocolos de roteamento
- IPsec e VPNs
- TLS/SSL para comunicações
- Firewalls de próxima geração
- Detecção e prevenção de intrusão (IDS/IPS)
- Segurança em SDN/NFV

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Redes de Acesso
- **Redes FTTH**: Arquiteturas PON, GPON/XGS-PON
- **Redes móveis**: Backhaul e fronthaul 4G/5G
- **Wi-Fi corporativo**: WLANs em larga escala
- **Hotspots**: Redes de acesso público
- **Satélite**: Banda larga via satélite

### 3.2 Redes de Transporte e Core
- **Backbone IP/MPLS**: Redes de transporte de operadoras
- **Redes ópticas**: DWDM, OTN, redes elásticas
- **Carrier Ethernet**: Serviços E-Line, E-LAN, E-Tree
- **SDH/SONET modernizado**: Migração para pacotes
- **5G transport**: FlexE, segment routing

### 3.3 Data Centers e Cloud
- **Redes de data center**: Spine-leaf, Clos networks
- **Interconexão de data centers**: DCI, dark fiber, DWDM
- **Virtualização de rede**: SDN, NFV
- **Cloud networking**: VPCs, conectividade híbrida
- **Edge computing**: Redes de borda

### 3.4 Serviços de Telecomunicações
- **VPNs corporativas**: MPLS VPN, IPsec VPN
- **Serviços dedicados**: Linhas alugadas, Ethernet privado
- **VoIP e IMS**: Infraestrutura de voz sobre IP
- **IPTV e vídeo**: Redes de distribuição de conteúdo
- **IoT**: Redes para Internet das Coisas

### 3.5 Operação e Manutenção
- **Monitoramento**: Performance, falhas, configuração
- **Orquestração**: Automação de serviços
- **Provisioning**: Provisionamento automático
- **Troubleshooting**: Diagnóstico e correção
- **Planejamento de capacidade**: Dimensionamento

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Conceitos de arquiteturas e protocolos
- **Aulas práticas**: Configuração de equipamentos de operadoras
- **Laboratórios**: Simulações de redes de transporte
- **Projetos**: Design de redes de comunicação de dados
- **Seminários**: Tecnologias emergentes (5G transport, SDN, NFV)
- **Estudos de caso**: Redes de operadoras reais

### 4.2 Recursos Didáticos
- Quadro e projetor multimídia
- Laboratório com equipamentos de telecom (switches, roteadores, ONTs)
- Simuladores de redes (GNS3, EVE-NG, Cisco Modeling Labs)
- Software de gerenciamento de redes
- Material didático digital
- Acesso a documentação de fabricantes

### 4.3 Avaliação

**Instrumentos:**
- Provas teórico-práticas (2 avaliações) - 50%
- Projetos de design de rede de comunicação - 30%
- Laboratórios e simulações - 15%
- Participação - 5%

**Critérios:**
- Compreensão de arquiteturas de redes de comunicação
- Conhecimento de tecnologias de acesso e transporte
- Capacidade de projetar soluções de QoS
- Entendimento de gerenciamento de redes de telecom
- Habilidade em configurar equipamentos
- Conhecimento de segurança em redes de comunicação

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Arquiteturas de redes de comunicação. Evolução |
| 2 | Modelos de serviço. Redes overlay e CDN |
| 3 | Tecnologias de acesso: xDSL, HFC, FTTx |
| 4 | Protocolos de enlace: HDLC, PPP, MPLS |
| 5 | **1ª Avaliação** |
| 6 | Ethernet avançada. VLANs e agregação |
| 7 | Redes metropolitanas. PON (GPON, EPON) |
| 8 | Tecnologias PDH/SDH. DWDM e OTN |
| 9 | Redes de backbone. IP over DWDM/MPLS |
| 10 | **2ª Avaliação** |
| 11 | Qualidade de Serviço (QoS). Mecanismos |
| 12 | Engenharia de tráfego. MPLS-TE |
| 13 | Gerenciamento de redes. TMN, FCAPS |
| 14 | Automação de redes. SDN, NFV |
| 15 | Segurança em redes de telecom. Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. FOROUZAN, B. A. **Comunicação de Dados e Redes de Computadores**. 4. ed. McGraw-Hill, 2008.
2. TANENBAUM, A. S.; WETHERALL, D. J. **Redes de Computadores**. 5. ed. Pearson, 2011.
3. KUROSE, J. F.; ROSS, K. W. **Redes de Computadores e a Internet: Uma Abordagem Top-Down**. 6. ed. Pearson, 2013.

### Bibliografia Complementar
4. STALLINGS, W. **Data and Computer Communications**. 10. ed. Pearson, 2013.
5. RRAMASWAMI, R.; SIVARAJAN, K.; SASAKI, G. **Optical Networks: A Practical Perspective**. 3. ed. Morgan Kaufmann, 2009.
6. GORALSKI, W. **Optical Networking and DWDM**. McGraw-Hill, 2001.
7. DAVIE, B.; REKHTER, Y. **MPLS: Technology and Applications**. Morgan Kaufmann, 2000.
8. VASSEUR, J. P.; PICKAVET, M.; DEMEESTER, P. **Network Recovery: Protection and Restoration of Optical, SONET-SDH, IP, and MPLS**. Morgan Kaufmann, 2004.

### Recursos Online
- [Metro Ethernet Forum (MEF)](https://www.mef.net/) - Padrões Carrier Ethernet
- [Optical Internetworking Forum (OIF)](https://www.oiforum.com/) - Padrões ópticos
- [ITU-T Study Groups](https://www.itu.int/en/ITU-T/studygroups/Pages/default.aspx) - Padrões ITU-T
- [IETF Working Groups](https://datatracker.ietf.org/wg/) - Padrões IETF
- [Cisco Networking Academy](https://www.netacad.com/) - Cursos técnicos
- [Juniper Learning Portal](https://learningportal.juniper.net/) - Recursos Juniper

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Compreender arquiteturas de redes de comunicação de dados e sua evolução

**RA2** - Analisar e projetar soluções de acesso fixo e móvel

**RA3** - Projetar redes locais, metropolitanas e de transporte

**RA4** - Entender tecnologias de transporte óptico e comutação de pacotes

**RA5** - Implementar mecanismos de qualidade de serviço (QoS) em redes

**RA6** - Aplicar conceitos de engenharia de tráfego em redes de telecom

**RA7** - Conhecer técnicas de gerenciamento e automação de redes

**RA8** - Implementar medidas de segurança em redes de comunicação de dados

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: Redes de comunicação de dados é a ponte entre redes de computadores e telecomunicações. Entenda bem as tecnologias de operadoras!

> 🌐 **Convergência**: Voz, dados e vídeo trafegam na mesma rede IP. Entenda como garantir qualidade para cada tipo de tráfego.

> 🔗 **Transporte**: DWDM e OTN são as tecnologias que movem a Internet por fibra óptica. São essenciais para backbones.

> 📡 **Acesso**: FTTH (fibra até a casa) é o futuro do acesso fixo. Entenda as arquiteturas PON e suas evoluções.

> ⚡ **5G**: As redes de transporte 5G exigem baixa latência e alta capacidade. Tecnologias como FlexE e segment routing são fundamentais.

> 🤖 **Automação**: SDN e NFV estão revolucionando as redes de telecom. Redes programáveis são o presente, não o futuro.

> 🔗 **Conexões**: Esta disciplina aprofunda conhecimentos de:
> - Redes de Computadores (fundamentos)
> - Comunicações Digitais (transmissão)
> - Comunicações Ópticas (transporte)
> - Telefonia (serviços convergentes)

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025