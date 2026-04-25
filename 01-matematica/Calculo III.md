---
tags: [matemática, cálculo, funções vetoriais, cálculo vetorial, demonstrações]
semestre: 3
area: Matemática
creditos: 6
dificuldade: alta
importancia: critica
status: completo
links: [Calculo_II, Equacoes Diferenciais A, Metodos Matematicos]
aliases: [Calculo_III]
keywords: [matemática, cálculo, funções vetoriais, cálculo vetorial, demonstrações]
---

# Cálculo Diferencial e Integral III

## 1. Ementa Expandida
Estudo rigoroso de funções vetoriais, cálculo diferencial e integral de funções de várias variáveis, integrais de linha e de superfície. Demonstrações formais dos teoremas de Green, Stokes e Gauss com aplicações em eletromagnetismo e engenharia.

---

## 2. Blocos Teóricos

### 2.1 Funções Vetoriais

#### 2.1.1 Definição e Propriedades

**Definição:** Uma **função vetorial** de uma variável real é:
$$\mathbf{r}(t) = (f(t), g(t), h(t)) = f(t)\mathbf{i} + g(t)\mathbf{j} + h(t)\mathbf{k}$$

onde $f, g, h: I \subseteq \mathbb{R} \to \mathbb{R}$ são funções escalares.

---

#### 2.1.2 Limite e Continuidade

**Definição:**
$$\lim_{t \to a} \mathbf{r}(t) = \mathbf{L} \Leftrightarrow \lim_{t \to a} |\mathbf{r}(t) - \mathbf{L}| = 0$$

**Teorema 2.1.2.1:** $\lim_{t \to a} \mathbf{r}(t) = (L_1, L_2, L_3) \Leftrightarrow \lim_{t \to a} f(t) = L_1, \lim_{t \to a} g(t) = L_2, \lim_{t \to a} h(t) = L_3$

**Demonstração:**
$(\Rightarrow)$ Se $\mathbf{r}(t) \to \mathbf{L}$, então para cada componente:
$$|f(t) - L_1| \leq |\mathbf{r}(t) - \mathbf{L}| \to 0$$

$(\Leftarrow)$ Se cada componente converge:
$$|\mathbf{r}(t) - \mathbf{L}| = \sqrt{(f-L_1)^2 + (g-L_2)^2 + (h-L_3)^2} \to 0 \quad \blacksquare$$

---

#### 2.1.3 Derivada de Função Vetorial

**Definição:**
$$\mathbf{r}'(t) = \lim_{h \to 0} \frac{\mathbf{r}(t+h) - \mathbf{r}(t)}{h} = (f'(t), g'(t), h'(t))$$

**Teorema 2.1.3.1 (Propriedades):**
- $(\mathbf{u} + \mathbf{v})' = \mathbf{u}' + \mathbf{v}'$
- $(c\mathbf{u})' = c\mathbf{u}'$
- $(\phi\mathbf{u})' = \phi'\mathbf{u} + \phi\mathbf{u}'$
- $(\mathbf{u} \cdot \mathbf{v})' = \mathbf{u}' \cdot \mathbf{v} + \mathbf{u} \cdot \mathbf{v}'$
- $(\mathbf{u} \times \mathbf{v})' = \mathbf{u}' \times \mathbf{v} + \mathbf{u} \times \mathbf{v}'$

**Demonstração do produto escalar:**
$$\frac{d}{dt}(\mathbf{u} \cdot \mathbf{v}) = \frac{d}{dt}\sum u_i v_i = \sum(u_i' v_i + u_i v_i') = \mathbf{u}' \cdot \mathbf{v} + \mathbf{u} \cdot \mathbf{v}' \quad \blacksquare$$

---

#### 2.1.4 Comprimento de Arco

**Definição:** O comprimento da curva $\mathbf{r}(t)$ de $t=a$ a $t=b$ é:
$$L = \int_a^b |\mathbf{r}'(t)|\,dt = \int_a^b \sqrt{(f')^2 + (g')^2 + (h')^2}\,dt$$

**Teorema 2.1.4.1:** O comprimento é independente da parametrização.

