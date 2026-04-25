---
tags: [cybersegurança, segurança da informação, redes, engenharia, telecomunicações, optativa]
semestre: 8
area: Computacao
creditos: 4
dificuldade: alta
importancia: alta
código: TEL015
carga_horaria: 60h (4 créditos)
status: completo
pré_requisitos: [Redes Computadores, Redes Comunicacao Dados]
links: [Redes Computadores, Redes Comunicacao Dados, Optativa III]
aliases: []
keywords: [cybersegurança, segurança da informação, redes, engenharia, telecomunicações, optativa]
resumo: "Estudo dos fundamentos de cybersegurança: segurança da informação, criptografia, ameaças cibernéticas, segurança de redes, segurança de aplicações web, gestão de vulnerabilidades, resposta a incidentes e aspectos regulat"
---

# Cybersegurança

## 1. Ementa Oficial

Estudo dos fundamentos de cybersegurança: segurança da informação, criptografia, ameaças cibernéticas, segurança de redes, segurança de aplicações web, gestão de vulnerabilidades, resposta a incidentes e aspectos regulatórios de proteção de dados. Aplicações em infraestruturas de telecomunicações.

### Objetivos da Disciplina

**Objetivo Geral:**
Proporcionar ao estudante conhecimentos fundamentais de cybersegurança, capacitando-o a compreender, analisar e implementar medidas de proteção em sistemas de informação e infraestruturas de telecomunicações.

**Objetivos Específicos:**
- Compreender os princípios de segurança da informação (confidencialidade, integridade, disponibilidade)
- Conhecer técnicas de criptografia simétrica e assimétrica
- Identificar e analisar ameaças e vulnerabilidades em sistemas
- Implementar controles de segurança em redes de computadores
- Conhecer práticas de segurança em desenvolvimento de aplicações
- Entender gestão de vulnerabilidades e testes de penetração
- Conhecer metodologias de resposta a incidentes de segurança
- Entender aspectos regulatórios (LGPD, Lei Carolina Dieckmann) e compliance

---

## 2. Conteúdo Programático

### Unidade 1: Fundamentos de Segurança da Informação (10h)

#### 1.1 Princípios e Conceitos
- História da segurança da informação
- Triade CIA (Confidencialidade, Integridade, Disponibilidade)
- Outras propriedades: autenticidade, não-repúdio, auditoria
- Classificação da informação
- Gestão de riscos em segurança da informação
- Políticas, normas e procedimentos de segurança
- Governança corporativa e segurança
- ISO/IEC 27001 e 27002

#### 1.2 Ameaças e Agentes de Ameaça
- Tipos de agentes ameaçadores
  - Hackers (white hat, black hat, gray hat)
  - Script kiddies
  - Hacktivistas
  - Cybercriminosos
  - APTs (Advanced Persistent Threats)
  - Insider threats
- Motivações de ataques
- Vetores de ataque
- Superfície de ataque
- Modelagem de ameaças (Threat Modeling)

---

### Unidade 2: Criptografia (12h)

#### 2.1 Fundamentos de Criptografia
- História da criptografia
- Terminologia básica
  - Plain text, cipher text, key
  - Cifra, decifra
  - Criptoanálise
- Criptografia simétrica (chave secreta)
  - DES, 3DES
  - AES (Advanced Encryption Standard)
  - Modos de operação (ECB, CBC, CTR, GCM)
- Criptografia assimétrica (chave pública)
  - RSA
  - Diffie-Hellman
  - Curvas elípticas (ECC)
  - ElGamal

#### 2.2 Funções Hash e Assinatura Digital
- Funções hash criptográficas
  - MD5 (obsoleto)
  - SHA-1 (obsoleto)
  - SHA-256, SHA-3
  - Blake2
- Propriedades das funções hash
- Ataques de colisão
- HMAC (Hash-based Message Authentication Code)
- Assinatura digital
  - Como funciona
  - Certificados digitais
  - PKI (Public Key Infrastructure)
  - CA (Certificate Authority)
  - SSL/TLS

#### 2.3 Protocolos Criptográficos
- SSL/TLS e HTTPS
- IPSec
- SSH (Secure Shell)
- S/MIME e PGP
- VPNs e protocolos de tunelamento
- Perfect Forward Secrecy (PFS)
- Criptografia pós-quântica (introdução)

---

### Unidade 3: Segurança de Redes (12h)

#### 3.1 Segurança em Camadas de Rede
- Segurança na camada física
- Segurança na camada de enlace (802.1X)
- Segurança na camada de rede (IPSec)
- Segurança na camada de transporte (TLS/SSL)
- Segurança na camada de aplicação

