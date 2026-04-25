---
type: concept
area: math
subarea: methods
topic: laplace-transform
tags: ["laplace", "transform", "circuits", "control", "differential-equations"]
status: final
---
# Laplace Transform

## Definition
$$\mathcal{L}\{f(t)\} = F(s) = \int_0^\infty f(t)\,e^{-st}\,dt, \quad s \in \mathbb{C}$$

## Common Pairs
| $f(t)$ | $F(s)$ |
|--------|--------|
| $\delta(t)$ | $1$ |
| $u(t)$ | $1/s$ |
| $e^{-at}$ | $1/(s+a)$ |
| $\sin(\omega t)$ | $\omega/(s^2+\omega^2)$ |
| $\cos(\omega t)$ | $s/(s^2+\omega^2)$ |

## Key Properties
- **Differentiation**: $\mathcal{L}\{f'(t)\} = sF(s) - f(0^-)$
- **Integration**: $\mathcal{L}\{\int_0^t f\} = F(s)/s$
- **Convolution**: $\mathcal{L}\{f*g\} = F(s)G(s)$

## Circuit Analysis Application
Replace components with impedances in s-domain:
- Resistor: $R$
- Inductor: $sL$
- Capacitor: $1/(sC)$

## Relations
- [[Circuitos Eletricos II|Electric Circuits II]]
- [[Analise Sinais Sistemas|Signal & System Analysis]]
- [[Equacoes Diferenciais B|Differential Equations B]]
- [[Transformada de Fourier|Fourier Transform]]
