# 🚦 Semáforo Inteligente com Arduino

<p align="center">
  <img src="https://img.shields.io/badge/status-em%20desenvolvimento-brightgreen?style=for-the-badge" alt="Status do Projeto">
  <img src="https://img.shields.io/badge/vers%C3%A3o-sprint%203-blue?style=for-the-badge" alt="Versão">
</p>

## 📌 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Protótipos Desenvolvidos](#-protótipos-desenvolvidos)
  - [Protótipo 1: Semáforo Básico](#protótipo-1-semáforo-básico)
  - [Protótipo 2: Botão para Pedestres](#protótipo-2-botão-para-pedestres)
  - [Protótipo 3: Sensor Infravermelho](#protótipo-3-sensor-infravermelho)
  - [Sprint 3: Cruzamento Inteligente com Maquete Física](#sprint-3-cruzamento-inteligente-com-maquete-física)
- [Componentes Utilizados](#-componentes-utilizados)
- [Maquete Física](#-maquete-física)
- [Conclusão](#-conclusão)
- [Como Contribuir](#-como-contribuir)

---

## 🧠 Sobre o Projeto

Este projeto visa desenvolver um **semáforo inteligente** utilizando a plataforma Arduino. Iniciamos com conceitos básicos de controle de LEDs e evoluímos para a simulação de um cruzamento urbano realista, incorporando sensores infravermelhos, botões para pedestres e uma maquete física para testes práticos.

---

## 🔧 Protótipos Desenvolvidos

### Protótipo 1: Semáforo Básico

🔗 [Acessar no Tinkercad](https://www.tinkercad.com/things/crLNLab5RRq-trabalha01)

**Objetivo:** Compreender a conexão de LEDs ao Arduino e programar a sequência de sinais.

**Funcionamento:**

```plaintext
1. LED verde acende por 5 segundos
2. LED amarelo acende por 2 segundos
3. LED vermelho acende por 5 segundos
4. O ciclo se repete continuamente
```

---

### Protótipo 2: Botão para Pedestres

🔗 [Acessar no Tinkercad](https://www.tinkercad.com/things/fGDRABPrAXn-trabalho02)

**Novidade:** Implementação de um botão que permite aos pedestres solicitar a travessia.

**Funcionamento:**

- O botão pode ser pressionado a qualquer momento.
- O sistema armazena o pedido e aguarda o momento seguro para ativar o semáforo dos pedestres.
- O semáforo de veículos fica vermelho e o LED verde para pedestres acende, permitindo a travessia.

---

### Protótipo 3: Sensor Infravermelho

🔗 [Acessar no Tinkercad](https://www.tinkercad.com/things/lXt8ejKZsI6-trabalho03)

**Novidade:** Inclusão de sensor infravermelho (IR) para detectar a presença de veículos.

**Funcionamento:**

- O sensor monitora a presença de carros na via.
- Se não há veículos, o tempo do sinal verde é reduzido.
- Se houver tráfego intenso, o sinal verde permanece por mais tempo.

---

### Sprint 3: Cruzamento Inteligente com Maquete Física

🔗 [Acessar no Tinkercad](https://www.tinkercad.com/things/4wrWFSQffOk-sprint3)

**Novidades:**

- **Melhoria no código:** Reestruturação para torná-lo mais modular e organizado.
- **Divisão do sistema em dois Arduinos Uno:**
  - Devido à limitação de entradas e saídas em um único Arduino.
  - Facilitou o manuseio e a organização dos cabos.
- **Construção de uma maquete física:**
  - Criamos um modelo realista para testar os componentes e o comportamento do sistema na prática.

**Funcionalidades Integradas:**

- Controle de semáforo para duas vias independentes.
- Botões para pedestres com controle de travessia segura.
- Sensores IR para detectar presença de veículos.
- Lógica de sincronização para evitar conflitos entre os sinais.
- Ajuste dinâmico de tempos baseado no tráfego.

---

## 🧩 Componentes Utilizados

| Quantidade | Componente                        |
|------------|-----------------------------------|
| 4          | LEDs Vermelhos (Veículos)         |
| 4          | LEDs Amarelos (Veículos)          |
| 4          | LEDs Verdes (Veículos)            |
| 4          | LEDs Vermelhos (Pedestres)        |
| 4          | LEDs Verdes (Pedestres)           |
| 32         | Resistores de 220 Ω               |
| 2          | Visores de 7 segmentos            |
| 2          | Botões de pressão                 |
| 2          | Placas de ensaio (Protoboards)    |
| 2          | Placas Arduino Uno                |
| Diversos   | Fios de conexão                   |

---

## 🖼️ Maquete Física

Abaixo, uma imagem da maquete construída para testes práticos:

<p align="center">
  <img src="URL_DA_IMAGEM" alt="Maquete do Semáforo Inteligente" width="600">
</p>



---

## ✅ Conclusão

Ao longo do desenvolvimento, evoluímos de um simples ciclo de LEDs para um sistema inteligente capaz de:

- Coordenar fluxos de veículos e pedestres com segurança.
- Ajustar tempos de sinal de forma dinâmica e eficiente.
- Simular cruzamentos reais com múltiplas vias e sensores.
- Ser testado e validado em uma maquete física realista.

Este projeto demonstra, na prática, como integrar hardware (Arduino, sensores, LEDs, botões) e software (programação em C/C++) para criar soluções reais de mobilidade urbana.

---
