---
tags: [computação, computação gráfica, projetos, engenharia, visualização]
semestre: 8
area: Computação
creditos: 4
dificuldade: media
importancia: media
código: CMP002
carga_horaria: 60h (4 créditos)
status: completo
pré_requisitos: [Programacao Orientada Objetos, Algoritmos II]
links: [Sistemas Digitais, Processamento Audio Video, TCC I]
aliases: [Projeto_Computacao_Grafica]
keywords: [computação, computação gráfica, projetos, engenharia, visualização]
resumo: "Estudo dos fundamentos de computação gráfica: sistemas gráficos, transformações geométricas, modelagem 2D e 3D, iluminação, texturização, visualização de dados e projeto assistido por computador."
---

# Projeto e Computação Gráfica

## 1. Ementa Oficial

Estudo dos fundamentos de computação gráfica: sistemas gráficos, transformações geométricas, modelagem 2D e 3D, iluminação, texturização, visualização de dados e projeto assistido por computador. Aplicações em engenharia e desenvolvimento de projetos gráficos.

### Objetivos da Disciplina

**Objetivo Geral:**
Capacitar o estudante a utilizar técnicas de computação gráfica para visualização e desenvolvimento de projetos em engenharia, compreendendo os fundamentos matemáticos e algorítmicos dos sistemas gráficos.

**Objetivos Específicos:**
- Compreender os fundamentos de sistemas gráficos e pipelines de renderização
- Aplicar transformações geométricas 2D e 3D
- Desenvolver modelagem geométrica de objetos
- Entender algoritmos de rasterização e iluminação
- Aplicar técnicas de texturização e mapeamento
- Visualizar dados e informações graficamente
- Utilizar ferramentas de projeto assistido por computador (CAD)
- Desenvolver projetos de visualização técnica

---

## 2. Conteúdo Programático

### Unidade 1: Fundamentos de Computação Gráfica (10h)

#### 1.1 Introdução à Computação Gráfica
- Histórico e evolução
- Aplicações em engenharia e ciência
- Hardware gráfico (GPUs)
- APIs gráficas (OpenGL, DirectX, Vulkan, WebGL)
- Pipeline de renderização
- Sistemas de coordenadas

#### 1.2 Dispositivos e Sistemas Gráficos
- Dispositivos de entrada (mouse, tablet, 3D mouse)
- Dispositivos de saída (monitores, projetores, VR/AR)
- Resolução e profundidade de cor
- Taxa de atualização e sincronização
- Framebuffers e buffers de profundidade
- Double buffering

#### 1.3 Primitivas Gráficas
- Pontos, linhas e polígonos
- Representação vetorial vs raster
- Algoritmos de rasterização:
  - Linha: DDA, Bresenham
  - Círculo: algoritmo do ponto médio
- Preenchimento de polígonos
- Antialiasing

---

### Unidade 2: Transformações Geométricas (10h)

#### 2.1 Transformações 2D
- Translação
- Escala
- Rotação
- Cisalhamento (shear)
- Reflexão
- Composição de transformações
- Matrizes de transformação homogêneas

#### 2.2 Transformações 3D
- Coordenadas 3D e sistemas de referência
- Translação, escala e rotação em 3D
- Rotações em torno de eixos arbitrários
- Quaternions para rotação
- Composição de transformações 3D
- Transformações entre sistemas de coordenadas

#### 2.3 Projeções e Viewing
- Projeção ortográfica
- Projeção perspectiva
- Volume de visualização (view frustum)
- Pipeline de visualização
- Matriz model-view-projection (MVP)
- Câmera virtual e parâmetros

---

### Unidade 3: Modelagem Geométrica (10h)

#### 3.1 Modelagem 2D
- Representação de curvas:
  - Splines
  - Curvas de Bézier
  - Curvas B-spline
  - Curvas NURBS
- Modelagem por varredura (sweeping)
- Operações booleanas
- Modelagem construtiva sólida (CSG)

#### 3.2 Modelagem 3D
- Representação de superfícies:
  - Malhas poligonais (meshes)
  - Superfícies paramétricas
  - Superfícies de subdivisão
- Modelagem sólida
- Estruturas de dados para modelos 3D
- Formatos de arquivo (OBJ, STL, FBX, glTF)

#### 3.3 Técnicas de Modelagem
- Modelagem poligonal
- Modelagem por subdivisão
- Sculpting digital
- Modelagem paramétrica
- Modelagem procedural
- Scanning 3D e reconstrução

---

### Unidade 4: Iluminação e Renderização (10h)

