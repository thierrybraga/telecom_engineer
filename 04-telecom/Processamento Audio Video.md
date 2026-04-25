---
tags: [processamento, áudio, vídeo, multimídia, telecomunicações, engenharia]
semestre: 9
area: Telecom
creditos: 4
dificuldade: alta
importancia: alta
código: TEL008
carga_horaria: 60h (4 créditos)
status: completo
pré_requisitos: [Processamento Digital Sinais, Comunicacoes Digitais]
links: [Comunicacoes Opticas, Redes Computadores, Telefonia]
aliases: [Processamento_Audio_Video]
keywords: [processamento, áudio, vídeo, multimídia, telecomunicações, engenharia]
resumo: "Estudo das técnicas de processamento, codificação e transmissão de sinais de áudio e vídeo: amostragem e quantização, compressão de áudio e vídeo, padrões de codificação (MPEG, H.26x, AAC), sistemas de transmissão de TV "
---

# Processamento de Áudio e Vídeo

## 1. Ementa Oficial

Estudo das técnicas de processamento, codificação e transmissão de sinais de áudio e vídeo: amostragem e quantização, compressão de áudio e vídeo, padrões de codificação (MPEG, H.26x, AAC), sistemas de transmissão de TV digital e streaming. Aplicações em telecomunicações e multimídia.

### Objetivos da Disciplina

**Objetivo Geral:**
Proporcionar ao estudante conhecimentos sobre processamento, codificação e transmissão de sinais de áudio e vídeo, capacitando-o a entender e aplicar técnicas modernas de compressão e transmissão de conteúdo multimídia.

**Objetivos Específicos:**
- Compreender os fundamentos de amostragem e quantização de áudio e vídeo
- Conhecer técnicas de compressão de áudio e vídeo
- Entender os padrões de codificação MPEG, H.26x, AAC
- Analisar sistemas de TV digital (ISDB-T, DVB, ATSC)
- Compreender protocolos de streaming e transmissão de vídeo
- Conhecer tecnologias de videoconferência e VoIP
- Aplicar conhecimentos em projetos de sistemas multimídia

---

## 2. Conteúdo Programático

### Unidade 1: Fundamentos de Áudio Digital (10h)

#### 1.1 Percepção Auditiva
- Anatomia do ouvido humano
- Faixa de frequência audível
- Mascaramento auditivo temporal e frequencial
- Limiar de audição
- Diagrama de Fletcher-Munson
- Psicoacústica e modelos perceptuais

#### 1.2 Amostragem e Quantização de Áudio
- Teorema de Nyquist para áudio
- Frequências de amostragem padrão (44.1 kHz, 48 kHz, 96 kHz)
- Resolução de quantização (8, 16, 24 bits)
- Relação sinal-ruído de quantização (SQNR)
- Dithering e noise shaping
- Formatos PCM (Pulse Code Modulation)

#### 1.3 Processamento Básico de Áudio
- Filtragem de áudio
- Equalização
- Efeitos de áudio (reverb, delay, chorus)
- Normalização e compressão dinâmica
- Análise espectral de áudio
- Extratores de características (MFCC, espectrograma)

---

### Unidade 2: Codificação e Compressão de Áudio (10h)

#### 2.1 Compressão Sem Perdas (Lossless)
- Redundância em sinais de áudio
- Codificação preditiva
- Códigos de Huffman
- FLAC (Free Lossless Audio Codec)
- ALAC (Apple Lossless)
- Aplicações de áudio sem perdas

#### 2.2 Compressão Com Perdas (Lossy)
- Modelos psicoacústicos
- Quantização perceptual
- Bancos de filtros (QMF, MDCT)
- MPEG-1 Layer 3 (MP3)
- MPEG-2/4 AAC (Advanced Audio Coding)
- HE-AAC e AAC+
- Ogg Vorbis
- Opus