#### 3.2 Firewalls e IDS/IPS
- Tipos de firewalls
  - Packet filtering
  - Stateful inspection
  - Application layer (proxy)
  - Next-Generation Firewall (NGFW)
  - WAF (Web Application Firewall)
- Arquiteturas de firewall
- IDS (Intrusion Detection System)
  - Baseado em assinatura
  - Baseado em anomalia
- IPS (Intrusion Prevention System)
- SIEM (Security Information and Event Management)
- Honeypots e honeynets

#### 3.3 Segurança em Redes Sem Fio
- WEP e suas vulnerabilidades
- WPA/WPA2 (TKIP, AES-CCMP)
- WPA3 (SAE)
- Rogue access points
- War driving e war chalking
- Bluetooth security
- ZigBee security
- Segurança em redes 5G

#### 3.4 Segurança em Redes de Telecomunicações
- Proteção de infraestrutura crítica
- SS7 e SIGTRAN security
- Diameter protocol security
- 5G security architecture
- Network slicing security
- SDN/NFV security
- Proteção contra DDoS em backbone
- Segurança em DNS

---

### Unidade 4: Ameaças e Ataques Cibernéticos (10h)

#### 4.1 Malware
- Vírus
- Worms
- Trojans
- Ransomware
- Spyware e adware
- Rootkits
- Botnets
- Fileless malware
- Técnicas de evasão

#### 4.2 Ataques a Aplicações Web
- OWASP Top 10
  - Injection (SQL, NoSQL, OS command, LDAP)
  - Broken authentication
  - Sensitive data exposure
  - XML External Entities (XXE)
  - Broken access control
  - Security misconfiguration
  - Cross-Site Scripting (XSS)
  - Insecure deserialization
  - Using components with known vulnerabilities
  - Insufficient logging and monitoring
- CSRF (Cross-Site Request Forgery)
- Clickjacking
- Session hijacking
- Cookie poisoning

#### 4.3 Ataques de Engenharia Social
- Phishing
- Spear phishing
- Whaling
- Vishing e smishing
- Pretexting
- Baiting
- Quid pro quo
- Tailgating
- Dumpster diving

#### 4.4 Ataques à Infraestrutura de Rede
- DoS e DDoS
- Man-in-the-middle (MITM)
- ARP spoofing
- DNS spoofing
- BGP hijacking
- VLAN hopping
- Port scanning
- Brute force
- Password attacks

---

### Unidade 5: Segurança de Aplicações e Desenvolvimento Seguro (10h)

#### 5.1 Secure Software Development
- SDL (Security Development Lifecycle)
- DevSecOps
- SAST (Static Application Security Testing)
- DAST (Dynamic Application Security Testing)
- IAST (Interactive Application Security Testing)
- SCA (Software Composition Analysis)
- Code review focado em segurança
- Segurança em APIs

#### 5.2 Autenticação e Autorização
- Autenticação multifator (MFA)
- SSO (Single Sign-On)
- OAuth 2.0 e OpenID Connect
- SAML
- Kerberos
- LDAP e Active Directory
- Controle de acesso baseado em papéis (RBAC)
- Controle de acesso baseado em atributos (ABAC)
- Zero Trust Architecture

#### 5.3 Hardening e Segurança de Sistemas
- Hardening de servidores (Windows, Linux)
- Hardening de aplicações web
- Hardening de bancos de dados
- Hardening de containers
- Hardening de cloud
- Patch management
- Configuração segura
- Remediação de vulnerabilidades

---

### Unidade 6: Gestão de Segurança e Resposta a Incidentes (6h)

#### 6.1 Gestão de Vulnerabilidades
- Identificação de vulnerabilidades
- Scanning de vulnerabilidades
- Classificação de severidade (CVSS)
- Priorização de correções
- Bug bounty programs
- Gestão de patches

#### 6.2 Testes de Penetração (Pentest)
- Metodologias: PTES, OWASP Testing Guide
- Fases do pentest
  - Reconhecimento
  - Scanning
  - Enumeração
  - Exploração
  - Pós-exploração
  - Relatório
- Tipos de pentest
  - Black box
  - White box
  - Gray box

#### 6.3 Resposta a Incidentes
- CSIRT (Computer Security Incident Response Team)
- Frameworks de resposta a incidentes
  - NIST SP 800-61
  - SANS Incident Handler's Handbook
- Fases da resposta a incidentes
  - Preparação
  - Identificação
  - Contenção
  - Erradicação
  - Recuperação
  - Lições aprendidas
- Forense digital (conceitos)
- Comunicação de incidentes
- Notificação de breaches