#### 4.1 Fundamentos de Cor e Luz
- Modelos de cor (RGB, CMYK, HSV, CIE)
- Luz e materiais
- Modelos de reflexão:
  - Difusa (Lambert)
  - Especular (Phong, Blinn-Phong)
  - Ambiente
- Modelo de iluminação local

#### 4.2 Técnicas de Renderização
- Flat shading
- Gouraud shading
- Phong shading
- Mapeamento de sombras (shadow mapping)
- Técnicas de ray tracing básico
- Global illumination (introdução)

#### 4.3 Texturização
- Mapeamento de texturas
- Coordenadas de textura (UV mapping)
- Filtros de textura (bilinear, trilinear, anisotrópico)
- Mipmapping
- Texturas procedurais
- Bump mapping e normal mapping
- Environment mapping

---

### Unidade 5: Visualização e Interação (10h)

#### 5.1 Visualização Científica
- Visualização de dados escalares
- Visualização de dados vetoriais
- Isosuperfícies e volume rendering
- Visualização de campos
- Técnicas de mapeamento de cor
- Visualização de dados temporais

#### 5.2 Interação e Interfaces
- Técnicas de interação (seleção, manipulação, navegação)
- Feedback visual e háptico
- Interfaces imersivas (VR/AR)
- Técnicas de realidade aumentada
- Interação gestual e por voz

#### 5.3 Animação
- Princípios de animação
- Interpolação de keyframes
- Animação de personagens
- Animação procedural
- Animação física (física de partículas, corpos rígidos)
- Motion capture

---

### Unidade 6: Projeto Assistido por Computador (10h)

#### 6.1 Fundamentos de CAD
- Conceitos de CAD/CAM/CAE
- Histórico e evolução
- Tipos de sistemas CAD
- Parâmetros e restrições
- Features e modelagem paramétrica
- Árvore de construção

#### 6.2 Ferramentas CAD
- Sistemas CAD 2D (AutoCAD, DraftSight)
- Sistemas CAD 3D (SolidWorks, Fusion 360, Inventor)
- CAD para engenharia elétrica (Eagle, KiCad)
- Simulação e análise (FEA, CFD básico)
- Documentação técnica e desenhos

#### 6.3 Aplicações em Engenharia
- Projeto de componentes mecânicos
- Layout de circuitos impressos (PCB)
- Projeto de instalações
- Prototipagem rápida (3D printing)
- Engenharia reversa
- Digital twin (gêmeo digital)

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Visualização de Redes
- **Topologias de rede**: Representação gráfica de infraestrutura
- **Mapas de calor**: Cobertura de sinal Wi-Fi/celular
- **Diagramas de fluxo**: Tráfego de dados
- **Dashboards**: Monitoramento de redes
- **Visualização 3D**: Torres e antenas

### 3.2 Simulação e Análise
- **Propagação de ondas**: Visualização de campo eletromagnético
- **Radiação de antenas**: Padrões de radiação 3D
- **Interferência**: Mapas de interferência
- **Ray tracing**: Simulação de propagação indoor
- **Fading**: Visualização de desvanecimento multipath

### 3.3 Projeto de Componentes
- **Antenas**: Modelagem 3D para fabricação
- **Caixas e gabinetes**: Design mecânico
- **PCBs**: Layout de placas de circuito
- **Conectores**: Modelagem de interfaces
- **Prototipagem**: Impressão 3D de componentes

### 3.4 Realidade Virtual e Aumentada
- **Treinamento**: Manutenção de equipamentos em VR
- **Planejamento**: Visualização de instalações em AR
- **Documentação**: Manuais interativos com AR
- **Manutenção remota**: Assistência técnica via AR
- **Showrooms**: Apresentação de produtos em VR

### 3.5 Processamento de Imagens
- **Análise de imagens**: Processamento de vídeo de vigilância
- **Reconstrução 3D**: Fotogrametria para mapeamento
- **Visão computacional**: Detecção de objetos em redes
- **Realidade virtual**: Criação de ambientes imersivos

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Conceitos matemáticos e algorítmicos
- **Demonstrações**: Visualização de algoritmos e técnicas
- **Laboratórios práticos**: Implementação e uso de ferramentas
- **Projetos**: Desenvolvimento de aplicações gráficas
- **Workshops**: Uso de software CAD específico
- **Seminários**: Tecnologias emergentes em gráficos

### 4.2 Recursos Didáticos
- Laboratório de computação com GPUs
- Software: OpenGL, Blender, Unity, AutoCAD, SolidWorks
- Kits de realidade virtual (VR headsets)
- Impressora 3D para prototipagem
- Tablets gráficos
- Material didático digital
- Bibliotecas gráficas (Three.js, Processing)

