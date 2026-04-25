---
tags: [IoT, Internet das Coisas, sensores, engenharia, telecomunicações, optativa]
semestre: 10
area: Optativas
creditos: 4
dificuldade: media
importancia: media
código: OPT003
carga_horaria: 60h (4 créditos)
status: completo
pré_requisitos: [Redes Computadores, Redes Sem Fio, Microprocessadores]
links: [Redes Sem Fio, Redes Comunicacao Dados, Telefonia Celular]
aliases: [Optativa_III]
keywords: [IoT, Internet das Coisas, sensores, engenharia, telecomunicações, optativa]
resumo: "Estudo dos fundamentos e aplicações da Internet das Coisas: arquiteturas IoT, sensores e atuadores, protocolos de comunicação, plataformas em nuvem, segurança em IoT, aplicações industriais, cidades inteligentes, saúde c"
---

# Optativa III: Internet das Coisas (IoT)

## 1. Ementa Oficial

Estudo dos fundamentos e aplicações da Internet das Coisas: arquiteturas IoT, sensores e atuadores, protocolos de comunicação, plataformas em nuvem, segurança em IoT, aplicações industriais, cidades inteligentes, saúde conectada e tendências emergentes em sistemas de comunicação para IoT.

### Objetivos da Disciplina

**Objetivo Geral:**
Proporcionar ao estudante conhecimentos especializados sobre Internet das Coisas (IoT), capacitando-o a compreender, projetar e implementar sistemas conectados de sensores e atuadores para diversas aplicações em engenharia.

**Objetivos Específicos:**
- Compreender arquiteturas e ecossistemas de IoT
- Conhecer sensores, atuadores e hardware para IoT
- Entender protocolos de comunicação específicos para IoT (MQTT, CoAP, LoRaWAN)
- Projetar e desenvolver aplicações IoT com microcontroladores
- Conhecer plataformas em nuvem para IoT
- Entender desafios de segurança em sistemas IoT
- Conhecer aplicações industriais (Indústria 4.0) e cidades inteligentes
- Analisar tendências emergentes: edge computing, AIoT, digital twin

---

## 2. Conteúdo Programático

### Unidade 1: Fundamentos de IoT (10h)

#### 1.1 Introdução à Internet das Coisas
- Conceito e definição de IoT
- Histórico e evolução
- Diferença entre IoT, M2M e SCADA
- Arquitetura em camadas de IoT
  - Camada de percepção (sensores/atuadores)
  - Camada de rede (conectividade)
  - Camada de aplicação (processamento/serviços)
- Ecossistema IoT: fabricantes, operadoras, desenvolvedores
- Projeções de mercado e tendências

#### 1.2 Hardware para IoT
- Microcontroladores para IoT
  - Arduino
  - ESP8266/ESP32
  - Raspberry Pi
  - STM32
  - ARM Cortex-M
- Sensores: temperatura, umidade, pressão, movimento, luz, gás
- Atuadores: relés, motores, válvulas
- Módulos de comunicação: Wi-Fi, Bluetooth, ZigBee, LoRa, NB-IoT
- Shield e HATs de expansão
- Consumo de energia em dispositivos IoT

---

### Unidade 2: Protocolos de Comunicação para IoT (12h)

#### 2.1 Protocolos de Aplicação
- **MQTT** (Message Queuing Telemetry Transport)
  - Modelo publish/subscribe
  - Brokers MQTT (Mosquitto, HiveMQ, AWS IoT Core)
  - Tópicos e hierarquia
  - QoS (Quality of Service)
  - Retained messages e Last Will
- **CoAP** (Constrained Application Protocol)
  - Modelo RESTful para dispositivos limitados
  - Métodos GET, POST, PUT, DELETE
  - Observação de recursos
- **HTTP/REST** para IoT
- **WebSockets**
- Comparação entre protocolos

#### 2.2 Protocolos de Transporte e Rede
- **TCP vs UDP** em IoT
- **6LoWPAN**: IPv6 over Low-Power Wireless Personal Area Networks
- **RPL** (Routing Protocol for Low-Power and Lossy Networks)
- **DTLS** (Datagram Transport Layer Security)
- **TLS/SSL** para IoT

#### 2.3 Tecnologias de Conectividade
- **LPWAN** (Low-Power Wide-Area Network)
  - LoRa/LoRaWAN
  - Sigfox
  - NB-IoT (Narrowband IoT)
  - LTE-M (LTE for Machines)
