---
tags: [indice, mapa, engenharia, telecomunicacoes, dashboard]
aliases: [HOME, MAPA, INDICE]
---

# Engenharia de Telecomunicações — Vault de Estudos

> Currículo completo do curso de Engenharia de Telecomunicações · UFSJ · 10 semestres

---

## Dashboard Dinâmico

> Requer plugin **Dataview** instalado e ativado.

```dataview
TABLE sem AS "Sem", area AS "Área", creditos AS "Cr", dificuldade AS "Dif", importancia AS "Imp", status AS "Status"
FROM ""
WHERE semestre >= 1
SORT semestre ASC, area ASC
```

---

## Progresso por Área

```dataview
TABLE length(rows) AS "Disciplinas", sum(rows.creditos) AS "Créditos"
FROM ""
WHERE area != null AND file.name != "!ÍNDICE"
GROUP BY area
SORT length(rows) DESC
```

---

## Estrutura Curricular por Semestre

### 1º Semestre — Fundamentos (7 disciplinas · 24 créditos)
(Syllabus detalhado em [[Syllabus/01_Matematica/Syllabus_Sem1]])

### 2º Semestre — Física e Cálculo (6 disciplinas · 20 créditos)

| Disciplina | Área | Cr | Dif | Imp |
|---|---|---|---|---|
| [[Calculo_Diferencial_Integral_II]] | Matemática | 6 | alta | crítica |
| [[Fenomenos_Mecanicos]] | Física | 4 | média | alta |
| [[Algoritmos_II]] | Computação | 4 | alta | alta |
| [[Lab_Fenomenos_Mecanicos]] | Física | 2 | média | alta |
| [[Expressao_Grafica]] | Engenharia | 2 | baixa | média |
| [[Ciencia_Tecnologia_Sociedade]] | Humanidades | 2 | baixa | baixa |

### 3º Semestre — Cálculo Avançado e Física (6 disciplinas · 24 créditos)

| Disciplina | Área | Cr | Dif | Imp |
|---|---|---|---|---|
| [[Calculo_III]] | Matemática | 6 | alta | crítica |
| [[Equacoes_Diferenciais_A]] | Matemática | 4 | alta | crítica |
| [[Estatistica_Probabilidade]] | Matemática | 4 | média | alta |
| [[Fenomenos_Termicos_Fluidos]] | Física | 4 | média | alta |
| [[Materiais_Eletricos_Magneticos]] | Elétrica | 4 | média | alta |
| [[Lab_Fenomenos_Termicos_Fluidos]] | Física | 2 | média | média |

### 4º Semestre — Equações Diferenciais e Circuitos (6 disciplinas · 24 créditos)

| Disciplina | Área | Cr | Dif | Imp |
|---|---|---|---|---|
| [[Circuitos_Eletricos_I]] | Elétrica | 6 | alta | crítica |
| [[Equacoes_Diferenciais_B]] | Matemática | 4 | alta | crítica |
| [[Fenomenos_Eletromagneticos]] | Física | 4 | alta | crítica |
| [[Sistemas_Digitais]] | Computação | 4 | alta | alta |
| [[Calculo_Numerico]] | Matemática | 4 | média | alta |
| [[Lab_Fenomenos_Eletromagneticos]] | Física | 2 | média | alta |

### 5º Semestre — Eletromagnetismo e Eletrônica (6 disciplinas · 28 créditos)

| Disciplina                      | Área        | Cr  | Dif   | Imp     |
| ------------------------------- | ----------- | --- | ----- | ------- |
| [[Circuitos_Eletricos_II]]      | Elétrica    | 6   | alta  | crítica |
| [[Eletronica_I]]                | Elétrica    | 6   | alta  | crítica |
| [[Analise_Sinais_Sistemas]]     | Telecom     | 6   | alta  | crítica |
| [[Eletromagnetismo]]            | Física      | 4   | alta  | crítica |
| [[Metodos_Matematicos]]         | Matemática  | 4   | alta  | alta    |
| [[Individuos_Grupos_Sociedade]] | Humanidades | 2   | baixa | média   |

### 6º Semestre — Telecomunicações Básicas (6 disciplinas · 28 créditos)

| Disciplina | Área | Cr | Dif | Imp |
|---|---|---|---|---|
| [[Eletronica_II]] | Elétrica | 6 | alta | crítica |
| [[Principios_Comunicacoes]] | Telecom | 6 | alta | crítica |
| [[Propagacao]] | Telecom | 4 | alta | crítica |
| [[Processamento_Digital_Sinais]] | Telecom | 4 | alta | crítica |
| [[Microprocessadores]] | Computação | 4 | alta | alta |
| [[Medidas_Eletricas]] | Elétrica | 4 | média | alta |

### 7º Semestre — Telecomunicações Avançadas (6 disciplinas · 24 créditos)

| Disciplina | Área | Cr | Dif | Imp |
|---|---|---|---|---|
| [[Antenas]] | Telecom | 6 | alta | crítica |
| [[Comunicacoes_Digitais]] | Telecom | 4 | alta | crítica |
| [[Redes_Comunicacao_Dados]] | Telecom | 4 | alta | crítica |
| [[Eletronica_Aplicada]] | Elétrica | 4 | alta | alta |
| [[Teoria_Informacao_Codificacao]] | Telecom | 4 | alta | alta |
| [[Meio_Ambiente_Sustentabilidade]] | Humanidades | 2 | baixa | média |

