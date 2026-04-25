---
type: concept
area: telecom
subarea: signals
topic: fourier-transform
tags: ["fourier", "transform", "signals", "dsp", "frequency-domain", "math"]
status: final
---
# Fourier Transform

## Definition
The Fourier Transform decomposes a time-domain signal $x(t)$ into its frequency components:

$$X(f) = \int_{-\infty}^{\infty} x(t)\, e^{-j2\pi ft}\, dt$$

The Inverse Fourier Transform recovers $x(t)$:

$$x(t) = \int_{-\infty}^{\infty} X(f)\, e^{j2\pi ft}\, df$$

## Properties
| Property | Time Domain | Frequency Domain |
|---|---|---|
| Linearity | $ax(t)+by(t)$ | $aX(f)+bY(f)$ |
| Time shift | $x(t-t_0)$ | $X(f)e^{-j2\pi ft_0}$ |
| Convolution | $x(t)*h(t)$ | $X(f)\cdot H(f)$ |
| Parseval | $\int|x(t)|^2dt$ | $\int|X(f)|^2df$ |

## Discrete Version (DFT / FFT)
$$X[k] = \sum_{n=0}^{N-1} x[n]\, e^{-j2\pi kn/N}$$

The FFT algorithm computes DFT in $O(N \log N)$ instead of $O(N^2)$.

## Applications
- Spectrum analysis of communication signals
- Filter design (frequency-selective)
- Modulation and demodulation
- Image and audio compression (JPEG, MP3)
- Channel estimation in OFDM

## Relations
- [[Analise Sinais Sistemas|Signal & System Analysis]]
- [[Processamento Digital Sinais|Digital Signal Processing]]
- [[Metodos Matematicos|Mathematical Methods]]
- [[Modulacao|Modulation]]
- [[Transformada de Laplace|Laplace Transform]]
