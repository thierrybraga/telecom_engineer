---
tags: [telefonia, comunicações, redes, engenharia, telecomunicações]
semestre: 8
area: Telecom
creditos: 4
dificuldade: alta
importancia: critica
código: TEL012
carga_horaria: 60h (4 créditos)
status: completo
pré_requisitos: [Principios Comunicacoes, Redes Computadores]
links: [Telefonia Celular, Comunicacoes Digitais, Redes Comunicacao Dados]
aliases: []
keywords: [telefonia, comunicações, redes, engenharia, telecomunicações]
resumo: "Estudo dos sistemas de telefonia: histórico e evolução, arquitetura de redes telefônicas, sinalização, comutação, transmissão, sistemas de telefonia digital, VoIP, IMS e convergência de serviços."
---

# Telefonia

## 1. Ementa Oficial

Estudo dos sistemas de telefonia: histórico e evolução, arquitetura de redes telefônicas, sinalização, comutação, transmissão, sistemas de telefonia digital, VoIP, IMS e convergência de serviços. Aplicações em redes de telecomunicações modernas.

### Objetivos da Disciplina

**Objetivo Geral:**
Proporcionar ao estudante conhecimentos sobre sistemas de telefonia fixa e móvel, desde os sistemas tradicionais até as tecnologias de voz sobre IP, capacitando-o a compreender, analisar e projetar sistemas de comunicação de voz.

**Objetivos Específicos:**
- Compreender a evolução histórica dos sistemas de telefonia
- Entender a arquitetura de redes telefônicas tradicionais e modernas
- Conhecer técnicas de sinalização em redes telefônicas
- Analisar sistemas de comutação de circuitos e pacotes
- Entender tecnologias de transmissão para telefonia
- Compreender sistemas de telefonia digital (ISDN, PDH, SDH)
- Aplicar conceitos de VoIP (Voz sobre IP)
- Conhecer arquiteturas IMS e convergência de serviços

---

## 2. Conteúdo Programático

### Unidade 1: Fundamentos e Evolução da Telefonia (10h)

#### 1.1 Histórico e Evolução
- Invenção do telefone (Alexander Graham Bell)
- Telefonia analógica tradicional (POTS - Plain Old Telephone Service)
- Evolução para telefonia digital
- Liberalização e desregulamentação do setor
- Convergência de redes e serviços
- Telefonia fixa vs móvel

#### 1.2 Arquitetura de Redes Telefônicas
- Estrutura hierárquica da rede telefônica
- Centrais telefônicas (exchanges)
  - Central local
  - Central tandem
  - Central de trânsito
- Loop local (last mile)
- Rede de transporte (backbone)
- Sistemas de suporte (OSS/BSS)

---

### Unidade 2: Sinalização em Redes Telefônicas (10h)

#### 2.1 Sinalização de Assinante
- Sinalização em loop (loop start)
- Sinalização em terra (ground start)
- Tons de sinalização:
  - Tom de discar (dial tone)
  - Tom de ocupado (busy tone)
  - Tom de ringback
  - Tom de confirmação

#### 2.2 Sinalização de Tronco
- Sinalização por canal associado (CAS)
  - E&M (Ear and Mouth)
  - R1, R2
- Sinalização por canal comum (CCS)
  - SS7 (Signaling System 7)
    - Arquitetura SS7
    - Pontos de sinalização (SP, STP, SCP)
    - Mensagens SS7 (ISUP, SCCP, TCAP)
- SIGTRAN (SS7 over IP)

---

### Unidade 3: Comutação em Redes Telefônicas (10h)

#### 3.1 Comutação de Circuitos
- Conceitos de comutação de circuitos
- Matrizes de comutação
  - Comutação espacial
  - Comutação temporal
  - Comutação espaço-temporal
- Centrais digitais (switches)
  - Classificação de switches
  - Arquitetura de centrais
- Tarifação e bilhetagem (CDR - Call Detail Record)

#### 3.2 Serviços Suplementares
- Identificação de chamadas (Caller ID)
- Chamada em espera
- Transferência de chamadas
- Conferência
- Secretária eletrônica
- Números gratuitos (0800) e de valor agregado

---

### Unidade 4: Transmissão e Sistemas Digitais (10h)

#### 4.1 Multiplexação e Modulação
- Multiplexação por divisão de tempo (TDM)
- Modulação por código de pulso (PCM)
- Hierarquia digital plesiócrona (PDH)
  - E1 (2 Mbps) e T1 (1.5 Mbps)
- Hierarquia digital síncrona (SDH/SONET)
  - STM-1, STM-4, STM-16, STM-64
- Redes ópticas para telefonia

