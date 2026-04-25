---
tags: [computação, microprocessadores, arquitetura, assembly, embedded]
semestre: 6
area: Computação
creditos: 4
dificuldade: alta
importancia: alta
status: completo
links: [Sistemas Digitais, Algoritmos II, Eletronica Aplicada]
aliases: []
keywords: [computação, microprocessadores, arquitetura, assembly, embedded]
---

# Microprocessadores

## 1. Ementa Expandida
Estudo da arquitetura, programação e interfaceamento de microprocessadores e microcontroladores. Desenvolvimento de aplicações embarcadas, sistemas de tempo real e comunicação com periféricos para sistemas de telecomunicações.

## 2. Blocos Teóricos

### 2.1 Arquitetura de Microprocessadores
- Organização básica: CPU, memória, I/O
- Modelo de von Neumann vs Harvard
- Arquitetura RISC vs CISC
- Ciclo de instrução: busca, decodificação, execução
- Pipeline e superescalaridade
- Hierarquia de memória: cache, RAM, ROM
- Barramentos: dados, endereços, controle
- Interrupções e exceções

### 2.2 Conjunto de Instruções
- Linguagem Assembly: sintaxe e diretivas
- Modos de endereçamento
- Instruções aritméticas e lógicas
- Instruções de transferência de dados
- Instruções de controle de fluxo
- Instruções de manipulação de bits
- Macros e sub-rotinas
- Chamadas de sistema

### 2.3 Microcontroladores
- Arquitetura típica de microcontroladores
- Periféricos integrados: GPIO, timers, ADC/DAC
- Comunicação serial: UART, SPI, I2C
- PWM e controle de motores
- Watchdog e low-power modes
- Famílias populares: ARM Cortex-M, AVR, PIC, ESP32
- Ferramentas de desenvolvimento: IDEs, debuggers

### 2.4 Sistemas Embarcados
- Sistemas de tempo real (RTS)
- Sistemas operacionais embarcados: FreeRTOS, Zephyr
- Scheduling: preemptivo, cooperativo
- Sincronização: semáforos, mutexes, filas
- Memória em sistemas embarcados
- Bootloaders e firmware
- Programação bare-metal

### 2.5 Interfaceamento
- Interfaces paralelas e seriais
- Conversores A/D e D/A
- Sensores e atuadores
- Displays: LCD, OLED, touch
- Memória externa: EEPROM, Flash, SD
- Comunicação sem fio: Bluetooth, Wi-Fi, LoRa
- Protocolos de comunicação industrial

## 3. Aplicações em Telecom

### 3.1 Sistemas de Comunicação Embarcados
- Módulos de comunicação celular (2G/3G/4G)
- Módulos Wi-Fi e Bluetooth
- Rádios definidos por software (SDR)
- Sistemas IoT e M2M
- Gateways de comunicação

### 3.2 Processamento de Sinais em Tempo Real
- Aquisição de dados de RF
- Processamento digital de sinais embarcado
- Filtragem em tempo real
- Modulação/demodulação digital
- Protocolos de áudio/voz

### 3.3 Controle de Equipamentos
- Controladores de antenas
- Sistemas de alarme e monitoramento
- Smart meters e telemetria
- Repetidores e amplificadores
- Sistemas de teste e medição

## 4. Prática/Laboratório
- Experimento 1: Introdução ao Assembly
- Experimento 2: Programação de GPIO e timers
- Experimento 3: Interrupções e comunicação serial
- Experimento 4: Conversores A/D e sensores
- Experimento 5: Comunicação I2C/SPI
- Experimento 6: PWM e controle
- Experimento 7: Sistema embarcado com RTOS
- Experimento 8: Projeto: módulo de comunicação

## 5. Bibliografia

### Bibliografia Básica
- PATTERSON, D. A.; HENNESSY, J. L. **Organização e Projeto de Computadores**. 5. ed. Elsevier, 2017.
- STALLINGS, W. **Arquitetura e Organização de Computadores**. 10. ed. Pearson, 2017.
- BARRY, R. **Using the FreeRTOS Real Time Kernel**. Real Time Engineers, 2016.

### Bibliografia Complementar
- ARM. **Cortex-M4 Technical Reference Manual**. ARM Limited, 2023.
- VALVANO, J. W. **Embedded Systems: Introduction to ARM Cortex-M Microcontrollers**. 5. ed. CreateSpace, 2019.
- BARR, M. **Programming Embedded Systems in C and C++**. O'Reilly, 1999.

## 6. Outputs Esperados
- Programação em Assembly e C embarcado
- Conhecimento de arquitetura de microprocessadores
- Desenvolvimento de aplicações embarcadas
- Interfaceamento com periféricos
- Noções de sistemas de tempo real
- Base para sistemas IoT e comunicação
- Preparação para projeto de hardware embarcado