#### 6.4 Aspectos Legais e Regulatórios
- LGPD (Lei Geral de Proteção de Dados)
- Lei Carolina Dieckmann (Lei 12.737/2012)
- Marco Civil da Internet
- ISO/IEC 27001
- PCI-DSS (para dados de cartão)
- Frameworks de compliance (NIST, CIS Controls)
- Aspectos criminais de crimes cibernéticos

---

## 3. Aplicações em Engenharia de Telecomunicações

### 3.1 Infraestrutura de Rede
- **Proteção de backbone**: DDoS mitigation, BGP security
- **Segurança de DNS**: DNSSEC, proteção contra hijacking
- **Segurança de roteadores e switches**: Hardening, ACLs
- **SDN/NFV security**: Isolamento, políticas de segurança
- **5G security**: Network slicing security, MEC security

### 3.2 Sistemas de Suporte (OSS/BSS)
- **Proteção de dados de clientes**: LGPD compliance
- **Segurança de billing**: Prevenção de fraude
- **CRM security**: Proteção de PII (Personally Identifiable Information)
- **APIs de telecom**: Segurança em APIs de provisionamento
- **Fraud management**: Detecção de uso fraudulento

### 3.3 Comunicações
- **VoIP security**: SRTP, SIPS, prevenção de toll fraud
- **Messaging security**: SMS fraud, SS7 attacks
- **Satellite communications**: Jamming, spoofing protection
- **IoT security**: Dispositivos conectados em redes de telecom
- **M2M security**: Comunicação máquina-a-máquina segura

### 3.4 Data Centers e Cloud
- **Physical security**: Controle de acesso, CCTV
- **Network security**: Segmentação, microsegmentação
- **Cloud security**: Responsabilidade compartilhada
- **Virtualization security**: Hypervisor security, VM isolation
- **Container security**: Kubernetes security, image scanning

### 3.5 Serviços de Segurança
- **MSS (Managed Security Services)**: Serviços gerenciados de segurança
- **SOC (Security Operations Center)**: Operações de segurança
- **Threat intelligence**: Inteligência de ameaças
- **Incident response**: Resposta a incidentes terceirizada
- **Security consulting**: Consultoria em segurança

---

## 4. Metodologia

### 4.1 Estratégias de Ensino
- **Aulas teóricas**: Conceitos de segurança da informação
- **Laboratórios práticos**: Configuração de ferramentas de segurança
- **CTF (Capture The Flag)**: Exercícios práticos de pentest
- **Análise de casos**: Incidentes reais e lições aprendidas
- **Simulações**: Resposta a incidentes
- **Seminários**: Tendências em cybersegurança
- **Workshops**: Ferramentas de segurança (Wireshark, Nmap, Metasploit)

### 4.2 Recursos Didáticos
- Quadro e projetor multimídia
- Laboratório de segurança (isolated network)
- Máquinas virtuais para práticas
- Ferramentas de segurança (Kali Linux, Wireshark, Nmap)
- Plataformas de CTF (TryHackMe, Hack The Box, PicoCTF)
- Documentação de vulnerabilidades (CVE, NVD)
- Material didático digital
- Simuladores de ataques

### 4.3 Avaliação

**Instrumentos:**
- Provas teórico-práticas (2 avaliações) - 40%
- Laboratórios práticos e desafios CTF - 30%
- Projeto de análise de vulnerabilidades - 20%
- Participação e seminários - 10%

**Critérios:**
- Compreensão dos princípios de segurança da informação
- Conhecimento de técnicas criptográficas
- Capacidade de identificar vulnerabilidades
- Habilidade em configurar controles de segurança
- Entendimento de OWASP Top 10 e segurança de aplicações
- Conhecimento de metodologias de resposta a incidentes
- Entendimento de aspectos regulatórios

---

## 5. Cronograma Sugerido (15 semanas)

| Semana | Conteúdo |
|--------|----------|
| 1 | Introdução à Cybersegurança. Triade CIA. Governança |
| 2 | Gestão de riscos. ISO/IEC 27001. Políticas de segurança |
| 3 | Criptografia simétrica. DES, AES, modos de operação |
| 4 | Criptografia assimétrica. RSA, ECC. Hash e assinatura digital |
| 5 | **1ª Avaliação** |
| 6 | SSL/TLS, VPNs. PKI e certificados digitais |
| 7 | Firewalls. IDS/IPS. SIEM |
| 8 | Segurança em redes sem fio. WPA2, WPA3 |
| 9 | Segurança em redes de telecom. 5G security, SS7 |
| 10 | **2ª Avaliação** |
| 11 | Malware. OWASP Top 10. Ataques a aplicações web |
| 12 | Engenharia social. Phishing. Ataques à infraestrutura |
| 13 | Desenvolvimento seguro. DevSecOps. Autenticação |
| 14 | Gestão de vulnerabilidades. Pentest. Resposta a incidentes |
| 15 | Aspectos legais. LGPD. Compliance. Revisão. **Prova Final** |