- **Redes de curto alcance**
  - Bluetooth/BLE (Bluetooth Low Energy)
  - ZigBee (IEEE 802.15.4)
  - Z-Wave
  - Thread
  - Wi-Fi HaLow (802.11ah)
- **Redes de campo industrial**
  - Modbus
  - Profibus
  - CAN bus
  - Industrial Ethernet

---

### Unidade 3: Plataformas e Processamento de Dados (10h)

#### 3.1 Plataformas em Nuvem para IoT
- **AWS IoT Core**
  - Device Gateway
  - Device Shadow
  - Rules Engine
  - Integração com outros serviços AWS
- **Microsoft Azure IoT Hub**
  - Device Provisioning Service
  - Stream Analytics
  - Time Series Insights
- **Google Cloud IoT Core**
- **IBM Watson IoT Platform**
- **Plataformas open-source**
  - ThingsBoard
  - Node-RED
  - Thinger.io
  - Mainflux

#### 3.2 Armazenamento e Análise de Dados
- Bancos de dados para IoT
  - Séries temporais (InfluxDB, TimescaleDB)
  - NoSQL (MongoDB, Cassandra)
- Big Data em IoT
- Stream processing (Apache Kafka, Apache Flink)
- Visualização de dados (Grafana, Kibana)
- Dashboards e interfaces de usuário

#### 3.3 Edge Computing e Fog Computing
- Conceito de edge computing
- Processamento na borda vs nuvem
- Latência e largura de banda
- Arquiteturas híbridas
- Dispositivos edge (gateways industriais)
- Fog computing: hierarquia de processamento

---

### Unidade 4: Segurança em IoT (10h)

#### 4.1 Ameaças e Vulnerabilidades
- Superfície de ataque em IoT
- Ataques DDoS via botnets de IoT (Mirai, Reaper)
- Vulnerabilidades em dispositivos legados
- Falta de atualizações de segurança
- Snooping e eavesdropping
- Man-in-the-middle attacks
- Firmware e hardware trojans

#### 4.2 Mecanismos de Segurança
- Criptografia em dispositivos limitados
  - Algoritmos leves (ChaCha20, Poly1305)
  - ECC (Elliptic Curve Cryptography)
- Autenticação e autorização
  - OAuth 2.0 e JWT para IoT
  - Certificados X.509
  - TPM (Trusted Platform Module)
- Secure boot
- Over-the-air (OTA) updates
- Network segmentation
- Blockchain para IoT

#### 4.3 Standards e Frameworks de Segurança
- OWASP IoT Top 10
- NIST Cybersecurity for IoT
- IEC 62443 (Industrial Automation and Control Systems)
- ETSI IoT Security standards
- ISO/IEC 27001 para IoT

---

### Unidade 5: Aplicações de IoT (10h)

#### 5.1 Indústria 4.0 e IoT Industrial
- Conceito de Indústria 4.0
- IoT industrial (IIoT - Industrial Internet of Things)
- Manutenção preditiva
- Monitoramento de equipamentos
- Digital Twin (gêmeo digital)
- Controle de qualidade automatizado
- Cadeia de suprimentos conectada
- Plataformas: GE Predix, Siemens MindSphere, PTC ThingWorx

#### 5.2 Cidades Inteligentes (Smart Cities)
- Iluminação pública inteligente
- Gestão de tráfego e transporte
- Monitoramento de qualidade do ar
- Gestão de resíduos
- Estacionamento inteligente
- Segurança pública e vigilância
- Eficiência energética em edifícios

#### 5.3 Saúde Conectada (IoMT)
- Wearables e dispositivos vestíveis
- Monitoramento remoto de pacientes
- Casas inteligentes para idosos
- Dispositivos médicos implantáveis
- Telemedicina
- Rastreamento de medicamentos
- Privacidade de dados de saúde (HIPAA, LGPD)

#### 5.4 Agricultura de Precisão (Smart Agriculture)
- Monitoramento de solo e clima
- Irrigação inteligente
- Drones agrícolas
- Rastreamento de gado
- Gestão de colheitas
- Supply chain de alimentos

#### 5.5 Outras Aplicações
- Varejo inteligente (smart retail)
- Logística e rastreamento de frota
- Energia (smart grids, medidores inteligentes)
- Casa conectada (smart home)
- Wearables de consumo

