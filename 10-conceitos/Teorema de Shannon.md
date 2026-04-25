---
type: concept
area: telecom
subarea: communications
topic: shannon-theorem
tags: ["shannon", "channel-capacity", "information-theory", "entropy", "coding"]
status: final
---
# Shannon's Channel Capacity Theorem

## Definition
The maximum error-free data rate (channel capacity) of a noisy channel:

$$C = B \log_2\left(1 + \frac{S}{N}\right) \quad \text{[bits/s]}$$

Where:
- $C$ = channel capacity (bits/s)
- $B$ = bandwidth (Hz)
- $S/N$ = signal-to-noise ratio (linear)

## Shannon Entropy
$$H(X) = -\sum_{i} p_i \log_2 p_i \quad \text{[bits]}$$

Measures average information content of a source.

## Key Results
- Shannon proved capacity is **achievable** with the right code
- Below capacity: reliable communication is possible
- Above capacity: errors are inevitable regardless of coding
- **Nyquist rate**: $f_s \geq 2B$ for lossless sampling

## Practical Implications
| System | SNR (dB) | B (MHz) | Capacity (Mbps) |
|--------|---------|---------|----------------|
| 5G mmWave | 30 | 400 | ~4000 |
| Fiber (DWDM) | 30 | 4000 | ~40000 |
| WiFi 6 | 25 | 80 | ~800 |

## Relations
- [[Teoria Informacao Codificacao|Information Theory & Coding]]
- [[Comunicacoes Digitais|Digital Communications]]
- [[Modulacao|Modulation]]
- [[Estatistica Probabilidade|Statistics & Probability]]