#### 2.3 Áudio em Aplicações Específicas
- Codificação de voz (telefonia)
- PCM de voz (64 kbps)
- Codificação paramétrica
- Codificação híbrida
- AMR, AMR-WB
- Speex, SILK
- Codecs para VoIP

---

### Unidade 3: Fundamentos de Vídeo Digital (10h)

#### 3.1 Percepção Visual
- Anatomia do olho humano
- Resolução espacial e temporal
- Persistência retiniana
- Sensibilidade a cores vs luminância
- Mascaramento visual
- Modelos de cor (RGB, YUV, YCbCr)

#### 3.2 Amostragem e Representação de Vídeo
- Amostragem espacial (resolução)
- Amostragem temporal (frame rate)
- Subamostragem de croma (4:4:4, 4:2:2, 4:2:0)
- Profundidade de cor (8, 10, 12 bits)
- Taxa de bits bruta de vídeo
- Formatos de vídeo digital (YUV, RGB)

#### 3.3 Padrões de Vídeo Analógico e Digital
- TV analógica: NTSC, PAL, SECAM
- Vídeo composto vs componente
- Vídeo digital SD (Standard Definition)
- Vídeo digital HD (High Definition)
- Vídeo UHD/4K/8K
- HDR (High Dynamic Range)

---

### Unidade 4: Compressão de Vídeo (12h)

#### 4.1 Redundância em Vídeo
- Redundância espacial
- Redundância temporal
- Redundância perceptual
- Redundância estatística
- Correlação inter-quadro
- Correlação intra-quadro

#### 4.2 Técnicas de Compressão de Vídeo
- Codificação por transformada (DCT)
- Quantização
- Codificação preditiva intra-quadro
- Compensação de movimento
- Predição inter-quadro (P-frames, B-frames)
- Vetores de movimento
- Codificação entrópica (Huffman, aritmética)

#### 4.3 Padrões de Codificação de Vídeo
- MPEG-1 (Video CD)
- MPEG-2 (DVD, TV digital)
- MPEG-4 Part 2 (DivX, Xvid)
- H.264/AVC (MPEG-4 Part 10)
- H.265/HEVC (High Efficiency Video Coding)
- H.266/VVC (Versatile Video Coding)
- AV1 (AOMedia Video 1)
- VP8, VP9
- Codificação de tela (screen content coding)

---

### Unidade 5: Sistemas de TV Digital (10h)

#### 5.1 Fundamentos de TV Digital
- Vantagens da TV digital vs analógica
- Multiplexação de programas
- EPG (Electronic Program Guide)
- Serviços de dados
- Interatividade

#### 5.2 Padrões de TV Digital Terrestre
- ISDB-T (Integrated Services Digital Broadcasting - Terrestrial)
- DVB-T/T2 (Digital Video Broadcasting - Terrestrial)
- ATSC (Advanced Television Systems Committee)
- DTMB (Digital Terrestrial Multimedia Broadcast)
- Comparação dos padrões

#### 5.3 Modulação e Transmissão de TV Digital
- Modulação COFDM (Coded Orthogonal Frequency Division Multiplexing)
- Modulação 8VSB (8-level Vestigial Sideband)
- Codificação de canal
- Hierarquias de modulação
- Single Frequency Network (SFN)
- Cobertura e planejamento de redes

---

### Unidade 6: Transmissão e Streaming de Vídeo (8h)

#### 6.1 Protocolos de Streaming
- RTP (Real-time Transport Protocol)
- RTCP (RTP Control Protocol)
- RTSP (Real Time Streaming Protocol)
- RTMP (Real-Time Messaging Protocol)
- HLS (HTTP Live Streaming)
- DASH (Dynamic Adaptive Streaming over HTTP)
- WebRTC

#### 6.2 Adaptação de Taxa e Qualidade
- ABR (Adaptive Bitrate Streaming)
- Controle de congestionamento
- Buffer management
- QoE (Quality of Experience)
- Balanceamento qualidade vs latência
- CBR vs VBR

