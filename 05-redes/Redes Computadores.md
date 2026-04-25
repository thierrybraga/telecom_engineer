---
tags: [redes, computadores, internet, protocolos, engenharia, telecomunicações]
semestre: 8
area: Computação
creditos: 4
dificuldade: alta
importancia: critica
código: TEL003
carga_horaria: 60h (4 créditos)
status: completo
pré_requisitos: [Algoritmos II, Sistemas Digitais]
links: [Redes Comunicacao Dados, Redes Sem Fio, Comunicacoes Digitais]
aliases: [Redes_Computadores]
keywords: [redes, computadores, internet, protocolos, engenharia, telecomunicações]
resumo: "Estudo dos princípios e arquiteturas de redes de computadores: modelos de referência OSI e TCP/IP, tecnologias de enlace, protocolos de rede, transporte e aplicação, redes locais e de longa distância, segurança de redes "
---

# Redes de Computadores

## 1. Ementa Oficial

Estudo dos princípios e arquiteturas de redes de computadores: modelos de referência OSI e TCP/IP, tecnologias de enlace, protocolos de rede, transporte e aplicação, redes locais e de longa distância, segurança de redes e tendências futuras.

### Objetivos da Disciplina

**Objetivo Geral:**
Proporcionar ao estudante conhecimentos sobre fundamentos, arquiteturas e protocolos de redes de computadores, capacitando-o a compreender, projetar e gerenciar infraestruturas de comunicação de dados.

**Objetivos Específicos:**
- Compreender os modelos de referência OSI e TCP/IP
- Conhecer as tecnologias de enlace de dados
- Entender os protocolos de rede IP e roteamento
- Analisar protocolos de transporte (TCP e UDP)
- Conhecer protocolos de aplicação (HTTP, FTP, DNS, etc.)
- Projetar e configurar redes locais (LANs)
- Entender tecnologias de redes de longa distância (WANs)
- Conhecer aspectos de segurança de redes

---

## 2. Conteúdo Programático

### Unidade 1: Introdução e Arquitetura de Redes (10h)

#### 1.1 Fundamentos de Redes
- Histórico e evolução das redes de computadores
- Classificação de redes (LAN, MAN, WAN, PAN)
- Topologias de rede
- Meios de transmissão:
  - Cabeados (par trançado, coaxial, fibra óptica)
  - Sem fio (rádio, microondas, satélite)
- Taxas de transmissão e largura de banda

#### 1.2 Modelos de Referência
- Modelo OSI (7 camadas)
- Modelo TCP/IP (4 camadas)
- Comparação OSI vs TCP/IP
- Encapsulamento e desencapsulamento
- Unidades de dados (PDU)
- Arquiteturas cliente-servidor e P2P

---

### Unidade 2: Camada de Enlace de Dados (10h)

#### 2.1 Funções da Camada de Enlace
- Framing (delimitação de quadros)
- Controle de erro (detecção e correção)
  - Código de Hamming
  - CRC (Cyclic Redundancy Check)
  - Checksum
- Controle de fluxo
  - Stop-and-wait
  - Sliding window
- Protocolos de acesso ao meio

#### 2.2 Redes Locais (LANs)
- Tecnologia Ethernet
  - Ethernet clássica (CSMA/CD)
  - Ethernet comutada
  - Fast Ethernet, Gigabit Ethernet, 10 Gigabit
- Endereçamento MAC
- Switches e bridges
- Spanning Tree Protocol (STP)
- VLANs (Virtual LANs)

#### 2.3 Tecnologias Sem Fio
- IEEE 802.11 (Wi-Fi)
- Bluetooth
- ZigBee
- LoRaWAN
- Considerações de mobilidade

---

### Unidade 3: Camada de Rede (12h)

#### 3.1 Protocolo IP
- Endereçamento IPv4
  - Classes de endereços
  - Máscaras de sub-rede
  - CIDR (Classless Inter-Domain Routing)
  - Subnetting e VLSM
- Endereçamento IPv6
  - Formato de endereços
  - Tipos de endereços (unicast, multicast, anycast)
  - Transição IPv4 para IPv6
- Protocolos ARP e ICMP

#### 3.2 Roteamento
- Conceitos de roteamento
- Algoritmos de roteamento
  - Distance Vector (RIP)
  - Link State (OSPF)
  - Path Vector (BGP)
- Roteamento estático vs dinâmico
- Tabelas de roteamento
- Roteadores e gateways

#### 3.3 Interconexão de Redes
- NAT (Network Address Translation)
- PAT (Port Address Translation)
- Túneis e VPNs
- MPLS (introdução)
- Arquiteturas de backbone