---

### Unidade 6: Tendências e Tópicos Avançados (8h)

#### 6.1 Inteligência Artificial e IoT (AIoT)
- Machine Learning em dispositivos IoT
- TinyML (Machine Learning em microcontroladores)
- Visão computacional em edge
- Processamento de linguagem natural
- Redes neurais embarcadas
- Anomaly detection
- Predictive analytics

#### 6.2 5G e IoT
- 5G para IoT: eMBB, URLLC, mMTC
- Network slicing para aplicações IoT
- Private 5G networks
- 5G NR para IoT industrial
- Redes determinísticas
- TSN (Time-Sensitive Networking)

#### 6.3 Tendências Emergentes
- Digital Twin avançado
- Metaverso industrial
- Robótica colaborativa (cobots)
- Veículos autônomos conectados
- Swarm robotics
- Bio-IoT e implantes
- IoT espacial (satélites LEO para IoT)
- Sustentabilidade e IoT verde

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Infraestrutura de Redes para IoT
- **Core networks**: Arquiteturas 5G para suportar IoT massivo
- **Radio access**: NB-IoT, LTE-M, LoRaWAN
- **Backhaul**: Conectividade para gateways IoT
- **Network slicing**: Slices dedicados para diferentes aplicações IoT
- **Edge computing**: MEC (Multi-access Edge Computing) para IoT

### 3.2 Protocolos e Comunicação
- **Desenvolvimento de protocolos**: Otimização para dispositivos limitados
- **Interoperabilidade**: Tradutores de protocolos e gateways
- **QoS**: Qualidade de serviço para diferentes classes de tráfego IoT
- **SDN/NFV**: Software-defined networking para gerenciamento de redes IoT

### 3.3 Sistemas de Monitoramento
- **Performance de rede**: Monitoramento de QoS em tempo real
- **Predição de falhas**: Análise preditiva em infraestrutura de telecom
- **Gestão de energia**: Otimização de consumo em estações base
- **Asset tracking**: Rastreamento de equipamentos de campo

### 3.4 Segurança de Redes
- **Detecção de anomalias**: Identificação de dispositivos comprometidos
- **Zero trust architecture**: Segurança para dispositivos IoT em redes corporativas
- **Criptografia leve**: Algoritmos para dispositivos com recursos limitados

### 3.5 Serviços de Valor Agregado
- **Plataformas de IoT**: Oferta de plataformas como serviço
- **Consultoria**: Projetos de digitalização e transformação
- **Integração**: Sistemas legados conectados à nuvem
- **Analytics**: Processamento e análise de dados de sensores

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Conceitos de arquiteturas e protocolos IoT
- **Laboratórios práticos**: Programação de microcontroladores
- **Projetos**: Desenvolvimento de solução IoT completa
- **Seminários**: Casos de uso e tendências do mercado
- **Workshops**: Uso de plataformas em nuvem (AWS, Azure)
- **Estudos de caso**: Implementações reais em indústria

### 4.2 Recursos Didáticos
- Quadro e projetor multimídia
- Laboratório com kits de desenvolvimento IoT
  - Arduino, ESP32, Raspberry Pi
  - Sensores e atuadores diversos
- Acesso a plataformas em nuvem (AWS IoT, Azure IoT)
- Software: Arduino IDE, PlatformIO, Node-RED
- Simuladores: Tinkercad, Proteus
- Material didático digital

### 4.3 Avaliação

**Instrumentos:**
- Provas teórico-práticas (2 avaliações) - 40%
- Projeto de sistema IoT completo - 40%
- Laboratórios práticos - 15%
- Participação - 5%