**Demonstração:**
Se $\mathbf{r}_1(u) = \mathbf{r}(t(u))$ com $\frac{dt}{du} > 0$:
$$\int_c^d |\mathbf{r}_1'(u)|du = \int_c^d \left|\frac{d\mathbf{r}}{dt}\frac{dt}{du}\right|du = \int_a^b |\mathbf{r}'(t)|dt \quad \blacksquare$$

---

### 2.2 Funções de Várias Variáveis

#### 2.2.1 Limite e Continuidade em $\mathbb{R}^n$

**Definição:** Seja $f: D \subseteq \mathbb{R}^n \to \mathbb{R}$. Então:
$$\lim_{\mathbf{x} \to \mathbf{a}} f(\mathbf{x}) = L$$

se:
$$\forall \epsilon > 0, \exists \delta > 0; 0 < |\mathbf{x} - \mathbf{a}| < \delta \Rightarrow |f(\mathbf{x}) - L| < \epsilon$$

**Teorema 2.2.1.1:** Se $\lim_{(x,y) \to (a,b)} f(x,y) = L$ existe, então o limite ao longo de qualquer curva contínua tendendo a $(a,b)$ também é $L$.

**Demonstração:** Segue da definição, pois a condição deve valer para todos os pontos na bola, incluindo aqueles em qualquer curva. $\blacksquare$

**Contra-recíproca útil:** Se limites ao longo de caminhos diferentes são distintos, o limite não existe.

---

#### 2.2.2 Derivadas Parciais

**Definição:** A derivada parcial de $f$ em relação a $x_i$ em $\mathbf{a}$ é:
$$\frac{\partial f}{\partial x_i}(\mathbf{a}) = \lim_{h \to 0} \frac{f(\mathbf{a} + h\mathbf{e}_i) - f(\mathbf{a})}{h}$$

onde $\mathbf{e}_i$ é o $i$-ésimo vetor canônico.

**Teorema 2.2.2.1 (Regra da Cadeia - Caso Simples):**
Se $z = f(x,y)$ com $x = x(t), y = y(t)$, então:
$$\frac{dz}{dt} = \frac{\partial f}{\partial x}\frac{dx}{dt} + \frac{\partial f}{\partial y}\frac{dy}{dt}$$

**Demonstração:**
$$\frac{\Delta z}{\Delta t} = \frac{f(x(t+\Delta t), y(t+\Delta t)) - f(x(t), y(t))}{\Delta t}$$

Adicionando e subtraindo $f(x(t), y(t+\Delta t))$:
$$= \frac{f(x(t+\Delta t), y(t+\Delta t)) - f(x(t), y(t+\Delta t))}{x(t+\Delta t)-x(t)}\cdot\frac{x(t+\Delta t)-x(t)}{\Delta t} + \frac{f(x(t), y(t+\Delta t)) - f(x(t), y(t))}{y(t+\Delta t)-y(t)}\cdot\frac{y(t+\Delta t)-y(t)}{\Delta t}$$

Tomando $\Delta t \to 0$:
$$\frac{dz}{dt} = \frac{\partial f}{\partial x}\frac{dx}{dt} + \frac{\partial f}{\partial y}\frac{dy}{dt} \quad \blacksquare$$

---

#### 2.2.3 Diferenciabilidade

**Definição:** $f$ é **diferenciável** em $\mathbf{a}$ se existe vetor $\nabla f(\mathbf{a})$ tal que:
$$f(\mathbf{a} + \mathbf{h}) = f(\mathbf{a}) + \nabla f(\mathbf{a}) \cdot \mathbf{h} + o(|\mathbf{h}|)$$

ou equivalentemente:
$$\lim_{\mathbf{h} \to \mathbf{0}} \frac{f(\mathbf{a}+\mathbf{h}) - f(\mathbf{a}) - \nabla f(\mathbf{a})\cdot\mathbf{h}}{|\mathbf{h}|} = 0$$

**Teorema 2.2.3.1:** Se as derivadas parciais $\frac{\partial f}{\partial x_i}$ existem e são contínuas em uma vizinhança de $\mathbf{a}$, então $f$ é diferenciável em $\mathbf{a}$.

**Demonstração (para $n=2$):**
$$f(a+h, b+k) - f(a,b) = [f(a+h, b+k) - f(a, b+k)] + [f(a, b+k) - f(a,b)]$$