#### 4.2 ISDN (Integrated Services Digital Network)
- Conceitos de ISDN
- Canais B e D
- Interfaces BRI (Basic Rate Interface) e PRI (Primary Rate Interface)
- Serviços oferecidos
- Evolução para tecnologias de pacotes

---

### Unidade 5: VoIP e Tecnologias de Pacotes (12h)

#### 5.1 Fundamentos de VoIP
- Conceitos de Voz sobre IP
- Protocolos de sinalização:
  - SIP (Session Initiation Protocol)
  - H.323
  - MGCP (Media Gateway Control Protocol)
  - MEGACO/H.248
- Protocolos de transporte de mídia:
  - RTP (Real-time Transport Protocol)
  - RTCP (RTP Control Protocol)
- Codecs de voz:
  - G.711, G.729, G.723.1, G.722
  - AMR, AMR-WB

#### 5.2 Arquitetura de VoIP
- Gateways de mídia (Media Gateways)
- Controladores de gateway (Media Gateway Controllers)
- Gatekeepers
- SBC (Session Border Controllers)
- QoS em VoIP
- Protocolos de qualidade (MOS, R-factor)

#### 5.3 Serviços de VoIP
- Telefonia IP corporativa (PBX IP)
- Centrais virtuais (Hosted PBX)
- Serviços de VoIP sobre Internet (Skype, WhatsApp)
- WebRTC
- Unified Communications (UC)

---

### Unidade 6: IMS e Arquiteturas Modernas (8h)

#### 6.1 Arquitetura IMS (IP Multimedia Subsystem)
- Conceitos de IMS
- Componentes da arquitetura IMS
  - P-CSCF (Proxy-CSCF)
  - I-CSCF (Interrogating-CSCF)
  - S-CSCF (Serving-CSCF)
  - HSS (Home Subscriber Server)
- Serviços em IMS
- Convergência fixo-móvel

#### 6.2 Tecnologias Emergentes
- Softswitches e next-generation networks (NGN)
- Software-Defined Networking (SDN) em telefonia
- Network Functions Virtualization (NFV)
- WebRTC e comunicações em tempo real
- Inteligência Artificial em call centers
- APIs de comunicação (CPaaS)

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Operadoras de Telecomunicações
- **Redes fixas**: Infraestrutura de telefonia tradicional
- **Redes de nova geração**: NGN, IMS
- **Interconexão**: Troca de tráfego entre operadoras
- **Roaming**: Acordos internacionais
- **Serviços de valor agregado**: 0800, 0900, etc.

### 3.2 Empresas e Centrais Telefônicas
- **PBX tradicional**: Centrais privadas analógicas/digitais
- **IP PBX**: Centrais baseadas em VoIP (Asterisk, Cisco CUCM, Avaya)
- **Unified Communications**: Integração voz-dados-vídeo
- **Call centers**: Sistemas de atendimento (ACD, IVR)
- **Contact centers**: Omnichannel (voz, chat, e-mail, redes sociais)

### 3.3 Serviços de VoIP
- **Operadores VoIP**: Oi, Vivo, Claro, Nextel
- **Serviços OTT**: Skype, WhatsApp, FaceTime, Google Meet
- **SIP Trunking**: Troncos SIP para empresas
- **Cloud PBX**: Centrais na nuvem
- **WebRTC**: Comunicação em navegadores

### 3.4 Redes Móveis
- **CS (Circuit Switched)**: Voz tradicional em 2G/3G
- **VoLTE**: Voz sobre LTE (4G)
- **VoNR**: Voz sobre 5G NR
- **SRVCC**: Single Radio Voice Call Continuity
- **Wi-Fi Calling**: Voz sobre Wi-Fi

### 3.5 Internet das Coisas (IoT)
- **M2M**: Comunicação máquina-a-máquina
- **NB-IoT**: Narrowband IoT para comunicações
- **LTE-M**: LTE para máquinas
- **Sensores conectados**: Telemetria e monitoramento
- **Comunicações de emergência**: E-911, E-112

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Conceitos de telefonia e redes
- **Demonstrações práticas**: Sistemas de comutação e VoIP
- **Laboratórios**: Configuração de PBX IP (Asterisk, FreePBX)
- **Projetos**: Implementação de sistema de telefonia
- **Seminários**: Tecnologias emergentes (IMS, WebRTC)
- **Estudos de caso**: Operadoras de telecom

### 4.2 Recursos Didáticos
- Quadro e projetor multimídia
- Laboratório com equipamentos de telefonia
- Software de simulação de redes telefônicas
- PBX IP para práticas (Asterisk/FreePBX)
- Softphones e telefones IP
- Analisadores de protocolo (Wireshark para SIP/RTP)
- Material didático digital

### 4.3 Avaliação