### 8º Semestre — Sistemas de Comunicação (6 disciplinas · 22 créditos)

| Disciplina | Área | Cr | Dif | Imp |
|---|---|---|---|---|
| [[Telefonia]] | Telecom | 4 | alta | crítica |
| [[Redes_Computadores]] | Computação | 4 | alta | crítica |
| [[Microondas]] | Telecom | 4 | alta | alta |
| [[Processos_Estocasticos]] | Matemática | 4 | alta | alta |
| [[Radiodifusao_Radioenlace]] | Telecom | 4 | média | alta |
| [[Economia_Administracao]] | Humanidades | 2 | média | média |

### 9º Semestre — Comunicações e TCC I (6 disciplinas · 26 créditos)

| Disciplina | Área | Cr | Dif | Imp |
|---|---|---|---|---|
| [[Telefonia_Celular]] | Telecom | 6 | alta | crítica |
| [[Comunicacoes_Opticas]] | Telecom | 4 | alta | crítica |
| [[Redes_Sem_Fio]] | Telecom | 4 | alta | crítica |
| [[TCC_I]] | Projeto | 4 | alta | crítica |
| [[Processamento_Audio_Video]] | Telecom | 4 | alta | alta |
| [[Estagio]] | Projeto | 4 | média | crítica |

### 10º Semestre — TCC II e Optativas (5 disciplinas · 22 créditos)

| Disciplina | Área | Cr | Dif | Imp |
|---|---|---|---|---|
| [[TCC_II]] | Projeto | 6 | alta | crítica |
| [[Optativa_I]] | Optativas | 4 | média | média |
| [[Optativa_II]] | Optativas | 4 | média | média |
| [[Optativa_III]] | Optativas | 4 | média | média |
| [[Optativa_IV]] | Optativas | 4 | média | média |

---

## Notas Extras no Vault

> Disciplinas de aprofundamento e conteúdo complementar, fora da grade obrigatória.

| Disciplina | Área | Sem | Observação |
|---|---|---|---|
| [[Fenomenos_Ondulatorios]] | Física | 3 | Complemento de Fenômenos Mecânicos |
| [[Lab_Fenomenos_Ondulatorios]] | Física | 3 | Lab de Fenômenos Ondulatórios |
| [[Cyberseguranca]] | Computação | 8 | Optativa avançada |
| [[Filosofia_Ciencia]] | Humanidades | 1 | Conteúdo complementar |
| [[Fundamentos_Fisica_Moderna]] | Física | 6 | Aprofundamento |
| [[Programacao_Orientada_Objetos]] | Computação | 3 | Complemento de Algoritmos |
| [[Projeto_Computacao_Grafica]] | Computação | 8 | Optativa |
| [[Optativa_V]] | Optativas | 10 | Optativa extra |
| [[Optativa_VI]] | Optativas | 10 | Optativa extra |
| [[Optativa_VII]] | Optativas | 10 | Optativa extra |

---

## Dependências Principais

```
Cálculo I → Cálculo II → Cálculo III → EDO A → EDO B → Métodos Matemáticos
                 ↓                                  ↓
           Fenômenos Mecânicos          Análise de Sinais e Sistemas
                                               ↓          ↓
                                             PDS    Princípios de Comunicações
                                                          ↓
                                              Comunicações Digitais → TCC

Fenômenos Eletromagnéticos → Eletromagnetismo → Propagação → Antenas
                                                                  ↓
                                                        Telefonia Celular

Algoritmos I → Algoritmos II → Sistemas Digitais → Microprocessadores
                                                          ↓
                                                  Redes de Computadores
```

---

## Como Usar Este Vault

| Ação | Atalho |
|---|---|
| Buscar qualquer disciplina | `Ctrl+O` |
| Pesquisa em todo o vault | `Ctrl+Shift+F` |
| Ver grafo de conexões | `Ctrl+G` |
| Abrir painel de backlinks | `Ctrl+Alt+B` |
| Criar nota do template | `Alt+N` (Templater) |

> **Dashboard interativo:** Abra `dashboard-app/` e execute `npm run dev` para a interface web com filtros e visualização matricial.

---

*Última atualização: 24/04/2026 · 60 disciplinas obrigatórias · 10 extras*


---

## 🧠 Hubs de Navegação

- [[Hub RF e Propagacao|📡 RF & Propagação]]
- [[Hub Redes e Comunicacoes|🌐 Redes & Comunicações]]
- [[Hub Sinais e Sistemas|〜 Sinais & Sistemas]]
- [[Hub Cyberseguranca|🔐 Cybersegurança]]
- [[Hub Matematica|∑ Matemática]]

---

## 📐 Conceitos Canônicos

- [[Transformada de Fourier]]
- [[Transformada de Laplace]]
- [[Modulacao|Modulação]]
- [[Equacoes de Maxwell|Equações de Maxwell]]
- [[Teorema de Shannon]]
- [[Modelo TCP-IP]]
