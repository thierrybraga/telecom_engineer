---
type: concept
area: telecom
subarea: communications
topic: modulation
tags: ["modulation", "am", "fm", "qam", "ask", "fsk", "psk", "signals"]
status: final
---
# Modulation

## Definition
Modulation is the process of varying one or more properties of a carrier signal $c(t) = A_c \cos(2\pi f_c t + \phi)$ in accordance with an information-bearing message signal $m(t)$.

## Analog Modulation
| Type | Parameter varied | Expression |
|------|-----------------|------------|
| AM   | Amplitude       | $s(t) = [A_c + m(t)]\cos(2\pi f_c t)$ |
| FM   | Frequency       | $s(t) = A_c \cos\left(2\pi f_c t + 2\pi k_f \int m(\tau)d\tau\right)$ |
| PM   | Phase           | $s(t) = A_c \cos(2\pi f_c t + k_p m(t))$ |

## Digital Modulation
| Type  | Parameter  | Bandwidth Efficiency |
|-------|-----------|---------------------|
| ASK   | Amplitude  | Low |
| FSK   | Frequency  | Low |
| PSK   | Phase      | Medium |
| QAM   | Amplitude+Phase | High |
| OFDM  | Multi-carrier   | Very High |

## Key Metrics
- **Bandwidth efficiency** $\eta_B = R_b / B$ (bits/s/Hz)
- **Power efficiency** related to $E_b/N_0$ for target BER
- **Spectral efficiency** in QAM-16: 4 bits/symbol

## Applications
- 4G/5G uses 256-QAM for peak rates
- DVB-T2 uses OFDM with up to 4096-QAM
- WiFi 802.11ax uses OFDMA + 1024-QAM

## Relations
- [[Comunicacoes Digitais|Digital Communications]]
- [[Principios Comunicacoes|Communication Principles]]
- [[Transformada de Fourier|Fourier Transform]]
- [[Analise Sinais Sistemas|Signal & System Analysis]]
- [[Teoria Informacao Codificacao|Information Theory & Coding]]