#### 6.3 Sistemas de Videoconferência e VoIP
- Arquitetura de videoconferência
- Codecs para videoconferência
- Sincronização áudio-vídeo (lip-sync)
- Mixing de áudio e vídeo
- SIP (Session Initiation Protocol)
- Sistemas: Zoom, Teams, Webex

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Radiodifusão de TV
- **TV aberta digital**: Transmissão terrestre ISDB-T, DVB-T2
- **TV por assinatura**: Cabo, satélite, IPTV
- **TV móvel**: ISDB-Tmm, DVB-H
- **Rádio digital**: HD Radio, DAB+, DRM
- **Emergência**: Alertas de emergência via TV/rádio

### 3.2 Streaming e OTT
- **Netflix, YouTube, Amazon Prime**: Streaming de vídeo
- **Spotify, Apple Music**: Streaming de áudio
- **Twitch, Kick**: Streaming ao vivo
- **Plataformas corporativas**: Treinamento, comunicação interna
- **Educação**: Aulas online, MOOCs

### 3.3 Comunicações em Tempo Real
- **VoIP**: Telefonia IP (Skype, WhatsApp)
- **Videoconferência**: Zoom, Teams, Google Meet
- **Webinars**: Apresentações online
- **Telemedicina**: Consultas remotas
- **Telepresença**: Robótica e VR

### 3.4 Redes Móveis
- **VoLTE**: Voz sobre LTE
- **VoNR**: Voz sobre 5G NR
- **Video chamadas**: Facetime, WhatsApp Video
- **Live streaming móvel**: Instagram Live, TikTok Live
- **Cloud gaming**: Stadia, Xbox Cloud Gaming

### 3.5 Vigilância e Segurança
- **CFTV IP**: Câmeras de segurança
- **Videoporteiros**: Interfones com vídeo
- **Análise de vídeo**: Detecção de eventos
- **Bodycams**: Câmeras corporais
- **Drones**: Transmissão de vídeo aéreo

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Conceitos de processamento e codificação
- **Demonstrações práticas**: Codecs e compressão
- **Laboratórios**: Processamento de áudio e vídeo
- **Análise de padrões**: MPEG, H.26x, AAC
- **Projetos**: Implementação de sistema de streaming
- **Seminários**: Tecnologias emergentes em multimídia

### 4.2 Recursos Didáticos
- Quadro e projetor multimídia
- Laboratório de processamento de sinais
- Software: MATLAB, FFmpeg, VLC, OBS Studio
- Analisadores de vídeo e áudio
- Codecs e ferramentas de compressão
- Material didático digital
- Vídeos e amostras de áudio para análise

### 4.3 Avaliação

**Instrumentos:**
- Provas teórico-práticas (2 avaliações) - 50%
- Relatórios de laboratório - 25%
- Projeto de compressão/transmissão - 20%
- Participação - 5%

**Critérios:**
- Compreensão dos fundamentos de áudio e vídeo digital
- Conhecimento de técnicas de compressão
- Capacidade de analisar padrões de codificação
- Entendimento de sistemas de TV digital
- Conhecimento de protocolos de streaming
- Qualidade de implementações práticas

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Percepção auditiva. Amostragem e quantização de áudio |
| 2 | Processamento básico de áudio. Formatos PCM |
| 3 | Compressão sem perdas de áudio |
| 4 | Compressão com perdas: MP3, AAC |
| 5 | **1ª Avaliação** |
| 6 | Percepção visual. Amostragem de vídeo |
| 7 | Padrões de vídeo. Representação digital |
| 8 | Redundância em vídeo. Técnicas de compressão |
| 9 | Padrões MPEG e H.26x |
| 10 | **2ª Avaliação** |
| 11 | H.264/AVC e H.265/HEVC em detalhe |
| 12 | Fundamentos de TV digital |
| 13 | Padrões ISDB-T, DVB, ATSC |
| 14 | Protocolos de streaming (HLS, DASH, WebRTC) |
| 15 | Videoconferência e VoIP. Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. RAO, K. R.; HWANG, J. J. **Techniques and Standards for Image, Video, and Audio Coding**. Prentice Hall, 1996.
2. SOLARI, S. J. **Digital Video and Audio Compression**. McGraw-Hill, 1997.
3. RICHARDSON, I. E. G. **The H.264 Advanced Video Compression Standard**. 2. ed. Wiley, 2010.