Pelo TVM em cada variável:
$$= \frac{\partial f}{\partial x}(c_1, b+k)h + \frac{\partial f}{\partial y}(a, c_2)k$$

para $c_1 \in (a, a+h), c_2 \in (b, b+k)$.

Como as derivadas parciais são contínuas:
$$= \frac{\partial f}{\partial x}(a,b)h + \frac{\partial f}{\partial y}(a,b)k + \epsilon_1 h + \epsilon_2 k$$

onde $\epsilon_1, \epsilon_2 \to 0$ quando $(h,k) \to (0,0)$.

Logo:
$$\frac{|f(\mathbf{a}+\mathbf{h}) - f(\mathbf{a}) - \nabla f \cdot \mathbf{h}|}{|\mathbf{h}|} \leq |\epsilon_1| + |\epsilon_2| \to 0 \quad \blacksquare$$

---

#### 2.2.4 Gradiente e Derivada Direcional

**Definição:** O **gradiente** de $f$ é:
$$\nabla f = \left(\frac{\partial f}{\partial x_1}, \frac{\partial f}{\partial x_2}, \ldots, \frac{\partial f}{\partial x_n}\right)$$

**Definição:** A **derivada direcional** de $f$ em $\mathbf{a}$ na direção do vetor unitário $\mathbf{u}$ é:
$$D_{\mathbf{u}}f(\mathbf{a}) = \lim_{h \to 0} \frac{f(\mathbf{a} + h\mathbf{u}) - f(\mathbf{a})}{h}$$

**Teorema 2.2.4.1:** Se $f$ é diferenciável em $\mathbf{a}$, então:
$$D_{\mathbf{u}}f(\mathbf{a}) = \nabla f(\mathbf{a}) \cdot \mathbf{u}$$

**Demonstração:**
Pela diferenciabilidade:
$$f(\mathbf{a} + h\mathbf{u}) = f(\mathbf{a}) + \nabla f(\mathbf{a}) \cdot (h\mathbf{u}) + o(|h\mathbf{u}|)$$

$$= f(\mathbf{a}) + h\nabla f(\mathbf{a}) \cdot \mathbf{u} + o(h)$$

Logo:
$$\frac{f(\mathbf{a} + h\mathbf{u}) - f(\mathbf{a})}{h} = \nabla f(\mathbf{a}) \cdot \mathbf{u} + \frac{o(h)}{h} \to \nabla f(\mathbf{a}) \cdot \mathbf{u} \quad \blacksquare$$

**Teorema 2.2.4.2:** O gradiente aponta na direção de maior crescimento de $f$, e $|\nabla f|$ é a taxa máxima de crescimento.

**Demonstração:**
Pela desigualdade de Cauchy-Schwarz:
$$|D_{\mathbf{u}}f| = |\nabla f \cdot \mathbf{u}| \leq |\nabla f||\mathbf{u}| = |\nabla f|$$

Igualdade ocorre quando $\mathbf{u}$ é paralelo a $\nabla f$. $\blacksquare$

---

### 2.3 Integrais Múltiplas

#### 2.3.1 Integral Dupla - Definição

**Definição:** Para $f: R = [a,b] \times [c,d] \to \mathbb{R}$ limitada, a integral dupla é:
$$\iint_R f(x,y)\,dA = \lim_{\|P\| \to 0} \sum_{i=1}^m\sum_{j=1}^n f(x_i^*, y_j^*)\Delta A_{ij}$$

**Teorema 2.3.1.1 (Fubini):** Se $f$ é contínua em $R = [a,b] \times [c,d]$, então:
$$\iint_R f(x,y)\,dA = \int_a^b\left(\int_c^d f(x,y)\,dy\right)dx = \int_c^d\left(\int_a^b f(x,y)\,dx\right)dy$$

**Demonstração (Esboço):**
As somas de Riemann podem ser reorganizadas:
$$\sum_{i,j} f(x_i^*, y_j^*)\Delta x_i \Delta y_j = \sum_i \Delta x_i \left(\sum_j f(x_i^*, y_j^*)\Delta y_j\right)$$

Quando $\|P\| \to 0$, a soma interna converge para $\int_c^d f(x_i^*, y)dy$, e a soma externa converge para $\int_a^b\left(\int_c^d f(x,y)dy\right)dx$. $\blacksquare$

