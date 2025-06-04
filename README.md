# 🚦 Semáforo Inteligente com Arduino

<p align="center">
  <img src="https://img.shields.io/badge/status-concluído-black?style=for-the-badge" alt="Status do Projeto">
  <img src="https://img.shields.io/badge/vers%C3%A3o-final-blue?style=for-the-badge" alt="Versão">
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

Este projeto tem como objetivo o desenvolvimento de um **semáforo inteligente** utilizando a plataforma Arduino. Iniciamos com conceitos básicos de controle de LEDs e evoluímos até simular um cruzamento urbano realista, incorporando sensores infravermelhos, botões para pedestres e uma maquete física para testes.

---

## 🔧 Protótipos Desenvolvidos

### Protótipo 1: Semáforo Básico

🔗 [Acessar no Tinkercad](https://www.tinkercad.com/things/crLNLab5RRq-trabalha01)

**Objetivo:** Compreender o funcionamento de LEDs com Arduino e a lógica básica de semáforo.

```plaintext
1. LED verde acende por 5 segundos
2. LED amarelo acende por 2 segundos
3. LED vermelho acende por 5 segundos
4. O ciclo se repete continuamente
```

---

### Protótipo 2: Botão para Pedestres

🔗 [Acessar no Tinkercad](https://www.tinkercad.com/things/fGDRABPrAXn-trabalho02)

**Novidade:** Inclusão de um botão que permite aos pedestres solicitar a travessia.

**Funcionamento:**

- O botão pode ser pressionado a qualquer momento.
- O pedido é armazenado até o momento seguro de travessia.
- O semáforo de veículos fica vermelho e o LED verde para pedestres acende.

---

### Protótipo 3: Sensor Infravermelho

🔗 [Acessar no Tinkercad](https://www.tinkercad.com/things/lXt8ejKZsI6-trabalho03)

**Novidade:** Inclusão de sensor IR para detecção de veículos.

**Funcionamento:**

- Detecta presença de carros.
- Se não houver veículos, o tempo do sinal verde é reduzido.
- Em caso de tráfego, o sinal verde se estende.

---

### Sprint 3: Cruzamento Inteligente com Maquete Física

🔗 [Acessar no Tinkercad](https://www.tinkercad.com/things/4wrWFSQffOk-sprint3)

**Destaques:**

- Código reorganizado e modularizado.
- Divisão do sistema em **dois Arduinos Uno**, otimizando o número de portas.
- Construção de **maquete física funcional** para testes realistas.

**Funcionalidades:**

- Controle de semáforos para duas vias.
- Botões de travessia para pedestres.
- Lógica de sincronização inteligente entre sinais.
- Ajuste automático de tempos com base no tráfego.

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

## ✅ Conclusão

Durante a jornada de desenvolvimento, partimos de um simples ciclo de LEDs até um sistema inteligente de controle de tráfego, que:

- Coordena veículos e pedestres de forma segura.
- Ajusta dinamicamente os tempos com base no tráfego.
- Integra sensores e botões de forma eficiente.
- Funciona plenamente em uma maquete física.

Este projeto exemplifica como **hardware e software** podem se unir para resolver desafios reais de mobilidade urbana.

---