**Critérios:**
- Compreensão de arquiteturas e protocolos IoT
- Capacidade de programar microcontroladores
- Conhecimento de plataformas em nuvem
- Entendimento de desafios de segurança
- Qualidade do projeto desenvolvido
- Documentação e apresentação do projeto

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Introdução a IoT. Arquiteturas e ecossistema |
| 2 | Hardware para IoT. Microcontroladores e sensores |
| 3 | Protocolos de aplicação: MQTT |
| 4 | Protocolos: CoAP, HTTP, WebSockets |
| 5 | **1ª Avaliação** |
| 6 | Tecnologias de conectividade: LPWAN (LoRa, NB-IoT) |
| 7 | Redes de curto alcance: BLE, ZigBee, Wi-Fi |
| 8 | Plataformas em nuvem: AWS IoT, Azure IoT |
| 9 | Armazenamento, análise e visualização de dados |
| 10 | **2ª Avaliação** |
| 11 | Edge computing. Processamento na borda |
| 12 | Segurança em IoT. Ameaças e mecanismos |
| 13 | Indústria 4.0. IoT industrial e Digital Twin |
| 14 | Smart Cities, Saúde Conectada, Agricultura de Precisão |
| 15 | Tendências: AIoT, 5G e IoT, Blockchain. Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. DA SILVA, R. C.; DA COSTA, J. P. C. **Internet das Coisas: Conceitos, Aplicações e Desafios**. Série Tekne, 2019.
2. HONDA, M. A. **Internet das Coisas (IoT): Fundamentos e Aplicações na Indústria 4.0**. Érica, 2020.
3. OLIVEIRA, T. **IoT: Internet das Coisas: Arquiteturas, Aplicações e Desafios**. Brasport, 2019.

### Bibliografia Complementar
4. MCEWEN, A.; CASSIMALLY, H. **Designing the Internet of Things**. Wiley, 2013.
5. BAHGA, A.; MADISETTI, V. **Internet of Things: A Hands-On Approach**. VPT, 2014.
6. SCHwartz, M. **Internet of Things with ESP8266**. Packt Publishing, 2016.
7. RAY, P. P. **Internet of Things for Architects: Architecting IoT solutions by implementing sensors, communication infrastructure, edge computing, analytics, and security**. Packt Publishing, 2018.
8. PETHURU, R.; CHETTY, P. **The Internet of Things: Enabling Technologies, Platforms, and Use Cases**. CRC Press, 2017.

### Recursos Online
- [AWS IoT Documentation](https://docs.aws.amazon.com/iot/) - Documentação AWS IoT
- [Microsoft Azure IoT](https://azure.microsoft.com/en-us/services/iot-hub/) - Azure IoT Hub
- [MQTT Specification](https://mqtt.org/mqtt-specification/) - Especificação MQTT
- [LoRa Alliance](https://lora-alliance.org/) - Tecnologia LoRaWAN
- [Arduino](https://www.arduino.cc/) - Plataforma Arduino
- [ESP32](https://docs.espressif.com/projects/esp-idf/) - Documentação ESP32

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Compreender arquiteturas, ecossistemas e aplicações de Internet das Coisas

**RA2** - Programar microcontroladores e interfaces com sensores/atuadores

**RA3** - Implementar protocolos de comunicação MQTT, CoAP e HTTP para IoT

**RA4** - Conectar dispositivos a plataformas em nuvem para IoT

**RA5** - Analisar e visualizar dados de sensores em tempo real

**RA6** - Identificar vulnerabilidades e aplicar mecanismos de segurança em sistemas IoT

**RA7** - Desenvolver projetos de IoT para aplicações industriais e smart cities

**RA8** - Acompanhar tendências emergentes como edge computing, AIoT e 5G para IoT

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: IoT é multidisciplinar! Você precisará de conhecimentos de eletrônica, programação, redes e processamento de dados. Pratique muito!

> 🔌 **Hardware**: Comece com Arduino para aprender os conceitos, depois migre para ESP32 quando precisar de conectividade Wi-Fi/Bluetooth nativa.

> 📡 **Protocolos**: MQTT é o mais popular para IoT. Entenda bem o modelo publish/subscribe e os diferentes níveis de QoS.

> ☁️ **Nuvem**: Não reinvente a roda. Use plataformas como AWS IoT ou Azure IoT Hub para gerenciar seus dispositivos.

> 🔒 **Segurança**: IoT é um pesadelo de segurança. Sempre use criptografia, autenticação forte e mantenha o firmware atualizado!

> 🏭 **Indústria 4.0**: O maior impacto do IoT está na indústria. Entenda bem conceitos como Digital Twin e manutenção preditiva.

> 🤖 **AIoT**: A combinação de IA + IoT está revolucionando o mercado. TinyML permite rodar ML em microcontroladores!

> 🔗 **Conexões**: Esta disciplina integra conhecimentos de:
> - Microprocessadores (programação embarcada)
> - Redes de Computadores (protocolos, conectividade)
> - Redes sem Fio (LoRa, NB-IoT, Bluetooth)
> - Telecomunicações (infraestrutura 5G para IoT)

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025