---

#### 2.3.2 Mudança de Variáveis

**Teorema 2.3.2.1 (Fórmula de Mudança de Variáveis):**
Seja $T: D^* \to D$ uma transformação bijetora com derivadas parciais contínuas e Jacobiano $J(u,v) = \det\begin{pmatrix} \frac{\partial x}{\partial u} & \frac{\partial x}{\partial v} \\ \frac{\partial y}{\partial u} & \frac{\partial y}{\partial v} \end{pmatrix} \neq 0$. Então:

$$\iint_D f(x,y)\,dx\,dy = \iint_{D^*} f(x(u,v), y(u,v))|J(u,v)|\,du\,dv$$

**Demonstração (Esboço):**
A transformação $T$ mapea um retângulo infinitesimal em $D^*$ de área $du\,dv$ em um paralelogramo em $D$ de área $|J|du\,dv$.

As arestas do paralelogramo são aproximadamente:
$$\frac{\partial \mathbf{r}}{\partial u}du \quad \text{e} \quad \frac{\partial \mathbf{r}}{\partial v}dv$$

cuja área é:
$$\left|\frac{\partial \mathbf{r}}{\partial u} \times \frac{\partial \mathbf{r}}{\partial v}\right|du\,dv = |J|du\,dv$$

Integrando sobre a soma de Riemann transformada obtemos o resultado. $\blacksquare$

---

#### 2.3.3 Coordenadas Polares

**Teorema 2.3.3.1:** Para $x = r\cos\theta, y = r\sin\theta$:
$$\iint_D f(x,y)\,dx\,dy = \iint_{D^*} f(r\cos\theta, r\sin\theta)\,r\,dr\,d\theta$$

**Demonstração:**
O Jacobiano é:
$$J = \det\begin{pmatrix} \cos\theta & -r\sin\theta \\ \sin\theta & r\cos\theta \end{pmatrix} = r\cos^2\theta + r\sin^2\theta = r$$

Logo $|J| = r$. $\blacksquare$

---

### 2.4 Campos Vetoriais

#### 2.4.1 Definições

**Definição:** Um **campo vetorial** em $\mathbb{R}^n$ é uma função $\mathbf{F}: D \subseteq \mathbb{R}^n \to \mathbb{R}^n$.

$$\mathbf{F}(x,y,z) = (P(x,y,z), Q(x,y,z), R(x,y,z))$$

---

#### 2.4.2 Divergência e Rotacional

**Definição:** O **divergência** de $\mathbf{F} = (P, Q, R)$ é:
$$\nabla \cdot \mathbf{F} = \frac{\partial P}{\partial x} + \frac{\partial Q}{\partial y} + \frac{\partial R}{\partial z}$$

**Definição:** O **rotacional** de $\mathbf{F}$ é:
$$\nabla \times \mathbf{F} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ \frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\ P & Q & R \end{vmatrix}$$

$$= \left(\frac{\partial R}{\partial y} - \frac{\partial Q}{\partial z}, \frac{\partial P}{\partial z} - \frac{\partial R}{\partial x}, \frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y}\right)$$

---

#### 2.4.3 Campos Conservativos

**Definição:** Um campo $\mathbf{F}$ é **conservativo** se existe $\phi$ (potencial) tal que $\mathbf{F} = \nabla \phi$.

**Teorema 2.4.3.1:** Se $\mathbf{F}$ é de classe $C^1$ e conservativo em uma região simplesmente conexa, então $\nabla \times \mathbf{F} = \mathbf{0}$.

**Demonstração:**
Se $\mathbf{F} = \nabla\phi = (\phi_x, \phi_y, \phi_z)$, então:
$$(\nabla \times \mathbf{F})_x = \frac{\partial \phi_z}{\partial y} - \frac{\partial \phi_y}{\partial z} = \phi_{zy} - \phi_{yz} = 0$$

pela igualdade das derivadas parciais mistas (Teorema de Schwarz). $\blacksquare$

**Teorema 2.4.3.2 (Recíproca):** Se $\nabla \times \mathbf{F} = \mathbf{0}$ em uma região simplesmente conexa, então $\mathbf{F}$ é conservativo.