---

## 6. Bibliografia

### Bibliografia Básica
1. STALLINGS, W.; BROWN, L. **Computer Security: Principles and Practice**. 4. ed. Pearson, 2018.
2. ANDERSON, R. **Security Engineering: A Guide to Building Dependable Distributed Systems**. 3. ed. Wiley, 2020.
3. SCHNEIER, B. **Applied Cryptography: Protocols, Algorithms, and Source Code in C**. 2. ed. Wiley, 2015.

### Bibliografia Complementar
4. SCARFONE, K.; MELL, P. **Guide to Intrusion Detection and Prevention Systems (IDPS)**. NIST, 2007.
5. WEIDMAN, G. **Penetration Testing: A Hands-On Introduction to Hacking**. No Starch Press, 2014.
6. NORTHWOOD, C. **The Web Application Hacker's Handbook**. 2. ed. Wiley, 2011.
7. TIPTON, H. F.; KRAUSE, M. **Information Security Management Handbook**. 6. ed. CRC Press, 2016.
8. SIKORSKI, M.; HONIG, A. **Practical Malware Analysis: The Hands-On Guide to Dissecting Malicious Software**. No Starch Press, 2012.

### Recursos Online
- [OWASP](https://owasp.org/) - Open Web Application Security Project
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework) - Framework de cibersegurança
- [CVE Details](https://www.cvedetails.com/) - Base de dados de vulnerabilidades
- [TryHackMe](https://tryhackme.com/) - Plataforma de aprendizado de segurança
- [Hack The Box](https://www.hackthebox.com/) - Laboratórios de pentest
- [SANS Internet Storm Center](https://isc.sans.edu/) - Monitoramento de ameaças
- [LGPD Brasil](https://www.lgpdbrasil.com.br/) - Recursos sobre LGPD

---

## 7. Resultados de Aprendizagem (RA)

Ao final da disciplina, o estudante deve ser capaz de:

**RA1** - Compreender os princípios fundamentais de segurança da informação e gestão de riscos

**RA2** - Aplicar técnicas de criptografia para proteção de dados e comunicações

**RA3** - Configurar e gerenciar controles de segurança em redes de computadores

**RA4** - Identificar e mitigar vulnerabilidades em aplicações web segundo OWASP Top 10

**RA5** - Implementar práticas de desenvolvimento seguro e DevSecOps

**RA6** - Realizar análises de vulnerabilidades e testes básicos de penetração

**RA7** - Aplicar metodologias de resposta a incidentes de segurança

**RA8** - Entender e aplicar requisitos regulatórios de proteção de dados (LGPD) e compliance

---

## 8. Notas para o Estudante

> 💡 **Dica de Estudo**: Cybersegurança é um campo vasto e em constante evolução. Mantenha-se atualizado com blogs, CVEs e comunidades de segurança!

> 🔐 **CIA Triad**: Toda decisão de segurança deve considerar Confidencialidade, Integridade e Disponibilidade. Nunca sacrifice segurança por conveniência!

> 🔑 **Criptografia**: Não invente seu próprio algoritmo criptográfico. Use bibliotecas estabelecidas (OpenSSL, libsodium). AES-256-GCM é seu amigo para encriptação simétrica.

> 🌐 **OWASP Top 10**: Se você só aprender uma coisa sobre segurança de aplicações, aprenda a prevenir SQL Injection e XSS. São os ataques mais comuns!

> 🕵️ **Engenharia Social**: O elo mais fraco da segurança é o humano. Phishing continua sendo o vetor de ataque #1. Educação é crucial!

> 🛡️ **Defesa em Profundidade**: Nunca confie em uma única camada de proteção. Múltiplas camadas (firewall, IDS, criptografia, hardening) são essenciais.

> 🚨 **Resposta a Incidentes**: Não é questão de "se", mas de "quando". Tenha um plano antes do incidente acontecer. Documente tudo!

> 🔗 **Conexões**: Esta disciplina integra conhecimentos de:
> - Redes de Computadores (protocolos, arquiteturas)
> - Sistemas Operacionais (hardening, logs)
> - Programação (desenvolvimento seguro)
> - Telecomunicações (infraestrutura crítica, 5G security)

---

**Professor Responsável:** [A definir]  
**Semestre:** 2024/1  
**Última atualização:** Abril/2025