---

### Unidade 4: Camada de Transporte (10h)

#### 4.1 Protocolo TCP
- Características do TCP
- Estabelecimento de conexão (three-way handshake)
- Encerramento de conexão
- Controle de fluxo (janela deslizante)
- Controle de congestionamento
  - Slow start
  - Congestion avoidance
  - Fast retransmit e fast recovery
- Números de sequência e acknowledgments

#### 4.2 Protocolo UDP
- Características do UDP
- Comparação TCP vs UDP
- Aplicações UDP
- Multicast e broadcast

#### 4.3 Qualidade de Serviço (QoS)
- Conceitos de QoS
- IntServ e DiffServ
- Controle de tráfego
- Políticas de escalonamento
- MPLS e engenharia de tráfego

---

### Unidade 5: Camada de Aplicação (10h)

#### 5.1 Protocolos de Aplicação
- HTTP/HTTPS (World Wide Web)
- FTP/SFTP (transferência de arquivos)
- SMTP/POP3/IMAP (e-mail)
- DNS (sistema de nomes de domínio)
- DHCP (configuração automática)
- SNMP (gerenciamento de rede)

#### 5.2 Aplicações de Rede
- World Wide Web
- Streaming de mídia
- VoIP (Voz sobre IP)
- Videoconferência
- Jogos online
- Computação em nuvem

#### 5.3 Segurança na Camada de Aplicação
- SSL/TLS
- HTTPS
- Certificados digitais
- Criptografia de ponta a ponta

---

### Unidade 6: Segurança de Redes e Tendências (8h)

#### 6.1 Fundamentos de Segurança
- Confidencialidade, integridade, disponibilidade
- Ameaças e ataques
  - Malware, vírus, worms
  - Ataques DDoS
  - Phishing
  - Man-in-the-middle
- Firewalls
- IDS/IPS (Sistemas de Detecção/Prevenção de Intrusão)

#### 6.2 Mecanismos de Segurança
- Criptografia
  - Criptografia simétrica
  - Criptografia assimétrica
  - Hashing
- Autenticação e autorização
- VPNs (Virtual Private Networks)
- IPsec

#### 6.3 Tendências e Novas Tecnologias
- Software Defined Networking (SDN)
- Network Function Virtualization (NFV)
- Internet das Coisas (IoT)
- Redes 5G
- Edge computing
- Redes definidas por intenção (IBN)

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Infraestrutura de Telecom
- **Backbone IP**: Redes de transporte de dados
- **Backhaul**: Interconexão de estações base
- **Core networks**: Núcleo de redes celulares
- **Metro Ethernet**: Redes metropolitanas
- **DWDM/OTN**: Transporte óptico de dados

### 3.2 Redes de Acesso
- **FTTH/FTTx**: Redes de fibra até o usuário
- **xDSL**: Acesso via par metálico
- **HFC**: Redes híbridas fibra-coaxial
- **Wi-Fi**: Acesso sem fio
- **5G**: Novas arquiteturas de acesso

### 3.3 Data Centers e Cloud
- **Redes de data center**: Topologias spine-leaf
- **Virtualização**: SDN, NFV
- **Interconexão**: DCI (Data Center Interconnect)
- **CDN**: Content Delivery Networks
- **Multicloud**: Conectividade entre nuvens

### 3.4 Serviços de Valor Agregado
- **VoIP**: Telefonia IP
- **IPTV**: TV por protocolo IP
- **IoT**: Redes para Internet das Coisas
- **Smart Cities**: Infraestrutura de comunicação
- **Indústria 4.0**: Redes industriais

### 3.5 Gerenciamento e Operação
- **NMS/OSS**: Sistemas de gerenciamento
- **Monitoramento**: SNMP, NetFlow, sFlow
- **Automação**: Orquestração de redes
- **Segurança**: Firewalls, IDS/IPS
- **Troubleshooting**: Diagnóstico de falhas

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Conceitos e protocolos
- **Aulas práticas**: Configuração de equipamentos
- **Laboratórios**: Simulações e experimentos
- **Projetos**: Design de redes
- **Seminários**: Tecnologias emergentes
- **Estudos de caso**: Redes reais

### 4.2 Recursos Didáticos
- Quadro e projetor multimídia
- Laboratório de redes com switches e roteadores
- Software de simulação (Packet Tracer, GNS3, EVE-NG)
- Analisadores de protocolo (Wireshark)
- Material didático digital
- Equipamentos de rede reais

### 4.3 Avaliação

**Instrumentos:**
- Provas teórico-práticas (2 avaliações) - 50%
- Projetos de design de rede - 30%
- Laboratórios práticos - 15%
- Participação - 5%