**Demonstração:** Segue do Teorema de Stokes. $\blacksquare$

---

### 2.5 Integrais de Linha

#### 2.5.1 Definição

**Definição:** A integral de linha de $\mathbf{F}$ ao longo de $C$ parametrizada por $\mathbf{r}(t), t \in [a,b]$ é:
$$\int_C \mathbf{F} \cdot d\mathbf{r} = \int_a^b \mathbf{F}(\mathbf{r}(t)) \cdot \mathbf{r}'(t)\,dt$$

**Teorema 2.5.1.1:** A integral de linha é independente da parametrização (preservando orientação).

**Demonstração:**
Se $\mathbf{r}_1(u) = \mathbf{r}(t(u))$ com $\frac{dt}{du} > 0$:
$$\int_c^d \mathbf{F}(\mathbf{r}_1(u)) \cdot \mathbf{r}_1'(u)\,du = \int_c^d \mathbf{F}(\mathbf{r}(t(u))) \cdot \frac{d\mathbf{r}}{dt}\frac{dt}{du}\,du$$
$$= \int_a^b \mathbf{F}(\mathbf{r}(t)) \cdot \mathbf{r}'(t)\,dt \quad \blacksquare$$

---

#### 2.5.2 Teorema Fundamental para Integrais de Linha

**Teorema 2.5.2.1:** Se $\mathbf{F} = \nabla\phi$ é conservativo, então:
$$\int_C \mathbf{F} \cdot d\mathbf{r} = \phi(B) - \phi(A)$$

onde $A$ e $B$ são os extremos de $C$.

**Demonstração:**
$$\int_C \nabla\phi \cdot d\mathbf{r} = \int_a^b \nabla\phi(\mathbf{r}(t)) \cdot \mathbf{r}'(t)\,dt = \int_a^b \frac{d}{dt}\phi(\mathbf{r}(t))\,dt$$
$$= \phi(\mathbf{r}(b)) - \phi(\mathbf{r}(a)) = \phi(B) - \phi(A) \quad \blacksquare$$

**Corolário:** Para campos conservativos, a integral de linha depende apenas dos extremos, não do caminho.

---

### 2.6 Teorema de Green

#### 2.6.1 Enunciado

**Teorema (Green):** Seja $D$ uma região plana simplesmente conexa com fronteira $C$ orientada positivamente (anti-horária). Se $P$ e $Q$ têm derivadas parciais contínuas em uma região contendo $D$, então:

$$\oint_C P\,dx + Q\,dy = \iint_D \left(\frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y}\right)dA$$

---

#### 2.6.2 Demonstração

**Demonstração (para região tipo I e II):**

Uma região **tipo I** é da forma:
$$D = \{(x,y): a \leq x \leq b, g_1(x) \leq y \leq g_2(x)\}$$

Vamos provar que:
$$\oint_C P\,dx = -\iint_D \frac{\partial P}{\partial y}\,dA$$

A fronteira $C$ consiste em:
- $C_1$: curva inferior $y = g_1(x)$ de $x=a$ a $x=b$
- $C_2$: segmento vertical em $x=b$ de $y=g_1(b)$ a $y=g_2(b)$
- $C_3$: curva superior $y = g_2(x)$ de $x=b$ a $x=a$
- $C_4$: segmento vertical em $x=a$ de $y=g_2(a)$ a $y=g_1(a)$

Em $C_2$ e $C_4$, $dx = 0$, logo:
$$\oint_C P\,dx = \int_{C_1} P\,dx + \int_{C_3} P\,dx$$

$$= \int_a^b P(x, g_1(x))\,dx + \int_b^a P(x, g_2(x))\,dx$$
$$= \int_a^b [P(x, g_1(x)) - P(x, g_2(x))]\,dx$$

Por outro lado:
$$\iint_D \frac{\partial P}{\partial y}\,dA = \int_a^b\int_{g_1(x)}^{g_2(x)} \frac{\partial P}{\partial y}\,dy\,dx$$
$$= \int_a^b [P(x, g_2(x)) - P(x, g_1(x))]\,dx$$

Logo:
$$\oint_C P\,dx = -\iint_D \frac{\partial P}{\partial y}\,dA$$

