---
tags: [radiodifusão, radioenlace, broadcast, telecomunicações, engenharia]
semestre: 8
area: Telecom
creditos: 4
dificuldade: media
importancia: alta
código: TEL011
carga_horaria: 60h (4 créditos)
status: completo
pré_requisitos: [Principios Comunicacoes, Propagacao, Antenas]
links: [Microondas, Comunicacoes Digitais, Processamento Audio Video]
aliases: [Radiodifusao_Radioenlace]
keywords: [radiodifusão, radioenlace, broadcast, telecomunicações, engenharia]
resumo: "Estudo dos sistemas de radiodifusão sonora e televisiva, analógicos e digitais, e de radioenlaces: princípios de transmissão, técnicas de modulação, padrões de radiodifusão, planejamento de sistemas de broadcast, radioen"
---

# Sistemas de Radiodifusão e Radioenlace

## 1. Ementa Oficial

Estudo dos sistemas de radiodifusão sonora e televisiva, analógicos e digitais, e de radioenlaces: princípios de transmissão, técnicas de modulação, padrões de radiodifusão, planejamento de sistemas de broadcast, radioenlaces terrestres e por satélite, arquiteturas e aplicações em telecomunicações.

### Objetivos da Disciplina

**Objetivo Geral:**
Proporcionar ao estudante conhecimentos sobre sistemas de radiodifusão e radioenlaces, capacitando-o a compreender, analisar e projetar sistemas de transmissão de áudio, vídeo e dados via radiodifusão e enlaces de rádio.

**Objetivos Específicos:**
- Compreender os princípios de sistemas de radiodifusão sonora e televisiva
- Conhecer técnicas de modulação para broadcast (AM, FM, TV analógica e digital)
- Entender os padrões de radiodifusão digital (ISDB-T, DVB, DRM, HD Radio)
- Analisar sistemas de radioenlace terrestre e por satélite
- Projetar enlaces de microondas e sistemas de distribuição
- Conhecer arquiteturas de head-end e transmissores
- Entender aspectos regulatórios e de licenciamento
- Aplicar conhecimentos em projetos de sistemas de broadcast

---

## 2. Conteúdo Programático

### Unidade 1: Fundamentos de Radiodifusão (10h)

#### 1.1 Introdução à Radiodifusão
- Histórico da radiodifusão
- Evolução tecnológica: analógico para digital
- Classificação dos serviços de radiodifusão
- Espectro de frequências para broadcast
- Organização do setor de radiodifusão
- Convergência digital e novas mídias

#### 1.2 Conceitos Básicos de Transmissão
- Estações transmissoras e receptoras
- Cadeia de transmissão (head-end, STL, transmissor, antena)
- Estudos de cobertura e planejamento
- Interferência e proteção de canais
- Propagação para broadcast
- Single Frequency Network (SFN)

---

### Unidade 2: Radiodifusão Sonora (12h)

#### 2.1 Sistemas AM e FM Analógicos
- Radiodifusão AM (Ondas Médias)
  - Modulação de amplitude
  - Características de propagação
  - Faixa de 530-1700 kHz
- Radiodifusão FM (VHF)
  - Modulação de frequência
  - Pré-ênfase e de-ênfase
  - Estéreo FM (multiplex)
  - Faixa de 88-108 MHz
- RDS (Radio Data System)

#### 2.2 Radiodifusão Digital de Áudio
- DRM (Digital Radio Mondiale)
  - Modos DRM30 e DRM+
  - Codificação audio AAC
  - Multiplexação COFDM
- HD Radio (IBOC - In-Band On-Channel)
  - Arquitetura híbrida
  - Sidebands digitais
- DAB/DAB+ (Digital Audio Broadcasting)
  - Ensemble e multiplex
  - MPEG Audio Layer II / HE-AAC v2
- Rádio por Internet (streaming)

---

### Unidade 3: Sistemas de Televisão (12h)

#### 3.1 TV Analógica
- Sistemas de TV em cores
  - NTSC (525 linhas, 60 Hz)
  - PAL (625 linhas, 50 Hz)
  - SECAM
- Sinal de vídeo composto e componente
- Sincronismo e blanking
- Modulação de vídeo (VSB)
- Modulação de áudio (FM)
- Faixas de VHF e UHF

#### 3.2 TV Digital Terrestre
- Padrões mundiais:
  - ISDB-T (Brasil, Japão)
  - DVB-T/DVB-T2 (Europa)
  - ATSC (EUA, Canadá, México)
  - DTMB (China)
- COFDM e modulação
- Codificação de vídeo (MPEG-2, H.264, H.265)
- Multiplexação de programas (TS - Transport Stream)
- EPG (Electronic Program Guide)
- Interatividade (Ginga no ISDB-T)

#### 3.3 TV por Outros Meios
- TV por satélite (DTH)
  - Modulação (QPSK, 8PSK)
  - Codificação e criptografia
- TV a cabo
  - Arquitetura HFC
  - Modulação QAM