**Critérios:**
- Compreensão dos modelos OSI e TCP/IP
- Capacidade de subnetting e endereçamento IP
- Conhecimento de protocolos de transporte
- Habilidade em configurar equipamentos de rede
- Entendimento de tecnologias LAN e WAN
- Conhecimento de segurança de redes

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Introdução às redes. Modelos OSI e TCP/IP |
| 2 | Meios de transmissão. Topologias |
| 3 | Camada de enlace: framing, controle de erro |
| 4 | Ethernet. Switches. VLANs |
| 5 | **1ª Avaliação** |
| 6 | Endereçamento IP (IPv4). Subnetting |
| 7 | Endereçamento IPv6. ARP. ICMP |
| 8 | Roteamento. Algoritmos. Protocolos (RIP, OSPF, BGP) |
| 9 | NAT. Interconexão de redes |
| 10 | **2ª Avaliação** |
| 11 | TCP. Controle de fluxo e congestionamento |
| 12 | UDP. Multicast. QoS |
| 13 | Protocolos de aplicação (HTTP, DNS, DHCP, etc.) |
| 14 | Segurança de redes. Criptografia. Firewalls |
| 15 | Tendências: SDN, NFV, IoT, 5G. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. KUROSE, J. F.; ROSS, K. W. **Redes de Computadores e a Internet: Uma Abordagem Top-Down**. 6. ed. Pearson, 2013.
2. TANENBAUM, A. S.; WETHERALL, D. J. **Redes de Computadores**. 5. ed. Pearson, 2011.
3. STALLINGS, W. **Data and Computer Communications**. 10. ed. Pearson, 2013.

### Bibliografia Complementar
4. COMER, D. E. **Redes de Computadores e Internet**. 6. ed. Bookman, 2016.
5. FOROUZAN, B. A. **Comunicação de Dados e Redes de Computadores**. 4. ed. McGraw-Hill, 2008.
6. PETERSON, L. L.; DAVIE, B. S. **Computer Networks: A Systems Approach**. 5. ed. Morgan Kaufmann, 2011.
7. ODOM, W. **CCNA Routing and Switching**. Cisco Press, 2016.
8. FALL, K. R.; STEVENS, W. R. **TCP/IP Illustrated, Volume 1: The Protocols**. 2. ed. Addison-Wesley, 2011.

### Recursos Online
- [Cisco Networking Academy](https://www.netacad.com/) - Cursos Cisco
- [Wireshark](https://www.wireshark.org/) - Analisador de protocolos
- [Packet Tracer](https://www.netacad.com/courses/packet-tracer) - Simulador Cisco
- [GNS3](https://www.gns3.com/) - Simulador de redes
- [RFC Editor](https://www.rfc-editor.org/) - Documentos RFC
- [IEEE 802 Standards](https://standards.ieee.org/) - Padrões IEEE

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Compreender os modelos de referência OSI e TCP/IP e suas camadas

**RA2** - Projetar e configurar redes locais Ethernet com switches e VLANs

**RA3** - Realizar subnetting e endereçamento IP para IPv4 e IPv6

**RA4** - Configurar e analisar protocolos de roteamento (RIP, OSPF, BGP)

**RA5** - Entender e aplicar protocolos de transporte TCP e UDP

**RA6** - Conhecer e utilizar protocolos de aplicação (HTTP, DNS, DHCP, etc.)

**RA7** - Implementar mecanismos básicos de segurança em redes

**RA8** - Acompanhar tendências tecnológicas como SDN, NFV, IoT e 5G

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: Redes é uma disciplina prática. Configure equipamentos reais ou simuladores para fixar os conceitos!

> 🌐 **TCP/IP**: É o "idioma" da Internet. Domine bem o modelo de camadas - ele organiza todo o conhecimento de redes.

> 🎯 **Endereçamento**: Subnetting é essencial. Pratique até conseguir calcular subnets de cabeça!

> 🚦 **Roteamento**: Entenda como os pacotes encontram seu caminho. RIP é simples, OSPF é eficiente, BGP é o "grande" da Internet.

> 📦 **TCP vs UDP**: TCP é confiável mas lento. UDP é rápido mas não confiável. Escolha conforme a aplicação.

> 🔒 **Segurança**: Redes sem segurança estão sujeitas a ataques. Entenda firewalls, criptografia e VPNs.

> 🔗 **Conexões**: Esta disciplina é fundamental para:
> - Redes de Comunicação de Dados (aprofundamento)
> - Redes sem Fio (tecnologias de acesso)
> - Telecomunicações (infraestrutura IP)
> - Sistemas de comunicação modernos

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025