Analogamente, para região **tipo II**:
$$\oint_C Q\,dy = \iint_D \frac{\partial Q}{\partial x}\,dA$$

Somando ambas as igualdades:
$$\oint_C P\,dx + Q\,dy = \iint_D \left(\frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y}\right)dA \quad \blacksquare$$

---

### 2.7 Teorema de Stokes

#### 2.7.1 Enunciado

**Teorema (Stokes):** Seja $S$ uma superfície orientada, suave por partes, com fronteira $C$ fechada, simples, orientada positivamente. Seja $\mathbf{F}$ um campo vetorial com derivadas parciais contínuas em uma região contendo $S$. Então:

$$\oint_C \mathbf{F} \cdot d\mathbf{r} = \iint_S (\nabla \times \mathbf{F}) \cdot d\mathbf{S} = \iint_S (\nabla \times \mathbf{F}) \cdot \mathbf{n}\,dS$$

onde $\mathbf{n}$ é o vetor normal unitário orientado de acordo com a regra da mão direita.

---

#### 2.7.2 Demonstração (Esboço para Gráfico)

Considere $S$ dada por $z = g(x,y)$ sobre $D \subseteq \mathbb{R}^2$.

A fronteira $C$ de $S$ corresponde à curva $C^*$ em $D$ (projeção).

Parametrizando $C^*$ por $(x(t), y(t))$, temos $C$ parametrizada por $\mathbf{r}(t) = (x(t), y(t), g(x(t),y(t)))$.

Para $\mathbf{F} = (P, Q, R)$:
$$\oint_C \mathbf{F} \cdot d\mathbf{r} = \oint_{C^*} \left(P + R\frac{\partial g}{\partial x}\right)dx + \left(Q + R\frac{\partial g}{\partial y}\right)dy$$

Aplicando Green em $D$:
$$= \iint_D \left[\frac{\partial}{\partial x}\left(Q + R\frac{\partial g}{\partial y}\right) - \frac{\partial}{\partial y}\left(P + R\frac{\partial g}{\partial x}\right)\right]dA$$

Expandindo e simplificando usando a regra da cadeia, obtém-se:
$$= \iint_D \left[\left(\frac{\partial R}{\partial y} - \frac{\partial Q}{\partial z}\right)\left(-\frac{\partial g}{\partial x}\right) + \left(\frac{\partial P}{\partial z} - \frac{\partial R}{\partial x}\right)\left(-\frac{\partial g}{\partial y}\right) + \left(\frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y}\right)\right]dA$$

O vetor normal à superfície $z = g(x,y)$ é proporcional a $\left(-\frac{\partial g}{\partial x}, -\frac{\partial g}{\partial y}, 1\right)$, e:
$$(\nabla \times \mathbf{F}) \cdot \mathbf{n}\,dS = (\nabla \times \mathbf{F}) \cdot \left(-\frac{\partial g}{\partial x}, -\frac{\partial g}{\partial y}, 1\right)dA$$

que coincide com o integrando acima. $\blacksquare$

---

### 2.8 Teorema da Divergência de Gauss

#### 2.8.1 Enunciado

**Teorema (Divergência de Gauss):** Seja $V$ uma região sólida limitada por uma superfície fechada $S$ orientada para fora. Seja $\mathbf{F}$ um campo vetorial com derivadas parciais contínuas em uma região contendo $V$. Então:

$$\iint_S \mathbf{F} \cdot d\mathbf{S} = \iiint_V (\nabla \cdot \mathbf{F})\,dV$$

---

#### 2.8.2 Demonstração (para Região Tipo I)

Uma região **tipo I** em $\mathbb{R}^3$ é:
$$V = \{(x,y,z): (x,y) \in D, u_1(x,y) \leq z \leq u_2(x,y)\}$$

Vamos provar que:
$$\iint_S R\mathbf{k} \cdot d\mathbf{S} = \iiint_V \frac{\partial R}{\partial z}\,dV$$

A fronteira $S$ consiste em:
- $S_1$: superfície inferior $z = u_1(x,y)$ (normal para baixo)
- $S_2$: superfície superior $z = u_2(x,y)$ (normal para cima)
- $S_3$: superfície lateral (vertical, $\mathbf{k} \cdot \mathbf{n} = 0$)