- IPTV (TV por protocolo IP)
- TV móvel (ISDB-Tmm, DVB-H)

---

### Unidade 4: Radioenlaces Terrestres (12h)

#### 4.1 Fundamentos de Radioenlaces
- Conceito de radioenlace
- Classificação:
  - Por frequência: HF, VHF, UHF, SHF, EHF
  - Por aplicação: PDH, SDH, IP, celular
- Topologias: ponto-a-ponto, ponto-a-multiponto
- Arquitetura de um enlace
- Aspectos regulatórios (licenciamento de freqüências)

#### 4.2 Planejamento de Radioenlaces
- Estudo de viabilidade
- Análise de perfil de terreno
- Zona de Fresnel e clearance
- Perda de percurso (path loss)
- Fading e margens
- Link budget (balanço de potência)
- Diversidade (espacial, de frequência)
- Coordenação de frequências

#### 4.3 Tecnologias de Radioenlace
- Sistemas PDH/SDH
- Sistemas IP/Ethernet
- Modulações: QPSK, 16-QAM, 64-QAM, 256-QAM
- Capacidade vs. robustez
- Adaptive Modulation
- XPIC (Cross-Polarization Interference Canceller)
- ATPC (Automatic Transmit Power Control)
- ACM (Adaptive Coding and Modulation)

---

### Unidade 5: Radioenlaces por Satélite (8h)

#### 5.1 Fundamentos de Satélites
- Órbitas de satélites
  - GEO (Geostationary)
  - MEO (Medium Earth Orbit)
  - LEO (Low Earth Orbit)
- Segmentos espacial, de controle e terreno
- Transponders e frequências
- Banda C, Ku, Ka
- Enlace ascendente (uplink) e descendente (downlink)

#### 5.2 VSAT e Aplicações
- Arquitetura VSAT
- Topologias: star, mesh
- Acesso múltiplo: FDMA, TDMA, CDMA, SCPC
- Aplicações:
  - TV por satélite (DTH)
  - Internet via satélite
  - Redes corporativas
  - Comunicações móveis marítimas/aeronáuticas

---

### Unidade 6: Instalações e Sistemas (6h)

#### 6.1 Estações Transmissoras
- Head-end e master control
- Transmissores de RF
  - Transmissores de estado sólido
  - Transmissores de tubo (IOT, klystron)
- Sistemas de combinação de canais
- Sistemas de alimentação e backup
- Torres e antenas de broadcast
- Sistemas de monitoramento

#### 6.2 Infraestrutura e Normas
- Sistemas de energia (nobreaks, geradores)
- Climatização
- Normas técnicas da ANATEL
- Normas da ABNT (NBR 15601-15607 - TV Digital)
- Licenciamento de estações
- Proteção contra descargas atmosféricas

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Radiodifusão Comercial
- **Emissoras de rádio AM/FM**: Sistemas de transmissão
- **TV aberta**: Transmissores digitais terrestres
- **TV por assinatura**: Cabo, satélite, IPTV
- **Web rádio e Web TV**: Streaming de conteúdo
- **Rádio digital**: Implementação de DRM, HD Radio, DAB

### 3.2 Radioenlaces de Operadoras
- **Backhaul celular**: Interligação de estações base
- **Backbone de transporte**: Enlaces de longa distância
- **Acesso corporativo**: Links dedicados para empresas
- **Redes de utilidade pública**: Energia, água, saneamento
- **Redes governamentais**: Segurança pública, defesa

### 3.3 Aplicações Industriais
- **Monitoramento remoto**: Telemetria via radioenlace
- **Vídeo vigilância**: Câmeras em locais remotos
- **Controle de processos**: Automação industrial
- **Mineração e agronegócio**: Comunicações em áreas remotas
- **Óleo e gás**: Plataformas offshore e dutovias

### 3.4 Eventos e Cobertura Temporária
- **OB vans**: Unidades móveis de transmissão
- **Cobertura de eventos**: Shows, esportes, política
- **Enlaces de contingência**: Backup de fibra
- **Comunicações de emergência**: Desastres naturais
- **Cobertura jornalística**: Link ao vivo para TV

### 3.5 Novas Tecnologias
- **5G Broadcast**: Radiodifusão via redes 5G
- **ATSC 3.0**: NextGen TV nos EUA
- **DVB-I**: Entrega de TV via IP
- **Low Latency DASH**: Streaming de baixa latência
- **Cloud playout**: Transmissão em nuvem

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Conceitos de radiodifusão e radioenlaces
- **Aulas práticas**: Uso de software de planejamento de RF
- **Laboratórios**: Análise de sinais de broadcast
- **Projetos**: Design de enlace de microondas
- **Visitas técnicas**: Emissoras e torres de transmissão
- **Seminários**: Novas tecnologias de broadcast

### 4.2 Recursos Didáticos
- Quadro e projetor multimídia
- Software de planejamento (Pathloss, Radio Mobile)
- Analisadores de espectro e TV
- Simuladores de sistemas de modulação
- Material didático digital
- Vídeos de instalações reais