### 4.3 Avaliação

**Instrumentos:**
- Provas teóricas (2 avaliações) - 40%
- Projetos práticos - 40%
- Exercícios de laboratório - 15%
- Participação - 5%

**Critérios:**
- Compreensão dos fundamentos de computação gráfica
- Capacidade de aplicar transformações geométricas
- Conhecimento de técnicas de modelagem
- Entendimento de iluminação e renderização
- Proficiência em ferramentas CAD
- Qualidade dos projetos desenvolvidos

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Introdução à computação gráfica. Sistemas gráficos |
| 2 | Dispositivos e primitivas gráficas |
| 3 | Algoritmos de rasterização |
| 4 | Transformações geométricas 2D |
| 5 | **1ª Avaliação** |
| 6 | Transformações 3D e projeções |
| 7 | Pipeline de visualização |
| 8 | Modelagem de curvas e superfícies |
| 9 | Modelagem 3D e malhas poligonais |
| 10 | **2ª Avaliação** |
| 11 | Iluminação e sombreamento |
| 12 | Texturização e mapeamento |
| 13 | Visualização científica |
| 14 | Animação e interação |
| 15 | CAD e aplicações em engenharia. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. HEARN, D.; BAKER, M. P.; CARITHERS, W. R. **Computer Graphics with OpenGL**. 4. ed. Pearson, 2010.
2. FOLEY, J. D. et al. **Computer Graphics: Principles and Practice**. 3. ed. Addison-Wesley, 2013.
3. SHIRLEY, P.; ASHIKHMIN, M. **Fundamentals of Computer Graphics**. 4. ed. AK Peters, 2016.

### Bibliografia Complementar
4. HUGHES, J. F. et al. **Computer Graphics: Principles and Practice**. 3. ed. Addison-Wesley, 2013.
5. MARSCHNER, S.; SHIRLEY, P. **Fundamentals of Computer Graphics**. 4. ed. CRC Press, 2016.
6. REAL TIME RENDERING, T. et al. **Real-Time Rendering**. 4. ed. AK Peters/CRC Press, 2018.
7. WATT, A. **3D Computer Graphics**. 3. ed. Addison-Wesley, 1999.
8. MORTENSON, M. E. **Geometric Modeling**. 3. ed. Industrial Press, 2006.

### Recursos Online
- [OpenGL Official Documentation](https://www.opengl.org/documentation/) - Documentação OpenGL
- [Khronos Group](https://www.khronos.org/) - Padrões gráficos (OpenGL, Vulkan, WebGL)
- [Blender](https://www.blender.org/) - Software de modelagem 3D open-source
- [Three.js](https://threejs.org/) - Biblioteca JavaScript 3D
- [Unity Learn](https://learn.unity.com/) - Tutoriais Unity
- [AutoCAD Learning](https://www.autodesk.com/learning) - Recursos AutoCAD

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Compreender os fundamentos de sistemas gráficos e pipelines de renderização

**RA2** - Aplicar transformações geométricas 2D e 3D em objetos e cenas

**RA3** - Desenvolver modelagem geométrica de objetos usando técnicas apropriadas

**RA4** - Implementar e compreender algoritmos de iluminação e renderização

**RA5** - Aplicar técnicas de texturização e mapeamento em modelos 3D

**RA6** - Visualizar dados científicos e técnicos de forma eficaz

**RA7** - Utilizar ferramentas CAD para desenvolvimento de projetos de engenharia

**RA8** - Desenvolver projetos de visualização técnica aplicados a telecomunicações

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: Computação gráfica envolve matemática (álgebra linear, geometria) e programação. Revise esses fundamentos!

> 🎨 **Pipeline**: Entenda o pipeline de renderização. É o "caminho" que os dados percorrem desde o modelo 3D até a imagem na tela.

> 📐 **Transformações**: Matrizes são a linguagem da computação gráfica. Toda transformação (translação, rotação, escala) é uma matriz.

> 💡 **Iluminação**: Modelos como Phong são simplificações da realidade. Entenda suas limitações e quando usar cada um.

> 🖨️ **CAD**: Ferramentas CAD são essenciais na engenharia moderna. Dedique tempo para dominar pelo menos um software.

> 🥽 **VR/AR**: Realidade virtual e aumentada são áreas em crescimento. A computação gráfica é a base dessas tecnologias.

> 🔗 **Conexões**: Esta disciplina integra conhecimentos de:
> - Programação Orientada a Objetos (implementação)
> - Álgebra Linear (transformações)
> - Geometria Analítica (modelagem)
> - Física (iluminação, animação)

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025