Em $S_3$: $\mathbf{k} \cdot \mathbf{n} = 0$, logo a contribuição é zero.

Em $S_2$: $z = u_2(x,y)$, normal $\mathbf{n}$ apontando para cima:
$$\iint_{S_2} R\mathbf{k} \cdot d\mathbf{S} = \iint_D R(x,y,u_2(x,y))\,dA$$

Em $S_1$: $z = u_1(x,y)$, normal apontando para baixo:
$$\iint_{S_1} R\mathbf{k} \cdot d\mathbf{S} = -\iint_D R(x,y,u_1(x,y))\,dA$$

Logo:
$$\iint_S R\mathbf{k} \cdot d\mathbf{S} = \iint_D [R(x,y,u_2) - R(x,y,u_1)]\,dA$$

Por outro lado:
$$\iiint_V \frac{\partial R}{\partial z}\,dV = \iint_D\int_{u_1}^{u_2} \frac{\partial R}{\partial z}\,dz\,dA = \iint_D [R(x,y,u_2) - R(x,y,u_1)]\,dA$$

Logo:
$$\iint_S R\mathbf{k} \cdot d\mathbf{S} = \iiint_V \frac{\partial R}{\partial z}\,dV$$

Analogamente para as componentes em $x$ e $y$. Somando as três igualdades:
$$\iint_S \mathbf{F} \cdot d\mathbf{S} = \iiint_V (\nabla \cdot \mathbf{F})\,dV \quad \blacksquare$$

---

## 3. Aplicações em Telecom

### 3.1 Eletromagnetismo

As **Equações de Maxwell** em forma diferencial usam divergência e rotacional:

$$\nabla \cdot \mathbf{E} = \frac{\rho}{\epsilon_0} \quad \text{(Lei de Gauss)}$$
$$\nabla \cdot \mathbf{B} = 0 \quad \text{(Lei de Gauss magnética)}$$
$$\nabla \times \mathbf{E} = -\frac{\partial \mathbf{B}}{\partial t} \quad \text{(Lei de Faraday)}$$
$$\nabla \times \mathbf{B} = \mu_0\mathbf{J} + \mu_0\epsilon_0\frac{\partial \mathbf{E}}{\partial t} \quad \text{(Lei de Ampère-Maxwell)}$$

### 3.2 Potenciais Elétricos

O campo elétrico estático é conservativo: $\mathbf{E} = -\nabla\phi$

Aplicando o Teorema de Green/Gauss:
$$\oint_C \mathbf{E} \cdot d\mathbf{r} = 0 \quad \text{(conservativo)}$$

### 3.3 Propagação de Ondas

A equação de onda:
$$\nabla^2 u = \frac{1}{c^2}\frac{\partial^2 u}{\partial t^2}$$

onde $\nabla^2 = \nabla \cdot \nabla = \frac{\partial^2}{\partial x^2} + \frac{\partial^2}{\partial y^2} + \frac{\partial^2}{\partial z^2}$ é o operador Laplaciano.

---

## 4. Prática/Laboratório

1. Demonstrações de convergência em várias variáveis
2. Cálculo de integrais múltiplas com mudança de coordenadas
3. Verificação do Teorema de Green em exemplos concretos
4. Aplicações dos teoremas de Stokes e Gauss
5. Implementação computacional de campos vetoriais

---

## 5. Bibliografia

### Básica
- STEWART, J. **Cálculo**. Vol. 2. 8. ed. Cengage, 2016.
- MARSDEN, J. E.; TROMBA, A. **Cálculo Vetorial**. 6. ed. LTC, 2012.

### Avançada
- APOSTOL, T. M. **Calculus**. Vol. 2. 2. ed. Wiley, 1969.
- SPIEGEL, M. R. **Análise Vetorial**. McGraw-Hill, 1971.

---

## 6. Outputs Esperados

- [ ] Domínio de funções de várias variáveis
- [ ] Cálculo de integrais múltiplas e mudança de coordenadas
- [ ] Compreensão de campos vetoriais, divergência e rotacional
- [ ] Aplicação dos teoremas de Green, Stokes e Gauss
- [ ] Conexão com fundamentos de eletromagnetismo
- [ ] Demonstrações formais dos principais teoremas