### 4.3 Avaliação

**Instrumentos:**
- Provas teórico-práticas (2 avaliações) - 50%
- Projeto de radioenlace - 30%
- Seminários/Relatórios - 15%
- Participação - 5%

**Critérios:**
- Compreensão de sistemas de radiodifusão analógica e digital
- Conhecimento de padrões de TV digital (ISDB-T, DVB)
- Capacidade de planejar radioenlaces
- Cálculo de link budget e margens
- Entendimento de arquiteturas de head-end
- Conhecimento de aspectos regulatórios

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Introdução à radiodifusão. Histórico e evolução |
| 2 | Cadeia de transmissão. Estudos de cobertura |
| 3 | Radiodifusão AM e FM analógicos |
| 4 | Radiodifusão digital: DRM, HD Radio, DAB |
| 5 | **1ª Avaliação** |
| 6 | TV analógica: NTSC, PAL, SECAM |
| 7 | TV digital terrestre: ISDB-T, DVB-T, ATSC |
| 8 | TV por satélite, cabo e IPTV |
| 9 | Fundamentos de radioenlaces |
| 10 | **2ª Avaliação** |
| 11 | Planejamento de radioenlaces. Link budget |
| 12 | Tecnologias de radioenlace. Modulações |
| 13 | Radioenlaces por satélite. VSAT |
| 14 | Estações transmissoras. Head-end |
| 15 | Normas e regulamentação. Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. SOARES, L. F. G. **Sistemas de Radiodifusão**. 2. ed. LTC, 2006.
2. WHITAKER, J. **Radio Frequency Transmission Systems: Design and Operation**. McGraw-Hill, 1990.
3. FREE, J. R. **Modern Radio Science 1993**. Oxford University Press, 1993.

### Bibliografia Complementar
4. REIMERS, U. H. **DVB: The Family of International Standards for Digital Video Broadcasting**. 2. ed. Springer, 2005.
5. FISCHER, W. **Digital Video and Audio Broadcasting Technology: A Practical Engineering Guide**. 3. ed. Springer, 2010.
6. GHOBRIAL, A.; SHARIF, S. **Microwave Link Design**. arXiv, 2005.
7. MAZOR, B. **Radio and Television Broadcasting in Cold War America*. dissertation, 2003.
8. KELLER, P. A. **Electronic Display Measurement: Concepts, Techniques, and Instrumentation**. Wiley, 1997.

### Recursos Online
- [ABERT - Associação Brasileira de Emissoras de Rádio e TV](https://www.abert.org.br/)
- [SET - Sociedade Brasileira de Engenharia de Televisão](https://www.set.org.br/)
- [ANATEL - Radiodifusão](https://www.gov.br/anatel/pt-br)
- [ITU-R Broadcasting](https://www.itu.int/en/ITU-R/conferences/broadcasting/Pages/default.aspx)
- [DVB Project](https://www.dvb.org/) - Padrões DVB
- [ATSC](https://www.atsc.org/) - Padrões ATSC

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Compreender os princípios de sistemas de radiodifusão sonora e televisiva

**RA2** - Analisar técnicas de modulação para broadcast analógico e digital

**RA3** - Conhecer e comparar os padrões de radiodifusão digital (ISDB-T, DVB, ATSC)

**RA4** - Projetar radioenlaces terrestres considerando propagação e interferência

**RA5** - Calcular link budget e dimensionar sistemas de transmissão

**RA6** - Entender arquiteturas de radioenlace por satélite e VSAT

**RA7** - Conhecer aspectos regulatórios e de licenciamento de estações

**RA8** - Aplicar conhecimentos em projetos de sistemas de broadcast e distribuição

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: Radiodifusão é uma área fascinante que une engenharia de RF com produção de conteúdo. Entenda bem a cadeia completa de transmissão!

> 📻 **AM vs FM**: AM propaga longe (onda de solo + ionosfera) mas tem qualidade inferior. FM tem qualidade estéreo mas alcance limitado à linha do horizonte.

> 📺 **TV Digital**: O Brasil usa ISDB-T com recursos de interatividade (Ginga). Entenda bem as particularidades do padrão brasileiro.

> 📡 **Radioenlaces**: São a "espinha dorsal" de muitas redes. Calcule bem o link budget - uma antena mal dimensionada pode custar caro!

> 🛰️ **Satélites**: GEO são os "clássicos" para broadcast. LEOs como Starlink estão mudando o paradigma de acesso via satélite.

> 📊 **SFN**: Single Frequency Network economiza espectro mas exige sincronização precisa. É a base da TV digital moderna.

> 🔗 **Conexões**: Esta disciplina integra conhecimentos de:
> - Princípios de Comunicações (modulações)
> - Propagação (cobertura)
> - Antenas (sistemas irradiantes)
> - Microondas (radioenlaces)
> - Processamento de Áudio e Vídeo (codecs)

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025