### Bibliografia Complementar
4. PAINTER, T.; SPANIAS, A. **Perceptual Coding of Digital Audio**. Proceedings of the IEEE, 2000.
5. SAYOOD, K. **Introduction to Data Compression**. 4. ed. Morgan Kaufmann, 2012.
6. WATKINSON, J. **The Art of Digital Audio**. 3. ed. Focal Press, 2001.
7. RAO, K. R.; YIP, P. **The Transform and Data Compression Handbook**. CRC Press, 2000.
8. PURI, A.; CHEN, T. **Multimedia Systems, Standards, and Networks**. Marcel Dekker, 2000.

### Padrões e Documentação
- ITU-T Rec. H.264 | ISO/IEC 14496-10 (MPEG-4 AVC)
- ITU-T Rec. H.265 | ISO/IEC 23008-2 (HEVC)
- ISO/IEC 13818 (MPEG-2)
- ISO/IEC 11172 (MPEG-1)
- ABNT NBR 15601 a 15607 (TV Digital Brasileira)

### Recursos Online
- [FFmpeg](https://ffmpeg.org/) - Framework de processamento multimídia
- [VideoLAN](https://www.videolan.org/) - Projeto VLC
- [x264](https://www.videolan.org/developers/x264.html) - Codec H.264 open source
- [AOMedia](https://aomedia.org/) - AV1 codec
- [DVB Project](https://www.dvb.org/) - Padrões DVB

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Compreender os fundamentos de amostragem, quantização e representação digital de áudio e vídeo

**RA2** - Aplicar técnicas de compressão de áudio com e sem perdas

**RA3** - Analisar e aplicar técnicas de compressão de vídeo intra e inter-quadro

**RA4** - Conhecer e comparar os principais padrões de codificação (MPEG, H.26x, AAC)

**RA5** - Entender os princípios e padrões de TV digital terrestre

**RA6** - Conhecer protocolos de streaming e técnicas de transmissão adaptativa

**RA7** - Compreender sistemas de videoconferência e VoIP

**RA8** - Aplicar conhecimentos em projetos de sistemas de áudio e vídeo

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: Áudio e vídeo são sinais com muita redundância. A compressão explora características tanto dos sinais quanto da percepção humana.

> 🎵 **Psicoacústica**: O ouvido humano não é perfeito. Codecs modernos removem o que você não conseguiria ouvir de qualquer forma.

> 📺 **TV Digital**: O Brasil usa ISDB-T. Entenda bem este padrão, especialmente se for trabalhar com radiodifusão.

> 🎬 **Compressão**: H.264/AVC ainda domina, mas H.265/HEVC e AV1 são o futuro. Acompanhe a evolução dos codecs.

> 🌐 **Streaming**: Adaptive Bitrate é a chave para streaming de qualidade em redes variáveis. Entenda como o Netflix entrega vídeo sem travar.

> 🎤 **VoIP**: A telefonia tradicional está morrendo. VoIP e videoconferência são o presente. Domine os protocolos SIP, RTP, WebRTC.

> 🔗 **Conexões**: Esta disciplina integra conhecimentos de:
> - Processamento Digital de Sinais (fundamentos)
> - Comunicações Digitais (transmissão)
> - Redes (protocolos e streaming)
> - Radiodifusão (TV digital)

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025