**Instrumentos:**
- Provas teórico-práticas (2 avaliações) - 50%
- Projeto de implementação de sistema VoIP - 30%
- Laboratórios práticos - 15%
- Participação - 5%

**Critérios:**
- Compreensão da arquitetura de redes telefônicas
- Conhecimento de sistemas de sinalização
- Entendimento de comutação de circuitos e pacotes
- Capacidade de configurar sistemas VoIP
- Conhecimento de protocolos SIP e RTP
- Entendimento de arquiteturas IMS

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Histórico da telefonia. Arquitetura de redes telefônicas |
| 2 | Estrutura hierárquica. Loop local e rede de transporte |
| 3 | Sinalização de assinante e de tronco |
| 4 | SS7. SIGTRAN |
| 5 | **1ª Avaliação** |
| 6 | Comutação de circuitos. Matrizes de comutação |
| 7 | Centrais digitais. Serviços suplementares |
| 8 | Multiplexação PCM. PDH e SDH |
| 9 | ISDN. Evolução para pacotes |
| 10 | **2ª Avaliação** |
| 11 | Fundamentos de VoIP. Protocolos SIP e H.323 |
| 12 | Codecs de voz. RTP/RTCP |
| 13 | Arquitetura de VoIP. Gateways e SBC |
| 14 | IMS. Arquitetura e componentes |
| 15 | Tecnologias emergentes. Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. BATES, R. J. **Telecomunicações de Voz e Dados**. 3. ed. LTC, 2004.
2. GRILLO, G. **Telefonia Digital**. Makron Books, 1995.
3. DAVIDSON, J.; PETERS, J. **Voice over IP Fundamentals**. Cisco Press, 2000.

### Bibliografia Complementar
4. COLLINS, D. **Carrier Grade Voice Over IP**. 3. ed. McGraw-Hill, 2013.
5. SWALE, R. **Telecommunications Technology Handbook**. Artech House, 2003.
6. KUMAR, B. P. **Broadband Communications: A Professionals Guide to ATM, Frame Relay, SMDS, SONET, and B-ISDN**. McGraw-Hill, 1995.
7. DUTTA-ROY, A. **An Introduction to ATM Networks**. IEEE Press, 2004.
8. MEGGELEN, J. V.; SMITH, J.; MADSEN, L. **Asterisk: The Future of Telephony**. 2. ed. O'Reilly, 2007.

### Recursos Online
- [ITU-T Recommendations](https://www.itu.int/en/ITU-T/publications/Pages/recs.aspx) - Recomendações ITU-T
- [IETF SIP Working Group](https://datatracker.ietf.org/wg/sip/documents/) - Documentos SIP
- [Asterisk Project](https://www.asterisk.org/) - PBX open source
- [FreePBX](https://www.freepbx.org/) - Interface para Asterisk
- [VoIP Info](https://www.voip-info.org/) - Wiki de VoIP
- [Wireshark](https://www.wireshark.org/) - Analisador de protocolos

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Compreender a evolução histórica e arquitetura de redes telefônicas

**RA2** - Analisar sistemas de sinalização em redes telefônicas (CAS, CCS, SS7)

**RA3** - Entender princípios de comutação de circuitos e matrizes de comutação

**RA4** - Compreender sistemas de transmissão digital (PDH, SDH, ISDN)

**RA5** - Aplicar conceitos de VoIP e protocolos de sinalização (SIP, H.323)

**RA6** - Configurar e gerenciar sistemas de telefonia IP

**RA7** - Entender arquiteturas IMS e convergência de serviços

**RA8** - Acompanhar tendências em telefonia e comunicações unificadas

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: Telefonia é uma área em transição. Domine bem os conceitos tradicionais (circuitos, SS7) e as novas tecnologias (VoIP, IMS)!

> ☎️ **POTS**: Plain Old Telephone Service é a base. Entenda o loop local e a hierarquia de centrais antes de partir para o digital.

> 📞 **Sinalização**: SS7 é o "cérebro" das redes telefônicas tradicionais. É complexo mas fundamental para entender como as chamadas são roteadas.

> 🌐 **VoIP**: A telefonia está migrando para IP. SIP é o protocolo dominante. Aprenda a analisar mensagens SIP!

> 🎵 **Codecs**: Qualidade vs largura de banda. G.711 é transparente mas consome muito. G.729 é eficiente mas comprime.

> 🏢 **PBX IP**: Configure um Asterisk ou FreePBX. A prática é essencial para entender telefonia IP.

> 🔗 **Conexões**: Esta disciplina integra conhecimentos de:
> - Princípios de Comunicações (sinais de voz)
> - Redes de Computadores (protocolos IP)
> - Comunicações Digitais (modulação, codificação)
> - Telefonia Celular (convergência fixo-móvel)

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025